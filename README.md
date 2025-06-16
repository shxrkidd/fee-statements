# fee-statements

# Fee Statements Generator

This project provides a simple Python-based fee statement generation tool for finance officers in learning institutions. It allows tracking of student payments, calculating outstanding balances, and generating statements in PDF format.

## Features
- Manage student fee records
- Track payments over time
- Generate PDF statements for easy sharing
- Simple and customizable structure

## Installation
Ensure you have Python installed, then clone this repository:

```sh
git clone https://github.com/shxrkidd/fee-statements.git
cd fee-statements


Install necessary dependencies:

```sh
pip install fpdf
```

## Usage
Example usage in Python:

```python
from student_fee import Student

student = Student("John Doe", "12345", 50000)
student.make_payment(20000, "2025-06-01")
student.make_payment(15000, "2025-06-10")

student.generate_statement_pdf()
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Feel free to open issues or submit pull requests. Contributions are welcome!

---


