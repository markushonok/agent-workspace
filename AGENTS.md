# Agent Workspace

This repository is infrastructure for one unit of coordinated work, which may span multiple agent executions, projects, and repositories. It is not itself a target project.

Keep workspace infrastructure and documentation in the root. Put project resources and all other mutable working material under `.work/`; place project resources directly under `.work/` without additional grouping directories. Contents of `.work/` are local to the workspace and are not tracked by this repository.

Before modifying a project resource, read its `AGENTS.md`, applicable local agent documentation, and referenced workflow documentation. Apply project-specific instructions and run project-specific Git commands, tests, and tooling against that resource.