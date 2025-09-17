# Personal Expense Tracker (Python)

A simple Python-based personal expense tracker that helps you manage and track your daily expenses. This project uses SQLite for data storage and provides a command-line interface for adding, viewing, and managing expenses.

## Features
- Add new expenses with details (amount, category, date, description)
- View all expenses
- Filter expenses by date or category
- Simple and easy-to-use CLI
- Data stored locally using SQLite

## Project Structure
```
Personal-Expense-Tracker-Python/
├── db.py                  # Database connection and operations
├── main.py                # Main application logic and CLI
├── Personal_Expense.sql   # SQL schema for initializing the database
```

## Getting Started

### Prerequisites
- Python 3.x

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/GODSROBOT/Personal-Expense-Tracker-Python.git
   cd Personal-Expense-Tracker-Python
   ```
2. (Optional) Create and activate a virtual environment:
   ```sh
   python -m venv venv
   .\venv\Scripts\activate
   ```
3. Install required packages (if any):
   ```sh
   pip install -r requirements.txt
   ```
   *(Note: If there is no requirements.txt, dependencies are likely standard library only.)*

### Database Setup
- The database will be created automatically when you run the application for the first time.
- If needed, you can use `Personal_Expense.sql` to initialize or reset the database schema.

### Usage
Run the main application:
```sh
python main.py
```
Follow the on-screen prompts to add, view, or filter your expenses.

## License
This project is licensed under the MIT License.

## Author
[GODSROBOT](https://github.com/GODSROBOT)
