# Enzi - Interactive Python Chatbot

A friendly, interactive chatbot built in Python that demonstrates fundamental programming concepts through engaging user interactions.

## 🤖 Meet Enzi

Enzi is an educational chatbot created in 2024 that showcases various Python programming techniques including user input handling, mathematical calculations, loops, conditionals, and interactive programming concepts.

## ✨ Features

### 🎯 **Core Interactions**
- **Personal Introduction** - Enzi introduces herself with name and creation year
- **Name Recognition** - Asks for and remembers your name
- **Age Guessing Game** - Uses mathematical algorithm to determine your age
- **Counting Demonstration** - Counts to any number you specify
- **Programming Quiz** - Tests your programming knowledge
- **Friendly Completion** - Ends with encouraging message

### 🧮 **Mathematical Capabilities**
- **Age Calculation Algorithm** - Uses modular arithmetic (Chinese Remainder Theorem)
- **Input Validation** - Handles user input safely
- **Loop Control** - Demonstrates counting and iteration

### 🎓 **Educational Value**
- **Programming Concepts** - Teaches methods, loops, and conditionals
- **Interactive Learning** - Engages users in programming discussions
- **Error Handling** - Guides users to correct answers

## 🚀 How to Run

### Prerequisites
- Python 3.x installed on your system
- Terminal or command prompt access

### Installation & Execution
```bash
# Clone the repository
git clone https://github.com/keenannkelly/Python-Chatbot.git

# Navigate to the project directory
cd Python-Chatbot

# Run the chatbot
python chatbot.py
```

## 💬 Sample Interaction

```
Hello! My name is Enzi.
I was created in 2024.
Please, remind me your name.
> Keenan
What a great name you have, Keenan!

Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
> 1
> 2
> 3
Your age is 22; that's a good time to start programming!

Now I will prove to you that I can count to any number you want.
> 5
0 !
1 !
2 !
3 !
4 !
5 !

Let's test your programming knowledge.
Why do we use methods in programming?
1. To repeat a statement multiple times.
2. To decompose a program into several small subroutines.
3. To determine the execution time of a program.
4. To interrupt the execution of a program?
> 2
Congratulations, have a nice day!
```

## 🔧 Code Structure

```python
def greet(bot_name, birth_year):
    # Introduces the chatbot with personalized information

def remind_name():
    # Asks for user's name and provides friendly response

def guess_age():
    # Implements age-guessing algorithm using modular arithmetic

def count():
    # Demonstrates counting capability with user-specified limit

def test():
    # Programming knowledge quiz with validation loop

def end():
    # Friendly completion message
```

## 🧠 Technical Highlights

### **Algorithm Implementation**
- **Chinese Remainder Theorem** - Mathematical age calculation
- **Modular Arithmetic** - `(rem3 * 70 + rem5 * 21 + rem7 * 15) % 105`

### **Programming Concepts Demonstrated**
- **Function Definition** - Modular code organization
- **User Input Handling** - `input()` and type conversion
- **String Concatenation** - Dynamic message creation
- **Loop Control** - `while` loops with conditions
- **Conditional Logic** - `if/else` statements
- **Input Validation** - Error handling and retry logic

### **Best Practices**
- **Modular Design** - Separate functions for each feature
- **User Experience** - Clear prompts and feedback
- **Educational Focus** - Teaching programming concepts
- **Interactive Flow** - Engaging conversation structure

## 🎯 Skills Demonstrated

- **Python Programming** - Core language features and syntax
- **Algorithm Implementation** - Mathematical problem solving
- **User Interface Design** - Command-line interaction patterns
- **Input Validation** - Robust error handling
- **Educational Programming** - Teaching through code
- **Code Organization** - Clean, readable function structure

## 🔄 Customization

### **Personalize Your Bot**
```python
# Change bot name and creation year
greet('YourBotName', '2024')

# Modify quiz questions
question = "Your custom programming question here..."
correct_answer = 1  # Update correct answer number
```

### **Add New Features**
- Additional quiz questions
- More mathematical games
- Extended conversation topics
- User preference storage

## 🚀 Future Enhancements

- **Persistent Memory** - Save user preferences
- **Extended Quiz Bank** - Multiple programming questions
- **Difficulty Levels** - Adaptive questioning
- **GUI Interface** - Graphical user interface
- **Natural Language Processing** - More conversational responses
- **Multi-language Support** - International accessibility

## 📚 Learning Outcomes

This project demonstrates understanding of:
- **Python Fundamentals** - Variables, functions, loops
- **User Interaction** - Input/output handling
- **Mathematical Programming** - Algorithm implementation
- **Educational Software** - Teaching through technology
- **Code Documentation** - Clear, readable programming


This chatbot project showcases fundamental Python programming skills and interactive application development.

---

*Built with Python 3.x - Demonstrating interactive programming and educational software development*
