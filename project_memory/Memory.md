# Project Memory

## Effective Deployment Workflow (Fix for 400 Error)
To resolve "deployment in progress" (400) errors and ensure updates go live:
1.  **Stage All Changes**: Run `git add .` to stage all modifications, including the `site/` directory and `project_memory` files.
2.  **Commit**: Run `git commit -m "Your message"` to verify a clean state.
3.  **Push**: Run `git push` to sync the local source with the remote repository.
4.  **Deploy**: Only *after* the push is successful, run `mkdocs gh-deploy`.

## Recent Changes
- **Documentation Overhaul**:
    - Renamed "Features" navigation item to "Documentation".
    - Enriched `hierarchy-operations.md` (Double Hierarchy, independent renaming, distinct context menus).
    - Enriched `nodes-in-peek.md` (Node parts, non-destructive removal).
    - Clarified `custom-collections.md` availability.
- **Configuration**:
    - Removed `project_memory` from `.gitignore`.

## Project State
- **Status**: Live and deployed.
- **URL**: https://Sekuora.github.io/Peek_a_Node_Docs/
