# Password_Generator

🔒 Strong Password Generator

A simple yet powerful command-line tool for generating strong, random passwords. This Python script allows users to customize their password requirements, ensuring maximum security for their accounts and sensitive data. 💻✨
Features 🌟

    Customizable Length: Specify the desired length of the password to suit your needs. 🔢
    Character Variety: Choose from uppercase letters, lowercase letters, digits, and special symbols to create a complex password. 🔠🔡🔢
    Random Generation: Utilizes Python's random module to generate passwords, ensuring unpredictability and strength. 🎲

Installation 🛠️

    Clone the repository:

    git clone https://github.com/dionabazi/Password-Generator.git

    cd Password-Generator

    Ensure you have Python 3 installed on your system. 🐍

Usage 📖

Run the script with the desired options:


python3 password_generator.py --length <length> --upper --lower --digits --symbols

Options ⚙️

    --length <length>: Specify the length of the password (default is 12). 🔍
    --upper: Include uppercase letters. 🔠
    --lower: Include lowercase letters. 🔡
    --digits: Include digits. 🔢
    --symbols: Include special symbols. ✨

Example 📌

Generate a 16-character password that includes uppercase letters, lowercase letters, digits, and symbols:

python3 password_generator.py --length 16 --upper --lower --digits --symbols
