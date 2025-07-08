# Student Management Program

A **console-based Python application** for managing student records, grades, and class reports. This project allows users to add, view, edit, remove, and search student information, as well as generate detailed reports by class or subject.

## Features

- **Add Students**: Input new student data with validation for age, national code, and student code uniqueness.
- **View Students**: Display all or selected student information in a tabular format.
- **Edit Students**: Update any field of a student's record using code, national code, or student code as lookup.
- **Remove Students**: Delete students based on various identifiers.
- **Search**: Find students by any piece of information.
- **Reports**:
  - **Class Report**: Shows averages and statistics for a selected class (A, B, or C).
  - **Subject Report**: Provides statistics for PHP, Python, or JS scores across all classes or per class.
- **User-Friendly Menu**: Interactive menu system with input validation and clear prompts.

## Getting Started

### Prerequisites

- Python 3.x
- Windows OS (uses `os.system("cls")` for clearing the console)

## Usage

Upon running, a menu will appear with the following options:

| Option | Description                         |
|--------|-------------------------------------|
| 1/A    | Add a student                       |
| 2/Sh   | Show students                       |
| 3/R    | Remove student                      |
| 4/E    | Edit student's information          |
| 5/S    | Search student                      |
| 6/Re   | Report (Class/Subject statistics)   |
| 7/Q    | Quit                                |

Follow the prompts to enter or select data. The application validates all inputs to ensure data integrity.

## Data Structure

Each student record contains:

- Code (auto-generated)
- Name
- Last Name
- Age
- National Code (unique, 10 digits)
- Student Code (unique)
- Class (A, B, or C)
- PHP Score (0-100 or 'Not registered')
- Python Score (0-100 or 'Not registered')
- JS Score (0-100 or 'Not registered')
- Status (Active/Deactive)

## Customization

- To adapt for non-Windows systems, replace `os.system("cls")` with `os.system("clear")`.
- You can expand the student data fields or add new report types as needed.

## Author

- [ Mehrbodyhe ]

