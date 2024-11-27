# Project Instructions
## Phases

### Phase 1: Project Setup
1. Clone the repository:
    ```sh
    git clone <repository_url>
    ```
2. Create and switch to your own branch:
    ```sh
    git checkout -b <your_branch_name>
    ```

### Phase 2: setup a python Env
1. Follow the instructions in the `README.md` file to set up the environment.

### Phase 3: reproccessing the dataset and finetuning the model
    "READ Backend Development phase first"
### Phase 4: Development

#### Frontend Development
- Work on the frontend components in the `frontend` directory.
- Ensure that the UI is responsive and user-friendly.

#### Backend Development
- all work is gonna be on python 3.12.6 **DO NOT WORK ON ANY DIFFERENT VERSION**
- Work on the backend components in the `backend` directory.
- Any development of the backend should be in a function with clear comments explaining what it does.
- Preferably use lowerCamelCase for function names and variables.
- Ensure that every function returns the data correctly.
- For testing, use a different file or command to ensure the main codebase remains clean for others.
- Make sure to include any new library in the requirements file, you can list all of the requirements using `pip freeze` 
- Make sure to use log any result/error , in python you can use TRY - EXCEPT statement..
- DO NOT TYPE ANY KEY ON YOUR EDITOR, ALWAYS KEEP THEM IN .env file with appropiate names
Example of a well-documented function:
```python
def fetchDataFromDatabase(query):
    """
    Fetches data from the database based on the provided query.
    
    Args:
        query (str): The SQL query to execute.
    
    Returns:
        list: A list of records fetched from the database.
    """
    # Implementation code here
    pass
```

## Git Instructions

### Switching Branches
- To switch to an existing branch:
  ```sh
  git checkout <branch_name>
  ```

### Committing Changes
- To commit changes:
  ```sh
  git add <file_name>
  git commit -m "Your commit message"
  ```
### Stashing Changes
- **What it does:** Temporarily saves your changes without committing them.
- **When to use:** When you need to switch branches or pull updates without losing your current work.
    ```sh
    git stash
    ```

### Warning
- **What it does:** Reminds you to avoid committing directly to the `main` branch.
- **When to use:** Always, to ensure the main branch remains stable and clean.

### Pushing Changes
- **What it does:** Uploads your local branch changes to the remote repository.
- **When to use:** After committing your changes and you want to share them with others.
    ```sh
    git push origin <your_branch_name>
    ```

### Pulling Changes
- **What it does:** Fetches and integrates changes from the remote repository into your current branch.
- **When to use:** To update your branch with the latest changes from the remote repository.
    ```sh
    git pull origin <branch_name>
    ```

### Merging Changes
- **What it does:** Combines changes from one branch into another.
- **When to use:** When you want to integrate updates from another branch into your current branch.
    ```sh
    git merge <branch_name>
    ```

### Resolving Conflicts
- **What it does:** Manually resolves conflicts that occur during a merge.
- **When to use:** When Git cannot automatically merge changes and you need to fix conflicts.
    ```sh
    git add <resolved_file>
    git commit -m "Resolved merge conflict in <file_name>"
    ```

### Deleting a Branch
- **What it does:** Removes a branch from your local or remote repository.
- **When to use:** After a branch is no longer needed, usually after merging.
    ```sh
    git branch -d <branch_name>
    ```
    ```sh
    git push origin --delete <branch_name>
    ```

