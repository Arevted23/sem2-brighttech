# How to use Git for development

To manage the development of the webpage using Git, follow these steps:

1. **Initialize a new Git repository**:

   ```sh
   git init
   ```

2. **Add files to the repository**:

   ```sh
   git add .
   ```

3. **Commit changes**:

   ```sh
   git commit -m "Initial commit"
   ```

4. **Create a new branch for a feature**:

   ```sh
   git checkout -b feature-branch
   ```

5. **Merge the feature branch back to the main branch**:
   ```sh
   git checkout main
   git merge feature-branch
   ```
