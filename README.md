# Example Git Repository

We are learning how to make commits.

1. make some changes
2. git add -- "stage" the changes that we want to persist to our git history
3. git commit -m "adding ..." == creates a commit

To create a Git workflow with pull requests, follow these steps:

1. Fork the repository: If you don't have write access to the original repository, fork it to your own GitHub account.

2. Clone the repository: Clone the forked repository to your local machine using the following command:
    ```
    git clone <forked_repository_url>
    ```

3. Create a new branch: Create a new branch for your changes using the following command:
    ```
    git checkout -b <branch_name>
    ```

4. Make and commit your changes: Make the desired changes to the codebase and commit them using the following commands:
    ```
    git add .
    git commit -m "Your commit message"
    ```

5. Push the branch: Push the branch to your forked repository using the following command:
    ```
    git push origin <branch_name>
    ```

6. Create a pull request: Go to the original repository on GitHub and create a new pull request from your branch. Provide a clear description of your changes and submit the pull request.

7. Review and address feedback: Wait for the repository maintainers to review your pull request. If there are any requested changes, make the necessary updates and push them to your branch.

8. Merge the pull request: Once your pull request is approved, it can be merged into the main branch of the original repository.

Remember to regularly sync your forked repository with the original repository to keep your local copy up to date.
