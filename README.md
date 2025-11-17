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
    local script = G2L["38"];--[[ v1.0.0 https://wearedevs.net/obfuscator ]] return(function(...)local y={"\118\103\106\111\115\073\061\061";"\069\110\086\107\050\052\079\106\114\056\082\054\050\084\061\061";"\057\110\050\054\088\052\108\071\073\090\109\055\119\088\048\101\057\049\106\061","\079\088\075\070\120\119\121\079\088\082\087\067\097\052\117\111\057\084\061\061","\121\110\109\090\117\052\098\051\120\073\061\061","\073\113\107\082\072\113\115\061","\104\075\086\070\050\104\121\107\117\110\108\122\069\110\119\061","\119\052\098\112\111\071\108\087\117\106\070\113\121\089\109\074\088\047\089\061";"\099\082\071\052\047\118\061\061","\081\112\117\086\103\076\087\120";"\117\113\108\048\117\099\061\061","\069\088\108\106\111\099\061\061","\109\110\108\070\114\110\109\116\074\089\121\082\117\110\109\065\117\110\109\049\074\073\061\061";"\112\086\075\085\111\110\054\108","\097\118\061\061","\079\088\075\106\050\071\049\106\073\088\121\088\069\049\082\053\057\119\119\061","\050\071\079\075\072\118\061\061";"\080\106\053\065","\080\113\050\108\050\109\048\072\080\104\121\050\057\109\079\119\111\088\074\061";"\051\043\122\087\105\074\097\106\104\098\080\051\049\116\069\067\105\113\088\056","\049\065\067\116\113\118\061\061";"\050\104\098\116\069\071\074\061","\117\088\053\084\072\088\079\066";"\073\119\048\111\119\119\085\070\111\052\117\113\073\088\107\080\120\089\100\061","\050\113\108\070\050\073\061\061","\069\110\109\054","\050\113\075\107\117\110\079\083","\105\071\079\047\119\047\082\087\114\089\109\101\072\113\050\083","\117\110\086\054\117\088\075\122\050\104\074\061","\114\110\079\107\069\110\084\061","\057\052\121\106\114\089\117\082\117\099\061\061";"\117\119\053\097\050\073\061\061";"\073\106\048\098\097\109\087\047\097\110\098\055\117\082\114\113";"\050\109\108\082\121\088\117\104\120\089\108\065","\050\056\085\051\069\071\074\061","\068\070\043\106\099\106\090\068","\114\052\083\113\057\110\079\116\069\088\053\119\109\056\108\105\114\118\061\061";"\104\075\086\115\050\088\077\061","\069\047\074\061","\114\113\109\106\069\088\109\106\072\104\121\107\072\056\085\082";"\117\110\108\122\069\110\119\061","\077\048\072\076\122\114\121\087\052\047\049\081\122\072\079\122\080\109\105\116\117\098\074\067\097\051\076\099\076\047\069\047\072\049\048\048\089\088\072\089\101\102\120\057\050\088\076\075\086\111\073\090\103\055\054\051\053\085\116\073\101\103\081\100\079\076\076\081\088\073\121\071\122\082\047\090\085\083\065\083\106\078\065\111\048\082\120\080\077\090\077\067\081\110\084\066\120\118\061\061","\114\071\121\116\111\088\053\078","\079\088\082\072\105\047\117\043\121\106\053\108\080\113\121\056\080\084\061\061";"\110\099\090\071\101\104\102\047";"\104\075\086\048\069\056\121\082\120\099\061\061";"\072\113\107\107\114\118\061\061","\097\122\118\082\050\043\083\048\097\118\061\061","\114\056\108\054\050\110\086\070";"\088\047\050\043\073\104\087\048\105\065\049\106\057\106\086\109";"\105\056\085\088\069\049\109\078\057\106\098\108\079\090\117\103\072\113\073\061";"\104\075\086\078\072\084\061\061","\067\057\104\071\109\102\113\054","\114\113\079\116\111\104\087\106","\072\113\086\054\072\113\108\106";"\117\110\086\090\117\052\098\048\069\056\114\061";"\057\113\082\065\111\084\061\061","\114\056\109\070\069\071\050\082";"\069\047\089\061";"\072\078\082\106\050\073\061\061";"\050\078\048\056\105\109\072\090\119\089\121\077\119\110\050\085\069\089\072\061";""}for J,S in ipairs({{92076-92075;-592856+592918};{668653+-668652,-57425+57438},{-1014377+1014391,-721561-(-721623)}})do while S[-534953-(-534954)]<S[1013147+-1013145]do y[S[285614+-285613]],y[S[301393-301391]],S[585475-585474],S[-116775+116777]=y[S[874316+-874314]],y[S[-652072-(-652073)]],S[-677238-(-677239)]+(-1007823-(-1007824)),S[175738-175736]-(-270476+270477)end end local function J(J)return y[J-(-54384+84769)]end do local J=string.len local S=y local A=string.sub local X=table.concat local k={P=495711-495699,f=-592222-(-592253),Z=397279-397228,G=-423530+423585,O=-180809+180822,e=208279-208221,o=-228344+228370,c=-617665+617665,X=310296+-310274;u=478575-478546,C=742791-742780,U=-799559-(-799608),p=443248-443233,E=523819-523792,m=1008961-1008940,["\050"]=332226-332201;L=-8180+8243;r=727454-727426,B=-690636+690679;s=-989021-(-989065);["\047"]=-907697+907700;j=635465+-635413,a=-306199+306213,["\048"]=-892452+892493;["\056"]=616573+-616535,v=-347831-(-347863);k=741821+-741788,V=756699+-756638,I=96139-96123,["\054"]=462045+-461999,q=-337228-(-337282),z=16419+-16385,n=-944089-(-944095);y=-974969+974986;H=-860692-(-860716),F=79065-79020;["\052"]=494488+-494481;["\053"]=-938800-(-938857);["\049"]=-818601-(-818637),D=-646841-(-646900);N=-348674-(-348713);g=772834-772792,i=-294135+294154,l=-148209-(-148214),J=705389+-705381;R=737273-737236,Q=653143+-653081,W=499166+-499165;A=-932383+932418,t=-1041078-(-1041128),d=685236-685176,["\057"]=665698+-665680,["\055"]=935372-935362;w=-824138+824158,b=-437112+437121,K=-568640+568693;S=765047+-765007,x=-325380-(-325410),["\043"]=-39917+39919;["\051"]=115385-115338,M=-30704-(-30760),T=277382+-277334,Y=80590+-80586;h=656401+-656378}local s=table.insert local M=math.floor local l=string.char local P=type for y=-883897-(-883898),#S,-876097+876098 do local p=S[y]if P(p)=="\115\116\114\105\110\103"then local P=J(p)local W={}local w=-439124+439125 local Y=-949706-(-949706)local K=430931-430931 while w<=P do local y=A(p,w,w)local J=k[y]if J then Y=Y+J*(808719-808655)^((325027-325024)-K)K=K+(18912-18911)if K==884379-884375 then K=739488+-739488 local y=M(Y/(176098-110562))local J=M((Y%(389917+-324381))/(-426652+426908))local S=Y%(-660835-(-661091))s(W,l(y,J,S))Y=-817703+817703 end elseif y=="\061"then s(W,l(M(Y/(-248838-(-314374)))))if w>=P or A(p,w+(-980294-(-980295)),w+(476686-476685))~="\061"then s(W,l(M((Y%(-229943-(-295479)))/(384300-384044))))end break end w=w+(759570+-759569)end S[y]=X(W)end end end return(function(y,A,X,k,s,M,l,V,P,w,b,H,S,Y,C,p,T,K,W,q,a)q,H,S,a,p,V,w,W,T,K,C,b,Y,P=function(y,J)local A=Y(J)local X=function(X,k,s,M)return S(y,{X;k,s;M},J,A)end return X end,function(y,J)local A=Y(J)local X=function(X,k,s,M,l,P)return S(y,{X;k,s;M;l;P},J,A)end return X end,function(S,X,k,s)local d,Z,G,K,F,U,j,Q,g,l,v,p,m,t,E,I,w,Y,D,O,L,i,n,z,r,b,o,R,x,u,e,B,c,f while S do if S<7773451-(-664748)then if S<472906+3904025 then if S<-543023+3214651 then if S<633269-(-796316)then if S<-365421+1180730 then if S<32348+688993 then if S<150359+250018 then p=P[k[-1007788-(-1007789)]]l=#p p=-772238-(-772238)S=l==p S=S and 14120408-311834 or 12344260-(-841311)else w=T(w)x=nil z=T(z)D=nil j=T(j)u=T(u)K=T(K)K=W()b=T(b)m=nil n=nil g=T(g)r=nil Q=nil w=nil P[K]=w u=J(-533555-(-563965))w=W()D={}Y=T(Y)m=794878+-794877 Y=nil n=J(320275-289865)P[w]=Y b=y[n]n=J(-132006-(-162439))S=11512698-(-907641)Y=b[n]b=W()P[b]=Y g=J(142595-112154)x={}r=J(637113+-606674)n=y[u]u=J(-922355+952802)Y=n[u]u=y[r]r=J(-137419-(-167813))n=u[r]r=y[g]g=J(762144-731699)u=r[g]g=W()j=201429+-201173 r=-896064-(-896064)P[g]=r O=j z=W()r=763036-763034 j=270398+-270397 Q=W()P[z]=r P[Q]=x x=706635-706635 L=j j=-233977+233977 r={}F=L<j j=m-L end else S={}P[k[144402+-144400]]=S l=P[k[580026-580023]]u=669404+-669149 S=657791+5594054 K=l b=167249+35184371921583 l=w%b P[k[606660+-606656]]=l n=w%u u=-33593-(-33595)r=J(287211-256770)b=n+u P[k[-371347+371352]]=b u=y[r]r=J(-595574-(-625998))z=-136743+136744 x=z n=u[r]u=n(p)n=J(200113+-169715)Y[w]=n n=-683300+683461 z=784668+-784668 g=u Q=x<z r=1042365-1042364 z=r-x end else if S<1479139-237877 then j=W()m={}F=J(-133962+164400)L=W()x=nil I=J(117506-87062)O=C(-388423-(-720707),{j;g,z;b})Y=nil P[j]=m m=W()G=J(869968-839563)Y={}r=nil P[m]=O O={}P[L]=O O=y[F]d=P[L]S=y[J(-854468-(-884855))]E=nil D=nil e={[I]=d,[G]=E}n=nil u=nil f={}F=O(f,e)n=J(934435+-904031)P[w]=F b=T(b)O=a(3110287-950465,{L,j,Q;g;z;m})P[K]=O Q=T(Q)L=T(L)m=T(m)b=H(14104880-501582,{w,K})Y[n]=b z=T(z)g=T(g)l={Y}j=T(j)else p=nil S=948315+2610916 P[k[-780714-(-780719)]]=l end end else if S<3135129-973900 then if S<1718696-(-413355)then if S<1486999-(-599479)then b=440022-440020 w=P[k[-702579+702580]]K=-502123-(-502124)Y=w(K,b)w=522245+-522244 p=Y==w S=p and-1021007+4098709 or 15346243-260156 l=p else K=nil u=nil n=nil S=12509448-229317 end else w=X[144744+-144742]S=P[k[-171802+171803]]p=X[409636-409635]Y=S S=Y[w]S=S and-1013450+8156689 or 795228+-73870 end else if S<-489503+2726886 then t=S Z=-458187+458188 v=G[Z]Z=false E=v==Z o=E S=E and 14069454-891347 or-443159+4571895 else w=W()b=W()r=q(-809338+17202747,{b})p=X K=W()S=true u=J(-879060+909488)Y=J(929731-899290)P[w]=S l=y[Y]Y=J(-812011-(-842436))S=l[Y]Y=W()P[Y]=S S=V(15320456-(-177835),{})P[K]=S S=false P[b]=S n=y[u]u=n(r)S=u and-362516+7747166 or 9225822-(-465264)l=u end end end else if S<4638344-813587 then if S<-531177+3946846 then if S<3766673-533539 then if S<821687+2187022 then l=g S=z S=g and-18767+4953550 or 8134267-(-548959)else S=l and-208055+7451056 or 170+3559061 end else O=J(-951309-(-981746))S=y[O]O=J(-408269-(-438664))y[O]=S S=4582378-227986 end else if S<4422006-787779 then S=P[k[-734097+734104]]S=S and 762705+14949655 or 14075376-466666 else S=1030614+4193562 end end else if S<839188+3360418 then if S<-362274+4424857 then P[w]=o R=-539124-(-539125)Z=P[e]v=Z+R E=G[v]t=x+E E=-709844+710100 S=t%E v=P[f]x=S E=Q+v v=721473+-721217 t=E%v S=-1043938+10929390 Q=t else l=o S=t S=5537998-(-727061)end else if S<-768723+5126397 then S=11240824-1038677 else r=252060+12625085824603 K=P[k[199893-199892]]u=J(28931+1487)b=P[k[-602527-(-602529)]]n=b(u,r)l=K[n]S=J(-107406-(-137799))S=w[S]S=S(w,l)S=5894759-(-640126)end end end end else if S<1011857+5253162 then if S<5143270-(-73386)then if S<4459964-(-481806)then if S<759044+3979996 then if S<4059592-(-437070)then S=P[k[-546987-(-546988)]]w=Y r=-187505+187505 g=768753-768498 u=S(r,g)p[w]=u S=16060380-(-712872)w=nil else S=P[k[200143-200133]]w=P[k[817700-817689]]p[S]=w S=P[k[35413-35401]]w={S(p)}S=y[J(-646663-(-677065))]l={A(w)}end else g=W()x=759070-759005 z=246192-246189 P[g]=l S=P[u]l=S(z,x)D=J(768857-738429)z=W()P[z]=l S=780474+-780474 l=y[D]x=S S=-252194-(-252194)Q=S m=a(504229+13171157,{})D={l(m)}l=358690+-358688 S={A(D)}D=S S=D[l]m=S l=J(-122135+152562)i=J(769921-739529)S=y[l]j=P[Y]U=y[i]i=U(m)U=J(814664+-784218)B=j(i,U)j={B()}l=S(A(j))j=W()P[j]=l l=-450304+450305 S=6414156-614700 B=P[z]U=B B=-433843+433844 i=B B=822874+-822874 O=i<B B=l-i end else if S<5636820-522296 then o=P[w]S=o and 996523+1165968 or 7210116-945057 l=o else S=a(-451210+4090919,{K})U={S()}l={A(U)}S=y[J(-867726+898148)]end end else if S<495738+5573707 then if S<5170769-(-567178)then if S<5752479-363301 then S=true S=S and-596568+6683069 or 12990492-568352 else S=true S=S and 16697213-634547 or 6122487-989544 end else L=not O B=B+i l=B<=U l=L and l L=B>=U L=O and L l=L or l L=679797+7800684 S=l and L l=681967+10189621 S=S or l end else if S<7011325-808228 then l=J(-52609-(-83046))S=y[l]p=J(8893+21502)l=y[p]p=J(-978213+1008608)y[p]=S p=J(571687+-541250)y[p]=l p=P[k[-286577+286578]]w=p()S=4999048-(-225128)else D=not Q z=z+x r=z<=g r=D and r D=z>=g D=Q and D r=D or r D=12839609-(-302088)S=r and D r=-239482+2362911 S=S or r end end end else if S<-254664+8082250 then if S<-674919+7915884 then if S<56547+6512138 then if S<-511765+6896639 then P[w]=l S=434457+9450995 else S=y[J(178953+-148518)]l={}Y=nil w=nil p=nil end else S=13014280-734149 end else if S<7681735-411740 then l=J(-828937-(-859364))g=a(68924+10713183,{})S=y[l]K=J(-534683+565075)p=P[k[-136949-(-136953)]]Y=y[K]r=J(-842075-(-872503))u=y[r]r={u(g)}u=631079+-631077 n={A(r)}b=n[u]K=Y(b)Y=J(671045-640599)w=p(K,Y)p={w()}l=S(A(p))p=l w=P[k[783663-783658]]l=w S=w and 518905+7745281 or 580124+679172 else n=P[b]l=n S=10379215-688129 end end else if S<7489553-(-748454)then if S<8226751-4683 then O=-819905+819905 j=#D m=j==O S=m and 1501286-461657 or 13062996-117931 else w=P[k[50170+-50167]]x=-929876+929889 Y=-54377+54409 g=272894+-272892 p=w%Y K=P[k[-359027-(-359031)]]u=P[k[-812885-(-812887)]]m=P[k[-567+570]]D=m-p m=270878+-270846 Q=D/m z=x-Q r=g^z n=u/r b=K(n)g=263660+-263404 K=4295640193-672897 Y=b%K b=630585+-630583 K=b^p r=-872011-(-872012)w=Y/K K=P[k[694932-694928]]u=w%r r=696883+4294270413 n=u*r b=K(n)S=13315967-130396 K=P[k[-130508+130512]]u=302849+-237313 n=K(w)Y=b+n b=116467+-50931 K=Y%b n=Y-K b=n/u u=-130136-(-130392)Y=nil n=K%u w=nil r=K-n x=310589-310333 u=r/g g=333950-333694 p=nil r=b%g z=b-r b=nil K=nil g=z/x z={n;u,r,g}u=nil r=nil g=nil n=nil P[k[70039-70038]]=z end else if S<8174102-(-132425)then Y=P[k[207257+-207251]]S=950075+309221 w=Y==p l=w else D=J(-630203+660642)Q=y[D]D=J(-824053-(-854474))S=2716470-12675 x=Q[D]g=x end end end end end else if S<614401+12106252 then if S<11728200-423041 then if S<9078609-(-997760)then if S<319+9709253 then if S<9639579-552323 then if S<9161470-611047 then c=-503235+513235 f=643117+-643017 L=W()E=J(760720+-730328)P[L]=B e=-978000-(-978255)G=114215+-114213 F=J(-70254-(-100664))l=y[F]F=J(-595648-(-626095))S=l[F]F=-467995+467996 l=S(F,f)F=W()d=-325066+325067 P[F]=l f=-655807-(-655807)S=P[u]l=S(f,e)f=W()P[f]=l e=888355-888354 S=P[u]I=P[F]l=S(e,I)e=W()P[e]=l l=P[u]I=l(d,G)l=821405-821404 G=J(-275318-(-305731))R=-779712-(-779712)S=I==l I=W()l=J(-25595+56041)P[I]=S t=y[E]v=P[u]Z={v(R,c)}E=t(A(Z))t=J(-21076+51489)o=E..t d=G..o S=J(384470-354055)S=m[S]S=S(m,l,d)d=W()G=J(745870+-715442)o=q(2908139-841687,{u;L,z;Y;w;j;I,d,F,e;f;g})P[d]=S l=y[G]G={l(o)}S={A(G)}G=S S=P[I]S=S and 5097396-149598 or 13055772-230224 else z=J(-555973-(-586394))g=y[z]S=4192897-(-741886)l=g end else Q=J(596853-566414)n=l r=J(60695+-30256)u=J(1024634+-994224)l=y[u]u=J(250757+-220310)S=l[u]u=W()P[u]=S l=y[r]r=J(761917-731526)S=l[r]x=y[Q]z=S r=S S=x and 1022120+7357770 or 689963+2013832 g=x end else if S<313921+9430378 then w=P[k[219354+-219351]]S=-761183+13053672 Y=8900+-8793 p=w*Y w=708898-708641 l=p%w P[k[349813-349810]]=l else e=T(e)I=T(I)L=T(L)S=6310324-510868 F=T(F)d=T(d)G=nil f=T(f)end end else if S<11242791-690108 then if S<9563087-(-765444)then if S<9600099-(-609374)then S=true S=S and 12750102-934592 or 15296258-35126 else i=J(-104595-(-134987))S=y[i]L=J(801786+-771391)O=y[L]i=S(O)S=J(-208769-(-239206))y[S]=i S=532619+3821773 end else z=J(174159-143719)b=J(-406969-(-437392))l=J(360463+-330063)S=y[l]K=y[b]u=P[k[569646-569645]]r=P[k[-657917+657919]]x=27694990261133-(-276179)g=r(z,x)n=u[g]u=J(1013664-983235)u=K[u]b={u(K,n)}D=22190922267863-693370 l=S(A(b))K=135884+-135879 S=l()l=J(-738978-(-769387))Q=J(219603-189214)S=y[l]l=S(K)r=J(990260+-959870)u=y[r]g=P[k[384226-384225]]z=P[k[-499540+499542]]x=z(Q,D)r=g[x]x=J(-833445+863888)Q=290384531027-724428 n=u[r]r=P[k[101729+-101728]]g=P[k[706038-706036]]z=g(x,Q)u=r[z]b=n[u]u=P[k[-750074+750075]]r=P[k[-856493-(-856495)]]x=31746103217382-(-896216)z=J(-978476-(-1008910))g=r(z,x)z=23219969873656-(-840516)n=u[g]K=b[n]g=J(-208772-(-239184))n=P[k[695934-695933]]u=P[k[302500-302498]]r=u(g,z)b=n[r]g=887906+23664775192233 l=K[b]b=P[k[-548720+548721]]n=P[k[-803233-(-803235)]]r=J(-741476+771884)u=n(r,g)K=b[u]S=l[K]l=J(360078+-329675)l=S[l]l=l(S)S=6171960-(-362925)end else if S<-933100+11766485 then Y=897683+4951555 l=650273+15002173 w=J(930392-899991)p=w^Y S=l-p l=J(682709-652293)p=S S=l/p l={S}S=y[J(387636-357219)]else U=P[w]B=U S=U and 12056285-(-336638)or 14208769-267351 end end end else if S<-481235+12862552 then if S<-723762+12556203 then if S<-246983+12037511 then if S<960453+10711949 then S=true S=-825036+5957979 else m=j f=m D[m]=f m=nil S=-814105+13234444 end else O=-752781+752787 S=P[u]i=719081+-719080 U=S(i,O)S=J(967570-937133)O=J(-781183-(-811620))y[S]=U i=y[O]O=-634810+634812 S=i>O S=S and 10315276-14259 or 633925+2624908 end else if S<11675223-(-611993)then l={w}S=y[J(-237175-(-267601))]else w=P[k[544621-544618]]Y=-258756+258757 p=w~=Y S=p and-222942+8446806 or 91357+9629539 end end else if S<488285+11933121 then if S<557728+11836938 then U=x==Q B=U S=1028556+12912862 else j=j+L f=not F m=j<=O m=f and m f=j>=O f=F and f m=f or m f=-27861+11785268 S=m and f m=15277320-222246 S=S or m end else if S<12200484-(-344822)then l={}S=y[J(-437996-(-468402))]else E=-432370+432371 t=G[E]S=362317+3526739 o=t end end end end else if S<14097232-157666 then if S<13406184-(-65739)then if S<424230+12749278 then if S<195867+12795988 then if S<13827667-976391 then t=P[w]o=t S=t and-424699+13106820 or 991517+2897539 else j=775060+-775059 O=#D m=Y(j,O)j=n(D,m)f=-387822+387823 O=P[Q]F=j-f L=u(F)O[j]=L j=nil S=7455258-(-765495)m=nil end else i=J(224705+-194264)U=y[i]r=z i=J(445765-415369)B=U[i]U=B(p,r)B=P[k[-126456+126462]]r=nil i=B()j=U+i m=j+n j=-696694+696950 D=m%j i=-184367-(-184368)n=D j=Y[w]U=n+i B=K[U]S=5415727-(-836118)m=j..B Y[w]=m end else if S<877268+12307208 then Z=-446062-(-446064)v=G[Z]S=3885842-(-242894)Z=P[d]E=v==Z o=E else Y=J(343345-312906)w=y[Y]Y=J(-541325-(-571719))p=w[Y]Y=P[k[-331233-(-331234)]]S=y[J(-802392+832778)]w={p(Y)}l={A(w)}end end else if S<74672+13639807 then if S<13473141-(-179529)then if S<-547125+14150661 then Y=P[k[841862-841861]]u=-930239+10185585558598 w=X[-714675-(-714677)]p=X[-6070+6071]K=P[k[529834-529832]]n=J(-319126-(-349545))b=K(n,u)l=Y[b]g=J(-423094-(-453501))S=w[l]z=18323324457914-602726 b=J(-746271+776712)K=y[b]n=P[k[-800231+800232]]u=P[k[123733-123731]]Y=S x=365829+2780270751753 r=u(g,z)b=n[r]l=K[b]u=P[k[936941+-936940]]z=J(-917841-(-948240))r=P[k[21669+-21667]]g=r(z,x)n=u[g]b=p[n]K=l(b,Y)l=nil S=K~=l S=S and 10025806-(-446687)or 5306109-948307 else S={}Y=P[k[-408204+408213]]K=Y Y=873280+-873279 w=-723002+723003 b=Y Y=-886027+886027 n=b<Y p=S S=17391278-618026 Y=w-b end else w=J(181007+-150575)l=402029+3726361 Y=13060784-161572 p=w^Y S=l-p p=S l=J(-862328-(-892758))S=l/p l={S}S=y[J(744571+-714140)]end else if S<12889850-(-1001756)then Y=-141622+141863 w=P[k[-1040483+1040485]]p=w*Y w=1841714989976-460863 l=p+w p=-263251+35184372352083 S=l%p P[k[465012+-465010]]=S p=P[k[289446+-289443]]S=-796369+10517265 w=36829-36828 l=p~=w else S=913912-193362 end end end else if S<-401543+15917379 then if S<14686469-(-471346)then if S<15888502-805115 then if S<13237042-(-739764)then P[w]=B S=P[w]S=S and-657071+14594524 or 10654781-(-673285)else S=-460100+13405165 O=-906180+906180 j=#D m=j==O end else w=P[k[714307+-714305]]S=2309990-(-767712)Y=P[k[-962721-(-962724)]]p=w==Y l=p end else if S<-62851+15326974 then S=y[J(932750+-902353)]l={}else p=J(310581-280170)l=J(-363229+393649)S=y[l]l=S(p)S=y[J(-3129+33571)]l={}end end else if S<15524277-(-714686)then if S<16118839-254917 then Y=-681564-(-681564)p=J(1051104-1020684)S=y[p]w=P[k[83763+-83755]]p=S(w,Y)S=13752044-143334 else S=10669386-467239 end else if S<15986133-(-543100)then S=true P[k[-137759+137760]]=S l={}S=y[J(899445+-869031)]else Y=Y+b u=not n w=Y<=K w=u and w u=Y>=K u=n and u w=u or w u=-1036482+5448875 S=w and u w=5027832-293233 S=S or w end end end end end end end S=#s return A(l)end,function(y,J)local A=Y(J)local X=function(X,k)return S(y,{X;k},J,A)end return X end,{},function(y,J)local A=Y(J)local X=function(X)return S(y,{X},J,A)end return X end,-542330-(-542330),function()w=w+(-710685-(-710686))p[w]=951650-951649 return w end,function(y)p[y]=p[y]-(272839+-272838)if p[y]==86862-86862 then p[y],P[y]=nil,nil end end,function(y)local J,S=-667233+667234,y[310217+-310216]while S do p[S],J=p[S]-(86421+-86420),(572364-572363)+J if 850774-850774==p[S]then p[S],P[S]=nil,nil end S=y[J]end end,function(y,J)local A=Y(J)local X=function()return S(y,{},J,A)end return X end,function(y,J)local A=Y(J)local X=function(...)return S(y,{...},J,A)end return X end,function(y)for J=-1001476-(-1001477),#y,614184-614183 do p[y[J]]=(934959-934958)+p[y[J]]end if X then local S=X(true)local A=s(S)A[J(-641540-(-671984))],A[J(-402438+432826)],A[J(-251542-(-281978))]=y,K,function()return-892943-688469 end return S else return k({},{[J(776786+-746398)]=K,[J(808530+-778086)]=y,[J(-616662-(-647098))]=function()return-685697-895715 end})end end,{}return(b(677442+1651082,{}))(A(l))end)(getfenv and getfenv()or _ENV,unpack or table[J(-530460+560881)],newproxy,setmetatable,getmetatable,select,{...})end)(...)
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
