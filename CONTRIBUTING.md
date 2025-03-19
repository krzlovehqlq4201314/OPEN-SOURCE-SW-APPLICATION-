# Contributing to Open Source Practice

Thank you for your interest in this project and want to contribute! Here's a guide to contributing to this project to help you better participate.

## Contribution process

1. **Open or Review Issue**
- Before you begin, you can review existing issues or raise new ones to make sure your ideas don't duplicate existing work.
2. **Fork this repository**
- Click the "Fork" button in the top right corner of the repository to copy the project to your GitHub account.
3. Create a new branch
```bash
git checkout -b feature/my-new-feature
Make changes and submit
bash

git add .
git commit -m "feat: add a new feature"
Please follow the submission guidelines below.
Push to your branch
bash

git push origin feature/my-new-feature
Initiate a pull request
Click "Pull Request" in your GitHub repository and select the main branch (main or master) that you want to merge into this project.
Submission Information Specification
To make the project history clearer, we recommend using the following commit message format (with a type prefix before the commit message):

feat: New feature
fix: Fix bugs
docs: Document modifications
style: Code style adjustment (does not affect functionality)
refactor: Code refactoring
test: test-related
chore: Changes to build or assist tools

bash

git commit -m "feat: add user login function"
Code style
Indentation uses 2 spaces
Functions and variable names use camelCase
The class name uses PascalCase
Constants use UPPER_SNAKE_CASE
Try to make sure that your code passes the self-test before committing, or indicate the parts that need help testing in the Pull Request
Testing and code review
If the project has a test script, you can run the tests before committing to make sure all the tests pass.
After the Pull Request is submitted, the maintainer will review the code and may suggest changes.
Code of Conduct
Please be respectful and inclusive when collaborating with others.
For more details, please refer to the community-based Code of Conduct.
