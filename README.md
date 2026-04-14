# ProxyLib
<img src="Images/window.png" alt="window">
- 👋 Hello, welcome to ProxyLib. Below you can see the components.
- Separator
- Tab
- DiscordInvite
- Paragraph
- Toggle
- Slider
- Dropdown
- Button
- Notify
- Menu Config

---
- Separator
<img src="Images/separator.png" alt="separator">

```lua
window:CreateSeparator({ Text = "" }) 
````
---
- Tab
<img src="Images/tab2.png" alt="tab2">

```lua
local Tab = window:CreateTab({
    Title = "", 
    Subtitle = "",
    Icon = "rbxassetid://", -- Your ID
})
```
---
- Discord Invite
<img src="Images/discordinvite.png" alt="discordinvite">

```lua
Tab:CreateDiscordInvite({
    Banner      = "rbxassetid://", -- Your ID
    Icon        = "rbxassetid://", -- Your ID
    Title       = "",
    Description = "",
    Link        = "https://discord.gg/", -- URL
    Button      = "",
})
```
---
- Paragraph
<img src="Images/paragraph.png" alt="paragaph">

```lua
local statusP = Tab:CreateParagraph({
    Title = "",
    Icon = "rbxassetid://", -- Your ID
    Description = "",
})
```
---
- Toggle
<img src="Images/toggle.png" alt="toggle">

```lua
Tab:CreateBoxToggle({
    Title = "",
    Description = "",
    Default = false, -- Toggle Start Active
    Confirmation = false, -- Ask before activating
})
```
---
- Slider
<img src="Images/slider.png" alt="slider">

```lua
Tab:CreateSlider({
    Title = "",
    Min = 0,
    Max = 100,
    Default = 50,
    Callback = function(value)
    end,
})
```
---
- Dropdown
<img src="Images/dropdown.png" alt="dropdown">

```lua
Tab:CreateDropdown({
    Title = "",
    Multiple = false, -- Active Case For Multiple Selection
    Default = { "" },
    Options = {
        { Value = "", Description = "" },
        { Value = "", Description = "" },
        { Value = "", Description = "" },
    },
})
```
---
- Button
<img src="Images/button.png" alt="button">

```lua
Tab:CreateButton({
    Title = "",
    Description = "",
    Confirmation = true,
    Callback = function()
    end,
})
```
---
- Notify
<img src="Images/notify.png" alt="notify">

```lua
window:Notify({
    Title = "",
    Text = "",
    Icon = "rbxassetid://", -- Your ID
    Duration = 5,
})
```
---
- Config Menu
<img src="Images/config_menu.png" alt="cfg">
---
- Window
<img src="Images/window.png" alt="window">
---
- Thanks For Use
- Made by @zerozxk and @araujozwx
---
