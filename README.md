# Python 3 and pip Installer Script

This is a batch script that automates the installation of Python 3 and pip on Windows using `curl`.

## Usage

1. **Download the Script:**
    - Clone or download this repository to your local machine.

2. **Run the Script:**
    - Open Command Prompt and navigate to the directory containing the script.
    - Execute the script using the following command:

    ```batch
    python.bat
    ```

3. **Follow the Prompts:**
    - The script will download the Python 3 installer and pip installer using `curl`.
    - It will then install Python 3 and pip silently.
    - The script will perform cleanup by deleting the installer files.

4. **Done:**
    - Once the script completes, Python 3 and pip will be installed on your system.

## Notes

- This script uses `curl` to download the installer files. Ensure that `curl` is available in your system's PATH.
- The script is set to install Python 3.10.0. You can modify `PYTHON_VERSION` and `PYTHON_URL` to install a different version.
- The Python installer is executed with the `/quiet` flag for a silent installation. You can adjust installation options as needed.
- The script uses `start /wait` to wait for the Python installer to complete before moving on to pip installation.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
