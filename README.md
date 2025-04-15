# Calorie Calculator (Java Console Application)

A simple Java-based console application that calculates your daily calorie needs based on your age, gender, weight, height, and activity level using the **Basal Metabolic Rate (BMR)** formula.

## Features

- Calculates **Basal Metabolic Rate (BMR)** using gender-specific formulas
- Adjusts calorie needs based on activity level:
  - Sedentary
  - Moderate
  - Active
- Validates all user inputs
- Easy-to-use console interface

## Technologies Used

- Java
- Java `Scanner` for input
- Command-line interface

## Getting Started  

1. Clone this repository or copy the source code.
 
2. Make sure you have **Java installed** on your system.  
   You can check using:
   ```bash
   java -version
   ```

3. Compile the code:
   ```bash
   javac App.java
   ```

4. Run the compiled program:
   ```bash
   java App
   ```
   
## Example Usage

```
Calorie Calculator
Enter your gender (M/F): M
Enter your age (in years): 21
Enter your weight (in kilograms): 70
Enter your height (in centimeters): 175
Enter your activity level (sedentary/moderate/active): moderate

Your Basal Metabolic Rate (BMR) is: 1723 calories per day.
Your estimated daily calorie needs are: 2671 calories per day.
```

## Formula Reference

- **BMR for Men**:  
  `88.362 + (13.397 × weight in kg) + (4.799 × height in cm) − (5.677 × age in years)`
- **BMR for Women**:  
  `447.593 + (9.247 × weight in kg) + (3.098 × height in cm) − (4.330 × age in years)`
- **Activity Multipliers**:
  - Sedentary: × 1.2
  - Moderate: × 1.55
  - Active: × 1.725
 
## 🌟 *Don’t Forget to Star!*
If you find this project useful, please consider giving it a star ⭐. It helps others discover it too!

