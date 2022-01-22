# Ingresso-Carrinho
Ticket para ingressar no carrinho
#include <stdio.h>
#include <stdlib.h>
#include <stdio.h>



int main()
{
    int ingressos, numero, debito, credito, dinheiro;
    
    printf("\n\n\t\t-**** Bem vindo ao nosso Parque!! ****\nNosso endereço é: \nRua: Parque dos carrinhos que batem, N. 00, Avenida Bate-Bate.\nPara mais informações, entre em contato pelo número: (16) 0000-0000");
    printf("\n\n1 - Comprar ingressos;\n2 - Sair.\nEscolha a opção desejada: ");
    scanf ("%d", &numero);
    
    switch(numero)
    {
        case 1: 
          system("clear");
           printf("Valor por ingresso: R$ 5,00\nTempo: 10 minutos\n\nQuantos ingressos deseja comprar: ");
           scanf("%d", & ingressos);
          
             printf("\n3 - Cartão de débito;\n4 - Cartão de Crédito;\n5 - Dinheiro.\nQual a forma de Pagamento: ");
             scanf("%d", & debito, "%d", credito, "%d", dinheiro);
                
            case 3:
            system("clear");
                printf("\n\n**************************************************************\nValor Total: R$%d,00\t//   Tempo Total: %d minutos\nForma de Pagamento: Cartão de débito.\nRua: Parque dos carrinhos que batem, N° 00, Avenida Bate-Bate.\nTelefone: (16) 0000-0000\n**************************************************************", ingressos * 5, ingressos * 10);
            break;
            
            case 4:
            system("clear");
                printf("\n\n**************************************************************\nValor Total: R$%d,00\t//   Tempo Total: %d minutos\nForma de Pagamento: Cartão de Crédito.\nRua: Parque dos carrinhos que batem, N° 00, Avenida Bate-Bate.\nTelefone: (16) 0000-0000\n**************************************************************", ingressos * 5, ingressos * 10);
            break;
            
            case 5:
            system("clear");
                printf("\n\n**************************************************************\nValor Total: R$%d,00\t//   Tempo Total: %d minutos\nForma de Pagamento: Dinheiro.\nRua: Parque dos carrinhos que batem, N° 00, Avenida Bate-Bate.\nTelefone: (16) 0000-0000\n**************************************************************", ingressos * 5, ingressos * 10); 
            break;
           
          
        case 2:
          system("clear");
          printf("obrigada pela vista, tenha um bom dia!");
          break;
    }
    system ("pause");

    return 0;
}
