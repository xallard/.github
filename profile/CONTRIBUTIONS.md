# Contributing to Xallard and Earn Certificates for Your Achievements

Welcome to the Xallard organization's contribution program! Where students and professionals like you earn certificates based on their commitment, contributions and leadership.

Here's a step-by-step guide on how to get started on this rewarding journey.

## Getting Started

### Fork the Repository

1. Visit the repository you would like to improve here [https://github.com/orgs/xallard/repositories](https://github.com/orgs/xallard/repositories)

2. Click the "Fork" button at the top right corner of the repository. This will create a copy of the repository in your GitHub account.

### Clone Your Fork

3. Open your terminal or command prompt.

4. Clone your forked repository to your local machine using the following command:

   ```shell
   git clone <your-forked-repository-git-url>
   ```

5. Change your current directory to your cloned directory:

   ```shell
   cd <your-forked-repository-folder>
   ```

6. Set the upstream repository to keep your fork in sync with the original repository:

   ```shell
   git remote add upstream <original-repository-git-url>
   ```

## Making Changes

### Create a Branch

7. Before making changes, create a new branch with a meaningful name related to your contribution. For example, to fix issue #342, you might create a branch like this:

   ```shell
   git checkout -b fix-login-issue-342
   ```

   Replace `fix-login-issue-342` with a descriptive branch name for your specific task.

   Examples:

   ```
   git checkout -b fix-user-authentication-123
   ```

   ```
   git checkout -b fix-database-connection-456
   ```

   ```
   git checkout -b feature-add-user-profile-789
   ```

   ```
   git checkout -b feature-implement-search-101
   ```

   ```
   git checkout -b enhancement-optimize-performance-202
   ```

   ```
   git checkout -b enhancement-improve-ux-303
   ```

   ```
   git checkout -b docs-update-install-guide-404
   ```

   ```
   git checkout -b docs-translate-user-manual-505
   ```

   ```
   git checkout -b refactor-restructure-code-606
   ```

   ```
   git checkout -b refactor-simplify-algorithms-707
   ```

   ```
   git checkout -b style-improve-formatting-808
   ```

   ```
   git checkout -b style-standardize-css-909
   ```

   ```
   git checkout -b test-add-unit-tests-1010
   ```

   ```
   git checkout -b test-implement-integration-tests-1111
   ```

   ```
   git checkout -b chore-update-dependencies-1212
   ```

   ```
   git checkout -b chore-clean-up-code-1313
   ```

   ```
   git checkout -b breaking-introduce-api-v2-1414
   ```

   ```
   git checkout -b breaking-remove-deprecated-1515
   ```

   ```
   git checkout -b security-patch-vulnerability-1616
   ```

   ```
   git checkout -b security-audit-and-fixes-1717
   ```

   ```
   git checkout -b revert-undo-feature-1818
   ```

   ```
   git checkout -b revert-rollback-hotfix-1919
   ```

### Commit Your Changes

8. Make your changes to the code. Ensure that your changes are clear, concise, and address the issue or feature you are working on.

9. Once your changes are complete, commit them with a descriptive commit message. For example:

   ```
   git commit -m "[fix issue #342]: Update the login form validation"
   ```

   Ensure the commit message starts with the issue number and a brief description of the change.

   Examples:

   ```
   git commit -m "[fix issue #12345]: Fix authentication bug"
   ```

   ```
   git commit -m "[feature issue #67890]: Implement user profile functionality"
   ```

   ```
   git commit -m "[enhancement issue #54321]: Optimize server performance"
   ```

   ```
   git commit -m "[docs issue #98765]: Update installation guide"
   ```

   ```
   git commit -m "[refactor issue #23456]: Simplify code structure"
   ```

   ```
   git commit -m "[style issue #78901]: Improve code formatting"
   ```

   ```
   git commit -m "[test issue #34567]: Add unit tests for login"
   ```

   ```
   git commit -m "[chore issue #45678]: Update project dependencies"
   ```

   ```
   git commit -m "[breaking issue #12312]: Introduce API v2"
   ```

   ```
   git commit -m "[security issue #56789]: Patch security vulnerability"
   ```

   ```
   git commit -m "[revert issue #89012]: Revert feature XYZ"
   ```

   These commit messages are written in a professional style and include references to specific issues by their numbers, making it clear which issues were addressed with each commit.

### Push Your Branch

10. Push your branch to your fork on GitHub:

    ```shell
    git push origin fix-login-issue-342
    ```

## Submitting Your Contribution

### Create a Pull Request

11. Visit your forked repository on GitHub

12. Click the "New Pull Request" button.

13. In the base branch option, select the branch to which you want to merge your changes to, in our case choose the `main` branch.

14. In the compare branch, select the branch from your forked repository that you created earlier, in our case `fix-login-issue-342`.

15. Provide a clear and concise title for your pull request. For example:

    ```
    [Fix Issue #342]: Update the login form validation
    ```

    Make sure to include the issue number in the title and use one of our prefixes

    ```
    [Fix Issue #12345]: Resolve critical authentication bug
    ```

    ```
    [Fix Issue #56789]: Address database connectivity issue
    ```

    ```
    [Fix Issue #98765]: Correct UI rendering glitch
    ```

    ```
    [Feature Issue #54321]: Implement user profile functionality
    ```

    ```
    [Feature Issue #67890]: Introduce advanced search feature
    ```

    ```
    [Feature Issue #34567]: Add real-time notifications
    ```

    ```
    [Enhancement Issue #24680]: Optimize server performance
    ```

    ```
    [Enhancement Issue #13579]: Enhance user experience with animations
    ```

    ```
    [Enhancement Issue #11223]: Improve error handling for better user feedback
    ```

    ```
    [Docs Issue #11111]: Update installation guide for clarity
    ```

    ```
    [Docs Issue #22222]: Expand API documentation with examples
    ```

    ```
    [Docs Issue #33333]: Translate user manual into multiple languages
    ```

    ```
    [Refactor Issue #44444]: Restructure code for modularity
    ```

    ```
    [Refactor Issue #55555]: Simplify complex algorithms
    ```

    ```
    [Refactor Issue #66666]: Rename variables for consistency
    ```

    ```
    [Style Issue #77777]: Improve code formatting and indentation
    ```

    ```
    [Style Issue #88888]: Standardize CSS class names
    ```

    ```
    [Style Issue #99999]: Enhance visual design for readability
    ```

    ```
    [Test Issue #12121]: Add comprehensive unit tests for authentication
    ```

    ```
    [Test Issue #23232]: Enhance test coverage for API endpoints
    ```

    ```
    [Test Issue #34343]: Implement automated integration tests
    ```

    ```
    [Chore Issue #45454]: Update project dependencies
    ```

    ```
    [Chore Issue #56565]: Clean up unused code and resources
    ```

    ```
    [Chore Issue #67676]: Reorganize project structure for better maintainability
    ```

    ```
    [Breaking Issue #78787]: Introduce breaking changes for API v2
    ```

    ```
    [Breaking Issue #89898]: Remove deprecated features
    ```

    ```
    [Breaking Issue #90909]: Restructure data storage format
    ```

    ```
    [Security Issue #10101]: Patch critical security vulnerability
    ```

    ```
    [Security Issue #20202]: Enhance authentication security measures
    ```

    ```
    [Security Issue #30303]: Conduct security audit and address findings
    ```

    ```
    [Revert Issue #41414]: Revert feature XYZ to previous state
    ```

    ```
    [Revert Issue #52525]: Rollback recent hotfix changes
    ```

    ```
    [Revert Issue #63636]: Undo UI redesign for stability reasons
    ```

    These titles follow a professional naming convention and indicate the nature of the changes being proposed in the respective pull requests.

16. In the pull request description, provide additional context and details about your changes. Reference the issue number again and describe what your changes aim to achieve.

17. Click the "Create Pull Request" button to submit your changes for review.

That's it! Your pull request is now submitted and will be carefully reviewed by our dedicated team of maintainers.

As you await feedback, be ready to actively participate in constructive discussions and refine your contributions to uphold the highest standards of code quality.

Welcome to Xallard!
