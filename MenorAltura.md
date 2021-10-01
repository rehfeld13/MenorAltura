# MenorAltura
Nesse algoritmo calculamos a altura de 4 pessoas e definimos a menor altura dentre eles no Portugol!


programa
 // by Rehfeld13
{
	
	funcao inicio()
	{
		real altura, MenorAltura= 9000
		inteiro i = 1


		enquanto(i<=4){
			escreva("Escreva a sua altura: ")
		     leia(altura)
		      se (altura <MenorAltura){
		     MenorAltura = altura     
			}
			i++	 
	    }
	   escreva("A menor altura é: "+MenorAltura) 
 	}
}


