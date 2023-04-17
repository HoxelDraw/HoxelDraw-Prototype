# HoxelDraw Prototype

## IMPORTANT:
## By downloading and running HoxelDraw, you agree to the terms outlined in the [HoxelDraw End-User License Agreement](https://github.com/HoxelDraw/HoxelDraw-Prototype/blob/master/EULA.md), which is included at the bottom of this README and is bundled with each release.

# User's Guide
### beta.2.0
### April 17, 2023
## Overview
HoxelDraw is currently supported only in Windows

## Main Menu

### File

**New**: Clears the existing scene

**Open**: Opens a File Dialog window to find and load an existing .hox file

**Save As**: Opens a File Dialog window to choose a path to save the current scene to a .hox file

**Import Palette**: Opens a File Dialog window to choose a .PNG file for a custom color palette. The first 255 pixels are used to populate the color palette.

## Cross Section View

### 3D View Controls
**Hover**: highlight the hoxel under the cursor. When using a hoxel tool (see Tools Panel), the highlighted hoxel will be modified first.

**Right-click + drag**: Orbit the 3D camera

**Mouse wheel**: Zoom (dolly) the 3D camera

**Left-click**: Use the active tool (see the Tools Panel). Many tools also have click+drag actions.

## Cross Section View Controls

### Slice Rotation sliders
The slicing hyperplane uses Euler rotations on the six planes of rotation in 4D (XY, XZ, XW, YZ, YW, ZW). Click and drag the handle in each slider to rotate the hyperplane in its respective rotation plane. **Ctrl + click** a slider to manually enter an angle (hit Enter to submit the value).

### Slice Position sliders
The slicing hyperplane rotates around the Slice Position. Click and drag the handle in each slider to move the hyperplane’s center of rotation. Again, **Ctrl + click** a slider to manually enter an angle.

### Slice Offset slider
The slice offset slider translates the slicing hyperplane along its local W axis (instead of along the global W axis). Again, **Ctrl + click** this slider to manually enter a value.

## Slice Grid View

**Hover**: highlight the hoxel under the cursor. When using a hoxel tool (see Tools Panel), the highlighted hoxel will be modified first.

**Right-click + drag**: Pan the entire Slice Grid (AKA the **Major View**)

**Mouse wheel**: Zoom the entire Slice Grid

**Ctrl + Right-click + drag**: Pan each individual slice (AKA **Minor Views**) within the Slice Grid

**Ctrl + Mouse wheel**: Zoom each individual minor view within the Slice Grid

The Double Axis Jack indicates axes within the Slice Grid. The larger Axis Jack (defaults to Yellow and Blue) shows the screen directions of the Z (blue) and W (yellow) axes and only applies to the whole grid. A minor view’s horizontal and vertical position within the major view indicates its Z and W coordinates.

The smaller Axis Jack (defaults to Red and Green) shows the screen directions of the X (red) and Y (green) axes and only applies to hoxels within minor views. A hoxel’s horizontal and vertical position within its minor view indicate its X and Y coordinates.

## Slice Grid View Controls

**Center Minor Views**: this button is used to reset any pan or zoom of the individual minor views

**Cross Section Overlay Show/Hide button**: use this button to toggle the cross section overlay, which shows a representation of how the slicing hyperplane intersects with the slice grid.

**Jump to Row/Column button**: Click Select to activate the selection mode. Click the Row/Column button to toggle between row selection and column selection modes. Use the cursor to select the desired row/column, then click on the row/column to align the slicing hyperplane with that row/column.

## Tools Panel

### Tools
Select a tool to begin using it in either the Cross Section view or the Slice Grid view.

**Hoxel Brush**: Left-Click to use the tool (see Tool Mode) on the highlighted hoxel or hoxel grid location. Left-Click + drag to use the tool on each hoxel the cursor hovers over. Adjust the Brush Size to use the hoxel brush on a larger area centered around the highlighted hoxel. The Brush Size is the side length of a 4D hypercube brush tip.

**Hoxel Line**: Left-Click + drag to create a thin line of hoxels in a straight 4D line between two hoxels. The start point is the highlighted hoxel when the mouse is first clicked. The end point is the currently-highlighted hoxel. Release the left mouse button to create the line.

**Hoxel Box**: Click + drag to create a 4D box of hoxels. The first corner is the highlighted hoxel when the mouse is first clicked. The opposite corner is the currently-highlighted hoxel. Release the left mouse button to create the box.

### Tool Mode
Select a Tool Mode to determine the effect of the active tool.

**Place**: Create new hoxels with the tool

**Remove**: Delete existing hoxels with the tool

**Color**: Change the color of existing hoxels to the active material (see Materials)

### Materials
**Current Material**: The color (diffuse color AKA albedo) that will be used by the active tool.

**Palette**: The colors/materials available for use. Click a color in the palette to change the Current Material.

## Scene Panel

**Grid Size**: The size of the current hoxel grid. To change the grid size, click in the text field, delete the existing grid size, then type in the new grid size.

**Clear Scene**: Click this button to clear everything in the hoxel grid.


# HoxelDraw End-User License Agreement

### Last updated: 3rd April 2023

This End-User License Agreement (referred to as the "EULA") is a legally binding agreement between you, the Licensee, an individual customer or entity, and the HoxelSoft, the company, and the author of HoxelDraw, the Software, which may include associated media, printed materials, and online or electronic documentation. This Agreement is a legally binding contract that includes terms that limit your legal rights and Licensors' liability to you, and shall govern all access to and use of this Software. You hereby agree, without limitation or alteration, to all the terms and conditions contained herein.

By installing, copying, or otherwise using the Licensed Product (Software), the Licensee agrees to be bound by the terms and conditions outlined in this EULA. However, if the Licensee does not agree to the terms and conditions outlined in this EULA, the said Licensee may not download, install, or use Software.

## Definitions
"EULA" shall refer to this End-User-License-Agreement, including any amendment to this Agreement.

"Licensee" shall refer to the individual or entity that downloads and uses the Software.

"Licensor" shall refer to the company or author, HoxelSoft

"Software/Licensed product" shall mean HoxelDraw, the Licensed Product provided pursuant to this EULA.

## Grant of License
Subject to the terms of this EULA, the HoxelSoft hereby grants to the Licensee, a royalty-free, revocable, limited, non-exclusive license during the term of this EULA to possess and to use a copy of the Software. The Software is being distributed by HoxelSoft. Licensee is not allowed to make a charge for distributing this Software, either for profit or merely to recover media and distribution costs.

## Intellectual Property
You hereby unconditionally agree that all right, title and interest in the copyrights and other intellectual property rights in the Licensed Product reside with the Licensors. The trademarks, logos, designs, and service marks appearing on the Licensed Product are registered and unregistered marks of Licensor.  Accordingly, nothing in this EULA or the Licensed Product grants you any right to use any form of intellectual property contained in the Licensed Product.

Therefore, all rights, titles, interests, and copyrights in and/or to the Software, including but not limited to all images, graphics, animations, audio, video, music, text, data, code, algorithm, and information, are owned by the Licensor. Accordingly, the Software is protected by all applicable copyright laws and international treaties, and the Licensee is expected to use the Software concerning all intellectual property contained therein, except as otherwise provided for in this EULA.

## Description of Rights and Limitations
Installation and Use: Licensee may install and use the Software on a shared computer or concurrently on different computers, and make multiple back-up copies of the Software, solely for Licensee's use within Licensee's business or personal use.

Reproduction and Distribution:  Licensee may not duplicate or re-distribute copies of the Software, without the Licensors express written permission. 

Licensee Limitation: The Licensee may not:

1. Use the Licensed Product for any purpose other than personal and non-commercial purposes;
2. Use the Licensed Product for any illegal or unlawful purpose;
3. Gather factual content or any other portion of the Licensed product by any automated means, including but not limited to database scraping or screen scraping; or
4. Reverse engineer, decompile, or disassemble Software, except and only to the extent that such activity is expressly permitted by applicable law notwithstanding the limitation.

### Update and Maintenance
HoxelSoft shall provide updates and maintenance on a bimonthly basis or as-needed basis.

## Support
HoxelSoft has no obligation to Software support, or to continue providing or updating any of the Software.

## General Provisions

### Termination
In the event of termination, all licenses provided under this EULA shall immediately terminate, and you agree to discontinue accessing or attempting to access this Licensed product.
Accordingly, this EULA may be:

1. Automatically terminated if the Licensee fails to comply with any of the terms and conditions under this EULA;
2. Terminated by HoxelSoft; or
3. Terminated by the Licensee.

Either HoxelSoft or the Licensee may terminate this EULA immediately upon written notice to the other party, including but not limited to electronic mail.

### Non-Transferability
The Licensee has the option to permanently transfer all rights under this Agreement, provided the recipient agrees to the terms of this EULA. Accordingly, this EULA is not assignable or transferable by the Licensee without the prior written consent of HoxelSoft; and any attempt to do so shall be void.

### Notice
Any notice, report, approval or consent required under this EULA shall be in writing and deemed to have been duly given if delivered by recorded delivery to the respective addresses of the parties.

### Integration
Both parties hereby agree that this EULA is the entire and exclusive statement and legal acknowledgement of the mutual understanding of the parties and supersedes and cancels any previous written and oral agreement and/or communication relating to the subject matter of this EULA.

### Severability
No delay or failure to exercise, on the part of either party, any privilege, power or rights under this EULA shall operate as a waiver of any of the terms and provisions of this EULA. Accordingly, no single or partial exercise of any right under this Agreement shall preclude further exercise of any other right under this EULA. Suppose any of the outlined provisions of this EULA is deemed to be unenforceable or invalid in whole or in part by a court of competent jurisdiction. In that case, such provision shall be limited to the minimum extent necessary for this EULA to remain in full force and effect and enforceable. The remaining provisions of this Agreement shall not be rendered unenforceable or invalid. They shall continue to be enforceable and valid in isolation of the unenforceable and invalid provisions of this EULA.

### Warranty and Disclaimer
HoxelSoft, and author of this Software, expressly disclaim any warranty for the HoxelDraw. The Licensed Product and all applicable documentation is provided as-is, without warranty of any kind, whether express or implied, including, without limitation, the implied warranties of merchantability, fitness for a particular purpose, or non-infringement. Accordingly, the Licensee accepts any risk arising out of the use or performance of the Software.

### Limited Liability
The Licensee agrees that the HoxelSoft shall not be liable to Licensee, or any other related person or entity claiming any loss of profits, income, savings, or any other consequential, incidental, special, punitive, direct or indirect damage, whether arising in contract, tort, warranty, or otherwise. Even if HoxelSoft has been advised of the possibility of such damages. These limitations shall necessarily apply regardless of the primary purpose of any limited remedy. Under no circumstances shall HoxelSoft aggregate liability to the Licensee, or any other person or entity claiming through the Licensee, exceed the actual monetary amount paid by the Licensee to HoxelSoft for the Software.

### Indemnification
You hereby agree to indemnify and hold HoxelSoft harmless from and against all liabilities, damages, losses or expenses, including but not limited to reasonable attorney or other professional fees in any claim, demand, action or proceeding initiated by any third-party against HoxelSoft, arising from any of your acts, including without limitation, violating this EULA or any other agreement or any applicable law.

### Entire Agreement
This Agreement rightly constitutes the entire understanding between the HoxelSoft and the Licensee and all parties involved. It supersedes all prior agreements of the parties, whether written or oral, express or implied, statement, condition, or a representation or warranty.

### Governing Law and Jurisdiction
This EULA shall be deemed to be construed under the jurisdiction of the courts located in Texas, USA, without regard to conflicts of laws as regards the provisions thereof. Any legal action relating to this EULA shall be brought exclusively in the courts of Texas, USA, and all parties consent to the jurisdiction thereof. Furthermore, the prevailing party in any action to enforce this EULA shall be entitled to recover costs and expenses including, without limitation, legal fees. Accordingly, this EULA is made within the exclusive jurisdiction of the Texas, USA, and its jurisdiction shall supersede any other jurisdiction of either party's election.

