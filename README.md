-- biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

-- janela principal

local Window = Fluent:CreateWindow({
    Title = "Ana Sofia Hub (BETA)" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

-- Abas

local Tabs = {
    Main = Window:AddTab({ Title = "Inicio" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
-- Abas

local Tabs = {
    Main = Window:AddTab({ Title = "Admins" }),

-- paragrafo

    Tabs.Main:AddParagraph({
        Title = "Executado",
        Content = "Script executado com sucesso"
    })

-- paragrafo

    Tabs.Main:AddParagraph({
        Title = "Key do Dopamina",
        Content = "Graciasporseleccionarnos"
    })
    
    -- paragrafo

    Tabs.Main:AddParagraph({
        Title = "Key do Shadow",
        Content = "</>FaseTesting"
    })

-- botao

Tabs.MainSection:NewButton("NAME ESP", "Q to toggle on and off", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/ESP-Script/main/ESP.lua"))()
end)

Tabs.Main:AddButton({ Title = "Ana shadow", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/xscripts7/XScripts/refs/heads/XScript/ShadowHub", true))() end })
Tabs.Main:AddButton({ Title = "Ana dopamina", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Dopamina-Hub-17894"))() end })
Tabs.Main:AddButton({ Title = "Ana sky", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/yofriendfromschool1/Sky-Hub/main/SkyHub.txt"))()end })
Tabs.Main:AddButton({ Title = "Ana sander X", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/New.lua'))() end })
Tabs.Main:AddButton({ Title = "Ana+carl hub", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/carlosdaniel987/Carlos/refs/heads/main/README.md"))() end })
Tabs.Admins:AddButton({ Title = "Fates admin", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua end })
Tabs.Admins:AddButton({ Title = "CMD X", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source end })
Tabs.Admins:AddButton({ Title = "infinite yeld", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source end })
