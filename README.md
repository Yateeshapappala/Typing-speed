# Typing Speed Game

This is a **Typing Speed** game built using Python, designed to test and improve your typing skills. The game challenges users to type a given sentence as quickly and accurately as possible. It tracks your typing speed in **Words Per Minute (WPM)** and displays your accuracy based on the input.

- **Typing Speed Measurement**: The game calculates your typing speed in words per minute (WPM).
- **Accuracy Tracking**: It measures how accurate your typing is by comparing your input with the provided sentence.
- **Time Tracking**: The game starts a timer when the user begins typing and stops when the sentence is typed completely.
- **Real-Time Feedback**: You get immediate feedback on your speed and accuracy after completing the test.

## Logic Used

### 1. **Sentence Selection**
The game provides a random sentence from a predefined list (or a file) of sentences. The sentences should be of varying difficulty to give users an appropriate challenge.

### 2. **Timer**
- A timer starts as soon as the user begins typing. The time taken to type the entire sentence is recorded.
- The time is then used to calculate the **Words Per Minute (WPM)**.
- **WPM Formula**:
  \[
  WPM = \frac{{\text{{Number of words typed}}}}{{\text{{Time taken in minutes}}}}
  \]
  where 1 word is considered to be 5 characters long.

### 3. **Typing Accuracy**
- The game compares the user’s typed sentence with the original sentence to determine the accuracy.
- The number of correct characters typed is counted and compared to the total number of characters.
- The accuracy is calculated as:
  \[
  \text{{Accuracy}} = \left(\frac{{\text{{Correct characters typed}}}}{{\text{{Total characters}}}} \right) \times 100
  \]

### 4. **End Result**
- Once the user finishes typing, the program displays:
  - **Time Taken** to type the sentence.
  - **Words Per Minute (WPM)**.
  - **Typing Accuracy** as a percentage.

