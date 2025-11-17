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


-- StarterGui.ScreenGui.Main.Keyframe.Top.ImageLabel.UIListLayout
G2L["b"] = Instance.new("UIListLayout", G2L["8"]);
G2L["b"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["b"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe.Top.ImageLabel.UIPadding
G2L["c"] = Instance.new("UIPadding", G2L["8"]);
G2L["c"]["PaddingLeft"] = UDim.new(0, 60);


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


-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UICorner
G2L["14"] = Instance.new("UICorner", G2L["13"]);
G2L["14"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UIStroke
G2L["15"] = Instance.new("UIStroke", G2L["13"]);
G2L["15"]["Transparency"] = 0.83;
G2L["15"]["Thickness"] = 2;
G2L["15"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UIStroke.UIGradient
G2L["16"] = Instance.new("UIGradient", G2L["15"]);
G2L["16"]["Rotation"] = 20;
G2L["16"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Enter.UIStroke.UIGradient.LocalScript
G2L["17"] = Instance.new("LocalScript", G2L["16"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons
G2L["18"] = Instance.new("Frame", G2L["11"]);
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["Size"] = UDim2.new(0, 363, 0, 52);
G2L["18"]["Position"] = UDim2.new(0.37893, 0, 0.94268, 0);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Name"] = [[Buttons]];
G2L["18"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.UIListLayout
G2L["19"] = Instance.new("UIListLayout", G2L["18"]);
G2L["19"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["19"]["Padding"] = UDim.new(0, 10);
G2L["19"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["19"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["19"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check
G2L["1a"] = Instance.new("TextButton", G2L["18"]);
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 14;
G2L["1a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(39, 39, 39);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1a"]["Size"] = UDim2.new(0, 141, 0, 33);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[Check Key]];
G2L["1a"]["Name"] = [[Check]];
G2L["1a"]["Position"] = UDim2.new(0.22452, 0, 0.01923, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UICorner
G2L["1b"] = Instance.new("UICorner", G2L["1a"]);
G2L["1b"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.LocalScript
G2L["1c"] = Instance.new("LocalScript", G2L["1a"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIStroke
G2L["1d"] = Instance.new("UIStroke", G2L["1a"]);
G2L["1d"]["Transparency"] = 0.83;
G2L["1d"]["Thickness"] = 2;
G2L["1d"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIStroke.UIGradient
G2L["1e"] = Instance.new("UIGradient", G2L["1d"]);
G2L["1e"]["Rotation"] = 67;
G2L["1e"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIStroke.UIGradient.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1e"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.ImageLabel
G2L["20"] = Instance.new("ImageLabel", G2L["1a"]);
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



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIListLayout
G2L["26"] = Instance.new("UIListLayout", G2L["1a"]);
G2L["26"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Right;
G2L["26"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["26"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIPadding
G2L["27"] = Instance.new("UIPadding", G2L["1a"]);
G2L["27"]["PaddingRight"] = UDim.new(0, 10);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy
G2L["28"] = Instance.new("TextButton", G2L["18"]);
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(39, 39, 39);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["28"]["Size"] = UDim2.new(0, 141, 0, 33);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[Buy Key]];
G2L["28"]["Name"] = [[Buy]];
G2L["28"]["Position"] = UDim2.new(0.22452, 0, 0.01923, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UICorner
G2L["29"] = Instance.new("UICorner", G2L["28"]);
G2L["29"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.LocalScript
G2L["2a"] = Instance.new("LocalScript", G2L["28"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIListLayout
G2L["2b"] = Instance.new("UIListLayout", G2L["28"]);
G2L["2b"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Right;
G2L["2b"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["2b"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIPadding
G2L["2c"] = Instance.new("UIPadding", G2L["28"]);
G2L["2c"]["PaddingRight"] = UDim.new(0, 10);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIStroke
G2L["2d"] = Instance.new("UIStroke", G2L["28"]);
G2L["2d"]["Transparency"] = 0.83;
G2L["2d"]["Thickness"] = 2;
G2L["2d"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIStroke.UIGradient
G2L["2e"] = Instance.new("UIGradient", G2L["2d"]);
G2L["2e"]["Rotation"] = 20;
G2L["2e"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIStroke.UIGradient.LocalScript
G2L["2f"] = Instance.new("LocalScript", G2L["2e"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel
G2L["30"] = Instance.new("ImageLabel", G2L["28"]);
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["30"]["ImageTransparency"] = 0.52;
G2L["30"]["Image"] = [[rbxassetid://14134388410]];
G2L["30"]["Size"] = UDim2.new(0, 25, 0, 23);
G2L["30"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["30"]["BackgroundTransparency"] = 1;
G2L["30"]["Position"] = UDim2.new(0.80916, 0, 0.18182, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIAspectRatioConstraint
G2L["31"] = Instance.new("UIAspectRatioConstraint", G2L["30"]);



-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UICorner
G2L["32"] = Instance.new("UICorner", G2L["30"]);
G2L["32"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIStroke
G2L["33"] = Instance.new("UIStroke", G2L["30"]);
G2L["33"]["Transparency"] = 0.83;
G2L["33"]["Thickness"] = 2;
G2L["33"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIStroke.UIGradient
G2L["34"] = Instance.new("UIGradient", G2L["33"]);
G2L["34"]["Rotation"] = 20;
G2L["34"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(0.155, 1),NumberSequenceKeypoint.new(0.737, 1),NumberSequenceKeypoint.new(1.000, 0)};


-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIStroke.UIGradient.LocalScript
G2L["35"] = Instance.new("LocalScript", G2L["34"]);



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
    local script = G2L["38"];--[[ v1.0.0 https://wearedevs.net/obfuscator ]] return(function(...)local Y={"\050\086\111\069\080\043\070\053\055\097\098\051\116\067\057\073\101\103\076\069\078\111\054\099\043\065\102\118\082\073\116\072\069\113\106\090\121\116\054\074\090\106\077\110\098\114\119\048\049\103\117\070\116\066\098\055\102\118\114\108\069\102\065\075\109\105\066\065\103\109\081\102\104\083\048\069\108\102\077\053\043\081\075\052\103\085\089\081\115\049\118\120\119\113\076\081\053\078\061\061";"\076\110\112\081\053\097\089\050\100\071\076\113\076\108\120\117\084\119\057\061","\105\110\112\069\118\107\079\061","\103\111\050\122\076\121\061\061","";"\110\073\074\054\118\111\043\071\100\078\061\061";"\118\082\097\049\065\078\061\061";"\110\073\074\077\105\082\101\061","\084\083\109\071\057\083\077\061";"\122\112\073\108\077\084\061\061";"\110\073\074\117\105\110\043\109\047\056\097\081\118\056\119\061";"\076\056\097\117\114\056\076\069\079\086\043\071\047\056\076\103\047\056\076\113\079\084\061\061";"\051\111\109\097\119\056\105\049";"\100\097\054\070\051\097\043\122\118\082\099\055\118\111\054\119\072\086\057\061";"\105\107\072\073\057\121\061\061","\114\083\076\049\118\082\076\049\057\110\043\109\057\111\052\071","\047\056\097\081\118\056\119\061";"\115\121\061\061";"\053\108\047\111\082\111\109\043\119\083\073\076\119\056\073\067","\047\082\099\050\057\082\072\067";"\057\083\074\090\057\083\097\049","\098\051\099\112\114\069\120\122\043\121\089\078\088\066\086\085\085\103\106\098";"\047\108\109\055\118\103\086\073\089\098\120\116\119\113\043\117\118\083\121\061","\114\056\072\109\118\056\050\061";"\105\049\076\076\119\103\079\073\114\083\054\098\053\048\120\072";"\053\098\043\097\089\070\072\082\076\108\057\061","\115\081\121\071\105\104\122\054\115\121\061\061","\105\083\097\117\105\084\061\061";"\105\083\073\109\047\056\072\122","\114\111\076\117\118\107\105\071","\114\107\043\069\065\082\099\048","\043\056\043\073\076\086\054\049\089\086\121\101\051\049\047\051","\118\056\074\109\105\108\072\049\114\111\071\090\105\050\061\061";"\057\048\071\049\105\084\061\061";"\118\056\076\090","\118\082\047\116\105\111\073\081\043\049\086\098\043\107\109\117","\087\066\086\099\070\121\061\061","\053\108\043\049\114\086\047\071\047\078\061\061";"\110\073\074\048\057\050\061\061","\089\111\097\099\115\051\078\061","\105\111\052\085\118\107\079\061";"\114\111\097\090\105\056\074\117";"\057\083\109\109\114\121\061\061";"\118\070\086\061";"\047\056\074\090\047\082\073\081\105\110\079\061";"\115\076\113\099\072\097\078\050\043\071\120\085\119\070\105\086\089\078\061\061","\100\110\057\101\119\098\047\083\072\056\099\073\072\113\105\075\043\084\061\061";"\118\070\079\061","\047\071\043\117\076\051\109\084\084\076\112\069\047\076\084\099\076\082\079\061";"\043\098\112\111\072\073\119\099\076\097\072\103\076\083\105\067","\089\098\072\065\119\097\047\089\119\119\073\085\043\071\079\050\089\121\061\061";"\047\111\073\050\082\110\112\056\076\070\076\049\114\076\121\050","\053\083\071\103\065\050\061\061";"\047\056\074\098\047\108\112\054\118\111\114\061"}for j,p in ipairs({{-871176+871177,-215096+215150},{-55241-(-55242);-601319+601326};{697152-697144,608099-608045}})do while p[687460+-687459]<p[-475088-(-475090)]do Y[p[964260+-964259]],Y[p[609324+-609322]],p[-259975+259976],p[21956-21954]=Y[p[-613119-(-613121)]],Y[p[232057-232056]],p[379814+-379813]+(-622196+622197),p[231599+-231597]-(382359+-382358)end end local function j(j)return Y[j-(-448010-(-486610))]end do local j=string.sub local p={K=73801-73786;M=972942+-972898,f=485281-485271;Y=-453432-(-453444);["\051"]=765816+-765797;m=-474495-(-474528),q=2634+-2598,W=-166543+166585;v=-388305-(-388332),C=-99329-(-99372),["\050"]=-513741+513789;x=388094-388093;l=-623092+623099;n=413210-413187;i=-32151+32176;["\056"]=-679343-(-679349);b=47178+-47127;Q=762418-762384;z=309650+-309610;L=477144+-477123,t=924255-924197,o=-5330+5368;["\049"]=608179-608127,["\053"]=223600-223582;U=509374-509327,h=488063+-488061,w=-1025304+1025324;A=-1033636+1033662;["\057"]=895323+-895299,k=614927-614872;c=89428+-89371,y=489538+-489506;["\052"]=-819820-(-819869),["\055"]=295963+-295952;Z=125850-125804;g=964169-964134;D=173076+-173017,a=506552-506547;F=539317+-539314;V=251646-251642,P=576839+-576776,T=739124+-739108;["\048"]=-899769+899808,p=-21326+21335;j=-777438-(-777500);["\054"]=647200+-647159,I=329997+-329944;G=108332+-108295;X=-322678-(-322738);d=-42204-(-42234);["\047"]=-332027-(-332056);u=45687+-45642,E=468874+-468824,r=-943769+943797;N=371990-371990;e=166743+-166687,H=969718-969705,["\043"]=490897+-490880;R=-339727-(-339749),S=597716+-597662,B=846096-846065;s=757191-757177,O=-409696+409704;J=248208+-248147}local w=type local H=math.floor local V=table.insert local i=table.concat local b=string.char local Z=Y local f=string.len for Y=887215+-887214,#Z,-727923+727924 do local P=Z[Y]if w(P)=="\115\116\114\105\110\103"then local w=f(P)local l={}local F=37635-37634 local D=665938-665938 local O=-400217-(-400217)while F<=w do local Y=j(P,F,F)local i=p[Y]if i then D=D+i*(-225828+225892)^((275006+-275003)-O)O=O+(767493-767492)if O==597920-597916 then O=1014522-1014522 local Y=H(D/(-522658+588194))local j=H((D%(118584-53048))/(-146900+147156))local p=D%(-31458+31714)V(l,b(Y,j,p))D=1042521+-1042521 end elseif Y=="\061"then V(l,b(H(D/(410267+-344731))))if F>=w or j(P,F+(1002695+-1002694),F+(636264-636263))~="\061"then V(l,b(H((D%(-140748+206284))/(-33634-(-33890)))))end break end F=F+(-350274+350275)end Z[Y]=i(l)end end end return(function(Y,w,H,V,i,b,Z,l,f,O,g,C,s,p,A,F,P,Q,D,r)P,p,F,O,A,f,r,C,l,g,s,Q,D={},function(p,H,V,i)local P,F,N,u,M,E,O,e,L,n,Z,R,G,I,v,m,t,X,T,B,x,c,k,q,U,a,K,W,o,h,D,C,d,y while p do if p<8173987-(-82198)then if p<980880+3617463 then if p<1197641-(-991102)then if p<1297746-444533 then if p<-57785+494778 then if p<106543-(-205836)then if p<-756066-(-1006286)then p=-49222+3100363 O=nil h=nil c=nil else p=841222+11042352 end else p=G Z=e p=e and 11027922-(-12402)or 421628+4478444 end else if p<-384175-(-979218)then d=-966488+966489 o=#M p=11307948-695973 n=-457888-(-457889)k=D(d,o)d=h(M,k)o=f[T]X=d-n L=c(X)k=nil o[d]=L d=nil else P=j(984708-946098)D=59719+-59719 p=Y[P]F=f[V[1007253-1007245]]P=p(F,D)p=14620088-(-522754)end end else if p<1683206-583910 then if p<1673587-648917 then if p<820910-(-123765)then k={}d=l()f[d]=k X=j(-865869+904492)o=s(116057+2161466,{d;e;G;C})k=l()n={}f[k]=o C=A(C)L=l()o={}M=nil a=nil c=nil f[L]=o W=j(-533009+571627)I=nil N=nil B=j(796758+-758145)o=Y[X]D=nil x=f[L]p=Y[j(936270+-897640)]u={[B]=x,[W]=a}X=o(n,u)D={}h=nil f[O]=X o=Q(-315217+13721678,{L,d;T,e;G,k})h=j(-806102+844718)k=A(k)G=A(G)d=A(d)T=A(T)f[F]=o e=A(e)C=g(-466425+11645289,{O;F})Z={D}D[h]=C L=A(L)else p={}f[V[-1007187-(-1007189)]]=p C=223943+35184371864889 c=-279615+279870 G=-12800+12801 p=-511883+3437366 Z=f[V[-999950+999953]]I=j(-484497-(-523135))O=Z Z=F%C f[V[824696+-824692]]=Z h=F%c c=1044404-1044402 C=h+c f[V[876273-876268]]=C c=Y[I]I=j(1022506-983864)h=c[I]c=h(P)h=j(555858-517246)I=248391+-248390 D[F]=h h=-581131+581339 N=G G=765837-765837 e=c T=N<G G=I-N end else c=A(c)D=A(D)T=nil d=A(d)e=A(e)C=A(C)k=nil O=A(O)G=A(G)F=A(F)c=j(-591204-(-629818))M=nil F=nil N=nil I=nil h=nil h=j(318707-280093)D=nil d=-498247+498503 G=l()I=j(-712956-(-751580))o=d O=l()f[O]=F F=l()f[F]=D e=j(776472+-737834)C=Y[h]h=j(246867-208219)D=C[h]C=l()f[C]=D h=Y[c]c=j(-932037+970686)D=h[c]c=Y[I]p=6882006-(-573954)I=j(64001+-25364)h=c[I]I=Y[e]e=j(24988+13662)c=I[e]I=789485-789485 e=l()N={}f[e]=I d=-559913+559914 T=l()I=-764384-(-764386)f[G]=I I={}M={}f[T]=N L=d d=-585154+585154 N=617148-617148 k=748216-748215 X=L<d d=k-L end else if p<2305855-212643 then D=f[V[-394487-(-394493)]]F=D==P p=214236+11327080 Z=F else y=80127+-80126 q=W[y]E=p y=false a=q==y p=a and-258045+6330967 or 5570450-(-245751)K=a end end end else if p<2677069-(-378060)then if p<915113+1917874 then if p<110879+2617545 then if p<2650728-(-53306)then P=f[V[-1004190-(-1004191)]]Z=#P P=968769-968769 p=Z==P p=p and 9665886-(-499796)or 8346776-(-702285)else R=1017573-1017572 f[F]=K y=f[u]q=y+R a=W[q]E=N+a a=-725751+726007 p=E%a q=f[n]N=p a=T+q q=-515740+515996 E=a%q T=E p=11147+8653691 end else f[F]=v p=f[F]p=p and-387008+8476256 or 8699690-68551 end else if p<-849779+3850812 then M=not T G=G+N I=G<=e I=M and I M=G>=e M=T and M I=M or I M=9378988-966806 p=I and M I=-747195-(-926954)p=p or I else Z={F}p=Y[j(1702+36907)]end end else if p<111212+3288999 then if p<565013+2654726 then f[F]=Z p=7903047-(-761791)else F=l()O=l()p=true D=j(-465441+504079)c=j(-519123-(-557754))P=H f[F]=p Z=Y[D]D=j(-996405-(-1035041))p=Z[D]D=l()f[D]=p p=Q(8469460-946622,{})C=l()f[O]=p I=Q(13348455-874090,{C})p=false f[C]=p h=Y[c]c=h(I)p=c and 6491873-517857 or 785605+3787511 Z=c end else if p<930716+3363631 then F=f[V[637877-637874]]D=905323+-905322 P=F~=D p=P and-920759+16321404 or-326029+11354127 else I=j(567743-529119)h=Z c=j(336590+-297976)Z=Y[c]T=j(857611+-818987)c=j(-33662-(-72311))p=Z[c]c=l()f[c]=p Z=Y[I]I=j(419234+-380606)p=Z[I]N=Y[T]e=N I=p G=p p=N and 6989499-(-384796)or-20674+345347 end end end end else if p<942787+6178340 then if p<5040770-(-941396)then if p<5422584-(-380092)then if p<-66737+5244665 then if p<-595314+5624118 then G=j(284734+-246107)e=Y[G]p=573109+10467215 Z=e else t=f[F]v=t p=t and 6820830-(-991266)or-148760+2899749 end else D=D+C c=not h F=D<=O F=c and F c=D>=O c=h and c F=c or F c=858668+6894583 p=F and c F=818033+7613166 p=p or F end else if p<-22488+5958400 then p=E Z=K p=3618412-459017 else p=3630964-(-942152)h=f[C]Z=h end end else if p<246767+6675872 then if p<-208270+6675196 then if p<-96971+6308934 then y=1032820-1032818 q=W[y]y=f[x]a=q==y p=6664485-848284 K=a else X=j(479735-441121)L=l()f[L]=v Z=Y[X]X=j(58023+-19374)p=Z[X]u=-555222+555477 n=-195346+195446 m=-354924-(-364924)X=425180+-425179 Z=p(X,n)X=l()f[X]=Z p=f[c]n=260385+-260385 W=-1025226-(-1025228)Z=p(n,u)x=646578+-646577 n=l()f[n]=Z p=f[c]u=976960-976959 B=f[X]Z=p(u,B)u=l()f[u]=Z Z=f[c]B=Z(x,W)Z=571895-571894 p=B==Z Z=j(-390982-(-429616))R=-906338-(-906338)W=j(816273+-777648)B=l()a=j(-266246+304853)f[B]=p E=Y[a]q=f[c]y={q(R,m)}a=E(w(y))E=j(600487-561862)p=j(-668610+707232)K=a..E p=k[p]x=W..K p=p(k,Z,x)W=j(-67068+105699)x=l()K=Q(877458+10709552,{c,L,G,D,F;d,B;x;X;u,n;e})f[x]=p Z=Y[W]W={Z(K)}p={w(W)}W=p p=f[B]p=p and 16110502-639695 or-436471+14562105 end else Z=j(-348158-(-386810))e=r(-231593+7283975,{})O=j(5544-(-33063))I=j(-176043+214674)p=Y[Z]P=f[V[-797894+797898]]D=Y[O]c=Y[I]I={c(e)}c=-754831+754833 h={w(I)}C=h[c]O=D(C)D=j(434353+-395719)F=P(O,D)P={F()}Z=p(w(P))F=f[V[780667+-780662]]P=Z p=F and 2239665-243771 or 12379221-837905 Z=F end else if p<7244640-200882 then p=-525674+17138079 else D=-646257+13607748 F=j(-459784+498431)Z=-925375+4683618 P=F^D p=Z-P Z=j(409839-371218)P=p p=Z/P Z={p}p=Y[j(-909335+947938)]end end end else if p<6872271-(-701968)then if p<-703373+8102265 then if p<7831496-659595 then if p<6646128-(-506597)then v=v+U L=not o Z=v<=t Z=L and Z L=v>=t L=o and L Z=L or Z L=932673+5317540 p=Z and L Z=5424406-364485 p=p or Z else p=24443+3026698 end else M=j(870040-831416)T=Y[M]M=j(-571894+610521)N=T[M]p=1204756-880083 e=N end else if p<7993857-484025 then d=d+L k=d<=o n=not X k=n and k n=d>=o n=X and n k=n or k n=10464112-677244 p=k and n k=587892+8999250 p=p or k else Z=j(-591287+629897)P=j(41514+-2895)p=Y[Z]Z=p(P)p=Y[j(509946-471320)]Z={}end end else if p<7192468-(-773922)then if p<-507935+8279972 then I=770243+-770243 p=f[V[931109-931108]]F=D e=-316822-(-317077)c=p(I,e)p=6316145-977886 P[F]=c F=nil else p=3290972-539983 t=N==T v=t end else if p<8090106-54671 then a=-353195-(-353196)E=W[a]K=E p=-634482+3342700 else p=328461-(-745383)end end end end end else if p<904401+10372487 then if p<259937+9658321 then if p<-402919+9076875 then if p<7697217-(-893271)then if p<8981080-536808 then if p<734690+7679262 then U=j(251415+-212777)I=G t=Y[U]U=j(144152+-105511)v=t[U]t=v(P,I)v=f[V[-547904+547910]]U=v()d=t+U k=d+h d=-956794+957050 p=-466253+3391736 M=k%d h=M U=-15215-(-15216)d=D[F]t=h+U v=O[t]k=d..v I=nil D[F]=k else p=f[V[574174-574164]]F=f[V[-827902+827913]]P[p]=F p=f[V[-120152-(-120164)]]F={p(P)}Z={w(F)}p=Y[j(1006146+-967542)]end else p=Y[j(-67198-(-105851))]Z={}end else if p<8984830-334346 then p=true p=-755887+9582982 else W=nil B=A(B)p=7621001-497886 X=A(X)n=A(n)x=A(x)L=A(L)u=A(u)end end else if p<9527556-6274 then if p<-802819+9884324 then if p<-970933+9836933 then p=s(7417359-491114,{O})t={p()}p=Y[j(-676654+715256)]Z={w(t)}else D=j(-693377+732001)F=Y[D]D=j(490824-452187)P=F[D]p=Y[j(256686-218047)]D=f[V[869794+-869793]]F={P(D)}Z={w(F)}end else F=f[V[517240+-517238]]p=-564541+17115419 D=f[V[-598241-(-598244)]]P=F==D Z=P end else if p<931911+8809908 then p=1293099-839905 d=#M o=-98944+98944 k=d==o else k=d n=k M[k]=n k=nil p=8305976-850016 end end end else if p<11748241-1039100 then if p<10987599-403973 then if p<10401018-(-52539)then if p<11088290-809485 then D=-45915+46156 F=f[V[689667+-689665]]P=F*D F=3845872324462-(-259985)Z=P+F P=907049+35184371181783 F=1017469-1017468 p=Z%P f[V[-1040764-(-1040766)]]=p P=f[V[607142+-607139]]Z=P~=F p=-778562+11806660 else p=f[c]o=168361-168355 U=-942095-(-942096)t=p(U,o)o=j(-609312+647913)p=j(-757102-(-795703))Y[p]=t U=Y[o]o=49816+-49814 p=U>o p=p and 14796159-326384 or 16523879-936575 end else D=nil Z={}p=Y[j(-538045-(-576688))]P=nil F=nil end else if p<-232854+10843050 then Z=j(755686-717046)G=j(828159+-789551)p=Y[Z]C=j(781349-742714)O=Y[C]N=34077239196187-736287 c=f[V[-408415+408416]]I=f[V[-931710-(-931712)]]e=I(G,N)h=c[e]c=j(981081+-942436)c=O[c]C={c(O,h)}Z=p(w(C))p=Z()p=11017167-531589 else d=#M o=-342076+342076 k=d==o p=k and 263778+623017 or 983140-529946 end end else if p<-188685+11218866 then if p<150624+10741652 then p=Y[j(-743872-(-782477))]Z={}else F=f[V[-625587+625590]]p=3619583-(-128228)D=-119983+120059 P=F*D F=607113-606856 Z=P%F f[V[-71013-(-71016)]]=Z end else if p<10774482-(-344498)then e=l()G=-617819+617822 N=867755-867690 k=s(-936611+13661139,{})f[e]=Z p=f[c]Z=p(G,N)G=l()p=-599902-(-599902)f[G]=Z N=p p=-236384+236384 T=p M=j(1045139-1006508)Z=Y[M]M={Z(k)}Z=425329+-425327 p={w(M)}M=p p=M[Z]k=p Z=j(482456+-443804)p=Y[Z]U=j(-699967-(-738574))d=f[D]t=Y[U]U=t(k)t=j(480081-441447)v=d(U,t)d={v()}Z=p(w(d))d=l()f[d]=Z Z=-350600+350601 p=-230392+7353507 v=f[G]t=v v=-586228+586229 U=v v=-810171-(-810171)o=U<v v=Z-U else N=12222086100134-(-369045)D=f[V[-119688+119689]]h=j(1002925+-964281)c=588772+24271944953922 P=H[545710+-545709]O=f[V[586960-586958]]C=O(h,c)Z=D[C]C=j(-714885+753523)F=H[671968-671966]p=F[Z]D=p O=Y[C]h=f[V[-288294-(-288295)]]c=f[V[230032-230030]]G=606426+31864331614491 e=j(147413+-108796)I=c(e,G)C=h[I]Z=O[C]c=f[V[-171929-(-171930)]]G=j(566040-527429)I=f[V[-272862-(-272864)]]e=I(G,N)h=c[e]C=P[h]O=Z(C,D)Z=nil p=O~=Z p=p and 11394121-791471 or 13368095-636738 end end end end else if p<14392563-(-157714)then if p<286044+12440519 then if p<12100026-8498 then if p<12308778-693986 then if p<11761878-196754 then f[V[-247736-(-247741)]]=Z p=768761+13488648 P=nil else C=-642916+642918 O=511199-511198 F=f[V[34690+-34689]]D=F(O,C)F=830382-830381 P=D==F Z=P p=P and 16918932-368054 or 9908672-470195 end else p=true p=p and-958485+11317831 or 30149+8555614 end else if p<324143+12313623 then Z={}p=true f[V[827477+-827476]]=p p=Y[j(766198-727566)]else Z=637325+11979683 F=j(-241527+280160)D=197653+4057708 P=F^D p=Z-P Z=j(121432+-82812)P=p p=Z/P Z={p}p=Y[j(842950+-804296)]end end else if p<15096557-957421 then if p<12880605-(-634525)then if p<12680161-(-360865)then I=31356397221044-228267 c=j(-76783-(-115412))p=j(965278-926672)p=F[p]O=f[V[521398+-521397]]C=f[V[1033874-1033872]]h=C(c,I)Z=O[h]p=p(F,Z)p=-694502+11180080 else P=H[-427089-(-427090)]F=H[-822269-(-822271)]p=f[V[699400+-699399]]D=p p=D[F]p=p and 7431733-261625 or 1966638-1010416 end else E=f[F]K=E p=E and 7840840-(-146049)or 2546231-(-161987)end else if p<239016+14227612 then p=f[V[321860+-321853]]p=p and 960865-141822 or-628973+15771815 else U=j(-70496+109103)p=Y[U]L=j(-285667+324318)o=Y[L]U=p(o)p=j(-280188-(-318789))Y[p]=U p=17013436-575240 end end end else if p<-8989+15534590 then if p<15574778-180471 then if p<-366277+15550850 then if p<14130718-(-979893)then P=j(302938-264287)Z=j(609079-570478)p=Y[Z]Z=Y[P]P=j(965639-926988)Y[P]=p P=j(-397263-(-435864))Y[P]=Z P=f[V[-108125-(-108126)]]p=67424+16544981 F=P()else D=f[V[-321579-(-321588)]]O=D F=623088+-623087 D=-51152+51153 C=D p={}P=p D=-138476+138476 h=C<D p=-145778+5484037 D=F-C end else p=true p=p and 771645-486523 or 8064318-(-762777)end else if p<-358071+15828118 then D=-715327-(-715359)F=f[V[-90804-(-90807)]]P=F%D e=-734156-(-734158)N=-1045826-(-1045839)O=f[V[404011+-404007]]c=f[V[-719040-(-719042)]]k=f[V[-373849+373852]]M=k-P k=-451672-(-451704)T=M/k G=N-T I=e^G h=c/I C=O(h)O=4294592989-(-374307)N=-578438-(-578694)I=-926965+926966 D=C%O C=-298990+298992 O=C^P F=D/O O=f[V[-822326-(-822330)]]e=-767669-(-767925)c=F%I I=703928+4294263368 P=nil h=c*I c=222121+-156585 C=O(h)O=f[V[588640+-588636]]h=O(F)F=nil D=C+h C=-888243-(-953779)O=D%C h=D-O C=h/c c=-97147-(-97403)h=O%c I=O-h c=I/e O=nil e=-799737-(-799993)I=C%e p=-419777+9468838 D=nil G=C-I e=G/N C=nil G={h,c;I;e}e=nil h=nil f[V[-673806+673807]]=G c=nil I=nil else K=f[F]p=K and 3069982-942174 or 4136692-977297 Z=K end end else if p<348954+16129780 then if p<15705117-(-649490)then o=j(-303492-(-342093))p=Y[o]o=j(771427+-732776)Y[o]=p p=-102670+16540866 else p=11401450-(-482124)end else if p<-693246+17249181 then p=Z and 435709+6053045 or 317604+13939805 else p=true p=p and 15532831-566297 or 10358897-(-446742)end end end end end end end p=#i return w(Z)end,-147569+147569,function(Y)local j,p=-1022493-(-1022494),Y[-437864-(-437865)]while p do P[p],j=P[p]-(27084+-27083),(119857+-119856)+j if P[p]==-814287-(-814287)then P[p],f[p]=nil,nil end p=Y[j]end end,function(Y)P[Y]=P[Y]-(369680-369679)if 419416+-419416==P[Y]then P[Y],f[Y]=nil,nil end end,{},function(Y,j)local w=D(j)local H=function(H,V,i,b)return p(Y,{H;V,i,b},j,w)end return H end,function(Y,j)local w=D(j)local H=function(...)return p(Y,{...},j,w)end return H end,function()F=F+(-597810+597811)P[F]=-186440-(-186441)return F end,function(Y,j)local w=D(j)local H=function(H,V,i,b,Z,f)return p(Y,{H;V;i;b,Z;f},j,w)end return H end,function(Y,j)local w=D(j)local H=function()return p(Y,{},j,w)end return H end,function(Y,j)local w=D(j)local H=function(H,V)return p(Y,{H,V},j,w)end return H end,function(Y)for j=-526534+526535,#Y,-554510-(-554511)do P[Y[j]]=(-183652-(-183653))+P[Y[j]]end if H then local p=H(true)local w=i(p)w[j(-1046709+1085322)],w[j(-770259+808905)],w[j(-27313+65928)]=Y,O,function()return 922768+1165418 end return p else return V({},{[j(-728410+767056)]=O;[j(-507746-(-546359))]=Y;[j(-72675+111290)]=function()return 1838969-(-249217)end})end end return(C(3322365-18748,{}))(w(Z))end)(getfenv and getfenv()or _ENV,unpack or table[j(83243-44616)],newproxy,setmetatable,getmetatable,select,{...})end)(...)
end;
};
G2L_MODULES[G2L["39"]] = {
Closure = function()
    local script = G2L["39"];--[[ v1.0.0 https://wearedevs.net/obfuscator ]] return(function(...)local V={"\078\050\086\108\108\085\108\049\090\111\108\119\072\112\109\089\069\106\061\061","\098\053\068\084\102\081\077\104\119\081\053\086\072\055\075\087\111\106\061\061";"\069\099\108\118\113\071\061\061","\113\051\068\055\069\106\061\061";"";"\107\071\051\048\073\048\066\054","\078\097\068\043\053\050\090\082\050\053\053\056\050\050\048\103";"\113\120\077\074\113\120\103\055","\102\066\113\120\068\116\103\103","\101\114\048\065\070\048\106\061";"\113\068\119\116\076\087\103\089\078\106\061\061","\068\077\099\122\105\084\117\085\055\098\065\071\080\073\106\081\110\103\120\078\065\099\119\066";"\053\081\119\086\083\111\079\061";"\083\097\085\061","\113\120\109\109\073\071\061\061","\078\100\119\048\057\070\061\061";"\081\055\052\049\053\118\048\101\072\053\119\076\078\056\119\053\078\122\079\061";"\081\082\048\117\083\047\080\055\119\120\103\075\069\053\080\109\073\099\108\106\090\047\048\122\076\112\103\087\069\106\061\061";"\078\101\113\052\053\118\113\118\069\120\048\085\053\081\054\118\050\101\078\061";"\078\056\090\047\078\082\069\089\113\050\119\065\053\085\053\056\076\050\110\061","\113\071\052\074";"\098\055\070\052\090\110\102\120\074\106\061\061";"\050\101\079\055\106\120\085\055\050\101\052\098\102\050\118\066\076\070\061\061";"\078\097\103\066\108\120\109\086\098\053\048\103\081\101\049\065\072\106\061\061","\081\082\048\117\083\047\080\055\081\082\053\065\113\120\109\109\073\120\081\061","\121\084\112\112\080\106\056\047\118\083\113\112\043\099\085\101\074\067\111\104\114\075\113\061","\073\101\053\075\083\099\069\068","\106\120\077\074\083\101\053\122\090\070\061\061","\066\108\099\079\102\106\061\061","\119\047\068\103\108\111\048\120\083\120\071\089\119\099\048\054\083\071\061\061","\083\112\053\074";"\073\099\119\065\076\050\054\051";"\119\112\068\087\113\120\077\074\083\101\053\122\090\070\061\061","\090\050\054\089\113\050\108\100";"\085\116\102\049\122\057\054\043\052\089\061\061","\069\120\103\075\069\106\061\061";"\069\101\119\052\090\082\079\099\106\068\103\117\076\051\106\087\081\089\061\061";"\119\050\053\051";"\072\087\109\074\078\120\053\051\102\103\119\084","\101\089\085\048\089\080\119\103","\053\112\103\075\073\112\053\065\079\085\119\068\090\112\053\122\090\112\053\056\079\106\061\061";"\116\104\117\114","\081\102\079\090\071\080\079\113\076\106\061\061";"\073\120\053\055\083\050\053\055\113\047\119\109\113\101\052\068","\083\097\079\061","\073\112\108\109\083\112\089\061","\083\118\069\052\069\120\055\052\050\050\109\113\076\055\056\065";"\102\047\090\111\081\101\118\054\069\081\066\120\073\055\068\066\102\071\061\061","\098\115\071\068\069\084\066\086\098\071\061\061","\107\052\066\055\104\080\052\077";"\098\071\061\061","\090\112\077\074\090\050\118\115\069\047\079\061","\073\120\108\065\076\047\080\055";"\053\055\077\055\106\053\069\055\073\053\073\061","\119\120\053\055\081\120\053\065\090\101\068\122\069\106\061\061";"\047\118\077\049\069\050\043\061";"\090\112\077\087\090\082\048\086\083\101\073\061";"\075\086\112\116\079\043\049\061";"\069\047\048\065\083\099\079\061";"\083\050\103\055\076\070\061\061";"\073\101\103\074\069\112\077\075","\075\051\072\055\109\089\113\068";"\076\082\048\086\069\082\080\119\069\120\052\075\069\056\106\120","\106\071\105\114\068\084\086\111";"\053\082\090\068\069\050\054\111\076\047\086\068";"\090\112\103\115\083\112\081\061";"\069\101\052\117\083\099\079\061","\047\118\077\075\069\047\119\109\090\112\103\115\083\112\081\061","\118\109\079\047\052\107\054\087\081\050\056\113\047\047\047\068\080\056\069\115\068\057\120\075\084\105\055\108\119\106\121\074\111\121\104\082\077\090\113\051";"\090\069\120\081\107\051\070\085","\069\120\118\109\090\112\108\066";"\047\118\077\086\083\101\119\068\102\070\061\061","\047\118\077\051\113\089\061\061"}for l,r in ipairs({{644567-644566;-453265-(-453338)},{-95408-(-95409);519980-519938},{-1012807+1012850,-961294+961367}})do while r[-332138+332139]<r[367475-367473]do V[r[-890140-(-890141)]],V[r[-359907-(-359909)]],r[-994897-(-994898)],r[-1042444+1042446]=V[r[-234379-(-234381)]],V[r[708232-708231]],r[952306-952305]+(1039383+-1039382),r[583500+-583498]-(774924+-774923)end end local function l(l)return V[l-(245160-215913)]end do local l=string.len local r=table.concat local Q=string.sub local W={U=616835-616831,I=915951+-915923;d=-725766-(-725809);["\052"]=-31681+31730;i=-327947-(-328005);Z=673291+-673262;Y=-965035+965083;S=-402754-(-402781);g=-879223-(-879228),A=535248-535198,b=1017793-1017779,o=145138-145119;N=-429272+429284;L=-324959-(-324985),["\053"]=852866+-852845,["\048"]=-309402+309411;z=-649455+649490,a=-121038-(-121041),["\056"]=473776+-473740,C=861350-861319,w=71454-71437,["\043"]=-664257-(-664313),W=-533295+533346;y=-574790-(-574852),x=-274647+274701,D=569101+-569064;B=72835+-72795;v=-101475-(-101528);G=1011385-1011353;X=-478199+478209,f=-11565+11595,m=74231+-74198;["\051"]=225420-225381;q=-680388-(-680412),E=230915-230890;O=-131001-(-131009);V=-970344+970385,s=744540-744506,T=-891835-(-891837);Q=-65643-(-65663),R=850400-850393,h=732071+-732060,k=-108451-(-108514),n=756829+-756769;F=-927747-(-927747),t=350907+-350892;J=-73779+73825;["\047"]=297510+-297487,H=681058+-681040;r=257253-257211,u=-904043-(-904090),["\054"]=-971065-(-971122),e=-131234-(-131272);p=-673767+673773,["\057"]=696969-696910;["\049"]=-509471-(-509515);M=-255209-(-255270);["\055"]=562792+-562740,l=-231230+231243;c=774514-774459,K=-132750-(-132795),j=842250-842234;P=376413+-376412,["\050"]=364616-364594}local N=math.floor local h=string.char local p=table.insert local S=V local Y=type for V=-727254+727255,#S,-380827+380828 do local u=S[V]if Y(u)=="\115\116\114\105\110\103"then local Y=l(u)local k={}local s=951479+-951478 local g=416368-416368 local f=297856+-297856 while s<=Y do local V=Q(u,s,s)local l=W[V]if l then g=g+l*(-151205-(-151269))^((-196156+196159)-f)f=f+(766489-766488)if f==-231744-(-231748)then f=272948+-272948 local V=N(g/(-1042464+1108000))local l=N((g%(-341323+406859))/(790372+-790116))local r=g%(-265976+266232)p(k,h(V,l,r))g=217000+-217000 end elseif V=="\061"then p(k,h(N(g/(689609-624073))))if s>=Y or Q(u,s+(-134242-(-134243)),s+(-978802-(-978803)))~="\061"then p(k,h(N((g%(1024323+-958787))/(192818+-192562))))end break end s=s+(888846-888845)end S[V]=r(k)end end end return(function(V,Q,W,N,h,p,S,g,y,k,G,q,f,O,r,j,Y,v,s,c,X,u)G,c,g,q,X,u,j,r,Y,y,f,v,k,s,O=function(V)u[V]=u[V]-(281191-281190)if-1012690+1012690==u[V]then u[V],Y[V]=nil,nil end end,function(V,l)local Q=g(l)local W=function(W,N,h,p,S,Y,u)return r(V,{W,N;h,p,S,Y;u},l,Q)end return W end,function(V)for l=-409801+409802,#V,-485271-(-485272)do u[V[l]]=(959654-959653)+u[V[l]]end if W then local r=W(true)local Q=h(r)Q[l(1010665+-981377)],Q[l(411734-382445)],Q[l(-41438-(-70710))]=V,f,function()return-1023916+212863 end return r else return N({},{[l(256048-226759)]=f;[l(-841793-(-871081))]=V;[l(307990-278718)]=function()return 172486-983539 end})end end,function(V,l)local Q=g(l)local W=function(W,N,h,p,S)return r(V,{W;N;h;p;S},l,Q)end return W end,function(V,l)local Q=g(l)local W=function(W,N)return r(V,{W;N},l,Q)end return W end,{},function(V,l)local Q=g(l)local W=function(W,N,h,p,S,Y)return r(V,{W;N,h;p;S;Y},l,Q)end return W end,function(r,W,N,h)local o,Z,I,J,M,T,R,S,e,P,g,E,B,m,x,L,s,f,t,U,D,H,b,i,n,d,F,u,C,O,w,a,K,z while r do if r<8084313-761678 then if r<4098637-571076 then if r<-521707+2296730 then if r<1131527-359618 then if r<-70412+681320 then if r<1592225-993042 then if r<1083749-792651 then g=305573-305541 s=Y[N[389103+-389100]]F=329316+-329314 u=s%g f=Y[N[415668-415664]]m=652065-652052 n=Y[N[276140+-276138]]a=Y[N[-382163-(-382166)]]R=a-u a=-848122-(-848154)H=R/a T=m-H E=F^T b=n/E E=-828942-(-828943)O=f(b)f=408525+4294558771 g=O%f O=286634-286632 f=O^u s=g/f f=Y[N[-844257+844261]]m=-720432-(-720688)n=s%E E=-360497+4295327793 b=n*E O=f(b)f=Y[N[-246264-(-246268)]]F=790503+-790247 n=-367652+433188 u=nil b=f(s)s=nil g=O+b O=196177+-130641 f=g%O b=g-f O=b/n n=387922+-387666 r=-183649+12881644 b=f%n E=f-b f=nil n=E/F F=-81240+81496 g=nil E=O%F T=O-E F=T/m T={b;n,E,F}E=nil n=nil F=nil O=nil b=nil Y[N[909679-909678]]=T else Z=-142223+142224 e=#R a=g(Z,e)U=1045092-1045091 Z=b(R,a)e=Y[H]a=nil i=Z-U d=n(i)r=854690+7680660 e[Z]=d Z=nil end else Y[s]=z r=Y[s]r=r and 952025+15403890 or 16306560-(-388063)end else if r<836750-113298 then r=-814954+15792442 s=Y[N[169379-169377]]g=Y[N[127140+-127137]]u=s==g S=u else g=-684380+2892748 s=l(797224-767954)S=-432500+14514053 u=s^g r=S-u u=r S=l(-806370+835670)r=S/u S={r}r=V[l(256098-226802)]end end else if r<-54250+1649785 then if r<2264383-786072 then if r<540831-(-468410)then n=nil f=nil r=7880765-(-1002522)b=nil else g=l(357974+-328726)u=W s=k()r=true Y[s]=r S=V[g]g=l(920989+-891702)r=S[g]g=k()Y[g]=r r=q(9953344-211142,{})f=k()n=l(387678-358416)Y[f]=r O=k()r=false E=q(4932612-13076,{O})Y[O]=r b=V[n]n=b(E)S=n r=n and 6107848-394970 or 10202095-(-209899)end else s=Y[N[38158-38155]]g=369293+-369218 u=s*g s=-731163+731420 r=-402304+9172954 S=u%s Y[N[786661+-786658]]=S end else if r<474168+1231640 then r=5055984-74458 T=l(173570-144320)F=V[T]S=F else K=l(-570384+599657)r=V[K]d=l(-548551-(-577854))e=V[d]K=r(e)r=l(-688451+717712)V[r]=K r=4985012-554818 end end end else if r<442426+1887982 then if r<3062494-993965 then if r<-245015+2205190 then if r<1754819-(-30441)then s=Y[N[44208-44207]]O=-682056+682058 f=-859648-(-859649)g=s(f,O)s=271661-271660 u=g==s S=u r=u and 14029182-(-948306)or 995750+-272688 else r=931788+2325248 end else r=true r=r and-302402+10437178 or-894032+4833618 end else if r<1859149-(-393949)then r=8415031-(-468256)else r=v(2521420-646186,{f})M={r()}S={Q(M)}r=V[l(-2413-(-31725))]end end else if r<3075001-(-116380)then if r<3192682-636371 then if r<1881820-(-560940)then L=Y[s]S=L r=L and 286784+10183331 or 533966+10695426 else Z=Z+d U=not i a=Z<=e a=U and a U=Z>=e U=i and U a=U or a U=16088121-625651 r=a and U a=3058972-(-473873)r=r or a end else r=V[l(415385-386076)]S={}end else if r<4161139-890933 then r=true r=r and 7129850-(-166021)or-87406+2802118 else r=7671449-(-264954)O=Y[N[608160-608158]]f=s==O S=f end end end end else if r<5442026-(-131960)then if r<-58615+4539992 then if r<3971401-(-320773)then if r<4347592-268726 then if r<702095+2931261 then Z=#R e=-731069-(-731069)a=Z==e r=-961737+1543993 else S={}r=V[l(-399977-(-429267))]end else r=t S=L r=189725+11039667 end else if r<112506+4266675 then t=Y[s]r=t and 9586275-(-425835)or 13713629-91795 L=t else r=-978670+2951018 end end else if r<-392132+5584734 then if r<-161031+5092435 then if r<45757+4870832 then r=-599421+7964490 g=Y[N[734523-734517]]s=g==u S=s else r=true Y[N[-612259-(-612260)]]=r S={}r=V[l(959438-930125)]end else a=X(1215559-473930,{})F=k()T=-288935+288938 Y[F]=S r=Y[n]m=172890+-172825 S=r(T,m)r=247768-247768 T=k()m=r Y[T]=S r=-155209-(-155209)R=l(386781+-357519)S=V[R]R={S(a)}H=r r={Q(R)}R=r S=-737526-(-737528)K=l(378511+-349238)r=R[S]S=l(-247922+277190)a=r r=V[S]Z=Y[g]M=V[K]K=M(a)M=l(-172114-(-201379))z=Z(K,M)Z={z()}S=r(Q(Z))Z=k()Y[Z]=S S=280823-280822 z=Y[T]M=z z=943390-943389 K=z z=468858+-468858 r=-979280+11471717 e=K<z z=S-K end else if r<-774471+6339888 then d=G(d)o=G(o)i=G(i)U=G(U)J=nil r=782228+9710209 x=G(x)D=G(D)else S=l(-633295-(-662544))r=Y[N[-373410-(-373415)]]S=r[S]S=S(r)r=545246+10190802 end end end else if r<-492091+6797171 then if r<830207+5247656 then if r<5152252-(-773716)then if r<-36661+5876008 then r=10335899-(-76095)b=Y[O]S=b else F=-810197+810452 r=Y[N[-769053-(-769054)]]s=g E=945222+-945222 n=r(E,F)u[s]=n r=-402390+16158342 s=nil end else r=true r=r and 687602+14797595 or 491701+1784755 end else if r<5609572-(-474072)then C=361555+-361553 w=J[C]C=Y[x]r=5229504-1031365 B=w==C L=B else s=W[-1043994-(-1043996)]u=W[418276+-418275]O=Y[N[-270522-(-270523)]]g=W[-745410-(-745413)]f=u==O S=f r=f and-863153+4136080 or 7071643-(-864760)end end else if r<7447468-297664 then if r<1031767+6064094 then if r<779817+5698336 then r=Y[N[548058+-548051]]r=r and 923380+7007954 or 17352473-1026975 else r={}O=35184371654901-(-433931)Y[N[-498141+498143]]=r S=Y[N[798409-798406]]r=-146855+9836939 E=l(-800202-(-829450))f=S S=s%O Y[N[-220583-(-220587)]]=S n=-71872-(-72127)T=-222849-(-222850)b=s%n n=-413794-(-413796)O=b+n Y[N[211591-211586]]=O n=V[E]E=l(456388+-427068)b=n[E]n=b(u)m=T T=-445955-(-445955)E=-1001293-(-1001294)H=m<T b=l(-43571-(-72865))T=E-m g[s]=b b=536039+-536025 F=n end else M=Y[s]z=M r=M and-777544+9540832 or-204462+804424 end else if r<8236938-954003 then S=5707345-384249 s=l(-693137+722391)g=494440+16205120 u=s^g r=S-u u=r S=l(855406-826151)r=S/u S={r}r=V[l(-846157+875436)]else S=l(-896654-(-925915))u=l(-144966+174269)r=V[S]S=V[u]u=l(292929-263626)V[u]=r u=l(643460-614199)V[u]=S u=Y[N[897938-897937]]s=u()r=444739+2812297 end end end end end else if r<11358522-(-596859)then if r<9086097-(-681588)then if r<9218181-448209 then if r<8029611-(-42632)then if r<761414+7174069 then if r<163069+7645097 then u=nil r=6869193-435396 Y[N[-816478+816483]]=S else u=l(-443176-(-472451))r=V[u]g=-828689-(-828689)s=Y[N[936043-936035]]u=r(s,g)r=869932+15455566 end else r=S and 415582+12054227 or-630292+11366340 end else if r<8278830-(-313744)then Z=#R e=-450050+450050 a=Z==e r=a and 11566474-476065 or 203172-(-379084)else r=198089-(-401873)M=m==H z=M end end else if r<616673+8870073 then if r<-950735+10212645 then if r<9568093-731311 then s=Y[N[641829+-641826]]g=-840385-(-840386)u=s~=g r=u and-724896+967973 or 946982+559360 else S={s}r=V[l(-903297+932603)]end else E=T K=l(4799+24449)M=V[K]K=l(-170566-(-199859))z=M[K]M=z(u,E)z=Y[N[788640+-788634]]K=z()Z=M+K a=Z+b Z=714942-714686 K=332023-332022 R=a%Z Z=g[s]b=R r=10304601-614517 M=b+K z=f[M]a=Z..z E=nil g[s]=a end else if r<9820352-95553 then T=T+m R=not H E=T<=F E=R and E R=T>=F R=H and R E=R or E R=478040+8977679 r=E and R E=293854-(-633810)r=r or E else S=l(329558-300283)u=l(212837-183580)r=V[S]S=r(u)r=V[l(-452724-(-481988))]S={}end end end else if r<10598244-117187 then if r<9613208-(-694260)then if r<981096+9036575 then if r<-19516+9827926 then J=-922878+922880 U=366697-366597 d=k()i=l(540772-511496)I=-159374-(-159374)Y[d]=z S=V[i]i=l(702344-673067)r=S[i]i=832096+-832095 x=602765-602764 S=r(i,U)U=-1035668+1035668 i=k()Y[i]=S o=197064+-196809 r=Y[n]S=r(U,o)U=k()P=607262+-597262 Y[U]=S o=-259082+259083 B=l(319557+-290284)r=Y[n]D=Y[i]S=r(o,D)o=k()Y[o]=S S=Y[n]D=S(x,J)S=4391-4390 r=D==S D=k()J=l(-785322-(-814589))Y[D]=r S=l(-979820+1009085)t=V[B]r=l(534060+-504768)w=Y[n]C={w(I,P)}B=t(Q(C))r=a[r]t=l(222577+-193310)L=B..t x=J..L r=r(a,S,x)J=l(967582+-938320)x=k()Y[x]=r S=V[J]L=q(968087+814936,{n,d;T;g,s,Z;D;x;i,o;U,F})J={S(L)}r={Q(J)}J=r r=Y[D]r=r and-76679+2481248 or-428558+4794179 else B=-975409-(-975410)r=13208983-(-412851)t=J[B]L=t end else K=-736052-(-736053)e=986969+-986963 r=Y[n]M=r(K,e)e=l(-612293+641554)r=l(627286-598025)V[r]=M K=V[e]e=-1032609-(-1032611)r=K>e r=r and 2035422-269533 or 12456146-960686 end else if r<672950+9748439 then n=l(-512475-(-541751))b=S E=l(635848+-606566)S=V[n]H=l(-844801-(-874083))n=l(586955-557678)r=S[n]n=k()Y[n]=r S=V[E]E=l(-646217-(-675514))r=S[E]m=V[H]F=m T=r E=r r=m and 771142+14104597 or 15306252-(-635624)else t=r C=-359324+359325 w=J[C]C=false B=w==C L=B r=B and 6281758-200999 or-963602+5161741 end end else if r<-495425+11626479 then if r<11601103-772342 then if r<76544+10548740 then d=not e z=z+K S=z<=M S=d and S d=z>=M d=e and d S=d or S d=885518+8911799 r=S and d S=7953550-842217 r=r or S else r=V[l(-313548+342856)]g=nil s=nil u=nil S={}end else E=nil i=l(-341404+370664)a={}d=k()U={}Z=k()Y[Z]=a g=nil b=nil e=y(15127837-954257,{Z,F,T;O})O=G(O)n=nil a=k()Y[a]=e e={}n=l(1013803-984551)b=k()Y[d]=e r=V[l(-783072+812391)]e=V[i]B=nil x=Y[d]J=l(160376+-131092)O=1587553781-198841 D=l(-754268+783556)g={}o={[D]=x,[J]=B}i=e(U,o)R=nil e=c(17005958-622343,{d;Z,H;F;T;a})Z=G(Z)Y[f]=i Y[s]=e S={g}R=13423903166779-194769 H=G(H)F=G(F)Y[b]=O H=l(671016-641715)T=G(T)O=V[n]a=G(a)n=l(-963630+992901)m=nil d=G(d)F=Y[f]T=Y[s]m=T(H,R)n=O[n]E=F[m]n=n(O,E)O=k()Y[O]=n E=l(506462+-477148)n=j(-903186+12969499,{O;b;f;s})g[E]=n end else if r<11690960-332820 then r=-966374+6498019 Y[s]=S else e=l(-721242-(-750503))r=V[e]e=l(-924268+953571)V[e]=r r=-975730+5405924 end end end end else if r<14377362-(-871039)then if r<306917+13209136 then if r<12167090-(-560224)then if r<82708+12438368 then if r<-627124+13054560 then u=k()Y[u]=W[507298-507297]r=Y[N[175806+-175805]]s=Y[u]S=l(1017213+-987906)g=Y[N[-362876-(-362878)]]S=r[S]S=S(r,s,g)r=nil s=k()Y[s]=r S=Y[N[100796+-100795]]f=Y[N[591978+-591975]]n=l(-582729+612014)O=Y[N[-886984-(-886988)]]E=32840726990392-(-519556)b=O(n,E)g=f[b]r=S[g]g=j(-360584+6489210,{u,N[-763221+763223],N[442256+-442253],N[313880+-313876],s})u=G(u)S=l(-281566-(-310883))S=r[S]S=S(r,g)Y[s]=S r=V[l(828356-799103)]S={}s=G(s)else r=g and 13967000-538771 or 6283427-714601 end else g=l(-906700+935982)r=V[l(-232498+261761)]s=V[g]g=l(-529881+559197)u=s[g]g=Y[N[567455+-567454]]s={u(g)}S={Q(s)}end else if r<-906143+14283544 then O=G(O)T=G(T)m=nil n=G(n)g=G(g)Z=G(Z)s=G(s)E=nil m={}f=G(f)H=nil s=nil g=nil E=l(-352239+381521)R=nil n=l(-227448-(-256724))a=nil F=G(F)b=nil f=k()b=l(808142+-778866)H=k()r=950814+1525315 Y[f]=s s=k()Y[s]=g O=V[b]b=l(-698937+728220)g=O[b]a=-684560-(-684561)F=l(678836+-649588)O=k()Y[O]=g b=V[n]n=l(-525362+554639)g=b[n]R={}n=V[E]E=l(-237025-(-266341))b=n[E]E=V[F]F=l(-211398+240702)n=E[F]E=-6825-(-6825)T=k()F=k()Y[F]=E E=1002183-1002181 Y[T]=E E={}Y[H]=m Z=837770-837514 m=152856+-152856 e=Z Z=558992-558991 d=Z Z=620109-620109 i=d<Z Z=a-d else m=-457497+12408475505067 b=l(759913-730644)O=V[b]n=Y[N[-51675+51678]]T=l(-126410-(-155666))E=Y[N[-412071+412075]]a=20054036479030-743356 F=E(T,m)b=n[F]F=l(222839+-193559)f=O[b]T=5740456721532-307723 b=Y[N[859823-859820]]n=Y[N[-658953-(-658957)]]E=n(F,T)F=31507248008640-955505 O=b[E]S=f[O]O=Y[N[-501781-(-501784)]]E=l(929230-899931)b=Y[N[-193472-(-193476)]]n=b(E,F)f=O[n]F=l(243077-213762)r=S[f]f=Y[N[779357-779354]]E=12530771341618-(-75161)n=l(938953-909648)R=l(787280+-757994)O=Y[N[976907+-976903]]b=O(n,E)T=1020472+20676071658340 S=f[b]b=Y[N[-445042-(-445045)]]n=Y[N[-725851-(-725855)]]E=n(F,T)F=l(-8765+38041)O=b[E]E=V[F]T=Y[N[-395437-(-395440)]]m=Y[N[975184-975180]]H=m(R,a)F=T[H]n=E[F]F=816810-816710 a=l(-915301-(-944619))Z=689978+16777183041354 T=-175753-(-176753)E=n(F,T)F=Y[N[-454118+454119]]m=Y[N[979331-979328]]H=Y[N[315499-315495]]R=H(a,Z)T=m[R]n=F[T]b=E..n f=O..b n=l(35280+-6011)r[S]=f b=V[n]E=Y[N[-463740-(-463743)]]F=Y[N[988243+-988239]]H=34375424907522-1038971 m=l(43859+-14564)T=F(m,H)n=E[T]O=b[n]m=755546+21536199106514 T=l(-655360+684638)n=Y[N[-614988+614991]]E=Y[N[94459+-94455]]F=E(T,m)T=25481407293586-883257 b=n[F]F=l(-190159+219418)f=O[b]b=Y[N[555289+-555286]]n=Y[N[-251938+251942]]E=n(F,T)O=b[E]m=l(-699559+728857)H=18270751544129-127494 S=f[O]E=l(-592485-(-621743))O=Y[N[511990-511987]]F=497099+4066569990554 b=Y[N[79933+-79929]]n=b(E,F)f=O[n]r=S[f]f=Y[N[615165-615162]]E=679497+18870498673674 O=Y[N[191400-191396]]n=l(30592+-1341)b=O(n,E)S=f[b]n=l(770164-740895)f=false r[S]=f b=V[n]E=Y[N[-995544-(-995547)]]F=Y[N[-736794-(-736798)]]T=F(m,H)n=E[T]O=b[n]m=16159166590125-(-618679)n=Y[N[-604752+604755]]E=Y[N[146431+-146427]]T=l(731838+-702572)F=E(T,m)b=n[F]f=O[b]b=Y[N[-796531+796534]]n=Y[N[-957027-(-957031)]]m=-585257+6137506543954 T=33717324483339-953783 F=l(-1005896+1035207)E=n(F,T)T=l(-266466+295776)O=b[E]S=f[O]O=Y[N[903080-903077]]F=165925+29307675192618 E=l(918364-889090)b=Y[N[459025-459021]]n=b(E,F)f=O[n]r=S[f]b=l(342021+-312719)O=V[b]n=Y[N[957123-957120]]E=Y[N[692600-692596]]S=l(17981+11300)F=E(T,m)b=n[F]f=O[b]b=1036366-1036366 E=-227990+227990 F=-826553-(-826586)n=-137197-(-137447)O={f(b,n,E,F)}S=r[S]S=S(r,Q(O))r=5167132-(-401694)end end else if r<14021876-(-882856)then if r<13906279-(-472560)then if r<-429728+14429856 then Y[s]=L I=-554560-(-554561)C=Y[o]w=C+I B=J[w]t=m+B B=-920388+920644 r=t%B m=r r=-84738+5616383 w=Y[U]B=H+w w=177064+-176808 t=B%w H=t else u=Y[N[-430024+430025]]S=#u u=-984443-(-984443)r=S==u r=r and-784708+16197799 or 774872+11923123 end else R=l(-537629-(-566911))H=V[R]R=l(-822364-(-851614))m=H[R]r=222753+15719123 F=m end else if r<15572319-516082 then r=S and 16238816-1046288 or 959030+5474767 else S=l(-935830+965098)F=X(7365307-157153,{})r=V[S]f=l(224297+-195024)u=Y[N[885106-885102]]g=V[f]E=l(-46547+75809)n=V[E]E={n(F)}b={Q(E)}n=271765-271763 O=b[n]f=g(O)g=l(-557055-(-586320))s=u(f,g)u={s()}S=r(Q(u))s=Y[N[-539080-(-539085)]]r=s and 789711+3775438 or-796158+8161227 u=S S=s end end end else if r<-210913+15993797 then if r<182887+15342889 then if r<15964381-483080 then if r<-787214+16202908 then g=299922+-299921 s=Y[N[-514844-(-514846)]]u=s*g s=23353383444473-(-182912)S=u+s s=774722-774721 u=35184372006421-(-82411)r=S%u Y[N[860915+-860913]]=r u=Y[N[-376815+376818]]r=548624+957718 S=u~=s else a=Z r=541022+1935107 U=a R[a]=U a=nil end else r=2424912-452564 end else if r<15977707-274797 then r=Y[N[1020236+-1020226]]s=Y[N[495703+-495692]]u[r]=s r=Y[N[-1038304+1038316]]s={r(u)}S={Q(s)}r=V[l(253032-223741)]else n=not b g=g+O s=g<=f s=n and s n=g>=f n=b and n s=n or s n=6108379-224822 r=s and n s=14727197-(-840594)r=r or s end end else if r<90097+16283742 then if r<817652+15533250 then if r<-544924+16858588 then S=F r=T r=F and 953952+4027574 or 1035562-(-666727)else r={}g=Y[N[-37367+37376]]s=-280001+280002 f=g u=r g=740975+-740974 r=535614+15220338 O=g g=966310+-966310 b=O<g g=s-O end else r=13142841-(-27275)end else if r<15898364-(-727665)then u=W[-844331-(-844332)]s=W[497736+-497734]r=Y[N[-885215-(-885216)]]g=r r=g[s]r=r and 669654+1572757 or 7402209-422620 else r=true r=338845+1937611 end end end end end end end r=#h return Q(S)end,{},function(V,l)local Q=g(l)local W=function()return r(V,{},l,Q)end return W end,function(V)local l,r=-784543+784544,V[-609061-(-609062)]while r do u[r],l=u[r]-(493821+-493820),l+(-312047-(-312048))if u[r]==-711145+711145 then u[r],Y[r]=nil,nil end r=V[l]end end,function(V,l)local Q=g(l)local W=function(W,N,h)return r(V,{W,N,h},l,Q)end return W end,function()s=(1012549-1012548)+s u[s]=-513898-(-513899)return s end,927385-927385,function(V,l)local Q=g(l)local W=function(...)return r(V,{...},l,Q)end return W end return(O(167368-(-974359),{}))(Q(S))end)(getfenv and getfenv()or _ENV,unpack or table[l(413593+-384343)],newproxy,setmetatable,getmetatable,select,{...})end)(...)
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
local function C_17()
local script = G2L["17"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_17);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.LocalScript
local function C_1c()
local script = G2L["1c"];
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
task.spawn(C_1c);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Check.UIStroke.UIGradient.LocalScript
local function C_1f()
local script = G2L["1f"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_1f);
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
local function C_2a()
local script = G2L["2a"];
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
task.spawn(C_2a);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.UIStroke.UIGradient.LocalScript
local function C_2f()
local script = G2L["2f"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_2f);
-- StarterGui.ScreenGui.Main.Keyframe.Login.Buttons.Buy.ImageLabel.UIStroke.UIGradient.LocalScript
local function C_35()
local script = G2L["35"];
	local speed = 3
	
	while true do
		script.Parent.Rotation += speed
		wait(0.01)
	end
end;
task.spawn(C_35);
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
