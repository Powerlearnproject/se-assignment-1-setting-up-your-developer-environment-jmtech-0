Developer Environment Setup
Step 1: Select Your Operating System
I chose Windows 11 as the operating system for my development environment. I downloaded it from the official Microsoft website here and followed the installation instructions. The process involved creating a bootable USB drive, setting up the OS, and configuring initial settings such as user accounts and privacy preferences.
Step 2: Install a Text Editor or Integrated Development Environment (IDE)
For my coding activities, I installed Visual Studio Code (VS Code), a powerful and versatile text editor. The installation package was downloaded from Visual Studio Code's official site. After installation, I customized the editor by selecting my preferred theme and font settings to enhance readability and comfort during coding sessions.
Step 3: Set Up Version Control System
Next, I installed Git, a distributed version control system, by downloading it from the official Git website. After installation, I configured Git with my user name and email using the following commands:
git config --global user.name "Joseph" 
git config --global user.email "jmuthama352@gmail.com"

I created a GitHub account at GitHub to host my repositories. To initialize a Git repository for my sample project, I navigated to the project directory and executed the following commands:
git init 
git add .
 git commit -m "Initial commit"
I then pushed the initial commit to a new repository on GitHub.
Step 4: Install Necessary Programming Languages and Runtimes
For this setup, I installed Python, which is essential for my project, by downloading the latest version from python.org. The installation process included selecting the option to add Python to the system PATH, ensuring I can execute Python commands from any directory in the command line.
Step 5: Install Package Managers
To manage Python packages efficiently, I installed pip, which is included with Python installations. I verified the installation by running:
pip –version

Step 6: Configure a Database (MySQL)
For database management, I installed MySQL by downloading the installer from MySQL's official site. The installation process involved setting up the MySQL server, configuring a root password, and creating a new database for my project.
Step 7: Set Up Development Environments and Virtualization (Optional)
Although optional, I explored Docker to containerize my development environment, ensuring consistency across different machines. I installed Docker Desktop from Docker's official website and familiarized myself with creating and managing containers.
Step 8: Explore Extensions and Plugins
To enhance the functionality of VS Code, I installed several extensions, including:
•	Python: Provides IntelliSense, linting, and debugging capabilities for Python.
•	GitLens: Enhances Git capabilities within VS Code.
•	Prettier: Ensures consistent code formatting across my projects.
•	MySQL: Provides MySQL database management within VS Code.
Step 9: Document Your Setup
I documented the entire setup process, including the commands used, configurations made, and any troubleshooting steps encountered. For instance, I faced an issue with Git not recognizing my SSH key, which I resolved by adding the SSH key to my GitHub account using the following commands:
ssh-keygen -t rsa -b 4096 -C "jmuthama352@gmail.com" ssh-add ~/.ssh/id_rsa

Reflection
The primary challenge during the setup was configuring MySQL, as there were several options and settings to navigate during the installation process. I overcame this by consulting MySQL documentation and online forums for guidance. Another challenge was ensuring all tools and environments were correctly configured to work together seamlessly, which required careful attention to detail and some trial and error.


