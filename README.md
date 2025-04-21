---

# BMI Calculator

## Description

The **BMICalculator** is a simple Java console application that calculates a user's Body Mass Index (BMI) based on their height (in inches) and weight (in pounds). After calculating the BMI, the program classifies the user's weight status according to standard BMI categories.

## Features

- Takes height in inches and weight in pounds as input from the user.
- Calculates BMI using the standard BMI formula for imperial units.
- Outputs the BMI value and corresponding weight category:
  - **Underweight**
  - **Healthy weight**
  - **Overweight**
  - **Obesity**

## Formula Used

\[
\text{BMI} = \frac{\text{weight (lb)}}{\text{height (in)}^2} \times 703
\]

## BMI Categories

| BMI Range          | Category       |
|--------------------|----------------|
| ≤ 18.5             | Underweight    |
| 18.5 – 24.9        | Healthy weight |
| 25.0 – 29.9        | Overweight     |
| ≥ 30.0             | Obesity        |

> _Note_: The program uses `>= 29.9` for obesity, which slightly overlaps the overweight range; you may want to adjust this depending on the precision you prefer.

## Requirements

- Java 8 or above

## How to Run

1. Save the code as `BMICalculator.java`.
2. Open a terminal or command prompt and navigate to the directory where the file is saved.
3. Compile the program:
   ```bash
   javac BMICalculator.java
   ```
4. Run the program:
   ```bash
   java BMICalculator
   ```

## Example Usage

```
Enter your height in inches: 64
Enter your weight in pounds: 120
Your BMI is: 20.579
Healthyweight
```

## License

This project is licensed under the MIT License.

---
