# OpenGL CodeBlocks GLUT Installer V0.1

This is a batch script for installing OpenGL CodeBlocks with GLUT support. The script is designed to work on a Windows 8.1 64-bit system. It sets up the necessary environment for working with OpenGL and GLUT in CodeBlocks IDE.

## Features

- Installs GLUT library and configuration files for CodeBlocks.
- Copies required DLLs, libraries, and headers to the appropriate directories.
- Configures the `CodeBlocks` IDE with OpenGL and GLUT templates.
- Tested on **Windows 8.1 64-bit** system with **CodeBlocks MinGW V20.03**.

## Prerequisites

Before running the installer, make sure you have the following:

- **CodeBlocks MinGW V20.03** installed.
- **Administrator privileges** for running the script.
- **64-bit Windows OS**.
  
Ensure the following before proceeding:
1. **CodeBlocks MinGW** version **V20.03** is installed.
2. This script must be run with **Administrator privileges**.
3. You are running this on a **64-bit Windows OS**.

## Installation Instructions

1. **Download and Extract**:
   - Download the script from the [GitHub repository](https://github.com/kztanvir/).
   - Extract the files to a folder on your system.

2. **Run the Script**:
   - Right-click on the `install.bat` file and select **Run as Administrator**.

3. **Script Execution**:
   - The script will automatically copy the required files to the appropriate directories.
   - It will create a folder named `GL` in your CodeBlocks installation directory.
   - It will copy the necessary `freeglut.dll`, libraries, and header files to CodeBlocks directories.

4. **Final Step**:
   - After the script completes, open **CodeBlocks** and check that OpenGL and GLUT templates are now available.

## Troubleshooting

- If the script does not work, ensure you have **CodeBlocks MinGW V20.03** installed correctly.
- If you encounter any errors related to missing files or directories, verify the folder paths in the script.
  
## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

**Created by**: MD. Kamruzzaman Tanvir  
**GitHub**: [https://github.com/kztanvir/](https://github.com/kztanvir/)
