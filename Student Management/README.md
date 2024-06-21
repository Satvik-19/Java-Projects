### Project Summary: Student Management System

1. **Student Class**:
   - Represents individual students with attributes: `name`, `rollNumber`, and `grade`.
   - Provides a constructor, getter methods, and a `toString` method for displaying student details.

2. **StudentManagementSystem Class**:
   - Manages a list of `Student` objects.
   - Methods include:
     - `addStudent(Student student)`: Adds a student to the list.
     - `removeStudent(int rollNumber)`: Removes a student by roll number.
     - `searchStudent(int rollNumber)`: Searches for a student by roll number.
     - `getAllStudents()`: Returns a list of all students.
     - `saveToFile(String filename)`: Saves student data to a file.
     - `loadFromFile(String filename)`: Loads student data from a file.

3. **StudentManagementSystemApp Class**:
   - Provides a graphical user interface (GUI) using Java Swing.
   - GUI Components:
     - Text fields for entering student name, roll number, and grade.
     - Buttons for adding, removing, searching, and displaying students.
     - A text area to display student information.
   - Integrates with `StudentManagementSystem` to perform backend operations based on user actions. 

This system enables efficient management of student records through both command-line operations and an interactive GUI, with support for data persistence via file operations.
