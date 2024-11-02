Project: Contact System
This project is a basic contact system developed in Java using Swing for the graphical interface. It allows 
users to submit contact information and receive feedback.

Project Structure

The project consists of two main classes:

NewJFrame
	This class represents the main window of the contact form.
	It allows users to enter their name, ID (RUT), address, region, and phone number, as well as a reason for contact.
	It includes buttons to submit and cancel the action.

FormularioEnviado
	This class is a dialog shown after submitting the form.
	It provides a series of evaluation fields about the user’s experience while filling out the form.
	It includes a button to finish and close the application.

Requirements:

Java Development Kit (JDK): Make sure you have JDK 8 or higher installed.
IDE: It is recommended to use an IDE like IntelliJ IDEA, Eclipse, or NetBeans to facilitate running or editing.
How to Use:

Run the application, and the contact window will open.
Fill in the required fields.
Click "Submit" to send the form. A new dialog will open, allowing you to evaluate your experience.
Click "Finish" to close the application.
Features

Data Entry: Allows users to enter their contact information.
Satisfaction Evaluation: After submitting the form, users can evaluate different aspects of the form.
Graphical Interface: Uses Swing components for a user-friendly experience.