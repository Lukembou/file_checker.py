# file_checker.py

### Overview

This Python script is like your personal file detective. You give it the path to a file you're interested in, and it goes to work checking three important things:

Is the File There?: First off, it makes sure the file actually exists at the location you specified. No use checking other things if the file isn't even there!

Who Can See What?: Next, it peeks at the file's permissions to see who can access it. It wants to make sure that only the right people can see what's inside. It checks if the file owner can read and write (because it's their file, after all), while everyone else should only be able to read.

Has Anyone Messed With It?: Lastly, it calculates a special code called a checksum. It's like a digital fingerprint of the file's contents. The script compares this fingerprint to one you might have saved from before. If they match, it means the file hasn't changed since you last checked it. If not, it raises a flag that something fishy might be going on.

Throughout the whole process, it keeps a log of what it's doing, so you can always go back and see what the detective found.

So, it's basically your file guardian, making sure your important files are safe and sound!

### File Checker Project

This Python script checks the integrity, availability, and confidentiality of files.

#### Dependencies

- [os module](https://docs.python.org/3/library/os.html): Used for file operations.
- [hashlib module](https://docs.python.org/3/library/hashlib.html): Used for calculating file checksums.
- [logging module](https://docs.python.org/3/library/logging.html): Used for logging results.

#### Usage Instructions

#### Step 1: Prepare Your Data

1. **Ensure Files Exist**: Make sure the files you want to check exist on your system.

#### Step 2: Install Dependencies

1. **Install Python**: If Python is not already installed, download and install it from the [official website](https://www.python.org/downloads/).

2. **No additional dependencies required**: The script uses built-in Python modules.

#### Step 3: Run the Script

1. **Execute the Script**: Open a terminal or command prompt and navigate to the directory containing the script.

2. **Run the Script**: Use the following command to run the script:

3. **Input File Path**: When prompted, enter the file path you want to check.

4. **Review Output**: The script will display the results of the checks, including availability, permissions, and checksum.

### Help

If you encounter any confusion or need assistance, feel free to reach out for help.

### Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

### Important Note

This code was helped generated through chatGPT, this is for personal use due to problems what may occur with licensing if you try to use this code elsewhere.

However, this code is still great to use as a security measure on personal devices and learning tool to help you grow in the security realm.

### License

This project is licensed under the [MIT License](LICENSE).
