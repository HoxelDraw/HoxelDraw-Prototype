HoxelDraw Prototype

IMPORTANT:
By downloading and running HoxelDraw, you agree to the terms outlined in the HoxelDraw End-User License Agreement which is bundled with each release.

User's Guide
beta.1.0
April 3, 2023
Overview
    HoxelDraw is currently supported only in Windows

Main Menu
    File
        Open: Opens a File Dialog window to find and load an existing .hox file
        Save As: Opens a File Dialog window to choose a path to save the current scene to a .hox file

Cross Section View
    3D View Controls
        Hover: highlight the hoxel under the cursor. When using a hoxel tool (see Tools Panel), the highlighted hoxel will be modified first.
        Right-click + drag: Orbit the 3D camera
        Mouse wheel: Zoom (dolly) the 3D camera
        Left-click: Use the active tool (see the Tools Panel). Many tools also have click+drag actions.

Cross Section View Controls
    Slice Rotation sliders
        The slicing hyperplane uses Euler rotations on the six planes of rotation in 4D (XY, XZ, XW, YZ, YW, ZW). Click and drag the handle in each slider to rotate the hyperplane in its respective rotation plane. Ctrl + click a slider to manually enter an angle (hit Enter to submit the value).
    Slice Position sliders
        The slicing hyperplane rotates around the Slice Position. Click and drag the handle in each slider to move the hyperplane’s center of rotation. Again, Ctrl + click a slider to manually enter an angle.
    Slice Offset slider
        The slice offset slider translates the slicing hyperplane along its local W axis (instead of along the global W axis). Again, Ctrl + click this slider to manually enter a value.

Slice Grid View
    Hover: highlight the hoxel under the cursor. When using a hoxel tool (see Tools Panel), the highlighted hoxel will be modified first.
    Right-click + drag: Pan the entire Slice Grid (AKA the Major View)
    Mouse wheel: Zoom the entire Slice Grid
    Ctrl + Right-click + drag: Pan each individual slice (AKA Minor Views) within the Slice Grid
    Ctrl + Mouse wheel: Zoom each individual minor view within the Slice Grid

    The Double Axis Jack indicates axes within the Slice Grid. The larger Axis Jack (defaults to Yellow and Blue) shows the screen directions of the Z (blue) and W (yellow) axes and only applies to the whole grid. A minor view’s horizontal and vertical position within the major view indicates its Z and W coordinates.
    The smaller Axis Jack (defaults to Red and Green) shows the screen directions of the X (red) and Y (green) axes and only applies to hoxels within minor views. A hoxel’s horizontal and vertical position within its minor view indicate its X and Y coordinates.

Slice Grid View Controls
    Center Minor Views: this button is used to reset any pan or zoom of the individual minor views
    Cross Section Overlay Show/Hide button: use this button to toggle the cross section overlay, which shows a representation of how the slicing hyperplane intersects with the slice grid.
    Jump to Row/Column button: Click Select to activate the selection mode. Click the Row/Column button to toggle between row selection and column selection modes. Use the cursor to select the desired row/column, then click on the row/column to align the slicing hyperplane with that row/column.

Tools Panel
    Tools
        Select a tool to begin using it in either the Cross Section view or the Slice Grid view.
        Hoxel Brush: Left-Click to use the tool (see Tool Mode) on the highlighted hoxel or hoxel grid location. Left-Click + drag to use the tool on each hoxel the cursor hovers over. Adjust the Brush Size to use the hoxel brush on a larger area centered around the highlighted hoxel. The Brush Size is the side length of a 4D hypercube brush tip.
        Hoxel Line: Left-Click + drag to create a thin line of hoxels in a straight 4D line between two hoxels. The start point is the highlighted hoxel when the mouse is first clicked. The end point is the currently-highlighted hoxel. Release the left mouse button to create the line.
        Hoxel Box: Click + drag to create a 4D box of hoxels. The first corner is the highlighted hoxel when the mouse is first clicked. The opposite corner is the currently-highlighted hoxel. Release the left mouse button to create the box.

    Tool Mode
        Select a Tool Mode to determine the effect of the active tool.
        Place: Create new hoxels with the tool
        Remove: Delete existing hoxels with the tool
        Color: Change the color of existing hoxels to the active material (see Materials)

    Materials
        Current Material: The color (diffuse color AKA albedo) that will be used by the active tool.
        Palette: The colors/materials available for use. Click a color in the palette to change the Current Material.

Scene Panel
    Grid Size: The size of the current hoxel grid. To change the grid size, click in the text field, delete the existing grid size, then type in the new grid size.
    Clear Scene: Click this button to clear everything in the hoxel grid.