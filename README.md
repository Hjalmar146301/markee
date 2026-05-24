# 📝 markee - See your markdown files update instantly

[![](https://img.shields.io/badge/Download_Markee-Blue?style=for-the-badge)](https://github.com/Hjalmar146301/markee/releases)

## 📖 About this application

Markee serves as a dedicated preview tool for Markdown files. It watches the files you edit in your favorite text editor. Every time you save your work, the preview window updates to show your changes. It supports rich content features like mathematical formulas through KaTeX, complex diagrams with Mermaid, and clear code highlighting for programming languages. The application hides the complexity of formatting and allows you to focus on your writing.

## 💻 System requirements

To run Markee on your computer, ensure your system meets these basic criteria:

* Operating System: Windows 10 or Windows 11.
* Memory: 4GB of RAM minimum.
* Storage: 50MB of available disk space.
* Graphics: A display with at least 1024x768 resolution.

Before you begin, verify that your Windows installation has all recent updates. This ensures the best compatibility with the software components used in the application.

## ⬇️ How to install the software

Follow these steps to set up Markee on your system.

1. Visit the [official releases page](https://github.com/Hjalmar146301/markee/releases) to access the installer.
2. Locate the file ending in `.msi` or `.exe` under the latest release section.
3. Click the filename to save the installer to your Downloads folder.
4. Open your Downloads folder and double-click the file you just saved.
5. Follow the on-screen prompts provided by the Windows installer.
6. Grant the application permission to install if a security prompt appears on your screen.

Once the installation finishes, you will find a shortcut on your desktop or in your Start menu. Click this shortcut to launch the application for the first time.

## 🚀 Getting started

After installing the application, follow this routine to start your workflow:

1. Launch the Markee application from your Start menu.
2. Select File from the top menu, then choose Open.
3. Navigate to the folder containing your Markdown files.
4. Select the file you wish to view.
5. Open that same file in your preferred text editor.
6. Type your content and press the save command in your editor.

Markee detects the save event instantly. The preview window reflects your changes without manual refreshing. It recognizes common syntax elements like headers, lists, and images.

## 🧩 Advanced features

The application includes built-in support for specialized content types often used in technical or professional documents.

### Mathematical formulas
Markee renders KaTeX expressions. Place your mathematical notation between dollar signs. For example, typing ` $E=mc^2$ ` results in a rendered equation. This saves you from using external tools to generate images of your math.

### Diagrams
The application creates diagrams using the Mermaid syntax. Define your flowcharts, sequence diagrams, or gantt charts within a code block labeled "mermaid". The application converts this text into a visual representation automatically upon saving.

### Syntax highlighting
If you include code snippets in your documents, mark them with triple backticks followed by the language name. Markee applies colors to the code text to improve readability. This helps you identify syntax errors and navigate long blocks of logic faster.

## 🛠 Troubleshooting common issues

If you encounter problems while running the application, check these common fixes:

* The preview does not update: Ensure you actually saved the file in your text editor. Some editors have an "Auto-save" feature which triggers the update frequently. If you do not have this on, you must save manually.
* The window remains blank: Check that your file extension uses `.md` or `.markdown`. The application only monitors files with these specific extensions for performance reasons.
* The application fails to launch: Restart your computer to clear any locked background processes. If it still fails, uninstall the program through the Control Panel and run the installer again.
* High memory usage: If you open a folder with thousands of deep subfolders, the application might take a moment to scan these for changes. Close unrelated background programs to free up system resources.

## 📁 Managing your workspace

Markee performs best when you keep a clean file structure. If you work on large projects, keep your Markdown files and images in the same root folder. The application maintains a small index of your files to keep performance fast. You do not need to configure anything; the application manages this index in the background. If you move your files, the application will simply re-scan the new location when you open it next.

## ⚙️ Settings and preferences

Access the settings menu by clicking the icon in the top right corner of the application window. Here you can toggle specific render features. If you do not need Mermaid diagrams, you can disable them to slightly improve loading times. You can also change the theme of the preview window to a light or dark mode depending on your work environment. These settings save automatically and will persist the next time you open the application.

## 📋 Best practices

1. Use consistent indentation in your Markdown files.
2. Keep your file names short and descriptive.
3. Avoid using spaces in file names if you intend to share your projects across different platforms.
4. Place your images in a local subfolder named "assets". Markee will resolve these relative paths without extra configuration.
5. Check the preview window periodically to ensure the application detected your file changes.

## 💬 Community and feedback

This project thrives on user feedback. If you find a feature that does not work as expected, or if you have a suggestion for improving the user interface, refer to the main repository page. You can contribute by opening a new issue in the tracker. Please provide a clear explanation of what happens and what you expected to see. Avoid including sensitive personal data in your reports. The project maintains an open nature to ensure the tool remains useful for everyone in the community.