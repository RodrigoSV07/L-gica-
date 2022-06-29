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
