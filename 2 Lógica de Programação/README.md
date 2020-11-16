# Gama Experience [Hacker]

<h2 align="center">2. Lógica de Programação</h2>

- 2.1 - Algorítimos
- 2.2 - Variáveis e Operações
- 2.3 - Decisões
- 2.4 - Repetições

# Exemplo de formulário para captura de Leads do assignment Show me the Leads

## Resumo

- Você receberá a URL exclusiva de sua equipe
- O Formulário deverá executar um POST nessa URL
- Deverão ser enviados name e email
- A validação desses dados deverá ser feita no próprio formulário HTML (Detalhes abaixo)
- Você poderá enviar o parametro redirectTo com um input hidden para direcionar o usuário para uma outra página após preenchimento
- Você poderá enviar o parametro debugMode com valor 'true' para testar o funcionamento sem salvar seus testes

## Configurando o formulário

Utilizando as propriedades method e action vamos configurar a maneira que o formulário envia os dados.

#### METHOD

Essa propriedade indica qual método será colocado no cabeçalho da requisição, nesse caso vamos colocar POST pois estamos criando um registro em nosso backend. Mais informações em https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods

#### ACTION

Essa propriedade indica para qual URL os dados serão enviados, esse dado será entregue a vocês assim que o assignmento começar.


```html
<form method="POST" action="URL do seu time">
</form>
```
