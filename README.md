# MASA StudentDB Matrix

CSV-driven institutional database engine for student directories and grading records

## Technical Architecture

The application is structured following modular separation of concerns and modern object-oriented software patterns:

- **Component Layering**: UI presentation views, operational business logic, and persistent storage abstractions are cleanly isolated.
- **Defensive Engineering**: Robust input sanitization and defensive exception management preventing unhandled runtime faults.
- **Modern Developer Experience**: High-contrast interface aesthetics adhering to professional software engineering standards.

## Preview

![Application Interface](screenshots/app_interface.png)

## Prerequisites

- Python 3.10 or higher
- Required libraries:

```bash
pip install customtkinter pillow
```

## Execution

Launch the application via Python:

```bash
python "Student Database Management System With CSV in Python/index.py"
```

## Project Structure

```
.
├── Student Database Management System With CSV in Python
├── screenshots/
│   └── app_interface.png
├── .gitignore
├── LICENSE             # MIT License
└── README.md           # Developer documentation
```

## License

This project is licensed under the terms of the MIT License. Refer to the `LICENSE` file for details.
