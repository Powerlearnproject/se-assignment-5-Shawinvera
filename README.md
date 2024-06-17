[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15287062&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code)
Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

Questions:

1. Installation of VS Code:

   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
     Open your web browser and go to the official Visual Studio Code website: https://code.visualstudio.com/
     Click on the "Download for Windows" button. This will download the installer (VSCodeSetup.exe).
     Once the download is complete, locate the VSCodeSetup.exe file in your Downloads folder or the location where you saved it.
     Double-click on VSCodeSetup.exe to run the installer.
     The installer will launch a setup wizard. Click on "Next" to proceed
     Read and accept the license agreement. Click on "Next" to continue.
     Select the destination folder where you want to install Visual Studio Code. The default location is typically C:\Program Files\Microsoft VS Code.
     Choose the Start Menu folder where the VS Code shortcuts will be created. Click on "Next".
     Click on "Install" to begin the installation process. Wait for the setup to complete.
     Once the installation is finished, click on "Finish" to exit the setup wizard.

2. First-time Setup:

   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
     Theme: Choose a theme that you find comfortable for long coding sessions. Popular themes include "Dark+ (default dark)", "Light+", and various community themes available in the Extensions Marketplace.

Font: Select a font that is easy to read and looks good in the editor. Some commonly used fonts are "Fira Code", "Consolas", "Menlo", etc.

File Associations: Configure file associations if needed, for example, to associate specific file types with certain languages or syntaxes.

Tab Size and Indentation: Set your preferred tab size and whether to use spaces or tabs for indentation (editor.tabSize, editor.insertSpaces).

Word Wrap: Decide if you want lines to wrap automatically (editor.wordWrap).

Line Numbers: Enable or disable line numbers in the editor (editor.lineNumbers).

Code Folding: Configure settings related to code folding (editor.folding).

Auto Save: Choose how often you want VS Code to automatically save your changes (files.autoSave).

Cursor Style: Customize the cursor style (editor.cursorStyle).

Terminal Shell: Set your preferred shell for the integrated terminal (terminal.integrated.shell).

Git Integration: Check if Git is configured correctly and linked to VS Code (git.enabled).
Key Extensions
Language Support: Install extensions for languages you work with (e.g., Python, JavaScript, Java, etc.).

Debugger: If not included by default, install debugger extensions for your programming languages.

Version Control: Extensions like GitLens for enhanced Git capabilities within VS Code.

Code Formatting: Install extensions like Prettier or ESLint for automatic code formatting.

Linters: Install linters specific to your programming languages (e.g., ESLint, Flake8, etc.).

Snippets: Install extensions that provide code snippets for your programming languages or frameworks.

3.  User Interface Overview:

    - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

    1.  Activity Bar:
        Purpose: The Activity Bar is located vertically on the far left side of the window. It contains icons representing different activities and views within VS Code.
        Components:
        Explorer: Provides access to your file system and project files.
        Search: Allows searching within files or across the entire project.
        Source Control: Integrates with version control systems like Git.
        Run and Debug: Provides options for running and debugging your code.
        Extensions: Manages installed extensions and allows you to search for new ones.

              . Side Bar:

        Purpose: The Side Bar is located to the right of the Activity Bar and consists of different panels that provide various functionalities and views.
        Components:
        Explorer: Duplicates the functionality of the Explorer in the Activity Bar, showing the file system and project files.
        Search: Provides advanced search options.
        Source Control: Shows Git status and allows interaction with version control.
        Extensions: Lists installed extensions and provides options for managing them.
        Debug: Displays debug-related information and controls.
        Remote Explorer: If enabled, shows connections to remote systems

Editor Group:
Purpose: The Editor Group consists of one or more editor panes where you open and work on files.
Functionality:
Each editor pane can display a different file or even the same file in split views (horizontal or vertical).
You can switch between different files or views by clicking on tabs at the top of each editor pane.

Status Bar:
Purpose: Located at the bottom of the window, the Status Bar provides information and quick access to various settings and tools.
Components:
Language Mode: Displays the programming language associated with the current file.
Line Endings: Indicates the line ending type used in the current file (e.g., CRLF or LF).
Encoding: Shows the character encoding of the current file.
Indentation: Indicates the indentation settings of the current file.
Git Status: Shows Git branch and changes if the file is part of a Git repository.
Notifications: Displays messages, such as errors or warnings.

4. Command Palette:

   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
     The Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows users to execute various commands or actions quickly without navigating through menus or memorizing keyboard shortcuts. It provides a searchable list of all available commands, making it easy to discover and execute functionalities within VS Code
     To access the Command Palette in VS Code, you can use the following methods:

Keyboard Shortcut: Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac). This shortcut opens the Command Palette at the top center of the VS Code window.

Menu Option: Click on View in the top menu bar, then select Command Palette....

Examples of Common Tasks Using the Command Palette:
Opening Files: You can quickly open files by typing "Open File" or simply "File" in the Command Palette. This allows you to search for and open any file within your project.

Switching Between Open Files: Type "Switch Editor" or "View: Show All Editors" to see a list of all open files and switch between them.

Running Tasks: If you have defined tasks in your tasks.json file (e.g., build tasks), you can execute them by typing "Tasks: Run Task" and selecting the task you want to run.

5. Extensions in VS Code:

   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
     Role of Extensions in VS Code:
     Enhancing Language Support: Extensions add support for programming languages that are not natively supported by VS Code or enhance existing language capabilities with features like syntax highlighting, IntelliSense (code completion), and debugging.

Integration with External Tools: Extensions integrate VS Code with external tools and services such as version control systems (Git), build systems, linters, formatters, and task runners.

Customization: Extensions allow users to customize their editor's appearance and behavior, including themes, icons, and keybindings

ChatGPT
Extensions in Visual Studio Code (VS Code) play a crucial role in extending its functionality beyond the core editor features. They allow users to customize and enhance their coding experience by adding support for various programming languages, integrating with external tools, providing new themes, and more. Here's a detailed look at the role of extensions and how users can find, install, and manage them:

Role of Extensions in VS Code:
Enhancing Language Support: Extensions add support for programming languages that are not natively supported by VS Code or enhance existing language capabilities with features like syntax highlighting, IntelliSense (code completion), and debugging.

Integration with External Tools: Extensions integrate VS Code with external tools and services such as version control systems (Git), build systems, linters, formatters, and task runners.

Customization: Extensions allow users to customize their editor's appearance and behavior, including themes, icons, and keybindings.

Productivity Tools: They provide productivity tools such as code snippets, live share for collaborative coding, code refactoring support, and more.

Development Workflow: Extensions can streamline the development workflow by offering features like debugging support, testing frameworks integration, and deployment tools.

Finding, Installing, and Managing Extensions:
Finding Extensions:
Extensions Marketplace: The primary way to discover extensions is through the Extensions view in VS Code (Ctrl + Shift + X or Cmd + Shift + X). This view allows users to search for extensions by name, category (e.g., Languages, Debuggers, Themes), and sort by popularity or rating.

Installing Extensions:
Once you find an extension in the Marketplace, click on "Install" to add it to your VS Code setup.
Extensions can also be installed via the command palette (Ctrl + Shift + P or Cmd + Shift + P > "Extensions: Install Extensions").

Managing Extensions:
Enabling/Disabling: Installed extensions can be enabled or disabled via the Extensions view. Disabled extensions do not load when VS Code starts.
Updating: VS Code automatically checks for updates to installed extensions. You can manually update extensions in the Extensions view.
Uninstalling: If you no longer need an extension, you can uninstall it from the Extensions view.

6. Integrated Terminal:

   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
     Press Ctrl + ` (backtick) on Windows/Linux or Cmd + (backtick) on macOS. This shortcut toggles the integrated terminal panel at the bottom of the VS Code window.
     If you have multiple terminal instances, you can switch between them using the dropdown arrow on the right side of the terminal panel.
     Right-click inside the terminal panel to access settings such as changing the terminal shell (Select Default Shell), splitting terminals (Split Terminal), and more.
     ou can run commands directly in the terminal, such as compiling code, running scripts, executing Git commands, and more.
     The integrated terminal behaves like a regular command-line interface, allowing you to use shell commands and utilities specific to your operating system.

Advantages over External Terminals:
Integration: No need to switch between VS Code and an external terminal window, reducing context-switching and improving workflow efficiency.

Workspace Awareness: Automatically starts in the workspace directory, eliminating the need to navigate manually to project directories.

Task Integration: Easily integrate with tasks and build systems configured in VS Code, enhancing automation and task management capabilities.

7. File and Folder Management:

   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
     Creating a New File:

Click on the Explorer icon in the Activity Bar on the left side of the VS Code window (or use Ctrl + Shift + E / Cmd + Shift + E).
Right-click on the folder where you want to create the file, then select New File from the context menu. Alternatively, press Ctrl + N (Windows/Linux) or Cmd + N (macOS) to create a new file in the current directory

Creating a New Folder:

Similarly, right-click on the folder where you want to create the new folder in the Explorer, then choose New Folder from the context menu.

Opening Files:

Double-click on a file in the Explorer to open it in the editor pane. Alternatively, right-click on the file and choose Open from the context menu.
Opening Folders:

To open an entire folder in VS Code, you can either use File > Open Folder... from the top menu, or drag and drop the folder into the VS Code window. VS Code will open all files and subfolders within that directory.

Managing Files and Folders:
Renaming Files and Folders:

Right-click on a file or folder in the Explorer and select Rename from the context menu. Alternatively, you can press F2 when the file or folder is selected.
Deleting Files and Folders:

Right-click on a file or folder in the Explorer and select Delete from the context menu. Alternatively, press Delete or Backspace while the file or folder is selected.
Moving Files and Folders:

To move a file or folder, you can simply drag and drop it to a new location within the Explorer panel. VS Code will automatically update file paths and references.

Navigating Between Files and Directories Efficiently:
Using the Explorer:

The Explorer in VS Code allows you to navigate through files and folders in your workspace. You can expand/collapse directories and click on files to open them

8. Settings and Preferences:

   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
     Users can find and customize settings in Visual Studio Code (VS Code) through the Settings interface, which provides a convenient way to adjust various editor preferences, themes, keybindings, and more. Here’s how you can find and customize settings in VS Code:

   Changing the Theme:
   To Change the Theme:
   In the Settings interface, type "Color Theme" into the search bar.
   Click on the dropdown menu under "Workbench: Color Theme" in the User Settings section.
   Select a theme from the list. For example, select "Dark+ (default dark)".

Adjusting Font Size:
To Adjust Font Size:
In the Settings interface, type "Font Size" into the search bar.
Find the "Editor: Font Size" setting in the User Settings section.
Adjust the value (e.g., set it to 14) to change the font size of the editor.

Customizing Keybindings:
To Customize Keybindings:

In the Settings interface, type "Keybindings" into the search bar.
Click on "Open Keyboard Shortcuts" in the search results to open the keybindings.json file.
To customize a keybinding, click on the pencil icon next to the command you want to change, then enter your desired key combination.
For example, to change the keybinding for "workbench.action.toggleSidebarVisibility" to Ctrl + B, add the following JSON snippet: 9. Debugging in VS Code:

- Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in
  VS Code?
  Open VS Code and navigate to the folder containing your project files.
  Click on the Debug icon in the Activity Bar on the left side (or press Ctrl + Shift + D).
  Click on the gear icon (create a launch.json file) or Add Configuration... to create a launch.json file if it doesn't exist already.
  Choose the environment you want to debug (e.g., Node.js, Chrome, etc.).
  VS Code will open the launch.json file with a template configuration.
  Modify the configurations array to specify how VS Code should launch and debug your program. For example, for a Node.js program, the configuration might look like this:
  Open the file containing the code you want to debug.
  Click in the gutter next to the line number where you want to set a breakpoint. A red dot will appear, indicating a breakpoint.
  Press F5 or click the green play button next to the configuration dropdown in the Debug view to start debugging.
  VS Code will launch your program in debugging mode and stop at the breakpoints you've set.
  Use the debug toolbar to control the debugging session. This includes buttons to step through code (Step Over, Step Into, Step Out), continue execution (Continue), pause (Pause), restart (Restart), and stop (Stop).

Key Debugging Features in VS Code:
Variable Inspection: Hover over variables to see their current values, or view them in the Variables panel.

Watch Expressions: Add expressions to monitor their values as you debug.

Call Stack: View the call stack to see the path that led to the current point in the code.

Breakpoint Management: Disable, enable, and remove breakpoints directly from the editor gutter.

10. Using Source Control: - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    Launch VS Code and open the folder or workspace where your project resides.
    Initialize Git Repository:Open the Source Control view by clicking on the Source Control icon in the Activity Bar on the left (Ctrl + Shift + G).
    Click on the Initialize Repository button (+ icon) or alternatively, open the integrated terminal (Ctrl + `) and type git init to initialize a Git repository in the root of your project directory

Making Commits:
Stage Changes:

In the Source Control view, you'll see a list of changed files. Click the + icon next to each file you want to stage for the commit, or use the Stage All Changes button (+ icon next to CHANGES) to stage all changes.
Commit Changes:

Enter a commit message in the text field at the top of the Source Control view.
Press Ctrl + Enter or click the checkmark icon to commit the staged changes.

Pushing Changes to GitHub:
Link Your Repository to GitHub (if not already linked):

If your repository is not yet linked to GitHub, you can do so by clicking on the ellipsis (...) in the Source Control view and selecting Publish to GitHub.
Push Commits to GitHub:

After committing your changes locally, you can push them to GitHub.
Click on the ellipsis (...) in the Source Control view and select Push to push your committed changes to the remote repository (GitHub).
References
PLP NOTES
GOOGLE CHROME
SCREENSHOTS

Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July
