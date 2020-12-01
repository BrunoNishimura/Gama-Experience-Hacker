# Gama Experience [Hacker]

<h2 align="center">2. Lógica de Programação</h2>

- 2.1 - Algorítimos
- 2.2 - Variáveis e Operações
- 2.3 - Decisões
- 2.4 - Repetições
<hr>

- <b>2.1 - Algorítimos</b>
<p>Algoritmo é uma sequência finita de passos (Instruções/Comandos) ordenados, cujo objetivo é a resolução de um problema através da transformação da informação (dados);</p>
<p>Entender que as instruções podem ser executadas de forma REPETITIVA e também pode haver alternativas de instruções</p>
- <b>2.2 - Variáveis e Operações</b><br>
<b>Operações Aritméticas: + - * / %</b><br>
<b>Operações Relacionais:</b> > >= < <= == !><br>
<b>Operações Lógicas:</b> AND(&&) OR(||) NOT(!) <br>

- <b>2.3 - Decisões</b><br>
<p>Indentação: Afastar o texto da sua margem para te ajudar na orientação visual. Organize os seus códigos!</p>
<p>Sempre temos que informar a máquina do que ela deve fazer<p>

<h1>Obseervações:</h1> 
<b>Decisões Alinhadas!</b>

```javascript
INICIO
    
    DECLARE NOTA1, NOTA2, MEDIA
    
    LEIA (NOTA1)
    LEIA (NOTA2)

    MEDIA = (NOTA1 + NOTA2) / 2

    ESCREVA ("A MEDIA FINAL VALE")
    ESCREVA (MEDIA)

    SE MEDIA >9 ENTAO
        ESCREVA ("CONCEITO A")
    SENAO
        SE MEDIA > 7 ENTAO
            ESCREVA ("CONCEITO B")
        SENAO
            SE MEDIA > 5 ENTAO 
                ESCREVA ("CONCEITO c")
            SENAO
                ESCREVA ("REPROVADO")
            FIM-SE    
        FIM-SE
    FIM-SE    
FIM
```

- <b>2.4 - Repetições</b>
<p>Trabalhando com repetições: Neste caso foi trabalhado uma sequência de instruções, em um bloco de repetição ao invés de ficar imprimindo os resultados um por um deixando o código imenso. Fácil, rápido e de uma maneira muito eficiente.</p>

```javascript
INICIO
    DECLARE TAB, NUMERO, RESULTADO

    LEIA (TAB)
    NUMERO = 0

    ENQUANTO(NUMERO <= 10) FACA
        RESULTADO = NUMERO * TAB
        ESCREVA(RESULTADO)
        NUMERO = NUMERO + 1
    FIM-ENQUANTO
FIM

TAB NUMERO RESULTADO TELA
8      11      40       0
                        8
                        16
                        24
                        32
                        40
                        48
                        56
                        64
                        72
                        80

Observação: Quando o NUMERO chegou ao 11, por ele ser maior que 10 a repetição parou.
```