# Agent Workspace Scaffold

Create a workspace instance as a worktree of this repository:

```sh
git -C /path/to/Repository worktree add -b my-workspace /path/to/Workspace
```

Keep infrastructure and documentation at the workspace root. Put project worktrees and other mutable working material in `.work/`, creating the directory when needed:

```text
Workspace/
    AGENTS.md
    .gitignore
    .aiignore
    .work/<project resources and other working files>
```