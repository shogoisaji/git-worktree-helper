# git-worktree-helper

A set of scripts to simplify the management of Git worktrees.

## Scripts

- `create-worktree`: Interactively create new Git worktrees.
- `delete-worktree`: Interactively delete existing Git worktrees.

## Installation

Add the `bin` directory to your `PATH`. For example, add the following to your `.bashrc` or `.zshrc`:

```bash
export PATH="/path/to/git-worktree-helper/bin:$PATH"
```

## Usage

### `create-worktree`

This script helps you create one or more worktrees interactively.

- **Interactive Mode**:

  ```bash
  create-worktree
  ```

  The script will prompt you for the base branch, the number of worktrees to create, and the base path for the new worktrees.

- **Non-interactive Mode**:
  ```bash
  create-worktree -b <base-branch> -n <num-worktrees> -p <base-path>
  ```

### `delete-worktree`

This script helps you delete one or more worktrees interactively.

```bash
delete-worktree
```

The script will list the available worktrees and prompt you to select which ones to delete.
