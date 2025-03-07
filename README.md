# Git Assignment: Push, Pull, and Pull Requests

## Objective
This assignment will help you understand and practice essential Git commands related to pushing changes, pulling updates, and creating pull requests in a collaborative development workflow.

---

## Prerequisites
- Git installed on your machine
- A GitHub account
- Basic knowledge of Git commands
- A text editor (VS Code, Sublime, etc.)

---

## Part 1: Setting Up Your Repository
1. **Fork a Repository**  
   - Go to [GitHub](https://github.com/) and find the repository shared by your instructor.
   - Click the **Fork** button to create a copy under your own GitHub account.

2. **Clone the Forked Repository**  
   - Open your terminal or command prompt and run the following command:
     ```sh
     git clone https://github.com/your-username/repository-name.git
     ```
   - Navigate into the project directory:
     ```sh
     cd repository-name
     ```

---

## Part 2: Making Changes and Pushing to GitHub
3. **Create a New Branch**  
   - Create a new branch to work on:
     ```sh
     git checkout -b feature-branch
     ```

4. **Make Some Changes**  
   - Edit any file or create a new one.
   - Save your changes.

5. **Stage and Commit Your Changes**  
   - Add the modified files to staging:
     ```sh
     git add .
     ```
   - Commit the changes:
     ```sh
     git commit -m "Added a new feature"
     ```

6. **Push Changes to GitHub**  
   - Push your branch to your GitHub repository:
     ```sh
     git push origin feature-branch
     ```

---

## Part 3: Creating a Pull Request (PR)
7. **Open a Pull Request**  
   - Go to your repository on GitHub.
   - You should see a prompt to create a **Pull Request** (PR).
   - Click **Compare & pull request**.
   - Add a meaningful title and description.
   - Click **Create pull request**.

---

## Part 4: Fetching and Merging Updates
8. **Fetch and Pull Changes from the Original Repository**  
   - Set the upstream repository (only needs to be done once):
     ```sh
     git remote add upstream https://github.com/original-owner/repository-name.git
     ```
   - Fetch the latest changes:
     ```sh
     git fetch upstream
     ```
   - Merge updates from the main branch:
     ```sh
     git checkout main
     git merge upstream/main
     ```

9. **Push the Updated Main Branch to Your GitHub Repository**  
   ```sh
   git push origin main
   ```

---

## Submission
Once you've completed the assignment:
- Share the **link to your repository** using the email samuel.developer202@gmail.com.
- Ensure your changes follow best practices (proper commit messages, clean code, etc.).

---

## Bonus Challenge (Optional)
- Resolve merge conflicts if they arise.
- Review a classmate’s pull request and provide feedback.
- Use Git **rebase** instead of merge to update your branch.

Happy coding! 🚀
