# Bottom Sheet
Learn about the [bottom sheet here](https://material.io/design/components/sheets-bottom.html)

## Fields

### Title
The title to appear at the top of the bottom sheet

### Items [separated by ',']
These are the "items" in the bottom sheet list which will have associated icons (if you set them). The character '-' Will show a divider line and the character '=' will show a thick divider line. Press the edit icon to use the text manager which makes this easier.

### Item Color
This is the text color for the items above. A color picker will make it easier to pick the color. 

### Icons [separated by ',']
These are the icons, where the first icon is associated with the first item, second to second, etc. Press the edit icon to use the icon manager which makes this easier.

NOTE: If you use a divider in the items section, you will also need to use a divider in the icon section to keep the items aligned correctly.

### Commands [separated by ',']
These are the commands that will be sent when an item is pressed. Press the edit icon to use the text manager which makes this easier.

NOTE: If you use a divider in the items section, you will also need to use a divider in the icon section to keep the items aligned correctly.

### Long Commands [separated by ',']
These are the commands that will be sent when an item is long pressed. Press the edit icon to use the text manager which makes this easier.

Leaving this field blank removes the ability to long press an item.

NOTE: If you use a divider in the items section, you will also need to use a divider in the icon section to keep the items aligned correctly.

### Sheet Background
This is the background color for the sheet. A color picker will make it easier to pick the color.

### Navigation color of the sheet
This is the background color of the navigation bar (if you device has one). A color picker will make it easier to pick the color.

### Floating Action Button (FAB)
This is an option which will show a floating action button at the top of the sheet which will provide an additional action (which might be good for separate or unrelated actions)

#### Icon for the FAB
This is the icon that goes inside the FAB, press the + to use the icon manager to select the icon.

#### Color for the FAB
This is the background color of the FAB. A color picker will make it easier to pick the color.

#### Command
This is the command that will be sent when the FAB is clicked.

## Advanced Fields

### Separator
Default separator character is a ',', but you can change it to a different character here.

NOTE: This will break all current data inside this instance of the bottom sheet if you already set it up.

### Single Icon
This will make the first icon chosen be shown for all items in the bottom sheet.

### Immersive Mode
This will hide the navigation and status bars when the bottom sheet is shown.

### Real Bottom Sheet Behavior
By default the sheet expands to the height that it needs to to show all items, making the list scrollable if necessary. This option will make it so that the sheet starts only showing 3 items and then can be dragged to show the rest.

### Real FAB Behavior
This option makes the FAB hide while the bottom sheet is being dragged.

### Start List From Bottom
This option will reverse the list items and scroll direction such that the list will start at the bottom (think of how chat apps work)

### Persistent Mode
This is a list of items which can be set so that they won't dismiss the sheet and will instead send a command to AutoApps Hub.

### Color Of Title Section
This will set a separate color to the title section if you don't want it to use the background color of the sheet.

### Divider Color
Color of the dividers if any are used.

### Text Field
Adds a text field to the sheet.

### Spinner Items
This will add a spinner dropdown to the top of the sheet so items can be selected.

### Default Spinner Item
This will allow setting the index of the currently selected spinner item.