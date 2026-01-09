# Hierarchy & Operations

The core power of Peek a Node comes from its **Hierarchy** system, allowing you to manage node groups and materials contextually.

## Peek a Node Group

To start, right-click on any node group and select:
`Peek Options -> Peek Node Group`

![Peek Node Group](assets/images/3_Custom_Collections_Peek_Node_Group.png)

This adds the node group to the **Peek Hierarchy**.

![Peek Hierarchy Location](assets/images/4_Peek_HIerarchy_Location.png)

## The Peek Hierarchy

The hierarchy shows the relationship between your node groups and the materials they belong to.

![Parts of the Hierarchy](assets/images/4_Peek_HIerarchy_Parts_of_the_Hierarchy.png)

### Hierarchy Context Menu
Clicking the dropdown arrow next to a hierarchy item reveals operations:

*   **Apply Material to Selected Object**: Propagate the material to other objects.
*   **Remove node group from file**: Safely remove data.
*   **Remove from peek view**: Stop tracking this group in the sidebar.

![Hierarchy Options](assets/images/4_Peek_HIerarchy_Context_Menu_Options.png)

---

## Node Group Operations

Peek distinguishes between a **Root Material** (the original) and **Variants**.

### Root Material
When first added, it is a Root Material. You can **Create Unique Variant** to branch off without affecting the original.

![Root Material Selected](assets/images/5_Node_Group_Operations_Root_Material_Selected.png)

### Unique Variants
A variant appears as a child of the root. This allows you to experiment safely.

![Variant Material Selected](assets/images/5_Node_Group_Operations_Variant_Material_Selected.png)

#### Merging Variants
You can merge your changes back to the parent or promote the variant to a new material.

**Merge to Parent**:
Commits the variant's settings to the root material.

*Option: Keep Variant on Merge*
If off, the variant is deleted after merge:
![Merge Keep Variant Off](assets/images/5_Node_Group_Operations_Merge_To_Parent_Keep_variant_toggle_off_1.png)

If on, the variant remains as a separate material assigned to the object:
![Merge Keep Variant On](assets/images/5_Node_Group_Operations_Merge_To_Parent_Keep_variant_toggle_on_merged_and_kept_variant.png)
