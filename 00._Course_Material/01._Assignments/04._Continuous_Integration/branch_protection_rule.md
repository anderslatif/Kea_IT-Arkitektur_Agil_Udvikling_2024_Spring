# Branch protection rule

Create a branch protection rule that requires at least 2 to review a pull request before being able to merge with main.

https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule

## Branch protection:

1. **⚙️ Settings**: Navigate to your repository on GitHub. Click on the "Settings" tab at the top.
2. **🌿 Branches**: In the settings menu, find and click on the "Branches" menu located on the left side.
3. **🔒 Branch Protection Rules**: Scroll down to the "Branch protection rules" section.
4. **✏️ Edit**: Find the branch you want to set rules for and click on "Edit" (or "Add rule" if you're setting this up for the first time).
5. **🔀 Require a Pull Request Before Merging**:
    - Check the option "Require a pull request before merging".
    - 🧑‍⚖️ **Required Number of Approvals**: Set the "Required number of approvals before merging" to **`2`**.
6. **✅ Require Status Checks**:
    - Check "Require status checks to pass before merging".
    - 🔍 **Search and Select Status Checks**: Search for the specific status checks you want to require and select them.
7. **💾 Save**: Once you're done setting up your rules, don't forget to save the changes.