🏥 Advanced Patient Tracking and Analysis System v2.0
Samsun University Software Engineering 1st Year "Introduction to Programming" Course Project

This project is a comprehensive console application developed in the C programming language, based on the fundamentals of Dynamic Memory Management and File Operations (File I/O). The system (v1.0), which initially kept data only in RAM, was developed within the scope of Assignment 4 and transformed into a persistent structure (v2.0) capable of saving, reading, and logging data.

🚀 v2.0 Update (New Features)
By adding "Assignment 4" requirements on top of the "Assignment 3" requirements, the project has gained the following capabilities:

💾 Data Persistence: Data is not lost even if the program is closed.

📂 CSV Support (Traditional): Saves and restores data as comma-separated values (.csv) files. It is coded using the traditional method with fprintf and fscanf.

🌐 JSON Support (Vibe Coding): Processes data in JSON format (.json), the modern web standard. It is coded by performing string manipulation with my custom-written parser algorithm, without using any external libraries.

📝 System Logging: Program startup, shutdown, data addition/deletion, and file operations are automatically recorded in the log.txt file with a date and time stamp.

🛠️ Technical Specifications
This project includes the following computer science concepts:

Dynamic Memory Management: Heap management with malloc, realloc, and free.

Struct & Pointers: Keeping data structures in an object-oriented-like architecture.

File I/O: Use of fopen, fclose, and file modes (w, r, a).

Algorithms:

Bubble Sort: Sorting patients by health score.

Linear Search: Name and range searching.

Custom Parsing: Custom string parsing to read JSON data.

UI/UX: ASCII-based Live Dashboard and Triage (Emergency) screen.

📸 Screenshots
Live Dashboard and Main Menu
<img width="422" height="561" alt="Ekran görüntüsü 2025-12-22 224712" src="https://github.com/user-attachments/assets/58ccfba8-6d7f-49fe-97ca-d24e322e5ffb" />

Triage (Emergency) Filter
<img width="446" height="427" alt="image" src="https://github.com/user-attachments/assets/c9332859-bdfe-4f5d-a58a-c7703aa6bde9" />

JSON and CSV Outputs
Sample data files generated when the project is run:

veri.csv: Excel-compatible data storage.

veri.json: Web-compatible data storage.

log.txt: System activity log.

📥 Installation and Execution
Clone the project or download it as a zip file.

Open the main.c file in a C compiler (Dev-C++, GCC, VS Code).

Compile and run.

Create your first file record by selecting 9 or 11 from the menu.

🙏 Acknowledgements
I would like to thank my esteemed professors who guided me with their vision and taught me the Vibe Coding (Hybrid Coding with AI) methodology in this project:

Asst. Prof. Dr. Nurettin Şenyer

Lecturer İlker Gür

Developer: Utkuhan AKAR
Date: December 22, 2025
Last Edited: March 24, 2026
