# wachinode
Simple KNIME utility node repository site.

### How to install


Clone the repository to local drive. 
e.g., 
```
cd ~
git clone ...
```

Open KNIME application and open a workspace.

Open menu: Help > Install New Software ...
Click "Add" button.

Name a repository (e.g., WachiNode)

Click "Local.." button, then select the directory: ~/wachinode/bin/WachiNodeUpdateSite"

Uncheck group items by "Category to Install" to see the 

Agree to license and install the software, then reset.

Look for category called “AltManipulator"

### Node description
```
ColumnConcatenate:

The node horizontally concatenates two tables together.

Diff:

Finds difference between two tables.

ListColumnResort:

Similar to column resorter, but without the complicated dialog. Allows further automation due to the fact that the column rearrangement is dependent on the column names listed in table in the input port 1 (bottom port, Table 1).

Shunt:

As the name suggests, this node does nothing to the data, and is used for workflow organization. Suggested use of the node: if there is a branching workflow and want to maintain the topology of the node while replacing some part of it, you could use shunt node to keep the flow intact while you replace a functional node with another.

SimpleColumnRename:

Renames columns based on the second input port table column.

SimpleJoin:

Same as ColumnConcatenate
```


