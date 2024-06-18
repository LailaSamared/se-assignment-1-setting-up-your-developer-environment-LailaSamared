Developer Environment Setup Documentation

This document provides detailed step-by-step instructions for setting up a developer environment, from installing an operating system to configuring necessary tools and services.

## 1. Installing Windows 11

### Step-by-Step Instructions:
1. Go to the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
2. Click "Download Now" to get the Installation Assistant.
3. Run the Installation Assistant and follow the prompts to upgrade your current OS to Windows 11.
4. Restart your computer when the installation is complete.

### Screenshot:
![Screenshot_2024-06-15-11-28-22-358](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/f8847cbc-b8f3-447f-b6f1-68ee43d8f7f1)

## 2. Installing Visual Studio Code

### Step-by-Step Instructions:
1. Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download).
2. Select the appropriate installer for Windows.
3. Run the installer and follow the prompts to complete the installation.

### Screenshot:
![Screenshot_2024-06-15-11-29-58-261](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/cfcb0e0f-b477-4197-a594-feed9d4f0d9e)

## 3. Set Up Version Control System

### Installing Git:
1. Go to the [Git download page](https://git-scm.com/downloads).
2. Download the Windows installer and run it.
3. Follow the installation steps, accepting the default options.

### Configure Git:
1. Open Git Bash (installed with Git).
2. Set your username and email:
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "youremail@example.com"
    ```

### Create a GitHub Account:
1. Go to [GitHub](https://github.com).
2. Click "Sign Up" and follow the instructions to create an account.

### Initialize a Git Repository:
1. Create a new directory for your project.
    ```bash
    mkdir my_project
    cd my_project
    ```
2. Initialize a Git repository:
    ```bash
    git init
    ```
3. Create a sample file and make your first commit:
    ```bash
    echo "# My Project" > README.md
    git add README.md
    git commit -m "Initial commit"
    ```

### Screenshot:
![Screenshot (62)](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/e96499f7-9081-4633-81e3-a2779661f9d1)

## 4. Installing Python

### Step-by-Step Instructions:
1. Go to the [Python download page](http://www.python.org).
2. Download the latest installer for Windows.
3. Run the installer and make sure to check "Add Python to PATH".
4. Follow the installation prompts.

### Screenshot:
![Screenshot (63)](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/be52cb5a-9c8c-4f05-b43f-7633006c8457)

## 5. Install Package Managers (pip)

### Step-by-Step Instructions:
1. Pip is installed by default with Python. Verify pip installation:
    ```bash
    pip --version
    ```

### Screenshot:
![Screenshot (64)](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/77601db6-65f0-4753-bc72-3bda1fc83f3a)

## 6. Configure a Database (MySQL)

### Step-by-Step Instructions:
1. Go to the [MySQL Installer download page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. Download the installer and run it.
3. Follow the installation prompts, selecting "Developer Default".
4. Configure MySQL server as per your preference during setup.

### Screenshot:
![Screenshot_2024-06-15-11-39-36-299](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/748794f0-9ca1-4af3-ae72-c5a207ff4cd2)

## 7. Set Up Development Environments and Virtualization (Optional)

### Docker Installation (Optional):
1. Go to the [Docker Desktop download page](https://www.docker.com/products/docker-desktop).
2. Download and run the installer.
3. Follow the installation prompts and start Docker Desktop.

### Screenshot:
![Screenshot_2024-06-15-11-45-45-470](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/50c9aea1-85c5-4145-8588-ca1afce6a898)

## 8. Explore Extensions and Plugins

### Visual Studio Code Extensions:
1. Open Visual Studio Code.
2. Go to the Extensions view by clicking the Extensions icon or pressing `Ctrl+Shift+X`.
3. Search and install the following extensions:
    - Python
    - GitLens
    - Docker
    - Prettier - Code formatter

### Screenshot:
![Screenshot (67)](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/5089f3e7-60eb-46a1-b578-23d73057539d)
![Screenshot (66)](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/b429cb81-77df-4a02-9304-e41f447bc8fc)
![Screenshot (65)](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/bf45349c-23c3-45f7-846d-3a6f78b10ea3)
![Screenshot (68)](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/d14b9941-1ead-4104-b1a0-2be19a979b36)


## 9. Document Your Setup

### Comprehensive Document:
*You are reading the comprehensive document right now.*

### GitHub Repository:
1. Create a new repository on GitHub.
2. Push your local repository to GitHub:
    ```bash
    git remote add origin https://github.com/yourusername/my_project.git
    git push -u origin master
    ```

### Screenshot:
![Screenshot (69)](https://github.com/LailaSamared/se-assignment-1-setting-up-your-developer-environment-LailaSamared/assets/133321338/78b72c11-14fe-4740-8523-355d371b4d3c)

## 10. Reflection on Challenges

### Challenges Faced:
1. **Windows 11 Installation**: Ensuring compatibility with existing hardware.
2. **Git Configuration**: Correctly setting up global configurations.
3. **MySQL Configuration**: Adjusting settings for optimal performance.

### Strategies to Overcome:
1. **Compatibility Checks**: Verified hardware compatibility on Microsoft's website before upgrading.
2. **Git Documentation**: Followed Git's official documentation for proper setup.
3. **MySQL Documentation**: Used MySQL's official setup guides for best practices.
