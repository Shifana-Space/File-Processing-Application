# File Processing Application in Java

## 1. Problem Statement

Develop a Java application to store employee details in a file and read the stored information using both byte streams and character streams. Handle input/output (I/O) exceptions appropriately.

## 2. Objective

The main objective of this application is to understand file handling in Java by performing file writing and reading operations using byte streams and character streams. It also demonstrates how to handle file-related errors using exception handling.

## 3. Description

This application stores employee information, such as employee ID, name, and salary, in a text file named `employee.txt`.

The application performs the following operations:

1. Stores employee details in a file using a byte stream.
2. Reads the stored information using a byte stream.
3. Reads the same information using a character stream.
4. Handles input/output exceptions using `IOException`.
5. Displays the employee details on the console.

## 4. Concepts Used

### Byte Streams

Byte streams handle data in the form of bytes. They can be used for binary data and text data.

* `FileOutputStream`: Writes employee details to a file.
* `FileInputStream`: Reads data from a file one byte at a time.

### Character Streams

Character streams are designed for reading and writing text data.

* `FileReader`: Reads characters from a file.
* `BufferedReader`: Reads text efficiently, including line-by-line reading.

### Exception Handling

The `IOException` class is used to handle errors that may occur during file operations. The `try-catch` block helps the program respond to these errors appropriately.

## 5. Program Workflow

1. Start the Java application.
2. Define the file name as `employee.txt`.
3. Store employee details in the file using `FileOutputStream`.
4. Read the stored details using `FileInputStream`.
5. Read the same details line by line using `FileReader` and `BufferedReader`.
6. Handle I/O exceptions using `try-catch`.
7. Display the results on the console.

## 6. Sample Employee Details

The application stores the following information:

* Employee ID: 101
* Employee Name: Shifana
* Salary: 30000

## 7. Expected Output

```text
Employee details stored successfully.

Reading using Byte Stream:
Employee ID: 101
Name: Shifana
Salary: 30000

Reading using Character Stream:
Employee ID: 101
Name: Shifana
Salary: 30000
```

## 8. Advantages

* Demonstrates basic file handling in Java.
* Explains the difference between byte streams and character streams.
* Enables persistent storage of employee information.
* Demonstrates exception handling during file operations.
* Helps understand Java I/O classes.

## 9. Conclusion

The File Processing Application demonstrates how to store and retrieve employee details using Java file-handling mechanisms. It uses byte streams for byte-based input/output, character streams for text processing, and exception handling to manage I/O errors.

