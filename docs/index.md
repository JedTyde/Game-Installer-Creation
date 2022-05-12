## Game Installer Creation

Research about Setup Installer Projects.

Hi, I'm Jose, a student in CITM. This is a class for Project2 subject.

### Installation

Installation is the configuration of a software or hardware with a view to making it usable with the computer.

Installation typically involves code (program) being copied/generated from the installation files to new files on the local computer for easier access by the operating system, creating necessary directories, registering environment variables, providing separate program for un-installation etc.

There are different types of installations:

-**Attended installation**

Most common form of installation. An installation process usually needs a user who attends it to make choices, specifying preferences such as the installation location, supplying passwords or assisting in product activation. For instance, if the disk in which the computer program is being installed was full, the installer may ask the user to specify another target path or clear enough space in the disk.

-**Silent installation**

Installation that does not display messages or windows during its progress. All silent installations are unattended but not all unattended installations are silent. Malware and viruses can be installed silently when a person clicks on a link while working at a business they think is real but is a hacker's program download. Silently installing a software can be used to deploy a program on networks in educational institutions.

-**Unattended installation**

Installation that is performed without user interaction during its progress or with no user present at all. One of the reasons to use this approach is to automate the installation of a large number of systems. An unattended installation either does not require the user to supply anything or has received all necessary input prior to the start of installation.

-**Headless installation**

Installation performed without using a computer monitor connected. In attended forms of headless installation, another machine connects to the target machine and takes over the display output.

-**Scheduled or automated installation**

Process that runs on a preset time or when a predefined condition transpires.

-**Clean installation**

Is done in the absence of any interfering elements such as old versions of the computer program being installed or leftovers from a previous installation.

-**Network installation**

Network installation, is an installation of a program from a shared network resource that may be done by installing a minimal system before proceeding to download further packages over the network. This may simply be a copy of the original media but software publishers which offer site licenses for institutional customers may provide a version intended for installation over a network.

### Packaging

Packaging is the creation of an executable (or file used by a service) that contains the files, registry and logic to install an application onto a device.
This packages must be prepared and meet the installation requirements for an specific environment.

There are different packaging format, like:
- **Microsoft Windows Installer**: Setup.msi
- **Legacy executables**: Setup.exe
- **Windows store**: appx
- **Batch files**: Install.vbs/bat
- **Loose Files / Raw Files**
- **.dll / .xla /.xlam / .ppam / .dotm, etc…**

### Advantages of packaging

What are the benefits of packaging?

- Simple installation, and simplicity in working with simple files.
- It is more ergonomic and easy to use.
- It provides an upgrade and patch features for new versions, as well as uninstalling and cleaning the system when removing the software.
- It has the digital certification of the application.
- Prevents piracy.

### Microsoft Windows Installer

Microsoft now provides the Microsoft® Windows® Installer (MSI) service as part of its desktop operating systems. It resides on workstations and controls installing, uninstalling, patching, and repairing of software.

The MSI Packaged Installation usually takes place in two phases: Acquisition & Execution.

The acquisition is divided into two phases, the first phase collects the information from the user and the second phase acquires the information from the MSI database. 

When the required information is collected from the user and the database, the MSI executes the Installation script and kicks off the installation of components. 

![image](https://user-images.githubusercontent.com/59925703/167963932-9dfde400-41b9-4ee4-9dec-814f46a404c5.png)

### Installer tools

There are several types of installer tools that can be used with a full functionality, for example:

-InstallShield: 

Good  management, localization and automation features. Best for complex products. It also has a well-integrated GUI. Best for small development teams.

![image](https://user-images.githubusercontent.com/59925703/167965671-1ad070ad-88ca-4d01-b9e7-a7d57877b95d.png)

-Advanced Installer: 

A lot of features. Compiles all kinds of setups and supports all new technologies. Support for App-V. Best for corporate teams.

![image](https://user-images.githubusercontent.com/59925703/167965634-998b0922-bb8b-4bd7-8b06-862d5ebaee5d.png)

-NSIS: 

Small and fast package bundler, one of the best installers with compression methods and fully customizable, from interfaces to wizards.Compatible with all Windows versions. Mainly script based and supports plug-ins.

![image](https://user-images.githubusercontent.com/59925703/167965608-98ce9d73-7fb8-4153-a109-40fd6d0612af.png)

-Inno Setup: 

Lot of features and fully customizable. Inno also supports digital signing and uses 7-zip LZMA/LZMA2 file compression. Mainly script based.

![image](https://user-images.githubusercontent.com/59925703/167965567-70b3c9df-e48a-48e7-8e50-8c9994698abe.png)

-WiX: 

Text source files. It has unnecessary to store the source as a binary. This helps a lot when working in different branches, versions, and merging. It has full integration in Visual Studio.

![image](https://user-images.githubusercontent.com/59925703/167965520-552b63ed-0d3f-4e22-9e14-6e71262beddc.png)

### WIX
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JedTyde/Game-Installer-Creation/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
