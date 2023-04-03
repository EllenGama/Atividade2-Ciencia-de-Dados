# Atividade-2-Ciencia-de-Dados
Você e sua equipe de programadores foram contratados para desenvolver um app de vendas para uma lanchonete. Você ficou com a parte de desenvolver a interface do cliente para retirada do produto.


-----INÍCIO-----

print('Sejam bem vindos a Hamburgueria da Ellen da Silva Gama')
#Identificador pessoal RU4064718
print('Cardápio')
print('    Código       Descrição               Valor R$')
print('     100     Cachorro-quente. . . . . . .  9,00  ')
print('     101     Cachorro-quente Duplo. . . . 11,00  ')
print('     102     x-Egg. . . . . . . . . . . . 12,00  ')
print('     103     X-Salada . . . . . . . . . . 13,00  ')
print('     104     X-Bacon. . . . . . . . . . . 14,00  ')
print('     105     X-Tudo . . . . . . . . . . . 17,00  ')
print('     200     Refrigerante Lata. . . . . .  5,00  ')
print('     201     Chá Gelado . . . . . . . . .  4,00  ')
print('Ou digite Sair para encerrar o programa.')
print('Sejam bem vindos a Hamburgueria da Ellen da Silva Gama')
#Identificador pessoal RU4064718
print('Cardápio')
print('    Código       Descrição               Valor R$')
print('     100     Cachorro-quente. . . . . . .  9,00  ')
print('     101     Cachorro-quente Duplo. . . . 11,00  ')
print('     102     x-Egg. . . . . . . . . . . . 12,00  ')
print('     103     X-Salada . . . . . . . . . . 13,00  ')
print('     104     X-Bacon. . . . . . . . . . . 14,00  ')
print('     105     X-Tudo . . . . . . . . . . . 17,00  ')
print('     200     Refrigerante Lata. . . . . .  5,00  ')
print('     201     Chá Gelado . . . . . . . . .  4,00  ')
print('Ou digite Sair para encerrar o programa.')
soma = 0
ru4064718 = 0

while ru4064718 == 0:
    cod = input('Informe o código desejado: ') #selecinar código do produto
    if cod == 'Sair':
        print('Encerrou o programa. Valor Total: {:.2f} ' . format(soma))
        break
    elif cod == '100':        #código do item escolhido
        soma += 9             #valor que será somado
        print('Você selecionou Cachorro-quente de R$ 9,00. Valor atual: R$ {:.2f}'.format(soma))
    elif cod == '101':
        soma += 11
        print('Você selecionou Cachorro-quente Duplo de R$ 11,00. Valor atual: R$ {:.2f}'.format(soma))
    elif cod == '102':
        soma += 12
        print('Você selecionou X-Egg de R$ 12,00. Valor atual: R$ {:.2f}'.format(soma))
    elif cod == '103':
        soma += 13
        print('Você selecionou X-Salada de R$ 13,00. Valor atual: R$ {:.2f}'.format(soma))
    elif cod == '104':
        soma += 14
        print('Você selecionou X-Bacon de R$ 14,00. Valor atual: R$ {:.2f}'.format(soma))
    elif cod == '105':
        soma += 17
        print('Você selecionou X-Tudo de R$ 17,00. Valor atual: R$ {:.2f}'.format(soma))
    elif cod == '200':
        soma += 5
        print('Você selecionou Refrigerante Lata de R$ 5,00. Valor atual: R$ {:.2f}'.format(soma))
    elif cod == '201':
        soma += 4
        print('Você selecionou Chá Gelado de R$ 4,00. Valor atual: R$ {:.2f}'.format(soma))
    else:
        print('Opção inválida')
        #Erro ao digitar número inválido
        continue
    desisao = int(input ('Deseja algo mais? \n 1 - Sim \n 0 - Não \n')) #Verificar se deseja incluir mais item ou não.
    if desisao == 1:
        continue
    else:
        print('Total a pagar é: R$ {:.2f}'. format(soma))  #Total final da compra

break

-----FIM-----
