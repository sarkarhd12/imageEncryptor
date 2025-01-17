# imageEncryptor

This Java application allows users to perform a bitwise XOR operation on the contents of a file with a given key. The application features a simple graphical user interface (GUI) to select a file and input the XOR key.


Features

    Select a file using a file chooser dialog.
    Input an integer key for the XOR operation.
    Perform the XOR operation on the file's data.
    Save the modified data back to the file.
    
Requirements

    Java Development Kit (JDK) 8 or later.
    An IDE or text editor to run the Java application.  

 Explanation:

    Imports: Import necessary classes for GUI components, file operations, and exception handling.
    operate(int key) Method: Opens a file dialog for the user to select a file, reads the file into a byte array, performs an XOR operation on each byte with the given key, and then writes the modified data back to the file. It also shows a confirmation message upon completion.
    main(String[] args) Method: Creates a simple GUI with a JFrame, JButton, and JTextField. The button's action listener reads the integer key from the text field, calls the operate method with that key, and handles potential number format exceptions.    

 Installation

    Clone the repository or download the source code files.

    bash

git clone <repository_url>

Open the project in your preferred Java IDE or text editor.
Compile and run the FileOperationExample.java file.   
