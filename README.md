# Project-on-Regular-Expression
# 🎓 University Management System 

A lightweight University Management System built in Python that leverages **Regular Expressions (regex)** for input validation and string parsing. This project is a command-line application designed to manage basic university operations like student registration, course assignment, and staff management.

## 📌 Features

- ✅ Add and manage student records
- ✅ Add and manage faculty and staff information
- ✅ Assign courses to students
- ✅ Input validation using **regular expressions**:
  - Student Name
  - Date of Birth
  - Email Id
  - Mobile Numbers
  - Gender
- ✅ Simple file-based storage for persistence

## 🧠 Technologies Used

- **Python 3**
- **Regular Expressions (`re` module)**
- **File I/O** for storing records (CSV or text format)

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/university-management-system.git
   cd university-management-system
2. Run the script
   python main.py
 ## 🧪 Sample Regex Patterns Used
 - Name           :  r'^[A-Za-z ]+$'
 - Date of Birth  :  r'\d{2}-\d{2}-\d{4}'
 - Email Id       :  r'^[a-z0-9]+@gmail.com$'
 - Mobile Number  :  r'^[789]\d{9}$'
 - Gender         :  r'^Male|Female$'

 ## 📁 File Structure

university-management-system/
│
├── main.py                   # Main script
├── students.txt              # Sample student data
├── utils.py                  # Helper functions with regex validation
└── README.md                 # This file

