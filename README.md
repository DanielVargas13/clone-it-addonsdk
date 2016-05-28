clone-it
========

Download this addon from [addons.mozilla.org] (https://addons.mozilla.org/en-US/firefox/addon/clone-it) (XUL Overlay)

Source Code Repository For Clone It (Addon SDK)

Source code released under [MPL 2.0] (https://www.mozilla.org/MPL/2.0/)

#### What it does: 
Allows easy duplication of current tab in new tab or window, Similar to Goggle chrome default feature, 
This feature is already available by holding down CTRL key | Command + dragging the tab to left or right.

### About this Add-on:
- Clone current tab in new tab. 
- Clone current tab in new window. 
- After install these 2 customizable buttons are available.

No menu items only toolbar buttons.

This addon was created in visual studios code.

####  To build (Platform):

- `Windows:` __CTRL + SHIFT + B__

#### Task Runner (Visual Studio Code):

- `Windows:` __CTRL + SHIFT + P__

| Task | Command | Result |
|----------|:-------------:|------:|
| Build | task build | Builds addon *.xpi |
| Test | task test | Runs tests printing to task console. |
| Run | task run | Spawns firefox with new profile instance. |
| Sign | task sign | Builds then signs the addon using AMO signing api. |
