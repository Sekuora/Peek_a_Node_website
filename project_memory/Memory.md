# Project Memory

## Recent Changes
- **Documentation Overhaul**:
    - Renamed "Features" navigation item to "Documentation".
    - Enriched `hierarchy-operations.md` and `nodes-in-peek.md` with:
        - Explanation of "Double Hierarchy" (Node Group and Material items).
        - Explicit mention of independent renaming capabilities.
        - Detailed breakdown of Hierarchy parts (Parent, Children, Node Group, Node Tree) and Context Menu operations.
        - Clearer "Merge to Parent" vs "New Material from Variant" vs "Keep Variant" descriptions.
    - Updated `custom-collections.md` to highlight availability only with Peek Hierarchy and the continued availability of the sidebar in the 3D Viewport.
- **Deployment**:
    - Initial `mkdocs gh-deploy` appeared successful but changes were not immediately visible.
    - Running explicit `mkdocs build` and `mkdocs gh-deploy` to force update.
- **Project Configuration**:
    - Removed `project_memory` from `.gitignore` to allow tracking of memory files.

## Project State
- Documentation website for Peek a Node is live.
- Deployed via MkDocs to GitHub Pages.
