# Password Generator with GUI

A secure and user-friendly password generator built with Python, featuring a graphical user interface (GUI) designed using `tkinter` and styled with `ttkbootstrap`.

## Features

- **Graphical User Interface**: Built with `tkinter` and enhanced with `ttkbootstrap` for modern styling.
- **Customizable Passwords**:
  - Set password length.
  - Include or exclude uppercase letters, lowercase letters, numbers, and special characters.
- **Random Password Generation**: Ensures strong and unpredictable passwords using Python's `random` and `string` modules.
- **Visual Appeal**: Includes icons and images using the `PIL` (Pillow) library.
- **Error Handling**: Displays user-friendly messages using `tkinter.messagebox`.

## Demo

Run the password generator locally and use the intuitive GUI to generate secure passwords.

## Technologies Used

- **Python**: Core programming language used to implement the password generator.
- **Libraries**:
  - `tkinter`: For creating the GUI.
  - `ttkbootstrap`: For modern styling of the interface.
  - `Pillow (PIL)`: For handling images and icons.
  - `string` and `random`: For character sets and randomization.
  - `math`: For additional mathematical operations (if needed).

## Installation and Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/gui-password-generator.git

2. Navigate to the project folder:
   ```bash
    cd gui-password-generator

3. Install dependencies: Ensure you have Python installed and run the following command:
   ```bash
   pip install ttkbootstrap pillow

4. Run the application:
   ```bash
   python password_generator.py
   
5. Use the GUI:
   - Set your desired password length.
   - Toggle options for uppercase, numbers, and special characters.
   - Click "Generate" to get a secure password.
   - Use the "Copy" button to copy the password to your clipboard.

## Customization
   - Styling: Modify ttkbootstrap themes for a unique look.
   - Advanced Features: Add password strength indicators or save passwords to a file.
   - Icons: Use the Pillow library to add custom icons and images.

## Credits
   - Developed with inspiration from GUI-based password management tools.
   - Uses Python's tkinter and ttkbootstrap for a sleek user experience.

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License. You are free to use, modify, and distribute it as per the license terms.
