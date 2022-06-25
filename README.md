local placeId = game.PlaceId
if placeId == 2753915549 then
   FirstSea = true
elseif placeId == 4442272183 then
   SecondSea = true
elseif placeId == 7449423635 then
   ThirdSea = true
else
    game:GetService("Players").LocalPlayer:Kick("Script for Blox Fruits only!")
end


function CheckQuest() 
    MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value
    if FirstSea then
        if MyLevel == 1 or MyLevel <= 9 then
            Mon = "Bandit [Lv. 5]"
            LevelQuest = 1
            NameQuest = "BanditQuest1"
            NameMon = "Bandit"
            CFrameMon = CFrame.new(1184.6668701172, 66.851402282715, 1513.2677001953)
            CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
        elseif MyLevel == 10 or MyLevel <= 14 then
            Mon = "Monkey [Lv. 14]"
            LevelQuest = 1
            NameQuest = "JungleQuest"
            NameMon = "Monkey"
            CFrameMon = CFrame.new(-1606.4381103516, 35.292171478271, 171.13681030273)
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
        elseif MyLevel == 15 or MyLevel <= 29 then
            Mon = "Gorilla [Lv. 20]"
            LevelQuest = 2
            NameQuest = "JungleQuest"
            NameMon = "Gorilla"
            CFrameMon = CFrame.new(-1155.7474365234, 13.141628265381, -546.68371582031)
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
        elseif MyLevel == 30 or MyLevel <= 39 then
            Mon = "Pirate [Lv. 35]"
            LevelQuest = 1
            NameQuest = "BuggyQuest1"
            NameMon = "Pirate"
            CFrameMon = CFrame.new(-1157.0579833984, 47.273414611816, 3970.0051269531)
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
        elseif MyLevel == 40 or MyLevel <= 59 then
            Mon = "Brute [Lv. 45]"
            LevelQuest = 2
            NameQuest = "BuggyQuest1"
            NameMon = "Brute"
            CFrameMon = CFrame.new(-1136.0251464844, 86.027862548828, 4303.5830078125)
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
        elseif MyLevel == 60 or MyLevel <= 74 then
            Mon = "Desert Bandit [Lv. 60]"
            LevelQuest = 1
            NameQuest = "DesertQuest"
            NameMon = "Desert Bandit"
            CFrameMon = CFrame.new(898.62774658203, 6.4384622573853, 4407.58203125)
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
        elseif MyLevel == 75 or MyLevel <= 89 then
            Mon = "Desert Officer [Lv. 70]"
            LevelQuest = 2
            NameQuest = "DesertQuest"
            NameMon = "Desert Officer"
            CFrameMon = CFrame.new(1537.9205322266, 14.452037811279, 4386.3881835938)
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
        elseif MyLevel == 90 or MyLevel <= 99 then
            Mon = "Snow Bandit [Lv. 90]"
            LevelQuest = 1
            NameQuest = "SnowQuest"
            NameMon = "Snow Bandit"
            CFrameMon = CFrame.new(1379.6555175781, 87.272789001465, -1354.8793945313)
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
        elseif MyLevel == 100 or MyLevel <= 119 then
            Mon = "Snowman [Lv. 100]"
            LevelQuest = 2
            NameQuest = "SnowQuest"
            NameMon = "Snowman"
            CFrameMon = CFrame.new(1296.3176269531, 105.77800750732, -1586.8228759766)
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
        elseif MyLevel == 120 or MyLevel <= 149 then
            Mon = "Chief Petty Officer [Lv. 120]"
            LevelQuest = 1
            NameQuest = "MarineQuest2"
            NameMon = "Chief Petty Officer"
            CFrameMon = CFrame.new(-4926.9541015625, 20.652038574219, 4254.30859375)
            CFrameQuest = CFrame.new(-5039.58643, 27.3500385, 4324.68018, 0, 0, -1, 0, 1, 0, 1, 0, 0)
        elseif MyLevel == 150 or MyLevel <= 174 then
            Mon = "Sky Bandit [Lv. 150]"
            LevelQuest = 1
            NameQuest = "SkyQuest"
            NameMon = "Sky Bandit"
            CFrameMon = CFrame.new(-5035.4375, 278.06744384766, -2845.1437988281)
            CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
        elseif MyLevel == 175 or MyLevel <= 224 then
            Mon = "Dark Master [Lv. 175]"
            LevelQuest = 2
            NameQuest = "SkyQuest"
            NameMon = "Dark Master"
            CFrameMon = CFrame.new(-5252.2421875, 388.65203857422, -2273.1125488281)
            CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
        elseif MyLevel == 225 or MyLevel <= 274 then
            Mon = "Toga Warrior [Lv. 225]"
            LevelQuest = 1
            NameQuest = "ColosseumQuest"
            NameMon = "Toga Warrior"
            CFrameMon = CFrame.new(-1951.6307373047, 7.2890739440918, -2795.9350585938)
            CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
        elseif MyLevel == 275 or MyLevel <= 299 then
            Mon = "Gladiator [Lv. 275]"
            LevelQuest = 2
            NameQuest = "ColosseumQuest"
            NameMon = "Gladiator"
            CFrameMon = CFrame.new(-1361.2359619141, 7.4425468444824, -3206.2006835938)
            CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
        elseif MyLevel == 300 or MyLevel <= 329 then
            Mon = "Military Soldier [Lv. 300]"
            LevelQuest = 1
            NameQuest = "MagmaQuest"
            NameMon = "Military Soldier"
            CFrameMon = CFrame.new(-5425.244140625, 10.298267364502, 8442.607421875)
            CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
        elseif MyLevel == 330 or MyLevel <= 449 then
            Mon = "Military Spy [Lv. 330]"
            LevelQuest = 2
            NameQuest = "MagmaQuest"
            NameMon = "Military Spy"
            CFrameMon = CFrame.new(-5808.0297851563, 82.834617614746, 8825.5166015625)
            CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
        elseif MyLevel == 450 or MyLevel <= 474 then
            Mon = "God's Guard [Lv. 450]"
            LevelQuest = 1
            NameQuest = "SkyExp1Quest"
            NameMon = "God's Guard"
            CFrameMon = CFrame.new(-4681.8432617188, 845.27716064453, -1955.4534912109)
            CFrameQuest = CFrame.new(-4721.88867, 843.874695, -1949.96643, 0.996191859, -0, -0.0871884301, 0, 1, -0, 0.0871884301, 0, 0.996191859)
        elseif MyLevel == 475 or MyLevel <= 524 then
            Mon = "Shanda [Lv. 475]"
            LevelQuest = 2
            NameQuest = "SkyExp1Quest"
            NameMon = "Shanda"
            CFrameMon = CFrame.new(-7656.3056640625, 5545.4931640625, -531.23907470703)
            CFrameQuest = CFrame.new(-7859.09814, 5544.19043, -381.476196, -0.422592998, 0, 0.906319618, 0, 1, 0, -0.906319618, 0, -0.422592998)
        elseif MyLevel == 525 or MyLevel <= 549 then
            Mon = "Royal Squad [Lv. 525]"
            LevelQuest = 1
            NameQuest = "SkyExp2Quest"
            NameMon = "Royal Squad"
            CFrameMon = CFrame.new(-7722.328125, 5610.9272460938, -1441.6092529297)
            CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
        elseif MyLevel == 550 or MyLevel <= 624 then
            Mon = "Royal Soldier [Lv. 550]"
            LevelQuest = 2
            NameQuest = "SkyExp2Quest"
            NameMon = "Royal Soldier"
            CFrameMon = CFrame.new(-7825.0087890625, 5606.8784179688, -1731.4152832031)
            CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
        elseif MyLevel == 625 or MyLevel <= 649 then
            Mon = "Galley Pirate [Lv. 625]"
            LevelQuest = 1
            NameQuest = "FountainQuest"
            NameMon = "Galley Pirate"
            CFrameMon = CFrame.new(5379.8198242188, 38.501140594482, 4033.5905761719)
            CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
        elseif MyLevel >= 650 then
            Mon = "Galley Captain [Lv. 650]"
            LevelQuest = 2
            NameQuest = "FountainQuest"
            NameMon = "Galley Captain"
            CFrameMon = CFrame.new(5556.1420898438, 113.47412109375, 4819.0576171875)
            CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
        end
    elseif SecondSea then
        if MyLevel == 700 or MyLevel <= 724 then
            Mon = "Raider [Lv. 700]"
            LevelQuest = 1
            NameQuest = "Area1Quest"
            NameMon = "Raider"
            CFrameMon = CFrame.new(-122.82179260254, 39.079746246338, 2362.2602539063)
            CFrameQuest = CFrame.new(-429.543518, 71.7699966, 1836.18188, -0.22495985, 0, -0.974368095, 0, 1, 0, 0.974368095, 0, -0.22495985)
        elseif MyLevel == 725 or MyLevel <= 774 then
            Mon = "Mercenary [Lv. 725]"
            LevelQuest = 2
            NameQuest = "Area1Quest"
            NameMon = "Mercenary"
            CFrameMon = CFrame.new(-942.66076660156, 72.959716796875, 1720.8294677734)
            CFrameQuest = CFrame.new(-429.543518, 71.7699966, 1836.18188, -0.22495985, 0, -0.974368095, 0, 1, 0, 0.974368095, 0, -0.22495985)
        elseif MyLevel == 775 or MyLevel <= 799 then
            Mon = "Swan Pirate [Lv. 775]"
            LevelQuest = 1
            NameQuest = "Area2Quest"
            NameMon = "Swan Pirate"
            CFrameMon = CFrame.new(1024.1345214844, 73.029739379883, 1262.7456054688)
            CFrameQuest = CFrame.new(638.43811, 71.769989, 918.282898, 0.139203906, 0, 0.99026376, 0, 1, 0, -0.99026376, 0, 0.139203906)
        elseif MyLevel == 800 or MyLevel <= 874 then
            Mon = "Factory Staff [Lv. 800]"
            NameQuest = "Area2Quest"
            LevelQuest = 2
            NameMon = "Factory Staff"
            CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
            CFrameMon = CFrame.new(296.786499, 72.9948196, -57.1298141, -0.876037002, -5.32364979e-08, 0.482243896, -3.87658332e-08, 1, 3.99718729e-08, -0.482243896, 1.63222538e-08, -0.876037002)
        elseif MyLevel == 875 or MyLevel <= 899 then
            Mon = "Marine Lieutenant [Lv. 875]"
            LevelQuest = 1
            NameQuest = "MarineQuest3"
            NameMon = "Marine Lieutenant"
            CFrameMon = CFrame.new(-2842.595703125, 72.96614074707, -3012.0222167969)
            CFrameQuest = CFrame.new(-2440.79639, 71.7140732, -3216.06812, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
        elseif MyLevel == 900 or MyLevel <= 949 then
            Mon = "Marine Captain [Lv. 900]"
            LevelQuest = 2
            NameQuest = "MarineQuest3"
            NameMon = "Marine Captain"
            CFrameMon = CFrame.new(-1927.8619384766, 72.96614074707, -3385.0322265625)
            CFrameQuest = CFrame.new(-2440.79639, 71.7140732, -3216.06812, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
        elseif MyLevel == 950 or MyLevel <= 974 then
            Mon = "Zombie [Lv. 950]"
            LevelQuest = 1
            NameQuest = "ZombieQuest"
            NameMon = "Zombie"
            CFrameMon = CFrame.new(-5685.9233398438, 48.480125427246, -853.23724365234)
            CFrameQuest = CFrame.new(-5497.06152, 47.5923004, -795.237061, -0.29242146, 0, -0.95628953, 0, 1, 0, 0.95628953, 0, -0.29242146)
        elseif MyLevel == 975 or MyLevel <= 999 then
            Mon = "Vampire [Lv. 975]"
            LevelQuest = 2
            NameQuest = "ZombieQuest"
            NameMon = "Vampire"
            CFrameMon = CFrame.new(-6018.3452148438, 6.4027013778687, -1267.6065673828)
            CFrameQuest = CFrame.new(-5497.06152, 47.5923004, -795.237061, -0.29242146, 0, -0.95628953, 0, 1, 0, 0.95628953, 0, -0.29242146)
        elseif MyLevel == 1000 or MyLevel <= 1049 then
            Mon = "Snow Trooper [Lv. 1000]"
            LevelQuest = 1
            NameQuest = "SnowMountainQuest"
            NameMon = "Snow Trooper"
            CFrameMon = CFrame.new(481.48031616211, 401.42202758789, -5361.2138671875)
            CFrameQuest = CFrame.new(609.858826, 400.119904, -5372.25928, -0.374604106, 0, 0.92718488, 0, 1, 0, -0.92718488, 0, -0.374604106)
        elseif MyLevel == 1050 or MyLevel <= 1099 then
            Mon = "Winter Warrior [Lv. 1050]"
            LevelQuest = 2
            NameQuest = "SnowMountainQuest"
            NameMon = "Winter Warrior"
            CFrameMon = CFrame.new(1148.3015136719, 429.38235473633, -5262.1708984375)
            CFrameQuest = CFrame.new(609.858826, 400.119904, -5372.25928, -0.374604106, 0, 0.92718488, 0, 1, 0, -0.92718488, 0, -0.374604106)
        elseif MyLevel == 1100 or MyLevel <= 1124 then
            Mon = "Lab Subordinate [Lv. 1100]"
            LevelQuest = 1
            NameQuest = "IceSideQuest"
            NameMon = "Lab Subordinate"
            CFrameMon = CFrame.new(-5775.5200195313, 42.301044464111, -4483.5092773438)
            CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
        elseif MyLevel == 1125 or MyLevel <= 1174 then
            Mon = "Horned Warrior [Lv. 1125]"
            LevelQuest = 2
            NameQuest = "IceSideQuest"
            NameMon = "Horned Warrior"
            CFrameMon = CFrame.new(-6283.5942382813, 18.321973800659, -5606.4282226563)
            CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
        elseif MyLevel == 1175 or MyLevel <= 1199 then
            Mon = "Magma Ninja [Lv. 1175]"
            LevelQuest = 1
            NameQuest = "FireSideQuest"
            NameMon = "Magma Ninja"
            CFrameMon = CFrame.new(-5686.64453125, 15.951762199402, -5713.7026367188)
            CFrameQuest = CFrame.new(-5428.03174, 15.0622921, -5299.43457, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)
        elseif MyLevel == 1200 or MyLevel <= 1349 then
            Mon = "Lava Pirate [Lv. 1200]"
            LevelQuest = 2
            NameQuest = "FireSideQuest"
            NameMon = "Lava Pirate"
            CFrameMon = CFrame.new(-5427.345703125, 67.961860656738, -4694.3706054688)
            CFrameQuest = CFrame.new(-5428.03174, 15.0622921, -5299.43457, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)
        elseif MyLevel == 1350 or MyLevel <= 1374 then
            Mon = "Arctic Warrior [Lv. 1350]"
            LevelQuest = 1
            NameQuest = "FrostQuest"
            NameMon = "Arctic Warrior"
            CFrameMon = CFrame.new(6009.58203125, 28.367122650146, -6247.9741210938)
            CFrameQuest = CFrame.new(5667.6582, 26.7997818, -6486.08984, -0.933587909, 0, -0.358349502, 0, 1, 0, 0.358349502, 0, -0.933587909)
        elseif MyLevel == 1375 or MyLevel <= 1424 then
            Mon = "Snow Lurker [Lv. 1375]"
            LevelQuest = 2
            NameQuest = "FrostQuest"
            NameMon = "Snow Lurker"
            CFrameMon = CFrame.new(5476.5615234375, 28.82799911499, -6847.412109375)
            CFrameQuest = CFrame.new(5667.6582, 26.7997818, -6486.08984, -0.933587909, 0, -0.358349502, 0, 1, 0, 0.358349502, 0, -0.933587909)
        elseif MyLevel == 1425 or MyLevel <= 1449 then
            Mon = "Sea Soldier [Lv. 1425]"
            LevelQuest = 1
            NameQuest = "ForgottenQuest"
            NameMon = "Sea Soldier"
            CFrameMon = CFrame.new(-3032.2255859375, 70.041687011719, -9779.5869140625)
            CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)
        elseif MyLevel >= 1450 then
            Mon = "Water Fighter [Lv. 1450]"
            LevelQuest = 2
            NameQuest = "ForgottenQuest"
            NameMon = "Water Fighter"
            CFrameMon = CFrame.new(-3261.4780273438, 291.33917236328, -10596.365234375)
            CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)
        end
    elseif ThirdSea then
        if MyLevel == 1500 or MyLevel <= 1524 then
            Mon = "Pirate Millionaire [Lv. 1500]"
            LevelQuest = 1
            NameQuest = "PiratePortQuest"
            NameMon = "Pirate Millionaire"
            CFrameMon = CFrame.new(-366.55215454102, 68.321365356445, 5561.5541992188)
            CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
        elseif MyLevel == 1525 or MyLevel <= 1574 then
            Mon = "Pistol Billionaire [Lv. 1525]"
            LevelQuest = 2
            NameQuest = "PiratePortQuest"
            NameMon = "Pistol Billionaire"
            CFrameMon = CFrame.new(-413.86712646484, 123.34642028809, 5857.123046875)
            CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
        elseif MyLevel == 1575 or MyLevel <= 1599 then
            Mon = "Dragon Crew Warrior [Lv. 1575]"
            LevelQuest = 1
            NameQuest = "AmazonQuest"
            NameMon = "Dragon Crew Warrior"
            CFrameMon = CFrame.new(6297.5546875, 108.10154724121, -1078.3551025391)
            CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563, 0.898790359, -0, -0.438378751, 0, 1, -0, 0.438378751, 0, 0.898790359)
         elseif MyLevel == 1600 or MyLevel <= 1624 then 
            Mon = "Dragon Crew Archer [Lv. 1600]"
            NameQuest = "AmazonQuest"
            LevelQuest = 2
            NameMon = "Dragon Crew Archer"
            CFrameQuest = CFrame.new(5833.1147460938, 51.60498046875, -1103.0693359375)
            CFrameMon = CFrame.new(6831.1171875, 441.76708984375, 446.58615112305)
         elseif MyLevel == 1625 or MyLevel <= 1649 then
            Mon = "Female Islander [Lv. 1625]"
            NameQuest = "AmazonQuest2"
            LevelQuest = 1
            NameMon = "Female Islander"
            CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
            CFrameMon = CFrame.new(5792.5166015625, 848.14392089844, 1084.1818847656)
         elseif MyLevel == 1650 or MyLevel <= 1699 then 
            Mon = "Giant Islander [Lv. 1650]"
            NameQuest = "AmazonQuest2"
            LevelQuest = 2
            NameMon = "Giant Islander"
            CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
            CFrameMon = CFrame.new(5009.5068359375, 664.11071777344, -40.960144042969)
        elseif MyLevel == 1700 or MyLevel <= 1724 then
            Mon = "Marine Commodore [Lv. 1700]"
            LevelQuest = 1
            NameQuest = "MarineTreeIsland"
            NameMon = "Marine Commodore"
            CFrameMon = CFrame.new(2335.4865722656, 190.39758300781, -7183.552734375)
            CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498, -0.965929747, 0, 0.258804798, 0, 1, 0, -0.258804798, 0, -0.965929747)
         elseif MyLevel == 1725 or MyLevel <= 1774 then
            Mon = "Marine Rear Admiral [Lv. 1725]"
            NameMon = "Marine Rear Admiral"
            NameQuest = "MarineTreeIsland"
            LevelQuest = 2
            CFrameQuest = CFrame.new(2179.98828125, 28.731239318848, -6740.0551757813)
            CFrameMon = CFrame.new(3294.3142089844, 385.41125488281, -7048.6342773438)
        elseif MyLevel == 1775 or MyLevel <= 1799 then
            Mon = "Fishman Raider [Lv. 1775]"
            LevelQuest = 1
            NameQuest = "DeepForestIsland3"
            NameMon = "Fishman Raider"
            CFrameMon = CFrame.new(-10310.296875, 426.3200378418, -8592.0048828125)
            CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)   
        elseif MyLevel == 1800 or MyLevel <= 1824 then
            Mon = "Fishman Captain [Lv. 1800]"
            LevelQuest = 2
            NameQuest = "DeepForestIsland3"
            NameMon = "Fishman Captain"
            CFrameMon = CFrame.new(-10728.3046875, 397.76626586914, -9079.86328125)
            CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)   
        elseif MyLevel == 1825 or MyLevel <= 1849 then
            Mon = "Forest Pirate [Lv. 1825]"
            LevelQuest = 1
            NameQuest = "DeepForestIsland"
            NameMon = "Forest Pirate"
            CFrameMon = CFrame.new(-13265.977539063, 428.16796875, -7758.57421875)
            CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)
        elseif MyLevel == 1850 or MyLevel <= 1899 then
            Mon = "Mythological Pirate [Lv. 1850]"
            LevelQuest = 2
            NameQuest = "DeepForestIsland"
            NameMon = "Mythological Pirate"
            CFrameMon = CFrame.new(-13392.751953125, 622.6171875, -7082.2348632813)
            CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)   
        elseif MyLevel == 1900 or MyLevel <= 1924 then
            Mon = "Jungle Pirate [Lv. 1900]"
            LevelQuest = 1
            NameQuest = "DeepForestIsland2"
            NameMon = "Jungle Pirate"
            CFrameMon = CFrame.new(-11997.963867188, 431.92016601563, -10300.259765625)
            CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)
        elseif MyLevel == 1925 or MyLevel <= 1974 then
            Mon = "Musketeer Pirate [Lv. 1925]"
            LevelQuest = 2
            NameQuest = "DeepForestIsland2"
            NameMon = "Musketeer Pirate"
            CFrameMon = CFrame.new(-13293.668945313, 496.21118164063, -9573.9326171875)
            CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)
        elseif MyLevel == 1975 or MyLevel <= 1999 then
            Mon = "Reborn Skeleton [Lv. 1975]"
            LevelQuest = 1
            NameQuest = "HauntedQuest1"
            NameMon = "Reborn Skeleton"
            CFrameMon = CFrame.new(-8767.4658203125, 184.68771362305, 6228.1762695313)
            CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
        elseif MyLevel == 2000 or MyLevel <= 2024 then
            Mon = "Living Zombie [Lv. 2000]"
            LevelQuest = 2
            NameQuest = "HauntedQuest1"
            NameMon = "Living Zombie"
            CFrameMon = CFrame.new(-10146.403320313, 139.62678527832, 5987.4208984375)
            CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
        elseif MyLevel == 2025 or MyLevel <= 2049 then
            Mon = "Demonic Soul [Lv. 2025]"
            LevelQuest = 1
            NameQuest = "HauntedQuest2"
            NameMon = "Demonic Soul"
            CFrameMon = CFrame.new(-9365.5595703125, 222.10494995117, 6231.1879882813)
            CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0) 
        elseif MyLevel == 2050 or MyLevel <= 2074 then
             Mon = "Posessed Mummy [Lv. 2050]"
             LevelQuest = 2
             NameQuest = "HauntedQuest2"
             NameMon = "Posessed Mummy"
             CFrameMon = CFrame.new(-9556.00488, 66.3880768, 6370.78076, 0.999951124, 3.36073747e-08, -0.00988800824, -3.39445911e-08, 1, -3.39356419e-08, 0.00988800824, 3.42696289e-08, 0.999951124)
             CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0)
        elseif MyLevel == 2075 or MyLevel <= 2099 then
            Mon = "Peanut Scout [Lv. 2075]"
            LevelQuest = 1
            NameQuest = "NutsIslandQuest"
            NameMon = "Peanut Scout"
            CFrameMon = CFrame.new(-2192.3247070312, 94.319366455078, -10092.274414062, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)
        elseif MyLevel == 2100 or MyLevel <= 2124 then
            Mon = "Peanut President [Lv. 2100]"
            LevelQuest = 2
            NameQuest = "NutsIslandQuest"
            NameMon = "Peanut President"
            CFrameMon = CFrame.new(-2120.5974121094, 124.56230163574, -10441.361328125, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)
        elseif MyLevel == 2125 or MyLevel <= 2149 then
            Mon = "Ice Cream Chef [Lv. 2125]"
            LevelQuest = 1
            NameQuest = "IceCreamIslandQuest"
            NameMon = "Ice Cream Chef"
            CFrameMon = CFrame.new(-898.00366210938, 119.35078430176, -10943.458984375, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)
        elseif MyLevel >= 2150 then
            Mon = "Ice Cream Commander [Lv. 2150]"
            LevelQuest = 2
            NameQuest = "IceCreamIslandQuest"
            NameMon = "Ice Cream Commander"
            CFrameMon = CFrame.new(-514.06311035156, 172.69267272949, -11215.62890625, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)
        end
    end
end

function CheckQuestBoss()
    if _G.SelectBoss == "Diamond [Lv. 750] [Boss]" then
        MsBoss = "Diamond [Lv. 750] [Boss]"
        NameQuestBoss = "Area1Quest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-424.080078, 73.0055847, 1836.91589)
        CFrameBoss = CFrame.new(-1736.26587, 198.627731, -236.412857)
    elseif _G.SelectBoss == "Jeremy [Lv. 850] [Boss]" then
        MsBoss = "Jeremy [Lv. 850] [Boss]"
        NameQuestBoss = "Area2Quest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(632.698608, 73.1055908, 918.666321)
        CFrameBoss = CFrame.new(2203.76953, 448.966034, 752.731079)
    elseif _G.SelectBoss == "Fajita [Lv. 925] [Boss]" then
        MsBoss = "Fajita [Lv. 925] [Boss]"
        NameQuestBoss = "MarineQuest3"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-2442.65015, 73.0511475, -3219.11523)
        CFrameBoss = CFrame.new(-2297.40332, 115.449463, -3946.53833)
    elseif _G.SelectBoss == "Don Swan [Lv. 1000] [Boss]" then
        MsBoss = "Don Swan [Lv. 1000] [Boss]"
        CFrameBoss = CFrame.new(2288.802, 15.1870775, 863.034607, 0.99974072, -8.41247214e-08, -0.0227668174, 8.4774733e-08, 1, 2.75850098e-08, 0.0227668174, -2.95079072e-08, 0.99974072)
    elseif _G.SelectBoss == "Smoke Admiral [Lv. 1150] [Boss]" then
        MsBoss = "Smoke Admiral [Lv. 1150] [Boss]"
        NameQuestBoss = "IceSideQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-6059.96191, 15.9868021, -4904.7373)
        CFrameBoss = CFrame.new(-5115.72754, 23.7664986, -5338.2207)
    elseif _G.SelectBoss == "Cursed Captain [Lv. 1325] [Raid Boss]" then
        MsBoss = "Cursed Captain [Lv. 1325] [Raid Boss]"
        CFrameBoss = CFrame.new(916.928589, 181.092773, 33422)
    elseif _G.SelectBoss == "Darkbeard [Lv. 1000] [Raid Boss]" then
        MsBoss = "Darkbeard [Lv. 1000] [Raid Boss]"
        CFrameBoss = CFrame.new(3876.00366, 24.6882591, -3820.21777)
    elseif _G.SelectBoss == "Order [Lv. 1250] [Raid Boss]" then
        MsBoss = "Order [Lv. 1250] [Raid Boss]"
        CFrameBoss = CFrame.new(-6221.15039, 16.2351036, -5045.23584)
    elseif _G.SelectBoss == "Awakened Ice Admiral [Lv. 1400] [Boss]" then
        MsBoss = "Awakened Ice Admiral [Lv. 1400] [Boss]"
        NameQuestBoss = "FrostQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(5669.33203, 28.2118053, -6481.55908)
        CFrameBoss = CFrame.new(6407.33936, 340.223785, -6892.521)
    elseif _G.SelectBoss == "Tide Keeper [Lv. 1475] [Boss]" then
        MsBoss = "Tide Keeper [Lv. 1475] [Boss]"
        NameQuestBoss = "ForgottenQuest"             
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-3053.89648, 236.881363, -10148.2324)
        CFrameBoss = CFrame.new(-3570.18652, 123.328949, -11555.9072)
        -- Old World
    elseif _G.SelectBoss == "Saber Expert [Lv. 200] [Boss]" then
        MsBoss = "Saber Expert [Lv. 200] [Boss]"
        CFrameBoss = CFrame.new(-1458.89502, 29.8870335, -50.633564)
    elseif _G.SelectBoss == "The Saw [Lv. 100] [Boss]" then
        MsBoss = "The Saw [Lv. 100] [Boss]"
        CFrameBoss = CFrame.new(-683.519897, 13.8534927, 1610.87854)
    elseif _G.SelectBoss == "The Gorilla King [Lv. 25] [Boss]" then
        MsBoss = "The Gorilla King [Lv. 25] [Boss]"
        NameQuestBoss = "JungleQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-1604.12012, 36.8521118, 154.23732)
        CFrameBoss = CFrame.new(-1223.52808, 6.27936459, -502.292664)
    elseif _G.SelectBoss == "Bobby [Lv. 55] [Boss]" then
        MsBoss = "Bobby [Lv. 55] [Boss]"
        NameQuestBoss = "BuggyQuest1"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-1139.59717, 4.75205183, 3825.16211)
        CFrameBoss = CFrame.new(-1147.65173, 32.5966301, 4156.02588)
    elseif _G.SelectBoss == "Yeti [Lv. 110] [Boss]" then
        MsBoss = "Yeti [Lv. 110] [Boss]"
        NameQuestBoss = "SnowQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(1384.90247, 87.3078308, -1296.6825)
        CFrameBoss = CFrame.new(1221.7356, 138.046906, -1488.84082)
    elseif _G.SelectBoss == "Mob Leader [Lv. 120] [Boss]" then
        MsBoss = "Mob Leader [Lv. 120] [Boss]"
        CFrameBoss = CFrame.new(-2848.59399, 7.4272871, 5342.44043)
        --The Gorilla King [Lv. 25] [Boss]
    elseif _G.SelectBoss == "Vice Admiral [Lv. 130] [Boss]" then
        MsBoss = "Vice Admiral [Lv. 130] [Boss]"
        NameQuestBoss = "MarineQuest2"
        LevelQuestBoss = 2
        CFrameQuestBoss = CFrame.new(-5035.42285, 28.6520386, 4324.50293)
        CFrameBoss = CFrame.new(-5078.45898, 99.6520691, 4402.1665)
    elseif _G.SelectBoss == "Warden [Lv. 175] [Boss]" then
        MsBoss = "Warden [Lv. 175] [Boss]"
        NameQuestBoss = "ImpelQuest"
        LevelQuestBoss = 1
        CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282)
        CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897)
    elseif _G.SelectBoss == "Chief Warden [Lv. 200] [Boss]" then
        MsBoss = "Chief Warden [Lv. 200] [Boss]"
        NameQuestBoss = "ImpelQuest"
        LevelQuestBoss = 2
        CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282)
        CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897)
    elseif _G.SelectBoss == "Swan [Lv. 225] [Boss]" then
        MsBoss = "Swan [Lv. 225] [Boss]"
        NameQuestBoss = "ImpelQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282)
        CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897)
    elseif _G.SelectBoss == "Magma Admiral [Lv. 350] [Boss]" then
        MsBoss = "Magma Admiral [Lv. 350] [Boss]"
        NameQuestBoss = "MagmaQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-5317.07666, 12.2721891, 8517.41699)
        CFrameBoss = CFrame.new(-5530.12646, 22.8769703, 8859.91309)
    elseif _G.SelectBoss == "Fishman Lord [Lv. 425] [Boss]" then
        MsBoss = "Fishman Lord [Lv. 425] [Boss]"
        NameQuestBoss = "FishmanQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(61123.0859, 18.5066795, 1570.18018)
        CFrameBoss = CFrame.new(61351.7773, 31.0306778, 1113.31409)
    elseif _G.SelectBoss == "Wysper [Lv. 500] [Boss]" then
        MsBoss = "Wysper [Lv. 500] [Boss]"
        NameQuestBoss = "SkyExp1Quest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-7862.94629, 5545.52832, -379.833954)
        CFrameBoss = CFrame.new(-7925.48389, 5550.76074, -636.178345)
    elseif _G.SelectBoss == "Thunder God [Lv. 575] [Boss]" then
        MsBoss = "Thunder God [Lv. 575] [Boss]"
        NameQuestBoss = "SkyExp2Quest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-7902.78613, 5635.99902, -1411.98706)
        CFrameBoss = CFrame.new(-7917.53613, 5616.61377, -2277.78564)
    elseif _G.SelectBoss == "Cyborg [Lv. 675] [Boss]" then
        MsBoss = "Cyborg [Lv. 675] [Boss]"
        NameQuestBoss = "FountainQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(5253.54834, 38.5361786, 4050.45166)
        CFrameBoss = CFrame.new(6041.82813, 52.7112198, 3907.45142)
        --Three World
    elseif _G.SelectBoss == "Kilo Admiral [Lv. 1750] [Boss]" then
        MsBoss = "Kilo Admiral [Lv. 1750] [Boss]"
        NameQuestBoss = "MarineTreeIsland"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(2180.54126, 27.8156815, -6741.5498)
        CFrameBoss = CFrame.new(2955.1189, 423.584412, -7240.22217)
    elseif _G.SelectBoss == "Captain Elephant [Lv. 1875] [Boss]" then
        MsBoss = "Captain Elephant [Lv. 1875] [Boss]"
        NameQuestBoss = "DeepForestIsland"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-13234.04, 331.488495, -7625.40137)
        CFrameBoss = CFrame.new(-13592.9053, 332.23584, -8134.08643)
    elseif _G.SelectBoss == "Beautiful Pirate [Lv. 1950] [Boss]" then
        MsBoss = "Beautiful Pirate [Lv. 1950] [Boss]"
        NameQuestBoss = "DeepForestIsland2"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-12680.3818, 389.971039, -9902.01953)
        CFrameBoss = CFrame.new(5310.80957, 22.5622349, 129.390533)
    elseif _G.SelectBoss == "Longma [Lv. 2000] [Boss]" then
        MsBoss = "Longma [Lv. 2000] [Boss]"
        CFrameBoss = CFrame.new(-10293.208, 332.791351, -9450.625)
    elseif _G.SelectBoss == "Stone [Lv. 1550] [Boss]" then
        MsBoss = "Stone [Lv. 1550] [Boss]"
        NameQuestBoss = "PiratePortQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-290.074677, 42.9034653, 5581.58984)
        CFrameBoss = CFrame.new(-970.778564, 40.0068855, 6795.5249)
    elseif _G.SelectBoss == "Island Empress [Lv. 1675] [Boss]" then
        MsBoss = "Island Empress [Lv. 1675] [Boss]"
        NameQuestBoss = "AmazonQuest2"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(5448.86133, 601.516174, 751.130676)
        CFrameBoss = CFrame.new(5813.94140625, 661.14862060547, 202.04710388184)
    elseif _G.SelectBoss == "Cake Queen [Lv. 2175] [Boss]" then
        MsBoss = "Cake Queen [Lv. 2175]"
        NameQuestBoss = "IceCreamIslandQuest"
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438)
        CFrameBoss = CFrame.new(-724.39819335938, 381.59127807617, -10988.33203125)
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
                        name.Font = Enum.Font.Code
                        name.FontSize = "Size14"
                        name.TextWrapped = true
                        name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' M')
                        name.Size = UDim2.new(1,0,1,0)
                        name.TextYAlignment = 'Top'
                        name.BackgroundTransparency = 1
                        name.TextStrokeTransparency = 0.5
                        if v.Team == game.Players.LocalPlayer.Team then
                            name.TextColor3 = Color3.new(80,245,245)
                        else
                            name.TextColor3 = Color3.new(245,80,80)
                        end
                    else
                        v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' M')
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
                            name.Font = Enum.Font.Code
                            name.FontSize = "Size14"
                            name.TextWrapped = true
                            name.Size = UDim2.new(1,0,1,0)
                            name.TextYAlignment = 'Top'
                            name.BackgroundTransparency = 1
                            name.TextStrokeTransparency = 0.5
                            if v.Name == "Chest1" then
                                name.TextColor3 = Color3.fromRGB(192,192,192)
                                name.Text = ("Chest 1" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                            end
                            if v.Name == "Chest2" then
                                name.TextColor3 = Color3.fromRGB(255,215,0)
                                name.Text = ("Chest 2" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                            end
                            if v.Name == "Chest3" then
                                name.TextColor3 = Color3.fromRGB(85, 255, 255)
                                name.Text = ("Chest 3" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                            end
                        else
                            v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
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
                        name.Font = Enum.Font.Code
                        name.FontSize = "Size14"
                        name.TextWrapped = true
                        name.Size = UDim2.new(1,0,1,0)
                        name.TextYAlignment = 'Top'
                        name.BackgroundTransparency = 1
                        name.TextStrokeTransparency = 0.5
                        name.TextColor3 = Color3.fromRGB(255, 0, 0)
                        name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' M')
                    else
                        v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' M')
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
                        name.Font = Enum.Font.Code
                        name.FontSize = "Size14"
                        name.TextWrapped = true
                        name.Size = UDim2.new(1,0,1,0)
                        name.TextYAlignment = 'Top'
                        name.BackgroundTransparency = 1
                        name.TextStrokeTransparency = 0.5
                        name.TextColor3 = Color3.fromRGB(255, 0, 0)
                    if v.Name == "Flower1" then 
                        name.Text = ("Blue Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                        name.TextColor3 = Color3.fromRGB(0, 0, 255)
                    end
                    if v.Name == "Flower2" then
                        name.Text = ("Red Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                        name.TextColor3 = Color3.fromRGB(255, 0, 0)
                    end
                else
                v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
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
                                delfile("NotSameServers.json")
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
                        writefile("NotSameServers.json", game:GetService('HttpService'):JSONEncode(AllIDs))
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

function Tween(Para1)
    Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 170 then
        Speed = 1000
    elseif Distance < 1000 then
        Speed = 350
    elseif Distance >= 1000 then
        Speed = 250
    end
    pcall(function() 
        tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart,TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),{CFrame = Para1})
        tween:Play()
        _G.Clip = true
        if Distance <= 100 then
            tween:Cancel()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Para1
            _G.Clip = false
        end
    end)
end

function Buso()
    if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
    end
end

function EquipWeapon(ToolSe)
    if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
        Tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
        wait(.1)
        game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tool)
    end
end

spawn(function()
    pcall(function()
        while wait() do
            for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do  
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

spawn(function()
    while wait() do
        pcall(function()
            if _G.Clip or _G.AutoFarm or _G.AutoSecondSea or _G.AutoThirdSea or _G.AutoFactory or _G.AutoCandy or _G.AutoObservation or _G.EliteHunter or _G.AutoSharkman or _G.AutoElectricClaw or _G.AutoFarmBoss or _G.AutoAllBoss then
                local char = game.Players.LocalPlayer.Character
                local hm = char.HumanoidRootPart
                if not hm:FindFirstChild("BodyVelocity") then
                    local bv = Instance.new("BodyVelocity")
                    bv.Parent = hm
                    bv.MaxForce = Vector3.new(100000,100000,100000)
                    bv.Velocity = Vector3.new(0,0,0)
                end
            else
                game.Players.LocalPlayer.Character.HumanoidRootPart.BodyVelocity:Destroy()
            end
        end)
    end
end)

spawn(function()
    game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.Clip or _G.AutoFarm or _G.AutoSecondSea or _G.AutoThirdSea or _G.AutoFactory or _G.AutoCandy or _G.AutoObservation or _G.EliteHunter or _G.AutoSharkman or _G.AutoElectricClaw or _G.AutoFarmBoss or _G.AutoAllBoss then
                for _, v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
                    if v:IsA("BasePart") then
                        v.CanCollide = false    
                    end
                end
            end
        end)
    end)
end)

local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/GreenDeno/Venyx-UI-Library/main/source.lua"))()
local killer = library.new("CAP Hub | Cmmunity", 5013109572)

local themes = {
    Background = Color3.fromRGB(24, 24, 24),
    Glow = Color3.fromRGB(0, 0, 0),
    Accent = Color3.fromRGB(10, 10, 10),
    LightContrast = Color3.fromRGB(20, 20, 20),
    DarkContrast = Color3.fromRGB(14, 14, 14),  
    TextColor = Color3.fromRGB(49, 183, 255)
}

local MainPage = killer:addPage("Auto Farm",6026568198)

local SetFarm = MainPage:addSection("Auto Farm Settings")
local Main = MainPage:addSection("Auto Farm")
local Fight = MainPage:addSection("Fighting Styles")
local BossFarm = MainPage:addSection("Auto Farm Boss")
local MasFarm = MainPage:addSection("Auto Farm Mastery")

local StatPage = killer:addPage("Auto Stats",7040410130)
local Stats = StatPage:addSection("Auto Stats")

local TelepPage = killer:addPage("Teleport",6035190846)
local Teleport = TelepPage:addSection("Teleport")
local Teleport1 = TelepPage:addSection("Island")

local RaidPage = killer:addPage("Dungeon",7251993295)
local Raid = RaidPage:addSection("Raid")

local DevilPage = killer:addPage("Devil Fruits",7044233235)
local Devil = DevilPage:addSection("Devil Fruits")

local ShopPage = killer:addPage("Shop",6031265976)
local Shop = ShopPage:addSection("Fighting Styles")
local Shop1 = ShopPage:addSection("Ablilities")
local Shop2 = ShopPage:addSection("Accessory")
local Shop3 = ShopPage:addSection("Sword")
local Shop4 = ShopPage:addSection("Gun")
local Shop5 = ShopPage:addSection("Candies")
local Shop6 = ShopPage:addSection("Bones")

local MiscPage = killer:addPage("Misc",6034509993)
local Server = MiscPage:addSection("Server")
local UI = MiscPage:addSection("UI")
local Team = MiscPage:addSection("Teams")
local Codes = MiscPage:addSection("Code")
local ESP = MiscPage:addSection("ESP")

local theme = killer:addPage("Theme", 5012544693)
local colors = theme:addSection("Settings")

SetFarm:addSlider("Lock at Level",0,1,2200,function(value)
    LevelLock = value
end)

SetFarm:addToggle("Start Lock Level",_G.StartLock,function(value)
    _G.StartLock = value
    while _G.StartLock do wait()
        if game.Players.LocalPlayer.Data.Level.Value >= LevelLock then
           game.Players.LocalPlayer:Kick("Completed Lock Level") 
        end
    end
end)

_G.FastAttack = true
SetFarm:addToggle("Fast Attack",_G.FastAttack,function(value)
    _G.FastAttack = value
end)

local CombatFrameworkR = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
local CameraShakerR = require(game.ReplicatedStorage.Util.CameraShaker)

spawn(function()
    for i=1,math.huge do
        game:GetService("RunService").Heartbeat:wait()
        if _G.FastAttack then
            pcall(function()
                CameraShakerR:Stop()
                CombatFrameworkR.activeController.attacking = false
                CombatFrameworkR.activeController.timeToNextAttack = 0
                CombatFrameworkR.activeController.increment = 3
                CombatFrameworkR.activeController.hitboxMagnitude = 80
            end)
        end
        game:GetService("RunService").Heartbeat:wait()
    end
end)

_G.SetSpawn = true
SetFarm:addToggle("Auto Set Spawn Points",_G.SetSpawn,function(value)
    _G.SetSpawn = value
end)

spawn(function()
    pcall(function()
        while wait(1) do
            if _G.SetSpawn then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
            end
        end
    end)
end)

WeaponList = {}
for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
    if v:IsA("Tool") then
        table.insert(WeaponList,v.Name)
    end
end

SetFarm:addDropdown("Select Weapon",WeaponList,function(value)
    _G.SelectWeapon = value
end)

SetFarm:addButton("Refresh Weapon",function()
    for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
        if v:IsA("Tool") then
            table.clear(WeaponList)
        end
    end
    wait(.1)
    for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
        if v:IsA("Tool") then
            table.insert(WeaponList,v.Name)
        end
    end
end)

Main:addToggle("Auto Farm Level",_G.AutoFarm,function(value)
    _G.AutoFarm = value
end)
Main:addToggle("Auto Second Sea",_G.AutoSecondSea,function(value)
    _G.AutoSecondSea = value
end)
Main:addToggle("Auto Third Sea",_G.AutoThirdSea,function(value)
    _G.AutoThirdSea = value
end)
Main:addToggle("Auto Factory",_G.AutoFactory,function(value)
    _G.AutoFactory = value
end)
Main:addToggle("Auto Farm Candy",_G.AutoCandy,function(value)
    _G.AutoCandy = value
end)
Main:addToggle("Auto Observation",_G.AutoObservation,function(value)
    _G.AutoObservation = value
end)
Main:addToggle("Auto Observation Hop",_G.AutoObservation_Hop,function(value)
    _G.AutoObservation_Hop = value
end)
Main:addToggle("Auto Elite Hunter",_G.EliteHunter,function(value)
    _G.EliteHunter = value
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
end)
Main:addToggle("Auto Elite Hunter Hop",_G.EliteHunter_Hop,function(value)
    _G.EliteHunter_Hop = value
end)

Fight:addToggle("Auto Superhuman",_G.AutoSuperhuman,function(value)
    _G.AutoSuperhuman = value
end)
Fight:addToggle("Auto Sharkman Karate",_G.AutoSharkman,function(value)
    _G.AutoSharkman = value
end)
Fight:addToggle("Auto DeathStep",_G.AutoDeathStep,function(value)
    _G.AutoDeathStep = value
end)
Fight:addToggle("Auto Electric Claw",_G.AutoElectricClaw,function(value)
    _G.AutoElectricClaw = value
end)
Fight:addToggle("Auto Dragon Talon",_G.AutoDragonTalon,function(value)
    _G.AutoDragonTalon = value
end)

spawn(function()
    while wait() do
        if _G.AutoFarm then
            pcall(function()
                CheckQuest()
                if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                    Magnet = false                                       
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                end
                if not game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible then
                    Magnet = false               
                    CheckQuest()
                    Tween(CFrameQuest)
                    if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 then
                        wait(1.1)
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NameQuest,LevelQuest)
                        wait(0.5)
                    end
                elseif game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                    CheckQuest()
                    if game:GetService("Workspace").Enemies:FindFirstChild(Mon) then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                                if v.Name == Mon then
                                    if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                                        repeat game:GetService("RunService").Heartbeat:wait()
                                            Buso()
                                            EquipWeapon(_G.SelectWeapon)
                                            PosMon = v.HumanoidRootPart.CFrame
                                            Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                            v.HumanoidRootPart.CanCollide = false
                                            v.Humanoid.WalkSpeed = 0
                                            v.Head.CanCollide = false
                                            Magnet = true
                                            game:GetService("VirtualUser"):CaptureController()
                                            game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                        until not _G.AutoFarm or v.Humanoid.Health <= 0 or not v.Parent or not game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible
                                    else                                        
                                        Magnet = false                                     
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                                    end
                                end
                            end
                        end
                    else                        
                        Magnet = false                    
                        Tween(CFrameMon)
                    end
                end
            end)
        end
    end
end)

spawn(function()
    pcall(function()
        while wait() do
            CheckQuest()
            if _G.AutoFarm then
                if (MyLevel >= 375 and MyLevel <= 449) and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
                    _G.AutoFarm = false
                    Tween(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
                    wait(.3)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                    wait(1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
                    wait(.5)
                    _G.AutoFarm = true
                end
                if (MyLevel >= 475 and MyLevel <= 624) and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then 
                    _G.AutoFarm = false
                    Tween(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
                    wait(.3)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                    wait(1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
                    wait(.5)
                    _G.AutoFarm = true
                end
                if (MyLevel >= 1250 and MyLevel <= 1349) and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
                    _G.AutoFarm = false
                    Tween(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
                    wait(.3)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                    wait(1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
                    wait(.5)
                    _G.AutoFarm = true
                end
                if (MyLevel >= 450 and MyLevel <= 474) and (CFrameQuest - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
                    _G.AutoFarm = false
                    Tween(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
                    wait(.3)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                    wait(1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(3864.6884765625, 6.7369503974915, -1926.2141113281))
                    wait(0.5)
                    _G.AutoFarm = true
                end
                if MyLevel >= 625 and (CFrameQuest - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
                    _G.AutoFarm = false
                    Tween(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
                    wait(.3)
                    game:GetService("ReplicatedStorage").Remotes.CommF:InvokeServer("AbandonQuest")
                    wait(1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.8227539062, 872.54229736328, -1667.5568847656))
                    wait(.5)
                    _G.AutoFarm = true
                end
                if (MyLevel >= 1350 and MyLevel <= 1424) and (CFrameQuest - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
                    _G.AutoFarm = false
                    Tween(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
                    wait(.3)
                    game:GetService("ReplicatedStorage").Remotes.CommF:InvokeServer("AbandonQuest")
                    wait(1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-6508.5581054688, 83.187019348145, -132.83953857422))
                    wait(.5)
                    _G.AutoFarm = true
                end
            end
        end
    end)
end)

spawn(function()
    while wait() do
        if _G.AutoSecondSea then
            local MyLevel = game.Players.LocalPlayer.Data.Level.Value
            if MyLevel >= 700 and FirstSea then
                _G.AutoFarm = false
                Tween(CFrame.new(4849.29883, 5.65138149, 719.611877))
                wait(1)
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress","Detective")
                wait(1)
                EquipWeapon("Key")
                Tween(CFrame.new(1347.7124, 37.3751602, -1325.6488))
                wait(1)
                if game.Workspace.Enemies:FindFirstChild("Ice Admiral [Lv. 700] [Boss]") and game.Workspace.Map.Ice.Door.CanCollide == false and game.Workspace.Map.Ice.Door.Transparency == 1 then
                    CheckBoss = true
                    for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                        if CheckBoss and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == "Ice Admiral [Lv. 700] [Boss]" then
                            repeat wait()
                                pcall(function() 
                                    Buso()
                                    EquipWeapon(_G.SelectWeapon)
                                    v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                                    v.HumanoidRootPart.CanCollide = false
                                    v.Humanoid.WalkSpeed = 0
                                    Tween(v.HumanoidRootPart.CFrame*CFrame.new(0,30,0)) 
                                    game:GetService("VirtualUser"):CaptureController()
                                    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                                
                                end)
                            until not CheckBoss or not v.Parent or v.Humanoid.Health <= 0
                        end
                    end        
                    CheckBoss = false
                    wait(1)
                    Tween(CFrame.new(1166.23743, 7.65220165, 1728.36487))
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
                else
                    EquipWeapon("Key")
                    Tween(CFrame.new(1347.7124, 37.3751602, -1325.6488))
                end 
            end
        end 
    end
end)

spawn(function()
    while wait() do
        if _G.AutoThirdSea then
            pcall(function()
                if game:GetService("Players").LocalPlayer.Data.Level.Value >= 1500 and SecondSea then
                    if _G.AutoFarm then
                        _G.AutoFarm = false
                    end                
                    Tween(CFrame.new(-1926.3221435547, 12.819851875305, 1738.3092041016))
                    wait(1.1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ZQuestProgress","Begin")
                    wait(1.1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")
                    Tween(CFrame.new(-26880.93359375, 22.848554611206, 473.18951416016))
                    if game:GetService("Workspace").Enemies:FindFirstChild("rip_indra [Lv. 1500] [Boss]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "rip_indra [Lv. 1500] [Boss]" then
                                repeat wait()
                                    pcall(function()
                                        Buso()
                                        EquipWeapon(_G.SelectWeapon)
                                        Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))  
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                                        v.Humanoid.WalkSpeed = 0                
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                 
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")                                
                                    end)
                                until _G.AutoThirdSea == false or v.Humanoid.Health <= 0 or not v.Parent                                
                                Tween(CFrame.new(-26880.93359375, 22.848554611206, 473.18951416016))
                            end
                        end
                    else
                        Tween(CFrame.new(-26880.93359375, 22.848554611206, 473.18951416016))
                    end
                end
            end)
        end
    end
end)

spawn(function()
    pcall(function()
        while wait() do
            if _G.AutoFactory then
                if game.Workspace.Enemies:FindFirstChild("Core") then
                    for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                        if v.Name == "Core" and v.Humanoid.Health > 0 then
                            repeat wait()
                                Tween(CFrame.new(448.46756, 199.356781, -441.389252))
                                Buso()
                                EquipWeapon(_G.SelectWeapon)
                                game:GetService("VirtualUser"):CaptureController()
                                game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                       
                            until v.Humanoid.Health <= 0 or _G.AutoFactory == false               
                        end
                    end
                end
            end
        end
    end)
end)

spawn(function()
    while wait() do
        if _G.AutoCandy then
            pcall(function()
                for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                    if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and not string.find(v.Name,"Boss") and (v.HumanoidRootPart.Position-game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 1000 then
                        repeat wait()
                            Buso()
                            EquipWeapon(_G.SelectWeapon)
                            v.HumanoidRootPart.CanCollide = false
                            v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                            v.Humanoid.WalkSpeed = 0
                            Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                            MagnetCandy = true
                            PosMonCandy = v.HumanoidRootPart.CFrame
                            game:GetService("VirtualUser"):CaptureController()
                            game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                        until _G.AutoCandy == false or not v.Parent or v.Humanoid.Health <= 0     
                        MagnetCandy = false    
                    end
                end
            end)
        end
    end
end)

spawn(function()
    pcall(function()
        while wait() do
            if _G.AutoObservation then
                if game.Players.LocalPlayer.VisionRadius.Value == 3000 then
                    game.StarterGui:SetCore("SendNotification", {
                        Icon = "";
                        Title = "Observation", 
                        Text = "You Have Max Points",
                        Duration = 2
                    })
                else
                    if SecondSea then
                        if game.Workspace.Enemies:FindFirstChild("Lava Pirate [Lv. 1200]") then
                            if game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
                                repeat wait()
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Enemies:FindFirstChild("Lava Pirate [Lv. 1200]").HumanoidRootPart.CFrame * CFrame.new(3,0,0)
                                until _G.AutoObservation == false or not game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                            else
                                repeat wait()
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Enemies:FindFirstChild("Lava Pirate [Lv. 1200]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)
                                    wait(1)
                                    if not game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and _G.AutoObservation_Hop == true then
                                        game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
                                    end
                                until _G.AutoObservation == false or game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                            end
                        else
                            Tween(CFrame.new(-5478.39209, 15.9775667, -5246.9126))
                        end
                    elseif FirstSea then
                        if game.Workspace.Enemies:FindFirstChild("Galley Captain [Lv. 650]") then
                            if game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
                                repeat wait()
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Enemies:FindFirstChild("Galley Captain [Lv. 650]").HumanoidRootPart.CFrame * CFrame.new(3,0,0)
                                until _G.AutoObservation == false or not game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                            else
                                repeat wait()
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Enemies:FindFirstChild("Galley Captain [Lv. 650]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)
                                    wait(1)
                                    if not game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and _G.AutoObservation_Hop == true then
                                        game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
                                    end
                                until _G.AutoObservation == false or game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                            end
                        else
                            Tween(CFrame.new(5533.29785, 88.1079102, 4852.3916))
                        end
                    elseif ThirdSea then
                        if game.Workspace.Enemies:FindFirstChild("Giant Islander [Lv. 1650]") then
                            if game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
                                repeat wait()
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Enemies:FindFirstChild("Giant Islander [Lv. 1650]").HumanoidRootPart.CFrame * CFrame.new(3,0,0)
                                until _G.AutoObservation == false or not game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                            else
                                repeat wait()
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Enemies:FindFirstChild("Giant Islander [Lv. 1650]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)
                                    wait(1)
                                    if not game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and _G.AutoObservation_Hop == true then
                                        game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
                                    end
                                until _G.AutoObservation == false or game.Players.LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                            end
                        else
                            Tween(CFrame.new(4530.3540039063, 656.75695800781, -131.60952758789))
                        end
                    end
                end
            end
        end
    end)
end)

local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Enemies = game:GetService("Workspace").Enemies
spawn(function()
    pcall(function()
        while wait() do
            if _G.EliteHunter_Hop then
                if _G.EliteHunter then
                    if ReplicatedStorage:FindFirstChild("Diablo [Lv. 1750]") or Enemies:FindFirstChild("Diablo [Lv. 1750]") or ReplicatedStorage:FindFirstChild("Urban [Lv. 1750]") or Enemies:FindFirstChild("Urban [Lv. 1750]") or ReplicatedStorage:FindFirstChild("Deandre [Lv. 1750]") or Enemies:FindFirstChild("Deadre [Lv. 1750]") then
                    
                    else
                        Hop()
                    end
                end
            end
        end
    end)
end)

        
spawn(function()
    while wait() do
        if  _G.EliteHunter then
            if not game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible then
                repeat Tween(CFrame.new(-5418.892578125, 313.74130249023, -2826.2260742188)) wait() until not _G.AutoSaber or (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-Vector3.new(-5418.892578125, 313.74130249023, -2826.2260742188)).Magnitude <= 10
                Distance = (game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - Vector3.new(-5418.892578125, 313.74130249023, -2826.2260742188)).Magnitude
                if Distance <= 10 then
                wait(1.1)
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter")
                end
            else
                if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text == "Defeat  Diablo (0/1)" then
                    if game:GetService("Workspace").Enemies:FindFirstChild("Diablo [Lv. 1750]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Diablo [Lv. 1750]" then
                                repeat wait()
                                    Buso()
                                    EquipWeapon(_G.SelectWeapon)
                                    Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                    sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                                    v.Humanoid.WalkSpeed = 0
                                    v.HumanoidRootPart.CanCollide = false
                                    v.HumanoidRootPart.Size = Vector3.new(60,60,60)        
                                    game:GetService("VirtualUser"):CaptureController()
                                    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                         
                                until _G.EliteHunter == false or v.Humanoid.Health <= 0                               
                            end
                        end
                    else
                        Tween(game:GetService("ReplicatedStorage")["Diablo [Lv. 1750]"].HumanoidRootPart.CFrame *CFrame.new(0,0,15))
                    end
                elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text == "Defeat  Deandre (0/1)" then
                    if game:GetService("Workspace").Enemies:FindFirstChild("Deandre [Lv. 1750]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Deandre [Lv. 1750]" then
                                repeat wait()
                                    Buso()
                                    EquipWeapon(_G.SelectWeapon)
                                    Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                    sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                                    v.Humanoid.WalkSpeed = 0
                                    v.HumanoidRootPart.CanCollide = false
                                    v.HumanoidRootPart.Size = Vector3.new(60,60,60)   
                                    game:GetService("VirtualUser"):CaptureController()
                                    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                            
                                until _G.EliteHunter == false or v.Humanoid.Health <= 0                                
                            end
                        end
                    else
                        Tween(game:GetService("ReplicatedStorage")["Deandre [Lv. 1750]"].HumanoidRootPart.CFrame *CFrame.new(0,0,15))
                    end
                elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text == "Defeat  Urban (0/1)" then
                    if game:GetService("Workspace").Enemies:FindFirstChild("Urban [Lv. 1750]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Urban [Lv. 1750]" then
                                repeat wait()
                                    Buso()
                                    EquipWeapon(_G.SelectWeapon)
                                    Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                    sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                                    v.Humanoid.WalkSpeed = 0
                                    v.HumanoidRootPart.CanCollide = false
                                    v.HumanoidRootPart.Size = Vector3.new(60,60,60)     
                                    game:GetService("VirtualUser"):CaptureController()
                                    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                             
                                until _G.EliteHunter == false or v.Humanoid.Health <= 0                                
                            end
                        end
                    else
                        Tween(game:GetService("ReplicatedStorage")["Urban [Lv. 1750]"].HumanoidRootPart.CFrame *CFrame.new(0,0,15))
                    end
                end
            end
        end
    end
end)

spawn(function()
    pcall(function()
        while wait() do wait()
            if _G.AutoSuperhuman then
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
                end   
                if game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") or game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman") then
                _G.SelectWeapon = "Superhuman"
                end  
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") or game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") or game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") or game.Players.LocalPlayer.Character:FindFirstChild("Electro") or game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") or game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") or game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") then
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 299 then
                    _G.SelectWeapon = "Black Leg"
                end
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 299 then
                    _G.SelectWeapon = "Electro"
                end
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value <= 299 then
                    _G.SelectWeapon = "Fishman Karate"
                end
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 299 then
                    _G.SelectWeapon = "Dragon Claw"
                end
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 300 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
                end
                if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 300 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
                end
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 300 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
                end
                if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 300 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
                end
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 300 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","1")
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2") 
                end
                if game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 300 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","1")
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2") 
                end
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 300 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
                end
                if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 300 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
                end 
                end
            end
        end
    end)
end)


spawn(function()
    while wait() do
        if _G.AutoDeathStep then
            if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") or game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") or game.Players.LocalPlayer.Backpack:FindFirstChild("Death Step") or game.Players.LocalPlayer.Character:FindFirstChild("Death Step") then
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 450 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
                    _G.SelectWeapon = "Death Step"
                end  
                if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 450 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
                    _G.SelectWeapon = "Death Step"
                end  
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 449 then
                    _G.SelectWeapon = "Black Leg"
                end 
            else 
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
            end
        end
    end
end)

spawn(function()
    pcall(function()
        while _G.AutoSharkman do wait()
            if _G.AutoSharkman then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
                if string.find(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate"), "keys") then  
                    if game.Players.LocalPlayer.Character:FindFirstChild("Water Key") or game.Players.LocalPlayer.Backpack:FindFirstChild("Water Key") then
                        Tween(CFrame.new(-2604.6958, 239.432526, -10315.1982, 0.0425701365, 0, -0.999093413, 0, 1, 0, 0.999093413, 0, 0.0425701365))
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
                    elseif game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 400 then
                    else 
                        Ms = "Tide Keeper [Lv. 1475] [Boss]"
                        if game.Workspace.Enemies:FindFirstChild(Ms) then   
                            for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Name == Ms then    
                                    repeat wait()
                                        Buso()
                                        EquipWeapon(_G.SelectWeapon)
                                        v.Humanoid.WalkSpeed = 0
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                        Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                    until not v.Parent or v.Humanoid.Health <= 0 or _G.AutoSharkman == false or game.Players.LocalPlayer.Character:FindFirstChild("Water Key") or game.Players.LocalPlayer.Backpack:FindFirstChild("Water Key")                                    
                                end
                            end
                        else
                            Tween(CFrame.new(-3570.18652, 123.328949, -11555.9072, 0.465199202, -1.3857326e-08, 0.885206044, 4.0332897e-09, 1, 1.35347511e-08, -0.885206044, -2.72606271e-09, 0.465199202))
                            wait(3)
                        end
                    end
                else 
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
                end
            end
        end
    end)
end)


spawn(function()
    pcall(function()
        while wait() do 
            if _G.AutoElectricClaw then
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") or game.Players.LocalPlayer.Character:FindFirstChild("Electro") or game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw") then
                    if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400 then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
                        _G.SelectWeapon = "Electric Claw"
                    end  
                    if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400 then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
                        _G.SelectWeapon = "Electric Claw"
                    end  
                    if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 399 then
                        _G.SelectWeapon = "Electro"
                    end 
                else
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
                end
            end
            if _G.AutoElectricClaw then
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") or game.Players.LocalPlayer.Character:FindFirstChild("Electro") then
                    if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") or game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400 then
                        if _G.AutoFarm == false then
                            repeat wait()
                                Tween(CFrame.new(-10371.4717, 330.764496, -10131.4199))
                            until not _G.AutoElectricClaw or (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-10371.4717, 330.764496, -10131.4199).Position).Magnitude <= 10
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw","Start")
                            wait(2)
                            repeat wait()
                                Tween(CFrame.new(-12550.532226563, 336.22631835938, -7510.4233398438))
                            until not _G.AutoElectricClaw or (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-12550.532226563, 336.22631835938, -7510.4233398438).Position).Magnitude <= 10
                            wait(1)
                            repeat wait()
                                Tween(CFrame.new(-10371.4717, 330.764496, -10131.4199))
                            until not _G.AutoElectricClaw or (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-10371.4717, 330.764496, -10131.4199).Position).Magnitude <= 10
                            wait(1)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
                        elseif _G.AutoFarm == true then
                            _G.AutoFarm = false
                            wait(1)
                            repeat wait()
                                Tween(CFrame.new(-10371.4717, 330.764496, -10131.4199))
                            until not _G.AutoElectricClaw or (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-10371.4717, 330.764496, -10131.4199).Position).Magnitude <= 10
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw","Start")
                            wait(2)
                            repeat wait()
                                Tween(CFrame.new(-12550.532226563, 336.22631835938, -7510.4233398438))
                            until not _G.AutoElectricClaw or (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-12550.532226563, 336.22631835938, -7510.4233398438).Position).Magnitude <= 10
                            wait(1)
                            repeat wait()
                                Tween(CFrame.new(-10371.4717, 330.764496, -10131.4199))
                            until not _G.AutoElectricClaw or (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-10371.4717, 330.764496, -10131.4199).Position).Magnitude <= 10
                            wait(1)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
                            _G.SelectWeapon = "Electric Claw"
                            wait(.1)
                            _G.AutoFarm = true
                        end
                    end
                end
            end
        end
    end)
end)

spawn(function()
    while wait() do
        if _G.AutoDragonTalon then
            if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") or game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Talon") or game.Players.LocalPlayer.Character:FindFirstChild("Dragon Talon") then
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 400 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
                    _G.SelectWeapon = "Dragon Talon"
                end  
                if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 400 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
                    _G.SelectWeapon = "Dragon Talon"
                end  
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 399 then
                    _G.SelectWeapon = "Dragon Claw"
                end 
            else 
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2")
            end
        end
    end
end)

MasFarm:addToggle("Auto Farm Mastery Gun",_G.AutoMasteryGun,function(value)
    _G.AutoMasteryGun = value
end)

MasFarm:addToggle("Auto Farm Mastery Fruit",_G.AutoMasteryFruit,function(value)
    _G.AutoMasteryFruit = value
end)

MasFarm:addSlider("Kill At",20,1,100,function(value)
    _G.KillAt = value
end)

MasFarm:addToggle("Auto Skill Z",_G.SkillZ,function(value)
    _G.SkillZ = value
end)

MasFarm:addToggle("Auto Skill X",_G.SkillX,function(value)
    _G.SkillX = value
end)

MasFarm:addToggle("Auto Skill C",_G.SkillC,function(value)
    _G.SkillC = value
end)

MasFarm:addToggle("Auto Skill V",_G.SkillV,function(value)
    _G.SkillV = value
end)


spawn(function()
    while wait() do
        if _G.AutoMasteryGun then
            pcall(function()
                CheckQuest()
                if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                    MagnetMas = false                                  
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                end
                if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                    MagnetMas = false
                    CheckQuest()
                    Tween(CFrameQuest)
                    if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 then
                        wait(1.1)
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest", NameQuest, LevelQuest)
                        wait(0.5)
                    end
                elseif game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible then
                    CheckQuest()
                    if game:GetService("Workspace").Enemies:FindFirstChild(Mon) then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            CheckQuest()
                            if v.Name == Mon then
                                repeat wait()
                                    if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                                        Buso()
                                        HealthMin = v.Humanoid.MaxHealth * _G.KillAt/100
                                        if v.Humanoid.Health <= HealthMin then
                                            EquipWeapon(SelectWeaponGun)
                                            v.HumanoidRootPart.CanCollide = false
                                            MagnetMas = true
                                            PosMonMas = v.HumanoidRootPart.CFrame
                                            v.HumanoidRootPart.Size = Vector3.new(2, 2, 1)
                                            v.Humanoid.WalkSpeed = 0
                                            Tween(v.HumanoidRootPart.CFrame*CFrame.new(0,30,0))
                                            local args = {
                                                [1] = v.HumanoidRootPart.Position,
                                                [2] = v.HumanoidRootPart
                                                }
                                            game:GetService("Players").LocalPlayer.Character[SelectWeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
                                        else
                                            EquipWeapon(_G.SelectWeapon)
                                            v.HumanoidRootPart.CanCollide = false
                                            v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                            v.Humanoid.WalkSpeed = 0
                                            PosMonMas = v.HumanoidRootPart.CFrame
                                            MagnetMas = true
                                            Tween(v.HumanoidRootPart.CFrame*CFrame.new(0,30,0))
                                            game:GetService("VirtualUser"):CaptureController()
                                            game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                        end
                                    else
                                        MagnetMas = false
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                                    end
                                until v.Humanoid.Health <= 0 or _G.AutoMasteryGun == false or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false
                            end
                        end
                    else
                        MagnetMas = false
                        Tween(CFrameMon)
                    end 
                end
            end)
        end
    end
end)

spawn(function()
    while wait() do
        if _G.MasteryFruit then
            if not game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible then
                CheckQuest()
                if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                    MagnetMas = false                                  
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                end
                CheckQuest()
                Tween(CFrameQuest)
                MagnetMas = false
                if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10 then
                    wait(1.1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest", NameQuest, LevelQuest)
                    wait(0.5)
                end
            elseif game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                CheckQuest()
                if game:GetService("Workspace").Enemies:FindFirstChild(Mon) then
                    pcall(function()
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == Mon then
                                repeat game:GetService("RunService").Heartbeat:wait()
                                    if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                                        HealthMon = v.Humanoid.MaxHealth * _G.KillAt/100
                                        if v.Humanoid.Health <= HealthMon then
                                            Buso()
                                            EquipWeapon(game.Players.LocalPlayer.Data.DevilFruit.Value)
                                            v.Head.CanCollide = false
                                            v.HumanoidRootPart.CanCollide = false
                                            v.Humanoid.WalkSpeed = 0
                                            Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                            USEBF = true
                                            MagnetMas = true
                                            PosMonMasteryFruit = v.HumanoidRootPart.CFrame
                                        else
                                            StartFastAttack = true
                                            USEBF = false
                                            Buso()
                                            EquipWeapon(_G.SelectWeapon)
                                            Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                            v.Head.CanCollide = false
                                            v.HumanoidRootPart.CanCollide = false
                                            v.Humanoid.WalkSpeed = 0
                                            MagnetMas = true
                                            PosMonMasteryFruit = v.HumanoidRootPart.CFrame
                                            game:GetService("VirtualUser"):CaptureController()
                                            game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                        end
                                    else
                                        USEBF = false
                                        MagnetMas = false
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                                    end
                                until v.Humanoid.Health <= 0 or _G.MasteryFruit == false or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false
                            end
                        end
                    end)
                else
                    USEBF = false
                    MagnetMas = false                        
                    Tween(CFrameMon)
                end 
            end
        end
    end
end)

spawn(function()
    while wait(.1) do
        if USEBF then
            pcall(function()
                CheckQuest()
                if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Human-Human: Buddha") then
                    if _G.SkillZ and game.Players.LocalPlayer.Character.HumanoidRootPart.Size == Vector3.new(2, 2.0199999809265, 1) then
                        local args = {
                            [1] = PosMonMasteryFruit.Position
                        }
                        game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
                        wait(.3)
                        game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
                    end
                    if _G.SkillX then
                        local args = {
                            [1] = PosMonMasteryFruit.Position
                        }
                        game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
                        game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
                    end
                    if _G.SkillC then
                        local args = {
                            [1] = PosMonMasteryFruit.Position
                        }
                        game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"C",false,game)
                        game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
                    end
                    if _G.SkillV then
                        local args = {
                            [1] = PosMonMasteryFruit.Position
                        }
                        game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"V",false,game)
                        game:GetService("VirtualInputManager"):SendKeyEvent(false,"V",false,game)
                    end
                elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild(game.Players.LocalPlayer.Data.DevilFruit.Value) then
                    if _G.SkillZ then
                        local args = {
                            [1] = PosMonMasteryFruit.Position
                        }
                        game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
                        game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
                    end
                    if _G.SkillX then
                        local args = {
                            [1] = PosMonMasteryFruit.Position
                        }
                        game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
                        game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
                    end
                    if _G.SkillC then
                        local args = {
                            [1] = PosMonMasteryFruit.Position
                        }
                        game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"C",false,game)
                        game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
                    end
                    if _G.SkillV then
                        local args = {
                            [1] = PosMonMasteryFruit.Position
                        }
                        game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"V",false,game)
                        game:GetService("VirtualInputManager"):SendKeyEvent(false,"V",false,game)
                    end
                end
            end)
        end
    end
end)


spawn(function()
    pcall(function()
        game:GetService("RunService").RenderStepped:Connect(function()
            if USEBF and PosMonMasteryFruit ~= nil then
                local args = {
                    [1] = PosMonMasteryFruit.Position
                }
                game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Data.DevilFruit.Value].RemoteEvent:FireServer(unpack(args))
            end
        end)
    end)
end)

BossName = {}

for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
    if string.find(v.Name,"Boss") then
        table.insert(BossName,v.Name)
    end
end

BossFarm:addDropdown("Select Boss",BossName,function(value)
    _G.SelectBoss = value
end)

BossFarm:addButton("Refresh Boss",function()
    for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
        if string.find(v.Name,"Boss") then
            table.clear(BossName)
        end
    end
    wait(.1)
    for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
        if string.find(v.Name,"Boss") then
            table.insert(BossName,v.Name)
        end
    end
end)

BossFarm:addToggle("Auto Farm Boss",_G.AutoFarmBoss,function(value)
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
    _G.AutoFarmBoss = value
end)

BossFarm:addToggle("Auto Farm All Boss",_G.AutoAllBoss,function(value)
    _G.AutoAllBoss = value
end)

spawn(function()
    while wait() do 
        if _G.AutoFarmBoss then
            pcall(function()
                CheckQuestBoss()
                if _G.SelectBoss == "Don Swan [Lv. 1000] [Boss]" or _G.SelectBoss == "Cursed Captain [Lv. 1325] [Raid Boss]" or _G.SelectBoss == "Saber Expert [Lv. 200] [Boss]" or _G.SelectBoss == "Mob Leader [Lv. 120] [Boss]" or _G.SelectBoss == "Darkbeard [Lv. 1000] [Raid Boss]" or _G.SelectBoss == "Longma [Lv. 2000] [Boss]" then
                    if game:GetService("Workspace").Enemies:FindFirstChild(_G.SelectBoss) then
                        for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                            if _G.AutoFarmBoss and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == MsBoss then
                                repeat wait()
                                    pcall(function() 
                                        Buso()
                                        EquipWeapon(_G.SelectWeapon)
                                        v.Humanoid.WalkSpeed = 0
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                        Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))     
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                               
                                    end)
                                until not _G.AutoFarmBoss or not v.Parent or v.Humanoid.Health <= 0                           
                            end
                        end
                    else
                        Tween(CFrameBoss)
                    end
                elseif _G.SelectBoss == "Order [Lv. 1250] [Raid Boss]" then
                    if game:GetService("Workspace").Enemies:FindFirstChild(_G.SelectBoss) then
                        for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                            if _G.AutoFarmBoss and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == MsBoss then
                                repeat wait()
                                    pcall(function() 
                                        Buso()
                                        EquipWeapon(_G.SelectWeapon)
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(80, 80, 80)
                                        v.Humanoid.WalkSpeed = 0
                                        Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))             
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                       
                                    end)
                                until not _G.AutoFarmBoss or not v.Parent or v.Humanoid.Health <= 0
                                
                            end
                        end
                    else
                        Tween(CFrameBoss)
                    end
                else
                    if game:GetService("Workspace").Enemies:FindFirstChild(_G.SelectBoss) or game:GetService("ReplicatedStorage"):FindFirstChild(_G.SelectBoss) then
                        if game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                            CheckQuestBoss()
                            Tween(CFrameQuestBoss)
                            repeat wait() until (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-CFrameQuestBoss.Position).Magnitude <= 3
                            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-CFrameQuestBoss.Position).Magnitude <= 3 then
                                wait(1.1)
                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest", NameQuestBoss, LevelQuestBoss)
                                wait(0.5)
                                Tween(CFrameBoss)
                            end
                        elseif game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                            for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if _G.AutoFarmBoss and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == MsBoss then
                                    repeat wait()
                                        pcall(function() 
                                            Buso()
                                            EquipWeapon(_G.SelectWeapon)
                                            v.HumanoidRootPart.CanCollide = false
                                            v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                            v.Humanoid.WalkSpeed = 0
                                            Tween(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))   
                                            game:GetService("VirtualUser"):CaptureController()
                                            game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))                                     
                                        end)
                                    until not _G.AutoFarmBoss or not v.Parent or v.Humanoid.Health <= 0 or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false                                
                                end
                            end
                            Tween(CFrameBoss)
                        end
                    end
                end
            end)
        end
    end
end)

spawn(function()
    pcall(function()
        while wait() do
            if _G.AutoAllBoss then
                for i,v in pairs(game.ReplicatedStorage:GetChildren()) do
                    if string.find(v.Name,"Boss") then
                        if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude < 18000 then
                            repeat game:GetService("RunService").Heartbeat:wait()
                                Buso()
                                EquipWeapon(_G.SelectWeapon)
                                v.HumanoidRootPart.CanCollide = false
                                v.Humanoid.WalkSpeed = 0
                                v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                                Tween(v.HumanoidRootPart.CFrame*CFrame.new(0,30,0))
                                game:GetService("VirtualUser"):CaptureController()
                                game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                            until v.Humanoid.Health <= 0 or _G.AutoAllBoss == false
                        end
                    end
                end
            end
        end
    end)
end)

spawn(function()
    while wait() do
        pcall(function()
            if _G.AutoFarm and Magnet then
                CheckQuest()
                for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                    if _G.AutoFarm and Magnet and (v.Name == "Factory Staff [Lv. 800]" or v.Name == "Monkey [Lv. 14]" or v.Name == "Dragon Crew Warrior [Lv. 1575]" or v.Name == "Dragon Crew Archer [Lv. 1600]") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 250 then
                        v.HumanoidRootPart.CFrame = PosMon
                        v.HumanoidRootPart.CanCollide = false
                        v.Humanoid:ChangeState(11)
                        v.Head.CanCollide = false
                        sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                    elseif _G.AutoFarm and Magnet and v.Name == Mon and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 400 then
                        v.HumanoidRootPart.CFrame = PosMon
                        v.HumanoidRootPart.CanCollide = false
                        v.Humanoid:ChangeState(11)
                        v.Head.CanCollide = false
                        sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                    end
                end
            end
            if _G.MasteryFruit and MagnetMas then
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    CheckQuest()
                    if v.Name == Mon and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                        if v.Name == "Factory Staff [Lv. 800]" or v.Name == "Monkey [Lv. 14]" or v.Name == "Dragon Crew Warrior [Lv. 1575]" or v.Name == "Dragon Crew Archer [Lv. 1600]" then
                            if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 250 then
                                v.HumanoidRootPart.CFrame = PosMonMasteryFruit
                                v.HumanoidRootPart.CanCollide = false
                                v.Head.CanCollide = false
                                v.Humanoid:ChangeState(11)
                                sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                            end
                        elseif v.Name == Mon then
                            if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 400 then
                                v.HumanoidRootPart.CFrame = PosMonMasteryFruit
                                v.HumanoidRootPart.CanCollide = false
                                v.Head.CanCollide = false
                                v.Humanoid:ChangeState(11)
                                sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                            end
                        end
                    end
                end
            end
            if _G.MasteryGun and MagnetMas then
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    CheckQuest()
                    if v.Name == Mon and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                        if v.Name == "Factory Staff [Lv. 800]" or v.Name == "Monkey [Lv. 14]" or v.Name == "Dragon Crew Warrior [Lv. 1575]" or v.Name == "Dragon Crew Archer [Lv. 1600]" then
                            if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 250 then
                                v.HumanoidRootPart.CFrame = PosMonMas
                                v.HumanoidRootPart.CanCollide = false
                                v.Head.CanCollide = false
                                v.Humanoid:ChangeState(11)
                                sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                            end
                        elseif v.Name == Mon then
                            if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 400 then
                                v.HumanoidRootPart.CFrame = PosMonMas
                                v.HumanoidRootPart.CanCollide = false
                                v.Head.CanCollide = false
                                v.Humanoid:ChangeState(11)
                                sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                            end
                        end
                    end
                end
            end
            if _G.AutoCandy and MagnetCandy then
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 400 then
                        v.HumanoidRootPart.CFrame = PosMonCandy
                        v.HumanoidRootPart.CanCollide = false
                        v.Head.CanCollide = false
                        v.Humanoid:ChangeState(11)
                        sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                    end
                end
            end
        end)
    end
end)

Stats:addToggle("Auto Melee",_G.Auto_Melee,function(value)
    _G.Auto_Melee = value
end)
Stats:addToggle("Auto Defense",_G.Auto_Defense,function(value)
    _G.Auto_Defense = value
end)
Stats:addToggle("Auto Sword",_G.Auto_Sword,function(value)
    _G.Auto_Sword = value
end)
Stats:addToggle("Auto Gun",_G.Auto_Gun,function(value)
    _G.Auto_Gun = value
end)
Stats:addToggle("Auto Devil Fruit",_G.Auto_DevilFruit,function(value)
    _G.Auto_DevilFruit = value
end)
Stats:addSlider("Stats Points",1,1,100,function(value)
    _G.PointStats = value
end)

spawn(function()
    while wait() do
        if _G.Auto_Melee then
            local args = {
                [1] = "AddPoint",
                [2] = "Melee",
                [3] = _G.PointStats
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end
    end
end)
spawn(function()
    while wait() do
        if _G.Auto_Defense then
            local args = {
                [1] = "AddPoint",
                [2] = "Defense",
                [3] = _G.PointStats
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end
    end
end)
spawn(function()
    while wait() do
        if _G.Auto_Sword then
            local args = {
                [1] = "AddPoint",
                [2] = "Sword",
                [3] = _G.PointStats
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end
    end
end)
spawn(function()
    while wait() do
        if _G.Auto_Gun then
            local args = {
                [1] = "AddPoint",
                [2] = "Gun",
                [3] = _G.PointStats
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end
    end
end)
spawn(function()
    while wait() do
        if _G.Auto_DevilFruit then
            local args = {
                [1] = "AddPoint",
                [2] = "Demon Fruit",
                [3] = _G.PointStats
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end
    end
end)

Teleport:addButton("Teleport To Old World",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelMain")
end)
Teleport:addButton("Teleport To Second Sea",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
end)
Teleport:addButton("Teleport To Third Sea",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")
end)
Teleport:addToggle("Teleport to Seabeast",TPSeabeast,function(value)
    TPSeabeast = value
    while TPSeabeast do wait()
        for i,v in pairs(game.Workspace.SeaBeasts:GetChildren()) do
            if v:FindFirstChild("HumanoidRootPart") then
                Tween(v.HumanoidRootPart.CFrame*CFrame.new(0,100,0))
            end
        end
    end
end)

Teleport:addToggle("CTRL + Click = TP",CTRL,function(value)
    CTRL = value
end)

local Plr = game.Players.LocalPlayer
local Mouse = Plr:GetMouse()
Mouse.Button1Down:Connect(function()
    if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
        return
    end
    if not Mouse.Target then
        return
    end
    if CTRL then
        Plr.Character:MoveTo(Mouse.Hit.p)
    end
end)

Teleport:addToggle("CTRL + Click = Tween",CTRL1,function(value)
    CTRL1 = value
end)

local Plr = game:GetService("Players").LocalPlayer
local Mouse = Plr:GetMouse()
Mouse.Button1Down:connect(function()
    if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
        return
    end
    if not Mouse.Target then
        return
    end
    if CTRL1 then
        Tween(CFrame.new(Mouse.Hit.p) * CFrame.new(0,2.5,0))
    end
end)

if FirstSea then
    local TP = Teleport1:addDropdown("Select Island", {
    "Start Island",
    "Marine Start",
    "Middle Town",
    "Jungle",
    "Pirate Village",
    "Desert",
    "Frozen Village",
    "Marine Ford",
    "Colosseum",
    "Sky 1st Floor",
    "Sky 2nd Floor",
    "Skr 3rd Floor",
    "Prison",
    "Magma Village",
    "Underwater City",
    "Fountain City",
    "House Cyborg's",
    "Shank's Room",
    "Mob Island"
    },function(value)
    ISLAND = value
    end)
end
if SecondSea then
    local TP = Teleport1:addDropdown("Select Island", {
    "First Spot",
    "Kingdom of Rose",
    "Swan Mansion",
    "Swan Room",
    "Green Zone",
    "Cafe",
    "Factory",
    "Colosseum",
    "Graveyard Island",
    "Snow Mountain",
    "Cold Island",
    "Hot Island",
    "Cursed Ship",
    "Ice Castle",
    "Forgotten Island",
    "Usoapp Island",
    "Minisky Island"
    },function(value)
    ISLAND = value
    end)
end
if ThirdSea then
    local TP = Teleport1:addDropdown("Select Island", {
    "Port Town",
    "Hydra Island" ,
    "Great Tree",
    "Castle on the Sea",
    "Floating Turtle",
    "Mansion",
    "Secret Temple",
    "Friendly Arena",
    "Beautiful Pirate Domain",
    "Haunted Castle",
    "Ice Cream Island",
    "Peanut Island"
    },function(value)
    ISLAND = value
    end)
end

Teleport1:addToggle("Teleport",_G.Teleport,function(value)
    _G.Teleport = value
    pcall(function()
        if _G.Teleport then
            repeat wait()
                if FirstSea then
                    if ISLAND == "Start Island" then
                        Tween(CFrame.new(1071.2832, 16.3085976, 1426.86792))
                    elseif ISLAND == "Marine Start" then
                        Tween(CFrame.new(-2573.3374, 6.88881969, 2046.99817))
                    elseif ISLAND == "Middle Town" then
                        Tween(CFrame.new(-655.824158, 7.88708115, 1436.67908))
                    elseif ISLAND == "Jungle" then
                        Tween(CFrame.new(-1249.77222, 11.8870859, 341.356476))
                    elseif ISLAND == "Pirate Village" then
                        Tween(CFrame.new(-1122.34998, 4.78708982, 3855.91992))
                    elseif ISLAND == "Desert" then
                        Tween(CFrame.new(1094.14587, 6.47350502, 4192.88721))
                    elseif ISLAND == "Frozen Village" then
                        Tween(CFrame.new(1198.00928, 27.0074959, -1211.73376))
                    elseif ISLAND == "Marine Ford" then
                        Tween(CFrame.new(-4505.375, 20.687294, 4260.55908))
                    elseif ISLAND == "Colosseum" then
                        Tween(CFrame.new(-1428.35474, 7.38933945, -3014.37305))
                    elseif ISLAND == "Sky 1st Floor" then
                        Tween(CFrame.new(-4970.21875, 717.707275, -2622.35449))
                    elseif ISLAND == "Sky 2nd Floor" then
                        Tween(CFrame.new(-4813.0249, 903.708557, -1912.69055))
                    elseif ISLAND == "Skr 3rd Floor" then
                        Tween(CFrame.new(-7952.31006, 5545.52832, -320.704956))
                    elseif ISLAND == "Prison" then
                        Tween(CFrame.new(4854.16455, 5.68742752, 740.194641))
                    elseif ISLAND == "Magma Village" then
                        Tween(CFrame.new(-5231.75879, 8.61593437, 8467.87695))
                    elseif ISLAND == "Underwater City" then
                        Tween(CFrame.new(61163.8516, 11.7796879, 1819.78418))
                    elseif ISLAND == "Fountain City" then
                        Tween(CFrame.new(5132.7124, 4.53632832, 4037.8562))
                    elseif ISLAND == "House Cyborg's" then
                        Tween(CFrame.new(6262.72559, 71.3003616, 3998.23047))
                    elseif ISLAND == "Shank's Room" then
                        Tween(CFrame.new(-1442.16553, 29.8788261, -28.3547478))
                    elseif ISLAND == "Mob Island" then
                        Tween(CFrame.new(-2850.20068, 7.39224768, 5354.99268))
                    end
                end
                if SecondSea then
                    if ISLAND == "First Spot" then
                        Tween(CFrame.new(82.9490662, 18.0710983, 2834.98779))
                    elseif ISLAND == "Kingdom of Rose" then
                        Tween(CFrame.new(-394.983521, 118.503128, 1245.8446))
                    elseif ISLAND == "Swan Mansion" then
                        Tween(CFrame.new(-390.096313, 331.886475, 673.464966))
                    elseif ISLAND == "Swan Room" then
                        Tween(CFrame.new(2302.19019, 15.1778421, 663.811035))
                    elseif ISLAND == "Green Zone" then
                        Tween(CFrame.new(-2372.14697, 72.9919434, -3166.51416))
                    elseif ISLAND == "Cafe" then
                        Tween(CFrame.new(-385.250916, 73.0458984, 297.388397))
                    elseif ISLAND == "Factory" then
                        Tween(CFrame.new(430.42569, 210.019623, -432.504791))
                    elseif ISLAND == "Colosseum" then
                        Tween(CFrame.new(-1836.58191, 44.5890656, 1360.30652))
                    elseif ISLAND == "Graveyard Island" then
                        Tween(CFrame.new(-5411.47607, 48.8234024, -721.272522))
                    elseif ISLAND == "Snow Mountain" then
                        Tween(CFrame.new(511.825226, 401.765198, -5380.396))
                    elseif ISLAND == "Cold Island" then
                        Tween(CFrame.new(-6026.96484, 14.7461271, -5071.96338))
                    elseif ISLAND == "Hot Island" then
                        Tween(CFrame.new(-5478.39209, 15.9775667, -5246.9126))
                    elseif ISLAND == "Cursed Ship" then
                        Tween(CFrame.new(902.059143, 124.752518, 33071.8125))
                    elseif ISLAND == "Ice Castle" then
                        Tween(CFrame.new(5400.40381, 28.21698, -6236.99219))
                    elseif ISLAND == "Forgotten Island" then
                        Tween(CFrame.new(-3043.31543, 238.881271, -10191.5791))
                    elseif ISLAND == "Usoapp Island" then
                        Tween(CFrame.new(4748.78857, 8.35370827, 2849.57959))
                    elseif ISLAND == "Minisky Island" then
                        Tween(CFrame.new(-260.358917, 49325.7031, -35259.3008))
                    end
                end
                if ThirdSea then
                    if ISLAND == "Port Town" then
                        Tween(CFrame.new(-236.423828, 6.72993994, 5362.34961))
                    elseif ISLAND == "Hydra Island" then
                        Tween(CFrame.new(5229.99561, 603.916565, 345.154022))
                    elseif ISLAND == "Great Tree" then
                        Tween(CFrame.new(2174.94873, 28.7312393, -6728.83154))
                    elseif ISLAND == "Castle on the Sea" then
                        Tween(CFrame.new(-5060.248046875, 314.51547241211, -2986.3635253906))
                    elseif ISLAND == "Floating Turtle" then
                        Tween(CFrame.new(-10919.2998, 331.788452, -8637.57227))
                    elseif ISLAND == "Mansion" then
                        Tween(CFrame.new(-12553.19140625, 337.16827392578, -7457.8315429688))
                    elseif ISLAND == "Secret Temple" then
                        Tween(CFrame.new(5217.35693, 6.56511116, 1100.88159, 0.00408430398))
                    elseif ISLAND == "Friendly Arena" then
                        Tween(CFrame.new(5220.28955, 72.8193436, -1450.86304))
                    elseif ISLAND == "Beautiful Pirate Domain" then
                        Tween(CFrame.new(5310.8095703125, 21.594484329224, 129.39053344727))
                    elseif ISLAND == "Haunted Castle" then
                        Tween(CFrame.new(-9506.1064453125, 142.13989257813, 5526.0405273438))
                    elseif ISLAND == "Ice Cream Island" then
                        Tween(CFrame.new(-871.98492431641, 65.819549560547, -10919.76953125))
                    elseif ISLAND == "Peanut Island" then
                        Tween(CFrame.new(-2018.2635498047, 38.103397369385, -10333.181640625))
                    end
                end
            until _G.Teleport == false
        else
            tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(.1, Enum.EasingStyle.Linear)
            tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame})
            tween:Play()
            _G.Clip = false
        end
    end)
end)

Raid:addDropdown("Select Chips",{"Flame","Ice","Quake","Light","Dark","String","Rumble","Magma","Human: Buddha","Sand"},function(value)
    _G.SelectChip = value
end)

Raid:addToggle("Auto Buy Chip",_G.AutoBuyChip,function(value)
    _G.AutoBuyChip = value
    while _G.AutoBuyChip do wait()
        pcall(function()
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("RaidsNpc","Select",_G.SelectChip)
        end)
    end
end)

Raid:addButton("Buy Chip",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("RaidsNpc","Select",_G.SelectChip)
end)

Raid:addToggle("Auto Start Raid",_G.Auto_StartRaid,function(value)
    _G.Auto_StartRaid = value
end)

Raid:addButton("Start Raid",function()
    if SecondSea then
        fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon2.Button.Main.ClickDetector)
    elseif ThirdSea then
        fireclickdetector(game:GetService("Workspace").Map["Boat Castle"].RaidSummon2.Button.Main.ClickDetector)
    end
end)

Raid:addToggle("Auto Farm Dungeon",_G.Auto_Dungeon,function(value)
    _G.Auto_Dungeon = value
end)
Raid:addToggle("Auto Awake",_G.Auto_Awakener,function(value)
    _G.Auto_Awakener = value
end)

Raid:addToggle("Kill Aura",KillAura,function(value)
    KillAura = value
end)

Raid:addToggle("Auto Next Island",NextIsLand,function(value)
    NextIsLand = value
end)

if SecondSea then
    Raid:addToggle("Teleport to Lab",TPLAB,function(value)
        TPLAB = value
        while TPLAB do wait()
            Tween(CFrame.new(-6438.73535, 250.645355, -4501.50684))
        end
    end)
end
if ThirdSea then
    Raid:addToggle("Teleport to Lab",TPLAB,function(value)
        TPLAB = value
        while TPLAB do wait()
            Tween(CFrame.new(-5017.40869, 314.844055, -2823.0127))
        end
    end)
end

if SecondSea then
    Raid:addToggle("Awakening Room",TPAWAKE,function(value)
        TPAWAKE = value
        while TPAWAKE do wait()
            Tween(CFrame.new(266.227783, 1.39509034, 1857.00732))
        end
    end)
elseif ThirdSea then
    Raid:addToggle("Awakening Room",TPAWAKE,function(value)
        TPAWAKE = value
        while TPAWAKE do wait()
            Tween(CFrame.new(-11571.440429688, 49.172668457031, -7574.7368164062))
        end
    end)
end

spawn(function()
    while wait(.1) do
        if _G.Auto_StartRaid then
            if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Timer.Visible == false then
                if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") and game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") or game.Players.LocalPlayer.Character:FindFirstChild("Special Microchip") then
                    if SecondSea then
                        fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon2.Button.Main.ClickDetector)
                    elseif ThirdSea then
                        fireclickdetector(game:GetService("Workspace").Map["Boat Castle"].RaidSummon2.Button.Main.ClickDetector)
                    end
                end
            end
        end
    end
end)

spawn(function()
    while wait() do
        if _G.Auto_Awakener then
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Awakener","Check")
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Awakener","Awaken")
        end
    end
end)

spawn(function()
    pcall(function() 
        while wait() do
            if _G.Auto_Dungeon or KillAura then
                for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
                    if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                        pcall(function()
                            repeat wait()
                                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                                v.Humanoid.Health = Die
                            until not _G.Auto_Dungeon or not v.Parent or v.Humanoid.Health <= 0
                        end)
                    end
                end
            end
        end
    end)
end)

spawn(function()
    pcall(function()
        while wait() do
            if _G.Auto_Dungeon or NextIsLand then
                repeat wait()
                    if game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") then
                        Tween(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame*CFrame.new(0,150,0))
                    elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") then
                        Tween(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").CFrame*CFrame.new(0,150,0))
                    elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") then
                        Tween(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").CFrame*CFrame.new(0,150,0))
                    elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") then
                        Tween(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").CFrame*CFrame.new(0,150,0))
                    elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
                        Tween(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").CFrame*CFrame.new(0,150,0))
                    end
                until not _G.Auto_Dungeon
            end
        end
    end)
end)

FruitList = {
    "Bomb-Bomb",
    "Spike-Spike",
    "Chop-Chop",
    "Spring-Spring",
    "Kilo-Kilo",
    "Spin-Spin",
    "Bird: Falcon",
    "Smoke-Smoke",
    "Flame-Flame",
    "Ice-Ice",
    "Sand-Sand",
    "Dark-Dark",
    "Revive-Revive",
    "Diamond-Diamond",
    "Light-Light",
    "Love-Love",
    "Rubber-Rubber",
    "Barrier-Barrier",
    "Magma-Magma",
    "Door-Door",
    "Quake-Quake",
    "Human-Human: Buddha",
    "String-String",
    "Bird-Bird: Phoenix",
    "Rumble-Rumble",
    "Paw-Paw",
    "Gravity-Gravity",
    "Dough-Dough",
    "Venom-Venom",
    "Shadow-Shadow",
    "Control-Control",
    "Soul-Soul",
    "Dragon-Dragon"
}

Devil:addDropdown("Select Fruits",FruitList,function(value)
    SelectFruit = value
end)

Devil:addToggle("Auto Buy Fruit Sniper",_G.BuyFruitSniper,function(value)
    _G.BuyFruitSniper = value
end)

spawn(function()
    pcall(function()
        while wait(.1) do
            if _G.Random_Auto then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("GetFruits")
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PurchaseRawFruit",SelectFruit)
            end 
        end
    end)
end)

Devil:addToggle("Auto Random Fruit",_G.Random_Auto,function(value)
    _G.Random_Auto = value
end)

spawn(function()
    pcall(function()
        while wait(.1) do
            if _G.Random_Auto then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin","Buy")
            end 
        end
    end)
end)

Devil:addButton("Random Fruit",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin","Buy")
end)

Devil:addToggle("Auto Drop Fruit",_G.DropFruit,function(value)
    _G.DropFruit = value
end)

spawn(function()
    while wait() do
        if _G.DropFruit then
            pcall(function()
                for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
                    if string.find(v.Name, "Fruit") then
                        EquipWeapon(v.Name)
                        SelectFruit = v.Name
                        wait(.1)
                        if game:GetService("Players").LocalPlayer.PlayerGui.Main.Dialogue.Visible == true then
                            game:GetService("Players").LocalPlayer.PlayerGui.Main.Dialogue.Visible = false
                        end
                        EquipWeapon(v.Name)
                        game:GetService("Players").LocalPlayer.Character:FindFirstChild(SelectFruit).EatRemote:InvokeServer("Drop")
                    end
                end
                for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
                    if string.find(v.Name, "Fruit") then
                        EquipWeapon(v.Name)
                        SelectFruit = v.Name
                        wait(.1)
                        if game:GetService("Players").LocalPlayer.PlayerGui.Main.Dialogue.Visible == true then
                            game:GetService("Players").LocalPlayer.PlayerGui.Main.Dialogue.Visible = false
                        end
                        EquipWeapon(v.Name)
                        game:GetService("Players").LocalPlayer.Character:FindFirstChild(SelectFruit).EatRemote:InvokeServer("Drop")
                    end
                end
            end)
        end
    end
end)

Devil:addToggle("Auto Store Fruit",_G.StoreFruit,function(value)
    _G.StoreFruit = value
end)

spawn(function()
    pcall(function()
        while wait(.1) do
            if _G.StoreFruit then
                for i,v in pairs(FruitList) do
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit",v)
                end
            end
        end
    end)
end)

Shop:addButton("Buy Black Leg",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
end)
Shop:addButton("Buy Electro",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
end)
Shop:addButton("Buy Fishman Karate",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
end)
Shop:addButton("Buy Dragon Claw",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","1")
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2")
end)
Shop:addButton("Buy Superhuman",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
end)
Shop:addButton("Buy Death Step",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
end)
Shop:addButton("Buy Sharkman Karate",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate",true)
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
end)
Shop:addButton("Buy Electric Claw",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
end)
Shop:addButton("Buy Dragon Talon",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
end)

Shop1:addButton("Buy Geppo",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Geppo")
end)
Shop1:addButton("Buy Buso Haki",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Buso")
end)
Shop1:addButton("Buy Soru",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Soru")
end)
Shop1:addButton("Buy Observation Haki", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("KenTalk","Buy")
end)

Shop2:addButton("Tomoe Ring",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Tomoe Ring")
end)

Shop2:addButton("Black Cape",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Black Cape")
end)

Shop2:addButton("Swordsman Hat",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Swordsman Hat")
end)

Shop3:addButton("Cutlass",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Cutlass")
end)

Shop3:addButton("Katana",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Katana")
end)

Shop3:addButton("Iron Mace",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Iron Mace")
end)

Shop3:addButton("Duel Katana",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Duel Katana")
end)

Shop3:addButton("Triple Katana", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Triple Katana")
end)


Shop3:addButton("Pipe",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Pipe")
end)

Shop3:addButton("Dual Headed Blade",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Dual-Headed Blade")
end)

Shop3:addButton("Bisento",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Bisento")
end)

Shop3:addButton("Soul Cane",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Soul Cane")
end)

Shop4:addButton("Slingshot",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Slingshot")
end)

Shop4:addButton("Musket",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Musket")
end)

Shop4:addButton("Flintlock",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Flintlock")
end)

Shop4:addButton("Refined Flintlock",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Refined Flintlock")
end)

Shop4:addButton("Cannon",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Cannon")
end)

Shop4:addButton("Kabucha",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Slingshot","1")
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Slingshot","2")
end)

Shop5:addButton("x2 ExP",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Candies","Buy",1,1)
end)

Shop5:addButton("Stats Refund",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Candies","Buy",1,2)
end)

Shop5:addButton("Race Reroll",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Candies","Buy",1,3)
end)

Shop5:addButton("Elf Hat",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Candies","Buy",3,1)
end)

Shop5:addButton("Santa Hat",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Candies","Buy",3,2)
end)

Shop5:addButton("Sleigh Boat",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Candies","Buy",3,3)
end)

Shop5:addButton("300 Fragments",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Candies","Buy",2,1)
end)

Shop5:addButton("700 Fragments",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Candies","Buy",2,2)
end)

Shop6:addButton("Random Surprise",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,1)
end)

Shop6:addButton("Stat Refund",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,2)
end)

Shop6:addButton("Race Reroll",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,3)
end)

Server:addButton("Server Hop",function()
    Hop()
end)

Server:addButton("Rejoin Server",function()
    game:GetService("TeleportService"):Teleport(game.PlaceId, game:GetService("Players").LocalPlayer)
end)

Codes:addButton("Open Devil Shop",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("GetFruits")
    game.Players.localPlayer.PlayerGui.Main.FruitShop.Visible = true
end)

UI:addButton("Open Inventory",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventoryWeapons")
    wait(1)
    game.Players.localPlayer.PlayerGui.Main.Inventory.Visible = true
end)

UI:addButton("Open Inventory Fruit",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventoryFruits")
    game:GetService("Players").LocalPlayer.PlayerGui.Main.FruitInventory.Visible = true
end)

Team:addButton("Join Pirates Team",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetTeam","Pirates") 
    Buso()
end)

Team:addButton("Join Marines Team",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetTeam","Marines") 
    Buso()
end)

local x2Code = {
    "3BVISITS",
    "UPD16",
    "FUDD10",
    "BIGNEWS",
    "THEGREATACE",
    "SUB2GAMERROBOT_EXP1",
    "StrawHatMaine",
    "Sub2OfficialNoobie",
    "SUB2NOOBMASTER123",
    "Sub2Daigrock",
    "Axiore",
    "TantaiGaming",
    "STRAWHATMAINE"
}

Codes:addButton("Redeem All Codes",function()
    function RedeemCode(value)
        game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(value)
    end
    for i,v in pairs(x2Code) do
        RedeemCode(v)
    end
end)

Codes:addDropdown("Selected Codes",{"SUB2GAMERROBOT_RESET1","Sub2UncleKizaru"},function(value)
    _G.CodeSelect = value
end)

Codes:addButton("Redeem Code Selected",function()
    game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(_G.CodeSelect)
end)

ESP:addToggle("ESP Player",false,function(value)
    ESPPlayer = value
    while ESPPlayer do wait()
    UpdatePlayerChams()
    end
end)


ESP:addToggle("ESP Chest",false,function(value)
    ChestESP = value
    while ChestESP do wait()
    UpdateChestChams() 
    end
end)


ESP:addToggle("ESP Fruit",false,function(value)
    DevilFruitESP = value
    while DevilFruitESP do wait()
    UpdateDevilChams() 
    end
end)

ESP:addToggle("ESP Flower",false,function(value)
    FlowerESP = value
    while FlowerESP do wait()
    UpdateFlowerChams() 
    end
end)

for theme, color in pairs(themes) do
    colors:addColorPicker(theme, color, function(color3)
        killer:setTheme(theme, color3)
    end)
end

colors:addKeybind("Toggle UI", Enum.KeyCode.RightControl, function()
    killer:toggle()
end)

killer:SelectPage(killer.pages[1], true)
