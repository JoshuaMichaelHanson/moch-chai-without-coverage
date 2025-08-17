# CS 633 Mocha Chai Without Coverage
**Hello and welcome to the wonderful world of unit testing!**  
Using the JavaScript test framework [Mocha](https://mochajs.org/) and BDD/TDD assertion library [Chai](https://www.chaijs.com/) we will execute 
tests for the classic game rock-paper-scissors. This is a simple example that does not contain code coverage.  
In the next example we will expand on this and show how to add another library that will allow us to see how much 
of our code is covered by tests.  
  
## Getting Started

### Preferred Method: GitHub Codespaces

GitHub Codespaces provides a complete, configurable dev environment in the cloud that works with your GitHub repository. This is the **preferred method** for working with this project as it will make the next assignment easier to complete.

To use GitHub Codespaces:

1. Fork the repository to your personal GitHub account: click the "Fork" button at the top-right of the linked repository page and wait for the fork to be created. Important: do NOT create a Codespace on the original linked project — you must create the Codespace on your own forked repository.
2. Navigate to your forked GitHub repository in your browser
3. Click on the green "Code" button
4. Select the "Codespaces" tab
5. Click on "Create codespace on main"
6. Wait for the codespace to initialize (this may take a minute)
7. Once loaded, you'll have a fully configured VS Code environment in your browser
8. You can run and test the application directly from the codespace

### Alternative Method: Clone Repository Locally

If you prefer to work locally:

1. Ensure you have Git installed on your machine
2. Open your terminal or command prompt
3. Clone the repository using:
   ```
   git clone https://github.com/yourusername/repository-name.git
   ```
4. Navigate to the project directory:
   ```
   cd repository-name
   ```

## How to run ##
You can view the app by opening index.html directly in a browser, but for live reload and a better development experience we recommend using the Live Preview extension from Microsoft in VS Code (works in both GitHub Codespaces and local VS Code).

Using Live Preview (Codespaces or local VS Code)
1. Open the project in VS Code (in Codespaces this is the environment that opens after creating your codespace; locally open the repository folder).
2. Install the Live Preview extension:
   - Open the Extensions view (click the square icon in the Activity Bar or press Ctrl+Shift+X).
   - Search for "Live Preview (Microsoft)" and select the extension published by Microsoft.
   - Click "Install".
3. Start the preview:
   - Open index.html in the editor.
   - Use one of the following to launch the preview:
     - Right-click inside the editor and choose "Open with Live Preview" (if available), or
     - Open the Command Palette (Ctrl+Shift+P) and run "Live Preview: Show Preview" to open an in-editor preview, or "Live Preview: Open in Browser" to open an external browser tab.
4. View the site:
   - Live Preview will open a preview pane or a browser tab showing the site. In Codespaces the preview may use a forwarded port — if so, open the Ports panel in Codespaces and click the forwarded port's "Open in Browser" action.
5. Live reload:
   - Edit files in the project and save; Live Preview will update the preview so you can see changes instantly.

Alternative: Open index.html directly
- You can always open index.html by double-clicking the file or using your browser's "Open File" option, but you won't get automatic live reload or the integrated preview experience.

Make changes and see them instantly in the Live Preview!
  
Cheers!