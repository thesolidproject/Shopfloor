# Shop Floor Visualization

## User Documentation

**Date last Modified: 14 May 2017**

--------------------------------------------------------------------------------

### Introduction

The shop floor visualization was designed to make viewing the manufacturing states a breeze as it can highlight critical states and inform you on where bottlenecks are occurring. This is a simple tutorial of how to use this widget, which may be expanded as it advances.

### Main View

When you first load the application, you are greeted with a view of all the states available on your screen. At a glance, you may quickly see which states require attention and which are on the right track. The table below shows you the color and the meaning:

Color  | Description
------ | ---------------------------------------------------------------------------------
Green  | No errors or bottlenecks found. This state is in the clear.
Yellow | Minor errors found. These states need to be reviewed but are not system critical.
Red    | Critical Errors found in state and require immediate attention.

### Theme Change

Users can change the colors of the navigation bar by clicking on the theme button located in the navigation bar.

### Key

There is a key available to the user in the navigation bar. The key will explain the schedule of a node current state.

### Admin Mode

When the browser is first opened or refreshed, admin mode is always off. To turn on admin mode, user would need to toggle the switch located in the far right of the navigation bar. Once toggled on, admin mode will allow the user to edit node details, delete nodes, create child nodes.

### Drag Node

Users can activate drag when left-clicking on a node and holding it.

### Save

The save button is located in the navigation bar. It is supposed to save all the changes made to the shop floor. Right now it is a work-in-progress and a task for future development.

### Detail Views

By left-clicking over a node, user can easily see the current progress and the description of the current state.

### Context Menu

The context menu is initiated by right-clicking on a node. There are five options on the menu: Edit Node, Delete Node, and Create Node.

### Edit Node

Edit node is initiated through the context menu. The user can edit any of the node's details, but only in admin mode.

### Delete Node

Delete node is initiated through the context menu. The user can delete any node by right-clicking on the desired node. Also, user can only delete nodes in admin mode.

### Create Node

Create node is initiated through the context menu. The user can create a node by right-clicking on any node and entering a node name. Also, user can only create nodes in admin mode.   
