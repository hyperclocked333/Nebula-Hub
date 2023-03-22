# Nebula Hub - The Hub For The Most Unasked Games
this is nebula hub  
i do what i do and it works 99% of the time (its open sourced too 😊)
loadstrings:  
miners haven mod closet cheat:  

```
--[[made by: https://github.com/hyperclocked333 ]]--

getgenv().settings = {
  layout = 1,
  autofarmToggle = "t",
  delays = { -- so you dont get macro checked and sniped out of existance
      layout = {
          minimum = .84,
          maximum = 1.59,
      },
      rebirth = {
          minimum = 1.07,
          maximum = 1.83,
      },
  },
  craftsmanToggle = "z", -- toggle the craftsman gui
  wandererToggle = "x", -- toggle the wanderer/masked man gui
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/hyperclocked333/Nebula-Hub/main/miners%20haven%20mod"))()
