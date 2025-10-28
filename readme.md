# Python Calculator 🧮

A feature-rich command-line calculator built with Python that performs various mathematical operations including basic arithmetic, factorial, square root, and power calculations.

## 🎯 Features

- **Basic Arithmetic Operations**
  - Addition
  - Subtraction
  - Multiplication
  - True Division
  - Floor Division
  - Modular Division
- **Advanced Operations**
  - Factorial calculation
  - Square root
  - Power/Exponentiation
- Interactive menu-driven interface
- Continuous operation until exit
- Input validation

<div align="center">

### Don't want to clone? No problem! Run it instantly:

[![Open in Codespaces](https://img.shields.io/badge/Open%20in-Codespaces-green?style=for-the-badge&logo=github)](https://codespaces.new/sridharchinthaparthi/python-calculator)

**Perfect for:**
- 📱 Mobile browsing - Test from your phone!
- ⚡ Quick exploration - No setup required
- 🧪 Experimentation - Fork and modify

</div>

## 📋 Prerequisites

- Python 3.10 installed on your system

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/sridahrchinthaparthi/python-calculator.git
```

2. Navigate to the project directory:
```bash
cd python-calculator
```

3. Run the calculator:
```bash
python calculator.py
```

## 🎮 How to Use

1. Run the program
2. Select an operation from the menu (1-10)
3. Enter the required values when prompted
4. View your result
5. Choose another operation or exit (option 10)

### Menu Options:
```
1  - Addition
2  - Subtraction
3  - Multiplication
4  - True Division
5  - Floor Division
6  - Modular Division
7  - Factorial
8  - Square Root
9  - Power
10 - Exit
```

## 💻 Code Structure

```python
#Mini Project on Calculator

def get():
    """Get two input values from user"""
    a=int(input('Enter val1: '))
    b=int(input('Enter val2: '))
    return a,b

# Mathematical operation functions
def add(a,b):
    return a+b

def sub(a,b):
    return a-b

def mul(a,b):
    return a*b

def true_div(a,b):
    return a/b

def floor_div(a,b):
    return a//b

def mod(a,b):
    return a%b

def fact():
    a=int(input('Enter val: '))
    fact=1
    for i in range(1,a+1):
        fact*=i
    return fact

def sqrt():
    a=int(input('Enter val: '))
    return a**(1/2)

def power(a,b):
    return a**b

# Main calculator loop with menu
while True:
    print('-'*45)
    print('Enter 1: addition')
    print('Enter 2: subtraction')
    print('Enter 3: Multiplication')
    print('Enter 4: True Division')
    print('Enter 5: Floor Division')
    print('Enter 6: Modular Division')
    print('Enter 7: Factorial')
    print('Enter 8: square root')
    print('Enter 9: Power')
    print('Enter 10: To Exit the app')
    choice=int(input('Enter your choice: '))
    
    if choice==1:
        m,n=get()
        print('The Sum is: ',add(m,n))
    elif choice==2:
        m,n=get()
        print('Sub is: ',sub(m,n))
    elif choice==3:
        m,n=get()
        print('Mul is: ',mul(m,n))
    elif choice==4:
        m,n=get()
        print('True division is: ',true_div(m,n))
    elif choice==5:
        m,n=get()
        print('Floor Division is: ',floor_div(m,n))
    elif choice==6:
        m,n=get()
        print('Modular Division is: ',mod(m,n))
    elif choice==7:
        print('Factorial is: ',fact())
    elif choice==8:
        print('Square root is: ',sqrt())
    elif choice==9:
        m,n=get()
        print('Power is: ',power(m,n))
    elif choice==10:
        print('Thank you for using this app')
        break
    else:
        print('Invalid Choice')
```

## 📸 Example Usage

```
---------------------------------------------
Enter 1: addition
Enter 2: subtraction
Enter 3: Multiplication
Enter 4: True Division
Enter 5: Floor Division
Enter 6: Modular Division
Enter 7: Factorial
Enter 8: square root
Enter 9: Power
Enter 10: To Exit the app
Enter your choice: 1
Enter val1: 25
Enter val2: 15
The Sum is: 40
```

## 🛠️ Future Enhancements

- [ ] Add trigonometric functions (sin, cos, tan)
- [ ] Implement memory storage functionality
- [ ] Add error handling for division by zero
- [ ] Create a GUI version using Tkinter
- [ ] Add calculation history
- [ ] Support for decimal/float operations in factorial

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/sridahrchinthaparthi/python-calculator/issues).

### Steps to Contribute:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

**Sridhar Chinthaparthi**
- Email: sridhar.chinthaparthi@gmail.com
- GitHub: [@sridharchinthaparthi](https://github.com/sridharchinthaparthi)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## ⭐ Show your support

Give a ⭐️ if this project helped you!

---


**Made with ❤️ by Sridhar Chinthaparthi**

