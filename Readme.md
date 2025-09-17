# Personal Expense Tracker (Python)

A simple Python-based personal expense tracker that helps you manage and track your daily expenses. This project uses SQLite for data storage and provides a command-line interface for adding, viewing, and managing expenses.

## Features
- Add new expenses with details (amount, category, date, description)
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

### Build as Windows Executable (.exe)
If you want to create a standalone Windows executable (.exe) for this app, use [PyInstaller](https://pyinstaller.org/):

#### Step-by-step: How to convert this Python app to .exe
1. Open a terminal or command prompt in the project directory.
2. (Optional but recommended) Activate your virtual environment if you have one:
   ```sh
   .\venv\Scripts\activate
   ```
3. Make sure all dependencies are installed:
   ```sh
   pip install -r requirements.txt
   ```
4. Install PyInstaller if not already installed:
   ```sh
   pip install pyinstaller
   ```
5. Run PyInstaller to build the executable:
   ```sh
   pyinstaller --onefile --windowed main.py
   ```
   - The `--onefile` flag bundles everything into a single .exe file.
   - The `--windowed` flag prevents a console window from appearing (for GUI apps).
6. After the process completes, find your `.exe` file in the `dist` folder:
   ```
   dist\main.exe
   ```
7. You can now copy or share this `.exe` file. It will run on any Windows machine without needing Python installed.

## License
This project is licensed under the MIT License.

## Author
[GODSROBOT](https://github.com/GODSROBOT)
