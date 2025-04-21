# Hospital Management System
Hospital Management System is a C++ console application designed to streamline core hospital operations such as patient admission, discharge, appointment scheduling, and billing. A well-written README is often the first entry point for users and contributors, communicating what the project does, why it’s useful, and how to get started.

All data for this system is stored in CSV files located in the data/ directory—covering patients, doctors, nurses, ambulances, and appointments—to balance human readability with ease of parsing. The source code is organized into include/ (header files) and src/ (implementations) folders, with a top-level Makefile driving the build process.

This project uses modern C++17 features and relies on a simple Makefile-based build system, offering a clean, maintainable architecture without introducing heavyweight dependencies. It follows structures outlined in popular C++ README templates and build guides to ensure clarity and ease of use.

## Project Description
Hospital Management System is a C++ console application that automates key hospital workflows, including patient admission, discharge, appointment scheduling, and billing management.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Usage](#usage)
- [Data Format](#data-format)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- Patient admission and discharge  
- Appointment scheduling  
- Billing management  
- Persistent data storage using CSV files  

## Tech Stack
- **Language:** C++17  
- **Build System:** Makefile  
- **Data Storage:** Plain-text CSV files  

## Prerequisites
- A C++17-compatible compiler (e.g., GCC 8+, Clang 5+, MSVC 19.15+) :contentReference[oaicite:4]{index=4}  
- GNU Make installed  

## Installation
**1. Clone the repository:**  
   git clone https://github.com/Vishesh-Nagar/Hospital.git  
   cd Hospital

### Directory Structure
├── build/  
├── data/  
├── docs/  
├── include/  
├── src/  
├── Makefile  
└── main.cpp  

## Usage
After building, run the application:
bash ./hospital

Follow the on-screen menu to navigate through admission, discharge, appointment, and billing features.

### Data Format
Detailed CSV schema and guidelines are provided in data/README.md to explain column definitions and storage conventions.

## Contributing
Contributions are welcome! Please submit pull requests or open issues for suggestions and bug reports. 
GitHub Docs

## License
This repository does not currently include a license. Please consider adding a LICENSE file to specify usage rights. 
GitHub Docs

## Contact
For questions or feedback, reach out at nagarvishesh16@gmail.com.
