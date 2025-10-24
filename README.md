# BMI-CALCULATOR-USING LOGIC GATE

Link: http://127.0.0.1:5500/adv.html

1) Implementation
A web-based Body Mass Index (BMI) calculator that demonstrates the practical application of digital logic gates (AND, OR, NOT, XOR, NAND, NOR) in health calculations.
🎯 Project Overview
This project showcases how fundamental computer science concepts like logic gates can be applied to real-world health applications. The calculator determines BMI categories using boolean logic operations, making it both educational and functional.
✨ Features

Logic Gate Processing: Implements AND, OR, NOT, XOR, NAND, and NOR gates for BMI classification
Real-time Calculations: Instant BMI computation with visual feedback
Transparent Operations: Displays all logic gate operations used in the calculation
Color-coded Results: Visual indicators for different BMI categories

🔵 Underweight (BMI < 18.5)
🟢 Normal Weight (18.5 ≤ BMI < 25)
🟠 Overweight (25 ≤ BMI < 30)
🔴 Obese (BMI ≥ 30)


Responsive Design: Works seamlessly on desktop and mobile devices
No Dependencies: Pure HTML, CSS, and JavaScript implementation

🛠️ Technologies Used

HTML5: Structure and content
CSS3: Styling with gradient backgrounds and modern UI
JavaScript: Logic gate implementation and BMI calculations

🔧 How It Works

Input Processing: Converts weight (kg) and height (cm) into BMI value
Binary Conversion: Transforms BMI into binary flags for logic processing
Logic Gate Operations: Uses combinational logic to determine BMI category

   isUnderweight = AND(lessThan185, 1)
   isNormal = AND(greaterEqual185, lessThan250)
   isOverweight = AND(greaterEqual250, lessThan300)
   isObese = AND(greaterEqual300, 1)

Result Display: Shows BMI value, category, and all logic operations  

    <img width="872" height="457" alt="image" src="https://github.com/user-attachments/assets/ef4b9a00-cb2c-4a1f-9b5f-c133e329bdf8" />



    
