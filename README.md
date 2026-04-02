# Application Menu in Windows Forms Ribbon (Syncfusion)

This sample shows how to add and configure the Office-style Application Menu for the Syncfusion Windows Forms Ribbon control. It covers both the Backstage (full-page) and classic drop-down Application Menu styles, demonstrates adding tabs/commands, images, keyboard shortcuts, and saving/loading settings to create a polished, Office-like user experience.

## Features
- Backstage view: full-page file menu with tabs and command buttons
- Classic drop-down Application Menu with recent items and separators
- Ribbon integration with tabs, groups, and quick access toolbar (QAT)
- Images, descriptions, and keyboard shortcuts for menu commands
- Recent documents list and custom footer/header areas
- Enable/disable items and runtime updates
- Localization-ready labels and tooltips
- Theme support consistent with Ribbon visual styles

## Getting Started
1. Create a Windows Forms App project in Visual Studio.
2. Install the NuGet package:
   - Project > Manage NuGet Packages > Browse > install "Syncfusion.Windows.Forms.Tools".
3. Add a Ribbon control to your form:
   - From the Toolbox, drag "RibbonControlAdv" onto the form (or create it in code).
4. Choose an Application Menu style:
   - Backstage: add a BackStageView to the Ribbon and populate with BackStage tabs and buttons.
   - Drop-down Application Menu: configure the Ribbon's ApplicationMenu with menu items.
5. Add commands:
   - File actions like New, Open, Save, Save As, Print, Options, and Exit.
6. Customize visuals and behavior:
   - Assign images, tooltips, and shortcuts. Enable/disable items based on app state.
7. Run the app and verify the Application Menu behavior.

## Usage Tips
- Choose Backstage for a modern, full-page file experience; use the drop-down menu for compact layouts.
- Populate a Recent Documents list and bind it to your MRU model.
- Provide accessible names, tooltips, and keyboard shortcuts for all commands.
- Keep destructive actions (e.g., Exit) separated by a visual divider.
- Align the Ribbon theme with your app’s style for consistency.

## About the Sample
This repository provides a focused example of configuring the Application Menu in the Syncfusion Windows Forms Ribbon, including both Backstage and drop-down styles. Extend it by adding your own controls, models, and services to match your application’s workflow.
