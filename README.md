    ```markdown
    # Git Assignment - <FerialVahmiyan>
    ```

    =========================================
    a. What is an _issue_? 
        It is a feature on GitHub that allows us to track requested changes and features in a software project.

    b. What is a _pull request_?
        Pull requests help you collaborate on code with other people.

    c. Describe the steps to open a _pull request_?
        1. Fork the Repository (if applicable)
        2. Clone the Repository
        3. Create a New Branch
        4. Make Your Changes
        5. Push Your Branch to GitHub
        6. Open a Pull Request
        7. Review and Submit the Pull Request
        8. Wait for Review

    d. Describe the steps to add a collaborator to a repository (share write permissions)
        1. Sign in to GitHub
        2. Navigate to Your Repository
        3. Go to the Settings of the Repository
        4. Access the Collaborators Section
        5. Add a Collaborator
        6. Set Permissions
        7. Send Invitation
        8. Collaborator Accepts the Invitation
        9. Confirm the Collaboration

    e. What is the difference between `git` and `GitHub`?
       .  Git: A tool for version control used locally to track and manage changes in your codebase.
       .  GitHub: A cloud-based platform that hosts Git repositories and adds collaboration tools, making it easier to work on projects with others.
    
    f. What does `git diff` do?
        The 'git diff' command is used to show the differences between various states of a Git repository. It helps you see what has changed between commits, branches, or the working directory and the staging area.

    g. What is the `main` branch?
        The 'main branch' in Git is the primary or default branch of a repository. It is typically where the stable, production-ready code resides.

    h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the `main` branch?
        For most projects, especially those involving multiple contributors or production code, it's best to avoid pushing directly to 'main' after the initial commit. Instead, use feature branches and pull requests to ensure that code is reviewed, tested, and stable before it becomes part of the main codebase. This workflow helps maintain the integrity and stability of the 'main' branch.