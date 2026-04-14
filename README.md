# ProxyLib

---
- Separator
<img src="Images/separator.png" alt="separator">

```lua
window:CreateSeparator({ Text = "Name" })
````
---
- Tab
<img src="Images/tab.png" alt="tab">

```lua
local homeTab = window:CreateTab({
    Title = "Home",
    Subtitle = "Main dashboard",
    Icon = "rbxassetid://134177068646875",
})
```

---
- Toggle
<img src="Images/toggle.png" alt="toggle">

```lua
Tab:CreateBoxToggle({
    Title = "Toggle",
    Description = "Example Toggle",
    Default = false, -- Toggle Start Active
    Confirmation = false, -- Ask before activating
})
```

---

