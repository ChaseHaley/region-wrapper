# Region Folding Extension for Visual Studio Code

This extension for Visual Studio Code allows users to easily wrap blocks of code with `#region` and `#endregion` comments, providing better organization and readability. It also displays a tree view of the regions in each file.

## Notice
This is a forked repository of [swssr's Region Wrapper](https://github.com/swssr/region-wrapper) VSCode extension. I currently have no plans to publish this extension on the VSCode store, but that may change should I further flesh out this extension. I simply forked swssr's implementation as it largely did what I wanted, but I wanted to add some personal tweaks that added some behaviors found in the Visual Studio extension [Menees VS Tools](https://marketplace.visualstudio.com/items?itemName=BillMenees.MeneesVSTools2022) that I was used to working with.

## Features

- Easily wrap selected code in `#region` and `#endregion` comments
- Choose from a predefined list of names or assign a custom name to each region
- View a list of regions in each file in the Activity Bar

## Usage

1. Select a block of code that you want to wrap in a region.
2. Right-click and select "Wrap with Region", or use the Command Palette to run the "Wrap with Region" command.
3. Enter a name for the region in the input box.
4. The selected code will be wrapped in `#region` and `#endregion` comments.

The tree view in the Activity Bar will automatically update to reflect the current regions in each file.
