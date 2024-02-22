# How to Use Review Templates in Windows

This guide outlines the process for Windows users to utilize review templates for code and workflow reviews, including steps for copying a template and appending the current date to the filename using Windows Command Prompt (CMD) with a PowerShell command.

## Step 1: Navigate to the Template Directory

First, ensure you are in the directory where your review templates are stored. If your templates are within a `templates` directory in your repository, navigate there with:

**cmd**
`cd path\to\your\repository\templates`

Replace path\to\your\repository\templates with the actual path to your templates directory.

## Step 2: List Available Templates

To view the templates you have available, use the `dir` command.

## Step 3: Copy the Template and Append the Current Date to the Filename
After selecting the appropriate template, you can copy it to a new file in your desired directory, appending the current date to the filename for organization. Use the following PowerShell command in CMD:
`PowerShell -Command "Copy-Item 'Application-Workflow-Review-Template.md' -Destination ('..\reviews\WorkflowReview_' + (Get-Date -Format 'yyyy-MM-dd') + '.md')"`

## Completing Your Review
Once you have copied the template and named it appropriately:

- Open the new markdown file.
Fill it out with your review findings, providing detailed observations, suggestions for improvements, and any questions you have.
- Submitting Your Review on GitHub
After completing your review, submit it on GitHub to share your feedback and collaborate with your team. Here are the steps to submit your review:

#### Step 1: Add Your Review Document to Your Repository
Navigate to the directory where you want to add your review document.
Use Git commands to add your document to the repository:
**cmd**
`git add .`
Commit your changes with a descriptive message:
**cmd**
`git commit -m "Add workflow review for YYYY-MM-DD"`
Replace YYYY-MM-DD with the actual date of your review.

#### Step 2: Push Your Review to GitHub
Push your review document to GitHub:
**cmd**
`git push origin main`
Replace main with the appropriate branch name if different.

#### Step 3: Open a Pull Request
On GitHub, navigate to your repository and click on "Pull Requests".
Click "New pull request".
Select your branch and compare it with the main project branch.
Provide a title and description for your pull request.
Click "Create pull request".
Step 4: Collaborate and Finalize
Collaborate with your team on the review. Address any comments or suggestions they may have.
Once the review is finalized and approved by your team, merge the pull request.