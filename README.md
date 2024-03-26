# DevOps Masters Program Class of 2024A Web Application

This web application displays a webpage welcoming users to the DevOps Masters Program Class of 2024A and showcases the management team.


Sure, here are the installation steps for the application along with running it:

### Installation Steps:

1. **Update and Install Python 3:**
   ```bash
   sudo apt update
   sudo apt install python3
   ```

2. **Install pip (Python Package Installer):**
   ```bash
   sudo apt install python3-pip
   ```

3. **Install Python Virtual Environment (optional but recommended):**
   ```bash
   sudo apt install python3-venv
   ```

4. **Clone the Repository:**
   ```bash
   git clone https://github.com/CHAFAH/JavaApp.git
   ```

5. **Navigate to the Project Directory:**
   ```bash
   cd JavaApp
   ```

6. **Set Up a Virtual Environment (optional but recommended):**
   ```bash
   python3 -m venv venv
   ```

7. **Activate the Virtual Environment:**
   ```bash
   source venv/bin/activate
   ```

8. **Install Flask:**
   ```bash
   pip install Flask
   ```

9. **Generate requirements.txt:**
   ```bash
   touch requirements.txt
   pip freeze > requirements.txt
   ```

### Running the Application:

1. **Make Sure You're in the Project Directory:**
   ```bash
   cd JavaApp
   ```

2. **Activate the Virtual Environment (if not already activated):**
   ```bash
   source venv/bin/activate
   ```

3. **Run the Flask Application:**
   ```bash
   python app.py
   ```

### Accessing the Application:

1. Once the application is running, open your web browser.
2. Enter the following URL, replacing `<your_server_ip>` with the public IP address or domain name of your Ubuntu server:
   ```
   http://<your_server_ip>:5000
   ```
   
   This will display the web application, welcoming users to the DevOps Masters Program Class of 2024A and showcasing the management team.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


