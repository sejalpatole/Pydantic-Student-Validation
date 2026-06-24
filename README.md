# Pydantic Student Validation

A simple Python project demonstrating how to use **Pydantic** for validating student data. This project ensures that student information such as name, age, email, and marks follows predefined validation rules before being processed.

## 🚀 Features

* Validate student data using Pydantic models
* Automatic type checking
* Custom validation rules
* Clear error messages for invalid data
* Easy to understand and beginner-friendly

## 🛠️ Technologies Used

* Python 3
* Pydantic

## 📂 Project Structure

```text
Pydantic-Student-Validation/
│
├── main.py
├── requirements.txt
└── README.md
```

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/sejalpatole/Pydantic-Student-Validation.git
```

2. Navigate to the project folder:

```bash
cd Pydantic-Student-Validation
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

Run the Python file:

```bash
python main.py
```

## 📌 Example

### Valid Input

```python
{
    "name": "John Doe",
    "age": 20,
    "email": "john@example.com",
    "marks": 85
}
```

### Invalid Input

```python
{
    "name": "",
    "age": -5,
    "email": "invalid-email",
    "marks": 150
}
```

Pydantic will raise validation errors and display meaningful messages.

## 🎯 Learning Outcomes

Through this project, you can learn:

* Python classes and objects
* Data validation
* Pydantic BaseModel
* Field validations
* Error handling
* Clean code practices

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

## 📄 License

This project is created for learning and educational purposes.
