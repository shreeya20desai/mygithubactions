# GitHub Actions

The aim of the project is to understand how GitHub Actions work and how it is used to automate the workflow.

## Implementation
- Created a workflow file inside the .github/ .workflows /
- Created & Configured the .yml file.
- Used the event trigger as push and runner environment as ubuntu-latest.
- Added a .py script to test teh workflow.
- Introduced errors in the .py script to test the failure detection.

## Key Learnings:
- GitHub Actions can automatically trigger workflows on events like push.
- The workflow successfully detected errors in the Python script.
- Error logs clearly highlighted the file name and line causing the issue.
- Received email notifications for workflow failures.

**Error shown in the GitHub Actions:**
<img width="1397" height="802" alt="image" src="https://github.com/user-attachments/assets/2b9489d7-34c4-4231-87a8-887c1554b216" />
