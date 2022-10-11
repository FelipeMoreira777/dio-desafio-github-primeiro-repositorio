# Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o Desafio de Projeto.

Sistema de locadora de filme para analisar a idade e se o cliente é maior ou menor de 18anos.
	

	programa
	{
	
	 funcao inicio()
	 {
		caracter nome,filme
		inteiro idade 
		cadeia cliente
	
		escreva ("Digite o seu nome: ")
		leia(nome)
		escreva ("Digite o nome do filme: ")
		leia(filme)
		escreva ("Digite a sua idade: ")
		leia(idade)
	
		se (idade>=18) {
			escreva ("Você pode locar essa filme")
		}
	
		senao { 
		     escreva ("Você não pode locar esse filme escolha outro")
		}     
	  }
	}
