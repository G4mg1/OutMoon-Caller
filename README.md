--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 61 | Scripts: 9 | Modules: 2 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.ScreenGui.Main
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Main]];
G2L["2"]["BackgroundTransparency"] = 0.6;


-- StarterGui.ScreenGui.Main.UIListLayout
G2L["3"] = Instance.new("UIListLayout", G2L["2"]);
G2L["3"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["3"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["3"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe
G2L["4"] = Instance.new("Frame", G2L["2"]);
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(55, 55, 55);
G2L["4"]["Size"] = UDim2.new(0, 434, 0, 275);
G2L["4"]["Position"] = UDim2.new(0.35328, 0, 0.3097, 0);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Name"] = [[Keyframe]];


-- StarterGui.ScreenGui.Main.Keyframe.Top
G2L["5"] = Instance.new("Frame", G2L["4"]);
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(68, 68, 68);
G2L["5"]["Size"] = UDim2.new(0, 434, 0, 47);
G2L["5"]["Position"] = UDim2.new(-0.00015, 0, 0.00087, 0);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Name"] = [[Top]];


-- StarterGui.ScreenGui.Main.Keyframe.Top.UICorner
G2L["6"] = Instance.new("UICorner", G2L["5"]);
G2L["6"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Keyframe.Top.UIListLayout
G2L["7"] = Instance.new("UIListLayout", G2L["5"]);
G2L["7"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["7"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe.Top.ImageLabel
G2L["8"] = Instance.new("ImageLabel", G2L["5"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["Image"] = [[rbxassetid://13050670424]];
G2L["8"]["Size"] = UDim2.new(0, 36, 0, 73);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Keyframe.Top.ImageLabel.UIAspectRatioConstraint
G2L["9"] = Instance.new("UIAspectRatioConstraint", G2L["8"]);



-- StarterGui.ScreenGui.Main.Keyframe.Top.ImageLabel.TextLabel
G2L["a"] = Instance.new("TextLabel", G2L["8"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["TextSize"] = 21;
G2L["a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/Jura.json]], Enum.FontWeight.Bold, Enum.FontStyle.Italic);
G2L["a"]["TextColor3"] = Color3.fromRGB(201, 201, 201);
G2L["a"]["BackgroundTransparency"] = 1;
G2L["a"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Text"] = [[OutMoon Key System Login]];


-- StarterGui.ScreenGui.Main.Keyframe.Top.ImageLabel.UIPadding
G2L["b"] = Instance.new("UIPadding", G2L["8"]);
G2L["b"]["PaddingLeft"] = UDim.new(0, 60);


-- StarterGui.ScreenGui.Main.Keyframe.Top.ImageLabel.UIListLayout
G2L["c"] = Instance.new("UIListLayout", G2L["8"]);
G2L["c"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["c"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe.Top.UIPadding
G2L["d"] = Instance.new("UIPadding", G2L["5"]);
G2L["d"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.ScreenGui.Main.Keyframe.Top.UIStroke
G2L["e"] = Instance.new("UIStroke", G2L["5"]);
G2L["e"]["Transparency"] = 0.83;
G2L["e"]["Thickness"] = 2;
G2L["e"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Top.UIStroke.UIGradient
G2L["f"] = Instance.new("UIGradient", G2L["e"]);
G2L["f"]["Rotation"] = 20;
G2L["f"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Top.UIStroke.UIGradient.LocalScript
G2L["10"] = Instance.new("LocalScript", G2L["f"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login
G2L["11"] = Instance.new("Frame", G2L["4"]);
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["Size"] = UDim2.new(0, 413, 0, 157);
G2L["11"]["Position"] = UDim2.new(0.02074, 0, 0.20727, 0);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Name"] = [[Login]];
G2L["11"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Guide
G2L["12"] = Instance.new("TextLabel", G2L["11"]);
G2L["12"]["TextWrapped"] = true;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextSize"] = 14;
G2L["12"]["TextScaled"] = true;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["12"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["BackgroundTransparency"] = 1;
G2L["12"]["Size"] = UDim2.new(0, 361, 0, 90);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[Hello Player Pls enter the key that was givin to you by the owner if you already bought it if not then bought it with robux !]];
G2L["12"]["Name"] = [[Guide]];
G2L["12"]["Position"] = UDim2.new(0.06295, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter
G2L["13"] = Instance.new("TextBox", G2L["11"]);
G2L["13"]["CursorPosition"] = -1;
G2L["13"]["Name"] = [[Enter]];
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["TextSize"] = 14;
G2L["13"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(25, 25, 25);
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Bold, Enum.FontStyle.Italic);
G2L["13"]["PlaceholderText"] = [[enter the key]];
G2L["13"]["Size"] = UDim2.new(0, 365, 0, 38);
G2L["13"]["Position"] = UDim2.new(0.25787, 0, 0.66879, 0);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Text"] = [[]];


-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UIStroke
G2L["14"] = Instance.new("UIStroke", G2L["13"]);
G2L["14"]["Transparency"] = 0.83;
G2L["14"]["Thickness"] = 2;
G2L["14"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UIStroke.UIGradient
G2L["15"] = Instance.new("UIGradient", G2L["14"]);
G2L["15"]["Rotation"] = 20;
G2L["15"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UIStroke.UIGradient.LocalScript
G2L["16"] = Instance.new("LocalScript", G2L["15"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UICorner
G2L["17"] = Instance.new("UICorner", G2L["13"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons
G2L["18"] = Instance.new("Frame", G2L["11"]);
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["Size"] = UDim2.new(0, 363, 0, 52);
G2L["18"]["Position"] = UDim2.new(0.37893, 0, 0.94268, 0);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Name"] = [[Buttons]];
G2L["18"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check
G2L["19"] = Instance.new("TextButton", G2L["18"]);
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(39, 39, 39);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["19"]["Size"] = UDim2.new(0, 141, 0, 33);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[Check Key]];
G2L["19"]["Name"] = [[Check]];
G2L["19"]["Position"] = UDim2.new(0.22452, 0, 0.01923, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.LocalScript
G2L["1a"] = Instance.new("LocalScript", G2L["19"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIStroke
G2L["1b"] = Instance.new("UIStroke", G2L["19"]);
G2L["1b"]["Transparency"] = 0.83;
G2L["1b"]["Thickness"] = 2;
G2L["1b"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIStroke.UIGradient
G2L["1c"] = Instance.new("UIGradient", G2L["1b"]);
G2L["1c"]["Rotation"] = 67;
G2L["1c"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIStroke.UIGradient.LocalScript
G2L["1d"] = Instance.new("LocalScript", G2L["1c"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIPadding
G2L["1e"] = Instance.new("UIPadding", G2L["19"]);
G2L["1e"]["PaddingRight"] = UDim.new(0, 10);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIListLayout
G2L["1f"] = Instance.new("UIListLayout", G2L["19"]);
G2L["1f"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Right;
G2L["1f"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["1f"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.ImageLabel
G2L["20"] = Instance.new("ImageLabel", G2L["19"]);
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["ImageTransparency"] = 0.52;
G2L["20"]["Image"] = [[rbxassetid://6776872133]];
G2L["20"]["Size"] = UDim2.new(0, 25, 0, 23);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["BackgroundTransparency"] = 1;
G2L["20"]["Position"] = UDim2.new(0.80916, 0, 0.18182, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.ImageLabel.UIAspectRatioConstraint
G2L["21"] = Instance.new("UIAspectRatioConstraint", G2L["20"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.ImageLabel.UICorner
G2L["22"] = Instance.new("UICorner", G2L["20"]);
G2L["22"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.ImageLabel.UIStroke
G2L["23"] = Instance.new("UIStroke", G2L["20"]);
G2L["23"]["Transparency"] = 0.83;
G2L["23"]["Thickness"] = 2;
G2L["23"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["23"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.ImageLabel.UIStroke.UIGradient
G2L["24"] = Instance.new("UIGradient", G2L["23"]);
G2L["24"]["Rotation"] = 20;
G2L["24"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.ImageLabel.UIStroke.UIGradient.LocalScript
G2L["25"] = Instance.new("LocalScript", G2L["24"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UICorner
G2L["26"] = Instance.new("UICorner", G2L["19"]);
G2L["26"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy
G2L["27"] = Instance.new("TextButton", G2L["18"]);
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["TextSize"] = 14;
G2L["27"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(39, 39, 39);
G2L["27"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["27"]["Size"] = UDim2.new(0, 141, 0, 33);
G2L["27"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["27"]["Text"] = [[Buy Key]];
G2L["27"]["Name"] = [[Buy]];
G2L["27"]["Position"] = UDim2.new(0.22452, 0, 0.01923, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UICorner
G2L["28"] = Instance.new("UICorner", G2L["27"]);
G2L["28"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.LocalScript
G2L["29"] = Instance.new("LocalScript", G2L["27"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIListLayout
G2L["2a"] = Instance.new("UIListLayout", G2L["27"]);
G2L["2a"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Right;
G2L["2a"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["2a"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIPadding
G2L["2b"] = Instance.new("UIPadding", G2L["27"]);
G2L["2b"]["PaddingRight"] = UDim.new(0, 10);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIStroke
G2L["2c"] = Instance.new("UIStroke", G2L["27"]);
G2L["2c"]["Transparency"] = 0.83;
G2L["2c"]["Thickness"] = 2;
G2L["2c"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIStroke.UIGradient
G2L["2d"] = Instance.new("UIGradient", G2L["2c"]);
G2L["2d"]["Rotation"] = 20;
G2L["2d"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIStroke.UIGradient.LocalScript
G2L["2e"] = Instance.new("LocalScript", G2L["2d"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel
G2L["2f"] = Instance.new("ImageLabel", G2L["27"]);
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["ImageTransparency"] = 0.52;
G2L["2f"]["Image"] = [[rbxassetid://14134388410]];
G2L["2f"]["Size"] = UDim2.new(0, 25, 0, 23);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["BackgroundTransparency"] = 1;
G2L["2f"]["Position"] = UDim2.new(0.80916, 0, 0.18182, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIAspectRatioConstraint
G2L["30"] = Instance.new("UIAspectRatioConstraint", G2L["2f"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UICorner
G2L["31"] = Instance.new("UICorner", G2L["2f"]);
G2L["31"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIStroke
G2L["32"] = Instance.new("UIStroke", G2L["2f"]);
G2L["32"]["Transparency"] = 0.83;
G2L["32"]["Thickness"] = 2;
G2L["32"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["32"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIStroke.UIGradient
G2L["33"] = Instance.new("UIGradient", G2L["32"]);
G2L["33"]["Rotation"] = 20;
G2L["33"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIStroke.UIGradient.LocalScript
G2L["34"] = Instance.new("LocalScript", G2L["33"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.UIListLayout
G2L["35"] = Instance.new("UIListLayout", G2L["18"]);
G2L["35"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["35"]["Padding"] = UDim.new(0, 10);
G2L["35"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["35"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["35"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Keyframe.Login.UIListLayout
G2L["36"] = Instance.new("UIListLayout", G2L["11"]);
G2L["36"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["36"]["Padding"] = UDim.new(0, 10);
G2L["36"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe.Login.API
G2L["37"] = Instance.new("Folder", G2L["11"]);
G2L["37"]["Name"] = [[API]];


-- StarterGui.ScreenGui.Main.Keyframe.Login.API.CheckWhitelist
G2L["38"] = Instance.new("ModuleScript", G2L["37"]);
G2L["38"]["Name"] = [[CheckWhitelist]];


-- StarterGui.ScreenGui.Main.Keyframe.Login.API.PurchaseKey
G2L["39"] = Instance.new("ModuleScript", G2L["37"]);
G2L["39"]["Name"] = [[PurchaseKey]];


-- StarterGui.ScreenGui.Main.Keyframe.UICorner
G2L["3a"] = Instance.new("UICorner", G2L["4"]);
G2L["3a"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Keyframe.UIStroke
G2L["3b"] = Instance.new("UIStroke", G2L["4"]);
G2L["3b"]["Transparency"] = 0.83;
G2L["3b"]["Thickness"] = 2;
G2L["3b"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.UIStroke.UIGradient
G2L["3c"] = Instance.new("UIGradient", G2L["3b"]);
G2L["3c"]["Rotation"] = 20;
G2L["3c"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.UIStroke.UIGradient.LocalScript
G2L["3d"] = Instance.new("LocalScript", G2L["3c"]);



-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["38"]] = {
Closure = function()
    local script = G2L["38"];local M = {}

function M.Check(textbox, player)
	local playername = player.Name
	if string.find(textbox.Text, playername) ~= nil then
		--[[
██████╗  █████╗ ██████╗ ██╗   ██╗ ██████╗ ██╗   ██╗████████╗███╗   ███╗ ██████╗  ██████╗ ███╗   ██╗     ██████╗ ███╗   ██╗    ████████╗ ██████╗ ██████╗ 
██╔══██╗██╔══██╗██╔══██╗╚██╗ ██╔╝██╔═══██╗██║   ██║╚══██╔══╝████╗ ████║██╔═══██╗██╔═══██╗████╗  ██║    ██╔═══██╗████╗  ██║    ╚══██╔══╝██╔═══██╗██╔══██╗
██████╔╝███████║██████╔╝ ╚████╔╝ ██║   ██║██║   ██║   ██║   ██╔████╔██║██║   ██║██║   ██║██╔██╗ ██║    ██║   ██║██╔██╗ ██║       ██║   ██║   ██║██████╔╝
██╔══██╗██╔══██║██╔══██╗  ╚██╔╝  ██║   ██║██║   ██║   ██║   ██║╚██╔╝██║██║   ██║██║   ██║██║╚██╗██║    ██║   ██║██║╚██╗██║       ██║   ██║   ██║██╔═══╝ 
██████╔╝██║  ██║██████╔╝   ██║   ╚██████╔╝╚██████╔╝   ██║   ██║ ╚═╝ ██║╚██████╔╝╚██████╔╝██║ ╚████║    ╚██████╔╝██║ ╚████║       ██║   ╚██████╔╝██║     
╚═════╝ ╚═╝  ╚═╝╚═════╝    ╚═╝    ╚═════╝  ╚═════╝    ╚═╝   ╚═╝     ╚═╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝     ╚═════╝ ╚═╝  ╚═══╝       ╚═╝    ╚═════╝ ╚═╝     
      
      
      script by > ElysianMoon2 and NotGoobyDolan2
      UI by > OutMoon
      
      this Troll Script lets you buy any gamepasses without prompting gamepass 
      
      if you want to use this script to make your own pls keep the credit cuz i dont want any skid to steal our scripts 
      
      thanks
      
      
]]

		print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")print("FEBYPASS")

		local MarketplaceService = game:GetService("MarketplaceService")

		local UserInputService = game:GetService("UserInputService")
		local Players = game:GetService("Players")
		local localPlayer = Players.LocalPlayer

		local activeResetThreads = setmetatable({}, { __mode = "k" })

		local function Finished(productInfo)
			local success, err = pcall(function()
				MarketplaceService:SignalPromptProductPurchaseFinished(localPlayer.UserId, productInfo.ProductId, true)
			end)
			if success then
				return
			end
			pcall(function()
				MarketplaceService:SignalPromptProductPurchaseFinished(localPlayer, productInfo.ProductId, true)
			end)
		end


		local mainGui = Instance.new("ScreenGui")
		mainGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
		mainGui.Parent = game.Players.LocalPlayer.PlayerGui
		mainGui.ResetOnSpawn = false



		local mainFrame = Instance.new("Frame")
		mainFrame.AnchorPoint = Vector2.new(0.5, 0.5)
		mainFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
		mainFrame.Size = UDim2.new(0, 420, 0, 530)
		mainFrame.BackgroundTransparency = 0.8
		mainFrame.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
		mainFrame.BorderSizePixel = 0
		mainFrame.Parent = mainGui

		local mainCorner = Instance.new("UICorner")
		mainCorner.CornerRadius = UDim.new(0, 28)
		mainCorner.Parent = mainFrame

		local mainStroke = Instance.new("UIStroke")
		mainStroke.Color = Color3.fromRGB(255, 0, 4)
		mainStroke.Thickness = 2.5
		mainStroke.Transparency = 0.3
		mainStroke.Parent = mainFrame

		local mainShadow = Instance.new("ImageLabel")
		mainShadow.BackgroundTransparency = 1
		mainShadow.Image = "rbxassetid://1316045217"
		mainShadow.Size = UDim2.new(1, 32, 1, 32)
		mainShadow.Position = UDim2.new(0, -16, 0, -16)
		mainShadow.ImageTransparency = 0.85
		mainShadow.ZIndex = mainFrame.ZIndex - 1
		mainShadow.Parent = mainFrame

		local titleLabel = Instance.new("TextLabel")
		titleLabel.Text = "Developer Products"
		titleLabel.Font = Enum.Font.GothamBlack
		titleLabel.TextSize = 28
		titleLabel.TextColor3 = Color3.fromRGB(220, 0, 4)
		titleLabel.BackgroundTransparency = 1
		titleLabel.Position = UDim2.new(0.5, -120, 0, 24)
		titleLabel.Size = UDim2.new(0, 240, 0, 36)
		titleLabel.AnchorPoint = Vector2.new(0, 0)
		titleLabel.Parent = mainFrame

		local subtitleLabel = Instance.new("TextLabel")
		subtitleLabel.Text = "by Baby_Outmoon"
		subtitleLabel.Font = Enum.Font.Gotham
		subtitleLabel.TextSize = 16
		subtitleLabel.TextColor3 = Color3.fromRGB(163, 0, 3)
		subtitleLabel.BackgroundTransparency = 1
		subtitleLabel.Position = UDim2.new(0.5, -120, 0, 60)
		subtitleLabel.Size = UDim2.new(0, 240, 0, 22)
		subtitleLabel.AnchorPoint = Vector2.new(0, 0)
		subtitleLabel.Parent = mainFrame

		local closeButton = Instance.new("TextButton")
		closeButton.Text = "✕"
		closeButton.Font = Enum.Font.GothamBold
		closeButton.TextSize = 22
		closeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
		closeButton.BackgroundColor3 = Color3.fromRGB(255, 100, 100)
		closeButton.Size = UDim2.new(0, 38, 0, 38)
		closeButton.Position = UDim2.new(1, -48, 0, 18)
		closeButton.AnchorPoint = Vector2.new(0, 0)
		closeButton.BorderSizePixel = 0
		closeButton.Parent = mainFrame
		local closeCorner = Instance.new("UICorner")
		closeCorner.CornerRadius = UDim.new(0, 16)
		closeCorner.Parent = closeButton

		local buyAllProductsButton = Instance.new("TextButton")
		buyAllProductsButton.Name = "BuyAllProductsButton"
		buyAllProductsButton.Font = Enum.Font.GothamBold
		buyAllProductsButton.Text = "Buy All Products"
		buyAllProductsButton.TextColor3 = Color3.fromRGB(255, 255, 255)
		buyAllProductsButton.TextSize = 18
		buyAllProductsButton.BackgroundColor3 = Color3.fromRGB(200, 0, 3)
		buyAllProductsButton.Position = UDim2.new(0.5, -110, 0, 100)
		buyAllProductsButton.Size = UDim2.new(0, 220, 0, 40)
		buyAllProductsButton.AnchorPoint = Vector2.new(0, 0)
		buyAllProductsButton.BorderSizePixel = 0
		buyAllProductsButton.Parent = mainFrame
		local buyAllCorner = Instance.new("UICorner")
		buyAllCorner.CornerRadius = UDim.new(0, 16)
		buyAllCorner.Parent = buyAllProductsButton


		local containerFrame = Instance.new("Frame")
		containerFrame.BackgroundTransparency = 1
		containerFrame.BackgroundColor3 = Color3.fromRGB(161, 0, 3)
		containerFrame.BorderSizePixel = 0
		containerFrame.Position = UDim2.new(0.5, -180, 0, 150)
		containerFrame.BorderSizePixel = 0
		containerFrame.Visible = false
		containerFrame.Size = UDim2.new(0, 360, 0, 350)
		containerFrame.AnchorPoint = Vector2.new(0, 0)
		containerFrame.Parent = mainFrame
		Instance.new("UICorner", containerFrame).CornerRadius = UDim.new(0, 20)
		local containerStroke = Instance.new("UIStroke")
		containerStroke.Color = Color3.fromRGB(116, 0, 2)
		containerStroke.Thickness = 2
		containerStroke.Transparency = 0.5
		containerStroke.Parent = containerFrame

		local scrollingFrame = Instance.new("ScrollingFrame")
		scrollingFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
		scrollingFrame.ScrollBarThickness = 8
		scrollingFrame.Active = true
		scrollingFrame.BackgroundTransparency = 1
		scrollingFrame.BorderSizePixel = 0
		scrollingFrame.Size = UDim2.new(1, 0, 1, 0)
		scrollingFrame.Parent = containerFrame

		local listLayout = Instance.new("UIListLayout")
		listLayout.SortOrder = Enum.SortOrder.LayoutOrder
		listLayout.Padding = UDim.new(0, 10)
		listLayout.Parent = scrollingFrame
		listLayout.VerticalAlignment = Enum.VerticalAlignment.Top
		listLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center


		local exampleProductFrame = Instance.new("Frame")
		exampleProductFrame.BackgroundTransparency = 0.5
		exampleProductFrame.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
		exampleProductFrame.BorderSizePixel = 0
		exampleProductFrame.Size = UDim2.new(1, -10, 0, 124)
		exampleProductFrame.Position = UDim2.new(0, 12, 0, 0)
		exampleProductFrame.Visible = false
		exampleProductFrame.Name = "ExampleFrame"
		exampleProductFrame.Parent = scrollingFrame
		Instance.new("UICorner", exampleProductFrame).CornerRadius = UDim.new(0, 14)
		local cardStroke = Instance.new("UIStroke")
		cardStroke.Color = Color3.fromRGB(177, 0, 3)
		cardStroke.Thickness = 1
		cardStroke.Transparency = 0.5
		cardStroke.Parent = exampleProductFrame

		local cardShadow = Instance.new("ImageLabel")
		cardShadow.BackgroundTransparency = 1
		cardShadow.Image = "rbxassetid://1316045217"
		cardShadow.Size = UDim2.new(1, 16, 1, 16)
		cardShadow.Position = UDim2.new(0, -8, 0, -8)
		cardShadow.ImageTransparency = 0.92
		cardShadow.ZIndex = exampleProductFrame.ZIndex - 1
		cardShadow.Parent = exampleProductFrame

		local nameLabel = Instance.new("TextLabel", exampleProductFrame)
		nameLabel.Name = "NameLabel"
		nameLabel.Font = Enum.Font.GothamSemibold
		nameLabel.Text = "Product Name:"
		nameLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
		nameLabel.TextSize = 18
		nameLabel.TextXAlignment = Enum.TextXAlignment.Left
		nameLabel.BackgroundTransparency = 1
		nameLabel.Position = UDim2.new(0.04, 0, 0.08, 0)
		nameLabel.Size = UDim2.new(0.8, 0, 0, 24)

		local idLabel = Instance.new("TextLabel", exampleProductFrame)
		idLabel.Name = "IDLabel"
		idLabel.Font = Enum.Font.Gotham
		idLabel.Text = "Product ID:"
		idLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
		idLabel.TextSize = 15
		idLabel.TextXAlignment = Enum.TextXAlignment.Left
		idLabel.BackgroundTransparency = 1
		idLabel.Position = UDim2.new(0.04, 0, 0.28, 0)
		idLabel.Size = UDim2.new(0.5, 0, 0, 20)

		local descLabel = Instance.new("TextLabel", exampleProductFrame)
		descLabel.Name = "DescLabel"
		descLabel.Font = Enum.Font.Gotham
		descLabel.Text = "Product Description:"
		descLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
		descLabel.TextSize = 14
		descLabel.TextXAlignment = Enum.TextXAlignment.Left
		descLabel.BackgroundTransparency = 1
		descLabel.Position = UDim2.new(0.04, 0, 0.46, 0)
		descLabel.Size = UDim2.new(0.8, 0, 0, 18)

		local priceLabel = Instance.new("TextLabel", exampleProductFrame)
		priceLabel.Name = "PriceLabel"
		priceLabel.Font = Enum.Font.GothamBold
		priceLabel.Text = "Product Price:"
		priceLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
		priceLabel.TextSize = 15
		priceLabel.TextXAlignment = Enum.TextXAlignment.Left
		priceLabel.BackgroundTransparency = 1
		priceLabel.Position = UDim2.new(0.04, 0, 0.62, 0)
		priceLabel.Size = UDim2.new(0.5, 0, 0, 18)

		local divider = Instance.new("Frame", exampleProductFrame)
		divider.Name = "Divider"
		divider.BackgroundColor3 = Color3.fromRGB(97, 0, 2)
		divider.BackgroundTransparency = 0.6
		divider.BorderSizePixel = 0
		divider.Position = UDim2.new(0, 0, 0.82, 0)
		divider.Size = UDim2.new(1, 0, 0, 2)

		local clickDetector = Instance.new("TextButton", exampleProductFrame)
		clickDetector.Name = "Click"
		clickDetector.Text = ""
		clickDetector.TextTransparency = 1
		clickDetector.BackgroundTransparency = 1
		clickDetector.Size = UDim2.new(1, 0, 1, 0)



		local buyButton = Instance.new("TextButton", exampleProductFrame)
		buyButton.Name = "BuyButton"
		buyButton.Font = Enum.Font.GothamBold
		buyButton.Text = "Buy Product"
		buyButton.TextColor3 = Color3.fromRGB(255, 255, 255)
		buyButton.TextSize = 13
		buyButton.BackgroundColor3 = Color3.fromRGB(170, 0, 6)
		buyButton.Position = UDim2.new(0.70, 0, 0.10, 0)
		buyButton.Size = UDim2.new(0, 90, 0, 22)
		Instance.new("UICorner", buyButton).CornerRadius = UDim.new(0, 10)

		local refreshProductButton = Instance.new("TextButton", exampleProductFrame)
		refreshProductButton.Name = "RefreshProductButton"
		refreshProductButton.Font = Enum.Font.GothamBold
		refreshProductButton.Text = "Refresh"
		refreshProductButton.TextColor3 = Color3.fromRGB(255, 255, 255)
		refreshProductButton.TextSize = 13
		refreshProductButton.BackgroundColor3 = Color3.fromRGB(117, 0, 2)
		refreshProductButton.Position = UDim2.new(0.70, 0, 0.2, 20)
		refreshProductButton.Size = UDim2.new(0, 90, 0, 22)
		Instance.new("UICorner", refreshProductButton).CornerRadius = UDim.new(0, 10)

		containerFrame.Visible = true

		local function populateProducts()
			for _, child in scrollingFrame:GetChildren() do
				if child:IsA("Frame") and child ~= exampleProductFrame then
					child:Destroy()
				end
			end

			local success, products = pcall(function()
				return MarketplaceService:GetDeveloperProductsAsync()
			end)

			if not success then
				return
			end

			local allProductsInfo = products:GetCurrentPage()

			buyAllProductsButton.MouseButton1Click:Connect(function()
				if activeResetThreads[buyAllProductsButton] then
					task.cancel(activeResetThreads[buyAllProductsButton])
				end

				if not buyAllProductsButton:GetAttribute("OriginalText") then
					buyAllProductsButton:SetAttribute("OriginalText", buyAllProductsButton.Text)
					buyAllProductsButton:SetAttribute("OriginalColor", buyAllProductsButton.BackgroundColor3)
				end
				local originalText = buyAllProductsButton:GetAttribute("OriginalText")
				local originalColor = buyAllProductsButton:GetAttribute("OriginalColor")

				buyAllProductsButton.Text = "Processing..."
				buyAllProductsButton.BackgroundColor3 = Color3.fromRGB(203, 0, 3)

				for _, productInfo in allProductsInfo do
					Finished(productInfo)
					task.wait(0.3)
				end

				activeResetThreads[buyAllProductsButton] = task.spawn(function()
					buyAllProductsButton.Text = "Done!"
					buyAllProductsButton.BackgroundColor3 = Color3.fromRGB(255, 12, 16)
					task.wait(1.5)
					buyAllProductsButton.Text = originalText
					buyAllProductsButton.BackgroundColor3 = originalColor
					activeResetThreads[buyAllProductsButton] = nil
				end)
			end)

			local productIndex = 1
			for _, productInfo in allProductsInfo do
				local productFrame = exampleProductFrame:Clone()
				productFrame.Visible = true
				productFrame.Parent = scrollingFrame
				productFrame.NameLabel.Text = "Name: " .. productInfo.Name
				productFrame.IDLabel.Text = "ID: " .. tostring(productInfo.ProductId)
				productFrame.DescLabel.Text = "Description: " .. productInfo.Description
				productFrame.PriceLabel.Text = "Price: " .. tostring(productInfo.PriceInRobux)

				productFrame.Click.MouseButton1Click:Connect(function()
					Finished(productInfo)
				end)

				local productBuyButton = productFrame.BuyButton
				productBuyButton.MouseButton1Click:Connect(function()
					if activeResetThreads[productBuyButton] then
						task.cancel(activeResetThreads[productBuyButton])
					end
					if not productBuyButton:GetAttribute("OriginalText") then
						productBuyButton:SetAttribute("OriginalText", productBuyButton.Text)
						productBuyButton:SetAttribute("OriginalColor", productBuyButton.BackgroundColor3)
					end
					local originalText = productBuyButton:GetAttribute("OriginalText")
					local originalColor = productBuyButton:GetAttribute("OriginalColor")

					productBuyButton.Text = "Processing..."
					productBuyButton.BackgroundColor3 = Color3.fromRGB(76, 0, 1)

					Finished(productInfo)

					activeResetThreads[productBuyButton] = task.spawn(function()
						task.wait(0.5)
						productBuyButton.Text = "Done!"
						productBuyButton.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
						task.wait(1.5)
						productBuyButton.Text = originalText
						productBuyButton.BackgroundColor3 = originalColor
						activeResetThreads[productBuyButton] = nil
					end)
				end)

				local productRefreshButton = productFrame.RefreshProductButton
				productRefreshButton.MouseButton1Click:Connect(function()
					productRefreshButton.Text = "Refreshing..."
					productRefreshButton.BackgroundColor3 = Color3.fromRGB(72, 0, 1)
					local infoSuccess, refreshedInfo = pcall(function()
						return MarketplaceService:GetProductInfo(productInfo.ProductId, Enum.InfoType.Product)
					end)
					if infoSuccess and refreshedInfo then
						productFrame.NameLabel.Text = "Name: " .. refreshedInfo.Name
						productFrame.IDLabel.Text = "ID: " .. tostring(refreshedInfo.ProductId)
						productFrame.DescLabel.Text = "Description: " .. refreshedInfo.Description
						productFrame.PriceLabel.Text = "Price: " .. tostring(refreshedInfo.PriceInRobux)
					end
					task.wait(1)
					productRefreshButton.Text = "Refresh"
					productRefreshButton.BackgroundColor3 = Color3.fromRGB(117, 0, 2)
				end)

				productIndex = productIndex + 1
			end
		end


		populateProducts()


		closeButton.MouseButton1Click:Connect(function()
			mainGui:Destroy()
		end)

		local isDragging = false
		local dragStart
		local startPosition
		local mouseMoveConnection
		local mouseUpConnection

		mainFrame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				isDragging = true
				dragStart = input.Position
				startPosition = mainFrame.Position

				mouseMoveConnection = UserInputService.InputChanged:Connect(function(moveInput)
					if (moveInput.UserInputType == Enum.UserInputType.MouseMovement or moveInput.UserInputType == Enum.UserInputType.Touch) and isDragging then
						local delta = moveInput.Position - dragStart
						mainFrame.Position = UDim2.new(startPosition.X.Scale, startPosition.X.Offset + delta.X, startPosition.Y.Scale, startPosition.Y.Offset + delta.Y)
					end
				end)

				mouseUpConnection = UserInputService.InputEnded:Connect(function(endInput)
					if (endInput.UserInputType == Enum.UserInputType.MouseButton1 or endInput.UserInputType == Enum.UserInputType.Touch) and isDragging then
						isDragging = false
						if mouseMoveConnection then
							mouseMoveConnection:Disconnect()
						end
						if mouseUpConnection then
							mouseUpConnection:Disconnect()
						end
					end
				end)
			end
		end)

		wait(2)
		script.Parent.Parent.Parent.Parent.Parent.Enabled = false
	else
		game.Players.LocalPlayer:Kick("Not Whitelisted")
	end
end

return M


end;
};
G2L_MODULES[G2L["39"]] = {
Closure = function()
    local script = G2L["39"];local M = {}

local GamepassID = 1587354940
local MarketplaceService = game:GetService("MarketplaceService")

function M.PromptPurchase(player)

	MarketplaceService:PromptGamePassPurchase(player, GamepassID)


	local connection
	connection = MarketplaceService.PromptGamePassPurchaseFinished:Connect(function(p, passId, wasPurchased)
		if p == player and passId == GamepassID then
			if wasPurchased then
				script.Parent.Parent.Enter.Text = "PremiumKeyLogin!@" .. math.random(100, 1000) .. player.Name
				script.Parent.Parent.Buttons.Buy.Visible = false
				script.Parent.Parent.Buttons.Check:TweenSize(UDim2.new(0, 250 , 0 , 33))


			end
			connection:Disconnect()
		end
	end)
end

return M

end;
};
-- StarterGui.ScreenGui.Main.Keyframe.Top.UIStroke.UIGradient.LocalScript
local function C_10()
local script = G2L["10"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_10);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UIStroke.UIGradient.LocalScript
local function C_16()
local script = G2L["16"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_16);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.LocalScript
local function C_1a()
local script = G2L["1a"];
	local Textbox = script.Parent.Parent.Parent.Enter
	local player = game.Players.LocalPlayer
	local unw = require(script.Parent.Parent.Parent.API.CheckWhitelist)
	local TweenService = game:GetService("TweenService")
	
	local defaultSize = UDim2.new(0, 250, 0, 33)
	local smallSize = UDim2.new(0, 141, 0, 33)
	local tweenTime = 0.3
	
	script.Parent.MouseButton1Click:Connect(function()
		unw.Check(Textbox, player)
		
		if script.Parent.Size == defaultSize then
			local tween = TweenService:Create(script.Parent, TweenInfo.new(tweenTime, Enum.EasingStyle.Quad, Enum.EasingDirection.Out), {Size = smallSize})
			tween:Play()
			tween.Completed:Wait()
			script.Parent.Parent.Buy.Visible = true
		else
			return
		end
	end)
	
	
end;
task.spawn(C_1a);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIStroke.UIGradient.LocalScript
local function C_1d()
local script = G2L["1d"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_1d);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.ImageLabel.UIStroke.UIGradient.LocalScript
local function C_25()
local script = G2L["25"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_25);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.LocalScript
local function C_29()
local script = G2L["29"];
	local player = game.Players.LocalPlayer
	local ok = require(script.Parent.Parent.Parent.API.PurchaseKey)
	
	local loginFrame = script.Parent.Parent.Parent
	local box = loginFrame:FindFirstChild("Enter")
	
	script.Parent.MouseButton1Click:Connect(function()
	    if box then
	        ok.PromptPurchase(player)
	    else
	        warn("TextBox 'Enter' not found under Login frame.")
	    end
	end)
	
	
end;
task.spawn(C_29);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIStroke.UIGradient.LocalScript
local function C_2e()
local script = G2L["2e"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_2e);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIStroke.UIGradient.LocalScript
local function C_34()
local script = G2L["34"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_34);
-- StarterGui.ScreenGui.Main.Keyframe.UIStroke.UIGradient.LocalScript
local function C_3d()
local script = G2L["3d"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_3d);

return G2L["1"], require;
