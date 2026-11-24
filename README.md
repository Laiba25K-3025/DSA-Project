# Hostel Management System

## Project Description
The **Hostel Management System** is a console-based C++ application that manages hostel activities through separate warden, student, and security guard portals. It handles student records, room allocation, payments, complaints, leave requests, visitor entries, and security using various data structures and algorithms.

## Features

### Warden Portal
- Add, update, search, and display student records.
- Allocate rooms to students.
- Manage room waiting lists.
- View student payment records.
- Manage student complaints.
- Review and approve leave requests.
- Publish hostel notices.
- View hostel reports and room occupancy.

### Student Portal
- View personal profile.
- Check room allocation details.
- View payment information.
- Submit complaints.
- Submit leave requests.
- View hostel notices.

### Security Guard Portal
- Record visitor entries and exits.
- View visitor records.
- Maintain student gate entry and exit logs.
- Monitor late entries and curfew records.

## Data Structures and Algorithms Used

| Data Structure / Algorithm | Application |
|---|---|
| Arrays | Store student and other records |
| Structures | Organize student and hostel data |
| Linked Lists | Manage complaints |
| Queue | Maintain room waiting lists |
| AVL Tree | Search student records using IDs |
| KMP Algorithm | Search students by partial names |
| Merge Sort | Sort student records alphabetically |
| Graph | Represent room and student relationships |
| BFS | Traverse graph relationships |
| Recursion | Tree traversal and report calculations |
| Dynamic Arrays | Manage student indexes |

## Technologies Used
- C++
- Dev-C++
- MinGW Compiler
- Standard C++ Libraries
- Windows Console

## Requirements
- Windows operating system
- Dev-C++ IDE
- MinGW C++ compiler
- C++11 or later

## How to Run the Project

1. Open Dev-C++.
2. Open the project `.cpp` file.
3. Compile the program.
4. Run the application.
5. Select a portal from the main menu.

## Demo Login Credentials

| Portal | Password / PIN |
|---|---|
| Warden | 1234 |
| Security Guard | 4321 |

### Sample Student Records

| Student ID | Student Name |
|---|---|
| 1001 | Ahmed Khan |
| 1002 | Ayesha Malik |
| 1003 | Bilal Ahmed |

## Important Notes
- The system stores records temporarily in memory.
- Data is reset when the program is closed.
- Payments are simulated and do not involve real transactions.
- The system uses fixed capacity limits for certain records.
- The `conio.h` library is used for password masking and keyboard input.
- The `system("cls")` command is used to clear the Windows console.

## Project Purpose
The purpose of this project is to demonstrate the practical implementation of Data Structures and Algorithms in a real-world hostel management scenario.
