# MKDocs Starter

Welcome to the **MKDocs Starter** repository! Fast setup MKDocs material theme with this starter project.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Python 3** (Required to run MKDocs)
- **Git Bash** (For Windows users)

## Installation and Execution

### MacOS & Linux Users
1. Clone the repository:
   ```sh
   git clone https://github.com/abhiramelf/mkdocs-starter.git
   cd mkdocs-starter
   ```
2. Run the following command inside the project folder:
   ```sh
   ./run.sh
   ```

### Windows Users
1. Clone the repository:
   ```sh
   git clone https://github.com/abhiramelf/mkdocs-starter.git
   cd mkdocs-starter
   ```
2. Open the **run.sh** file and modify **line 5**:
   Change:
   ```sh
   source venv/bin/activate
   ```
   To:
   ```sh
   source venv/Scripts/activate
   ```
3. Open **Git Bash** (Do not use Windows CMD or PowerShell) and run:
   ```sh
   ./run.sh
   ```

## Running the Server
After executing the script, your MKDocs server should be running. You can view the documentation in your browser by navigating to:
```
http://127.0.0.1:8000/
```

## Stopping the Server
To stop the server, use **Ctrl+C** in the terminal.

## Customizing Your Documentation
You can modify the documentation content inside the `docs/` folder and update the `mkdocs.yml` configuration file to suit your project needs.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

Happy documenting! 🚀
