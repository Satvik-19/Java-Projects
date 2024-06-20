Here’s a concise explanation focusing on the main working parts of the code without including the code snippets:

1. **Input Number of Subjects and Marks:**
   - The program asks the user to enter the number of subjects.
   - It then creates an array to store the marks for each subject and uses a loop to input these marks from the user.

2. **Calculate Total Marks:**
   - The `calculateTotalMarks` method is called to add up all the marks stored in the array.

3. **Calculate Average Percentage:**
   - The `calculateAveragePercentage` method calculates the average percentage by dividing the total marks by the number of subjects.

4. **Determine Grade:**
   - The `calculateGrade` method determines the grade based on the average percentage using conditional statements to assign grades (A, B, C, D, F).

5. **Display Results:**
   - The program prints the total marks, average percentage (formatted to two decimal places), and the grade to the console.

6. **Close Scanner:**
   - The `Scanner` object is closed to free up resources.

**Helper Methods:**
- **calculateTotalMarks:** This method takes the array of marks and returns their sum.
- **calculateAveragePercentage:** This method computes the average percentage by dividing the total marks by the number of subjects.
- **calculateGrade:** This method assigns a grade based on the calculated average percentage using a series of conditional checks.
