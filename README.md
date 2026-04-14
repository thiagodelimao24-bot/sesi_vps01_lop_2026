
#Titulo: VPS01
## Verificação Pratíca Somativa 01
Arquivos gerados durante a avaliação de Lógica de programação, algoritmos e fluxogramas

## Tecnologias

|Tecnologia|Utilidade|
|:-:|-|
|Linguagem **C** |Desenvolvimento|
|IDE |Embarcadeiro **DevC++**|
|Draw.oi para |desenhar os *Fluxogramas*|
|Bloco de notas |*portugal* lógica|

##como testar
- 1 clone este repositor 
- 2 Abra os arquivos .c como DevC++
- 3 Pressione F11 para compliar executar

## Exemplo de codígo
```c
#include<stdio.h>
#include<windows.h>
void main(){
	SetConsoleOutputCP(CP_UTF8);
	char nome[20], sexo;
	int idade;
	printf("Digite seu nome, sexo m/f e idade\n");
	scanf(" %s %c %d", &nome, &sexo, &idade);
	if(sexo == 'm'){
		if(idade > 65){
			printf("O atendimento do paciente %s é prioritário", nome);
  		}else{
		  	printf("O atendimento do paciente %s é normal", nome);
  		}
   }else{
      if(idade > 60){
	  	printf("O atendimento do paciente %s é prioritário", nome);
      }else{
      	printf("O atendimento do paciente %s é normal", nome);
	  }
    }
    getch();
}
```
|[Fluxograma](./triagem.png).
