1. GitHub Repository Creation:

  - Log in to your GitHub account.

  - Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").

  - Initialize it with a README file.


2. Local Folder Setup:

  - Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").

  - Open a terminal or command prompt and navigate to the created folder.



3. Git Initialization:

  - Initialize a new Git repository in your local folder.



4. Connecting to GitHub:

  - Link your local repository to the GitHub repository you created in Task 1.

   ```

git remote add origin <repository-url>

   ```

   Replace https://github.com/JamesMungai254/PLPBasicGitAssignment.git with the actual URL of your GitHub repository.



5. Create a File:

  - Inside your local folder, create a new text file (e.g., `hello.txt`).

  - Add a simple text message (e.g., "Hello, Git!").



6. Committing Changes:

  - Stage the changes.

   ```bash

   git add hello.txt

   ```

  - Commit the changes.

   ```bash

   git commit -m "Add hello.txt with a greeting"

   ```
7. Pushing to GitHub:

  - Push the committed changes to your GitHub repository.

   ```bash

   git push -u origin main

   ```
