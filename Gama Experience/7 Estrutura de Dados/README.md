# Gama Experience [Hacker]

<h2 align="center">7. Estrutura de Dados</h2>

- 7.1 - Estrutura De Dados – Introdução
- 7.2 - Pilhas I
- 7.2.1 - Pilhas II
- 7.3 - Filas e Listas
- 7.4 - Busca I
- 7.4.1 - Busca II
- 7.5 - Algorítimos de Ordenação I
- 7.5.1 - Algorítimos de Ordenação II

 ```javascript
    var valores = {5, 8, 10, 22, 45, 38}
   
    function busca(num) {
        for (i = 0; i < 6; i++) {
            if (num == valores[i]) {
            return i;
            }
        }
        return -1;
    }


    // usando a nossa ferramenta de busca 

    console.log(busca(10));
    console.log(busca(50));
```      