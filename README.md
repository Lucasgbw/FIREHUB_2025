local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

Fluent:Notify({ Title = "Notification", Content = "obrigado por usa meu script $" })




local Window = Fluent:CreateWindow({
    Title = "FIRE HUB🔥" .. Fluent.Version,
    TabWidth = 130, Size = UDim2.fromOffset(580, 460), Theme = "Red"
})

local alvodongc
local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "Nome"
local Nzx = Instance.new("ImageButton")
ScreenGui.Parent = game.CoreGui

-- Criando o UICorner para deixar o botão redondo
local Estetica = Instance.new("UICorner")
Estetica.CornerRadius = UDim.new(1, 0) -- O "1" faz o botão ficar completamente redondo
Estetica.Parent = Nzx -- Aplica o UICorner ao botão Nzx

myzx.Name = "nyyzx"
nyzx.Parent = ScreenGui
Nzx.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Nzx.Position = UDim2.new(0.799450576, 0, 0.278925627, 0)
Nzx.Size = UDim2.new(0, 60, 0, 60)
Nzx.Visible = true
Nzx.Draggable = true     
Nzx.Active = true     
Nzx.Selectable = true
Nzx.Image = "rbxassetid://103006981698580" -- Id da imagem aqui

-- Função para alternar a visibilidade de "alvodongc"
for i, v in pairs(game.CoreGui:GetDescendants()) do
    if v.Name == "CanvasGroup" then
        alvodongc = v.Parent
    end
end

local function FVGE_fake_script()
    Nzx.MouseButton1Up:Connect(function()
        task.wait()
        if not toggle then
            toggle = true
            alvodongc.Visible = true
        else
            toggle = false
            alvodongc.Visible = false
        end
    end)
end
coroutine.wrap(FVGE_fake_script)()



local MainTab = Window:AddTab({ Title = "scripts☃️" })

MainTab:AddButton({
    Title = "ANIMAÇAO DE R6📿",
    Callback = function()
        print("Botão clicado!")
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Imagnir/r6_anims_for_r15/main/r6_anims.lua", true))()
    end})

MainTab:AddButton({
    Title = "nameless admin",
    Callback = function()
        print("Botão clicado!")loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Nameless-Admin-V2-24856"))()
    end
})

MainTab:AddButton({
    Title = "script slow motion",
    Callback = function()
        print("Botão clicado!") loadstring(game:HttpGet("https://pastebin.com/raw/dAnuL1X3"))()
    end
})

MainTab:AddButton({
    Title = "fly gui",
    Callback = function()
        print("Botão clicado!") loadstring(game:HttpGet('https://pastebin.com/raw/YSL3xKYU'))()
    end
})

MainTab:AddButton({
    Title = "fake lag",
    Callback = function()
        print("Botão clicado!")loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FAKE-LAG-22520"))()
   end
})

local MainTab = Window:AddTab({ Title = "scripts v2💥" })

MainTab:AddButton({
    Title = "ID GEMIDO DE SAFADINHA",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =6865649264,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "ID gemido de gostosa",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =7818422471,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id de menina sus",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8233569802,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id estourado",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 7236490488,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id de menina com safadeza",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8161174075,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id gemido",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8107899910,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})


local MainTab = Window:AddTab({ Title = "scripts v3😈" })

MainTab:AddButton({
    Title = "cleiti brookhaven ",
    Callback = function()
        print("Botão clicado!")loadstring(game:HttpGet("https://pastefy.app/ta8BeBZc/raw"))()
    end
})

MainTab:AddButton({
    Title = "script sus",
    Callback = function()
        print("Botão clicado!")--Made by muscle_legends2021 (Gio)
--YouTube: GioBolqvi

loadstring(game:HttpGet("https://pastefy.app/YZoglOyJ/raw"))()
    end
})

MainTab:AddButton({
    Title = "serpente x",
    Callback = function()
        print("Botão clicado!")loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/SerpenteXbetaByDefense129/main/Serpente.Scripts"))()
    end
})

MainTab:AddButton({
    Title = "infinite yield",
    Callback = function()
        print("Botão clicado!")loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
    end
})

MainTab:AddButton({
    Title = "fe blackhole",
    Callback = function()
        print("Botão clicado!")
loadstring(game:HttpGet("https://raw.githubusercontent.com/GoofyBlox/GoofyZ/refs/heads/main/Best/Vortex.lua", true))()
    end
})

MainTab:AddButton({
    Title = "vfly",
    Callback = function()
        print("Botão clicado!")
loadstring(game:HttpGet("https://raw.githubusercontent.com/HubStudioInjection/Exploits/refs/heads/main/VFly.lua"))()
    end
})

MainTab:AddButton({
    Title = "speed hub",
    Callback = function()
        print("Botão clicado!") loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
    end
})


local MainTab = Window:AddTab({ Title = "scripts v4 com IDS👻" })


MainTab:AddButton({
    Title = "id round 6",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8166751254,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id boneca catando",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 7738210779,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id ???",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 7797658235,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id assustar",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =146563959,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id assustar 2",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =1332644289,
    [3] = 0.8
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id assustar 3",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =8411427507,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id assustar 4",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 6854647842,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id assustar 5",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 930613220,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

local MainTab = Window:AddTab({ Title = "scripts v5 com IDS🥠" })

MainTab:AddButton({
    Title = "REDZ BLOX fruits ",
    Callback = function()
        print("Botão clicado!")
loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))()
    end
})

MainTab:AddButton({
    Title = "rochips painel",
    Callback = function()
        print("Botão clicado!")
loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Rochips-Universal-21865"))()
    end
})

MainTab:AddButton({
    Title = "SETARIUM HUB",
    Callback = function()
        print("Botão clicado!")
loadstring(game:HttpGet("https://raw.githubusercontent.com/L0RD-SUD0/Sunterium-Hub/refs/heads/main/BETA%20RELEASE%200.1"))() 
    end
})

MainTab:AddButton({
    Title = "THE darkones",
    Callback = function()
        print("Botão clicado!")loadstring(game:HttpGet('https://raw.githubusercontent.com/TheDarkoneMarcillisePex/Other-Scripts/main/Brook%20Haven%20Gui'))()
    end
})

MainTab:AddButton({
    Title = "id engraçado",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 6489326185,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id engraçado 2",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =3021344720,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id engraçado 3",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =5992724820,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})


MainTab:AddButton({
    Title = "id engraçado 4",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =9128808411,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id engraçado 65?",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =7772388444,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

local MainTab = Window:AddTab({ Title = "sounds🦠⚒️🦠" })

MainTab:AddButton({
    Title = "id de menina sexxxxo",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8397021114,
    [3] = 1.2
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id Sigma.",
    Callback = function()local args = {
    [1] = workspace,
    [2] =5992724820,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id assustador",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 6470853207,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "pessoa falando bucxceta",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =6416719788 ,
    [3] = 10
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id pau e bola short",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =6416682623 ,
    [3] = 10
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id de um tapixxxznha gosxtxoso",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 4810649957,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

local MainTab = Window:AddTab({ Title = "sounds v2💤" })

MainTab:AddButton({
    Title = "id de um pedófilo com criança",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 1562596766,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id de menina safadeza gostosa",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8259946669,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id estouradasso",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 9074246432,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id de sirene assustador",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 5754340849,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

local MainTab = Window:AddTab({ Title = "sounds v3👾" })

MainTab:AddButton({
    Title = "id de risada sombria",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8714865850,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

local MainTab = Window:AddTab({ Title = "sounds v4🖥️😭" })

MainTab:AddButton({
    Title = "sound 1",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 7644757406,
    [3] = 0.9
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})

MainTab:AddButton({
    Title = "sound 2",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 103211341252816,
    [3] = 1.1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})

MainTab:AddButton({
    Title = "sound 3",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 7127692762,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})


MainTab:AddButton({
    Title = "sound 4",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 71276927627,
    [3] = 1.1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})

MainTab:AddButton({
    Title = "sound 5",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 6416677392 ,
    [3] = 10
}

MainTab:AddButton({
    Title = "sound 6",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] =6486261822,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})

local MainTab = Window:AddTab({ Title = "sounds v5" })

MainTab:AddButton({
    Title = "sound 1",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 6416686951,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})

MainTab:AddButton({
    Title = "sound 2",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 4506260428,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})

MainTab:AddButton({
    Title = "sound 3",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 268116333,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})

MainTab:AddButton({
    Title = "sound 4",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 6565335291,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})

MainTab:AddButton({
    Title = "sound 5",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 3419187043 ,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end})
