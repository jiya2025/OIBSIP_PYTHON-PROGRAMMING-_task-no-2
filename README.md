# OIBSIP_PYTHON-PROGRAMMING-_task-no-2


🎯 **Objective**:

The main goal of this project is to:

* Develop a **command-line application** in Python.
* Take user inputs (weight and height), calculate BMI, and classify it.
* Use basic **AI logic** like input validation, interaction, and decision making.
* Help users understand their health status in terms of BMI category.

 🧰 **Tools and Technologies Used**:

| Tool / Library              | Purpose                                                                |
| --------------------------- | ---------------------------------------------------------------------- |
| **Python**                  | Main programming language                                              |
| **Built-in functions**      | `input()`, `print()`, `float()`, etc. for interaction and calculations |
| **Control Flow Statements** | `if`, `elif`, `else` for BMI classification logic                      |
| **Loops**                   | `while` loop for input validation and repetition                       |
| **Exception Handling**      | `try-except` to prevent crashes from invalid input                     |
| **Basic AI logic**          | Rule-based logic to simulate intelligent interaction                   |

---

 🪜 **Steps Involved**:

 **Step 1: Start the Program**

* Greet the user and ask for their **name** to make the interaction personalized.

 **Step 2: Input Validation**

* Prompt the user to input their **weight (kg)** and **height (meters)**.
* Use **input validation with AI-like rules** to ensure the values are within a realistic range (e.g., weight: 1–300 kg, height: 0.5–2.5 m).
* Handle invalid inputs using a `while` loop and `try-except`.

 **Step 3: BMI Calculation**

* Apply the BMI formula:

  $$
  \text{BMI} = \frac{\text{weight (kg)}}{\text{height (m)}^2}
  $$

**Step 4: Classification of BMI**

* Use `if-elif-else` to categorize the BMI:

  * BMI < 18.5 → Underweight
  * 18.5 ≤ BMI < 25 → Normal weight
  * 25 ≤ BMI < 30 → Overweight
  * BMI ≥ 30 → Obese
    
**Step 5: Display the Result**

* Show the user their BMI value rounded to 2 decimal places.
* Inform them of their health category in a friendly message.

 🎯 **Expected Outcome**:

| Feature                    | Description                                                      |
| -------------------------- | ---------------------------------------------------------------- |
| ✅ Personalized Interaction | Greets the user and interacts politely like a basic AI assistant |
| ✅ BMI Computation          | Accurately calculates BMI using user inputs                      |
| ✅ BMI Classification       | Classifies the result into medical categories                    |
| ✅ Validated Inputs         | Ensures meaningful and error-free user data                      |
| ✅ AI-like Behavior         | Offers feedback, handles incorrect inputs, and guides the user   |

