# Logica-
programa {

     inclua biblioteca Util --> U
    inteiro numero
    inteiro inicial, final, alea
    cadeia inicio

  funcao inicio() {
    
    escreva ("Teste a sua sorte na loteria! Digite 'Iniciar': ")
    leia (inicio)
    escreva ("Os numeros gerados foram: ")
    
    para (numero = 1; numero <= 6; numero++){
    escreva (alea, " ", "\n")

    inicial = 1
    final = 50

    alea = U.sorteia(inicial, final)
    }

    escreva ("Obrigado por jogar! Confira se seus números foram")
    escreva ("os vencedores na tela!")
  }
}


programa
{
inclua biblioteca Util --> u
inteiro numero[5]
inteiro i
inteiro inicial, final, alea

	
	funcao inicio()
	{
	inicial = 1
	final = 50

	escreva("Números sorteados \n")

	para (i = 0; i <= 4; i++) {
		alea = u.sorteia(inicial, final)
		numero[i] = alea

		escreva(alea, " ")
		
	}
		
	}
}

programa
{ 
	
inteiro vet[10]
	inteiro i
	

	
	funcao inicio()
	{
	
		para(i = 0; i <  10; i++) {
			escreva("Digite os seus números: ")
			leia(vet[i])
	
		
		
			}
		

		para (i = 10; i>= 0; i--) {
			escreva(i, " ")
		}
			
	}
}







programa
{
 inteiro alunos[10]
  inteiro mat, pos, cont
  caracter controle = 's'
	
	funcao inicio()
	{
		para(pos = 0; pos < 10; pos++) {
			enquanto(verdadeiro) {
			escreva("Digite a matricula: ")
			leia(mat)
              
						
			//Verificar se a matricula ja existe
			para(cont = 0; cont < 10; cont++)
				se(mat == alunos[cont]) {
					escreva("Valor ja eiste!! digite outro")
					controle = 'n'
				}
			

			//Verifica se número ou intervalo é valido
		se ((mat < 100) ou (mat > 200)) {
			escreva("Valor invalido")
			controle = 'n'
	}

		// Se matricula é valida , efetua-la
		se (controle != 'n') {
			alunos[pos] = mat
			pare
		}
		//libera o cadastro de dados do vetor 
		controle = 's'
			}
		}
		//Ordenar valores na tela e mostra=lo
	
		
		
		
	
	
	}
}






programa
{
 inteiro num1[5]
  inteiro num2[5]
  inteiro i
	
	funcao inicio()
	{
		escreva("Digite o número que você deseja multiplicar: \n")
		para (i = 0; i<= 4; i++) {
		escreva("Digite o número: ")
		leia(num1[i])
		num2[i] = num1[i]* 3
	}
	     para (i = 0; i<= 4; i++){
		escreva("\nOs Valores são: \n" +num1[i] , " e ", + num2[i] )
	     }
	   }
		
}

