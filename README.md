# Markdown_to_Google_Doc1
Markdown to google doc procedure
# How to Work with Google Docs and App Script

## Creating a Google Docs Document

Creating a Google Docs document is a simple process that you can accomplish from your web browser. Here's a step-by-step guide:

1. **Go to Google Docs:**
   - Open your web browser and navigate to Google Docs.

2. **Sign In:**
   - If not already signed in, sign in to your Google Account. If you don't have an account, you can create one.

3. **Access Google Docs:**
   - Once signed in, you'll be redirected to Google Docs. If not, click the grid icon in the top right corner and select "Docs."

4. **Create a New Document:**
   - Click on the "+ Blank" button to create a new, empty Google Docs document.
   - Alternatively, choose a template from the gallery for a pre-designed document.

5. **Start Editing:**
   - The new document opens in the editor, where you can type, format text, add images, and more.

6. **Name Your Document:**
   - Click on "Untitled document" at the top to give it a name. Enter the desired name and press "Enter."

7. **Save and Access Later:**
   - Google Docs automatically saves changes. To access later, go to Google Docs and find it in the list of documents.

That's it! You've created a new Google Docs document, ready for collaboration and access from any device.

## Opening App Script in Google Docs

To open Google Apps Script from within Google Docs, follow these steps:

1. **Open Google Docs:**
   - Open your web browser and go to Google Docs.
   - Sign in to your Google Account if not already signed in.

2. **Access Script Editor:**
   - Open the document where you want to create or edit a script.
   - In the menu, go to "Extensions" > "Apps Script."

3. **Script Editor:**
   - This opens the Google Apps Script editor in a new tab.

## Copying and Pasting Markdown Content to App Script

To copy and paste and run a Markdown file content to App Script, follow these steps:

1. **Open the Markdown File:**
   - Open the Markdown file using a text editor like Notepad or Visual Studio Code.

2. **Copy Content:**
   - Select all content (Ctrl + A on Windows or Command + A on Mac) and copy (Ctrl + C on Windows or Command + C on Mac).

3. **Open Google Apps Script Editor:**
   - Go to [https://script.google.com](https://script.google.com), select your project, and open the script editor.

4. **Create or Open Script File:**
   - Create a new script file or open an existing one.

5. **Paste Content:**
   - In the script editor, click where you want to paste and paste the content (Ctrl + V on Windows or Command + V on Mac).

6. **Review and Adjust:**
   - Review and adjust formatting if needed.

7. **Save the Script:**
   - Save using the script editor's options.

8. **Run the Function:**
   - Click the play button (▶️) or right-click on the function and select "Run."

9. **Authorize the Script:**
   - If needed, authorize the script.

10. **Review Logs:**
    - Check logs by going to "View" > "Logs" in the script editor.

11. **Navigate Back to Google Doc:**
    - Go back to your Google Doc by clicking the tab on the left of the App Script.

Now you've successfully copied and run Markdown content in App Script from your Google Doc.


# Steps to contribute and edit codes using the Github website’s UI:


### Fork the Repository:

1. **Navigate to the Repository:**
   - Click your GitHub profile icon on the top right corner
   - Select Your Repositories from the drop-down menu
   -Go to the GitHub repository that you want to contribute to.


2. **Fork the Repository:**
   - Click the "Fork" button in the top right corner of the repository's page.
   - This creates a copy (fork) of the repository in your GitHub account.


### Clone the Forked Repository:

3. **Clone the Forked Repository:**
   - Open a terminal or command prompt on your local machine.
   - Use the `git clone` command to clone the forked repository to your machine.

   ```bash
   git clone https://github.com/your-username/forked-repository.git
   ```

### Create a Branch:

4. **Create a New Branch:**
   - Navigate to the cloned repository on your local machine.
   - Create a new branch for your changes.


   ```bash
   git checkout -b feature-branch
   ```

   Replace "feature-branch" with a descriptive name for your branch.

### Make Changes:

5. **Make Changes Locally:**
   - Open the project files using a code editor.
   - Make the necessary changes to the code.

### Commit Changes:

6. **Commit Changes:**
   - Save your changes and return to the terminal.
   - Use the following commands to commit your changes.

   ```bash
   git add .
   git commit -m "Description of changes"
   ```

### Push Changes to Your Fork:

7. **Push Changes to Your Fork:**
   - Push your changes to your forked repository on GitHub.

   ```bash
   git push origin feature-branch
   ```

### Create a Pull Request:

8. **Open a Pull Request:**
   - Visit your forked repository on GitHub.
   - Click on the "Pull Requests" tab.
   - Click the "New Pull Request" button.
   - Choose the branch you created as the base and compare branches.

### Submit the Pull Request:

9. **Describe Changes and Submit:**
   - Write a clear and descriptive title for your pull request.
   - Provide additional details in the comment box about the changes you made.
   - Click the "Create Pull Request" button.

### Collaborate and Discuss:

10. **Collaborate and Discuss:**
    - Engage in any discussions or feedback provided by maintainers or contributors.
    - Make additional changes if required based on the feedback.

### Merge the Pull Request:

11. **Merge the Pull Request:**
    - Once your changes are approved and ready to be merged, a repository maintainer can merge your pull request.

12. **Delete the Branch (Optional):**
    - After your changes are merged, you can delete the branch locally and on your forked repository.

    ```bash
    git branch -d feature-branch
    git push origin --delete feature-branch
    ```

Congratulations! You've successfully contributed to a GitHub repository using the website's UI. Keep in mind that the process might vary slightly based on the repository's specific guidelines and structure.

