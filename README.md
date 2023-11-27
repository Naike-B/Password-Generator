# Password-Generator

## Description
This application was created to help users creating a new password that is randomly generated. 
The user can choose to include the following in the password:
- lower case characters
- upper case characters 
- numbers 
- special characters

The user can choose to include all character types, a combination of some of them or just one of them.

The minimum and maximum length of the password is defined and the user is made aware of this when prompted to choose how long the password should be.

While working on this application, I learned about a bunch of new things. The **null** value, how to use a **while loop** to run the code until the condtion set is met when I don't know how many times the code should run. The **confirm function** which shows a modal window with a question and two buttons: OK and Cancel. The result is true if OK is pressed and false otherwise. The **concat method** to join two or more strings. I also found a function to generate a random value from an array using the static methods **Math.floor** and **Math.random**.

## Installation 
N/A

## Usage
To use this application, navigate to ![Password-Generator]()

Click on the red button **Generate password**

You'll be presented with a series of prompts to choose the password's criteria:
- Length: between 8 and 128 characters
- Lower case characters (OK = Yes, Cancel = No)
- Upper case characters (OK = Yes, Cancel = No)
- Numbers (OK = Yes, Cancel = No)
- Special characters (OK = Yes, Cancel = No)

The password is randomly generated and displayed in the white box under **Your Password:**

See an example below:
![alt Password generator example](assets/images/Password-Generator-Usage.mp4)