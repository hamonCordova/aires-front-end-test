# Teste de front-end para a Aires Crédito Digital 💸

![Logotipo Aires Crédito Digital](https://www.aires.digital/_nuxt/img/aires-logo-blue.031b66e.svg)

Saudações, candidato. 🖖
Gostariamos de conhecer mais sobre sua expêriencia técnica e entender como você desenvolve um projeto do zero, com uso real do que verá no seu dia a dia trabalhando na Aires. Para esse teste, você deve estar preparado para consumir e listar os dados da nossa API, que retornará dados das simulações de FGTS de um cliente fictício.

## Tecnologias e regras
 
 Abaixo, umas lista com as regras e requisitos técnicos necessários.
 Se você utilizar algo que não seja obrigatório, contará como um bônus para a sua candidatura. 👏👏
 
 Lembrando que aqui na Aires, utilizamos Vue.js e Angular 2+ como framework front-end, mas mandatoriamente Vue.js. Caso selecionado e você não souber Angular 2+, não será um problema, iremos auxiliá-lo no processo de aprendizagem do framework. 🤝🤓

### Regras
O projeto deve ser desenvolvido do zero, seguindo as regras e tecnogias requisitadas. Você deve criar um projeto do ZERO, sem uso de boilerplate ou templates já construidos anteriomente.
 
##### Obrigatório  💪
   - ###### Criar uma tela inicial que receba uma hash (string) de contato e realize uma consulta na API
     - Essa tela deve conter um input, requisitando  a hash do contato.
     - Assim que o usuário informar a hash e confirmar com o uso de um botão, deve-se fazer a requisição na API passando os parâmetros corretamente.
     - Se a API retornar com status diferente de 200, exibir mensagem em tela para o usuário, dependendo do que ocorreu.
     - Se a API retonar 200, mandar o usuário para uma página de detalhes com os dados da simulação.
   - ###### Construir a tela de detalhes com os dados obtidos
  
     - Nessa tela deve ser exibido um card para cada objeto do array retornado da API.
     - No card deve ser mostrado as seguintes informações (na ordem da sua escolha)
       - CPF
       - Nome Completo
       - Data de Nascimento
       - Data de Inclusão
       - Data de Atualização
       - Situação

##### Bônus 👀

- Na tela de listagem, incluir um filtro por situação. Esse filtro deve ser feito no front-end.

### Tecnologias
Qualquer outra coisa não listada abaixo, é opcional e a sua escolha.
| Tecnologia | Requisito |  Obrigatório |
| ---------- | --------- |  --------------- |
| Framework JS | Vue.js (2 ou 3) | Sim |
| Pré-processador JS | Typescript | Sim |
| Framework CSS | Não deve-se usar | Sim |
| Pré-processador CSS | SASS/SCSS | Sim |
| Layout | A sua escolha, contanto que desenvolvido por você (não precisa de protótipo) | Sim |
| Vue.js Framework | A sua escolha (recomendado: Nuxt.js) | Não |
| Testes Automatizados | A sua escolha | Não |
| Metodologia CSS | A sua escolha (recomendado: BEM) | Não |

### API

| URL | Parâmetro |
| ---------- | --------- |
| https://integracoes-api-stage.aires.digital/simulacao/contato-whatsapp/${hash} | ${hash}, obtida no input da tela inicial | 
> Em todas as URL's devem ser utilizadas uma key no header, `x-api-key` sendo `c6354fcd-781a-4e09-a4d8-a14df1404196` seu valor.

### Entrega do teste
Primeiramente, você pode fazer um fork desse repositório aqui, para sua conta do Github, depois disso crie uma branch nova com o seu nome (ex: nome_sobrenome), para podermos indentificá-lo.

Após terminar o desafio, você pode solicitar um pull request para a branch main do nosso repositório.
Depois disso, avise a pessoa que lhe enviou teste.


