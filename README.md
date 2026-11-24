Hostel Management System
A console-based Hostel Management System developed in C++. It provides separate portals for the warden, students, and security guard to manage hostel operations such as student records, room allocation, payments, complaints, leave requests, visitors, and gate entries.
Features
Warden Portal
- Add, view, search, and manage student records.
- Allocate rooms according to student eligibility and room availability.
- Manage room bookings, deposits, rent, balances, and payment records.
- Maintain a room waiting list.
- View and manage student complaints according to priority.
- Review and process leave requests.
- Publish hostel notices.
- View room occupancy, student information, and management reports.
Student Portal
- View personal profile and room details.
- Check payment information and outstanding balance.
- Submit complaints and check their status.
- Submit leave requests.
- View hostel notices.
Security Guard Portal
- Record student entry and exit.
- Monitor late entries and violations.
- Record visitor entries and exits.
- View relevant gate and visitor records.
Data Structures and Algorithms
The project demonstrates the use of the following concepts:
Concept	Use in the system
Arrays	Store student, room, booking, payment, visitor, leave, notice, and gate-log records
Linked-list Queue	Maintain the room waiting list in first-come, first-served order
Priority-ordered Linked List	Store complaints according to their priority
AVL Tree	Search active student records by student ID
KMP Algorithm	Search student names using partial-name matching
Merge Sort	Sort student records alphabetically
Graph (Adjacency List)	Represent room-to-student relationships and check room occupancy
Breadth-First Search (BFS)	Traverse the room-student graph
Dynamic Array	Store student indexes used by search and sorting operations
Recursion	Used in recursive operations such as tree traversal and report calculations


Technologies Used
- Language: C++
- IDE: Dev-C++
- Compiler: MinGW (included with many Dev-C++ installations)
- Interface: Console-based
Requirements
- Windows operating system
- Dev-C++ with a working MinGW compiler
- C++11 or later compiler support
The program uses conio.h for getch() and system("cls") to clear the Windows console. These are platform-specific functions, so the project is intended to run in a Windows environment with a compatible compiler.
How to Run in Dev-C++
1. Open Dev-C++.
2. Select File → Open and open the project's .cpp source file.
3. If needed, open Tools → Compiler Options and make sure the compiler supports C++11 or later.
4. Select Execute → Compile & Run (or press F11, depending on your Dev-C++ version).
5. The program will open in a console window.
If Dev-C++ reports an error related to conio.h, check that the selected compiler is the MinGW compiler bundled with or configured for Dev-C++.
Demo Login Details
Portal	Login PIN
Warden	1234
Security Guard	4321


The program also loads three sample student records at startup:
Student ID	Sample Name
1001	Ahmed Khan
1002	Ayesha Malik
1003	Bilal Ahmed


These are fictional demonstration records.
Storage and Limitations
- Records are stored in arrays and linked data structures while the program is running.
- Data is not saved permanently to a file or database. Records added during a session are lost when the program closes.
- Payment handling is simulated; no real payment is processed.
- The program uses fixed maximum capacities for several record types.
Project Purpose
This project demonstrates how data structures and algorithms can be applied to a practical management system. It organizes common hostel tasks into role-based portals and reduces the need to manage records manually.
