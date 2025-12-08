--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 18 | Scripts: 12 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.ScreenGui.loadmap
G2L["2"] = Instance.new("LocalScript", G2L["1"]);
G2L["2"]["Name"] = [[loadmap]];


-- StarterGui.ScreenGui.killall
G2L["3"] = Instance.new("LocalScript", G2L["1"]);
G2L["3"]["Name"] = [[killall]];


-- StarterGui.ScreenGui.kickall
G2L["4"] = Instance.new("LocalScript", G2L["1"]);
G2L["4"]["Name"] = [[kickall]];


-- StarterGui.ScreenGui.reall
G2L["5"] = Instance.new("LocalScript", G2L["1"]);
G2L["5"]["Name"] = [[reall]];


-- StarterGui.ScreenGui.r6all
G2L["6"] = Instance.new("LocalScript", G2L["1"]);
G2L["6"]["Name"] = [[r6all]];


-- StarterGui.ScreenGui.hint
G2L["7"] = Instance.new("LocalScript", G2L["1"]);
G2L["7"]["Name"] = [[hint]];


-- StarterGui.ScreenGui.msg
G2L["8"] = Instance.new("LocalScript", G2L["1"]);
G2L["8"]["Name"] = [[msg]];


-- StarterGui.ScreenGui.Blustall
G2L["9"] = Instance.new("LocalScript", G2L["1"]);
G2L["9"]["Name"] = [[Blustall]];


-- StarterGui.ScreenGui.Load
G2L["a"] = Instance.new("Frame", G2L["1"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["a"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["a"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Name"] = [[Load]];
G2L["a"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Load.LocalScript
G2L["b"] = Instance.new("LocalScript", G2L["a"]);



-- StarterGui.ScreenGui.Load.bg
G2L["c"] = Instance.new("ImageLabel", G2L["a"]);
G2L["c"]["ZIndex"] = 10000000;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["c"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["c"]["Image"] = [[rbxassetid://992001116]];
G2L["c"]["Size"] = UDim2.new(1.41, 0, 1, 0);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["BackgroundTransparency"] = 0.4;
G2L["c"]["Name"] = [[bg]];
G2L["c"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.bg.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.ScreenGui.Load.Logo
G2L["e"] = Instance.new("ImageLabel", G2L["a"]);
G2L["e"]["ZIndex"] = 10000000;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["e"]["Image"] = [[rbxassetid://73958241564252]];
G2L["e"]["Size"] = UDim2.new(0, 109, 0, 133);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["BackgroundTransparency"] = 0.4;
G2L["e"]["Name"] = [[Logo]];
G2L["e"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["f"] = Instance.new("LocalScript", G2L["e"]);



-- StarterGui.ScreenGui.Load.Logo.LocalScript
G2L["10"] = Instance.new("LocalScript", G2L["e"]);



-- StarterGui.ScreenGui.Load.Logo.UIAspectRatioConstraint
G2L["11"] = Instance.new("UIAspectRatioConstraint", G2L["e"]);



-- StarterGui.ScreenGui.Load.Logo.UICorner
G2L["12"] = Instance.new("UICorner", G2L["e"]);
G2L["12"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.ScreenGui.loadmap
local function C_2()
local script = G2L["2"];
	--[[
	  Script made by g4mg_99
	  
	  Moon Admin
	]]
	
	
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	
	local name = "_MoonUnc"..tostring(os.time())
	
	local function Notify(title, msg, duration)
		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = title,
			Text = msg,
			Duration = duration
		})
	end
	
	
	local servicesToCheck = {
		"ReplicatedStorage",
		"Workspace",
		"Lighting",
		"ServerScriptService",
		"ServerStorage",
		"StarterGui",
		"StarterPack",
		"StarterPlayer",
		"ReplicatedFirst",
		"SoundService",
		"Chat",
		"LocalizationService",
		"TestService"
	}
	
	
	local function FindAllRemotes(container, foundRemotes)
		foundRemotes = foundRemotes or {}
		
		local success, children = pcall(function()
			return container:GetChildren()
		end)
		
		if not success then
			return foundRemotes
		end
		
		for i = 1, #children do
			local child = children[i]
			
			if child:IsA("RemoteEvent") or child:IsA("RemoteFunction") then
				table.insert(foundRemotes, child)
			end
			
			FindAllRemotes(child, foundRemotes)
		end
		
		return foundRemotes
	end
	
	
	local function GetAllRemotes()
		local allRemotes = {}
		
		for i = 1, #servicesToCheck do
			local serviceName = servicesToCheck[i]
			local success, service = pcall(function()
				return game:GetService(serviceName)
			end)
			
			if success and service then
				FindAllRemotes(service, allRemotes)
			end
		end
		
		return allRemotes
	end
	
	
	local function TestRemote(remote)
		if not remote then
			return
		end
		
		local holyshit = [[
	local M = {}
	local originalMapObjects = {}
	
	for i = 1, #workspace:GetChildren() do
		local child = workspace:GetChildren()[i]
		if child:IsA("Model") or child:IsA("Part") or child:IsA("MeshPart") then
			local clone = child:Clone()
			table.insert(originalMapObjects, clone)
		end
	end
	
	function M.ReloadMap()
		local children = workspace:GetChildren()
		
		for i = 1, #children do
			local child = children[i]
			if child:IsA("Model") or child:IsA("Part") or child:IsA("MeshPart") then
				child.Parent = nil
			end
		end
	
		task.wait(3)
		
		for i = 1, #originalMapObjects do
			local clone = originalMapObjects[i]:Clone()
			clone.Parent = workspace
		end
		
		local Players = game:GetService("Players")
		for i = 1, #Players:GetPlayers() do
			local player = Players:GetPlayers()[i]
			player:LoadCharacter()
		end
	end
	
	M.ReloadMap()
	]]
		
		if remote:IsA("RemoteFunction") then
			task.spawn(function()
				local success, result = pcall(function()
					return remote:InvokeServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully loaded the map", 5)
				else
					return
				end
			end)
		elseif remote:IsA("RemoteEvent") then
			task.spawn(function()
				local success, err = pcall(function()
					remote:FireServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully loaded the map", 5)
				else
					return
				end
			end)
		end
	end
	
	
	local function TestAllRemotes()
		local remotes = GetAllRemotes()
		
		if #remotes == 0 then
			Notify("MoonAdmin", "No Backdoor Found", 5)
			return
		end
	
		
		for i = 1, #remotes do
			local remote = remotes[i]
			TestRemote(remote)
			task.wait(0.1) 
		end
	end
	
	local player = Players.LocalPlayer
	
	player.Chatted:Connect(function(msg)
		if msg == "?loadmap" then
			TestAllRemotes()
		end
	end)
end;
task.spawn(C_2);
-- StarterGui.ScreenGui.killall
local function C_3()
local script = G2L["3"];
	--[[
	  Script made by g4mg_99
	  
	  Moon Admin
	]]
	
	
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	
	local name = "_MoonUnc"..tostring(os.time())
	
	local function Notify(title, msg, duration)
		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = title,
			Text = msg,
			Duration = duration
		})
	end
	
	
	local servicesToCheck = {
		"ReplicatedStorage",
		"Workspace",
		"Lighting",
		"ServerScriptService",
		"ServerStorage",
		"StarterGui",
		"StarterPack",
		"StarterPlayer",
		"ReplicatedFirst",
		"SoundService",
		"Chat",
		"LocalizationService",
		"TestService"
	}
	
	
	local function FindAllRemotes(container, foundRemotes)
		foundRemotes = foundRemotes or {}
		
		local success, children = pcall(function()
			return container:GetChildren()
		end)
		
		if not success then
			return foundRemotes
		end
		
		for i = 1, #children do
			local child = children[i]
			
			if child:IsA("RemoteEvent") or child:IsA("RemoteFunction") then
				table.insert(foundRemotes, child)
			end
			
			FindAllRemotes(child, foundRemotes)
		end
		
		return foundRemotes
	end
	
	
	local function GetAllRemotes()
		local allRemotes = {}
		
		for i = 1, #servicesToCheck do
			local serviceName = servicesToCheck[i]
			local success, service = pcall(function()
				return game:GetService(serviceName)
			end)
			
			if success and service then
				FindAllRemotes(service, allRemotes)
			end
		end
		
		return allRemotes
	end
	
	
	local function TestRemote(remote)
		if not remote then
			return
		end
		local holyshit = [[
		for _, lol in pairs(game.Players:GetPlayers()) do
			local health = lol.Character:FindFirstChildOfClass("Humanoid")
			
			if health then
				health.Health = 0
			end
		end
		]]
		
		if remote:IsA("RemoteFunction") then
			task.spawn(function()
				local success, result = pcall(function()
					return remote:InvokeServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully loaded the map", 5)
				else
					return
				end
			end)
		elseif remote:IsA("RemoteEvent") then
			task.spawn(function()
				local success, err = pcall(function()
					remote:FireServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully Killed all", 5)
				else
					return
				end
			end)
		end
	end
	
	
	local function TestAllRemotes()
		local remotes = GetAllRemotes()
		
		if #remotes == 0 then
			Notify("MoonAdmin", "No Backdoor Found", 5)
			return
		end
	
		
		for i = 1, #remotes do
			local remote = remotes[i]
			TestRemote(remote)
			task.wait(0.1) 
		end
	end
	
	local player = Players.LocalPlayer
	
	player.Chatted:Connect(function(msg)
		if msg == "?kill all" then
			TestAllRemotes()
		end
	end)
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.kickall
local function C_4()
local script = G2L["4"];
	--[[
	  Script made by g4mg_99
	  
	  Moon Admin
	]]
	
	
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	
	local name = "_MoonUnc"..tostring(os.time())
	
	local function Notify(title, msg, duration)
		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = title,
			Text = msg,
			Duration = duration
		})
	end
	
	
	local servicesToCheck = {
		"ReplicatedStorage",
		"Workspace",
		"Lighting",
		"ServerScriptService",
		"ServerStorage",
		"StarterGui",
		"StarterPack",
		"StarterPlayer",
		"ReplicatedFirst",
		"SoundService",
		"Chat",
		"LocalizationService",
		"TestService"
	}
	
	
	local function FindAllRemotes(container, foundRemotes)
		foundRemotes = foundRemotes or {}
		
		local success, children = pcall(function()
			return container:GetChildren()
		end)
		
		if not success then
			return foundRemotes
		end
		
		for i = 1, #children do
			local child = children[i]
			
			if child:IsA("RemoteEvent") or child:IsA("RemoteFunction") then
				table.insert(foundRemotes, child)
			end
			
			FindAllRemotes(child, foundRemotes)
		end
		
		return foundRemotes
	end
	
	
	local function GetAllRemotes()
		local allRemotes = {}
		
		for i = 1, #servicesToCheck do
			local serviceName = servicesToCheck[i]
			local success, service = pcall(function()
				return game:GetService(serviceName)
			end)
			
			if success and service then
				FindAllRemotes(service, allRemotes)
			end
		end
		
		return allRemotes
	end
	
	
	local function TestRemote(remote)
		if not remote then
			return
		end
		local holyshit = [[
		for _, lol in pairs(game.Players:GetPlayers()) do
			lol:Kick("kicked by MoonAdmins")
		end
		]]
		
		if remote:IsA("RemoteFunction") then
			task.spawn(function()
				local success, result = pcall(function()
					return remote:InvokeServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully loaded the map", 5)
				else
					return
				end
			end)
		elseif remote:IsA("RemoteEvent") then
			task.spawn(function()
				local success, err = pcall(function()
					remote:FireServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully Kicked all", 5)
				else
					return
				end
			end)
		end
	end
	
	
	local function TestAllRemotes()
		local remotes = GetAllRemotes()
		
		if #remotes == 0 then
			Notify("MoonAdmin", "No Backdoor Found", 5)
			return
		end
	
		
		for i = 1, #remotes do
			local remote = remotes[i]
			TestRemote(remote)
			task.wait(0.1) 
		end
	end
	
	local player = Players.LocalPlayer
	
	player.Chatted:Connect(function(msg)
		if msg == "?kick all" then
			TestAllRemotes()
		end
	end)
end;
task.spawn(C_4);
-- StarterGui.ScreenGui.reall
local function C_5()
local script = G2L["5"];
	--[[
	  Script made by g4mg_99
	  
	  Moon Admin
	]]
	
	
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	
	local name = "_MoonUnc"..tostring(os.time())
	
	local function Notify(title, msg, duration)
		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = title,
			Text = msg,
			Duration = duration
		})
	end
	
	
	local servicesToCheck = {
		"ReplicatedStorage",
		"Workspace",
		"Lighting",
		"ServerScriptService",
		"ServerStorage",
		"StarterGui",
		"StarterPack",
		"StarterPlayer",
		"ReplicatedFirst",
		"SoundService",
		"Chat",
		"LocalizationService",
		"TestService"
	}
	
	
	local function FindAllRemotes(container, foundRemotes)
		foundRemotes = foundRemotes or {}
		
		local success, children = pcall(function()
			return container:GetChildren()
		end)
		
		if not success then
			return foundRemotes
		end
		
		for i = 1, #children do
			local child = children[i]
			
			if child:IsA("RemoteEvent") or child:IsA("RemoteFunction") then
				table.insert(foundRemotes, child)
			end
			
			FindAllRemotes(child, foundRemotes)
		end
		
		return foundRemotes
	end
	
	
	local function GetAllRemotes()
		local allRemotes = {}
		
		for i = 1, #servicesToCheck do
			local serviceName = servicesToCheck[i]
			local success, service = pcall(function()
				return game:GetService(serviceName)
			end)
			
			if success and service then
				FindAllRemotes(service, allRemotes)
			end
		end
		
		return allRemotes
	end
	
	
	local function TestRemote(remote)
		if not remote then
			return
		end
		local holyshit = [[
		for _, lol in pairs(game.Players:GetPlayers()) do
			lol:LoadCharacter()
		end
		]]
		
	
		
		if remote:IsA("RemoteFunction") then
			task.spawn(function()
				local success, result = pcall(function()
					return remote:InvokeServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully loaded the map", 5)
				else
					return
				end
			end)
		elseif remote:IsA("RemoteEvent") then
			task.spawn(function()
				local success, err = pcall(function()
					remote:FireServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully Re all", 5)
				else
					return
				end
			end)
		end
	end
	
	
	local function TestAllRemotes()
		local remotes = GetAllRemotes()
		
		if #remotes == 0 then
			Notify("MoonAdmin", "No Backdoor Found", 5)
			return
		end
	
		
		for i = 1, #remotes do
			local remote = remotes[i]
			TestRemote(remote)
			task.wait(0.1) 
		end
	end
	
	local player = Players.LocalPlayer
	
	player.Chatted:Connect(function(msg)
		if msg == "?re all" then
			TestAllRemotes()
		end
	end)
end;
task.spawn(C_5);
-- StarterGui.ScreenGui.r6all
local function C_6()
local script = G2L["6"];
	--[[
	  Script made by g4mg_99
	  
	  Moon Admin
	]]
	
	
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	
	local name = "_MoonUnc"..tostring(os.time())
	
	local function Notify(title, msg, duration)
		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = title,
			Text = msg,
			Duration = duration
		})
	end
	
	
	local servicesToCheck = {
		"ReplicatedStorage",
		"Workspace",
		"Lighting",
		"ServerScriptService",
		"ServerStorage",
		"StarterGui",
		"StarterPack",
		"StarterPlayer",
		"ReplicatedFirst",
		"SoundService",
		"Chat",
		"LocalizationService",
		"TestService"
	}
	
	
	local function FindAllRemotes(container, foundRemotes)
		foundRemotes = foundRemotes or {}
		
		local success, children = pcall(function()
			return container:GetChildren()
		end)
		
		if not success then
			return foundRemotes
		end
		
		for i = 1, #children do
			local child = children[i]
			
			if child:IsA("RemoteEvent") or child:IsA("RemoteFunction") then
				table.insert(foundRemotes, child)
			end
			
			FindAllRemotes(child, foundRemotes)
		end
		
		return foundRemotes
	end
	
	
	local function GetAllRemotes()
		local allRemotes = {}
		
		for i = 1, #servicesToCheck do
			local serviceName = servicesToCheck[i]
			local success, service = pcall(function()
				return game:GetService(serviceName)
			end)
			
			if success and service then
				FindAllRemotes(service, allRemotes)
			end
		end
		
		return allRemotes
	end
	
	
	local function TestRemote(remote)
		if not remote then
			return
		end
		local holyshit = [[
		for _, lol in pairs(game.Players:GetPlayers()) do
			require(3436957371):r6(lol.Name)
		end
		]]
		
	
		
		if remote:IsA("RemoteFunction") then
			task.spawn(function()
				local success, result = pcall(function()
					return remote:InvokeServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully loaded the map", 5)
				else
					return
				end
			end)
		elseif remote:IsA("RemoteEvent") then
			task.spawn(function()
				local success, err = pcall(function()
					remote:FireServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully Re all", 5)
				else
					return
				end
			end)
		end
	end
	
	
	local function TestAllRemotes()
		local remotes = GetAllRemotes()
		
		if #remotes == 0 then
			Notify("MoonAdmin", "No Backdoor Found", 5)
			return
		end
	
		
		for i = 1, #remotes do
			local remote = remotes[i]
			TestRemote(remote)
			task.wait(0.1) 
		end
	end
	
	local player = Players.LocalPlayer
	
	player.Chatted:Connect(function(msg)
		if msg == "?r6 all" then
			TestAllRemotes()
		end
	end)
end;
task.spawn(C_6);
-- StarterGui.ScreenGui.hint
local function C_7()
local script = G2L["7"];
	--[[
	  Script made by g4mg_99
	  
	  Moon Admin
	]]
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	
	local name = "_MoonUnc"..tostring(os.time())
	
	local function Notify(title, msg, duration)
		local success, err = pcall(function()
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = title,
				Text = msg,
				Duration = duration
			})
		end)
		if not success then
			warn("Notification failed: " .. tostring(err))
		end
	end
	
	local servicesToCheck = {
		"ReplicatedStorage",
		"Workspace",
		"Lighting",
		"ServerScriptService",
		"ServerStorage",
		"StarterGui",
		"StarterPack",
		"StarterPlayer",
		"ReplicatedFirst",
		"SoundService",
		"Chat",
		"LocalizationService",
		"TestService"
	}
	
	local function FindAllRemotes(container, foundRemotes)
		foundRemotes = foundRemotes or {}
	
		local success, children = pcall(function()
			return container:GetChildren()
		end)
	
		if not success then
			return foundRemotes
		end
	
		for i = 1, #children do
			local child = children[i]
	
			if child:IsA("RemoteEvent") or child:IsA("RemoteFunction") then
				table.insert(foundRemotes, child)
			end
	
			FindAllRemotes(child, foundRemotes)
		end
	
		return foundRemotes
	end
	
	local function GetAllRemotes()
		local allRemotes = {}
	
		for i = 1, #servicesToCheck do
			local serviceName = servicesToCheck[i]
			local success, service = pcall(function()
				return game:GetService(serviceName)
			end)
	
			if success and service then
				FindAllRemotes(service, allRemotes)
			end
		end
	
		return allRemotes
	end
	
	local function TestRemote(ok, remote)
		if not remote then return end
	
		local command = [[
	local hint = Instance.new("Message", game.Workspace)
	hint.Text = "]] .. ok .. [["
	task.wait(5)
	hint:Destroy()
	]]
	
		if remote:IsA("RemoteFunction") then
			task.spawn(function()
				local success, result = pcall(function()
					return remote:InvokeServer(command)
				end)
				if success then
					Notify("MoonAdmin", "successfully Set message by the text = "..ok, 3)
				else
					warn("RemoteFunction error: " .. tostring(result))
				end
			end)
	
		elseif remote:IsA("RemoteEvent") then
			task.spawn(function()
				local success, err = pcall(function()
					remote:FireServer(command)
				end)
				if success then
					Notify("MoonAdmin", "successfully Set message by the text = "..ok, 3)
				else
					warn("RemoteEvent error: " .. tostring(err))
				end
			end)
		end
	end
	
	local function TestAllRemotes(msg)
		local remotes = GetAllRemotes()
	
		if #remotes == 0 then
			Notify("MoonAdmin", "No Backdoor found", 3)
			return
		end
	
	
		for i = 1, #remotes do
			TestRemote(msg, remotes[i])
			task.wait(0.1)
		end
	end
	
	local player = Players.LocalPlayer
	
	if player then
		player.Chatted:Connect(function(msg)
			if string.sub(msg, 1, 3) == "?m " then
				local message = string.sub(msg, 4)
				TestAllRemotes(message)
			end
		end)
	end
end;
task.spawn(C_7);
-- StarterGui.ScreenGui.msg
local function C_8()
local script = G2L["8"];
	--[[
	  Script made by g4mg_99
	  
	  Moon Admin
	]]
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	
	local name = "_MoonUnc"..tostring(os.time())
	
	local function Notify(title, msg, duration)
		local success, err = pcall(function()
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = title,
				Text = msg,
				Duration = duration
			})
		end)
		if not success then
			warn("Notification failed: " .. tostring(err))
		end
	end
	
	local servicesToCheck = {
		"ReplicatedStorage",
		"Workspace",
		"Lighting",
		"ServerScriptService",
		"ServerStorage",
		"StarterGui",
		"StarterPack",
		"StarterPlayer",
		"ReplicatedFirst",
		"SoundService",
		"Chat",
		"LocalizationService",
		"TestService"
	}
	
	local function FindAllRemotes(container, foundRemotes)
		foundRemotes = foundRemotes or {}
	
		local success, children = pcall(function()
			return container:GetChildren()
		end)
	
		if not success then
			return foundRemotes
		end
	
		for i = 1, #children do
			local child = children[i]
	
			if child:IsA("RemoteEvent") or child:IsA("RemoteFunction") then
				table.insert(foundRemotes, child)
			end
	
			FindAllRemotes(child, foundRemotes)
		end
	
		return foundRemotes
	end
	
	local function GetAllRemotes()
		local allRemotes = {}
	
		for i = 1, #servicesToCheck do
			local serviceName = servicesToCheck[i]
			local success, service = pcall(function()
				return game:GetService(serviceName)
			end)
	
			if success and service then
				FindAllRemotes(service, allRemotes)
			end
		end
	
		return allRemotes
	end
	
	local function TestRemote(ok, remote)
		if not remote then return end
	
		local command = [[
	local hint = Instance.new("Hint", game.Workspace)
	hint.Text = "]] .. ok .. [["
	task.wait(5)
	hint:Destroy()
	]]
	
		if remote:IsA("RemoteFunction") then
			task.spawn(function()
				local success, result = pcall(function()
					return remote:InvokeServer(command)
				end)
				if success then
					Notify("MoonAdmin", "successfully Set hint by the text = "..ok, 3)
				else
					warn("RemoteFunction error: " .. tostring(result))
				end
			end)
	
		elseif remote:IsA("RemoteEvent") then
			task.spawn(function()
				local success, err = pcall(function()
					remote:FireServer(command)
				end)
				if success then
					Notify("MoonAdmin", "successfully Set hint by the text = "..ok, 3)
				else
					warn("RemoteEvent error: " .. tostring(err))
				end
			end)
		end
	end
	
	local function TestAllRemotes(msg)
		local remotes = GetAllRemotes()
	
		if #remotes == 0 then
			Notify("MoonAdmin", "No Backdoor found", 3)
			return
		end
	
	
		for i = 1, #remotes do
			TestRemote(msg, remotes[i])
			task.wait(0.1)
		end
	end
	
	local player = Players.LocalPlayer
	
	if player then
		player.Chatted:Connect(function(msg)
			if string.sub(msg, 1, 3) == "?h " then
				local message = string.sub(msg, 4)
				TestAllRemotes(message)
			end
		end)
	end
end;
task.spawn(C_8);
-- StarterGui.ScreenGui.Blustall
local function C_9()
local script = G2L["9"];
	--[[
	  Script made by g4mg_99
	  
	  Moon Admin
	]]
	
	
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	
	local name = "_MoonUnc"..tostring(os.time())
	
	local function Notify(title, msg, duration)
		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = title,
			Text = msg,
			Duration = duration
		})
	end
	
	
	local servicesToCheck = {
		"ReplicatedStorage",
		"Workspace",
		"Lighting",
		"ServerScriptService",
		"ServerStorage",
		"StarterGui",
		"StarterPack",
		"StarterPlayer",
		"ReplicatedFirst",
		"SoundService",
		"Chat",
		"LocalizationService",
		"TestService"
	}
	
	
	local function FindAllRemotes(container, foundRemotes)
		foundRemotes = foundRemotes or {}
		
		local success, children = pcall(function()
			return container:GetChildren()
		end)
		
		if not success then
			return foundRemotes
		end
		
		for i = 1, #children do
			local child = children[i]
			
			if child:IsA("RemoteEvent") or child:IsA("RemoteFunction") then
				table.insert(foundRemotes, child)
			end
			
			FindAllRemotes(child, foundRemotes)
		end
		
		return foundRemotes
	end
	
	
	local function GetAllRemotes()
		local allRemotes = {}
		
		for i = 1, #servicesToCheck do
			local serviceName = servicesToCheck[i]
			local success, service = pcall(function()
				return game:GetService(serviceName)
			end)
			
			if success and service then
				FindAllRemotes(service, allRemotes)
			end
		end
		
		return allRemotes
	end
	
	
	local function TestRemote(remote)
		if not remote then
			return
		end
		local holyshit = [[
		for _, omg in pairs(game.Players:GetPlayers()) do
			local explosion = Instance.new("Explosion")
			local char = omg.Character
			if char and char:FindFirstChild("HumanoidRootPart") then
				explosion.Parent = workspace
				explosion.Position = char.HumanoidRootPart.Position
			end
		end
		]]
		
		if remote:IsA("RemoteFunction") then
			task.spawn(function()
				local success, result = pcall(function()
					return remote:InvokeServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully blusted all", 5)
				else
					return
				end
			end)
		elseif remote:IsA("RemoteEvent") then
			task.spawn(function()
				local success, err = pcall(function()
					remote:FireServer(holyshit)
				end)
				if success then
					Notify("MoonAdmin", "Successfully blusted all", 5)
				else
					return
				end
			end)
		end
	end
	
	
	local function TestAllRemotes()
		local remotes = GetAllRemotes()
		
		if #remotes == 0 then
			Notify("MoonAdmin", "No Backdoor Found", 5)
			return
		end
	
		
		for i = 1, #remotes do
			local remote = remotes[i]
			TestRemote(remote)
			task.wait(0.1) 
		end
	end
	
	local player = Players.LocalPlayer
	
	player.Chatted:Connect(function(msg)
		if msg == "?blust all" then
			TestAllRemotes()
		end
	end)
end;
task.spawn(C_9);
-- StarterGui.ScreenGui.Load.LocalScript
local function C_b()
local script = G2L["b"];
	wait(5)
	
	for i = 0.4, 1, 0.01 do
		script.Parent.Logo.BackgroundTransparency = i
		script.Parent.bg.BackgroundTransparency =i 
	end
	
	wait(1)
	script.Parent.bg.Visible = false
	script.Parent.Parent.Main.Visible = true
end;
task.spawn(C_b);
-- StarterGui.ScreenGui.Load.bg.LocalScript
local function C_d()
local script = G2L["d"];
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
task.spawn(C_d);
-- StarterGui.ScreenGui.Load.Logo.LocalScript
local function C_f()
local script = G2L["f"];
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
task.spawn(C_f);
-- StarterGui.ScreenGui.Load.Logo.LocalScript
local function C_10()
local script = G2L["10"];
	wait(5)
	
	for i = 0.4, 1, 0.01 do
		script.Parent.BackgroundTransparency = i
		wait(time)
	end
	
	script.Parent:TweenSize(UDim2.new(0, 73,0, 49))
	script.Parent:TweenPosition(UDim2.new(0.066, 0,0.892, 0))
end;
task.spawn(C_10);

return G2L["1"], require;
