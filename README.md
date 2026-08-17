# gqs-algoritmo-01-py

## O que esse código faz:
Este código implementa uma função para verificar se um texto é um palíndromo
	*Um palíndromo é uma palavra, frase ou sequência de caracteres que se lê da mesma forma de trás para frente, desconsiderando espaços, pontuações, acentos e diferenças entre letras maiúsculas e minúsculas*

## Como executar:
Passo a passo para rodar a versão Java:
 *	1 - Salve o arquivo: Crie um arquivo com o nome exato de `Analisador.java` (a maiúscula importa) e cole o código Java acima dentro dele
 *	2 - Abra o terminal: Navegue até a pasta onde você salvou o arquivo `Analisador.java`
 *	3 - Compile o código (`javac`):Execute o comando abaixo para gerar o arquivo binário `.class`:
```javac Analisador.java```
		*(Se o terminal não exibir nenhuma mensagem de erro e pular de linha, a compilação foi bem-sucedida)*
 *	4 - Execute o programa (`java`): Execute a classe compilada chamando apenas o nome dela (sem a extensão `.java` ou `.class`):
		```java Analisador```
	    O resultado impresso no seu terminal será:
		```Teste 1: true
		Teste 2: false```

## Exemplo de Saída:
O console exibirá exatamente o seguinte texto:
    ```Teste 1: True
		Teste 2: False```

Embora a frase "Socorram-me, subi no ônibus em Marrocos" seja um palíndromo famoso, a expressão regular utilizada (`[^a-zA-Z0-9]`) remove caracteres acentuados
*  A palavra `ônibus` vira apenas `nibus` (o caractere `ô` é excluído)
*  Sem a letra "o", a frase perde a simetria ao ser invertida, fazendo com que o teste real retorne False
