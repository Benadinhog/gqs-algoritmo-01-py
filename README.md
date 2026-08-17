
## O que esse código faz:
Este código implementa uma função para verificar se um texto é um palíndromo
	*Um palíndromo é uma palavra, frase ou sequência de caracteres que se lê da mesma forma de trás para frente, desconsiderando espaços, pontuações, acentos e diferenças entre letras maiúsculas e minúsculas*

## Como executar:
Passo a passo para rodar a versão Java:
 *	1 - **Salve o arquivo:** Crie um arquivo com o nome exato de `analisar.py`
 *	2 - **Abra o terminal:** Navegue até a pasta onde salvou o arquivo
 *	3 - **Execute o comando:** Digite o comando abaixo e aperte Enter:

~~~
python analisar.py
~~~

*(Nota: Em alguns sistemas como macOS ou Linux, o comando exato pode ser `python3 analisar.py`)*

## Exemplo de Saída:
O console exibirá exatamente o seguinte texto:

~~~
Teste 1: True
Teste 2: False
~~~

Embora a frase "Socorram-me, subi no ônibus em Marrocos" seja um palíndromo famoso, a expressão regular utilizada (`[^a-zA-Z0-9]`) remove caracteres acentuados
*  A palavra `ônibus` vira apenas `nibus` (o caractere `ô` é excluído)
*  Sem a letra "o", a frase perde a simetria ao ser invertida, fazendo com que o teste real retorne False
