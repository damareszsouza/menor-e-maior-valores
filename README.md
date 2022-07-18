# menor-e-maior-valores


 
Moodle - IFRS

Programador Web - Turma 2022A
Painel Meus cursos  PW2022A  3 Lógica de Programação  3.24 Praticando um pouco...
 
3.24 Praticando um pouco...
Neste curso, você faz seu próprio tempo de estudos. Seu progresso será aferido pelos questionários denominados "Teste seu conhecimento". Entretanto, sabemos da importância em praticar, pois só assim você aperfeiçoar sua aprendizagem. Para isso, elaboramos esse livro, com algumas questões desafiadoras e seu gabarito. Utilize o menu de navegação para acessar os enunciados. Quando finalizar sua resposta, confira com o gabarito localizado logo abaixo.



 

Exercício 7: Menor e maior valor
Gabarito do Exercício 7
Exercício 7: Faça um programa que leia 100 números inteiros e no final, escreva o maior e o menor valor lido. 

OPÇÃO COM PARA

programa

{

   funcao inicio(){

      inteiro menor, maior, valor

      valor = 0

      escreva("Informe os valores: ")

      leia (valor)

      maior = valor

      menor = valor

      para(inteiro contagem = 1; contagem < 100; contagem++) {

         leia (valor)

         se(maior < valor) {

            maior = valor

         }

         se(menor > valor) {

            menor = valor

         }

      }

      escreva("O maior é: ", maior)

      escreva("O menor é: ", menor)

   }

}
