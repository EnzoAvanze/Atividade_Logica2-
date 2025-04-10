EX 1
programa {
  funcao inicio() {
    real n1,
    escreva("Digite um número\n")
      leia(n1)
    enquanto(n1>0){
      se(n1%2==0){
        escreva("Seu número é par!")
        escreva("\nDigite um número\n")
      leia(n1)
      }senao escreva("Seu número é impar!")
      escreva("\nDigite um número\n")
      leia(n1)
    }
  }
}

EX2
programa {
  funcao inicio() {
    real n1,n2,n3
    enquanto(n1>0){
      escreva("Digite um número\n")
      leia(n1)
      escreva("Digite outro número\n")
      leia(n2)
      n3=n1/n2
      se(n2>0){
      escreva("o resultado é: ",n3,"\n")
      }senao escreva("error")
    }
  }
}

EX3
programa {
  funcao inicio() {
     inteiro numero
    real numero
escreva("Digite um numero: ")
      leia(numero)

    enquanto (numero >= 10 e numero <= 50){
      escreva("\nSeu numero está entre 10 a 50")
      escreva("\nDigite um numero: ")
      leia(numero)
    } 
      escreva("Seu numero não está no intervalo de 10 a 50")
    }
}

EX4
programa {
  funcao inicio() {
     inteiro numero
        
        escreva("Digite um número inteiro positivo para a contagem regressiva: ")
        leia(numero)
        
        se (numero < 0) {
            escreva("Por favor, digite um número positivo.\n")
        } senao {
            escreva("Contagem regressiva iniciando de ", numero, " até 0:\n")
            
            para (inteiro i = numero; i >= 0; i--) {
                escreva(i, "\n")
            }
            
            escreva("Contagem regressiva concluída!\n")
        }
  }
}

EX5
programa {
  funcao inicio() {
    inteiro senha=0, nova
    escreva("Crie uma senha apenas com numeros inteiros\n")
    leia(senha)

    escreva("Informe sua senha\n")
    leia(nova)
    enquanto (nova!=senha){
    escreva("Confirme sua senha novamente\n")
    leia(nova)



  }}
}

EX6
programa {
  funcao inicio() {
    inteiro n1
    escreva("Digite um numero\n")
    leia(n1)
    escreva("resultado\n",n1*1,"\n",n1*2,"\n",n1*3,"\n",n1*4,"\n",n1*5,"\n",n1*6,"\n",n1*7,"\n",n1*8,"\n",n1*9,"\n",n1*10)

  }
}

EX7
programa {
  funcao inicio() {
    cadeia n1,n2,n3
    escreva("\nEscreva uma letra:\n")
    leia(n1)
    enquanto(n1>="a" ou n1<="z" ou n1>="A" ou n1<="Z"){
      se(n1=="a" ou n1=="e" ou n1=="i" ou n1=="o" ou n1=="u" ou n1=="A" ou n1=="E" ou n1=="I" ou n1=="O" ou n1=="U"){
        escreva("\nSua letra é uma vogal\n")
        escreva("\nEscreva uma letra:\n")
        leia(n1)
      }senao{escreva("\nSua letra é uma consoante\n")
      escreva("\nEscreva uma letra:\n")
      leia(n1)
    }
    }
  }
}

EX8
programa
{
    funcao inicio()
    {
        real peso, altura, imc

        escreva("Digite o peso (kg): ")
        leia(peso)

        enquanto (peso >= 0)
        {escreva("Digite a altura (m): ")
          leia(altura)

          se (altura > 0)
          {imc = peso / (altura * altura)
           escreva("IMC: ", imc)
           se (imc < 18.5)
             {escreva("\nAbaixo do peso\n")
                }
                senao
                {se (imc < 25)
                    {escreva("\nPeso normal\n")
                    }
                    senao
                    {se (imc < 30)
                        {escreva("\nSobrepeso\n")
                        }
                        senao
                        {escreva("\nObesidade\n")
                         escreva("\n Digite o peso (kg): ")
                          leia(peso)
                        }
                    }
                }
            }
        }
    }
}

EX9
programa{ 
  funcao inicio() {

  inteiro a1,a2,a3,a4,a5
  escreva("\nInforme um numero: \n")
  leia(a1)
  enquanto (a1>0) {
    escreva("\nInforme um numero: \n")
    leia(a1)
    
    }
  }
}

EX10
programa { 
  funcao inicio() {
    inteiro a1,a2,a3,a4,a5
    enquanto (a1>0){
    escreva("\nDigite Sua Idade: \n")
    leia(a1)
    se(a1==18)
      {escreva("Idade Igual")}
      senao se(a1<18)
      {escreva("Menor de Idade")}
      senao {escreva("Superior de 18 Anos")}
    }
  }
}
