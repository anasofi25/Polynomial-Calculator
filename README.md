# Polynomial Calculator 🧮

A **Polynomial Calculator** that allows users to input polynomials, perform various operations (addition, subtraction, multiplication, differentiation, and integration), and view the results via a graphical user interface (GUI). The application uses **JavaFX** and follows object-oriented principles to provide a modular, user-friendly solution for polynomial calculations.
![calc](https://github.com/user-attachments/assets/67467ff8-67ee-4343-8ca1-c6af2c11c277)

## 🎯 Assignment Objective

### Main Objective:
Design and implement a polynomial calculator with a graphical interface where users can input polynomials, select mathematical operations, and view results. Supported operations include:
- Addition ➕
- Subtraction ➖
- Multiplication ✖️
- Differentiation ✍️
- Integration ➗

### Sub-Objectives:
- Analyze the problem and define functional requirements.
- Model the problem using use case diagrams and descriptions.
- Design the software using object-oriented principles (encapsulation, etc.).
- Implement the solution.
- Test the application with various scenarios.
- Draw conclusions and suggest future improvements.

---

## 🔍 Problem Analysis & Use Cases

### Functional Requirements:
1. **User can input polynomials** ✏️
2. **User can select mathematical operations** ➕ ➖ ✖️
3. **User can view the results** 📊

### Use Cases:
1. **Input Polynomial** 📝
   - Actor: User
   - Description: User inputs polynomial expressions.
   - Steps:
     1. User enters polynomial expression(s).
     2. User confirms input.

2. **Perform Addition** ➕
   - Actor: User
   - Description: User selects addition operation.
   - Steps:
     1. User inputs two polynomials.
     2. User selects addition operation.
     3. System computes the result.
     4. System displays the result.

3. **Perform Subtraction** ➖
   - Actor: User
   - Description: User selects subtraction operation.
   - Steps:
     1. User inputs two polynomials.
     2. User selects subtraction operation.
     3. System computes the result.
     4. System displays the result.

4. **Perform Multiplication** ✖️
   - Actor: User
   - Description: User selects multiplication operation.
   - Steps:
     1. User inputs two polynomials.
     2. User selects multiplication operation.
     3. System computes the result.
     4. System displays the result.

5. **Perform Differentiation** ✍️
   - Actor: User
   - Description: User selects differentiation operation.
   - Steps:
     1. User inputs a polynomial.
     2. User selects differentiation operation.
     3. System computes the result.
     4. System displays the result.

6. **Perform Integration** ➗
   - Actor: User
   - Description: User selects integration operation.
   - Steps:
     1. User inputs a polynomial.
     2. User selects integration operation.
     3. System computes the result.
     4. System displays the result.

---

## 🛠️ Design

### Class Diagram:
- **Polynomial Class**: Handles polynomial operations like addition, subtraction, multiplication, differentiation, and integration.
- **CalculatorController Class**: Manages user interactions and integrates with the Polynomial class.

### Key Methods:
- **addTerm()**: Adds terms to the polynomial.
- **add()**: Performs addition with another polynomial.
- **subtract()**: Performs subtraction with another polynomial.
- **multiply()**: Multiplies polynomials.
- **differentiate()**: Computes the derivative of the polynomial.
- **integrate()**: Computes the integral of the polynomial.
- **toString()**: Converts the polynomial to a human-readable format.

---

## 💻 Implementation

### **CalculatorController Class**:
- **Fields**: `polynomial1TextField`, `polynomial2TextField`, `resultTextArea` for UI input and output.
- **Methods**:
  - `add()`, `subtract()`, `multiply()`, `integrate()`, `differentiate()` to perform corresponding operations and display the result.

### **Polynomial Parsing**:
- `parsePolynomial()`: Converts string inputs into `Polynomial` objects.
- `parseSingleTerm()`: Parses individual terms of a polynomial.

---

## 📊 Results

### Graphical User Interface (GUI):

The GUI allows users to input polynomials and select operations. Here is how the interface looks:

![Polynomial Calculator GUI](your-image-path.png)

### Testing:

- **Addition**: Tests for polynomials with different degrees and coefficients.
- **Subtraction**: Similar to addition, but with subtraction.
- **Multiplication**: Ensures the polynomial multiplication works correctly.
- **Differentiation**: Validates differentiation for various polynomials.
- **Integration**: Tests the integration functionality for polynomials.

---

## 📝 Conclusions

The polynomial calculator was successfully designed and implemented, fulfilling all requirements of the assignment. The GUI is intuitive, and the mathematical operations are accurate and easy to perform.

### Future Improvements:
- Add **division** operation.
- **Optimize performance** for large polynomials.
- **Refine the user interface** for better usability.

---

## 📚 Bibliography

- [Baeldung: JUnit 5](https://www.baeldung.com/junit-5)
