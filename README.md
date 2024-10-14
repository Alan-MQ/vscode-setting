# VSCode File Preview Feature

### Purpose
This project aims to provide a file preview feature for Visual Studio Code, similar to the Telescope feature in Neovim.

### Usage
1. **Setup CSS and JS Files**  
   Place the CSS and JS files in a directory of your choice.

2. **Update User Settings**  
   Open your `settings.json` file by pressing `Cmd + Shift + P` and add the following configuration:

   ```json
   {
       "vscode_custom_css.imports": [
           "file:///Users/alan/replace-your-own-file-path.css",
           "file:///Users/alan/replace-your-own-file-path.js"
       ]
   }
   ```

   Make sure to replace the file paths with the actual paths to your CSS and JS files.

3. **Install Required Plugin**  
   Install the **Custom CSS and JS Loader** extension from the VSCode marketplace.

4. **Enable Custom CSS and JS**  
   After installing the plugin, press `Cmd + Shift + P`, type in **Enable Custom Css And JS**, and select it to activate your custom styles and scripts.

Now you can experience the file preview feature!

### Contribution
I gathered this code from various blogs and ChatGPT. This repository could benefit from your contributions! Any thoughts or improvements are welcome!
