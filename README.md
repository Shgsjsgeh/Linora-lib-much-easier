# Linora-lib-much-easier

# loading the library

    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/cat"))()

# making a window

    local Window = Library:CreateWindow("cattoware UI Doc", Vector2.new(500, 400), Enum.KeyCode.RightControl)

# making a tab

    local AimingTab = Window:CreateTab("Tab 1")

 # section (has to be added)

     local testSection = AimingTab:CreateSector("First Section", "left")

# making a button

    testSection:AddButton("Button", function(IhateGayPeople)
    print("button")
    end)

# making a toggle

    testSection:AddToggle("Toggle", false, function(first)
    print("ejejejejejeje")
    end)

# slider

    testSection:AddSlider("Slider", 0, 120, 2000, 1, function(State)

# color picker

    local ColorToggle = testSection:AddToggle("ColorPicker w/Toggle", false, function(e)

# DropDown

    testSection:AddDropdown("Dropdown", {"here", "here", "here", "here"}, "here", true, function(dropdown)

# more soon...
