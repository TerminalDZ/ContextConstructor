# ContextConstructor

[![Made with HTML, CSS, JS](https://img.shields.io/badge/Made%20with-HTML%2C%20CSS%2C%20JS-orange?style=for-the-badge&logo=html5)](https://shields.io/)

**ContextConstructor** is a versatile web-based utility designed to help you consolidate and organize code and text from multiple files and folders into a single, structured output. This is particularly useful for preparing comprehensive context for AI models, especially when dealing with project structures or file types not natively supported by direct uploads to AI platforms (e.g., PHP projects).

---

## Key Features 🚀

* **Multiple Input Methods:**
    * **Select Folder:** Upload an entire folder, and the tool will recursively fetch all files, maintaining their relative paths.
    * **Select Files:** Upload individual files.
    * **Manual Path Entry:** Specify a custom path for a file and then attach the corresponding file.
* **Folder Base Path Customization:** When adding a folder, you can specify a base path prefix that will be prepended to all files from that folder, allowing for accurate representation of project structures.
* **Drag & Drop Reordering:** Easily reorder the added files in the list to control their sequence in the final output.
* **Individual Path Editing:** Modify the path of any file after it has been added to the list.
* **Duplicate File Prevention:** Automatically ignores duplicate files based on their paths.
* **Clear & Manage:** Options to remove individual files or clear the entire list.
* **Combined Output:** Generates a single text block with each file's content prefixed by its name/path.
* **Copy to Clipboard:** Easily copy the entire combined output.
* **User-Friendly Interface:** Clean, intuitive, and responsive design.

---

## How ContextConstructor Helps You (Especially with AI) 🤖

Modern AI models, like large language models (LLMs), often require a significant amount of context to understand and generate relevant code, explanations, or documentation. However, directly uploading entire complex projects or certain file types (like PHP, server configurations, etc.) to these AI platforms can be challenging or unsupported.

**ContextConstructor bridges this gap by:**

1.  **Consolidating Project Code:** You can select an entire project folder (e.g., a PHP backend, a JavaScript frontend, or a mix). The tool will extract all file contents.
2.  **Preserving Structure (with Paths):** By including the file paths in the output, you provide the AI with crucial information about the project's architecture and how files relate to each other. This is vital for the AI to understand imports, dependencies, and the overall flow.
    * *Example:* Instead of just pasting PHP code, the AI sees `includes/config.php: [PHP code here]`, which gives it context.
3.  **Handling Unsupported File Types:** If an AI platform doesn't allow `.php` or `.env` uploads, you can use ContextConstructor to read these files and include their content in the text prompt.
4.  **Creating Large, Coherent Prompts:** You can combine code from various parts of your application (backend, frontend, database schema, configuration files) into one structured text block. This allows you to ask the AI more complex questions or request comprehensive tasks that span multiple components.
5.  **Selective Inclusion:** You can choose which files and folders to include, tailoring the context specifically for the AI task at hand.
6.  **Controlled Ordering:** The order in which files appear can influence the AI's understanding. You can reorder files as needed.

---

## Use Cases 💡

* Generating documentation for an entire project.
* Asking an AI to refactor code across multiple files.
* Explaining a complex bug that involves interactions between different modules.
* Getting an AI to write unit tests based on existing code.
* Migrating code from one framework/language to another by providing the full source context.
* Preparing a "knowledge base" from your project files for a custom AI assistant.

---

## How to Use 🛠️

1.  **Add Files/Folders:**
    * Click "**Select Folder**" to upload an entire directory. You'll be prompted to confirm or set a base path for these files.
    * Click "**Select Files**" to upload one or more individual files.
    * Use the "**Or enter path manually**" section to type a desired path (e.g., `src/utils/helpers.js`), then click "**Attach File to Path**" to select the actual file for that path.
2.  **Manage File List:**
    * The added files will appear in the "**Added Files**" list. The number of files is displayed.
    * **Drag and drop** files to reorder them.
    * Click the **pencil icon** (Edit Path) next to a file to change its displayed path.
    * Click the **cross icon** (Remove File) next to a file to remove it.
    * Click "**Clear All**" (and confirm) to remove all files from the list.
3.  **Combine Content:**
    * Once your files are added and ordered, click the "**Combine & Display Content**" button.
4.  **View and Copy Output:**
    * The combined content will appear in the "**Combined Output**" textarea, with each file's content prefixed by its path.
    * Click the "**Copy**" button to copy the entire output to your clipboard.
5.  **Paste into AI:**
    * You can now paste this structured text into your preferred AI model's input prompt.

---

## Contributing 🤝

Contributions are welcome! If you have suggestions for improvements or find any bugs, please feel free to open an issue or submit a pull request on the project's repository (if applicable).

---

## Author 🧑‍💻

This tool was created by **Idriss Boukmouche**.
