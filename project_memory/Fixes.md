# Project Fixes

## Deployment
- **Issue**: `mkdocs gh-deploy` failed with status 400 (deployment in progress) and site was stale.
- **Fix**: The issue was resolved by ensuring the git working directory was clean and synced with remote *before* triggering the mkdocs deployment. Staging and pushing the `site/` folder explicitly helped clear the conflict.

## Documentation
- **Issue**: Documentation was described as "sparse" and lacking detail.
- **Fix**: 
    - Rewrote `hierarchy-operations.md` to detail the "Double Hierarchy" (Material vs Node Group) and independent renaming.
    - Expanded `nodes-in-peek.md` with "Parts of a Node" and better operator descriptions.
    - Renamed "Features" to "Documentation" in navigation for better UX.
