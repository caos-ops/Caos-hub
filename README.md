if game.PlaceId == 2753915549 then

World1 = true

elseif game.PlaceId == 4442272183 then

World2 = true

elseif game.PlaceId == 7449423635 then

World3 = true

else

game:GetService("Players").LocalPlayer:Kick("Do not Support, Please wait...")

end

 

function CheckQuest()

MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value

if World1 then

if MyLevel == 1 or MyLevel <= 9 then

Mon = "Bandit"

LevelQuest = 1

NameQuest = "BanditQuest1"

NameMon = "Bandit"

CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)

CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)

elseif MyLevel == 10 or MyLevel <= 14 then

Mon = "Monkey"

LevelQuest = 1

NameQuest = "JungleQuest"

NameMon = "Monkey"

CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)

CFrameMon = CFrame.new(-1448.51806640625, 67.85301208496094, 11.46579647064209)

elseif MyLevel == 15 or MyLevel <= 29 then

Mon = "Gorilla"

LevelQuest = 2

NameQuest = "JungleQuest"

NameMon = "Gorilla"

CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)

CFrameMon = CFrame.new(-1129.8836669921875, 40.46354675292969, -525.4237060546875)

elseif MyLevel == 30 or MyLevel <= 39 then

Mon = "Pirate"

LevelQuest = 1

NameQuest = "BuggyQuest1"

NameMon = "Pirate"

CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)

CFrameMon = CFrame.new(-1103.513427734375, 13.752052307128906, 3896.091064453125)

elseif MyLevel == 40 or MyLevel <= 59 then

Mon = "Brute"

LevelQuest = 2

NameQuest = "BuggyQuest1"

NameMon = "Brute"

CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)

CFrameMon = CFrame.new(-1140.083740234375, 14.809885025024414, 4322.92138671875)

elseif MyLevel == 60 or MyLevel <= 74 then

Mon = "Desert Bandit"

LevelQuest = 1

NameQuest = "DesertQuest"

NameMon = "Desert Bandit"

CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)

CFrameMon = CFrame.new(924.7998046875, 6.44867467880249, 4481.5859375)

elseif MyLevel == 75 or MyLevel <= 89 then

Mon = "Desert Officer"

LevelQuest = 2

NameQuest = "DesertQuest"

NameMon = "Desert Officer"

CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)

CFrameMon = CFrame.new(1608.2822265625, 8.614224433898926, 4371.00732421875)

elseif MyLevel == 90 or MyLevel <= 99 then

Mon = "Snow Bandit"

LevelQuest = 1

NameQuest = "SnowQuest"

NameMon = "Snow Bandit"

CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)

CFrameMon = CFrame.new(1354.347900390625, 87.27277374267578, -1393.946533203125)

elseif MyLevel == 100 or MyLevel <= 119 then

Mon = "Snowman"

LevelQuest = 2

NameQuest = "SnowQuest"

NameMon = "Snowman"

CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)

CFrameMon = CFrame.new(1201.6412353515625, 144.57958984375, -1550.0670166015625)

elseif MyLevel == 120 or MyLevel <= 149 then

Mon = "Chief Petty Officer"

LevelQuest = 1

NameQuest = "MarineQuest2"

NameMon = "Chief Petty Officer"

CFrameQuest = CFrame.new(-5039.58643, 27.3500385, 4324.68018, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-4881.23095703125, 22.65204429626465, 4273.75244140625)

elseif MyLevel == 150 or MyLevel <= 174 then

Mon = "Sky Bandit"

LevelQuest = 1

NameQuest = "SkyQuest"

NameMon = "Sky Bandit"

CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)

CFrameMon = CFrame.new(-4953.20703125, 295.74420166015625, -2899.22900390625)

elseif MyLevel == 175 or MyLevel <= 189 then

Mon = "Dark Master"

LevelQuest = 2

NameQuest = "SkyQuest"

NameMon = "Dark Master"

CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)

CFrameMon = CFrame.new(-5259.8447265625, 391.3976745605469, -2229.035400390625)

elseif MyLevel == 190 or MyLevel <= 209 then

Mon = "Prisoner"

LevelQuest = 1

NameQuest = "PrisonerQuest"

NameMon = "Prisoner"

CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)

CFrameMon = CFrame.new(5098.9736328125, -0.3204058110713959, 474.2373352050781)

elseif MyLevel == 210 or MyLevel <= 249 then

Mon = "Dangerous Prisoner"

LevelQuest = 2

NameQuest = "PrisonerQuest"

NameMon = "Dangerous Prisoner"

CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)

CFrameMon = CFrame.new(5654.5634765625, 15.633401870727539, 866.2991943359375)

elseif MyLevel == 250 or MyLevel <= 274 then

Mon = "Toga Warrior"

LevelQuest = 1

NameQuest = "ColosseumQuest"

NameMon = "Toga Warrior"

CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)

CFrameMon = CFrame.new(-1820.21484375, 51.68385696411133, -2740.6650390625)

elseif MyLevel == 275 or MyLevel <= 299 then

Mon = "Gladiator"

LevelQuest = 2

NameQuest = "ColosseumQuest"

NameMon = "Gladiator"

CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)

CFrameMon = CFrame.new(-1292.838134765625, 56.380882263183594, -3339.031494140625)

elseif MyLevel == 300 or MyLevel <= 324 then

Mon = "Military Soldier"

LevelQuest = 1

NameQuest = "MagmaQuest"

NameMon = "Military Soldier"

CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)

CFrameMon = CFrame.new(-5411.16455078125, 11.081554412841797, 8454.29296875)

elseif MyLevel == 325 or MyLevel <= 374 then

Mon = "Military Spy"

LevelQuest = 2

NameQuest = "MagmaQuest"

NameMon = "Military Spy"

CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)

CFrameMon = CFrame.new(-5802.8681640625, 86.26241302490234, 8828.859375)

elseif MyLevel == 375 or MyLevel <= 399 then

Mon = "Fishman Warrior"

LevelQuest = 1

NameQuest = "FishmanQuest"

NameMon = "Fishman Warrior"

CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)

CFrameMon = CFrame.new(60878.30078125, 18.482830047607422, 1543.7574462890625)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))

end

elseif MyLevel == 400 or MyLevel <= 449 then

Mon = "Fishman Commando"

LevelQuest = 2

NameQuest = "FishmanQuest"

NameMon = "Fishman Commando"

CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)

CFrameMon = CFrame.new(61922.6328125, 18.482830047607422, 1493.934326171875)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))

end

elseif MyLevel == 450 or MyLevel <= 474 then

Mon = "God's Guard"

LevelQuest = 1

NameQuest = "SkyExp1Quest"

NameMon = "God's Guard"

CFrameQuest = CFrame.new(-4721.88867, 843.874695, -1949.96643, 0.996191859, -0, -0.0871884301, 0, 1, -0, 0.0871884301, 0, 0.996191859)

CFrameMon = CFrame.new(-4710.04296875, 845.2769775390625, -1927.3079833984375)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))

end

elseif MyLevel == 475 or MyLevel <= 524 then

Mon = "Shanda"

LevelQuest = 2

NameQuest = "SkyExp1Quest"

NameMon = "Shanda"

CFrameQuest = CFrame.new(-7859.09814, 5544.19043, -381.476196, -0.422592998, 0, 0.906319618, 0, 1, 0, -0.906319618, 0, -0.422592998)

CFrameMon = CFrame.new(-7678.48974609375, 5566.40380859375, -497.2156066894531)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))

end

elseif MyLevel == 525 or MyLevel <= 549 then

Mon = "Royal Squad"

LevelQuest = 1

NameQuest = "SkyExp2Quest"

NameMon = "Royal Squad"

CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-7624.25244140625, 5658.13330078125, -1467.354248046875)

elseif MyLevel == 550 or MyLevel <= 624 then

Mon = "Royal Soldier"

LevelQuest = 2

NameQuest = "SkyExp2Quest"

NameMon = "Royal Soldier"

CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-7836.75341796875, 5645.6640625, -1790.6236572265625)

elseif MyLevel == 625 or MyLevel <= 649 then

Mon = "Galley Pirate"

LevelQuest = 1

NameQuest = "FountainQuest"

NameMon = "Galley Pirate"

CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)

CFrameMon = CFrame.new(5551.02197265625, 78.90135192871094, 3930.412841796875)

elseif MyLevel >= 650 then

Mon = "Galley Captain"

LevelQuest = 2

NameQuest = "FountainQuest"

NameMon = "Galley Captain"

CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)

CFrameMon = CFrame.new(5441.95166015625, 42.50205993652344, 4950.09375)

end

elseif World2 then

if MyLevel == 700 or MyLevel <= 724 then

Mon = "Raider"

LevelQuest = 1

NameQuest = "Area1Quest"

NameMon = "Raider"

CFrameQuest = CFrame.new(-429.543518, 71.7699966, 1836.18188, -0.22495985, 0, -0.974368095, 0, 1, 0, 0.974368095, 0, -0.22495985)

CFrameMon = CFrame.new(-728.3267211914062, 52.779319763183594, 2345.7705078125)

elseif MyLevel == 725 or MyLevel <= 774 then

Mon = "Mercenary"

LevelQuest = 2

NameQuest = "Area1Quest"

NameMon = "Mercenary"

CFrameQuest = CFrame.new(-429.543518, 71.7699966, 1836.18188, -0.22495985, 0, -0.974368095, 0, 1, 0, 0.974368095, 0, -0.22495985)

CFrameMon = CFrame.new(-1004.3244018554688, 80.15886688232422, 1424.619384765625)

elseif MyLevel == 775 or MyLevel <= 799 then

Mon = "Swan Pirate"

LevelQuest = 1

NameQuest = "Area2Quest"

NameMon = "Swan Pirate"

CFrameQuest = CFrame.new(638.43811, 71.769989, 918.282898, 0.139203906, 0, 0.99026376, 0, 1, 0, -0.99026376, 0, 0.139203906)

CFrameMon = CFrame.new(1068.664306640625, 137.61428833007812, 1322.1060791015625)

elseif MyLevel == 800 or MyLevel <= 874 then

Mon = "Factory Staff"

NameQuest = "Area2Quest"

LevelQuest = 2

NameMon = "Factory Staff"

CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)

CFrameMon = CFrame.new(73.07867431640625, 81.86344146728516, -27.470672607421875)

elseif MyLevel == 875 or MyLevel <= 899 then

Mon = "Marine Lieutenant"

LevelQuest = 1

NameQuest = "MarineQuest3"

NameMon = "Marine Lieutenant"

CFrameQuest = CFrame.new(-2440.79639, 71.7140732, -3216.06812, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)

CFrameMon = CFrame.new(-2821.372314453125, 75.89727783203125, -3070.089111328125)

elseif MyLevel == 900 or MyLevel <= 949 then

Mon = "Marine Captain"

LevelQuest = 2

NameQuest = "MarineQuest3"

NameMon = "Marine Captain"

CFrameQuest = CFrame.new(-2440.79639, 71.7140732, -3216.06812, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)

CFrameMon = CFrame.new(-1861.2310791015625, 80.17658233642578, -3254.697509765625)

elseif MyLevel == 950 or MyLevel <= 974 then

Mon = "Zombie"

LevelQuest = 1

NameQuest = "ZombieQuest"

NameMon = "Zombie"

CFrameQuest = CFrame.new(-5497.06152, 47.5923004, -795.237061, -0.29242146, 0, -0.95628953, 0, 1, 0, 0.95628953, 0, -0.29242146)

CFrameMon = CFrame.new(-5657.77685546875, 78.96973419189453, -928.68701171875)

elseif MyLevel == 975 or MyLevel <= 999 then

Mon = "Vampire"

LevelQuest = 2

NameQuest = "ZombieQuest"

NameMon = "Vampire"

CFrameQuest = CFrame.new(-5497.06152, 47.5923004, -795.237061, -0.29242146, 0, -0.95628953, 0, 1, 0, 0.95628953, 0, -0.29242146)

CFrameMon = CFrame.new(-6037.66796875, 32.18463897705078, -1340.6597900390625)

elseif MyLevel == 1000 or MyLevel <= 1049 then

Mon = "Snow Trooper"

LevelQuest = 1

NameQuest = "SnowMountainQuest"

NameMon = "Snow Trooper"

CFrameQuest = CFrame.new(609.858826, 400.119904, -5372.25928, -0.374604106, 0, 0.92718488, 0, 1, 0, -0.92718488, 0, -0.374604106)

CFrameMon = CFrame.new(549.1473388671875, 427.3870544433594, -5563.69873046875)

elseif MyLevel == 1050 or MyLevel <= 1099 then

Mon = "Winter Warrior"

LevelQuest = 2

NameQuest = "SnowMountainQuest"

NameMon = "Winter Warrior"

CFrameQuest = CFrame.new(609.858826, 400.119904, -5372.25928, -0.374604106, 0, 0.92718488, 0, 1, 0, -0.92718488, 0, -0.374604106)

CFrameMon = CFrame.new(1142.7451171875, 475.6398010253906, -5199.41650390625)

elseif MyLevel == 1100 or MyLevel <= 1124 then

Mon = "Lab Subordinate"

LevelQuest = 1

NameQuest = "IceSideQuest"

NameMon = "Lab Subordinate"

CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)

CFrameMon = CFrame.new(-5707.4716796875, 15.951709747314453, -4513.39208984375)

elseif MyLevel == 1125 or MyLevel <= 1174 then

Mon = "Horned Warrior"

LevelQuest = 2

NameQuest = "IceSideQuest"

NameMon = "Horned Warrior"

CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)

CFrameMon = CFrame.new(-6341.36669921875, 15.951770782470703, -5723.162109375)

elseif MyLevel == 1175 or MyLevel <= 1199 then

Mon = "Magma Ninja"

LevelQuest = 1

NameQuest = "FireSideQuest"

NameMon = "Magma Ninja"

CFrameQuest = CFrame.new(-5428.03174, 15.0622921, -5299.43457, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)

CFrameMon = CFrame.new(-5449.6728515625, 76.65874481201172, -5808.20068359375)

elseif MyLevel == 1200 or MyLevel <= 1249 then

Mon = "Lava Pirate"

LevelQuest = 2

NameQuest = "FireSideQuest"

NameMon = "Lava Pirate"

CFrameQuest = CFrame.new(-5428.03174, 15.0622921, -5299.43457, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)

CFrameMon = CFrame.new(-5213.33154296875, 49.73788070678711, -4701.451171875)

elseif MyLevel == 1250 or MyLevel <= 1274 then

Mon = "Ship Deckhand"

LevelQuest = 1

NameQuest = "ShipQuest1"

NameMon = "Ship Deckhand"

CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)

CFrameMon = CFrame.new(1212.0111083984375, 150.79205322265625, 33059.24609375)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))

end

elseif MyLevel == 1275 or MyLevel <= 1299 then

Mon = "Ship Engineer"

LevelQuest = 2

NameQuest = "ShipQuest1"

NameMon = "Ship Engineer"

CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)

CFrameMon = CFrame.new(919.4786376953125, 43.54401397705078, 32779.96875)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))

end

elseif MyLevel == 1300 or MyLevel <= 1324 then

Mon = "Ship Steward"

LevelQuest = 1

NameQuest = "ShipQuest2"

NameMon = "Ship Steward"

CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125)

CFrameMon = CFrame.new(919.4385375976562, 129.55599975585938, 33436.03515625)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))

end

elseif MyLevel == 1325 or MyLevel <= 1349 then

Mon = "Ship Officer"

LevelQuest = 2

NameQuest = "ShipQuest2"

NameMon = "Ship Officer"

CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125)

CFrameMon = CFrame.new(1036.0179443359375, 181.4390411376953, 33315.7265625)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))

end

elseif MyLevel == 1350 or MyLevel <= 1374 then

Mon = "Arctic Warrior"

LevelQuest = 1

NameQuest = "FrostQuest"

NameMon = "Arctic Warrior"

CFrameQuest = CFrame.new(5667.6582, 26.7997818, -6486.08984, -0.933587909, 0, -0.358349502, 0, 1, 0, 0.358349502, 0, -0.933587909)

CFrameMon = CFrame.new(5966.24609375, 62.97002029418945, -6179.3828125)

if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-6508.5581054688, 5000.034996032715, -132.83953857422))

end

elseif MyLevel == 1375 or MyLevel <= 1424 then

Mon = "Snow Lurker"

LevelQuest = 2

NameQuest = "FrostQuest"

NameMon = "Snow Lurker"

CFrameQuest = CFrame.new(5667.6582, 26.7997818, -6486.08984, -0.933587909, 0, -0.358349502, 0, 1, 0, 0.358349502, 0, -0.933587909)

CFrameMon = CFrame.new(5407.07373046875, 69.19437408447266, -6880.88037109375)

elseif MyLevel == 1425 or MyLevel <= 1449 then

Mon = "Sea Soldier"

LevelQuest = 1

NameQuest = "ForgottenQuest"

NameMon = "Sea Soldier"

CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)

CFrameMon = CFrame.new(-3028.2236328125, 64.67451477050781, -9775.4267578125)

elseif MyLevel >= 1450 then

Mon = "Water Fighter"

LevelQuest = 2

NameQuest = "ForgottenQuest"

NameMon = "Water Fighter"

CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)

CFrameMon = CFrame.new(-3352.9013671875, 285.01556396484375, -10534.841796875)

end

elseif World3 then

if MyLevel == 1500 or MyLevel <= 1524 then

Mon = "Pirate Millionaire"

LevelQuest = 1

NameQuest = "PiratePortQuest"

NameMon = "Pirate Millionaire"

CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)

CFrameMon = CFrame.new(-245.9963836669922, 47.30615234375, 5584.1005859375)

elseif MyLevel == 1525 or MyLevel <= 1574 then

Mon = "Pistol Billionaire"

LevelQuest = 2

NameQuest = "PiratePortQuest"

NameMon = "Pistol Billionaire"

CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)

CFrameMon = CFrame.new(-187.3301544189453, 86.23987579345703, 6013.513671875)

elseif MyLevel == 1575 or MyLevel <= 1599 then

Mon = "Dragon Crew Warrior"

LevelQuest = 1

NameQuest = "AmazonQuest"

NameMon = "Dragon Crew Warrior"

CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563, 0.898790359, -0, -0.438378751, 0, 1, -0, 0.438378751, 0, 0.898790359)

CFrameMon = CFrame.new(6141.140625, 51.35136413574219, -1340.738525390625)

elseif MyLevel == 1600 or MyLevel <= 1624 then

Mon = "Dragon Crew Archer"

NameQuest = "AmazonQuest"

LevelQuest = 2

NameMon = "Dragon Crew Archer"

CFrameQuest = CFrame.new(5833.1147460938, 51.60498046875, -1103.0693359375)

CFrameMon = CFrame.new(6616.41748046875, 441.7670593261719, 446.0469970703125)

elseif MyLevel == 1625 or MyLevel <= 1649 then

Mon = "Female Islander"

NameQuest = "AmazonQuest2"

LevelQuest = 1

NameMon = "Female Islander"

CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)

CFrameMon = CFrame.new(4685.25830078125, 735.8078002929688, 815.3425903320312)

elseif MyLevel == 1650 or MyLevel <= 1699 then

Mon = "Giant Islander"

NameQuest = "AmazonQuest2"

LevelQuest = 2

NameMon = "Giant Islander"

CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)

CFrameMon = CFrame.new(4729.09423828125, 590.436767578125, -36.97627639770508)

elseif MyLevel == 1700 or MyLevel <= 1724 then

Mon = "Marine Commodore"

LevelQuest = 1

NameQuest = "MarineTreeIsland"

NameMon = "Marine Commodore"

CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498, -0.965929747, 0, 0.258804798, 0, 1, 0, -0.258804798, 0, -0.965929747)

CFrameMon = CFrame.new(2286.0078125, 73.13391876220703, -7159.80908203125)

elseif MyLevel == 1725 or MyLevel <= 1774 then

Mon = "Marine Rear Admiral"

NameMon = "Marine Rear Admiral"

NameQuest = "MarineTreeIsland"

LevelQuest = 2

CFrameQuest = CFrame.new(2179.98828125, 28.731239318848, -6740.0551757813)

CFrameMon = CFrame.new(3656.773681640625, 160.52406311035156, -7001.5986328125)

elseif MyLevel == 1775 or MyLevel <= 1799 then

Mon = "Fishman Raider"

LevelQuest = 1

NameQuest = "DeepForestIsland3"

NameMon = "Fishman Raider"

CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)

CFrameMon = CFrame.new(-10407.5263671875, 331.76263427734375, -8368.5166015625)

elseif MyLevel == 1800 or MyLevel <= 1824 then

Mon = "Fishman Captain"

LevelQuest = 2

NameQuest = "DeepForestIsland3"

NameMon = "Fishman Captain"

CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)

CFrameMon = CFrame.new(-10994.701171875, 352.38140869140625, -9002.1103515625)

elseif MyLevel == 1825 or MyLevel <= 1849 then

Mon = "Forest Pirate"

LevelQuest = 1

NameQuest = "DeepForestIsland"

NameMon = "Forest Pirate"

CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)

CFrameMon = CFrame.new(-13274.478515625, 332.3781433105469, -7769.58056640625)

elseif MyLevel == 1850 or MyLevel <= 1899 then

Mon = "Mythological Pirate"

LevelQuest = 2

NameQuest = "DeepForestIsland"

NameMon = "Mythological Pirate"

CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)

CFrameMon = CFrame.new(-13680.607421875, 501.08154296875, -6991.189453125)

elseif MyLevel == 1900 or MyLevel <= 1924 then

Mon = "Jungle Pirate"

LevelQuest = 1

NameQuest = "DeepForestIsland2"

NameMon = "Jungle Pirate"

CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)

CFrameMon = CFrame.new(-12256.16015625, 331.73828125, -10485.8369140625)

elseif MyLevel == 1925 or MyLevel <= 1974 then

Mon = "Musketeer Pirate"

LevelQuest = 2

NameQuest = "DeepForestIsland2"

NameMon = "Musketeer Pirate"

CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)

CFrameMon = CFrame.new(-13457.904296875, 391.545654296875, -9859.177734375)

elseif MyLevel == 1975 or MyLevel <= 1999 then

Mon = "Reborn Skeleton"

LevelQuest = 1

NameQuest = "HauntedQuest1"

NameMon = "Reborn Skeleton"

CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)

CFrameMon = CFrame.new(-8763.7236328125, 165.72299194335938, 6159.86181640625)

elseif MyLevel == 2000 or MyLevel <= 2024 then

Mon = "Living Zombie"

LevelQuest = 2

NameQuest = "HauntedQuest1"

NameMon = "Living Zombie"

CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)

CFrameMon = CFrame.new(-10144.1318359375, 138.62667846679688, 5838.0888671875)

elseif MyLevel == 2025 or MyLevel <= 2049 then

Mon = "Demonic Soul"

LevelQuest = 1

NameQuest = "HauntedQuest2"

NameMon = "Demonic Soul"

CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-9505.8720703125, 172.10482788085938, 6158.9931640625)

elseif MyLevel == 2050 or MyLevel <= 2074 then

Mon = "Posessed Mummy"

LevelQuest = 2

NameQuest = "HauntedQuest2"

NameMon = "Posessed Mummy"

CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-9582.0224609375, 6.251527309417725, 6205.478515625)

elseif MyLevel == 2075 or MyLevel <= 2099 then

Mon = "Peanut Scout"

LevelQuest = 1

NameQuest = "NutsIslandQuest"

NameMon = "Peanut Scout"

CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-2143.241943359375, 47.72198486328125, -10029.9951171875)

elseif MyLevel == 2100 or MyLevel <= 2124 then

Mon = "Peanut President"

LevelQuest = 2

NameQuest = "NutsIslandQuest"

NameMon = "Peanut President"

CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-1859.35400390625, 38.10316848754883, -10422.4296875)

elseif MyLevel == 2125 or MyLevel <= 2149 then

Mon = "Ice Cream Chef"

LevelQuest = 1

NameQuest = "IceCreamIslandQuest"

NameMon = "Ice Cream Chef"

CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-872.24658203125, 65.81957244873047, -10919.95703125)

elseif MyLevel == 2150 or MyLevel <= 2199 then

Mon = "Ice Cream Commander"

LevelQuest = 2

NameQuest = "IceCreamIslandQuest"

NameMon = "Ice Cream Commander"

CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)

CFrameMon = CFrame.new(-558.06103515625, 112.04895782470703, -11290.7744140625)

elseif MyLevel == 2200 or MyLevel <= 2224 then

Mon = "Cookie Crafter"

LevelQuest = 1

NameQuest = "CakeQuest1"

NameMon = "Cookie Crafter"

CFrameQuest = CFrame.new(-2021.32007, 37.7982254, -12028.7295, 0.957576931, -8.80302053e-08, 0.288177818, 6.9301187e-08, 1, 7.51931211e-08, -0.288177818, -5.2032135e-08, 0.957576931)

CFrameMon = CFrame.new(-2374.13671875, 37.79826354980469, -12125.30859375)

elseif MyLevel == 2225 or MyLevel <= 2249 then

Mon = "Cake Guard"

LevelQuest = 2

NameQuest = "CakeQuest1"

NameMon = "Cake Guard"

CFrameQuest = CFrame.new(-2021.32007, 37.7982254, -12028.7295, 0.957576931, -8.80302053e-08, 0.288177818, 6.9301187e-08, 1, 7.51931211e-08, -0.288177818, -5.2032135e-08, 0.957576931)

CFrameMon = CFrame.new(-1598.3070068359375, 43.773197174072266, -12244.5810546875)

elseif MyLevel == 2250 or MyLevel <= 2274 then

Mon = "Baking Staff"

LevelQuest = 1

NameQuest = "CakeQuest2"

NameMon = "Baking Staff"

CFrameQuest = CFrame.new(-1927.91602, 37.7981339, -12842.5391, -0.96804446, 4.22142143e-08, 0.250778586, 4.74911062e-08, 1, 1.49904711e-08, -0.250778586, 2.64211941e-08, -0.96804446)

CFrameMon = CFrame.new(-1887.8099365234375, 77.6185073852539, -12998.3505859375)

elseif MyLevel == 2275 or MyLevel <= 2299 then

Mon = "Head Baker"

LevelQuest = 2

NameQuest = "CakeQuest2"

NameMon = "Head Baker"

CFrameQuest = CFrame.new(-1927.91602, 37.7981339, -12842.5391, -0.96804446, 4.22142143e-08, 0.250778586, 4.74911062e-08, 1, 1.49904711e-08, -0.250778586, 2.64211941e-08, -0.96804446)

CFrameMon = CFrame.new(-2216.188232421875, 82.884521484375, -12869.2939453125)

elseif MyLevel == 2300 or MyLevel <= 2324 then

Mon = "Cocoa Warrior"

LevelQuest = 1

NameQuest = "ChocQuest1"

NameMon = "Cocoa Warrior"

CFrameQuest = CFrame.new(233.22836303710938, 29.876001358032227, -12201.2333984375)

CFrameMon = CFrame.new(-21.55328369140625, 80.57499694824219, -12352.3876953125)

elseif MyLevel == 2325 or MyLevel <= 2349 then

Mon = "Chocolate Bar Battler"

LevelQuest = 2

NameQuest = "ChocQuest1"

NameMon = "Chocolate Bar Battler"

CFrameQuest = CFrame.new(233.22836303710938, 29.876001358032227, -12201.2333984375)

CFrameMon = CFrame.new(582.590576171875, 77.18809509277344, -12463.162109375)

elseif MyLevel == 2350 or MyLevel <= 2374 then

Mon = "Sweet Thief"

LevelQuest = 1

NameQuest = "ChocQuest2"

NameMon = "Sweet Thief"

CFrameQuest = CFrame.new(150.5066375732422, 30.693693161010742, -12774.5029296875)

CFrameMon = CFrame.new(165.1884765625, 76.05885314941406, -12600.8369140625)

elseif MyLevel == 2375 or MyLevel <= 2399 then

Mon = "Candy Rebel"

LevelQuest = 2

NameQuest = "ChocQuest2"

NameMon = "Candy Rebel"

CFrameQuest = CFrame.new(150.5066375732422, 30.693693161010742, -12774.5029296875)

CFrameMon = CFrame.new(134.86563110351562, 77.2476806640625, -12876.5478515625)

elseif MyLevel == 2400 or MyLevel <= 2424 then

Mon = "Candy Pirate"

LevelQuest = 1

NameQuest = "CandyQuest1"

NameMon = "Candy Pirate"

CFrameQuest = CFrame.new(-1150.0400390625, 20.378934860229492, -14446.3349609375)

CFrameMon = CFrame.new(-1310.5003662109375, 26.016523361206055, -14562.404296875)

elseif MyLevel == 2425 or MyLevel <= 2449 then

Mon = "Snow Demon"

LevelQuest = 2

NameQuest = "CandyQuest1"

NameMon = "Snow Demon"

CFrameQuest = CFrame.new(-1150.0400390625, 20.378934860229492, -14446.3349609375)

CFrameMon = CFrame.new(-880.2006225585938, 71.24776458740234, -14538.609375)

elseif MyLevel == 2450 or MyLevel <= 2474 then

Mon = "Isle Outlaw"

LevelQuest = 1

NameQuest = "TikiQuest1"

NameMon = "Isle Outlaw"

CFrameQuest = CFrame.new(-16545.9355, 55.6863556, -173.230499)

CFrameMon = CFrame.new(-16120.6035, 116.520554, -103.038849)

elseif MyLevel == 2475 or MyLevel <= 2499 then

Mon = "Island Boy"

LevelQuest = 2

NameQuest = "TikiQuest1"

NameMon = "Island Boy"

CFrameQuest = CFrame.new(-16545.9355, 55.6863556, -173.230499)

CFrameMon = CFrame.new(-16751.3125, 121.226219, -264.015015)

elseif MyLevel == 2500 or MyLevel <= 2524 then

Mon = "Sun-kissed Warrio"

LevelQuest = 1

NameQuest = "TikiQuest2"

NameMon = "Sun-kissed Warrio"

CFrameQuest = CFrame.new(-16539.078125, 55.68632888793945, 1051.5738525390625)

CFrameMon = CFrame.new(-16294.6748, 32.7874393, 1062.4856)

elseif MyLevel >= 2525 then

Mon = "Isle Champion"

LevelQuest = 2

NameQuest = "TikiQuest2"

NameMon = "Isle Champion"

CFrameQuest = CFrame.new(-16539.078125, 55.68632888793945, 1051.5738525390625)

CFrameMon = CFrame.new(-16933.2129, 93.3503036, 999.450989)

end

end

end

 

function Hop()

local PlaceID = game.PlaceId

local AllIDs = {}

local foundAnything = ""

local actualHour = os.date("!*t").hour

local Deleted = false

function TPReturner()

local Site;

if foundAnything == "" then

Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100'))

else

Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100&cursor=' .. foundAnything))

end

local ID = ""

if Site.nextPageCursor and Site.nextPageCursor ~= "null" and Site.nextPageCursor ~= nil then

foundAnything = Site.nextPageCursor

end

local num = 0;

for i,v in pairs(Site.data) do

local Possible = true

ID = tostring(v.id)

if tonumber(v.maxPlayers) > tonumber(v.playing) then

for _,Existing in pairs(AllIDs) do

if num ~= 0 then

if ID == tostring(Existing) then

Possible = false

end

else

if tonumber(actualHour) ~= tonumber(Existing) then

local delFile = pcall(function()

AllIDs = {}

table.insert(AllIDs, actualHour)

end)

end

end

num = num + 1

end

if Possible == true then

table.insert(AllIDs, ID)

wait()

pcall(function()

wait()

game:GetService("TeleportService"):TeleportToPlaceInstance(PlaceID, ID, game.Players.LocalPlayer)

end)

wait(4)

end

end

end

end

function Teleport()

while wait() do

pcall(function()

TPReturner()

if foundAnything ~= "" then

TPReturner()

end

end)

end

end

Teleport()

end

 

function UpdateIslandESP()

for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do

pcall(function()

if IslandESP then

if v.Name ~= "Sea" then

if not v:FindFirstChild('NameEsp') then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = "GothamBold"

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(7, 236, 240)

else

v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

end

else

if v:FindFirstChild('NameEsp') then

v:FindFirstChild('NameEsp'):Destroy()

end

end

end)

end

end

 

function isnil(thing)

return (thing == nil)

end

local function round(n)

return math.floor(tonumber(n) + 0.5)

end

Number = math.random(1, 1000000)

function UpdatePlayerChams()

for i,v in pairs(game:GetService'Players':GetChildren()) do

pcall(function()

if not isnil(v.Character) then

if ESPPlayer then

if not isnil(v.Character.Head) and not v.Character.Head:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Character.Head)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Character.Head

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance')

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

if v.Team == game.Players.LocalPlayer.Team then

name.TextColor3 = Color3.new(0,255,0)

else

name.TextColor3 = Color3.new(255,0,0)

end

else

v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..' | '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance\nHealth : ' .. round(v.Character.Humanoid.Health*100/v.Character.Humanoid.MaxHealth) .. '%')

end

else

if v.Character.Head:FindFirstChild('NameEsp'..Number) then

v.Character.Head:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end)

end

end

function UpdateChestChams()

for i,v in pairs(game.Workspace:GetChildren()) do

pcall(function()

if string.find(v.Name,"Chest") then

if ChestESP then

if string.find(v.Name,"Chest") then

if not v:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

if v.Name == "Chest1" then

name.TextColor3 = Color3.fromRGB(109, 109, 109)

name.Text = ("Chest 1" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

if v.Name == "Chest2" then

name.TextColor3 = Color3.fromRGB(173, 158, 21)

name.Text = ("Chest 2" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

if v.Name == "Chest3" then

name.TextColor3 = Color3.fromRGB(85, 255, 255)

name.Text = ("Chest 3" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

else

v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

end

else

if v:FindFirstChild('NameEsp'..Number) then

v:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end)

end

end

function UpdateDevilChams()

for i,v in pairs(game.Workspace:GetChildren()) do

pcall(function()

if DevilFruitESP then

if string.find(v.Name, "Fruit") then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 255, 255)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end)

end

end

function UpdateFlowerChams()

for i,v in pairs(game.Workspace:GetChildren()) do

pcall(function()

if v.Name == "Flower2" or v.Name == "Flower1" then

if FlowerESP then

if not v:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 0, 0)

if v.Name == "Flower1" then

name.Text = ("Blue Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

name.TextColor3 = Color3.fromRGB(0, 0, 255)

end

if v.Name == "Flower2" then

name.Text = ("Red Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

name.TextColor3 = Color3.fromRGB(255, 0, 0)

end

else

v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

else

if v:FindFirstChild('NameEsp'..Number) then

v:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end)

end

end

function UpdateRealFruitChams()

for i,v in pairs(game.Workspace.AppleSpawner:GetChildren()) do

if v:IsA("Tool") then

if RealFruitESP then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 0, 0)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end

for i,v in pairs(game.Workspace.PineappleSpawner:GetChildren()) do

if v:IsA("Tool") then

if RealFruitESP then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 174, 0)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end

for i,v in pairs(game.Workspace.BananaSpawner:GetChildren()) do

if v:IsA("Tool") then

if RealFruitESP then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(251, 255, 0)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end

end

 

function UpdateIslandESP()

for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do

pcall(function()

if IslandESP then

if v.Name ~= "Sea" then

if not v:FindFirstChild('NameEsp') then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = "GothamBold"

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(7, 236, 240)

else

v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

end

else

if v:FindFirstChild('NameEsp') then

v:FindFirstChild('NameEsp'):Destroy()

end

end

end)

end

end

 

function isnil(thing)

return (thing == nil)

end

local function round(n)

return math.floor(tonumber(n) + 0.5)

end

Number = math.random(1, 1000000)

function UpdatePlayerChams()

for i,v in pairs(game:GetService'Players':GetChildren()) do

pcall(function()

if not isnil(v.Character) then

if ESPPlayer then

if not isnil(v.Character.Head) and not v.Character.Head:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Character.Head)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Character.Head

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance')

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

if v.Team == game.Players.LocalPlayer.Team then

name.TextColor3 = Color3.new(0,255,0)

else

name.TextColor3 = Color3.new(255,0,0)

end

else

v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..' | '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance\nHealth : ' .. round(v.Character.Humanoid.Health*100/v.Character.Humanoid.MaxHealth) .. '%')

end

else

if v.Character.Head:FindFirstChild('NameEsp'..Number) then

v.Character.Head:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end)

end

end

function UpdateChestChams()

for i,v in pairs(game.Workspace:GetChildren()) do

pcall(function()

if string.find(v.Name,"Chest") then

if ChestESP then

if string.find(v.Name,"Chest") then

if not v:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

if v.Name == "Chest1" then

name.TextColor3 = Color3.fromRGB(109, 109, 109)

name.Text = ("Chest 1" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

if v.Name == "Chest2" then

name.TextColor3 = Color3.fromRGB(173, 158, 21)

name.Text = ("Chest 2" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

if v.Name == "Chest3" then

name.TextColor3 = Color3.fromRGB(85, 255, 255)

name.Text = ("Chest 3" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

else

v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

end

else

if v:FindFirstChild('NameEsp'..Number) then

v:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end)

end

end

function UpdateDevilChams()

for i,v in pairs(game.Workspace:GetChildren()) do

pcall(function()

if DevilFruitESP then

if string.find(v.Name, "Fruit") then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 255, 255)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end)

end

end

function UpdateFlowerChams()

for i,v in pairs(game.Workspace:GetChildren()) do

pcall(function()

if v.Name == "Flower2" or v.Name == "Flower1" then

if FlowerESP then

if not v:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 0, 0)

if v.Name == "Flower1" then

name.Text = ("Blue Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

name.TextColor3 = Color3.fromRGB(0, 0, 255)

end

if v.Name == "Flower2" then

name.Text = ("Red Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

name.TextColor3 = Color3.fromRGB(255, 0, 0)

end

else

v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

else

if v:FindFirstChild('NameEsp'..Number) then

v:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end)

end

end

function UpdateRealFruitChams()

for i,v in pairs(game.Workspace.AppleSpawner:GetChildren()) do

if v:IsA("Tool") then

if RealFruitESP then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 0, 0)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end

for i,v in pairs(game.Workspace.PineappleSpawner:GetChildren()) do

if v:IsA("Tool") then

if RealFruitESP then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 174, 0)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end

for i,v in pairs(game.Workspace.BananaSpawner:GetChildren()) do

if v:IsA("Tool") then

if RealFruitESP then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(251, 255, 0)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..' '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end

end

 

spawn(function()

while wait() do

pcall(function()

if MobESP then

for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do

if v:FindFirstChild('HumanoidRootPart') then

if not v:FindFirstChild("MobEap") then

local BillboardGui = Instance.new("BillboardGui")

local TextLabel = Instance.new("TextLabel")

 

BillboardGui.Parent = v

BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

BillboardGui.Active = true

BillboardGui.Name = "MobEap"

BillboardGui.AlwaysOnTop = true

BillboardGui.LightInfluence = 1.000

BillboardGui.Size = UDim2.new(0, 200, 0, 50)

BillboardGui.StudsOffset = Vector3.new(0, 2.5, 0)

 

TextLabel.Parent = BillboardGui

TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

TextLabel.BackgroundTransparency = 1.000

TextLabel.Size = UDim2.new(0, 200, 0, 50)

TextLabel.Font = Enum.Font.GothamBold

TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)

TextLabel.Text.Size = 35

end

local Dis = math.floor((game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).Magnitude)

v.MobEap.TextLabel.Text = v.Name.." - "..Dis.." Distance"

end

end

else

for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do

if v:FindFirstChild("MobEap") then

v.MobEap:Destroy()

end

end

end

end)

end

end)

 

spawn(function()

while wait() do

pcall(function()

if SeaESP then

for i,v in pairs(game:GetService("Workspace").SeaBeasts:GetChildren()) do

if v:FindFirstChild('HumanoidRootPart') then

if not v:FindFirstChild("Seaesps") then

local BillboardGui = Instance.new("BillboardGui")

local TextLabel = Instance.new("TextLabel")

 

BillboardGui.Parent = v

BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

BillboardGui.Active = true

BillboardGui.Name = "Seaesps"

BillboardGui.AlwaysOnTop = true

BillboardGui.LightInfluence = 1.000

BillboardGui.Size = UDim2.new(0, 200, 0, 50)

BillboardGui.StudsOffset = Vector3.new(0, 2.5, 0)

 

TextLabel.Parent = BillboardGui

TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

TextLabel.BackgroundTransparency = 1.000

TextLabel.Size = UDim2.new(0, 200, 0, 50)

TextLabel.Font = Enum.Font.GothamBold

TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)

TextLabel.Text.Size = 35

end

local Dis = math.floor((game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).Magnitude)

v.Seaesps.TextLabel.Text = v.Name.." - "..Dis.." Distance"

end

end

else

for i,v in pairs (game:GetService("Workspace").SeaBeasts:GetChildren()) do

if v:FindFirstChild("Seaesps") then

v.Seaesps:Destroy()

end

end

end

end)

end

end)

 

spawn(function()

while wait() do

pcall(function()

if NpcESP then

for i,v in pairs(game:GetService("Workspace").NPCs:GetChildren()) do

if v:FindFirstChild('HumanoidRootPart') then

if not v:FindFirstChild("NpcEspes") then

local BillboardGui = Instance.new("BillboardGui")

local TextLabel = Instance.new("TextLabel")

 

BillboardGui.Parent = v

BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

BillboardGui.Active = true

BillboardGui.Name = "NpcEspes"

BillboardGui.AlwaysOnTop = true

BillboardGui.LightInfluence = 1.000

BillboardGui.Size = UDim2.new(0, 200, 0, 50)

BillboardGui.StudsOffset = Vector3.new(0, 2.5, 0)

 

TextLabel.Parent = BillboardGui

TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

TextLabel.BackgroundTransparency = 1.000

TextLabel.Size = UDim2.new(0, 200, 0, 50)

TextLabel.Font = Enum.Font.GothamBold

TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)

TextLabel.Text.Size = 35

end

local Dis = math.floor((game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).Magnitude)

v.NpcEspes.TextLabel.Text = v.Name.." - "..Dis.." Distance"

end

end

else

for i,v in pairs (game:GetService("Workspace").NPCs:GetChildren()) do

if v:FindFirstChild("NpcEspes") then

v.NpcEspes:Destroy()

end

end

end

end)

end

end)

 

function isnil(thing)

return (thing == nil)

end

local function round(n)

return math.floor(tonumber(n) + 0.5)

end

Number = math.random(1, 1000000)

 

function UpdateIslandMirageESP()

for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do

pcall(function()

if MirageIslandESP then

if v.Name == "Mirage Island" then

if not v:FindFirstChild('NameEsp') then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = "Code"

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(80, 245, 245)

else

v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')

end

end

else

if v:FindFirstChild('NameEsp') then

v:FindFirstChild('NameEsp'):Destroy()

end

end

end)

end

end

 

function isnil(thing)

return (thing == nil)

end

local function round(n)

return math.floor(tonumber(n) + 0.5)

end

Number = math.random(1, 1000000)

 

function UpdateAfdESP()

for i,v in pairs(game:GetService("Workspace").NPCs:GetChildren()) do

pcall(function()

if AfdESP then

if v.Name == "Advanced Fruit Dealer" then

if not v:FindFirstChild('NameEsp') then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = "Code"

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(80, 245, 245)

else

v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')

end

end

else

if v:FindFirstChild('NameEsp') then

v:FindFirstChild('NameEsp'):Destroy()

end

end

end)

end

end

 

 

 

function InfAb()

if InfAbility then

if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility") then

local inf = Instance.new("ParticleEmitter")

inf.Acceleration = Vector3.new(0,0,0)

inf.Archivable = true

inf.Drag = 20

inf.EmissionDirection = Enum.NormalId.Top

inf.Enabled = true

inf.Lifetime = NumberRange.new(0,0)

inf.LightInfluence = 0

inf.LockedToPart = true

inf.Name = "Agility"

inf.Rate = 500

local numberKeypoints2 = {

NumberSequenceKeypoint.new(0, 0);

NumberSequenceKeypoint.new(1, 4);

}

inf.Size = NumberSequence.new(numberKeypoints2)

inf.RotSpeed = NumberRange.new(9999, 99999)

inf.Rotation = NumberRange.new(0, 0)

inf.Speed = NumberRange.new(30, 30)

inf.SpreadAngle = Vector2.new(0,0,0,0)

inf.Texture = ""

inf.VelocityInheritance = 0

inf.ZOffset = 2

inf.Transparency = NumberSequence.new(0)

inf.Color = ColorSequence.new(Color3.fromRGB(0,0,0),Color3.fromRGB(0,0,0))

inf.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart

end

else

if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility") then

game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility"):Destroy()

end

end

end

 

local LocalPlayer = game:GetService'Players'.LocalPlayer

local originalstam = LocalPlayer.Character.Energy.Value

function infinitestam()

LocalPlayer.Character.Energy.Changed:connect(function()

if InfiniteEnergy then

LocalPlayer.Character.Energy.Value = originalstam

end

end)

end

 

spawn(function()

pcall(function()

while wait(.1) do

if InfiniteEnergy then

wait(0.1)

originalstam = LocalPlayer.Character.Energy.Value

infinitestam()

end

end

end)

end)

 

function NoDodgeCool()

if nododgecool then

for i,v in next, getgc() do

if game:GetService("Players").LocalPlayer.Character.Dodge then

if typeof(v) == "function" and getfenv(v).script == game:GetService("Players").LocalPlayer.Character.Dodge then

for i2,v2 in next, getupvalues(v) do

if tostring(v2) == "0.1" then

repeat wait(.1)

setupvalue(v,i2,0)

until not nododgecool

end

end

end

end

end

end

end

 

function fly()

local mouse=game:GetService("Players").LocalPlayer:GetMouse''

localplayer=game:GetService("Players").LocalPlayer

game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart")

local torso = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart

local speedSET=25

local keys={a=false,d=false,w=false,s=false}

local e1

local e2

local function start()

local pos = Instance.new("BodyPosition",torso)

local gyro = Instance.new("BodyGyro",torso)

pos.Name="EPIXPOS"

pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)

pos.position = torso.Position

gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)

gyro.CFrame = torso.CFrame

repeat

wait()

localplayer.Character.Humanoid.PlatformStand=true

local new=gyro.CFrame - gyro.CFrame.p + pos.position

if not keys.w and not keys.s and not keys.a and not keys.d then

speed=1

end

if keys.w then

new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed

speed=speed+speedSET

end

if keys.s then

new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed

speed=speed+speedSET

end

if keys.d then

new = new * CFrame.new(speed,0,0)

speed=speed+speedSET

end

if keys.a then

new = new * CFrame.new(-speed,0,0)

speed=speed+speedSET

end

if speed>speedSET then

speed=speedSET

end

pos.position=new.p

if keys.w then

gyro.CFrame = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*15),0,0)

elseif keys.s then

gyro.CFrame = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*15),0,0)

else

gyro.CFrame = workspace.CurrentCamera.CoordinateFrame

end

until not Fly

if gyro then

gyro:Destroy()

end

if pos then

pos:Destroy()

end

flying=false

localplayer.Character.Humanoid.PlatformStand=false

speed=0

end

e1=mouse.KeyDown:connect(function(key)

if not torso or not torso.Parent then

flying=false e1:disconnect() e2:disconnect() return

end

if key=="w" then

keys.w=true

elseif key=="s" then

keys.s=true

elseif key=="a" then

keys.a=true

elseif key=="d" then

keys.d=true

end

end)

e2=mouse.KeyUp:connect(function(key)

if key=="w" then

keys.w=false

elseif key=="s" then

keys.s=false

elseif key=="a" then

keys.a=false

elseif key=="d" then

keys.d=false

end

end)

start()

end

 

function Click()

wait(.1)

game:GetService'VirtualUser':CaptureController()

game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))

end

 

function AutoHaki()

if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("HasBuso") then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")

end

end

 

function UnEquipWeapon(Weapon)

if game.Players.LocalPlayer.Character:FindFirstChild(Weapon) then

_G.NotAutoEquip = true

wait(.5)

game.Players.LocalPlayer.Character:FindFirstChild(Weapon).Parent = game.Players.LocalPlayer.Backpack

wait(.1)

_G.NotAutoEquip = false

end

end

 

function EquipWeapon(ToolSe)

if not _G.NotAutoEquip then

if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then

Tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)

wait(.1)

game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tool)

end

end

end

 

spawn(function()

while wait() do

for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"]:GetChildren()) do

pcall(function()

if v.Name == ("CurvedRing") or v.Name == ("SlashHit") or v.Name == ("SwordSlash") or v.Name == ("SlashTail") or v.Name == ("Sounds") then

v:Destroy()

end

end)

end

end

end)

 

function Check_Sword(Sword_Name)

for i, v in pairs(game:GetService("ReplicatedStorage").Remotes['CommF_']:InvokeServer("getInventory")) do

if (v.Type == "Sword") then

if v.Name == Sword_Name then

return true

end

end

end

end

 

function GetDistance(target)

return math.floor((target.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude)

end

 

function BTP(P)

 repeat wait(1)

  game.Players.LocalPlayer.Character.Humanoid:ChangeState(15)

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P

  task.wait()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P

 until (P.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1500

end

 

function TelePPlayer(P)

 game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P

end

 

function TP(Pos)

Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude

if Distance < 25 then

Speed = 10000

elseif Distance < 50 then

Speed = 2000

elseif Distance < 150 then

Speed = 800

elseif Distance < 250 then

Speed = 600

elseif Distance < 500 then

Speed = 400

elseif Distance < 750 then

Speed = 250

elseif Distance >= 1000 then

Speed = 200

end

game:GetService("TweenService"):Create(

game.Players.LocalPlayer.Character.HumanoidRootPart,

TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),

{CFrame = Pos}

):Play()

end

 

function TP1(Pos)

Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude

if Distance < 25 then

Speed = 5000

elseif Distance < 50 then

Speed = 2000

elseif Distance < 150 then

Speed = 800

elseif Distance < 250 then

Speed = 600

elseif Distance < 500 then

Speed = 300

elseif Distance < 750 then

Speed = 250

elseif Distance >= 1000 then

Speed = 200

end

game:GetService("TweenService"):Create(

game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,

TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),

{CFrame = Pos}

):Play()

end

 

function topos(Pos)

Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude

if Distance < 25 then

Speed = 5000

elseif Distance < 50 then

Speed = 2000

elseif Distance < 150 then

Speed = 800

elseif Distance < 250 then

Speed = 600

elseif Distance < 500 then

Speed = 300

elseif Distance < 750 then

Speed = 250

elseif Distance >= 1000 then

Speed = 200

end

game:GetService("TweenService"):Create(

game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,

TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),

{CFrame = Pos}

):Play()

end

 

function TPB(CFgo)

 local tween_s = game:service"TweenService"

 local info = TweenInfo.new((game:GetService("Workspace").Boats.MarineBrigade.VehicleSeat.CFrame.Position - CFgo.Position).Magnitude/300, Enum.EasingStyle.Linear)

 tween = tween_s:Create(game:GetService("Workspace").Boats.MarineBrigade.VehicleSeat, info, {CFrame = CFgo})

 tween:Play()

 

 local tweenfunc = {}

 

 function tweenfunc:Stop()

  tween:Cancel()

 end

 

 return tweenfunc

end

 

function TPP(CFgo)

 if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health <= 0 or not game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") then tween:Cancel() repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") and game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 wait(7) return end

 local tween_s = game:service"TweenService"

 local info = TweenInfo.new((game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - CFgo.Position).Magnitude/325, Enum.EasingStyle.Linear)

 tween = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = CFgo})

 tween:Play()

 

 local tweenfunc = {}

 

 function tweenfunc:Stop()

  tween:Cancel()

 end

 

 return tweenfunc

end

 

getgenv().ToTargets = function(p)

task.spawn(function()

pcall(function()

if game:GetService("Players").LocalPlayer:DistanceFromCharacter(p.Position) <= 250 then

game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = p

elseif not game.Players.LocalPlayer.Character:FindFirstChild("Root")then

local K = Instance.new("Part",game.Players.LocalPlayer.Character)

K.Size = Vector3.new(1,0.5,1)

K.Name = "Root"

K.Anchored = true

K.Transparency = 1

K.CanCollide = false

K.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,20,0)

end

local U = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude

local z = game:service("TweenService")

local B = TweenInfo.new((p.Position-game.Players.LocalPlayer.Character.Root.Position).Magnitude/300,Enum.EasingStyle.Linear)

local S,g = pcall(function()

local q = z:Create(game.Players.LocalPlayer.Character.Root,B,{CFrame = p})

q:Play()

end)

if not S then

return g

end

game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame

if S and game.Players.LocalPlayer.Character:FindFirstChild("Root") then

pcall(function()

if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 20 then

spawn(function()

pcall(function()

if (game.Players.LocalPlayer.Character.Root.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 150 then

game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame

else

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=game.Players.LocalPlayer.Character.Root.CFrame

end

end)

end)

elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 10 and(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 20 then

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p

elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 10 then

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p

end

end)

end

end)

end)

end

 

Type = 1

spawn(function()

while wait(.1) do

if Type == 1 then

Pos = CFrame.new(0,PosY,0)

elseif Type == 2 then

Pos = CFrame.new(0,PosY,-30)

elseif Type == 3 then

Pos = CFrame.new(30,PosY,0)

elseif Type == 4 then

Pos = CFrame.new(0,PosY,30) 

elseif Type == 5 then

Pos = CFrame.new(-30,PosY,0)

elseif Type == 6 then

Pos = CFrame.new(0,35,0)

end

end

end)

 

spawn(function()

while wait(.1) do

Type = 1

wait(0.5)

Type = 2

wait(0.5)

Type = 3

wait(0.5)

Type = 4

wait(0.5)

Type = 5

wait(0.5)

end

end)

 

task.spawn(function()

while task.wait() do

pcall(function()

if _G.AutoFarmNearest and AutoFarmNearestMagnet or SelectMag and _G.BringMonster then

for i,v in pairs(game.Workspace.Enemies:GetChildren()) do

if not string.find(v.Name,"Boss") and (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= _G.BringMode then

if InMyNetWork(v.HumanoidRootPart) then

v.HumanoidRootPart.CFrame = PosMon

v.Humanoid.JumpPower = 0

v.Humanoid.WalkSpeed = 0

v.HumanoidRootPart.Size = Vector3.new(60,60,60)

v.HumanoidRootPart.Transparency = 1

v.HumanoidRootPart.CanCollide = false

v.Head.CanCollide = false

if v.Humanoid:FindFirstChild("Animator") then

v.Humanoid.Animator:Destroy()

end

v.Humanoid:ChangeState(11)

v.Humanoid:ChangeState(14)

end

end

end

end

end)

end

end)

 

spawn(function()

game:GetService("RunService").Heartbeat:Connect(function()

if _G.AutoVampire or AutoFarmChest or _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFactory or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.Autoheart or _G.Autodoughking or _G.AutoFarmMaterial or _G.AutoNevaSoulGuitar or _G.Auto_Dragon_Trident or _G.Autotushita or _G.d or _G.Autowaden or _G.Autogay or _G.Autopole or _G.Autosaw or _G.AutoObservationHakiV2 or _G.AutoFarmNearest or AutoFarmChest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Tweenfruit or _G.AutoKai or _G.TeleportNPC or _G.Leather or _G.Auto_Wing or _G.Umm or _G.Makori_gay or Radioactive or Fish or Gunpowder or Dragon_Scale or Cocoafarm or Scrap or MiniHee or _G.AutoFarmSeabaest or Auto_Cursed_Dual_Katana or _G.AutoFarmMob or _G.AutoMysticIsland or _G.AutoFarmDungeon or _G.AutoRaidPirate or _G.AutoQuestRace or _G.TweenMGear or getgenv().AutoFarm or _G.AutoPlayerHunter or _G.AutoFactory or Grab_Chest or _G.Namfon or _G.AutoSwordMastery or _G.AutoSeaBest or _G.AutoKillTial or _G.Auto_Saber or _G.Position_Spawn or _G.Farmfast or _G.AutoRace or _G.RaidPirate then

if not game:GetService("Workspace"):FindFirstChild("LOL") then

local LOL = Instance.new("Part")

LOL.Name = "LOL"

LOL.Parent = game.Workspace

LOL.Anchored = true

LOL.Transparency = 1

LOL.Size = Vector3.new(30,-0.5,30)

elseif game:GetService("Workspace"):FindFirstChild("LOL") then

game.Workspace["LOL"].CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0, -3.6, 0)

end

else

if game:GetService("Workspace"):FindFirstChild("LOL") then

game:GetService("Workspace"):FindFirstChild("LOL"):Destroy()

end

end

end)

end)

 

spawn(function()

pcall(function()

while wait() do

if _G.AutoVampire or AutoFarmChest or _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFactory or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.AutoFarm or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.Autoheart or _G.Autodoughking or _G.AutoFarmMaterial or _G.AutoNevaSoulGuitar or _G.Auto_Dragon_Trident or _G.Autotushita or _G.d or _G.Autowaden or _G.Autogay or _G.Autopole or _G.Autosaw or _G.AutoObservationHakiV2 or _G.AutoFarmNearest or AutoFarmChest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Tweenfruit or _G.TeleportNPC or _G.Leather or _G.Auto_Wing or _G.Umm or _G.Makori_gay or Radioactive or Fish or Gunpowder or Dragon_Scale or Cocoafarm or Scrap or MiniHee or _G.AutoFarmSeabaest or Auto_Cursed_Dual_Katana or _G.AutoFarmMob or _G.AutoMysticIsland or _G.AutoFarmDungeon or _G.AutoRaidPirate or _G.AutoQuestRace or _G.TweenMGear or getgenv().AutoFarm or _G.AutoPlayerHunter or _G.AutoFactory or Grab_Chest or _G.Namfon or _G.AutoSwordMastery or _G.Auto_Seabest or _G.AutoSeaBest or _G.AutoKillTial or _G.Auto_Saber or _G.Position_Spawn or _G.Farmfast or _G.AutoRace or _G.RaidPirate == true then

if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then

local Noclip = Instance.new("BodyVelocity")

Noclip.Name = "BodyClip"

Noclip.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart

Noclip.MaxForce = Vector3.new(100000,100000,100000)

Noclip.Velocity = Vector3.new(0,0,0)

end

end

end

end)

end)

 

spawn(function()

pcall(function()

game:GetService("RunService").Stepped:Connect(function()

if _G.AutoVampire or AutoFarmChest or _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFactory or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.Autoheart or _G.Autodoughking or _G.AutoFarmMaterial or _G.AutoNevaSoulGuitar or _G.Auto_Dragon_Trident or _G.Autotushita or _G.Autowaden or _G.Autogay or _G.Autopole or _G.Autosaw or _G.AutoObservationHakiV2 or _G.AutoFarmNearest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Tweenfruit or _G.TeleportNPC or _G.AutoKai or _G.Leather or _G.Auto_Wing or _G.Umm or _G.Makori_gay or Radioactive or Fish or Gunpowder or Dragon_Scale or Cocoafarm or Scrap or MiniHee or _G.AutoFarmSeabaest or Auto_Cursed_Dual_Katana or _G.AutoFarmMob or _G.AutoMysticIsland or _G.AutoFarmDungeon or _G.AutoRaidPirate or _G.AutoQuestRace or _G.TweenMGear or getgenv().AutoFarm or _G.AutoPlayerHunter or _G.AutoFactory or _G.Namfon or _G.AutoSwordMastery or _G.Auto_Seabest or _G.AutoSeaBest or _G.AutoKillTial or _G.Auto_Saber or _G.Position_Spawn or _G.TPB or _G.Farmfast or _G.AutoRace or _G.RaidPirate == true then

for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do

if v:IsA("BasePart") then

v.CanCollide = false

end

end

end

end)

end)

end)

 

function InstancePos(pos)

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos

end

 

function TP3(pos)

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos

end

 

spawn(function()

while wait() do

if _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFactory or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.Autoheart or _G.Autodoughking or _G.d or _G.Autowaden or _G.Autogay or _G.AutoObservationHakiV2 or _G.AutoFarmMaterial or _G.AutoFarmNearest or _G.AutoCarvender or _G.AutoTwinHook or AutoMobAura or _G.Leather or _G.Auto_Wing or _G.Umm or _G.Makori_gay or Radioactive or Fish or Gunpowder or Dragon_Scale or Cocoafarm or Scrap or MiniHee or _G.AutoFarmSeabaest or Auto_Cursed_Dual_Katana or _G.AutoFarmMob or _G.AutoRaidPirate or getgenv().AutoFarm or _G.AutoPlayerHunter or _G.AutoFactory or _G.AttackDummy or _G.AutoSwordMastery or _G.Auto_Seabest or _G.AutoSeaBest or _G.AutoKillTial or _G.Auto_Saber or _G.Farmfast or _G.RaidPirate == true then

pcall(function()

game:GetService("ReplicatedStorage").Remotes.CommE:FireServer("Ken",true)

end)

end

end

end)

 

spawn(function()

game:GetService("RunService").RenderStepped:Connect(function()

if _G.AutoClick or Fastattack then

pcall(function()

game:GetService'VirtualUser':CaptureController()

game:GetService'VirtualUser':Button1Down(Vector2.new(0,1,0,1))

end)

end

end)

end)

 

function StopTween(target)

if not target then

_G.StopTween = true

wait()

topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)

wait()

if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then

game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()

end

_G.StopTween = false

_G.Clip = false

end

end

 

spawn(function()

pcall(function()

while wait() do

for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do

if v:IsA("Tool") then

if v:FindFirstChild("RemoteFunctionShoot") then

SelectWeaponGun = v.Name

end

end

end

end

end)

end)

 

game:GetService("Players").LocalPlayer.Idled:connect(function()

game:GetService("VirtualUser"):Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

wait(1)

game:GetService("VirtualUser"):Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

end)

 

function CheckItem(ah)

for k, v in pairs(game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("getInventory")) do

if v.Name == ah then

return v

end

end

end

 

function CheckSea(e)

if game.PlaceId == 2753915549 then

if e == 1 then

return true

end

elseif game.PlaceId == 4442272183 then

if e == 2 then

return true

end

elseif game.PlaceId == 7449423635 then

if e == 3 then

return true

end

end

return false

end

w = task.wait

t = task

 

TempleOfTimeCFrame =

CFrame.new(

28734.3945,

14888.2324,

-   109.071777,

-   0.650207579,

4.1780531e-08,

-   0.759756625,

97876595e-08,
1,

3.80575109e-08,

0.759756625,

9.71147784e-09,

-   0.650207579

)

 

spawn(

function()

while task.wait() do

if _G.AutoDooHee then

MoveCamtoMoon()

end

end

end

)

Memayto = false

DaGatCan = false

if game.ReplicatedStorage.Remotes.CommF_:InvokeServer("CheckTempleDoor") then

DaGatCan = true

end

function PullLever()

local bn =

CFrame.new(

28576.4688,

14939.2832,

76.5164413,

-   1,

0,

0,

0,

0.707134247,

-   0.707079291,

-   0,

-   0.707079291,

-   0.707134247

)

local bo =

CFrame.new(

28576.4688,

14935.9512,

75.469101,

-   1,

-   4.22219593e-08,

13133396e-08,
0,

-   0.258819044,

-   0.965925813,

4.37113883e-08,

-   0.965925813,

0.258819044

)

local bp = 0.2

if

game:GetService("Workspace").Map["Temple of Time"].Lever.Lever.CFrame.Z > bo.Z + bp or

game:GetService("Workspace").Map["Temple of Time"].Lever.Lever.CFrame.Z < bo.Z - bp

then

CheckAndTweenTemple()

topos(game:GetService("Workspace").Map["Temple of Time"].Lever.Part.CFrame)

for r, v in pairs(game:GetService("Workspace").Map["Temple of Time"].Lever:GetDescendants()) do

if v.Name == "ProximityPrompt" then

fireproximityprompt(v)

end

end

end

end

 function IsMirageIsland2()

  if game:GetService("Workspace").Map:FindFirstChild("MysticIsland") then

   return true

  else

   return false

  end

 end

 function TweenTemple()

  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(

   "requestEntrance",

   Vector3.new(28282.5703125, 14896.8505859375, 105.1042709350586)

  )

 end

function TweenTempleLegit()

  AllNPCS = getnilinstances()

  for r, v in pairs(game:GetService("Workspace").NPCs:GetChildren()) do

   table.insert(AllNPCS, v)

  end

  for r, v in pairs(AllNPCS) do

   if v.Name == "Mysterious Force" then

    TempleMysteriousNPC1 = v

   end

   if v.Name == "Mysterious Force3" then

    TempleMysteriousNPC2 = v

   end

  end

  topos(TempleMysteriousNPC2.HumanoidRootPart.CFrame)

  wait(0.5)

  if

   (TempleMysteriousNPC2.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <

    15

   then

   game.ReplicatedStorage.Remotes.CommF_:InvokeServer("RaceV4Progress", "TeleportBack")

  end

  if

   (TempleMysteriousNPC1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <

    15

   then

   game.ReplicatedStorage.Remotes.CommF_:InvokeServer("RaceV4Progress", "Teleport")

end

 end

 function CheckAndTweenTemple()

  if (TempleOfTimeCFrame.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1200 then

   TweenTemple()

  end

  if (TempleOfTimeCFrame.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1200 then

   TweenTemple()

  end

 end

function MoonTextureId()

if Sea1 then

return game:GetService("Lighting").FantasySky.MoonTextureId

elseif Sea2 then

return game:GetService("Lighting").FantasySky.MoonTextureId

elseif Sea3 then

return game:GetService("Lighting").Sky.MoonTextureId

end

end

 function CheckMoon()

  moon8 = "http://www.roblox.com/asset/?id=9709150401"

  moon7 = "http://www.roblox.com/asset/?id=9709150086"

  moon6 = "http://www.roblox.com/asset/?id=9709149680"

  moon5 = "http://www.roblox.com/asset/?id=9709149431"

  moon4 = "http://www.roblox.com/asset/?id=9709149052"

  moon3 = "http://www.roblox.com/asset/?id=9709143733"

  moon2 = "http://www.roblox.com/asset/?id=9709139597"

  moon1 = "http://www.roblox.com/asset/?id=9709135895"

  moonreal = MoonTextureId()

  cofullmoonkothangbeo = "Bad Moon"

  if moonreal == moon5 or moonreal == moon4 then

   if moonreal == moon5 then

    cofullmoonkothangbeo = "Full Moon"

   elseif moonreal == moon4 then

    cofullmoonkothangbeo = "Next Night"

   end

  end

  return cofullmoonkothangbeo

 end

 function getBlueGear()

  if game.workspace.Map:FindFirstChild("MysticIsland") then

   for r, v in pairs(game.workspace.Map.MysticIsland:GetChildren()) do

    if v:IsA("MeshPart") and v.MeshId == "rbxassetid://10153114969" then

     return v

    end

   end

  end

 end

 function getHighestPoint()

  if not game.workspace.Map:FindFirstChild("MysticIsland") then

   return nil

  end

  for r, v in pairs(game:GetService("Workspace").Map.MysticIsland:GetDescendants()) do

   if v:IsA("MeshPart") then

    if v.MeshId == "rbxassetid://6745037796" then

     return v

    end

   end

  end

 end

 spawn(function()

if TwenetoHighestPoint then

  HighestPoint = getHighestPoint()

  if HighestPoint then

   topos(HighestPoint.CFrame * CFrame.new(0, 211.88, 0))

  end

end

 end)

 function MoveCamtoMoon()

  workspace.CurrentCamera.CFrame =

   CFrame.new(

   workspace.CurrentCamera.CFrame.Position,

   game:GetService("Lighting"):GetMoonDirection() + workspace.CurrentCamera.CFrame.Position

  )

 end

 

 spawn(function()

if TweentoBlueGear then

  BlueGear = getBlueGear()

  if BlueGear then

   topos(BlueGear.CFrame)

  end

end

 end)

 

local Client = game.Players.LocalPlayer

local STOP = require(Client.PlayerScripts.CombatFramework.Particle)

local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)

spawn(function()

while task.wait() do

pcall(function()

if not shared.orl then shared.orl = STOPRL.wrapAttackAnimationAsync end

if not shared.cpc then shared.cpc = STOP.play end

STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)

local Hits = STOPRL.getBladeHits(b,c,d)

if Hits then

if _G.FastAttack then

STOP.play = function() end

a:Play(0.01,0.01,0.01)

func(Hits)

STOP.play = shared.cpc

wait(a.length * 0.5)

a:Stop()

else

a:Play()

end

end

end

end)

end

end)

 

function GetBladeHit()

local CombatFrameworkLib = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework))

local CmrFwLib = CombatFrameworkLib[2]

local p13 = CmrFwLib.activeController

local weapon = p13.blades[1]

if not weapon then

return weapon

end

while weapon.Parent ~= game.Players.LocalPlayer.Character do

weapon = weapon.Parent

end

return weapon

end

function AttackHit()

local CombatFrameworkLib = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework))

local CmrFwLib = CombatFrameworkLib[2]

local plr = game.Players.LocalPlayer

for i = 1, 1 do

local bladehit = require(game.ReplicatedStorage.CombatFramework.RigLib).getBladeHits(plr.Character,{plr.Character.HumanoidRootPart},60)

local cac = {}

local hash = {}

for k, v in pairs(bladehit) do

if v.Parent:FindFirstChild("HumanoidRootPart") and not hash[v.Parent] then

table.insert(cac, v.Parent.HumanoidRootPart)

hash[v.Parent] = true

end

end

bladehit = cac

if #bladehit > 0 then

pcall(function()

CmrFwLib.activeController.timeToNextAttack = 1

CmrFwLib.activeController.attacking = false

CmrFwLib.activeController.blocking = false

CmrFwLib.activeController.timeToNextBlock = 0

CmrFwLib.activeController.increment = 3

CmrFwLib.activeController.hitboxMagnitude = 120

CmrFwLib.activeController.focusStart = 0

game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(GetBladeHit()))

game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, i, "")

end)

end

end

end

spawn(function()

while wait(.1) do

if _G.FastAttack then

pcall(function()

repeat task.wait(_G.FastAttackDelay)

AttackHit()

until not _G.FastAttack

end)

end

end

end)

 

local CamShake = require(game.ReplicatedStorage.Util.CameraShaker)

CamShake:Stop()

 

HttpService = game:GetService("HttpService")

local i = "Sla Hub"

local j = "-BloxFruit.json"

local l = game.Players.LocalPlayer.Name .. j

if Adel then

HttpService = game:GetService("HttpService")

local i = "Sla Hub"

local j = "-BloxFruit.json"

local l = game.Players.LocalPlayer.Name .. j

end

function SaveSettings(m, n)

if m ~= nil then

h[m] = n

end

HttpService = game:GetService("HttpService")

if not isfolder(i) then

makefolder(i)

end

writefile(i .. "/" .. l, HttpService:JSONEncode(h))

end

function ReadSetting()

local s, o =

pcall(

function()

HttpService = game:GetService("HttpService")

if not isfolder(i) then

makefolder(i)

end

return HttpService:JSONDecode(readfile(i .. "/" .. l))

end

)

if s then

return o

else

SaveSettings()

return ReadSetting()

end

end

 

function MoonTextureId()

if Sea1 then

return game:GetService("Lighting").FantasySky.MoonTextureId

elseif Sea2 then

return game:GetService("Lighting").FantasySky.MoonTextureId

elseif Sea3 then

return game:GetService("Lighting").Sky.MoonTextureId

end

end

 

function CheckMoon()

moon8 = "http://www.roblox.com/asset/?id=9709150401"

moon7 = "http://www.roblox.com/asset/?id=9709150086"

moon6 = "http://www.roblox.com/asset/?id=9709149680"

moon5 = "http://www.roblox.com/asset/?id=9709149431"

moon4 = "http://www.roblox.com/asset/?id=9709149052"

moon3 = "http://www.roblox.com/asset/?id=9709143733"

moon2 = "http://www.roblox.com/asset/?id=9709139597"

moon1 = "http://www.roblox.com/asset/?id=9709135895"

moonreal = MoonTextureId()

cofullmoonkothangbeo = "Bad Moon"

if moonreal == moon5 or moonreal == moon4 then

if moonreal == moon5 then

cofullmoonkothangbeo = "Full Moon"

elseif moonreal == moon4 then

cofullmoonkothangbeo = "Next Night"

end

end

return cofullmoonkothangbeo

end

 

function function7()

GameTime = "Error"

local c = game.Lighting

local ao = c.ClockTime

if ao >= 18 or ao < 5 then

GameTime = "Night"

else

GameTime = "Day"

end

return GameTime

end

function function6()

return math.floor(game.Lighting.ClockTime)

end

function getServerTime()

RealTime = tostring(math.floor(game.Lighting.ClockTime * 100) / 100)

RealTime = tostring(game.Lighting.ClockTime)

RealTimeTable = RealTime:split(".")

Minute, Second = RealTimeTable[1], tonumber(0 + tonumber(RealTimeTable[2] / 100)) * 60

return Minute, Second

end

function function8()

local c = game.Lighting

local ao = c.ClockTime

if CheckMoon() == "Full Moon" and ao <= 5 then

return tostring(function6()) .. " ( Will End Moon In " .. math.floor(5 - ao) .. " Minutes )"

elseif CheckMoon() == "Full Moon" and (ao > 5 and ao < 12) then

return tostring(function6()) .. " ( Fake Moon )"

elseif CheckMoon() == "Full Moon" and (ao > 12 and ao < 18) then

return tostring(function6()) .. " ( Will Full Moon In " .. math.floor(18 - ao) .. " Minutes )"

elseif CheckMoon() == "Full Moon" and (ao > 18 and ao <= 24) then

return tostring(function6()) .. " ( Will End Moon In " .. math.floor(24 + 6 - ao) .. " Minutes )"

end

if CheckMoon() == "Next Night" and ao < 12 then

return tostring(function6()) .. " ( Will Full Moon In " .. math.floor(18 - ao) .. " Minutes )"

elseif CheckMoon() == "Next Night" and ao > 12 then

return tostring(function6()) .. " ( Will Full Moon In " .. math.floor(18 + 12 - ao) .. " Minutes )"

end

return tostring(function6())

end

 

function CheckAcientOneStatus()

if not game.Players.LocalPlayer.Character:FindFirstChild("RaceTransformed") then

return "You have yet to achieve greatness"

end

local v227 = nil

local v228 = nil

local v229 = nil

v229, v228, v227 = game.ReplicatedStorage.Remotes.CommF_:InvokeServer("UpgradeRace", "Check")

if v229 == 1 then

return "Required Train More"

elseif v229 == 2 or v229 == 4 or v229 == 7 then

return "Can Buy Gear With " .. v227 .. " Fragments"

elseif v229 == 3 then

return "Required Train More"

elseif v229 == 5 then

return "You Are Done Your Race."

elseif v229 == 6 then

return "Upgrades completed: " .. v228 - 2 .. "/3, Need Trains More"

end

if v229 ~= 8 then

if v229 == 0 then

return "Ready For Trial"

else

return "You have yet to achieve greatness"

end

end

return "Remaining " .. 10 - v228 .. " training sessions."

end

 

local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Sla Hub", HidePremium = false, IntroText = "", SaveConfig = true, ConfigFolder = "Sla Hub"})

 

OrionLib:MakeNotification({

 Name = "Sla Hub",

 Content = "Choose Teams Bro?",

 Image = "rbxassetid://119980140458596",

 Time = 7

})

 

OrionLib:MakeNotification({

 Name = "Sla Hub",

 Content = "Sla Hub",

 Image = "rbxassetid://119980140458596",

 Time = 25

})

 

OrionLib:MakeNotification({

Name = "Sla Hub",

Content = "Please Wait loading script...,Do not enable any function",

Image = "rbxassetid://119980140458596",

Time = 5

})

 

-------------Tab-----------------------

 

local W = Window:MakeTab({

Name = "Welcome",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local M = Window:MakeTab({

Name = "General",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local ST = Window:MakeTab({

Name = "Setting",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local IQ = Window:MakeTab({

Name = "Item & Quest",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local S = Window:MakeTab({

Name = "Stats",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local E = Window:MakeTab({

Name = "ESP",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local RA = Window:MakeTab({

Name = "Raid",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local LC = Window:MakeTab({

Name = "Local Players",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local Wld = Window:MakeTab({

Name = "World Teleport",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local SV = Window:MakeTab({

Name = "Status Sever",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local D = Window:MakeTab({

Name = "Devil Fruit",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local R = Window:MakeTab({

Name = "Race V4",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local SH = Window:MakeTab({

Name = "Shop",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

local C = Window:MakeTab({

Name = "Misc",

Icon = "rbxassetid://119980140458596",

PremiumOnly = false

})

 

-----Label--------------------

local Section = W:AddSection({

Name = "Update"

})

 

W:AddLabel("[+] Sla Hub is HERE!")

W:AddLabel("[+] Best AutoFarm!")

W:AddLabel("[+] Up and Growing")

W:AddLabel("[+] Smooth")

 

local Section = W:AddSection({

Name = "Status"

})

 

local locallv = W:AddLabel("Level")

 

spawn(function()

while wait() do

pcall(function()

locallv:Set("Level :".." "..game:GetService("Players").LocalPlayer.Data.Level.Value)

end)

end

end)

 

local localrace = W:AddLabel("Race")

 

spawn(function()

while wait() do

pcall(function()

localrace:Set("Race :".." "..game:GetService("Players").LocalPlayer.Data.Race.Value)

end)

end

end)

 

local localbeli = W:AddLabel("Beli")

 

spawn(function()

while wait() do

pcall(function()

localbeli:Set("Beli :".." "..game:GetService("Players").LocalPlayer.Data.Beli.Value)

end)

end

end)

local localfrag = W:AddLabel("Fragment")

 

spawn(function()

while wait() do

pcall(function()

localfrag:Set("Fragments :".." "..game:GetService("Players").LocalPlayer.Data.Fragments.Value)

end)

end

end)

 

 

local localexp = W:AddLabel("ExP")

 

spawn(function()

while wait() do

pcall(function()

localexp:Set("ExP Points :".." "..game:GetService("Players").LocalPlayer.Data.Exp.Value)

end)

end

end)

 

local localstat = W:AddLabel("Stats Points")

 

spawn(function()

while wait() do

pcall(function()

localstat:Set("Stats Points :".." "..game:GetService("Players").LocalPlayer.Data.Points.Value)

end)

end

end)

 

local localbountyhornor = W:AddLabel("Bounty")

 

spawn(function()

while wait() do

pcall(function()

localbountyhornor:Set("Bounty / Honor :".." "..game:GetService("Players").LocalPlayer.leaderstats["Bounty/Honor"].Value)

end)

end

end)

 

local localDevil = W:AddLabel("Devil Fruit")

 

spawn(function()

while wait() do

pcall(function()

if game:GetService("Players").LocalPlayer.Character:FindFirstChild(game:GetService("Players").LocalPlayer.Data.DevilFruit.Value) or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(game:GetService("Players").LocalPlayer.Data.DevilFruit.Value) then

localDevil:Set("Devil Fruit :".." "..game:GetService("Players").LocalPlayer.Data.DevilFruit.Value)

else

localDevil:Set("Not Have Devil Fruit")

end

end)

end

end)

 

local Section = W:AddSection({

Name = "Status Hack"

})

 

local LevelFarmFarm W:AddLabel("Kaitun: Coming Soon")

W:AddLabel("Config Save : Comming Son...")

local Farmfast = W:AddLabel("Farm Fast : âŒ")

local Bypass = W:AddLabel("Bypass âŒ")

local Section = W:AddSection({

Name = "World"

})

local WolrdSet3 = W:AddLabel("World 1 âŒ ")

local WolrdSet = W:AddLabel("Wolrd : 2 âŒ")

local WolrdSet1 = W:AddLabel("Wolrd : 3 âŒ")

local Section = W:AddSection({

Name = "Stats Point"

})

local StastMelee = W:AddLabel("")

local StastDefense = W:AddLabel("")

local StastSword = W:AddLabel("")

local StastGun = W:AddLabel("")

local StastDevilFruit = W:AddLabel("")

local PointsStast = W:AddLabel("")

local Section = W:AddSection({

Name = "Melee Check"

})

local  Superhuman =             W:AddLabel("âŒ : Superhuman")

local  DeathStep =              W:AddLabel("âŒ : Sharkman Karate")

local  ElectricClaw =             W:AddLabel("âŒ : Electric Claw")

local  DragonTalon =             W:AddLabel("âŒ : Dragon Talon")

local   GodHuman =            W:AddLabel("âŒ : God Human")

local Section = W:AddSection({

Name = "Sword Legend Check"

})

local   Shisui =            W:AddLabel("âŒ : Shisui")

local     Saddi =           W:AddLabel("âŒ : Saddi")

local      Wando =         W:AddLabel("âŒ : Wando")

local     TrueTripleKatana          W:AddLabel("âŒ : True Triple Katana")

local Section = W:AddSection({

Name = "World 1 Weapon"

})

local   Saber  = W:AddLabel("âŒ : Saber")

local Section = W:AddSection({

Name = "World 2 Weapon"

})

local       Rengoku =         W:AddLabel("âŒ : Rengoku")

local    MidnightBlade =            W:AddLabel("âŒ : Midnight Blade")

local       DragonTrident =        W:AddLabel("âŒ : DragonTrident")

local Section = W:AddSection({

Name = "World 3 Weapon"

})

local     Yama =          W:AddLabel("âŒ : Yama")

local        BuddySword =        W:AddLabel("âŒ : Buddy Sword")

local       Canvander =        W:AddLabel("âŒ : Canvander")

local      TwinHooks =         W:AddLabel("âŒ : Twin Hooks")

local     SpikeyTrident =          W:AddLabel("âŒ : Spikey Trident")

local   HallowScythe =            W:AddLabel("âŒ : Hallow Scythe")

local     DarkDagger =           W:AddLabel("âŒ : Dark Dagger")

local     Tushita          W:AddLabel("âŒ : Tushita")

local Section = W:AddSection({

Name = "Gun"

})

local   Kabucha =            W:AddLabel("âŒ : Kabucha")

local   AcidumRifle =             W:AddLabel("âŒ : Acidum Rifle")

local    BizarreRifle =            W:AddLabel("âŒ : Bizarre Rifle")

local Section = W:AddSection({

Name = "Quest"

})

local   BartiloQuest =            W:AddLabel("âŒ : Bartilo Quest")

local   DonSwanQuest =             W:AddLabel("âŒ : Don Swan Quest")

local    KillDonSwan =           W:AddLabel("âŒ : Kill Don Swan")

 

 

local Section = W:AddSection({

Name = "Acessory"

})

 

 

local Dark_Coat = W:AddLabel("âŒ: Dark Coat")

local Ghoul_Mask = W:AddLabel("âŒ: Ghoul Mask")

local Swan_Glass = W:AddLabel("âŒ: Swan Glass")

local Pale_Scarf = W:AddLabel("âŒ: Pale Scarf")

local Valkyrie_Helm = W:AddLabel("âŒ: Valkyrie Helm")

 

 

spawn(function()

while task.wait() do

pcall(function()

for i,v in pairs(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventoryWeapons")) do

if v.Name == "Saber" then

Dark_Coat:Set("âœ…: Dark Coat")

end

if v.Name == "Ghoul Mask" then

Ghoul_Mask:Set("âœ…: Ghoul Mask")

end

if v.Name == "Swan Glasses" then

Swan_Glass:Set("âœ…: Swan Glass")

end

if v.Name == "Pale Scarf" then

Pale_Scarf:Set("âœ…: Pale Scarf")

end

if v.Name == "Valkyrie Helmet" then

Valkyrie_Helm:Set("âœ…: Valkyrie Helmet")

end

end

end)

end

end)

 

local Section = M:AddSection({

Name = "Select Weapon"

})

 

M:AddParagraph("Select Weapon","Please Select Weapon")

 

local WeaponList = {"Melee","Sword","Fruit","Gun"}

_G.SelectWeapon = "Melee"

M:AddDropdown({

Name = "Select Weapon",

Default = "",

Options = WeaponList,

Flag = "Select Weapon",

Save = true,

Callback = function(Value)

_G.SelectWeapon = Value

end

})

task.spawn(function()

while wait() do

pcall(function()

if _G.SelectWeapon == "Melee" then

for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do

if v.ToolTip == "Melee" then

if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then

_G.SelectWeapon = v.Name

end

end

end

elseif _G.SelectWeapon == "Sword" then

for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do

if v.ToolTip == "Sword" then

if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then

_G.SelectWeapon = v.Name

end

end

end

elseif _G.SelectWeapon == "Gun" then

for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do

if v.ToolTip == "Gun" then

if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then

_G.SelectWeapon = v.Name

end

end

end

elseif _G.SelectWeapon == "Fruit" then

for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do

if v.ToolTip == "Blox Fruit" then

if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then

_G.SelectWeapon = v.Name

end

end

end

end

end)

end

end)

 

if World2 and World1 then

local Section = M:AddSection({

Name = "BOOTS"

})

 

M:AddButton({

Name = "BOOST FPS",

Callback = function()

pcall(function()

game:GetService("Lighting").FantasySky:Destroy()

local g = game

local w = g.Workspace

local l = g.Lighting

local t = w.Terrain

t.WaterWaveSize = 0

t.WaterWaveSpeed = 0

t.WaterReflectance = 0

t.WaterTransparency = 0

l.GlobalShadows = false

l.FogEnd = 9e9

l.Brightness = 0

settings().Rendering.QualityLevel = "Level01"

for i, v in pairs(g:GetDescendants()) do

if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then

v.Material = "Plastic"

v.Reflectance = 0

elseif v:IsA("Decal") or v:IsA("Texture") then

v.Transparency = 1

elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then

v.Lifetime = NumberRange.new(0)

elseif v:IsA("Explosion") then

v.BlastPressure = 1

v.BlastRadius = 1

elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then

v.Enabled = false

elseif v:IsA("MeshPart") then

v.Material = "Plastic"

v.Reflectance = 0

v.TextureID = 10385902758728957

end

end

for i, e in pairs(l:GetChildren()) do

if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then

e.Enabled = false

end

end

for i, v in pairs(game:GetService("Workspace").Camera:GetDescendants()) do

if v.Name == ("Water;") then

v.Transparency = 1

v.Material = "Plastic"

end

end

end)

end

})

end

 

local Section = M:AddSection({

Name = "Other Farm"

})

 

M:AddParagraph("Redeem Code","Click to Button to Reddem All Code In Blox Fruits.")

 

local x2Code = {

"JULYUPDATE_RESET",

"staffbattle",

"Sub2CaptainMaui",

"SUB2GAMERROBOT_RESET1",

"KittGaming",

"Sub2Fer999",

"Enyu_is_Pro",

"Magicbus",

"ENYU_IS_PRO",

"FUDD10",

"BIGNEWS",

"THEGREATACE",

"SUB2GAMERROBOT_EXP1",

"STRAWHATMAIME",

"SUB2OFFICIALNOOBIE",

"SUB2NOOBMASTER123",

"SUB2DAIGROCK",

"AXIORE",

"TANTAIGAMIMG",

"STRAWHATMAINE",

"JCWK",

"FUDD10_V2",

"SUB2FER999",

"MAGICBIS",

"TY_FOR_WATCHING",

"STARCODEHEO"

}

 

 

 

M:AddButton({

Name = "Redeem all code",

Callback = function()

function RedeemCode(value)

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(value)

end

for i,v in pairs(x2Code) do

RedeemCode(v)

end

end

})

 

local Section = M:AddSection({

Name = "Auto Farm Level"

})

 

 

M:AddParagraph("Main Farm","Click to Box to Farm, I ready update new mob farm!.")

 

ToggleFarm = M:AddToggle({

Name = "Auto Farm",

Default = false,

Flag = "LevelFarm",

Save = true,

Callback = function(Value)

_G.AutoFarm = Value

StopTween(_G.AutoFarm)

end

})

 

local Section = M:AddSection({

Name = "Mastery Menu"

})

 

M:AddParagraph("Mastery Menu","Click To Box to Start Farm Mastery")

 

M:AddToggle({

Name = "Auto Farm BF Mastery",

Default = false,

Flag = "Mastery",

Save = true,

Callback = function(Value)

_G.AutoFarmFruitMastery = Value

StopTween(_G.AutoFarmFruitMastery)

if _G.AutoFarmFruitMastery == false then

UseSkill = false

end

end

})

 

M:AddToggle({

Name = "Auto Farm Gun Mastery",

Default = false,

Flag = "Gun Mastery",

Save = true,

Callback = function(Value)

_G.AutoFarmGunMastery = Value

StopTween(_G.AutoFarmGunMastery)

end

})

 

M:AddSlider({

Name = "Health Mob",

Min = 0,

Max = 100,

Default = 25,

Color = Color3.fromRGB(255,255,255),

Increment = 1,

ValueName = "Health",

Flag = "Health Mob",

Save = true,

Callback = function(Value)

_G.Kill_At = Value

end

})

 

M:AddToggle({

Name = "Skill Z",

Default = false,

Flag = "Skill Z",

Save = true,

Callback = function(Value)

_G.SkillZ = Value

end

})

 

M:AddToggle({

Name = "Skill! X",

Default = false,

Default = false,

Flag = "Skill X",

Save = true,

Callback = function(Value)

_G.SkillX = Value

end

})

 

 

M:AddToggle({

Name = "Skill C",

Default = false,

Default = false,

Flag = "Skill C",

Save = true,

Callback = function(Value)

_G.SkillC = Value

end

})

 

 

M:AddToggle({

Name = "Skill V",

Default = false,

Default = false,

Flag = "Skill V",

Save = true,

Callback = function(Value)

_G.SkillV = Value

end

})

 

M:AddToggle({

Name = "Skill F",

Default = false,

Default = false,

Flag = "Skill F",

Save = true,

Callback = function(Value)

_G.SkillF = Value

end

})

 

local Section = M:AddSection({

Name = "Bring Mob"

})

 

M:AddToggle({

Name = "Bring Mobs[Fix]",

Default = true,

Flag = "Bring Mobs",

Save = false,

Callback = function(Value)

_G.BringMonster = Value

end

})

local Bring = {"Low", "Normal", "Super Bring"}

_G.BringMode = "Normal"

M:AddDropdown({

Name = "Bring Mode",

Default = "Normal",

Options = Bring,

Default = false,

Flag = "Bring Mode",

Save = true,

Callback = function(Value)

_G.BringMode = Value

end

})

spawn(function()

while wait(.1) do

if _G.BringMode then

pcall(function()

if _G.BringMode == "Low" then

_G.BringMode = 300

elseif _G.BringMode == "Normal" then

_G.BringMode = 375

elseif _G.BringMode == "Super Bring" then

_G.BringMode = 450

end

end)

end

end

end)

 

local Section = M:AddSection({

Name = "FastAttack :"

})

 

M:AddToggle({

Name = "FastAttack",

Default = true,

Flag = "FastAttack",

Save = false,

Callback = function(Value)

_G.FastAttack = Value

end

})

local CameraShaker = require(game.ReplicatedStorage.Util.CameraShaker)

CombatFrameworkR = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)

y = debug.getupvalues(CombatFrameworkR)[2]

spawn(function()

game:GetService("RunService").RenderStepped:Connect(function()

if _G.FastAttack then

if typeof(y) == "table" then

pcall(function()

CameraShaker:Stop()

y.activeController.timeToNextAttack = (math.huge^math.huge^math.huge)

y.activeController.timeToNextAttack = 0

y.activeController.hitboxMagnitude = 60

y.activeController.active = false

y.activeController.timeToNextBlock = 0

y.activeController.focusStart = 1655503339.0980349

y.activeController.increment = 1

y.activeController.blocking = false

y.activeController.attacking = false

y.activeController.humanoid.AutoRotate = true

end)

end

end

end)

end)

spawn(function()

game:GetService("RunService").RenderStepped:Connect(function()

if _G.FastAttack == true then

game.Players.LocalPlayer.Character.Stun.Value = 0

game.Players.LocalPlayer.Character.Busy.Value = false

end

end)

end)

 

local AttackList = {"0", "0.1", "0.175", "0.2", "0.25", "0.3", "0.35", "0.4", "0.45", "0.5", "0.55", "0.6", "0.65", "0.7", "0.75", "0.8", "0.85", "0.9", "0.95", "0.1"}

M:AddDropdown({

 Name = "FastAttack Delay",

 Default = "0.5",

 Options = AttackList,

Flag = "FastAttack Delay",

Save = true,

 Callback = function(Value)

  _G.FastAttackDelay = Value

 end

})

spawn(function()

while wait(.1) do

if _G.FastAttackDelay then

pcall(function()

if _G.FastAttackDelay == "0" then

_G.FastAttackDelay = 0

elseif _G.FastAttackDelay == "0.1" then

_G.FastAttackDelay = 0.1

elseif _G.FastAttackDelay == "0.175" then

_G.FastAttackDelay = 0.175

elseif _G.FastAttackDelay == "0.2" then

_G.FastAttackDelay = 0.2

elseif _G.FastAttackDelay == "0.25" then

_G.FastAttackDelay = 0.25

elseif _G.FastAttackDelay == "0.3" then

_G.FastAttackDelay = 0.3

elseif _G.FastAttackDelay == "0.35" then

_G.FastAttackDelay = 0.35

elseif _G.FastAttackDelay == "0.4" then

_G.FastAttackDelay = 0.5

elseif _G.FastAttackDelay == "0.45" then

_G.FastAttackDelay = 0.45

elseif _G.FastAttackDelay == "0.5" then

_G.FastAttackDelay = 0.5

elseif _G.FastAttackDelay == "0.55" then

_G.FastAttackDelay = 0.55

elseif _G.FastAttackDelay == "0.6" then

_G.FastAttackDelay = 0.6

elseif _G.FastAttackDelay == "0.65" then

_G.FastAttackDelay = 0.65

elseif _G.FastAttackDelay == "0.7" then

_G.FastAttackDelay = 0.7

elseif _G.FastAttackDelay == "0.75" then

_G.FastAttackDelay = 0.75

elseif _G.FastAttackDelay == "0.8" then

_G.FastAttackDelay = 0.8

elseif _G.FastAttackDelay == "0.85" then

_G.FastAttackDelay = 0.85

elseif _G.FastAttackDelay == "0.9" then

_G.FastAttackDelay = 0.9

elseif _G.FastAttackDelay == "0.95" then

_G.FastAttackDelay = 0.95

elseif _G.FastAttackDelay == "1" then

_G.FastAttackDelay = 1

end

end)

end

end

end)

 

local Section = M:AddSection({

Name = "Bypass Teleport"

})

 

M:AddToggle({

Name = "Bypass TP[BETA]",

Default = false,

Flag = "Bypass TP",

Save = true,

Callback = function(Value)

BypassTP = true

end

})

 

 

local Section = M:AddSection({

Name = "Distance Mobs"

})

 

PosY = 30

M:AddSlider({

Name = "Distance Mob",

Min = 0,

Max = 65,

Default = PosY,

Color = Color3.fromRGB(255,255,255),

Increment = 1,

ValueName = "Distance",

Default = false,

Flag = "Distance",

Save = true,

Callback = function(Value)

PosY = Value

end

})

 

local Section = M:AddSection({

Name = "Farm Fast : Lv 10 => 120"

})

 

Farmfasttoggle = M:AddToggle({

Name = "Auto Farm Fast",

Default = false,

Flag = "Farm Fast",

Save = true,

Callback = function(Value)

_G.Farmfast = Value

StopTween(_G.Farmfast)

end

})

 

local Section = M:AddSection({

Name = "Kaitun Met Vaiz"

})

 

M:AddParagraph("Kaitun/Cantay","Kaitun báº£n nÃ y Ä‘ell khÃ¡c gÃ¬ báº£n kia.")

 

M:AddToggle({

Name = "Kaitun[Ko cÃ³ kill players]",

Default = false,

Flag = "Kaitun",

Save = true,

Callback = function(Value)

_G.RedeemCode = Value

_G.AutoFarm = Value

_G.Farmfast = Value

_G.SelectWeapon = "Combat"

_G.AutoPlayerHunter = Value

_G.Auto_Stats_Kaitun = Value

_G.Auto_Saber = Value

_G.AutoSuperhuman = Value

_G.AutoBartilo = Value

_G.AutoBuyLegendarySword = Value

_G.BuyAllAib = Value

StopTween(_G.AutoFarm)

StopTween(_G.Hunter)

StopTween(_G.Farmfast)

StopTween(_G.Auto_Saber)

end

})

 

M:AddToggle({

Name = "Auto Click[Kick]",

Default = false,

Flag = "Auto Click",

Save = true,

Callback = function(Value)

_G.AutoClick = Value

end

})

 

spawn(function()

game:GetService("RunService").RenderStepped:Connect(function()

if _G.AutoClick or Fastattack then

pcall(function()

game:GetService'VirtualUser':CaptureController()

game:GetService'VirtualUser':Button1Down(Vector2.new(0,1,0,1))

end)

end

end)

end)

 

spawn(function()

while wait() do

if _G.RedeemCode then

if MyLevel >= 10 then

function RedeemCode(value)

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(value)

end

for i,v in pairs(x2Code) do

RedeemCode(v)

end

end

end

end

end)

 

local Section = M:AddSection({

Name = "Mob & Boss Farm"

})

 

if World1 then

M:AddDropdown({

Name = "Select Mobs",

Default = "",

Options = {"Bandit","Monkey","Gorilla","Pirate","Brute","Desert Bandit","Desert Officer","Snow Bandit","Snowman","Chief Petty Officer","Sky Bandit","Dark Master","Prisoner", "Dangerous Prisoner","Toga Warrior","Gladiator","Military Soldier","Military Spy","Fishman Warrior","Fishman Commando","God's Guard","Shanda","Royal Squad","Royal Soldier","Galley Pirate ","Galley Captain"},

Callback = function(Value)

SelectMonster = Value

end

})

end

 

if World2 then

M:AddDropdown({

Name = "Select Mobs",

Default = "",

Options = {"Raider","Mercenary","Swan Pirate","Factory Staff","Marine Lieutenant","Marine Captain","Zombie","Vampire","Snow Trooper","Winter Warrior","Lab Subordinate","Horned Warrior","Magma Ninja","Lava Pirate","Ship Deckhand","Ship Engineer","Ship Steward","Ship Officer","Arctic Warrior","Snow Lurker","Sea Soldier","Water Fighter"},

Callback = function(Value)

SelectMonster = Value

end

})

end

 

if World3 then

M:AddDropdown({

Name = "Select Mobs",

Default = "",

Options = {"Pirate Millionaire","Dragon Crew Warrior","Dragon Crew Archer","Female Islander","Giant Islander","Marine Commodore","Marine Rear Admiral","Fishman Raider","Fishman Captain","Forest Pirate","Mythological Pirate","Jungle Pirate","Musketeer Pirate","Reborn Skeleton","Living Zombie","Demonic Soul","Posessed Mummy", "Peanut Scout", "Peanut President", "Ice Cream Chef", "Ice Cream Commander", "Cookie Crafter", "Cake Guard", "Baking Staff", "Head Baker", "Cocoa Warrior", "Chocolate Bar Battler", "Sweet Thief", "Candy Rebel", "Candy Pirate", "Snow Demon"},

Callback = function(Value)

SelectMonster = Value

end

})

end

 

M:AddToggle({

Name = "Farm Mob",

Default = false,

Callback = function(Value)

_G.AutoFarmSelectMonster = Value

end

})

 

local Section = M:AddSection({

Name = "Nearest Farm"

})

 

M:AddToggle({

Name = "Auto Farm Nearest",

Default = false,

Flag = "Auto Farm Nearest",

Save = true,

Callback = function(Value)

_G.AutoFarmNearest = Value

StopTween(_G.AutoFarmNearest)

end

})

 

local Section = M:AddSection({

Name = "Chest Farm"

})

 

TweenChest = M:AddToggle({

Name = "Auto Chest [MUP]",

Default = false,

Flag = "Auto Chest",

Save = true,

Callback = function(Value)

AutoFarmChest = Value

StopTween(AutoFarmChest)

end

})

 

M:AddToggle({

Name = "Auto Chest[Bypass]",

Default = false,

Flag = "Auto Chest[Bypass]",

Save = true,

Callback = function(Value)

_G.ChestBypass = Value

end

})

 

M:AddToggle({

Name = "Stop Only Dark Key or God's Chalice",

Default = false,

Flag = "Stop Only Dark Key or God's Chalice",

Save = true,

Callback = function(Value)

_G.StopChest = Value

end

})

spawn(function()

while wait() do

if _G.StopChest then

if game.Players.LocalPlayer.Backpack:FindFirstChild("Fist of Darkness") or game.Players.LocalPlayer.Character:FindFirstChild("Fist of Darkness") or game.Players.LocalPlayer.Backpack:FindFirstChild("God's Chalice") or game.Players.LocalPlayer.Character:FindFirstChild("God's Chalice") then

AutoFarmChest = false

StopTween(AutoFarmChest)

TweenChest:Set(false)

end

end

end

end)

 

local Section = M:AddSection({

Name = "Bone Menu"

})

 

local Bone = M:AddLabel("Bone : ")

 

spawn(function()

while wait() do

pcall(function()

Bone:Set("Bone You Have : "..(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Check")))

end)

end

end)

 

ToggleBone = M:AddToggle({

Name = "Auto Farm Bone",

Default = false,

Flag = "Auto Farm Bone",

Save = true,

Callback = function(Value)

_G.Auto_Bone = Value

StopTween(_G.Auto_Bone)

end

})

 

ToggleRandom = M:AddToggle({

Name = "Auto Random Bone",

Default = false,

Flag = "Auto Random Bone",

Save = true,

Callback = function(Value)

_G.Auto_Random_Bone = Value

end

})

spawn(function()

pcall(function()

while wait(.1) do

if _G.Auto_Random_Bone then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,1)

end

end

end)

end)

 

local Section = M:AddSection({

Name = "Other Menu"

})

 

local EliteProgress = M:AddLabel("")

 

spawn(function()

pcall(function()

while wait() do

EliteProgress:Set("Elite Progress : "..game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter","Progress"))

end

end)

end)

 

M:AddToggle({

Name = "Auto Elite",

Default = false,

Flag = "Auto Elite",

Save = true,

Callback = function(Value)

_G.AutoElitehunter = Value

StopTween(_G.AutoElitehunter)

end

})

 

 

M:AddToggle({

Name = "Auto Factory",

Default = false,

Flag = "Auto Factory",

Save = true,

Callback = function(Value)

_G.AutoFactory = Value

StopTween(_G.AutoFactory)

end

})

 

M:AddToggle({

Name = "Raid Castle",

Default = false,

Flag = "Auto Castle",

Save = true,

Callback = function(Value)

_G.RaidPirate = Value

StopTween(_G.RaidPirate)

end

})

local Section = M:AddSection({

Name = "Dough King Menu"

})

 

 

M:AddToggle({

Name = "Auto Katakuri",

Default = false,

Flag = "Auto Katakuri",

Save = true,

Callback = function(Value)

_G.AutoDoughtBoss = Value

StopTween(_G.AutoDoughtBoss)

end

})

 

M:AddToggle({

Name = "Auto Spawn Katakuri",

Default = true,

Callback = function(Value)

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CakePrinceSpawner",Value)

end

})

 

M:AddToggle({

Name = "Auto Katakuri v2",

Default = false,

Flag = "Auto Katakuri v2",

Save = true,

Callback = function(Value)

_G.Autodoughking = Value

StopTween(_G.Autodoughking)

end

})

 

M:AddToggle({

Name = "Auto Katakuri v2[HOP]",

Default = false,

Flag = "Auto Katakuri v2[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

local Section = M:AddSection({

Name = "Boss"

})

 

M:AddParagraph("Auto Farm Boss :","Chá» Update thÃ´i ae!!!")

 

local Section = M:AddSection({

Name = "Observation Haki"

})

 

M:AddToggle({

Name = "Auto Farm Observation Haki",

Default = false,

Flag = "Auto Farm Observation Haki",

Save = true,

Callback = function(Value)

_G.AutoObservation = Value

StopTween(_G.AutoObservation)

end

})

 

M:AddToggle({

Name = "Auto Farm Observation Haki[HOP]",

Default = false,

Flag = "Auto Farm Observation Haki[HOP]",

Save = true,

Callback = function(Value)

_G.AutoObservation_Hop = Value

end

})

 

local Section = M:AddSection({

Name = "Melee v2"

})

 

M:AddToggle({

Name = "Auto Death Step",

Default = false,

Flag = "Auto Death Step",

Save = true,

Callback = function(Value)

_G.AutoDeathStep = Value

end

})

 

M:AddToggle({

Name = "Auto SharkMan Karate",

Default = false,

Flag = "Auto SharkMan",

Save = true,

Callback = function(Value)

_G.AutoSharkman = Value

StopTween(_G.AutoSharkman)

end

})

 

M:AddToggle({

Name = "Auto Electric Claw",

Default = false,

Flag = "Auto Electric Claw",

Save = true,

Callback = function(Value)

_G.AutoElectricClaw = Value

StopTween(_G.AutoElectricClaw)

end

})

 

M:AddToggle({

Name = "Auto Dragon Talon",

Default = false,

Flag = "Auto Dragon Talon",

Save = true,

Callback = function(Value)

_G.AutoDragonTalon = Value

end

})

 

M:AddToggle({

Name = "Auto GodHuman",

Default = false,

Flag = "Auto GodHuman",

Save = true,

Callback = function(Value)

_G.Auto_God_Human = Value

end

})

 

ST:AddToggle({

Name = "Auto Haki",

Default = true,

Callback = function(Value)

_G.AUTOHAKI = Value

end

})

spawn(function()

while wait(.1) do

if _G.AUTOHAKI then

if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then

local args = {

[1] = "Buso"

}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))

end

end

end

end)

 

ST:AddToggle({

Name = "Anti Afk",

Default = true,

Callback = function(Value)

local vu = game:GetService("VirtualUser")

repeat wait() until game:IsLoaded()

game:GetService("Players").LocalPlayer.Idled:connect(function()

game:GetService("VirtualUser"):ClickButton2(Vector2.new())

vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

wait(1)

vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

end)

end

})

 

ST:AddToggle({

Name = "White screen",

Default = false,

Flag = "White screen",

Save = true,

Callback = function(Value)

_G.WhiteScreen = Value

if _G.WhiteScreen == true then

game:GetService("RunService"):Set3dRenderingEnabled(false)

elseif _G.WhiteScreen == false then

game:GetService("RunService"):Set3dRenderingEnabled(true)

end

end

})

 

function CheckAntiCheatBypass()

for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do

if v:IsA("LocalScript") then

if v.Name == "General" or v.Name == "Shiftlock"  or v.Name == "FallDamage" or v.Name == "4444" or v.Name == "CamBob" or v.Name == "JumpCD" or v.Name == "Looking" or v.Name == "Run" then

v:Destroy()

end

end

end

for i,v in pairs(game:GetService("Players").LocalPlayer.PlayerScripts:GetDescendants()) do

if v:IsA("LocalScript") then

if v.Name == "RobloxMotor6DBugFix" or v.Name == "Clans"  or v.Name == "Codes" or v.Name == "CustomForceField" or v.Name == "MenuBloodSp"  or v.Name == "PlayerList" then

v:Destroy()

end

end

end

end

 

CheckAntiCheatBypass()

 

ST:AddToggle({

Name = "Antiban",

Default = true,

Callback = function(Value)

_G.AntiCheat = Value

CheckAntiCheatBypass()

end

})

 

local Section = IQ:AddSection({

Name = "Saber Menu"

})

 

local SaberBoss = IQ:AddLabel("Boss Saber : ")

spawn(function()

while wait() do

pcall(function()

if game:GetService("ReplicatedStorage"):FindFirstChild("Saber Expert") or game:GetService("ReplicatedStorage"):FindFirstChild("Saber Expert") or game:GetService("ReplicatedStorage"):FindFirstChild("Saber Expert") or game:GetService("Workspace").Enemies:FindFirstChild("Saber Expert") or game:GetService("Workspace").Enemies:FindFirstChild("Saber Expert") or game:GetService("Workspace").Enemies:FindFirstChild("Saber Expert") then

SaberBoss:Set("Boss Saber : âœ… Spawn")

else

SaberBoss:Set("Boss Saber : âŒ Not Spawn")

end

end)

end

end)

 

IQ:AddToggle({

Name = "Auto Saber",

Default = false,

Flag = "Auto Saber",

Save = true,

Callback = function(Value)

_G.Auto_Saber = Value

StopTween(_G.Auto_Saber)

end

})

 

 

IQ:AddToggle({

Name = "Auto Saber[HOP]",

Default = false,

Flag = "Auto Saber[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

local Section = IQ:AddSection({

Name = "Pole V.1"

})

 

local PoleBoss = IQ:AddLabel("Boss Thunder God : ")

spawn(function()

while wait() do

pcall(function()

if game:GetService("ReplicatedStorage"):FindFirstChild("Thunder God") or game:GetService("ReplicatedStorage"):FindFirstChild("Thunder God") or game:GetService("ReplicatedStorage"):FindFirstChild("Thunder God") or game:GetService("Workspace").Enemies:FindFirstChild("Thunder God") or game:GetService("Workspace").Enemies:FindFirstChild("Thunder God") or game:GetService("Workspace").Enemies:FindFirstChild("Thunder God") then

PoleBoss:Set("Boss Thunder : âœ… Spawn")

else

PoleBoss:Set("Boss Thunder : âŒ Not Spawn")

end

end)

end

end)

 

TogglePolev1 = IQ:AddToggle({

Name = "Auto Pole V.1",

Default = false,

Flag = "Auto Pole",

Save = true,

Callback = function(Value)

_G.Autopole = Value

StopTween(_G.AutoPole)

end

})

 

TogglePolev1Hop = IQ:AddToggle({

Name = "Auto Pole V.1[HOP]",

Default = false,

Flag = "Auto Pole[HOP]",

Save = true,

Callback = function(Value)

_G.AutopoleHop = Value

end

})

 

local Section = IQ:AddSection({

Name = "Second Sea"

})

 

IQ:AddToggle({

Name = "Auto Second Sea",

Default = false,

Flag = "Auto Second",

Save = true,

Callback = function(Value)

_G.AutoSecondSea = Value

StopTween(_G.AutoSecondSea)

end

})

 

local Section = IQ:AddSection({

Name = "Vampire"

})

IQ:AddToggle({

Name = "Auto Vampire",

Default = false,

Flag = "Auto Vampire",

Save = true,

Callback = function(Value)

_G.AutoVampire = Value

StopTween(_G.AutoVampire)

end

})

 

 

local Section = IQ:AddSection({

Name = "SuperHuman"

})

 

IQ:AddToggle({

Name = "Auto SuperHuman",

Default = false,

Flag = "Auto SuperHuman",

Save = true,

Callback = function(Value)

_G.AutoSuperhuman = Value

StopTween(_G.AutoSuperhuman)

end

})

 

local Section = IQ:AddSection({

Name = "Bartilo"

})

 

 

BartiloToggle = IQ:AddToggle({

Name = "Auto Bartilo Quest",

Default = false,

Flag = "Auto Bartilo",

Save = true,

Callback = function(Value)

_G.AutoBartilo = Value

StopTween(_G.AutoBartilo)

StopTween(_G.AutoFarm)

end

})

 

local Section = IQ:AddSection({

Name = "Next Sea Third"

})

 

 

IQ:AddToggle({

Name = "Auto Third Sea",

Default = false,

Flag = "Auto Third",

Save = true,

Callback = function(Value)

_G.AutoThirdSea = Value

StopTween(_G.AutoThirdSea)

end

})

 

IQ:AddToggle({

Name = "Auto Buy Legend Sword",

Default = false,

Flag = "Auto Legend",

Save = true,

Callback = function(Value)

_G.AutoBuyLegendarySword = Value

end

})

 

local Section = IQ:AddSection({

Name = "Buddy Sword"

})

 

IQ:AddToggle({

Name = "Auto Buddy Sword",

Default = false,

Flag = "Auto Buddy",

Save = true,

Callback = function(Value)

_G.AutoBudySword = Value

StopTween(_G.AutoBudySword)

end

})

 

IQ:AddToggle({

Name = "Auto Buddy Sword[HOP]",

Default = false,

Flag = "Auto Buddy[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

local Section = IQ:AddSection({

Name = "Soul Guita"

})

 

IQ:AddToggle({

Name = "Auto Soul Guita",

Default = false,

Flag = "Auto Soul",

Save = true,

Callback = function(Value)

_G.AutoNevaSoulGuitar = Value

StopTween(_G.AutoNevaSoulGuitar)

end

})

 

IQ:AddToggle({

Name = "Auto Soul Guita[HOP]",

Default = false,

Flag = "Auto Soul[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

IQ:AddToggle({

Name = "Auto Auto Observation V2",

Default = false,

Flag = "Auto ObservationV2",

Save = true,

Callback = function(Value)

_G.AutoObservationHakiV2 = Value

StopTween(_G.AutoObservationHakiV2)

end

})

 

local Section = IQ:AddSection({

Name = "Auto Dual Curset Katana[Not Work]"

})

 

IQ:AddToggle({

Name = "Auto Dual Curset Katana",

Default = false,

Flag = "Auto DualCursetKatana",

Save = true,

Callback = function(Value)

Auto_Cursed_Dual_Katana = Value

StopTween(Auto_Cursed_Dual_Katana)

end

})

 

local Section = IQ:AddSection({

Name = "Tushita"

})

 

IQ:AddToggle({

Name = "Auto Tushita",

Default = false,

Flag = "Auto Tushita",

Save = true,

Callback = function(Value)

_G.Autotushita = Value

StopTween( _G.Autotushita)

 

end

})

 

IQ:AddToggle({

Name = "Auto Tushita[HOP]",

Default = false,

Flag = "Auto Tushita[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

local Section = IQ:AddSection({

Name = "Cavander"

})

 

IQ:AddToggle({

Name = "Auto Cavander",

Default = false,

Flag = "Auto Cavander",

Save = true,

Callback = function(Value)

_G.AutoCarvender = Value

StopTween( _G.AutoCarvender)

end

})

 

IQ:AddToggle({

Name = "Auto Cavander[HOP]",

Default = false,

Flag = "Auto Cavander[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

local Section = IQ:AddSection({

Name = "Twin Hook"

})

 

IQ:AddToggle({

Name = "Auto Twin Hook",

Default = false,

Flag = "Auto Twin",

Save = true,

Callback = function(Value)

_G.AutoTwinHook = Value

StopTween( _G.AutoTwinHook)

end

})

 

IQ:AddToggle({

Name = "Auto Twin Hook[HOP]",

Default = false,

Flag = "Auto Twin[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

local Section = IQ:AddSection({

Name = "ArenaTrainer"

})

 

IQ:AddLabel("Cho tháº±ng nÃ o Ä‘ell hiá»ƒu thÃ¬ Ä‘Ã¢y lÃ  tá»± Ä‘á»™ng Ä‘Ã¡nh hÃ¬nh ná»™m")

 

IQ:AddToggle({

Name = "Automatically hit the dummy",

Default = false,

Flag = "Auto dummy",

Save = true,

Callback = function(Value)

_G.Namfon = Value

StopTween(_G.Namfon)

end

})

 

IQ:AddToggle({

Name = "Automatically hit the dummy[HOP]",

Default = false,

Flag = "Auto dummy[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

local Section = IQ:AddSection({

Name = "Seperator Hallow Scythe"

})

 

IQ:AddToggle({

Name = "Auto Hallow Scythe",

Default = false,

Flag = "Auto Hallow",

Save = true,

Callback = function(Value)

_G.AutoFarmBossHallow = Value

StopTween(_G.AutoFarmBossHallow)

end

})

 

ToggleHallow = IQ:AddToggle({

Name = "Auto Hallow Scythe[HOP]",

Default = false,

Flag = "Auto Hallow[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

local Section = IQ:AddSection({

Name = "Dark Dragger"

})

 

IQ:AddToggle({

Name = "Auto Dark Dragger",

Default = false,

Flag = "Auto Dark",

Save = true,

Callback = function(Value)

_G.AutoDarkDagger = Value

StopTween(_G.AutoDarkDagger)

end

})

 

IQ:AddToggle({

Name = "Auto Dark Dragger[HOP]",

Default = false,

Flag = "Auto Dark[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

spawn(function()

pcall(function()

while wait() do

if (_G.AutoDarkDagger_Hop and _G.AutoDarkDagger) and World3 and not game:GetService("ReplicatedStorage"):FindFirstChild("rip_indra True Form") and not game:GetService("Workspace").Enemies:FindFirstChild("rip_indra True Form") then

Hop()

end

end

end)

end)

 

 

function EquipAllWeapon()

pcall(function()

for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do

if v:IsA('Tool') and not (v.Name == "Summon Sea Beast" or v.Name == "Water Body" or v.Name == "Awakening") then

local ToolHumanoid = game.Players.LocalPlayer.Backpack:FindFirstChild(v.Name)

game.Players.LocalPlayer.Character.Humanoid:EquipTool(ToolHumanoid)

wait(1)

end

end

end)

end

 

local Section = IQ:AddSection({

Name = "SeaBeast"

})

 

IQ:AddToggle({

Name = "Auto Seabeast",

Default = false,

Flag = "Auto Seabeast",

Save = true,

Callback = function(Value)

_G.AutoSeaBest = Value

StopTween(_G.AutoSeaBest)

end

})

 

IQ:AddToggle({

Name = "Auto Seabeast[HOP]",

Default = false,

Flag = "Auto Seabeast[HOP]",

Save = true,

Callback = function(Value)

_G.Hop = Value

end

})

 

 

spawn(function()

pcall(function()

while wait() do

if _G.Hop == true then

Hop()

elseif _G.Hop == false then

end

end

end)

end)

 

local Section = IQ:AddSection({

Name = "Mirrage Menu"

})

 

IQ:AddToggle({

Name = "Auto Summon and Find Mirrage Island",

Default = false,

Flag = "Auto Mirrage",

Save = true,

Callback = function(Value)

_G.dao = Value

if Value then

_G.dao = true

else

_G.dao = false

end

 

 

if _G.dao then

local args = {

[1] = "requestEntrance",

[2] = Vector3.new(-12463.6025390625, 378.3270568847656, -7566.0830078125)

}

 

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))

wait(1)

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5411.22021, 778.609863, -2682.27759, 0.927179396, 0, 0.374617696, 0, 1, 0, -0.374617696, 0, 0.927179396)

wait(0)

-- Script generated by SimpleSpy - credits to exx#9394

 

local args = {

[1] = "BuyBoat",

[2] = "PirateBrigade"

}

 

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))

 

function two(gotoCFrame) --- Tween

pcall(function()

game.Players.LocalPlayer.Character.Humanoid.Sit = false

game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false

end)

if (game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - gotoCFrame.Position).Magnitude <= 200 then

pcall(function()

tweenz:Cancel()

end)

game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.CFrame = gotoCFrame

else

local tween_s = game:service"TweenService"

local info = TweenInfo.new((game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - gotoCFrame.Position).Magnitude/325, Enum.EasingStyle.Linear)

tween, err = pcall(function()

tweenz = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = gotoCFrame})

tweenz:Play()

end)

if not tween then return err end

end

function _TweenCanCle()

tweenz:Cancel()

end

 

end

two(CFrame.new(-5100.7085, 29.968586, -6792.45459, -0.33648631, -0.0396691673, 0.940852463, -6.40461678e-07, 0.999112308, 0.0421253517, -0.941688359, 0.0141740013, -0.336187631))

 

wait(13)

for _,v in next, workspace.Boats.PirateBrigade:GetDescendants() do

if v.Name:find("VehicleSeat") then

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame

if game:GetService("Workspace").Map:FindFirstChild("MysticIsland") then

topos(game:GetService("Workspace").Map:FindFirstChild("MysticIsland").HumanoidRootPart.CFrame * CFrame.new(0,500,-100))

 

end

end

end

end

 

end

})

 

IQ:AddToggle({

Name = "Find Mirrage[HOP]",

Default = false,

Flag = "Auto Mirrage2",

Save = true,

Callback = function(Value)

_G.Hop =  Value

end

})

 

local Section = S:AddSection({

Name = "Stats Select"

})

 

spawn(function()

while wait() do

local count10 = 0

local count = 0

for i,v in pairs(game.workspace:GetChildren()) do

if string.find(v.Name,"Chest") and v:IsA("Part") then

count10 = count10 + 1

end

end

for i,v in pairs(game.Workspace:GetChildren()) do

if v.Name == "Blox Fruit Dealer" then

else

if string.find(v.Name, "Fruit") and v:IsA("Tool") then

count = count + 1

end

if string.find(v.Name, "Fruit") and v:IsA("Model") then

count = count + 1

end

end

end

Fruit:Set("Fruit : "..count)

Chest:Set("Chest : "..count10)

wait(5)

end

end)

 

Chest = S:AddLabel("Chest")

 

Fruit = S:AddLabel("Fruit")

 

local Pointstat = S:AddLabel("Stat Points")

 

spawn(function()

while wait() do

pcall(function()

Pointstat:Set("Stat Points : "..tostring(game:GetService("Players")["LocalPlayer"].Data.Points.Value))

end)

end

end)

 

local Melee = S:AddLabel("Melee : ")

local Defense = S:AddLabel("Defense : ")

local Sword = S:AddLabel("Sword : ")

local Gun = S:AddLabel("Gun : ")

local Fruit = S:AddLabel("Fruit : ")

 

spawn(function()

while wait() do

pcall(function()

Melee:Set("Melee : "..game.Players.localPlayer.Data.Stats.Melee.Level.Value)

end)

end

end)

 

spawn(function()

while wait() do

pcall(function()

Defense:Set("Defense : "..game.Players.localPlayer.Data.Stats.Defense.Level.Value)

end)

end

end)

 

spawn(function()

while wait() do

pcall(function()

Sword:Set("Sword : "..game.Players.localPlayer.Data.Stats.Sword.Level.Value)

end)

end

end)

 

spawn(function()

while wait() do

pcall(function()

Gun:Set("Gun : "..game.Players.localPlayer.Data.Stats.Gun.Level.Value)

end)

end

end)

 

spawn(function()

while wait() do

pcall(function()

Fruit:Set("Fruit : "..game.Players.localPlayer.Data.Stats["Demon Fruit"].Level.Value)

end)

end

end)

 

S:AddToggle({

Name = "Auto Stats Kaitun",

Default = false,

Flag = "Auto Kaitun",

Save = true,

Callback = function(Value)

_G.Auto_Stats_Kaitun = Value

end

})

 

S:AddToggle({

Name = "Melee",

Default = false,

Flag = "Auto Melee",

Save = true,

Callback = function(Value)

melee = Value

end

})

 

S:AddToggle({

Name = "Defense",

Default = false,

Flag = "Auto Defense",

Save = true,

Callback = function(Value)

defense = Value

end

})

 

S:AddToggle({

Name = "Sword",

Default = false,

Flag = "Auto Sword",

Save = true,

Callback = function(Value)

sword = Value

end

})

 

S:AddToggle({

Name = "Gun",

Default = false,

Flag = "Auto Gun",

Save = true,

Callback = function(Value)

gun = Value

end

})

 

S:AddToggle({

Name = "Devil Fruit",

Default = false,

Flag = "Auto Fruit",

Save = true,

Callback = function(Value)

demonfruit = Value

end

})

 

PointStats = 1

S:AddSlider({

Name = "Point",

Min = 1,

Max = 2450,

Default = 1,

Color = Color3.fromRGB(255,255,255),

Increment = 1,

ValueName = "Point",

Flag = "Auto Point",

Save = true,

Callback = function(Value)

PointStats = Value

end

})

 

local Section = E:AddSection({

Name = "ESP MENU"

})

 

E:AddToggle({

Name = "ESP Players",

Default = false,

Flag = "ESP Players",

Save = true,

Callback = function(a)

ESPPlayer = a

UpdatePlayerChams()

end

})

function isnil(thing)

return (thing == nil)

end

local function round(n)

return math.floor(tonumber(n) + 0.5)

end

Number = math.random(1, 1000000)

function UpdatePlayerChams()

for i,v in pairs(game:GetService'Players':GetChildren()) do

pcall(function()

if not isnil(v.Character) then

if ESPPlayer then

if not isnil(v.Character.Head) and not v.Character.Head:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Character.Head)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Character.Head

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance')

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

if v.Team == game.Players.LocalPlayer.Team then

name.TextColor3 = Color3.new(0,255,0)

else

name.TextColor3 = Color3.new(255,0,0)

end

else

v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..' | '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distance\nHealth : ' .. round(v.Character.Humanoid.Health*100/v.Character.Humanoid.MaxHealth) .. '%')

end

else

if v.Character.Head:FindFirstChild('NameEsp'..Number) then

v.Character.Head:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end)

end

end

 

E:AddToggle({

Name = "ESP Fruits",

Default = false,

Flag = "ESP Fruits",

Save = true,

Callback = function(b)

DevilFruitESP = b

while DevilFruitESP do wait()

UpdateDevilChams()

end

end

})

function UpdateDevilChams()

for i,v in pairs(game.Workspace:GetChildren()) do

pcall(function()

if DevilFruitESP then

if string.find(v.Name, "Fruit") then

if not v.Handle:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v.Handle)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v.Handle

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 255, 255)

name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

else

v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distance')

end

end

else

if v.Handle:FindFirstChild('NameEsp'..Number) then

v.Handle:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end)

end

end

 

spawn(function()

while wait(2) do

if FlowerESP then

UpdateFlowerChams()

end

if DevilFruitESP then

UpdateDevilChams()

end

if ChestESP then

UpdateChestChams()

end

if ESPPlayer then

UpdatePlayerChams()

end

if RealFruitESP then

UpdateRealFruitChams()

end

end

end)

 

E:AddToggle({

Name = "ESP Island",

Default = false,

Flag = "ESP Island",

Save = true,

Callback = function(Value)

IslandESP = Value

while IslandESP do wait()

UpdateIslandESP()

end

end

})

function UpdateIslandESP()

for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do

pcall(function()

if IslandESP then

if v.Name ~= "Sea" then

if not v:FindFirstChild('NameEsp') then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = "GothamBold"

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(7, 236, 240)

else

v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

end

else

if v:FindFirstChild('NameEsp') then

v:FindFirstChild('NameEsp'):Destroy()

end

end

end)

end

end

 

E:AddToggle({

Name = "ESP Flower",

Default = false,

Flag = "ESP Flower",

Save = true,

Callback = function(Value)

FlowerESP = Value

UpdateFlowerChams()

end

})

function UpdateFlowerChams()

for i,v in pairs(game.Workspace:GetChildren()) do

pcall(function()

if v.Name == "Flower2" or v.Name == "Flower1" then

if FlowerESP then

if not v:FindFirstChild('NameEsp'..Number) then

local bill = Instance.new('BillboardGui',v)

bill.Name = 'NameEsp'..Number

bill.ExtentsOffset = Vector3.new(0, 1, 0)

bill.Size = UDim2.new(1,200,1,30)

bill.Adornee = v

bill.AlwaysOnTop = true

local name = Instance.new('TextLabel',bill)

name.Font = Enum.Font.GothamSemibold

name.FontSize = "Size14"

name.TextWrapped = true

name.Size = UDim2.new(1,0,1,0)

name.TextYAlignment = 'Top'

name.BackgroundTransparency = 1

name.TextStrokeTransparency = 0.5

name.TextColor3 = Color3.fromRGB(255, 0, 0)

if v.Name == "Flower1" then

name.Text = ("Blue Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

name.TextColor3 = Color3.fromRGB(0, 0, 255)

end

if v.Name == "Flower2" then

name.Text = ("Red Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

name.TextColor3 = Color3.fromRGB(255, 0, 0)

end

else

v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distance')

end

else

if v:FindFirstChild('NameEsp'..Number) then

v:FindFirstChild('NameEsp'..Number):Destroy()

end

end

end

end)

end

end

 

local TimeRaid = RA:AddLabel("Wait For Dungeon")

 

local checkisland = RA:AddLabel("Island : Not Raid")

 

_G.SelectChip = selectraids or ""

Raidslist = {}

RaidsModule = require(game.ReplicatedStorage.Raids)

for i,v in pairs(RaidsModule.raids) do

table.insert(Raidslist,v)

end

for i,v in pairs(RaidsModule.advancedRaids) do

table.insert(Raidslist,v)

end

 

 

RA:AddDropdown({

Name = "Select Chips",

Default = "",

Options = Raidslist,

Flag = "Select Chips",

Save = true,

Callback = function(Value)

_G.SelectChip = Value

end

})

 

 

 

RA:AddButton({

Name = "Buy Chip",

Callback = function()

_G.AutoBuyChip = value

end

})

 

RA:AddButton({

Name = "Buy Chips Select",

Callback = function()

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("RaidsNpc","Select",_G.SelectChip)

end

})

 

RA:AddToggle({

Name = "Auto Start Raid",

Default = false,

Flag = "Auto Start",

Save = true,

Callback = function(Value)

_G.Auto_StartRaid = Value

end

})

 

 

local Section = RA:AddSection({

Name = "Raid Menu"

})

 

RA:AddToggle({

Name = "KillAura",

Default = false,

Flag = "Auto KillAura",

Save = true,

Callback = function(Value)

_G.Kill_Aura = Value

end

})

 

RA:AddToggle({

Name = "Next Island",

Default = false,

Flag = "Auto NextIsland",

Save = true,

Callback = function(Value)

_G.Auto_Dungeon = Value

StopTween(_G.Auto_Dungeon)

end

})

 

RA:AddToggle({

Name = "Auto Awakener",

Default = false,

Flag = "Auto Awakener",

Save = true,

Callback = function(Value)

_G.Auto_Awakener = Value

end

})

 

local Section = RA:AddSection({

Name = "Raid Law Menu"

})

 

RA:AddToggle({

Name = "Auto Buy Chips Law[Raid]",

Default = false,

Flag = "Auto Chips Law",

Save = true,

Callback = function(Value)

_G.Auto_Buy_Law_Chip = Value

end

})

 

RA:AddToggle({

Name = "Start Raid Law",

Default = false,

Flag = "Auto Start Raid Law",

Save = true,

Callback = function(Value)

_G.Auto_Start_Law_Dungeon = Value

end

})

 

RA:AddToggle({

Name = "Auto Kill Law",

Default = false,

Flag = "Auto Kill Law",

Save = true,

Callback = function(Value)

_G.Auto_Kill_Law = Value

StopTween(_G.Auto_Kill_Law)

end

})

 

local Section = LC:AddSection({

Name = "Teleport Island"

})

 

 

if World1 then

LC:AddDropdown({

Name = "Select Island",

Default = "",

Options = {"WindMill",

"Marine",

"Middle Town",

"Jungle",

"Pirate Village",

"Desert",

"Snow Island",

"MarineFord",

"Colosseum",

"Sky Island 1",

"Sky Island 2",

"Sky Island 3",

"Prison",

"Magma Village",

"Under Water Island",

"Fountain City",

"Shank Room",

"Mob Island",},

Flag = "Select Island",

Save = true,

Callback = function(Value)

_G.SelectIsland = Value

end

})

end

 

if World2 then

LC:AddDropdown({

Name = "Select Island",

Default = "",

Options = {"The Cafe",

"Frist Spot",

"Dark Area",

"Flamingo Mansion",

"Flamingo Room",

"Green Zone",

"Factory",

"Colossuim",

"Zombie Island",

"Two Snow Mountain",

"Punk Hazard",

"Cursed Ship",

"Ice Castle",

"Forgotten Island",

"Ussop Island",

"Mini Sky Island"},

Flag = "Select Island",

Save = true,

Callback = function(Value)

_G.SelectIsland = Value

end

})

end

 

if World3 then

LC:AddDropdown({

Name = "Select Island",

Default = "",

Options = {"Mansion",

"Port Town",

"Great Tree",

"Castle On The Sea",

"MiniSky",

"Hydra Island",

"Floating Turtle",

"Haunted Castle",

"Ice Cream Island",

"Peanut Island",

"Cake Island",

"Cocoa Island",

"Tiki Outpost New",

"Candy Island Newâ›„"},

Flag = "Select Island",

Save = true,

Callback = function(Value)

_G.SelectIsland = Value

end

})

end

 

LC:AddToggle({

Name = "Teleport To Island",

Default = false,

Callback = function(Value)

_G.TeleportIsland = Value

if _G.TeleportIsland == true then

repeat wait()

if _G.SelectIsland == "WindMill" then

topos(CFrame.new(979.79895019531, 16.516613006592, 1429.0466308594))

elseif _G.SelectIsland == "Marine" then

topos(CFrame.new(-2566.4296875, 6.8556680679321, 2045.2561035156))

elseif _G.SelectIsland == "Middle Town" then

topos(CFrame.new(-690.33081054688, 15.09425163269, 1582.2380371094))

elseif _G.SelectIsland == "Jungle" then

topos(CFrame.new(-1612.7957763672, 36.852081298828, 149.12843322754))

elseif _G.SelectIsland == "Pirate Village" then

topos(CFrame.new(-1181.3093261719, 4.7514905929565, 3803.5456542969))

elseif _G.SelectIsland == "Desert" then

topos(CFrame.new(944.15789794922, 20.919729232788, 4373.3002929688))

elseif _G.SelectIsland == "Snow Island" then

topos(CFrame.new(1347.8067626953, 104.66806030273, -1319.7370605469))

elseif _G.SelectIsland == "MarineFord" then

topos(CFrame.new(-4914.8212890625, 50.963626861572, 4281.0278320313))

elseif _G.SelectIsland == "Colosseum" then

topos( CFrame.new(-1427.6203613281, 7.2881078720093, -2792.7722167969))

elseif _G.SelectIsland == "Sky Island 1" then

topos(CFrame.new(-4869.1025390625, 733.46051025391, -2667.0180664063))

elseif _G.SelectIsland == "Sky Island 2" then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))

elseif _G.SelectIsland == "Sky Island 3" then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))

elseif _G.SelectIsland == "Prison" then

topos( CFrame.new(4875.330078125, 5.6519818305969, 734.85021972656))

elseif _G.SelectIsland == "Magma Village" then

topos(CFrame.new(-5247.7163085938, 12.883934020996, 8504.96875))

elseif _G.SelectIsland == "Under Water Island" then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))

elseif _G.SelectIsland == "Fountain City" then

topos(CFrame.new(5127.1284179688, 59.501365661621, 4105.4458007813))

elseif _G.SelectIsland == "Shank Room" then

topos(CFrame.new(-1442.16553, 29.8788261, -28.3547478))

elseif _G.SelectIsland == "Mob Island" then

topos(CFrame.new(-2850.20068, 7.39224768, 5354.99268))

elseif _G.SelectIsland == "The Cafe" then

topos(CFrame.new(-380.47927856445, 77.220390319824, 255.82550048828))

elseif _G.SelectIsland == "Frist Spot" then

topos(CFrame.new(-11.311455726624, 29.276733398438, 2771.5224609375))

elseif _G.SelectIsland == "Dark Area" then

topos(CFrame.new(3780.0302734375, 22.652164459229, -3498.5859375))

elseif _G.SelectIsland == "Flamingo Mansion" then

topos(CFrame.new(-483.73370361328, 332.0383605957, 595.32708740234))

elseif _G.SelectIsland == "Flamingo Room" then

topos(CFrame.new(2284.4140625, 15.152037620544, 875.72534179688))

elseif _G.SelectIsland == "Green Zone" then

topos( CFrame.new(-2448.5300292969, 73.016105651855, -3210.6306152344))

elseif _G.SelectIsland == "Factory" then

topos(CFrame.new(424.12698364258, 211.16171264648, -427.54049682617))

elseif _G.SelectIsland == "Colossuim" then

topos( CFrame.new(-1503.6224365234, 219.7956237793, 1369.3101806641))

elseif _G.SelectIsland == "Zombie Island" then

topos(CFrame.new(-5622.033203125, 492.19604492188, -781.78552246094))

elseif _G.SelectIsland == "Two Snow Mountain" then

topos(CFrame.new(753.14288330078, 408.23559570313, -5274.6147460938))

elseif _G.SelectIsland == "Punk Hazard" then

topos(CFrame.new(-6127.654296875, 15.951762199402, -5040.2861328125))

elseif _G.SelectIsland == "Cursed Ship" then

topos(CFrame.new(923.40197753906, 125.05712890625, 32885.875))

elseif _G.SelectIsland == "Ice Castle" then

topos(CFrame.new(6148.4116210938, 294.38687133789, -6741.1166992188))

elseif _G.SelectIsland == "Forgotten Island" then

topos(CFrame.new(-3032.7641601563, 317.89672851563, -10075.373046875))

elseif _G.SelectIsland == "Ussop Island" then

topos(CFrame.new(4816.8618164063, 8.4599885940552, 2863.8195800781))

elseif _G.SelectIsland == "Mini Sky Island" then

topos(CFrame.new(-288.74060058594, 49326.31640625, -35248.59375))

elseif _G.SelectIsland == "Great Tree" then

topos(CFrame.new(2681.2736816406, 1682.8092041016, -7190.9853515625))

elseif _G.SelectIsland == "Castle On The Sea" then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-5071.82324, 314.858734, -3150.69922, -0.392243683, -1.68831065e-08, -0.919861317, 2.14809548e-09, 1, -1.9269951e-08, 0.919861317, -9.53446655e-09, -0.392243683))

elseif _G.SelectIsland == "MiniSky" then

topos(CFrame.new(-260.65557861328, 49325.8046875, -35253.5703125))

elseif _G.SelectIsland == "Port Town" then

topos(CFrame.new(-290.7376708984375, 6.729952812194824, 5343.5537109375))

elseif _G.SelectIsland == "Hydra Island" then

topos(CFrame.new(5228.8842773438, 604.23400878906, 345.0400390625))

elseif _G.SelectIsland == "Floating Turtle" then

topos(CFrame.new(-13274.528320313, 531.82073974609, -7579.22265625))

elseif _G.SelectIsland == "Mansion" then

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-12471.169921875, 374.94024658203, -7551.677734375))

elseif _G.SelectIsland == "Haunted Castle" then

topos(CFrame.new(-9515.3720703125, 164.00624084473, 5786.0610351562))

elseif _G.SelectIsland == "Ice Cream Island" then

topos(CFrame.new(-902.56817626953, 79.93204498291, -10988.84765625))

elseif _G.SelectIsland == "Peanut Island" then

topos(CFrame.new(-2062.7475585938, 50.473892211914, -10232.568359375))

elseif _G.SelectIsland == "Cake Island" then

topos(CFrame.new(-1884.7747802734375, 19.327526092529297, -11666.8974609375))

elseif _G.SelectIsland == "Cocoa Island" then

topos(CFrame.new(87.94276428222656, 73.55451202392578, -12319.46484375))

elseif _G.SelectIsland == "Candy Island Newâ›„" then

topos(CFrame.new(-1014.4241943359375, 149.11068725585938, -14555.962890625))

elseif _G.SelectIsland == "Tiki Outpost New" then

topos(CFrame.new(-16101.1885, 12.8422165, 380.942291, 0.194113985, 1.39194061e-08, -0.980978966, -9.82904691e-09, 1, 1.22443504e-08, 0.980978966, 7.26528837e-09, 0.194113985))

else

_G.TeleportIsland = false

StopTween(_G.TeleportIsland)

end

until not _G.TeleportIsland

end

StopTween(_G.TeleportIsland)

end

})

 

local Section = LC:AddSection({

Name = "Teleport NPC"

})

 

NPC1 = {

"Random Devil Fruit",

"Blox Fruits Dealer",

"Remove Devil Fruit",

"Ability Teacher",

"Dark Step",

"Electro",

"Fishman Karate"

}

 

NPC2 = {

"Dargon Berath",

"Mtsterious Man",

"Mysterious Scientist",

"Awakening Expert",

"Nerd",

"Bar Manager",

"Blox Fruits Dealer",

"Trevor",

"Enhancement Editor",

"Pirate Recruiter",

"Marines Recruiter",

"Chemist",

"Cyborg",

"Ghoul Mark",

"Guashiem",

"El Admin",

"El Rodolfo",

"Arowe"

}

 

NPC3 = {

"Blox Fruits Dealer",

"Remove Devil Fruit",

"Horned Man",

"Hungey Man",

"Previous Hero",

"Butler",

"Lunoven",

"Trevor",

"Elite Hunter",

"Player Hunter",

"Uzoth",

"Spy",

"Beast Hunter",

"Shafi"

}

 

if World1 then

LC:AddDropdown({

 Name = "Select NPC",

 Default = "",

 Options = NPC1,

Flag = "Select NPC",

Save = true,

 Callback = function(Value)

  _G.SelectNPC = Value

 end

})

end

if World2 then

LC:AddDropdown({

Name = "Select NPC",

Default = "",

Options = NPC2,

Flag = "Select NPC",

Save = true,

Callback = function(Value)

_G.SelectNPC = Value

end

})

end

if World3 then

LC:AddDropdown({

Name = "Select NPC",

Default = "",

Options = NPC3,

Flag = "Select NPC",

Save = true,

Callback = function(Value)

_G.SelectNPC = Value

end

})

end

 

LC:AddToggle({

Name = "Teleport To NPC",

Default = false,

Callback = function(Value)

_G.TeleportNPC = Value

if _G.TeleportNPC == true then

repeat wait()

if _G.SelectNPC == "Dargon Berath" then

topos(CFrame.new(703.372986, 186.985519, 654.522034, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Mtsterious Man" then

topos(CFrame.new(-2574.43335, 1627.92371, -3739.35767, 0.378697902, -9.06400288e-09, 0.92552036, -8.95582009e-09, 1, 1.34578926e-08, -0.92552036, -1.33852689e-08, 0.378697902))

elseif _G.SelectNPC == "Mysterious Scientist" then

topos(CFrame.new(-6437.87793, 250.645355, -4498.92773, 0.502376854, -1.01223634e-08, -0.864648759, 2.34106086e-08, 1, 1.89508653e-09, 0.864648759, -2.11940012e-08, 0.502376854))

elseif _G.SelectNPC == "Awakening Expert" then

topos(CFrame.new(-408.098846, 16.0459061, 247.432846, 0.028394036, 6.17599138e-10, 0.999596894, -5.57905944e-09, 1, -4.59372484e-10, -0.999596894, -5.56376767e-09, 0.028394036))

elseif _G.SelectNPC == "Nerd" then

topos(CFrame.new(-401.783722, 73.0859299, 262.306702, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Bar Manager" then

topos(CFrame.new(-385.84726, 73.0458984, 316.088806, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Blox Fruits Dealer" then

topos(CFrame.new(-450.725464, 73.0458984, 355.636902, -0.780352175, -2.7266168e-08, 0.625340283, 9.78516468e-09, 1, 5.58128797e-08, -0.625340283, 4.96727601e-08, -0.780352175))

elseif _G.SelectNPC == "Trevor" then

topos(CFrame.new(-341.498322, 331.886444, 643.024963, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Plokster" then

topos( CFrame.new(-1885.16016, 88.3838196, -1912.28723, -0.513468027, 0, 0.858108759, 0, 1, 0, -0.858108759, 0, -0.513468027))

elseif _G.SelectNPC == "Enhancement Editor" then

topos(CFrame.new(-346.820221, 72.9856339, 1194.36218, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Pirate Recruiter" then

topos(CFrame.new(-428.072998, 72.9495239, 1445.32422, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Marines Recruiter" then

topos(CFrame.new(-1349.77295, 72.9853363, -1045.12964, 0.866493046, 0, -0.499189168, 0, 1, 0, 0.499189168, 0, 0.866493046))

elseif _G.SelectNPC == "Chemist" then

topos( CFrame.new(-2777.45288, 72.9919434, -3572.25732, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Ghoul Mark" then

topos(CFrame.new(635.172546, 125.976357, 33219.832, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Cyborg" then

topos(CFrame.new(629.146851, 312.307373, -531.624146, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Guashiem" then

topos(CFrame.new(937.953003, 181.083359, 33277.9297, 1, -8.60126406e-08, 3.81773896e-17, 8.60126406e-08, 1, -1.89969598e-16, -3.8177373e-17, 1.89969598e-16, 1))

elseif _G.SelectNPC == "El Admin" then

topos(CFrame.new(1322.80835, 126.345039, 33135.8789, 0.988783717, -8.69797603e-08, -0.149354503, 8.62223786e-08, 1, -1.15461916e-08, 0.149354503, -1.46101409e-09, 0.988783717))

elseif _G.SelectNPC == "El Rodolfo" then

topos(CFrame.new(941.228699, 40.4686775, 32778.9922, -0.818029106, -1.19524382e-08, 0.575176775, -1.28741648e-08, 1, 2.47053866e-09, -0.575176775, -5.38394795e-09, -0.818029106))

elseif _G.SelectNPC == "Arowe" then

topos(CFrame.new(-1994.51038, 125.519142, -72.2622986, -0.16715166, -6.55417338e-08, -0.985931218, -7.13315558e-08, 1, -5.43836585e-08, 0.985931218, 6.12376851e-08, -0.16715166))

elseif _G.SelectNPC == "Random Devil Fruit" then

topos(CFrame.new(-1436.19727, 61.8777695, 4.75247526, -0.557794094, 2.74216543e-08, 0.829979479, 5.83273234e-08, 1, 6.16037932e-09, -0.829979479, 5.18467118e-08, -0.557794094))

elseif _G.SelectNPC == "Blox Fruits Dealer" then

topos(CFrame.new(-923.255066, 7.67800522, 1608.61011, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Remove Devil Fruit" then

topos(CFrame.new(5664.80469, 64.677681, 867.85907, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Ability Teacher" then

topos(CFrame.new(-1057.67822, 9.65220833, 1799.49146, -0.865874112, -9.26330159e-08, 0.500262439, -7.33759435e-08, 1, 5.816689e-08, -0.500262439, 1.36579752e-08, -0.865874112))

elseif _G.SelectNPC == "Dark Step" then

topos( CFrame.new(-987.873047, 13.7778397, 3989.4978, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Electro" then

topos(CFrame.new(-5389.49561, 13.283, -2149.80151, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Fishman Karate" then

topos( CFrame.new(61581.8047, 18.8965912, 987.832703, 1, 0, 0, 0, 1, 0, 0, 0, 1))

elseif _G.SelectNPC == "Random Devil Fruit" then

topos(CFrame.new(-12491, 337, -7449))

elseif _G.SelectNPC == "Blox Fruits Dealer" then

topos(CFrame.new(-12511, 337, -7448))

elseif _G.SelectNPC == "Remove Devil Fruit" then

topos(CFrame.new(-5571, 1089, -2661))

elseif _G.SelectNPC == "Horned Man" then

topos(CFrame.new(-11890, 931, -8760))

elseif _G.SelectNPC == "Hungey Man" then

topos(CFrame.new(-10919, 624, -10268))

elseif _G.SelectNPC == "Previous Hero" then

topos(CFrame.new(-10368, 332, -10128))

elseif _G.SelectNPC == "Butler" then

topos(CFrame.new(-5125, 316, -3130))

elseif _G.SelectNPC == "Lunoven" then

topos(CFrame.new(-5117, 316, -3093))

elseif _G.SelectNPC == "Elite Hunter" then

topos(CFrame.new(-5420, 314, -2828))

elseif _G.SelectNPC == "Player Hunter" then

topos(CFrame.new(-5559, 314, -2840))

elseif _G.SelectNPC == "Uzoth" then

topos(CFrame.new(-9785, 852, 6667))

elseif _G.SelectNPC == "Spy" then

topos(CFrame.new(-16467.9727, 527.77948, 537.789185, -0.0820864514, -8.05455471e-08, 0.996625185, 7.25887404e-08, 1, 8.67970158e-08, -0.996625185, 7.94686343e-08, -0.0820864514))

elseif _G.SelectNPC == "Beast Hunter" then

topos(CFrame.new(-16283.6279, 72.7846222, 261.499695, 0.997676075, 8.0908265e-08, 0.0681359023, -7.95997366e-08, 1, -2.19196554e-08, -0.0681359023, 1.64451155e-08, 0.997676075))

elseif _G.SelectNPC == "Shafi" then

topos(CFrame.new(-16516.3965, 23.1659603, -190.191513, -0.978645384, 2.56767185e-09, -0.205555975, 8.21029023e-10, 1, 8.58245919e-09, 0.205555975, 8.23041635e-09, -0.978645384))

end

until not _G.TeleportNPC

end

StopTween(_G.TeleportNPC)

end

})

 

local Section = LC:AddSection({

Name = "Teleport SeSeabeast"

})

 

LC:AddToggle({

Name = "Teleport to Seabeast",

Default = false,

Flag = "Teleport to Seabeast",

Save = true,

Callback = function(Value)

for i,v in pairs(game:GetService("Workspace").SeaBeasts:GetChildren()) do

if v:FindFirstChild("HumanoidRootPart") then

topos(v.HumanoidRootPart.CFrame*CFrame.new(0,100,0))

end

end

end

})

 

local Section = LC:AddSection({

Name = "Teleport Mirrage"

})

 

LC:AddButton({

Name = "Revome Frog",

Callback = function()

game:GetService("Lighting").LightingLayers:Destroy()

game:GetService("Lighting").Sky:Destroy()

end

})

 

LC:AddToggle({

Name = "Teleport To Mirage Island",

Default = false,

Flag = "Teleport to Mirage",

Save = true,

Callback = function(Value)

_G.AutoMysticIsland = Value

StopTween(_G.AutoMysticIsland)

end

})

 

local Section = LC:AddSection({

Name = "Players"

})

 

spawn(function()

while wait() do

pcall(function()

for i,v in pairs(game:GetService("Players"):GetPlayers()) do

if i == 12 then

plyserv:Set("Players :".." "..i.." ".."/".." ".."12".." ".."(Max)")

elseif i == 1 then

plyserv:Set("Player :".." "..i.." ".."/".." ".."12")

else

plyserv:Set("Players :".." "..i.." ".."/".." ".."12")

end

end

end)

end

end)

 

Playerslist = {}

 

for i,v in pairs(game:GetService("Players"):GetChildren()) do

table.insert(Playerslist,v.Name)

end

 

local SelectedPly = LC:AddDropdown({

Name = "Select Players",

Default = "",

Options = Playerslist,

Callback = function(Value)

_G.SelectPly = Value

end

})

 

LC:AddButton({

Name = "Refresh Players",

Callback = function()

NewPlayerList = {}

for i,v in pairs(game.Players:GetChildren()) do

table.insert(Playerslist ,v.Name)

end

SelectedPly:Refresh(NewPlayerList)

end

})

 

LC:AddToggle({

Name = "Teleport To Players",

Default = false,

Callback = function(Value)

_G.TeleportPly = Value

pcall(function()

if _G.TeleportPly then

repeat topos(game:GetService("Players")[_G.SelectPly].Character.HumanoidRootPart.CFrame) wait() until _G.TeleportPly == false

end

StopTween(_G.TeleportPly)

end)

end

})

 

 

LC:AddToggle({

Name = "Auto Kill Players",

Default = false,

Callback = function(Value)

_G.Auto_Kill_Ply = Value

StopTween(_G.Auto_Kill_Ply)

end

})

 

local Section = LC:AddSection({

Name = "AimBot"

})

 

LC:AddToggle({

Name = "AimBot",

Default = false,

Callback = function(Value)

_G.Aimbot_Gun = Value

_G.Aimbot_Skill = Value

 

end

})

 

 

 

LC:AddToggle({

Name = "Aimbot Skill Nearest",

Default = false,

Flag = "Aimbot Skill Nearest",

Save = true,

Callback = function(Value)

AimSkillNearest = Value

end

})

 

local Section = Wld:AddSection({

Name = "World Menu"

})

 

Wld:AddButton({

Name = "Old World",

Callback = function()

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelMain")

end

})

 

Wld:AddButton({

Name = "Second World",

Callback = function()

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")

end

})

 

Wld:AddButton({

Name = "Third World",

Callback = function()

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")

end

})

 

local Section = SV:AddSection({

Name = "FullMoon Check"

})

 

local FM = SV:AddLabel("Server Time : " .. function8() .. " | ".. CheckMoon() .. " | " .. function7())

 

spawn(function()

while wait() do

SV:Set("Server Time : " .. function8() .. " | ".. CheckMoon() .. " | " .. function7())

end

end)

 

local Section = SV:AddSection({

Name = "Anclient One Check"

})

 

local bL = SV:AddLabel("Anclient One Status : " .. tostring(CheckAcientOneStatus()))

 

local Section = SV:AddSection({

Name = "Elite Check"

})

 

local Elite_Hunter_Status = SV:AddLabel("Only Third Sea")

 

 

spawn(function()

while wait() do

pcall(function()

if game:GetService("ReplicatedStorage"):FindFirstChild("Diablo") or game:GetService("ReplicatedStorage"):FindFirstChild("Deandre") or game:GetService("ReplicatedStorage"):FindFirstChild("Urban") or game:GetService("Workspace").Enemies:FindFirstChild("Diablo") or game:GetService("Workspace").Enemies:FindFirstChild("Deandre") or game:GetService("Workspace").Enemies:FindFirstChild("Urban") then

Elite_Hunter_Status:Set("Elite : âœ… Spawn") 

else

Elite_Hunter_Status:Set("Elite : âŒ not Spawn") 

end

end)

end

end)

 

local Section = SV:AddSection({

Name = "Elite Hunter"

})

 

local EliteProgress = SV:AddLabel("")

 

spawn(function()

pcall(function()

while wait() do

EliteProgress:Set("Elite Progress : "..game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter","Progress"))

end

end)

end)

 

local Section = SV:AddSection({

Name = "Mirage Check"

})

 

if World3 then

spawn(function()

pcall(function()

while wait() do

if game.Workspace._WorldOrigin.Locations:FindFirstChild('Mirage Island') then

Mirragecheck:Set('Mirrage: âœ…')

else

Mirragecheck:Set('Mirrage: âŒ ' )end

end

end)

end)

<p style="margin-top:0pt;
