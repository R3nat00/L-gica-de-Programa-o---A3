algoritmo "AnáliseIBGE"
var // Declaração de todas as variáveis.
   Cidade1, Cidade2, Cidade3, Passeio1, Passeio2, Passeio3: Inteiro
   Acidente1, Acidente2, Acidente3: Inteiro
   Local1, Local2, Local3: Caractere
   MediaV, Media, Indice1, Indice2, Indice3: Real
inicio

   // Será solicitado ao Usuário a escolha de 3 cidades entre as 10 cidades
   // mais populosas do estado do Paraná através do código, seguidos de quantidade de veículos e acidentes fatais.
   // Em seguida mostrará o maior e menor índice de acidentes entre as cidades escolhidas.
   // Média de veículos e média de acidentes de trânsito.
     
   EscrevaL ("----------------------------------------------------")
   EscrevaL ("-- Escolha 3 das cidades mais populosas do Paraná --")
   EscrevaL ("----------------------------------------------------")
   EscrevaL ("----------- Para Curitiba digite '1' ---------------")
   EscrevaL ("----------- Para Londrina digite '2' ---------------")
   EscrevaL ("----------- Para Maringá digite '3' ----------------")
   EscrevaL ("----------- Para Ponta Grossa digite '4' -----------")
   EscrevaL ("----------- Para Cascavel digite '5' ---------------")
   EscrevaL ("----------- Para São José dos Pinhais digite '6' ---")
   EscrevaL ("----------- Para Foz do Iguacú digite '7' ----------")
   EscrevaL ("----------- Para Colombo digite '8' ----------------")
   EscrevaL ("----------- Para Guarapuava digite '9' -------------")
   EscrevaL ("----------- Para Paranaguá digite '10' -------------")
   EscrevaL ("----------------------------------------------------")
   EscrevaL ("")
   Repita
      Escreva ("Qual será a primeira cidade? ")
      Leia (Cidade1)
   Ate (Cidade1 >=1) e (Cidade1 <=10)
   EscrevaL("")
   Repita
      Escreva ("Qual será a segunda cidade? ")
      Leia (Cidade2)
   Ate (Cidade2 >=1) e (Cidade2 <=10) e (Cidade2 <> Cidade1)
   EscrevaL ("")
   Repita
      Escreva ("Qual será a terceira cidade? ")
      Leia (Cidade3)
   Ate (Cidade3 >=1) e (Cidade3 <=10) e (Cidade3 <> Cidade1) e (Cidade3 <> Cidade2)
   EscrevaL ("")


   se (Cidade1 = 1) entao
      Local1 <- "Curitiba"
      Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
      Leia (Passeio1)
      EscrevaL ("")
      Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
      Leia (Acidente1)
      EscrevaL ("")
   senao
      se (Cidade1 = 2) entao
         Local1 <- "Londrina"
         Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
         Leia (Passeio1)
         EscrevaL ("")
         Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
         Leia (Acidente1)
         EscrevaL ("")
      senao
         se (Cidade1 = 3) entao
            Local1 <- "Maringá"
            Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
            Leia (Passeio1)
            EscrevaL ("")
            Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
            Leia (Acidente1)
            EscrevaL ("")
         senao
            se (Cidade1 = 4) entao
               Local1 <- "Ponta Grossa"
               Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
               Leia (Passeio1)
               EscrevaL ("")
               Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
               Leia (Acidente1)
               EscrevaL ("")
            senao
               se (Cidade1 = 5) entao
                  Local1 <- "Cascavel"
                  Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
                  Leia (Passeio1)
                  EscrevaL ("")
                  Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
                  Leia (Acidente1)
                  EscrevaL ("")
               senao
                  se (Cidade1 = 6) entao
                     Local1 <- "Pinhais"
                     Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
                     Leia (Passeio1)
                     EscrevaL ("")
                     Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
                     Leia (Acidente1)
                     EscrevaL ("")
                  senao
                     se (Cidade1 = 7) entao
                        Local1 <- "Foz do Iguaçu"
                        Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
                        Leia (Passeio1)
                        EscrevaL ("")
                        Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
                        Leia (Acidente1)
                        EscrevaL ("")
                     senao
                        se (Cidade1 = 8) entao
                           Local1 <- "Colombo"
                           Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
                           Leia (Passeio1)
                           EscrevaL ("")
                           Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
                           Leia (Acidente1)
                           EscrevaL ("")
                        senao
                           se (Cidade1 = 9) entao
                              Local1 <- "Guarapuava"
                              Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
                              Leia (Passeio1)
                              EscrevaL ("")
                              Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
                              Leia (Acidente1)
                              EscrevaL ("")
                           senao
                              se (Cidade1 = 10) entao
                                 Local1 <- "Paranaguá"
                                 Escreva ("Qual o número de veículos de passeio da cidade de ", Local1,"? ")
                                 Leia (Passeio1)
                                 EscrevaL ("")
                                 Escreva ("Qual o número de acidentes fatais na cidade de ", Local1,"? ")
                                 Leia (Acidente1)
                                 EscrevaL ("")
                              FimSe
                           FimSe
                        FimSe
                     FimSe
                  FimSe
               FimSe
            FimSe
         FimSe
      FimSe
   FimSe

   Escolha Cidade2
           Caso 1
                Local2 <- "Curitiba"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 2
                Local2 <- "Londrina"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 3
                Local2 <- "Maringá"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 4
                Local2 <- "Ponta Grossa"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 5
                Local2 <- "Cascavel"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 6
                Local2 <- "Pinhais"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 7
                Local2 <- "Foz do Iguacçu"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 8
                Local2 <- "Colombo"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 9
                Local2 <- "Guarapuava"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
           Caso 10
                Local2 <- "Paranaguá"
                Escreva ("Qual o número de veículos de passeio da cidade de ", Local2,"? ")
                Leia (Passeio2)
                EscrevaL ("")
                Escreva ("Qual o número de acidentes fatais na cidade de ", Local2,"? ")
                Leia (Acidente2)
                EscrevaL ("")
   FimEscolha
   
   se (Cidade3 = 1) entao
      Local3 <- "Curitiba"
      Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
      Leia (Passeio3)
      EscrevaL ("")
      Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
      Leia (Acidente3)
      EscrevaL ("")
   senao
      se (Cidade3 = 2) entao
         Local3 <- "Londrina"
         Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
         Leia (Passeio3)
         EscrevaL ("")
         Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
         Leia (Acidente3)
         EscrevaL ("")
      senao
         se (Cidade3 = 3) entao
            Local3 <- "Maringá"
            Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
            Leia (Passeio3)
            EscrevaL ("")
            Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
            Leia (Acidente3)
            EscrevaL ("")
         senao
            se (Cidade3 = 4) entao
               Local3 <- "Ponta Grossa"
               Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
               Leia (Passeio3)
               EscrevaL ("")
               Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
               Leia (Acidente3)
               EscrevaL ("")
            senao
               se (Cidade3 = 5) entao
                  Local3 <- "Cascavel"
                  Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
                  Leia (Passeio3)
                  EscrevaL ("")
                  Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
                  Leia (Acidente3)
                  EscrevaL ("")
               senao
                  se (Cidade3 = 6) entao
                     Local3 <- "Pinhais"
                     Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
                     Leia (Passeio3)
                     EscrevaL ("")
                     Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
                     Leia (Acidente3)
                     EscrevaL ("")
                  senao
                     se (Cidade3 = 7) entao
                        Local3 <- "Foz do Iguaçu"
                        Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
                        Leia (Passeio3)
                        EscrevaL ("")
                        Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
                        Leia (Acidente3)
                        EscrevaL ("")
                     senao
                        se (Cidade3 = 8) entao
                           Local3 <- "Colombo"
                           Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
                           Leia (Passeio3)
                           EscrevaL ("")
                           Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
                           Leia (Acidente3)
                           EscrevaL ("")
                        senao
                           se (Cidade3 = 9) entao
                              Local3 <- "Guarapuava"
                              Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
                              Leia (Passeio3)
                              EscrevaL ("")
                              Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
                              Leia (Acidente3)
                              EscrevaL ("")
                           senao
                              se (Cidade3 = 10) entao
                                 Local3 <- "Paranaguá"
                                 Escreva ("Qual o número de veículos de passeio da cidade de ", Local3,"? ")
                                 Leia (Passeio3)
                                 EscrevaL ("")
                                 Escreva ("Qual o número de acidentes fatais na cidade de ", Local3,"? ")
                                 Leia (Acidente3)
                                 EscrevaL ("")
                              FimSe
                           FimSe
                        FimSe
                     FimSe
                  FimSe
               FimSe
            FimSe
         FimSe
      FimSe
   FimSe


   // Cálculo da média de veículos entre as 3 cidades escolhidas.
   
   MediaV <- (Passeio1+Passeio2+Passeio3) /3
   
   EscrevaL ("----------------------------------------------------------------------------")
   EscrevaL  ("A Média de veículos entre ", Local1, ", ", Local2, " e ", Local3, " é de aproximadamente ", MediaV:4:2, ".")
   EscrevaL ("----------------------------------------------------------------------------")
   EscrevaL ("")

   //Cálculo e demonstração dos indices de acidentes de trânsito.
   
   Indice1 <- (Acidente1*100/Passeio1)
   Indice2 <- (Acidente2*100/Passeio2)
   Indice3 <- (Acidente3*100/Passeio3)
   
   Se (Indice1 < Indice2) entao
      Se (Indice1 < Indice3) entao
         EscrevaL ("")
         EscrevaL ("----------------------------------------------------------------------------")
         EscrevaL ("O menor índice de acidentes pertence à cidade de ", Local1, " com ", Indice1:4:2, "%.")
         EscrevaL ("----------------------------------------------------------------------------")
         EscrevaL ("")
      FimSe
   FimSe
   
   Se (Indice2 < Indice1) entao
      Se (Indice2 < Indice3) entao
         EscrevaL ("")
         EscrevaL ("----------------------------------------------------------------------------")
         EscrevaL ("O menor índice de acidentes pertence à cidade de ", Local2, " com ", Indice2:4:2, "%.")
         EscrevaL ("----------------------------------------------------------------------------")
         EscrevaL ("")
      FimSe
   FimSe
   
   Se (Indice3 < Indice1) entao
      Se (Indice3 < Indice2) entao
         EscrevaL ("")
         EscrevaL ("----------------------------------------------------------------------------")
         EscrevaL ("O menor índice de acidentes pertence à cidade de ", Local3, " com ", Indice3:4:2, "%.")
         EscrevaL ("----------------------------------------------------------------------------")
         EscrevaL ("")
      FimSe
   FimSe
   
   Se (Indice1 > Indice2) e (Indice1 > Indice3) entao
      EscrevaL ("")
      EscrevaL ("----------------------------------------------------------------------------")
      EscrevaL ("O maior índice de acidentes pertence à cidade de ", Local1, " com ", Indice1:4:2, "%.")
      EscrevaL ("----------------------------------------------------------------------------")
      EscrevaL ("")
   FimSe
   
   Se (Indice2 > Indice1) e (Indice2 > Indice3) entao
      EscrevaL ("")
      EscrevaL ("----------------------------------------------------------------------------")
      EscrevaL ("O maior índice de acidentes pertence à cidade de ", Local2, " com ", Indice2:4:2, "%.")
      EscrevaL ("----------------------------------------------------------------------------")
      EscrevaL ("")
   FimSe
   
   Se (Indice3 > Indice1) e (Indice3 > Indice2) entao
      EscrevaL ("")
      EscrevaL ("----------------------------------------------------------------------------")
      EscrevaL ("O maior índice de acidentes pertence à cidade de ", Local3, " com ", Indice3:4:2, "%.")
      EscrevaL ("----------------------------------------------------------------------------")
      EscrevaL ("")
   FimSe

   EscrevaL ("")
   EscrevaL ("----------------------------------------------------------------------------")

   //Cálculo e demonstração da média dos acidentes das cidades com menos de 2000 veículos.
   
   Se (Passeio1>=2000) e (Passeio2>=2000) e (Passeio3>=2000) entao
      EscrevaL ("Nenhuma das cidades tem menos de 2000 veículos, nesse caso, não há como calcular a média desejada.")
   senao
        Se (Passeio1>=2000) e (Passeio2>=2000) e (Passeio3<2000) entao
           EscrevaL ("Apenas a cidade de ", Local3, " tem menos de 2000 veículos, nesse caso, não há como calcular a média desejada.")
        senao
             Se (Passeio1<2000) e (Passeio2>=2000) e (Passeio3>=2000) entao
                EscrevaL ("Apenas a cidade de ", Local1, " tem menos de 2000 veículos, nesse caso, não há como calcular a média desejada.")
             senao
                  Se (Passeio1>=2000) e (Passeio2<2000) e (Passeio3>=2000) entao
                     EscrevaL ("Apenas a cidade de ", Local2, " tem menos de 2000 veículos, nesse caso, não há como calcular a média desejada.")
                  senao
                       Se (Passeio1>2000) e (Passeio2<2000) e (Passeio3<2000) entao
                          Media <- (Acidente2+Acidente3)/2
                          EscrevaL ("A média de acidentes entre as cidades de ", Local2, " e ", Local3, " é de: ", Media:4:2,".")
                       senao
                            Se (Passeio1<2000) e (Passeio2<2000) e (Passeio3<2000) entao
                               Media <- (Acidente1+Acidente2+Acidente3)/3
                               EscrevaL ("A média de acidentes entre as cidades de ", Local1, ", ", Local2," e ", Local3," é de: ", Media:4:2,".")
                            senao
                                 Se (Passeio1<2000) e (Passeio2<2000) e (Passeio3>2000) entao
                                    Media <- (Acidente1+Acidente2)/2
                                    EscrevaL ("A média de acidentes entre as cidades de ", Local1, " e ", Local2, " é de: ", Media:4:2,".")
                                 senao
                                      Se (Passeio1<2000) e (Passeio2>2000) e (Passeio3<2000) entao
                                         Media <- (Acidente1+Acidente3)/2
                                         EscrevaL ("A média de acidentes entre as cidades de ", Local1, " e ", Local3, " é de: ", Media:4:2,".")
                                      senao
                                      FimSe
                                 FimSe
                            FimSe
                       FimSe
                  FimSe
             Fimse
        Fimse
   FimSe
   
   EscrevaL ("----------------------------------------------------------------------------")
   EscrevaL ("")
   
   
fimalgoritmo
