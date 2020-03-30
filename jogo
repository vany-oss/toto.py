#Usei estrutura de repitiçao, com loop infinito...fiz varios if e elif. e os nr dos preiomois sao breaks. mas vi k estava a ser interessante desenvolvi...ha um erro  um nr prémio nao sera imprimido e nr 25 ele n emprimi o ganho mas cantabilisa isso pk fiz um break se a tentativa for maior k volaor apostado.
print('\033[44mOla! ---->Seja Benvindo Ao TotoGame<----:\033[m\n\033[36mHá 5 Números dentro do quadro abaixo,que\nSe for acertado à primeira será o Jackpot de \033[32m500$.\nTens 10 Tentativas para Ganhares 2500$.\nMas aprtir de 11 Tentativas Os Nr Prémios Começam\nA serem revelados e o Jackpot Será INVÁLIDO. \033[m')
print('\033[42mHá Também 2 Números Chaves que Dà 10$ \nSe acertares qual foi.\033[m')
print('Os Jackpot começam a sererem \033[41mINVALIDADOS\033[m\nApartir de \033[33m11*\033[m Tentativas,e acabam em \033[33m22*\033[m Tentativas.\nSó Ficam os prémios das Chaves.\033[32mBoa Sorte.\033[m ')
print('\033[41mO Valor do Jogo é 2$, por Tentativas.\033[m\033[31m \nPara Sair Degite nr 99:\033[m')
print('\033[33m[0 ] 1] 2 ] 3] 4] 5] 6] 7] 8]  9] 10]\n[11]12] 13]14]15]16]17]18]19] 20] 21] \n[22]23]24]25]26]27]28]29]30]31]32]33|\n[34]35]36]37]38]39]40]41]42]43]44]45]\n[46]47]48]49]50]\033[m')
n1 = int(input('\033[32mQuantos Queres Apostar\033[m?'))
print('\033[36mATENSÃO! Com {}.0 Euros Dà-te o direiro à {} \nTentativas.Boa Sorte.\033[m'.format(n1,n1/2))
soma = 0
ten = 0
ganhoeu = 0
ponto = n1/2
jack = 0
ch =0
while True:
    print('-' * 40)
    print('\033[33m[0 ] 1] 2 ] 3] 4] 5] 6] 7] 8]  9] 10]\n[11]12] 13]14]15]16]17]18]19] 20] 21] \n[22]23]24]25]26]27]28]29]30]31]32]33|\n[34]35]36]37]38]39]40]41]42]43]44]45]\n[46]47]48]49]50]\033[m')
    print('-' * 40)
    print ('\033[32mTenta Ganhar Algum Dinheiro.\033[m')
    #n1 =float(input('\033[35mQuantos Euros quer Apostar? -->\033[m'))
    num =(int(input('Qual é o teu palpite?')))
    if num == 25:
       
        ponto += +500
        jack += 500
    if ten  == n1 / 2:
        print('\033[31mO Teu saldo e de 0.0$.Fim Do Jogo.')
        break
       
        print('\033[42mPARABENS GANHASTE 500$.\033[m')
    elif ten >= 10:
         print('1* Jackpot INVALIDO o nr era \033[32m25\033[m')
        #break
    if num == 21:  
        ponto += + 10
        ch += 10
   
        print('Prabens!Ganhaste\033[32m 10$, 21\033[m é Nr Chave')
    if num == 17:
        ponto += + 500
        jack += 500
        print('\033[42mPARABENS GANHASTE 500$.\033[m')
    elif ten >= 13:
        print('2* Jackpot INVALIDO o nr era \033[32m17\033[m')
        #break
    if num == 37:
        ponto += + 500
        jack += 500
        print('\033[42mPARABENS GANHASTE 500$.\033[m')
    elif ten >= 16:
        print('3* Jackpot INVÁLIDO o nr era \033[32m37\033[m')
        #break
    if num == 30:
        ponto += + 10
        ch+= 10
        print ('\033[36mPARABÉNS. Ja Ganhaste 10$ 30 é nr Chave\033[m')
    if num == 47:
        ponto += + 500
        jack += 500
        print('\033[42mPARABENS GANHASTE 500$.\033[m')
    elif ten >=19:
        print('4* Jackpot INVÁLIDO o nr era \033[32m47\033[m')
        #break
    if num == 33:
        ponto += +500
        jack += 500
        print('\033[42mPARABENS GANHASTE 500$.\033[m')
    elif ten >=21:
   
        print('Último Jackpot INVALIDO o nr era \033[32m33\033[m\n\033[44mJà Ganhei {}$ de ti Parar Saires do Jogo Degita 99\033[m'.format(ganhoeu))
    if num == 99:
    #elif num == 99:
        break
    ten += 1
    soma += num
    ganhoeu = 2 * ten
    ponto += 1
    jack += 1
    ch += 1
print('\033[42mFizeste {} Tentativas e a soma Entre:\033[m\nTodos os Números que Degitate é: \033[33m{}\033[m :\033[m'.format(ten, soma))
print('\033[42mEu ganhei {} $ e Tu ficaste com {}$ No teu Saldo de {} Euros:\033[m'.format(ganhoeu  , n1 - ganhoeu  ,n1))
#print('\033[44m---->voçe saiu----->Volte Sempre: comMaisDINHEIRO-->(-:)\033[m')
print('\033[44mNo Total Ganhaste {} Euros, do Jackpot e {} Euros Nas Chaves.\033[m'.format(jack -ten,ch - ten))
print('\033[44m---->voçe saiu----->Volte Sempre: comMaisDINHEIRO-->(-:)\033[m')
