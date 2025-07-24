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

---

# git-worktree-helper

Git worktree の管理を簡素化するための一連のスクリプトです。

## スクリプト

- `create-worktree`: 新しい Git worktree を対話的に作成します。
- `delete-worktree`: 既存の Git worktree を対話的に削除します。

## インストール

1. このリポジトリをクローンします:
   ```bash
   git clone https://github.com/your-username/git-worktree-helper.git
   ```
2. `bin` ディレクトリを `PATH` に追加します。例えば、`.bashrc` や `.zshrc` に以下を追記します:
   ```bash
   export PATH="/path/to/git-worktree-helper/bin:$PATH"
   ```

## 使い方

### `create-worktree`

このスクリプトは、対話的に 1 つまたは複数の worktree を作成するのに役立ちます。

- **対話モード**:

  ```bash
  create-worktree
  ```

  スクリプトは、ベースブランチ、作成する worktree の数、および新しい worktree のベースパスを尋ねます。

- **非対話モード**:
  ```bash
  create-worktree -b <base-branch> -n <num-worktrees> -p <base-path>
  ```

### `delete-worktree`

このスクリプトは、対話的に 1 つまたは複数の worktree を削除するのに役立ちます。

```bash
delete-worktree
```

スクリプトは利用可能な worktree を一覧表示し、削除するものを選択するように促します。
