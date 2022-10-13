# Desafio de Projeto com Git/GitHub da DIO
Repositório criado para o Desafio de Projeto.

O programa soma venda do funcionario dos ultimos 4 meses, faz a media de venda e informa o valor bonus que ele ira ganhar.
	

	programa
	{
		
		funcao inicio()
		{
			real janeiro,fevereiro,marco,abril,total,media,bonus
			cadeia funcionario
			
			escreva("Digite o nome do funcionario:")
			leia(funcionario)
			escreva("Digite o valor da venda:")
			leia(janeiro)
			escreva("Digite o valor da venda:")
			leia(fevereiro)
			escreva("Digite o valor da venda:")
			leia(marco)
			escreva("Digite o valor da venda:")
			leia(abril)
	
			total = (janeiro+fevereiro+marco+abril)
			media = (total)/4
			bonus = (media/10)
	
			escreva("O funcionario: " + funcionario + " Seu valor total de vendas é: " + total + " E obteve uma media " + media + " O seu bonus é no valor de: " + bonus + " Parabens")
		}
	}
