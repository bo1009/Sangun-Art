getgenv().Config = {
  ["Hide"] = true,
  ["WhiteScreen"] = false, 
  ["Fps Boost"] = true,
  ["Webhook"] = "https://discord.com/api/webhooks/1173059368447655996/V118UZx4nJ0bCfgKHzFfxtsPav8JT9IA18iPT9iv49CNvinGtqJqhvNOjm7jifHRsGbY", 
  ["Team"] = "Marines", 
  ["Fps Cap"] = 30,
  ["Item"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["C"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Blox Fruit"] = {
            ["Enable"] = false,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 1.5},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["C"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["V"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["F"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Sword"] = {
            ["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Gun"] = {
            ["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0}
        } 
      } 
}

loadstring(game:HttpGet("https://eltrul.xyz/Annie Bounty.lua"))()
