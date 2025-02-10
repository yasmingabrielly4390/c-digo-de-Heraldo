programa
{
    funcao inicio()
    {
       
        real numeros[10], quadrados[10]
        para (inteiro i = 0; i < 10; i++)
        {
            escreva("Digite um número real: ")
            leia(numeros[i])
            quadrados[i] = numeros[i] * numeros[i]
        }

        escreva("\nValores ao quadrado:\n")
        para (inteiro i = 0; i < 10; i++)
        {
            escreva("Número: ", numeros[i], " | Quadrado: ", quadrados[i], "\n")
        }
    }
}



