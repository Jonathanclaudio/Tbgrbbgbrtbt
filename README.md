se game.PlaceId == 2753915549 então
    Mundo1 = verdadeiro
elseif game.PlaceId == 4442272183 então
    Mundo2 = verdadeiro
elseif game.PlaceId == 7449423635 então
    Mundo3 = verdadeiro
outro
    game:GetService("Jogadores").LocalPlayer:Kick("Não dê suporte, aguarde...")
fim

função CheckQuest()
    MeuNível = jogo:GetService("Jogadores").LocalPlayer.Data.Level.Value
    se World1 então
        se MyLevel == 1 ou MyLevel <= 9 então
            Seg = "Bandido"
            LevelQuest = 1
            NomeQuest = "BanditQuest1"
            NomeMon = "Bandido"
            CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
            CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)
        elseif MeuNível == 10 ou MeuNível <= 14 então
            Seg = "Macaco"
            LevelQuest = 1
            NomeQuest = "JungleQuest"
            NomeMon = "Macaco"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1448.51806640625, 67.85301208496094, 11.46579647064209)
        elseif MeuNível == 15 ou MeuNível <= 29 então
            Seg = "Gorila"
            LevelQuest = 2
            NomeQuest = "JungleQuest"
            NomeMon = "Gorila"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1129.8836669921875, 40.46354675292969, -525.4237060546875)
        elseif MeuNível == 30 ou MeuNível <= 39 então
            Seg = "Pirata"
            LevelQuest = 1
            NomeQuest = "BuggyQuest1"
            NomeMon = "Pirata"
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-1103.513427734375, 13.752052307128906, 3896.091064453125)
        elseif MeuNível == 40 ou MeuNível <= 59 então
            Seg = "Bruto"
            LevelQuest = 2
            NomeQuest = "BuggyQuest1"
            NomeMon = "Bruto"
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-1140.083740234375, 14.809885025024414, 4322.92138671875)
        elseif MeuNível == 60 ou MeuNível <= 74 então
            Mon = "Bandido do Deserto"
            LevelQuest = 1
            NomeQuest = "DesertQuest"
            NomeMon = "Bandido do Deserto"
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
            CFrameMon = CFrame.new(924.7998046875, 6.44867467880249, 4481.5859375)
        elseif MeuNível == 75 ou MeuNível <= 89 então
            Mon = "Oficial do Deserto"
            LevelQuest = 2
            NomeQuest = "DesertQuest"
            NomeMon = "Oficial do Deserto"
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
            CFrameMon = CFrame.new(1608.2822265625, 8.614224433898926, 4371.00732421875)
        elseif MeuNível == 90 ou MeuNível <= 99 então
            Seg = "Bandido da Neve"
            LevelQuest = 1
            NomeQuest = "Quest de Neve"
            NomeMon = "Bandido da Neve"
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
            CFrameMon = CFrame.new(1354.347900390625, 87.27277374267578, -1393.946533203125)
        elseif MeuNível == 100 ou MeuNível <= 119 então
            Seg = "Boneco de Neve"
            LevelQuest = 2
            NomeQuest = "Quest de Neve"
            NomeMon = "Boneco de Neve"
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
            CFrameMon = CFrame.new(1201.6412353515625, 144.57958984375, -1550.0670166015625)
        elseif MeuNível == 120 ou MeuNível <= 149 então
            Mon = "Suboficial Chefe"
            LevelQuest = 1
            NomeQuest = "MarineQuest2"
            NomeMon = "Suboficial Chefe"
            CFrameQuest = CFrame.new(-5039.58643, 27.3500385, 4324.68018, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-4881.23095703125, 22.65204429626465, 4273.75244140625)
        elseif MeuNível == 150 ou MeuNível <= 174 então
            Seg = "Bandido do Céu"
            LevelQuest = 1
            NomeQuest = "SkyQuest"
            NomeMon = "Bandido do Céu"
            CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
            CFrameMon = CFrame.novo(-4953.20703125, 295.74420166015625, -2899.22900390625)
        elseif MeuNível == 175 ou MeuNível <= 189 então
            Mon = "Mestre das Trevas"
            LevelQuest = 2
            NomeQuest = "SkyQuest"
            NomeMon = "Mestre das Trevas"
            CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
            CFrameMon = CFrame.novo(-5259.8447265625, 391.3976745605469, -2229.035400390625)
        elseif MeuNível == 190 ou MeuNível <= 209 então
            Seg = "Prisioneiro"
            LevelQuest = 1
            NameQuest = "Quest do Prisioneiro"
            NomeMon = "Prisioneiro"
            CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)
            CFrameMon = CFrame.new(5098.9736328125, -0.3204058110713959, 474.2373352050781)
        elseif MeuNível == 210 ou MeuNível <= 249 então
            Mon = "Prisioneiro Perigoso"
            LevelQuest = 2
            NameQuest = "Quest do Prisioneiro"
            NameMon = "Prisioneiro Perigoso"
            CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)
            CFrameMon = CFrame.new(5654.5634765625, 15.633401870727539, 866.2991943359375)
        elseif MeuNível == 250 ou MeuNível <= 274 então
            Mon = "Guerreiro Toga"
            LevelQuest = 1
            NameQuest = "ColosseumQuest"
            NomeMon = "Guerreiro Toga"
            CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
            CFrameMon = CFrame.novo(-1820.21484375, 51.68385696411133, -2740.6650390625)
        elseif MeuNível == 275 ou MeuNível <= 299 então
            Seg = "Gladiador"
            LevelQuest = 2
            NameQuest = "ColosseumQuest"
            NomeMon = "Gladiador"
            CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
            CFrameMon = CFrame.new(-1292.838134765625, 56.380882263183594, -3339.031494140625)
        elseif MeuNível == 300 ou MeuNível <= 324 então
            Mon = "Soldado Militar"
            LevelQuest = 1
            NomeQuest = "MagmaQuest"
            NomeMon = "Soldado Militar"
            CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
            CFrameMon = CFrame.new(-5411.16455078125, 11.081554412841797, 8454.29296875)
        elseif MeuNível == 325 ou MeuNível <= 374 então
            Mon = "Espião Militar"
            LevelQuest = 2
            NomeQuest = "MagmaQuest"
            NameMon = "Espião Militar"
            CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
            CFrameMon = CFrame.novo(-5802.8681640625, 86.26241302490234, 8828.859375)
        elseif MeuNível == 375 ou MeuNível <= 399 então
            Mon = "Guerreiro Homem-Peixe"
            LevelQuest = 1
            NomeQuest = "PeixeQuest"
            NomeMon = "Guerreiro Homem-Peixe"
            CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
            CFrameMon = CFrame.new(60878.30078125, 18.482830047607422, 1543.7574462890625)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
            fim
        elseif MeuNível == 400 ou MeuNível <= 449 então
            Seg = "Comando dos Homens-Peixe"
            LevelQuest = 2
            NomeQuest = "PeixeQuest"
            NomeMon = "Comando Fishman"
            CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
            CFrameMon = CFrame.new(61922.6328125, 18.482830047607422, 1493.934326171875)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
            fim
        senão se MyLevel == 450 ou MyLevel <= 474 então
            Seg = "Guarda de Deus"
            LevelQuest = 1
            NomeQuest = "SkyExp1Quest"
            NomeMon = "Guarda de Deus"
            CFrameQuest = CFrame.new(-4721,88867, 843,874695, -1949,96643, 0,996191859, -0, -0,0871884301, 0, 1, -0, 0,0871884301, 0, 0,996191859)
            CFrameMon = CFrame.novo(-4710.04296875, 845.2769775390625, -1927.3079833984375)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
            fim
        elseif MeuNível == 475 ou MeuNível <= 524 então
            Seg = "Shanda"
            LevelQuest = 2
            NomeQuest = "SkyExp1Quest"
            NomeMon = "Shanda"
            CFrameQuest = CFrame.new(-7859.09814, 5544.19043, -381.476196, -0.422592998, 0, 0.906319618, 0, 1, 0, -0.906319618, 0, -0.422592998)
            CFrameMon = CFrame.novo(-7678.48974609375, 5566.40380859375, -497.2156066894531)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
            fim
        elseif MeuNível == 525 ou MeuNível <= 549 então
            Seg = "Esquadrão Real"
            LevelQuest = 1
            NomeQuest = "SkyExp2Quest"
            NomeMon = "Esquadrão Real"
            CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-7624.25244140625, 5658.13330078125, -1467.354248046875)
        elseif MeuNível == 550 ou MeuNível <= 624 então
            Mon = "Soldado Real"
            LevelQuest = 2
            NomeQuest = "SkyExp2Quest"
            NomeMon = "Soldado Real"
            CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-7836.75341796875, 5645.6640625, -1790.6236572265625)
        elseif MeuNível == 625 ou MeuNível <= 649 então
            Seg = "Pirata da Galera"
            LevelQuest = 1
            NameQuest = "Quest da Fonte"
            NomeMon = "Pirata da Galera"
            CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
            CFrameMon = CFrame.new(5551.02197265625, 78.90135192871094, 3930.412841796875)
        elseif MeuNível >= 650 então
            Seg = "Capitão de cozinha"
            LevelQuest = 2
            NameQuest = "Quest da Fonte"
            NomeMon = "Capitão da Galera"
            CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
            CFrameMon = CFrame.new(5441.95166015625, 42.50205993652344, 4950.09375)
        fim
    senão se World2 então
        se MyLevel == 700 ou MyLevel <= 724 então
            Seg = "Invasor"
            LevelQuest = 1
            NomeQuest = "Area1Quest"
            NomeMon = "Raider"
            CFrameQuest = CFrame.new(-429,543518, 71,7699966, 1836,18188, -0,22495985, 0, -0,974368095, 0, 1, 0, 0,974368095, 0, -0,22495985)
            CFrameMon = CFrame.new(-728.3267211914062, 52.779319763183594, 2345.7705078125)
        elseif MeuNível == 725 ou MeuNível <= 774 então
            Seg = "Mercenário"
            LevelQuest = 2
            NomeQuest = "Area1Quest"
            NomeMon = "Mercenário"
            CFrameQuest = CFrame.new(-429,543518, 71,7699966, 1836,18188, -0,22495985, 0, -0,974368095, 0, 1, 0, 0,974368095, 0, -0,22495985)
            CFrameMon = CFrame.new(-1004.3244018554688, 80.15886688232422, 1424.619384765625)
        elseif MeuNível == 775 ou MeuNível <= 799 então
            Seg = "Pirata Cisne"
            LevelQuest = 1
            NomeQuest = "Area2Quest"
            NomeMon = "Pirata Cisne"
            CFrameQuest = CFrame.new(638,43811, 71,769989, 918,282898, 0,139203906, 0, 0,99026376, 0, 1, 0, -0,99026376, 0, 0,139203906)
            CFrameMon = CFrame.new(1068.664306640625, 137.61428833007812, 1322.1060791015625)
        elseif MeuNível == 800 ou MeuNível <= 874 então
            Seg = "Equipe da Fábrica"
            NomeQuest = "Area2Quest"
            LevelQuest = 2
            NameMon = "Equipe da Fábrica"
            CFrameQuest = CFrame.new(632,698608, 73,1055908, 918,666321, -0,0319722369, 8,96074881e-10, -0,999488771, 1,36326533e-10, 1, 8,92172336e-10, 0,999488771, -1,07732087e-10, -0,0319722369)
            CFrameMon = CFrame.new(73.07867431640625, 81.86344146728516, -27.470672607421875)
        elseif MeuNível == 875 ou MeuNível <= 899 então
            Mon = "Tenente da Marinha"
            LevelQuest = 1
            NomeQuest = "MarineQuest3"
            NomeMon = "Tenente da Marinha"
            CFrameQuest = CFrame.new(-2440,79639, 71,7140732, -3216,06812, 0,866007268, 0, 0,500031412, 0, 1, 0, -0,500031412, 0, 0,866007268)
            CFrameMon = CFrame.new(-2821.372314453125, 75.89727783203125, -3070.089111328125)
        elseif MeuNível == 900 ou MeuNível <= 949 então
            Mon = "Capitão da Marinha"
            LevelQuest = 2
            NomeQuest = "MarineQuest3"
            NomeMon = "Capitão da Marinha"
            CFrameQuest = CFrame.new(-2440,79639, 71,7140732, -3216,06812, 0,866007268, 0, 0,500031412, 0, 1, 0, -0,500031412, 0, 0,866007268)
            CFrameMon = CFrame.novo(-1861.2310791015625, 80.17658233642578, -3254.697509765625)
        elseif MeuNível == 950 ou MeuNível <= 974 então
            Seg = "Zumbi"
            LevelQuest = 1
            NomeQuest = "ZombieQuest"
            NomeMon = "Zumbi"
            CFrameQuest = CFrame.new(-5497,06152, 47,5923004, -795,237061, -0,29242146, 0, -0,95628953, 0, 1, 0, 0,95628953, 0, -0,29242146)
            CFrameMon = CFrame.new(-5657.77685546875, 78.96973419189453, -928.68701171875)
        elseif MeuNível == 975 ou MeuNível <= 999 então
            Seg = "Vampiro"
            LevelQuest = 2
            NomeQuest = "ZombieQuest"
            NomeMon = "Vampiro"
            CFrameQuest = CFrame.new(-5497,06152, 47,5923004, -795,237061, -0,29242146, 0, -0,95628953, 0, 1, 0, 0,95628953, 0, -0,29242146)
            CFrameMon = CFrame.new(-6037.66796875, 32.18463897705078, -1340.6597900390625)
        elseif MeuNível == 1000 ou MeuNível <= 1049 então
            Seg = "Soldado da Neve"
            LevelQuest = 1
            NomeQuest = "SnowMountainQuest"
            NomeMon = "Soldado da Neve"
            CFrameQuest = CFrame.new(609,858826, 400,119904, -5372,25928, -0,374604106, 0, 0,92718488, 0, 1, 0, -0,92718488, 0, -0,374604106)
            CFrameMon = CFrame.new(549.1473388671875, 427.3870544433594, -5563.69873046875)
        caso contrário, se MyLevel == 1050 ou MyLevel <= 1099, então
            Seg = "Guerreiro do Inverno"
            LevelQuest = 2
            NomeQuest = "SnowMountainQuest"
            NomeMon = "Guerreiro do Inverno"
            CFrameQuest = CFrame.new(609,858826, 400,119904, -5372,25928, -0,374604106, 0, 0,92718488, 0, 1, 0, -0,92718488, 0, -0,374604106)
            CFrameMon = CFrame.new(1142.7451171875, 475.6398010253906, -5199.41650390625)
        elseif MeuNível == 1100 ou MeuNível <= 1124 então
            Seg = "Subordinado de Laboratório"
            LevelQuest = 1
            NomeQuest = "IceSideQuest"
            NameMon = "Subordinado de laboratório"
            CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
            CFrameMon = CFrame.novo(-5707.4716796875, 15.951709747314453, -4513.39208984375)
        elseif MeuNível == 1125 ou MeuNível <= 1174 então
            Mon = "Guerreiro com Chifres"
            LevelQuest = 2
            NomeQuest = "IceSideQuest"
            NomeMon = "Guerreiro Chifrudo"
            CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
            CFrameMon = CFrame.novo(-6341.36669921875, 15.951770782470703, -5723.162109375)
        elseif MeuNível == 1175 ou MeuNível <= 1199 então
            Seg = "Magma Ninja"
            LevelQuest = 1
            NomeQuest = "FireSideQuest"
            NomeMon = "Magma Ninja"
            CFrameQuest = CFrame.new(-5428,03174, 15,0622921, -5299,43457, -0,882952213, 0, 0,469463557, 0, 1, 0, -0,469463557, 0, -0,882952213)
            CFrameMon = CFrame.new(-5449.6728515625, 76.65874481201172, -5808.20068359375)
        elseif MeuNível == 1200 ou MeuNível <= 1249 então
            Seg = "Pirata da Lava"
            LevelQuest = 2
            NomeQuest = "FireSideQuest"
            NomeMon = "Pirata da Lava"
            CFrameQuest = CFrame.new(-5428,03174, 15,0622921, -5299,43457, -0,882952213, 0, 0,469463557, 0, 1, 0, -0,469463557, 0, -0,882952213)
            CFrameMon = CFrame.novo(-5213.33154296875, 49.73788070678711, -4701.451171875)
        elseif MeuNível == 1250 ou MeuNível <= 1274 então
            Mon = "Marinheiro de convés do navio"
            LevelQuest = 1
            NomeQuest = "ShipQuest1"
            NomeMon = "Marinheiro do Navio"
            CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)         
            CFrameMon = CFrame.new(1212.0111083984375, 150.79205322265625, 33059.24609375)    
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            fim
        elseif MeuNível == 1275 ou MeuNível <= 1299 então
            Mon = "Engenheiro de Navio"
            LevelQuest = 2
            NomeQuest = "ShipQuest1"
            NomeMon = "Engenheiro de Navio"
            CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)   
            CFrameMon = CFrame.new(919.4786376953125, 43.54401397705078, 32779.96875)   
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            fim             
        elseif MeuNível == 1300 ou MeuNível <= 1324 então
            Mon = "Comissário de bordo"
            LevelQuest = 1
            NomeQuest = "ShipQuest2"
            NomeMon = "Administrador do Navio"
            CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125)         
            CFrameMon = CFrame.new(919.4385375976562, 129.55599975585938, 33436.03515625)      
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            fim
        elseif MeuNível == 1325 ou MeuNível <= 1349 então
            Mon = "Oficial do navio"
            LevelQuest = 2
            NomeQuest = "ShipQuest2"
            NomeMon = "Oficial do navio"
            CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125)
            CFrameMon = CFrame.new(1036.0179443359375, 181.4390411376953, 33315.7265625)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            fim
        elseif MeuNível == 1350 ou MeuNível <= 1374 então
            Seg = "Guerreiro do Ártico"
            LevelQuest = 1
            NomeQuest = "FrostQuest"
            NomeMon = "Guerreiro do Ártico"
            CFrameQuest = CFrame.new(5667,6582, 26,7997818, -6486,08984, -0,933587909, 0, -0,358349502, 0, 1, 0, 0,358349502, 0, -0,933587909)
            CFrameMon = CFrame.new(5966.24609375, 62.97002029418945, -6179.3828125)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-6508.5581054688, 5000.034996032715, -132.83953857422))
            fim
        elseif MeuNível == 1375 ou MeuNível <= 1424 então
            Seg = "Espreitador da Neve"
            LevelQuest = 2
            NomeQuest = "FrostQuest"
            NomeMon = "Espreitador da Neve"
            CFrameQuest = CFrame.new(5667,6582, 26,7997818, -6486,08984, -0,933587909, 0, -0,358349502, 0, 1, 0, 0,358349502, 0, -0,933587909)
            CFrameMon = CFrame.new(5407.07373046875, 69.19437408447266, -6880.88037109375)
        elseif MeuNível == 1425 ou MeuNível <= 1449 então
            Mon = "Soldado do Mar"
            LevelQuest = 1
            NameQuest = "Quest esquecida"
            NomeMon = "Soldado do Mar"
            CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)
            CFrameMon = CFrame.novo(-3028.2236328125, 64.67451477050781, -9775.4267578125)
        elseif MeuNível >= 1450 então
            Seg = "Lutador da Água"
            LevelQuest = 2
            NameQuest = "Quest esquecida"
            NomeMon = "Lutador da Água"
            CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)
            CFrameMon = CFrame.novo(-3352.9013671875, 285.01556396484375, -10534.841796875)
        fim
    elseif Mundo3 então
        se MyLevel == 1500 ou MyLevel <= 1524 então
            Mon = "Pirata Milionário"
            LevelQuest = 1
            NameQuest = "PiratePortQuest"
            NomeMon = "Pirata Milionário"
            CFrameQuest = CFrame.new(-290,074677, 42,9034653, 5581,58984, 0,965929627, -0, -0,258804798, 0, 1, -0, 0,258804798, 0, 0,965929627)
            CFrameMon = CFrame.novo(-245.9963836669922, 47.30615234375, 5584.1005859375)
        elseif MeuNível == 1525 ou MeuNível <= 1574 então
            Mon = "Bilionário da Pistola"
            LevelQuest = 2
            NameQuest = "PiratePortQuest"
            NomeMon = "Bilionário da Pistola"
            CFrameQuest = CFrame.new(-290,074677, 42,9034653, 5581,58984, 0,965929627, -0, -0,258804798, 0, 1, -0, 0,258804798, 0, 0,965929627)
            CFrameMon = CFrame.novo(-187.3301544189453, 86.23987579345703, 6013.513671875)
        elseif MeuNível == 1575 ou MeuNível <= 1599 então
            Mon = "Guerreiro da Tripulação Dragão"
            LevelQuest = 1
            NomeQuest = "AmazonQuest"
            NomeMon = "Guerreiro da Tripulação Dragão"
            CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563, 0.898790359, -0, -0.438378751, 0, 1, -0, 0.438378751, 0, 0.898790359)
            CFrameMon = CFrame.new(6141.140625, 51.35136413574219, -1340.738525390625)
        elseif MeuNível == 1600 ou MeuNível <= 1624 então
            Mon = "Arqueiro da Tripulação do Dragão"
            NomeQuest = "AmazonQuest"
            LevelQuest = 2
            NomeMon = "Arqueiro da Tripulação do Dragão"
            CFrameQuest = CFrame.new(5833.1147460938, 51.60498046875, -1103.0693359375)
            CFrameMon = CFrame.new(6616.41748046875, 441.7670593261719, 446.0469970703125)
        elseif MeuNível == 1625 ou MeuNível <= 1649 então
            Mon = "Mulher da Ilha"
            NomeQuest = "AmazonQuest2"
            LevelQuest = 1
            NomeMon = "Mulher da Ilha"
            CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
            CFrameMon = CFrame.new(4685.25830078125, 735.8078002929688, 815.3425903320312)
        elseif MeuNível == 1650 ou MeuNível <= 1699 então
            Mon = "Ilha Gigante"
            NomeQuest = "AmazonQuest2"
            LevelQuest = 2
            NomeMon = "Ilha Gigante"
            CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
            CFrameMon = CFrame.new(4729.09423828125, 590.436767578125, -36.97627639770508)
        elseif MeuNível == 1700 ou MeuNível <= 1724 então
            Mon = "Comodoro da Marinha"
            LevelQuest = 1
            NameQuest = "IlhaÁrvoreMarinha"
            NomeMon = "Comodoro da Marinha"
            CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498, -0.965929747, 0, 0.258804798, 0, 1, 0, -0.258804798, 0, -0.965929747)
            CFrameMon = CFrame.new(2286.0078125, 73.13391876220703, -7159.80908203125)
        elseif MeuNível == 1725 ou MeuNível <= 1774 então
            Mon = "Contra-almirante da Marinha"
            NomeMon = "Contra-almirante da Marinha"
            NameQuest = "IlhaÁrvoreMarinha"
            LevelQuest = 2
            CFrameQuest = CFrame.new(2179.98828125, 28.731239318848, -6740.0551757813)
            CFrameMon = CFrame.new(3656.773681640625, 160.52406311035156, -7001.5986328125)
        elseif MeuNível == 1775 ou MeuNível <= 1799 então
            Seg = "Invasor Homem-Peixe"
            LevelQuest = 1
            NomeQuest = "DeepForestIsland3"
            NomeMon = "Fishman Raider"
            CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)   
            CFrameMon = CFrame.novo(-10407.5263671875, 331.76263427734375, -8368.5166015625)
        elseif MeuNível == 1800 ou MeuNível <= 1824 então
            Mon = "Capitão Homem-Peixe"
            LevelQuest = 2
            NomeQuest = "DeepForestIsland3"
            NomeMon = "Capitão Homem-Peixe"
            CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)   
            CFrameMon = CFrame.novo(-10994.701171875, 352.38140869140625, -9002.1103515625)
        elseif MeuNível == 1825 ou MeuNível <= 1849 então
            Seg = "Pirata da Floresta"
            LevelQuest = 1
            NameQuest = "Ilha da Floresta Profunda"
            NomeMon = "Pirata da Floresta"
            CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)
            CFrameMon = CFrame.novo(-13274.478515625, 332.3781433105469, -7769.58056640625)
        elseif MeuNível == 1850 ou MeuNível <= 1899 então
            Mon = "Pirata Mitológico"
            LevelQuest = 2
            NameQuest = "Ilha da Floresta Profunda"
            NomeMon = "Pirata Mitológico"
            CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)   
            CFrameMon = CFrame.novo(-13680.607421875, 501.08154296875, -6991.189453125)
        elseif MeuNível == 1900 ou MeuNível <= 1924 então
            Seg = "Pirata da Selva"
            LevelQuest = 1
            NomeQuest = "DeepForestIsland2"
            NomeMon = "Pirata da Selva"
            CFrameQuest = CFrame.new(-12680,3818, 389,971039, -9902,01953, -0,0871315002, 0, 0,996196866, 0, 1, 0, -0,996196866, 0, -0,0871315002)
            CFrameMon = CFrame.novo(-12256.16015625, 331.73828125, -10485.8369140625)
        elseif MeuNível == 1925 ou MeuNível <= 1974 então
            Mon = "Pirata Mosqueteiro"
            LevelQuest = 2
            NomeQuest = "DeepForestIsland2"
            NomeMon = "Pirata Mosqueteiro"
            CFrameQuest = CFrame.new(-12680,3818, 389,971039, -9902,01953, -0,0871315002, 0, 0,996196866, 0, 1, 0, -0,996196866, 0, -0,0871315002)
            CFrameMon = CFrame.novo(-13457.904296875, 391.545654296875, -9859.177734375)
        elseif MeuNível == 1975 ou MeuNível <= 1999 então
            Mon = "Esqueleto Renascido"
            LevelQuest = 1
            NomeQuest = "HauntedQuest1"
            NomeMon = "Esqueleto Renascido"
            CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-8763.7236328125, 165.72299194335938, 6159.86181640625)
        elseif MeuNível == 2000 ou MeuNível <= 2024 então
            Seg = "Zumbi Vivo"
            LevelQuest = 2
            NomeQuest = "HauntedQuest1"
            NomeMon = "Zumbi Vivo"
            CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-10144.1318359375, 138.62667846679688, 5838.0888671875)
        elseif MyLevel == 2025 ou MyLevel <= 2049 então
            Mon = "Alma Demoníaca"
            LevelQuest = 1
            NomeQuest = "HauntedQuest2"
            NomeMon = "Alma Demoníaca"
            CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-9505.8720703125, 172.10482788085938, 6158.9931640625)
        elseif MyLevel == 2050 ou MyLevel <= 2074 então
            Seg = "Múmia Possuída"
            LevelQuest = 2
            NomeQuest = "HauntedQuest2"
            NameMon = "Múmia Possuída"
            CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-9582.0224609375, 6.251527309417725, 6205.478515625)
        elseif MyLevel == 2075 ou MyLevel <= 2099 então
            Seg = "Escoteiro de Amendoim"
            LevelQuest = 1
            NomeQuest = "NutsIslandQuest"
            NomeMon = "Peanut Scout"
            CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-2143.241943359375, 47.72198486328125, -10029.9951171875)
        elseif MeuNível == 2100 ou MeuNível <= 2124 então
            Mon = "Presidente Amendoim"
            LevelQuest = 2
            NomeQuest = "NutsIslandQuest"
            NomeMon = "Presidente Amendoim"
            CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-1859.35400390625, 38.10316848754883, -10422.4296875)
        elseif MeuNível == 2125 ou MeuNível <= 2149 então
            Seg = "Chef de Sorvete"
            LevelQuest = 1
            NameQuest = "IceCreamIslandQuest"
            NomeMon = "Chef de Sorvete"
            CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-872.24658203125, 65.81957244873047, -10919.95703125)
        elseif MyLevel == 2150 ou MyLevel <= 2199 então
            Mon = "Comandante do Sorvete"
            LevelQuest = 2
            NameQuest = "IceCreamIslandQuest"
            NameMon = "Comandante do Sorvete"
            CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-558.06103515625, 112.04895782470703, -11290.7744140625)
        elseif MyLevel == 2200 ou MyLevel <= 2224 então
            Seg = "Artesão de biscoitos"
            LevelQuest = 1
            NomeQuest = "CakeQuest1"
            NomeMon = "Criador de Biscoitos"
            CFrameQuest = CFrame.new(-2021.32007, 37.7982254, -12028.7295, 0.957576931, -8.80302053e-08, 0.288177818, 6.9301187e-08, 1, 7.51931211e-08, -0.288177818, -5.2032135e-08, 0.957576931)
            CFrameMon = CFrame.novo(-2374.13671875, 37.79826354980469, -12125.30859375)
        elseif MeuNível == 2225 ou MeuNível <= 2249 então
            Seg = "Guarda do Bolo"
            LevelQuest = 2
            NomeQuest = "CakeQuest1"
            NomeMon = "Guarda do Bolo"
            CFrameQuest = CFrame.new(-2021.32007, 37.7982254, -12028.7295, 0.957576931, -8.80302053e-08, 0.288177818, 6.9301187e-08, 1, 7.51931211e-08, -0.288177818, -5.2032135e-08, 0.957576931)
            CFrameMon = CFrame.novo(-1598.3070068359375, 43.773197174072266, -12244.5810546875)
        elseif MeuNível == 2250 ou MeuNível <= 2274 então
            Seg = "Equipe de panificação"
            LevelQuest = 1
            NomeQuest = "CakeQuest2"
            NomeMon = "Equipe de panificação"
            CFrameQuest = CFrame.new(-1927.91602, 37.7981339, -12842.5391, -0.96804446, 4.22142143e-08, 0.250778586, 4.74911062e-08, 1, 1.49904711e-08, -0.250778586, 2.64211941e-08, -0.96804446)
            CFrameMon = CFrame.new(-1887.8099365234375, 77.6185073852539, -12998.3505859375)
        elseif MeuNível == 2275 ou MeuNível <= 2299 então
            Seg = "Padeiro Chefe"
            LevelQuest = 2
            NomeQuest = "CakeQuest2"
            NomeMon = "Padeiro Chefe"
            CFrameQuest = CFrame.new(-1927.91602, 37.7981339, -12842.5391, -0.96804446, 4.22142143e-08, 0.250778586, 4.74911062e-08, 1, 1.49904711e-08, -0.250778586, 2.64211941e-08, -0.96804446)
            CFrameMon = CFrame.novo(-2216.188232421875, 82.884521484375, -12869.2939453125)
        elseif MeuNível == 2300 ou MeuNível <= 2324 então
            Mon = "Guerreiro do Cacau"
            LevelQuest = 1
            NomeQuest = "ChocQuest1"
            NomeMon = "Guerreiro do Cacau"
            CFrameQuest = CFrame.new(233.22836303710938, 29.876001358032227, -12201.2333984375)
            CFrameMon = CFrame.novo(-21.55328369140625, 80.57499694824219, -12352.3876953125)
        elseif MeuNível == 2325 ou MeuNível <= 2349 então
            Seg = "Batalhador de Barras de Chocolate"
            LevelQuest = 2
            NomeQuest = "ChocQuest1"
            NameMon = "Batalhador de Barras de Chocolate"
            CFrameQuest = CFrame.new(233.22836303710938, 29.876001358032227, -12201.2333984375)
            CFrameMon = CFrame.new(582.590576171875, 77.18809509277344, -12463.162109375)
        elseif MeuNível == 2350 ou MeuNível <= 2374 então
            Seg = "Ladrão Doce"
            LevelQuest = 1
            NomeQuest = "ChocQuest2"
            NomeMon = "Ladrão Doce"
            CFrameQuest = CFrame.new(150.5066375732422, 30.693693161010742, -12774.5029296875)
            CFrameMon = CFrame.new(165.1884765625, 76.05885314941406, -12600.8369140625)
        elseif MeuNível == 2375 ou MeuNível <= 2399 então
            Seg = "Rebelde Doce"
            LevelQuest = 2
            NomeQuest = "ChocQuest2"
            NomeMon = "Candy Rebel"
            CFrameQuest = CFrame.new(150.5066375732422, 30.693693161010742, -12774.5029296875)
            CFrameMon = CFrame.new(134.86563110351562, 77.2476806640625, -12876.5478515625)
        elseif MeuNível == 2400 ou MeuNível <= 2424 então
            Seg = "Pirata Doce"
            LevelQuest = 1
            NomeQuest = "CandyQuest1"
            NomeMon = "Pirata Doce"
            CFrameQuest = CFrame.novo(-1150.0400390625, 20.378934860229492, -14446.3349609375)
            CFrameMon = CFrame.novo(-1310.5003662109375, 26.016523361206055, -14562.404296875)
        elseif MeuNível == 2425 ou MeuNível <= 2449 então
            Mon = "Demônio da Neve"
            LevelQuest = 2
            NomeQuest = "CandyQuest1"
            NomeMon = "Demônio da Neve"
            CFrameQuest = CFrame.novo(-1150.0400390625, 20.378934860229492, -14446.3349609375)
            CFrameMon = CFrame.novo(-880.2006225585938, 71.24776458740234, -14538.609375)
        elseif MeuNível == 2450 ou MeuNível <= 2474 então
            Mon = "Ilha Fora da Lei"
            LevelQuest = 1
            NomeQuest = "TikiQuest1"
            NomeMon = "Ilha Fora da Lei"
            CFrameQuest = CFrame.novo(-16545.9355, 55.6863556, -173.230499)
            CFrameMon = CFrame.novo(-16120.6035, 116.520554, -103.038849)
        elseif MeuNível == 2475 ou MeuNível <= 2499 então
            Seg = "Garoto da Ilha"
            LevelQuest = 2
            NomeQuest = "TikiQuest1"
            NomeMon = "Garoto da Ilha"
            CFrameQuest = CFrame.novo(-16545.9355, 55.6863556, -173.230499)
            CFrameMon = CFrame.novo(-16751.3125, 121.226219, -264.015015)
        elseif MyLevel == 2500 ou MyLevel <= 2524 então
            Seg = "Warrio beijado pelo sol"
            LevelQuest = 1
            NomeQuest = "TikiQuest2"
            NomeMon = "Warrio beijado pelo sol"
            CFrameQuest = CFrame.novo(-16539.078125, 55.68632888793945, 1051.5738525390625)
            CFrameMon = CFrame.novo(-16294.6748, 32.7874393, 1062.4856)
        senão se MyLevel >= 2525 então
            Seg = "Campeão da Ilha"
            LevelQuest = 2
            NomeQuest = "TikiQuest2"
            NomeMon = "Campeão da Ilha"
            CFrameQuest = CFrame.novo(-16539.078125, 55.68632888793945, 1051.5738525390625)
            CFrameMon = CFrame.novo(-16933.2129, 93.3503036, 999.450989)
        fim
    fim
fim

função Hop()
    PlaceID local = jogo.PlaceId
    Todos os IDs locais = {}
    local foundAnything = ""
    hora real local = os.date("!*t").hora
    local Excluído = falso
    função TPReturner()
        Site local;
        se foundAnything == "" então
            Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100'))
        outro
            Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100&cursor=' .. foundAnything))
        fim
        ID local = ""
        se Site.nextPageCursor e Site.nextPageCursor ~= "null" e Site.nextPageCursor ~= nil então
            foundAnything = Site.nextPageCursor
        fim
        num local = 0;
        para i,v em pares(Site.data) faça
            local Possível = verdadeiro
            ID = tostring(v.id)
            se tonumber(v.maxPlayers) > tonumber(v.playing) então
                para _,Existindo em pares(AllIDs) faça
                    se num ~= 0 então
                        se ID == tostring(Existente) então
                            Possível = falso
                        fim
                    outro
                        se tonumber(horareal) ~= tonumber(existente) então
                            local delFile = pcall(função()
                                Todos os IDs = {}
                                table.insert(AllIDs, horaatual)
                            fim)
                        fim
                    fim
                    num = num + 1
                fim
                se possível == verdadeiro então
                    tabela.insert(TodosIDs, ID)
                    espere()
                    pcall(função()
                        espere()
                        jogo:GetService("TeleportService"):TeleportToPlaceInstance(PlaceID, ID, jogo.Jogadores.JogadorLocal)
                    fim)
                    espere(4)
                fim
            fim
        fim
    fim
    função Teleport()
        enquanto espera() faz
            pcall(função()
                TPReturner()
                se encontradoQualquer coisa ~= "" então
                    TPReturner()
                fim
            fim)
        fim
    fim
    Teletransporte()
fim       

função UpdateIslandESP()
    para i,v em pares(jogo:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) faça
        pcall(função()
            se IslandESP então
                se v.Nome ~= "Mar" então
                    se não v:FindFirstChild('NameEsp') então
                        fatura local = Instance.new('BillboardGui',v)
                        bill.Nome = 'NomeEsp'
                        fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                        bill.Tamanho = UDim2.novo(1,200,1,30)
                        conta.Adornee = v
                        bill.AlwaysOnTop = verdadeiro
                        nome local = Instance.new('TextLabel',bill)
                        nome.Fonte = "GothamBold"
                        nome.FontSize = "Tamanho14"
                        nome.TextWrapped = verdadeiro
                        nome.Tamanho = UDim2.novo(1,0,1,0)
                        nome.TextYAlignment = 'Topo'
                        nome.BackgroundTransparency = 1
                        nome.TextStrokeTransparency = 0,5
                        nome.TextColor3 = Cor3.fromRGB(7, 236, 240)
                    outro
                        v['NameEsp'].TextLabel.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                    fim
                fim
            outro
                se v:FindFirstChild('NameEsp') então
                    v:FindFirstChild('NomeEsp'):Destruir()
                fim
            fim
        fim)
    fim
fim

função isnil(coisa)
retornar (coisa == nulo)
fim
função local round(n)
retornar math.floor(tonumber(n) + 0.5)
fim
Número = math.random(1, 1000000)
função UpdatePlayerChams()
para i,v em pares(jogo:GetService'Players':GetChildren()) faça
    pcall(função()
        se não isnil(v.Character) então
            se ESPPlayer então
                se não isnil(v.Character.Head) e não v.Character.Head:FindFirstChild('NameEsp'..Number) então
                    fatura local = Instance.new('BillboardGui',v.Character.Head)
                    bill.Nome = 'NomeEsp'..Número
                    fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                    bill.Tamanho = UDim2.novo(1,200,1,30)
                    bill.Adornee = v.Personagem.Cabeça
                    bill.AlwaysOnTop = verdadeiro
                    nome local = Instance.new('TextLabel',bill)
                    nome.Fonte = Enum.Fonte.GothamSemibold
                    nome.FontSize = "Tamanho14"
                    nome.TextWrapped = verdadeiro
                    nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Personagem.Cabeça.Posição - v.Personagem.Cabeça.Posição).Magnitude/3) ..' Distância')
                    nome.Tamanho = UDim2.novo(1,0,1,0)
                    nome.TextYAlignment = 'Topo'
                    nome.BackgroundTransparency = 1
                    nome.TextStrokeTransparency = 0,5
                    se v.Team == game.Players.LocalPlayer.Team então
                        nome.TextColor3 = Cor3.novo(0,255,0)
                    outro
                        nome.TextColor3 = Cor3.novo(255,0,0)
                    fim
                outro
                    v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..' | '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distância\nSaúde : ' .. round(v.Character.Humanoid.Health*100/v.Character.Humanoid.MaxHealth) .. '%')
                fim
            outro
                se v.Character.Head:FindFirstChild('NameEsp'..Number) então
                    v.Character.Head:FindFirstChild('NomeEsp'..Número):Destruir()
                fim
            fim
        fim
    fim)
fim
fim
função UpdateChestChams()
para i,v em pares(game.Workspace:GetChildren()) faça
    pcall(função()
        se string.find(v.Nome,"Baú") então
            se ChestESP então
                se string.find(v.Nome,"Baú") então
                    se não v:FindFirstChild('NameEsp'..Number) então
                        fatura local = Instance.new('BillboardGui',v)
                        bill.Nome = 'NomeEsp'..Número
                        fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                        bill.Tamanho = UDim2.novo(1,200,1,30)
                        conta.Adornee = v
                        bill.AlwaysOnTop = verdadeiro
                        nome local = Instance.new('TextLabel',bill)
                        nome.Fonte = Enum.Fonte.GothamSemibold
                        nome.FontSize = "Tamanho14"
                        nome.TextWrapped = verdadeiro
                        nome.Tamanho = UDim2.novo(1,0,1,0)
                        nome.TextYAlignment = 'Topo'
                        nome.BackgroundTransparency = 1
                        nome.TextStrokeTransparency = 0,5
                        se v.Nome == "Baú1" então
                            nome.TextColor3 = Cor3.fromRGB(109, 109, 109)
                            nome.Texto = ("Baú 1" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        fim
                        se v.Nome == "Peito2" então
                            nome.TextColor3 = Cor3.fromRGB(173, 158, 21)
                            nome.Texto = ("Baú 2" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        fim
                        se v.Nome == "Peito3" então
                            nome.TextColor3 = Cor3.fromRGB(85, 255, 255)
                            nome.Texto = ("Baú 3" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        fim
                    outro
                        v['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Posição).Magnitude/3) ..' Distância')
                    fim
                fim
            outro
                se v:FindFirstChild('NomeEsp'..Número) então
                    v:FindFirstChild('NomeEsp'..Número):Destroy()
                fim
            fim
        fim
    fim)
fim
fim
função UpdateDevilChams()
para i,v em pares(game.Workspace:GetChildren()) faça
    pcall(função()
        se DevilFruitESP então
            se string.find(v.Nome, "Fruta") então   
                se não v.Handle:FindFirstChild('NameEsp'..Number) então
                    fatura local = Instance.new('BillboardGui',v.Handle)
                    bill.Nome = 'NomeEsp'..Número
                    fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                    bill.Tamanho = UDim2.novo(1,200,1,30)
                    conta.Adornee = v.Manipular
                    bill.AlwaysOnTop = verdadeiro
                    nome local = Instance.new('TextLabel',bill)
                    nome.Fonte = Enum.Fonte.GothamSemibold
                    nome.FontSize = "Tamanho14"
                    nome.TextWrapped = verdadeiro
                    nome.Tamanho = UDim2.novo(1,0,1,0)
                    nome.TextYAlignment = 'Topo'
                    nome.BackgroundTransparency = 1
                    nome.TextStrokeTransparency = 0,5
                    nome.TextColor3 = Cor3.fromRGB(255, 255, 255)
                    nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distância')
                outro
                    v.Handle['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Handle.Posição).Magnitude/3) ..' Distância')
                fim
            fim
        outro
            se v.Handle:FindFirstChild('NameEsp'..Number) então
                v.Handle:FindFirstChild('NomeEsp'..Número):Destruir()
            fim
        fim
    fim)
fim
fim
função UpdateFlowerChams()
para i,v em pares(game.Workspace:GetChildren()) faça
    pcall(função()
        se v.Nome == "Flor2" ou v.Nome == "Flor1" então
            se FlowerESP então
                se não v:FindFirstChild('NameEsp'..Number) então
                    fatura local = Instance.new('BillboardGui',v)
                    bill.Nome = 'NomeEsp'..Número
                    fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                    bill.Tamanho = UDim2.novo(1,200,1,30)
                    conta.Adornee = v
                    bill.AlwaysOnTop = verdadeiro
                    nome local = Instance.new('TextLabel',bill)
                    nome.Fonte = Enum.Fonte.GothamSemibold
                    nome.FontSize = "Tamanho14"
                    nome.TextWrapped = verdadeiro
                    nome.Tamanho = UDim2.novo(1,0,1,0)
                    nome.TextYAlignment = 'Topo'
                    nome.BackgroundTransparency = 1
                    nome.TextStrokeTransparency = 0,5
                    nome.TextColor3 = Cor3.fromRGB(255, 0, 0)
                    se v.Nome == "Flor1" então
                        nome.Texto = ("Flor Azul" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        nome.TextColor3 = Cor3.fromRGB(0, 0, 255)
                    fim
                    se v.Nome == "Flor2" então
                        nome.Texto = ("Flor Vermelha" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        nome.TextColor3 = Cor3.fromRGB(255, 0, 0)
                    fim
                outro
                    v['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Posição).Magnitude/3) ..' Distância')
                fim
            outro
                se v:FindFirstChild('NomeEsp'..Número) então
                v:FindFirstChild('NomeEsp'..Número):Destroy()
                fim
            fim
        fim   
    fim)
fim
fim
função UpdateRealFruitChams()
para i,v em pares(game.Workspace.AppleSpawner:GetChildren()) faça
    se v:IsA("Ferramenta") então
        se RealFruitESP então
            se não v.Handle:FindFirstChild('NameEsp'..Number) então
                fatura local = Instance.new('BillboardGui',v.Handle)
                bill.Nome = 'NomeEsp'..Número
                fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                bill.Tamanho = UDim2.novo(1,200,1,30)
                conta.Adornee = v.Manipular
                bill.AlwaysOnTop = verdadeiro
                nome local = Instance.new('TextLabel',bill)
                nome.Fonte = Enum.Fonte.GothamSemibold
                nome.FontSize = "Tamanho14"
                nome.TextWrapped = verdadeiro
                nome.Tamanho = UDim2.novo(1,0,1,0)
                nome.TextYAlignment = 'Topo'
                nome.BackgroundTransparency = 1
                nome.TextStrokeTransparency = 0,5
                nome.TextColor3 = Cor3.fromRGB(255, 0, 0)
                nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distância')
            outro
                v.Handle['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' '.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Handle.Posição).Magnitude/3) ..' Distância')
            fim
        outro
            se v.Handle:FindFirstChild('NameEsp'..Number) então
                v.Handle:FindFirstChild('NomeEsp'..Número):Destruir()
            fim
        fim
    fim
fim
para i,v em pares(game.Workspace.PineappleSpawner:GetChildren()) faça
    se v:IsA("Ferramenta") então
        se RealFruitESP então
            se não v.Handle:FindFirstChild('NameEsp'..Number) então
                fatura local = Instance.new('BillboardGui',v.Handle)
                bill.Nome = 'NomeEsp'..Número
                fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                bill.Tamanho = UDim2.novo(1,200,1,30)
                conta.Adornee = v.Manipular
                bill.AlwaysOnTop = verdadeiro
                nome local = Instance.new('TextLabel',bill)
                nome.Fonte = Enum.Fonte.GothamSemibold
                nome.FontSize = "Tamanho14"
                nome.TextWrapped = verdadeiro
                nome.Tamanho = UDim2.novo(1,0,1,0)
                nome.TextYAlignment = 'Topo'
                nome.BackgroundTransparency = 1
                nome.TextStrokeTransparency = 0,5
                nome.TextColor3 = Cor3.fromRGB(255, 174, 0)
                nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distância')
            outro
                v.Handle['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' '.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Handle.Posição).Magnitude/3) ..' Distância')
            fim
        outro
            se v.Handle:FindFirstChild('NameEsp'..Number) então
                v.Handle:FindFirstChild('NomeEsp'..Número):Destruir()
            fim
        fim
    fim
fim
para i,v em pares(game.Workspace.BananaSpawner:GetChildren()) faça
    se v:IsA("Ferramenta") então
        se RealFruitESP então
            se não v.Handle:FindFirstChild('NameEsp'..Number) então
                fatura local = Instance.new('BillboardGui',v.Handle)
                bill.Nome = 'NomeEsp'..Número
                fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                bill.Tamanho = UDim2.novo(1,200,1,30)
                conta.Adornee = v.Manipular
                bill.AlwaysOnTop = verdadeiro
                nome local = Instance.new('TextLabel',bill)
                nome.Fonte = Enum.Fonte.GothamSemibold
                nome.FontSize = "Tamanho14"
                nome.TextWrapped = verdadeiro
                nome.Tamanho = UDim2.novo(1,0,1,0)
                nome.TextYAlignment = 'Topo'
                nome.BackgroundTransparency = 1
                nome.TextStrokeTransparency = 0,5
                nome.TextColor3 = Cor3.fromRGB(251, 255, 0)
                nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distância')
            outro
                v.Handle['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' '.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Handle.Posição).Magnitude/3) ..' Distância')
            fim
        outro
            se v.Handle:FindFirstChild('NameEsp'..Number) então
                v.Handle:FindFirstChild('NomeEsp'..Número):Destruir()
            fim
        fim
    fim
fim
fim

função UpdateIslandESP()
    para i,v em pares(jogo:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) faça
        pcall(função()
            se IslandESP então
                se v.Nome ~= "Mar" então
                    se não v:FindFirstChild('NameEsp') então
                        fatura local = Instance.new('BillboardGui',v)
                        bill.Nome = 'NomeEsp'
                        fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                        bill.Tamanho = UDim2.novo(1,200,1,30)
                        conta.Adornee = v
                        bill.AlwaysOnTop = verdadeiro
                        nome local = Instance.new('TextLabel',bill)
                        nome.Fonte = "GothamBold"
                        nome.FontSize = "Tamanho14"
                        nome.TextWrapped = verdadeiro
                        nome.Tamanho = UDim2.novo(1,0,1,0)
                        nome.TextYAlignment = 'Topo'
                        nome.BackgroundTransparency = 1
                        nome.TextStrokeTransparency = 0,5
                        nome.TextColor3 = Cor3.fromRGB(7, 236, 240)
                    outro
                        v['NameEsp'].TextLabel.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                    fim
                fim
            outro
                se v:FindFirstChild('NameEsp') então
                    v:FindFirstChild('NomeEsp'):Destruir()
                fim
            fim
        fim)
    fim
fim

função isnil(coisa)
retornar (coisa == nulo)
fim
função local round(n)
retornar math.floor(tonumber(n) + 0.5)
fim
Número = math.random(1, 1000000)
função UpdatePlayerChams()
para i,v em pares(jogo:GetService'Players':GetChildren()) faça
    pcall(função()
        se não isnil(v.Character) então
            se ESPPlayer então
                se não isnil(v.Character.Head) e não v.Character.Head:FindFirstChild('NameEsp'..Number) então
                    fatura local = Instance.new('BillboardGui',v.Character.Head)
                    bill.Nome = 'NomeEsp'..Número
                    fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                    bill.Tamanho = UDim2.novo(1,200,1,30)
                    bill.Adornee = v.Personagem.Cabeça
                    bill.AlwaysOnTop = verdadeiro
                    nome local = Instance.new('TextLabel',bill)
                    nome.Fonte = Enum.Fonte.GothamSemibold
                    nome.FontSize = "Tamanho14"
                    nome.TextWrapped = verdadeiro
                    nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Personagem.Cabeça.Posição - v.Personagem.Cabeça.Posição).Magnitude/3) ..' Distância')
                    nome.Tamanho = UDim2.novo(1,0,1,0)
                    nome.TextYAlignment = 'Topo'
                    nome.BackgroundTransparency = 1
                    nome.TextStrokeTransparency = 0,5
                    se v.Team == game.Players.LocalPlayer.Team então
                        nome.TextColor3 = Cor3.novo(0,255,0)
                    outro
                        nome.TextColor3 = Cor3.novo(255,0,0)
                    fim
                outro
                    v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..' | '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' Distância\nSaúde : ' .. round(v.Character.Humanoid.Health*100/v.Character.Humanoid.MaxHealth) .. '%')
                fim
            outro
                se v.Character.Head:FindFirstChild('NameEsp'..Number) então
                    v.Character.Head:FindFirstChild('NomeEsp'..Número):Destruir()
                fim
            fim
        fim
    fim)
fim
fim
função UpdateChestChams()
para i,v em pares(game.Workspace:GetChildren()) faça
    pcall(função()
        se string.find(v.Nome,"Baú") então
            se ChestESP então
                se string.find(v.Nome,"Baú") então
                    se não v:FindFirstChild('NameEsp'..Number) então
                        fatura local = Instance.new('BillboardGui',v)
                        bill.Nome = 'NomeEsp'..Número
                        fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                        bill.Tamanho = UDim2.novo(1,200,1,30)
                        conta.Adornee = v
                        bill.AlwaysOnTop = verdadeiro
                        nome local = Instance.new('TextLabel',bill)
                        nome.Fonte = Enum.Fonte.GothamSemibold
                        nome.FontSize = "Tamanho14"
                        nome.TextWrapped = verdadeiro
                        nome.Tamanho = UDim2.novo(1,0,1,0)
                        nome.TextYAlignment = 'Topo'
                        nome.BackgroundTransparency = 1
                        nome.TextStrokeTransparency = 0,5
                        se v.Nome == "Baú1" então
                            nome.TextColor3 = Cor3.fromRGB(109, 109, 109)
                            nome.Texto = ("Baú 1" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        fim
                        se v.Nome == "Peito2" então
                            nome.TextColor3 = Cor3.fromRGB(173, 158, 21)
                            nome.Texto = ("Baú 2" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        fim
                        se v.Nome == "Peito3" então
                            nome.TextColor3 = Cor3.fromRGB(85, 255, 255)
                            nome.Texto = ("Baú 3" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        fim
                    outro
                        v['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Posição).Magnitude/3) ..' Distância')
                    fim
                fim
            outro
                se v:FindFirstChild('NomeEsp'..Número) então
                    v:FindFirstChild('NomeEsp'..Número):Destroy()
                fim
            fim
        fim
    fim)
fim
fim
função UpdateDevilChams()
para i,v em pares(game.Workspace:GetChildren()) faça
    pcall(função()
        se DevilFruitESP então
            se string.find(v.Nome, "Fruta") então   
                se não v.Handle:FindFirstChild('NameEsp'..Number) então
                    fatura local = Instance.new('BillboardGui',v.Handle)
                    bill.Nome = 'NomeEsp'..Número
                    fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                    bill.Tamanho = UDim2.novo(1,200,1,30)
                    conta.Adornee = v.Manipular
                    bill.AlwaysOnTop = verdadeiro
                    nome local = Instance.new('TextLabel',bill)
                    nome.Fonte = Enum.Fonte.GothamSemibold
                    nome.FontSize = "Tamanho14"
                    nome.TextWrapped = verdadeiro
                    nome.Tamanho = UDim2.novo(1,0,1,0)
                    nome.TextYAlignment = 'Topo'
                    nome.BackgroundTransparency = 1
                    nome.TextStrokeTransparency = 0,5
                    nome.TextColor3 = Cor3.fromRGB(255, 255, 255)
                    nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distância')
                outro
                    v.Handle['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Handle.Posição).Magnitude/3) ..' Distância')
                fim
            fim
        outro
            se v.Handle:FindFirstChild('NameEsp'..Number) então
                v.Handle:FindFirstChild('NomeEsp'..Número):Destruir()
            fim
        fim
    fim)
fim
fim
função UpdateFlowerChams()
para i,v em pares(game.Workspace:GetChildren()) faça
    pcall(função()
        se v.Nome == "Flor2" ou v.Nome == "Flor1" então
            se FlowerESP então
                se não v:FindFirstChild('NameEsp'..Number) então
                    fatura local = Instance.new('BillboardGui',v)
                    bill.Nome = 'NomeEsp'..Número
                    fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                    bill.Tamanho = UDim2.novo(1,200,1,30)
                    conta.Adornee = v
                    bill.AlwaysOnTop = verdadeiro
                    nome local = Instance.new('TextLabel',bill)
                    nome.Fonte = Enum.Fonte.GothamSemibold
                    nome.FontSize = "Tamanho14"
                    nome.TextWrapped = verdadeiro
                    nome.Tamanho = UDim2.novo(1,0,1,0)
                    nome.TextYAlignment = 'Topo'
                    nome.BackgroundTransparency = 1
                    nome.TextStrokeTransparency = 0,5
                    nome.TextColor3 = Cor3.fromRGB(255, 0, 0)
                    se v.Nome == "Flor1" então
                        nome.Texto = ("Flor Azul" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        nome.TextColor3 = Cor3.fromRGB(0, 0, 255)
                    fim
                    se v.Nome == "Flor2" então
                        nome.Texto = ("Flor Vermelha" ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                        nome.TextColor3 = Cor3.fromRGB(255, 0, 0)
                    fim
                outro
                    v['NomeEsp'..Número].TextLabel.Texto = (v. Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' Distância')
                fim
            outro
                se v:FindFirstChild('NomeEsp'..Número) então
                v:FindFirstChild('NomeEsp'..Número):Destroy()
                fim
            fim
        fim   
    fim)
fim
fim
função UpdateRealFruitChams()
para i,v em pares(game.Workspace.AppleSpawner:GetChildren()) faça
    se v:IsA("Ferramenta") então
        se RealFruitESP então
            se não v.Handle:FindFirstChild('NameEsp'..Number) então
                fatura local = Instance.new('BillboardGui',v.Handle)
                bill.Nome = 'NomeEsp'..Número
                fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                bill.Tamanho = UDim2.novo(1,200,1,30)
                conta.Adornee = v.Manipular
                bill.AlwaysOnTop = verdadeiro
                nome local = Instance.new('TextLabel',bill)
                nome.Fonte = Enum.Fonte.GothamSemibold
                nome.FontSize = "Tamanho14"
                nome.TextWrapped = verdadeiro
                nome.Tamanho = UDim2.novo(1,0,1,0)
                nome.TextYAlignment = 'Topo'
                nome.BackgroundTransparency = 1
                nome.TextStrokeTransparency = 0,5
                nome.TextColor3 = Cor3.fromRGB(255, 0, 0)
                nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distância')
            outro
                v.Handle['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' '.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Handle.Posição).Magnitude/3) ..' Distância')
            fim
        outro
            se v.Handle:FindFirstChild('NameEsp'..Number) então
                v.Handle:FindFirstChild('NomeEsp'..Número):Destruir()
            fim
        fim
    fim
fim
para i,v em pares(game.Workspace.PineappleSpawner:GetChildren()) faça
    se v:IsA("Ferramenta") então
        se RealFruitESP então
            se não v.Handle:FindFirstChild('NameEsp'..Number) então
                fatura local = Instance.new('BillboardGui',v.Handle)
                bill.Nome = 'NomeEsp'..Número
                fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                bill.Tamanho = UDim2.novo(1,200,1,30)
                conta.Adornee = v.Manipular
                bill.AlwaysOnTop = verdadeiro
                nome local = Instance.new('TextLabel',bill)
                nome.Fonte = Enum.Fonte.GothamSemibold
                nome.FontSize = "Tamanho14"
                nome.TextWrapped = verdadeiro
                nome.Tamanho = UDim2.novo(1,0,1,0)
                nome.TextYAlignment = 'Topo'
                nome.BackgroundTransparency = 1
                nome.TextStrokeTransparency = 0,5
                nome.TextColor3 = Cor3.fromRGB(255, 174, 0)
                nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distância')
            outro
                v.Handle['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' '.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Handle.Posição).Magnitude/3) ..' Distância')
            fim
        outro
            se v.Handle:FindFirstChild('NameEsp'..Number) então
                v.Handle:FindFirstChild('NomeEsp'..Número):Destruir()
            fim
        fim
    fim
fim
para i,v em pares(game.Workspace.BananaSpawner:GetChildren()) faça
    se v:IsA("Ferramenta") então
        se RealFruitESP então
            se não v.Handle:FindFirstChild('NameEsp'..Number) então
                fatura local = Instance.new('BillboardGui',v.Handle)
                bill.Nome = 'NomeEsp'..Número
                fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                bill.Tamanho = UDim2.novo(1,200,1,30)
                conta.Adornee = v.Manipular
                bill.AlwaysOnTop = verdadeiro
                nome local = Instance.new('TextLabel',bill)
                nome.Fonte = Enum.Fonte.GothamSemibold
                nome.FontSize = "Tamanho14"
                nome.TextWrapped = verdadeiro
                nome.Tamanho = UDim2.novo(1,0,1,0)
                nome.TextYAlignment = 'Topo'
                nome.BackgroundTransparency = 1
                nome.TextStrokeTransparency = 0,5
                nome.TextColor3 = Cor3.fromRGB(251, 255, 0)
                nome.Texto = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' Distância')
            outro
                v.Handle['NomeEsp'..Número].TextLabel.Texto = (v.Nome ..' '.. round((jogo:GetService('Jogadores').JogadorLocal.Personagem.Cabeça.Posição - v.Handle.Posição).Magnitude/3) ..' Distância')
            fim
        outro
            se v.Handle:FindFirstChild('NameEsp'..Number) então
                v.Handle:FindFirstChild('NomeEsp'..Número):Destruir()
            fim
        fim
    fim
fim
fim

gerar(função()
enquanto espera() faz
    pcall(função()
        se MobESP então
            para i,v em pares(jogo:GetService("Workspace").Enemies:GetChildren()) faça
                se v:FindFirstChild('HumanoidRootPart') então
                    se não v:FindFirstChild("MobEap") então
                        BillboardGui local = Instância.new("BillboardGui")
                        TextLabel local = Instância.new("TextLabel")

                        BillboardGui.Parent = v
                        BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Irmão
                        BillboardGui.Active = verdadeiro
                        BillboardGui.Nome = "MobEap"
                        BillboardGui.AlwaysOnTop = verdadeiro
                        BillboardGui.Influência da Luz = 1.000
                        BillboardGui.Size = UDim2.new(0, 200, 0, 50)
                        BillboardGui.StudsOffset = Vetor3.novo(0, 2.5, 0)

                        TextLabel.Parent = BillboardGui
                        TextLabel.BackgroundColor3 = Cor3.fromRGB(255, 255, 255)
                        TextLabel.BackgroundTransparência = 1.000
                        TextLabel.Size = UDim2.new(0, 200, 0, 50)
                        TextLabel.Font = Enum.Fonte.GothamBold
                        TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)
                        TextLabel.Texto.Tamanho = 35
                    fim
                    local Dis = math.floor((jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoid.Posição - v.ParteRaizHumanoid.Posição).Magnitude)
                    v.MobEap.TextLabel.Text = v.Nome.." - "..Dis.." Distância"
                fim
            fim
        outro
            para i,v em pares(jogo:GetService("Workspace").Enemies:GetChildren()) faça
                se v:FindFirstChild("MobEap") então
                    v.MobEap:Destruir()
                fim
            fim
        fim
    fim)
fim
fim)

gerar(função()
enquanto espera() faz
    pcall(função()
        se SeaESP então
            para i,v em pares(jogo:GetService("Workspace").SeaBeasts:GetChildren()) faça
                se v:FindFirstChild('HumanoidRootPart') então
                    se não v:FindFirstChild("Seaesps") então
                        BillboardGui local = Instância.new("BillboardGui")
                        TextLabel local = Instância.new("TextLabel")

                        BillboardGui.Parent = v
                        BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Irmão
                        BillboardGui.Active = verdadeiro
                        BillboardGui.Nome = "Seaesps"
                        BillboardGui.AlwaysOnTop = verdadeiro
                        BillboardGui.Influência da Luz = 1.000
                        BillboardGui.Size = UDim2.new(0, 200, 0, 50)
                        BillboardGui.StudsOffset = Vetor3.novo(0, 2.5, 0)

                        TextLabel.Parent = BillboardGui
                        TextLabel.BackgroundColor3 = Cor3.fromRGB(255, 255, 255)
                        TextLabel.BackgroundTransparência = 1.000
                        TextLabel.Size = UDim2.new(0, 200, 0, 50)
                        TextLabel.Font = Enum.Fonte.GothamBold
                        TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)
                        TextLabel.Texto.Tamanho = 35
                    fim
                    local Dis = math.floor((jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoid.Posição - v.ParteRaizHumanoid.Posição).Magnitude)
                    v.Seaesps.TextLabel.Text = v.Nome.." - "..Dis.." Distância"
                fim
            fim
        outro
            para i,v em pares (game:GetService("Workspace").SeaBeasts:GetChildren()) faça
                se v:FindFirstChild("Seaesps") então
                    v.Seaesps:Destruir()
                fim
            fim
        fim
    fim)
fim
fim)

gerar(função()
enquanto espera() faz
    pcall(função()
        se NpcESP então
            para i,v em pares(jogo:GetService("Workspace").NPCs:GetChildren()) faça
                se v:FindFirstChild('HumanoidRootPart') então
                    se não v:FindFirstChild("NpcEspes") então
                        BillboardGui local = Instância.new("BillboardGui")
                        TextLabel local = Instância.new("TextLabel")

                        BillboardGui.Parent = v
                        BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Irmão
                        BillboardGui.Active = verdadeiro
                        BillboardGui.Nome = "NpcEspes"
                        BillboardGui.AlwaysOnTop = verdadeiro
                        BillboardGui.Influência da Luz = 1.000
                        BillboardGui.Size = UDim2.new(0, 200, 0, 50)
                        BillboardGui.StudsOffset = Vetor3.novo(0, 2.5, 0)

                        TextLabel.Parent = BillboardGui
                        TextLabel.BackgroundColor3 = Cor3.fromRGB(255, 255, 255)
                        TextLabel.BackgroundTransparência = 1.000
                        TextLabel.Size = UDim2.new(0, 200, 0, 50)
                        TextLabel.Font = Enum.Fonte.GothamBold
                        TextLabel.TextColor3 = Color3.fromRGB(7, 236, 240)
                        TextLabel.Texto.Tamanho = 35
                    fim
                    local Dis = math.floor((jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoid.Posição - v.ParteRaizHumanoid.Posição).Magnitude)
                    v.NpcEspes.TextLabel.Text = v.Name.." - "..Dis.." Distância"
                fim
            fim
        outro
            para i,v em pares (jogo:GetService("Workspace").NPCs:GetChildren()) faça
                se v:FindFirstChild("NpcEspes") então
                    v.NpcEspes:Destruir()
                fim
            fim
        fim
    fim)
fim
fim)

função isnil(coisa)
retornar (coisa == nulo)
fim
função local round(n)
retornar math.floor(tonumber(n) + 0.5)
fim
Número = math.random(1, 1000000)

função UpdateIslandMirageESP()
para i,v em pares(jogo:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) faça
    pcall(função()
        se MirageIslandESP então
            se v.Nome == "Ilha Mirage" então
                se não v:FindFirstChild('NameEsp') então
                    fatura local = Instance.new('BillboardGui',v)
                    bill.Nome = 'NomeEsp'
                    fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                    bill.Tamanho = UDim2.novo(1,200,1,30)
                    conta.Adornee = v
                    bill.AlwaysOnTop = verdadeiro
                    nome local = Instance.new('TextLabel',bill)
                    nome.Fonte = "Código"
                    nome.FontSize = "Tamanho14"
                    nome.TextWrapped = verdadeiro
                    nome.Tamanho = UDim2.novo(1,0,1,0)
                    nome.TextYAlignment = 'Topo'
                    nome.BackgroundTransparency = 1
                    nome.TextStrokeTransparency = 0,5
                    nome.TextColor3 = Cor3.fromRGB(80, 245, 245)
                outro
                    v['NomeEsp'].TextLabel.Text = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                fim
            fim
        outro
            se v:FindFirstChild('NameEsp') então
                v:FindFirstChild('NomeEsp'):Destruir()
            fim
        fim
    fim)
fim
fim

função isnil(coisa)
retornar (coisa == nulo)
fim
função local round(n)
retornar math.floor(tonumber(n) + 0.5)
fim
Número = math.random(1, 1000000)

função UpdateAfdESP()
para i,v em pares(jogo:GetService("Workspace").NPCs:GetChildren()) faça
    pcall(função()
        se AfdESP então
            se v.Nome == "Negociante de frutas avançado" então
                se não v:FindFirstChild('NameEsp') então
                    fatura local = Instance.new('BillboardGui',v)
                    bill.Nome = 'NomeEsp'
                    fatura.ExtentsOffset = Vetor3.novo(0, 1, 0)
                    bill.Tamanho = UDim2.novo(1,200,1,30)
                    conta.Adornee = v
                    bill.AlwaysOnTop = verdadeiro
                    nome local = Instance.new('TextLabel',bill)
                    nome.Fonte = "Código"
                    nome.FontSize = "Tamanho14"
                    nome.TextWrapped = verdadeiro
                    nome.Tamanho = UDim2.novo(1,0,1,0)
                    nome.TextYAlignment = 'Topo'
                    nome.BackgroundTransparency = 1
                    nome.TextStrokeTransparency = 0,5
                    nome.TextColor3 = Cor3.fromRGB(80, 245, 245)
                outro
                    v['NomeEsp'].TextLabel.Text = (v.Nome ..' \n'.. round((jogo:GetService('Jogadores').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
                fim
            fim
        outro
            se v:FindFirstChild('NameEsp') então
                v:FindFirstChild('NomeEsp'):Destruir()
            fim
        fim
    fim)
fim
fim



função InfAb()
    se InfAbility então
        se não for jogo:GetService("Jogadores").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility") então
            local inf = Instance.new("ParticleEmitter")
            inf.Aceleração = Vetor3.novo(0,0,0)
            inf.Archivable = verdadeiro
            inf.Arrastar = 20
            inf.EmissionDirection = Enum.NormalId.Topo
            inf.Enabled = verdadeiro
            inf.Lifetime = IntervaloNúmero.novo(0,0)
            inf.InfluênciaDaLuz = 0
            inf.LockedToPart = verdadeiro
            inf.Name = "Agilidade"
            Taxa de inf. = 500
            número localKeypoints2 = {
                NumberSequenceKeypoint.novo(0, 0);
                NumberSequenceKeypoint.novo(1, 4);
            }
            inf.Size = NumberSequence.new(númeroPontosChave2)
            inf.RotSpeed ​​= IntervaloNúmero.novo(9999, 99999)
            inf.Rotação = NumberRange.new(0, 0)
            inf.Speed ​​= IntervaloNúmero.novo(30, 30)
            inf.SpreadAngle = Vetor2.novo(0,0,0,0)
            inf.Textura = ""
            inf.VelocityInheritance = 0
            inf.ZOffset = 2
            inf.Transparência = NumberSequence.new(0)
            inf.Color = ColorSequence.new(Cor3.fromRGB(0,0,0),Cor3.fromRGB(0,0,0))
            inf.Parent = jogo:GetService("Jogadores").LocalPlayer.Character.HumanoidRootPart
        fim
    outro
        se jogo:GetService("Jogadores").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agilidade") então
            jogo:GetService("Jogadores").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agilidade"):Destroy()
        fim
    fim
fim

local LocalPlayer = jogo:GetService'Players'.LocalPlayer
local originalstam = LocalPlayer.Character.Energy.Value
função infinitestam()
    LocalPlayer.Character.Energy.Changed:conectar(função()
        se Energia Infinita então
            LocalPlayer.Character.Energy.Value = originalstam
        fim
    fim)
fim

gerar(função()
    pcall(função()
        enquanto espera(.1) faça
            se Energia Infinita então
                espere(0,1)
                originalstam = LocalPlayer.Character.Energy.Value
                infinitestam()
            fim
        fim
    fim)
fim)

função NoDodgeCool()
    se nododgecool então
        para i,v em seguida, getgc() faça
            se jogo:GetService("Jogadores").LocalPlayer.Character.Dodge então
                se typeof(v) == "função" e getfenv(v).script == game:GetService("Jogadores").LocalPlayer.Character.Dodge então
                    para i2,v2 em seguida, getupvalues(v) faça
                        se tostring(v2) == "0.1" então
                        repetir espera(.1)
                            valor de configuração(v,i2,0)
                        até não nododgecool
                        fim
                    fim
                fim
            fim
        fim
    fim
fim

função fly()
    mouse local=jogo:GetService("Jogadores").LocalPlayer:GetMouse''
    localplayer=jogo:GetService("Jogadores").LocalPlayer
    jogo:GetService("Jogadores").LocalPlayer.Character:WaitForChild("HumanoidRootPart")
    torso local = jogo:GetService("Jogadores").LocalPlayer.Character.HumanoidRootPart
    velocidade localSET=25
    chaves locais={a=falso,d=falso,w=falso,s=falso}
    e1 local
    e2 local
    função local start()
        posição local = Instance.new("PosiçãoCorpo",torso)
        giroscópio local = Instance.new("BodyGyro",torso)
        pos.Nome="EPIXPOS"
        pos.maxForce = Vector3.new(matemática.enorme, matemática.enorme, matemática.enorme)
        pos.position = torso.Posição
        giroscópio.maxTorque = Vetor3.novo(9e9, 9e9, 9e9)
        giroscópio.CFrame = torso.CFrame
        repita
                espere()
                localplayer.Character.Humanoid.PlatformStand=true
                local novo=giro.CFrame - giro.CFrame.p + pos.posição
                se não keys.w e não keys.s e não keys.a e não keys.d então
                velocidade=1
                fim
                se chaves.w então
                novo = novo + workspace.CurrentCamera.CoordinateFrame.lookVector * velocidade
                velocidade=velocidade+velocidadeSET
                fim
                se chaves.s então
                novo = novo - workspace.CurrentCamera.CoordinateFrame.lookVector * velocidade
                velocidade=velocidade+velocidadeSET
                fim
                se chaves.d então
                novo = novo * CFrame.new(velocidade,0,0)
                velocidade=velocidade+velocidadeSET
                fim
                se chaves.a então
                novo = novo * CFrame.new(-velocidade,0,0)
                velocidade=velocidade+velocidadeSET
                fim
                se velocidade>velocidadeSET então
                velocidade=velocidadeSET
                fim
                pos.posição=novo.p
                se chaves.w então
                gyro.CFrame = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(velocidade*15),0,0)
                elseif chaves.s então
                gyro.CFrame = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*15),0,0)
                outro
                giroscópio.CFrame = espaço de trabalho.CurrentCamera.CoordinateFrame
                fim
        até não voar
        se giroscópio então
                giroscópio:Destruir()
        fim
        se pos então
                pos:Destruir()
        fim
        voando=falso
        localplayer.Character.Humanoid.PlatformStand=false
        velocidade=0
    fim
    e1=mouse.KeyDown:conectar(função(tecla)
        se não torso ou não torso.Pai então
                voando=falso e1:desconectar() e2:desconectar() retornar
        fim
        se chave=="w" então
            chaves.w=verdadeiro
        elseif chave=="s" então
            chaves.s=verdadeiro
        elseif chave=="a" então
            chaves.a=verdadeiro
        elseif chave=="d" então
            chaves.d=verdadeiro
        fim
    fim)
    e2=mouse.KeyUp:conectar(função(tecla)
        se chave=="w" então
            chaves.w=falso
        elseif chave=="s" então
            chaves.s=falso
        elseif chave=="a" então
            chaves.a=falso
        elseif chave=="d" então
            chaves.d=falso
        fim
    fim)
    começar()
fim

função Click()
    espere(.1)
    jogo:GetService'VirtualUser':CaptureController()
    jogo:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
fim

função AutoHaki()
    se não for jogo:GetService("Jogadores").LocalPlayer.Character:FindFirstChild("HasBuso") então
        jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
    fim
fim

função UnEquipWeapon(Arma)
    se game.Players.LocalPlayer.Character:FindFirstChild(Arma) então
        _G.NotAutoEquip = verdadeiro
        espere(.5)
        jogo.Jogadores.JogadorLocal.Personagem:EncontrarPrimeiroFilho(Arma).Pai = jogo.Jogadores.JogadorLocal.Mochila
        espere(.1)
        _G.NotAutoEquip = falso
    fim
fim

função EquipWeapon(ToolSe)
    se não _G.NotAutoEquip então
        se game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) então
            Ferramenta = jogo.Jogadores.JogadorLocal.Mochila:FindFirstChild(FerramentaSe)
            espere(.1)
            jogo.Jogadores.JogadorLocal.Personagem.Humanoide:EquipTool(Ferramenta)
        fim
    fim
fim

gerar(função()
enquanto espera() faz
    para i,v em pares(jogo:GetService("Workspace")["_WorldOrigin"]:GetChildren()) faça
        pcall(função()
            se v.Name == ("CurvedRing") ou v.Name == ("SlashHit") ou v.Name == ("SwordSlash") ou v.Name == ("SlashTail") ou v.Name == ("Sounds") então
                v:Destruir()
            fim
        fim)
    fim
fim
fim)

função Check_Sword(Nome_Espada)
    para i, v em pares(jogo:GetService("ReplicatedStorage").Remotes['CommF_']:InvokeServer("getInventory")) faça
        se (v.Type == "Espada") então
            se v.Nome == Nome_da_Espada então
                retornar verdadeiro
            fim
        fim
    fim
fim

função GetDistance(alvo)
    retornar math.floor((target.Position - jogo.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude)
fim

função BTP(P)
	repetir esperar(1)
		jogo.Jogadores.JogadorLocal.Personagem.Humanoide:MudarEstado(15)
		jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame = P
		tarefa.esperar()
		jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame = P
	até (P.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1500
fim

função TelePPlayer(P)
	jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame = P
fim
    
    função TP(Pos)
    Distância = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    se Distância < 25 então
        Velocidade = 10000
    elseif Distância < 50 então
        Velocidade = 2000
    elseif Distância < 150 então
        Velocidade = 800
    elseif Distância < 250 então
        Velocidade = 600
    elseif Distância < 500 então
        Velocidade = 400
    elseif Distância < 750 então
        Velocidade = 250
    elseif Distância >= 1000 então
        Velocidade = 200
    fim
    jogo:GetService("TweenService"):Criar(
        jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide,
        TweenInfo.new(Distância/Velocidade, Enum.EasingStyle.Linear),
        {CFrame = Pos}
    ):Jogar()
fim

    função TP1(Pos)
        Distância = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        se Distância < 25 então
            Velocidade = 5000
        elseif Distância < 50 então
            Velocidade = 2000
        elseif Distância < 150 então
            Velocidade = 800
        elseif Distância < 250 então
            Velocidade = 600
        elseif Distância < 500 então
            Velocidade = 300
        elseif Distância < 750 então
            Velocidade = 250
        elseif Distância >= 1000 então
            Velocidade = 200
        fim
        jogo:GetService("TweenService"):Criar(
            jogo:GetService("Jogadores").LocalPlayer.Character.HumanoidRootPart,
            TweenInfo.new(Distância/Velocidade, Enum.EasingStyle.Linear),
            {CFrame = Pos}
        ):Jogar()
fim

    função topos(Pos)
        Distância = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        se Distância < 25 então
            Velocidade = 5000
        elseif Distância < 50 então
            Velocidade = 2000
        elseif Distância < 150 então
            Velocidade = 800
        elseif Distância < 250 então
            Velocidade = 600
        elseif Distância < 500 então
            Velocidade = 300
        elseif Distância < 750 então
            Velocidade = 250
        elseif Distância >= 1000 então
            Velocidade = 200
        fim
        jogo:GetService("TweenService"):Criar(
            jogo:GetService("Jogadores").LocalPlayer.Character.HumanoidRootPart,
            TweenInfo.new(Distância/Velocidade, Enum.EasingStyle.Linear),
            {CFrame = Pos}
        ):Jogar()
fim

função TPB(CFgo)
	tween_s locais = jogo:serviço"TweenService"
	informações locais = TweenInfo.new((jogo:GetService("Espaço de trabalho").Barcos.BrigadaMarinha.AssentoVeículo.CFrame.Posição - CFgo.Posição).Magnitude/300, Enum.EasingStyle.Linear)
	tween = tween_s:Create(game:GetService("Espaço de trabalho").Barcos.BrigadaMarinha.AssentoVeículo, informações, {CFrame = CFgo})
	interpolação:Reproduzir()

	função interpolada local = {}

	função tweenfunc:Stop()
		interpolação:Cancelar()
	fim

	retornar tweenfunc
fim

função TPP(CFgo)
	se game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health <= 0 ou não game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") então tween:Cancel() repita wait() até game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid") e game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 wait(7) return end
	tween_s locais = jogo:serviço"TweenService"
	informações locais = TweenInfo.new((jogo:GetService("Jogadores")["Jogador Local"].Character.HumanoidRootPart.Position - CFgo.Position).Magnitude/325, Enum.EasingStyle.Linear)
	tween = tween_s:Criar(jogo.Jogadores.JogadorLocal.Personagem["ParteRaizHumanoide"], informação, {CFrame = CFgo})
	interpolação:Reproduzir()

	função interpolada local = {}

	função tweenfunc:Stop()
		interpolação:Cancelar()
	fim

	retornar tweenfunc
fim

getgenv().ToTargets = função(p)
tarefa.spawn(função()
    pcall(função()
        se jogo:GetService("Jogadores").LocalPlayer:DistanceFromCharacter(p.Position) <= 250 então
            jogo:GetService("Jogadores").LocalPlayer.Character.HumanoidRootPart.CFrame = p
        elseif não game.Players.LocalPlayer.Character:FindFirstChild("Root")então
            local K = Instância.new("Parte",jogo.Jogadores.JogadorLocal.Personagem)
            K.Tamanho = Vetor3.novo(1,0.5,1)
            K.Nome = "Raiz"
            K.Ancorado = verdadeiro
            K.Transparência = 1
            K.CanCollide = falso
            K.CFrame = jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame * CFrame.novo(0,20,0)
        fim
        local U = (jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.Posição-p.Posição).Magnitude
        local z = jogo:serviço("TweenService")
        local B = TweenInfo.new((p.Posição-jogo.Jogadores.JogadorLocal.Personagem.Raiz.Posição).Magnitude/300,Enum.EasingStyle.Linear)
        local S,g = pcall(função()
        local q = z:Criar(jogo.Jogadores.JogadorLocal.Personagem.Raiz,B,{CFrame = p})
        q:Reproduzir()
    fim)
    se não S então
        retornar g
    fim
    jogo.Jogadores.JogadorLocal.Personagem.Raiz.CFrame = jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame
        se S e game.Players.LocalPlayer.Character:FindFirstChild("Root") então
            pcall(função()
                se (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 20 então
                    gerar(função()
                        pcall(função()
                            se (jogo.Jogadores.JogadorLocal.Personagem.Raiz.Posição-jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.Posição).Magnitude > 150 então
                                jogo.Jogadores.JogadorLocal.Personagem.Raiz.CFrame = jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame
                            outro
                                jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame=jogo.Jogadores.JogadorLocal.Personagem.Raiz.CFrame
                            fim
                        fim)
                    fim)
                elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 10 e (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 20 então
                    jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame = p
                elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 10 então
                    jogo.Jogadores.JogadorLocal.Personagem.ParteRaizHumanoide.CFrame = p
                fim
            fim)
        fim
    fim)
fim)
fim

Tipo = 1
gerar(função()
enquanto espera(.1) faça
    se Tipo == 1 então
        Pos = CFrame.novo(0,PosY,0)
    elseif Tipo == 2 então
        Pos = CFrame.novo(0,PosY,-30)
    elseif Tipo == 3 então
        Pos = CFrame.novo(30,PosY,0)
    elseif Tipo == 4 então
        Pos = CFrame.novo(0,PosY,30)	
    elseif Tipo == 5 então
        Pos = CFrame.novo(-30,PosY,0)
    elseif Tipo == 6 então
        Pos = CFrame.novo(0,35,0)
    fim
    fim
fim)

gerar(função()
enquanto espera(.1) faça
    Tipo = 1
    espere(0,5)
    Tipo = 2
    espere(0,5)
    Tipo = 3
    espere(0,5)
    Tipo = 4
    espere(0,5)
    Tipo = 5
    espere(0,5)
fim
fim)

tarefa.spawn(função()
    enquanto task.wait() faz
        pcall(função()
            se _G.AutoFarmNearest e AutoFarmNearestMagnet ou SelectMag e _G.BringMonster então
                para i,v em pares(game.Workspace.Enemies:GetChildren()) faça
                    se não string.find(v.Name,"Boss") e (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= _G.BringMode então
                        se InMyNetWork(v.HumanoidRootPart) então
                            v.HumanoidRootPart.CFrame = PosMon
                            v.Humanoide.JumpPower = 0
                            v.Humanoid.VelocidadeDeCaminhada = 0
                            v.HumanoidRootPart.Size = Vetor3.novo(60,60,60)
                            v.HumanoidRootPart.Transparência = 1
                            v.HumanoidRootPart.CanCollide = falso
                            v.Head.CanCollide = falso
                            se v.Humanoid:FindFirstChild("Animador") então
                                v.Humanoid.Animator:Destruir()
                            fim
                            v.Humanoid:ChangeState(11)
                            v.Humanoid:ChangeState(14)
                        fim
                    fim
                fim
            fim
        fim)
    fim
    fim)

gerar(função()
jogo:GetService("RunService").Heartbeat:Connect(função()
    se _G.AutoVampire ou AutoFarmChest ou _G.AutoAdvanceDungeon ou _G.AutoDoughtBoss ou _G.Auto_DungeonMobAura ou _G.AutoFarmChest ou _G.AutoFactory ou _G.AutoFarmBossHallow ou _G.AutoFarmSwanGlasses ou _G.AutoLongSword ou _G.AutoBlackSpikeycoat ou _G.AutoElectricClaw ou _G.AutoFarmGunMastery ou _G.AutoHolyTorch ou _G.AutoLawRaid ou _G.AutoFarmBoss ou _G.AutoTwinHooks ou _G.AutoOpenSwanDoor ou _G.AutoDragon_Trident ou _G.AutoSaber ou _G.NOCLIP ou _G.AutoFarmFruitMastery ou _G.AutoFarmGunMastery ou _G.TeleportIsland ou _G.Auto_EvoRace ou _G.AutoFarmAllMsBypassType ou _G.AutoObservationv2 ou _G.AutoMusketeerHat ou _G.AutoEctoplasm ou _G.AutoRengoku ou _G.Auto_Rainbow_Haki ou _G.AutoObservation ou _G.AutoDarkDagger ou _G.Safe_Mode ou _G.MasteryFruit ou _G.AutoBudySword ou _G.AutoOderSword ou _G.AutoBounty ou _G.AutoAllBoss ou _G.Auto_Bounty ou _G.AutoSharkman ou _G.Auto_Mastery_Fruit ou _G.Auto_Mastery_Gun ou _G.Auto_Dungeon ou _G.Auto_Cavender ou _G.Auto_Pole ou _G.Auto_Kill_Ply ou _G.Auto_Factory ou _G.AutoSecondSea ou _G.TeleportPly ou _G.AutoBartilo ou _G.Auto_DarkBoss ou _G.GrabChest ou _G.AutoFarmBounty ou _G.Holy_Torch ou _G.AutoFarm ou _G.Clip ou _G.AutoElitehunter ou _G.AutoThirdSea ou _G.Auto_Bone ou _G.Autoheart ou _G.Autodoughking ou _G.AutoFarmMaterial ou _G.AutoNevaSoulGuitar ou _G.Auto_Dragon_Trident ou _G.Autotushita ou _G.d ou _G.Autowaden ou _G.Autogay ou _G.Autopole ou _G.Autosaw ou _G.AutoObservationHakiV2 ou _G.AutoFarmNearest ou AutoFarmChest ou _G.AutoCarvender ou _G.AutoTwinHook ou AutoMobAura ou _G.Tweenfruit ou _G.AutoKai ou _G.TeleportNPC ou _G.Leather ou _G.Auto_Wing ou _G.Umm ou _G.Makori_gay ou Radioactive ou Fish ou Gunpowder ou Dragon_Scale ou Cocoafarm ou Scrap ou MiniHee ou _G.AutoFarmSeabaest ou Auto_Cursed_Dual_Katana ou _G.AutoFarmMob ou _G.AutoMysticIsland ou _G.AutoFarmDungeon ou _G.AutoRaidPirate ou _G.AutoQuestRace ou _G.TweenMGear ou getgenv().AutoFarm ou _G.AutoPlayerHunter ou _G.AutoFactory ou Grab_Chest ou _G.Namfon ou _G.AutoSwordMastery ou _G.AutoSeaBest ou _G.AutoKillTial ou _G.Auto_Saber ou _G.Position_Spawn ou _G.Farmfast ou _G.AutoRace ou _G.RaidPirate então
        se não for jogo:GetService("Workspace"):FindFirstChild("LOL") então
            LOL local = Instância.new("Parte")
            LOL.Nome = "LOL"
            LOL.Parent = jogo.Espaço de trabalho
            LOL.Ancorado = verdadeiro
            LOL.Transparência = 1
            LOL.Tamanho = Vetor3.novo(30,-0.5,30)
        elseif jogo:GetService("Espaço de trabalho"):FindFirstChild("LOL") então
            jogo.Workspace["LOL"…
