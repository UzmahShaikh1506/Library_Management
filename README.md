# Library Management

## **This project implements a simple library management system using Java Swing..**

- Java Swing is a part of Java Foundation Classes (JFC) that is used to create window-based applications.
- The javax.swing package provides classes for java swing API such as JButton, JTextField, JTextArea, JRadioButton, JCheckbox, JMenu, JColorChooser etc.

---

### Components Used **:**

- JLabel - To display text as labels
- JTextField - For text input
- JButton - For buttons
- JPanel - To group components in a pane

---

### **The main features are:**

- Adding new books to the library
- Viewing all books in the library
- Editing book details
- Deleting books
- Clearing the form fields
- Exiting the application

---
---

### **Output:** 
![image](https://github.com/UzmahShaikh1506/Library_Management/assets/131281147/cbd736b4-9273-4945-b943-9bea65e2f2a3)


### **The program does the following:**

1. It creates GUI components like labels, text fields, and buttons.
2. It maintains a ArrayList of String arrays to store all the book details. Each String array represents one book.
3. When the Add button is clicked, it gets the text from all the text fields and creates a String array with the book details. This is added to the ArrayList to store the book.
4. The View button displays all books in a JTable.
5. The Edit button allows editing a book's details based on the book ID.
6. The Delete button removes a book from the ArrayList based on the book ID.
7. The Clear button simply clears all the text fields.
8. The Exit button exits the Java application.


