# MediCare+
Console-based Hospital Management System in modern C++ (MediCare+): patient registration, doctor &amp; medicine management, and automated billing with file-based persistence.

# MediCare+ 🩺

A menu-driven **Hospital Management System** written in modern **C++17**.  
It streamlines patient registration, doctor allocation, medicine inventory, and transparent billing – all from a single console program. :contentReference[oaicite:2]{index=2}:contentReference[oaicite:3]{index=3}

---

## ✨ Key Features
- **Patient profiles** – create, update, and persist across sessions  
- **Doctor directory** – track specialisations & departments  
- **Appointment booking** – match patients with the right doctor  
- **Medicine catalogue** – lookup & update prices, supports STL `map` / `vector` storage  
- **Automated billing** – combines consultation fees + purchased medicines  
- **File-based persistence** – no external DB required  
- Built with classic OOP pillars: *inheritance, polymorphism, encapsulation,* and *exception handling* :contentReference[oaicite:4]{index=4}:contentReference[oaicite:5]{index=5}

---

## 🏗️ Build Instructions
> Tested on **g++ 13** and **clang++ 17** (C++17 or newer).

```bash
# Clone the repo
git clone https://github.com/<org-or-user>/MediCarePlus.git
cd MediCarePlus

# Compile
g++ -std=c++17 -Wall -Wextra -O2 -o MediCarePlus "MediCare+.cpp"

# Run
./MediCarePlus
