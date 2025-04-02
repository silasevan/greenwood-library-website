# g

# Greenwood Library Website - Git Adventure Project

## Project Overview

Welcome to the **Greenwood Library Website** repository! This project serves as a demonstration of Git version control best practices, including **branching, merging, conflict resolution, and collaboration via pull requests**. The purpose is to showcase proficiency in Git and facilitate teamwork in a real-world development scenario.

## Repository Structure

The repository is structured with multiple branches representing different sections of the project. These branches ensure that development progresses in an organized manner:

- **main** - 
- **add-books-review**
   **update-events** - The integrated before merging into `main`.
- **Home** - Development branch for the homepage section.
- **Contant us** - Branch for the book catalog implementation.
- **Update-events** - Branch for the contact page.
- **add-book-reviews** - Branch dedicated to resolving responsive design issues.

Each feature branch is created, developed, and then merged into the `develop` branch using **pull requests** before merging into `main`.

## Git Workflow & Collaboration

This project follows a structured **Git workflow** to ensure efficient collaboration:

1. **Cloning the Repository**
   ```bash
   git clone https://github.com/silasevan/greenwood-library.git
   cd greenwood-library
   ```
2. **Creating a New Branch**
   ```bash
   git checkout -b add-book-reviews
   ```
3. **Making Changes & Committing**
   ```bash
   git add .
   git commit -m "Add new feature: Search functionality"
   ```
4. **Pushing to Remote Repository**
   ```bash
   git push origin add-book-reviews
   ```
5. **Creating a Pull Request (PR)**
   - Go to the GitHub repository.
   - Navigate to the `Pull Requests` tab.
   - Click on `New Pull Request` and select the base branch (`main`) and compare branch (`feature/new-feature`).
   - Add a description and submit the PR for review.
6. **Review & Merge PR**
   - Team members review the PR and approve it.
   - The branch is merged into `main`.
   - 

## Commit Message Guidelines

To maintain a clean and understandable commit history, follow these guidelines:
- Use clear and descriptive messages (e.g., `add book review section`)

## Merging Strategies

- **Feature branches** should be merged into `main` using **fast-forward or squash merges**.
-
## Conflict Resolution

Conflicts may arise when merging branches. Follow these steps to resolve conflicts:
1. Identify the conflict using `git status`.
2. Open conflicting files and manually resolve conflicts.
3. Stage the resolved files with `git add <file>`.
4. Continue the merge process with `git commit`.

Example:
```bash
git merge feature/new-feature
# Resolve conflicts manually
git add .
git commit -m "Resolve merge conflict in homepage.html"
```

## Running the Project Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/silasevan/greenwood-library.git
   ```
2. Navigate to the project directory:
   ```bash
   cd greenwood-library
   ```


## Screen shot 
<img src='./img/book review branch.png'>
<img src='./img/clonning repo.png'>
<img src='./img/commit add-books-review.png'>
<img src='./img/commit and push to update -events branch.png'>
<img src='./img/confirm merge for update events.png'>
<img src='./img/creating a pull Request.png'>
<img src='./img/git pull to main.png'>
<img src='./img/green wood repo setup.png'>
<img src='./img/merge pull for update event.png'>
<img src='./img/merge succesful.png'>
<img src='./img/merging pull request for add-book-reviews.png'>
<img src='./img/Pul request outcome for add-book-reviews.png'>
<img src='./img/confirm merge for update events.png'>
<img src='./img/Pull request add-book-reviews.png'>
<img src='./img/Pull request for add-book-reviews.png'>
<img src='./img/Push for add-book-reviews.png'>
<img src='./img/succesfully merge pull request add-book-reviews.png'>
<img src='./img/succesfully pull request for update event.png'>
<img src='./img/switch to add-books-review branch.png'>
<img src='./img/Update  events branch.png'>
<img src='./img/Update event pull request.png'>




