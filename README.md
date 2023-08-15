# Projeto Integrador - Modelo

_(Coloque aqui o nome do seu projeto.)_

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.
_(Coloque aqui uma breve descrição do seu projeto.)_

Cadastre seu projeto nesse [link](https://docs.google.com/spreadsheets/d/1V_1h6hJ3cNLK5eY7Hy5B8hQDxYy8GcZNHyFfC2HdawI/edit?usp=sharing).

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Equipe:

- [Aluno1](github.com/aluno1)
- [Aluno2](github.com/aluno2) 
         
Links do projeto:
(_Coloque aqui os links para a documentação do projeto e os repositórios e plubicação do backend e frontend._)

- [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
- Backend: [Repositório](github.com/marcoandre/pi-backend) e [Publicação](https://pi-backend.herokuapp.com/)
- Frontend[Repositório](github.com/marcoandre/pi-frontend) e [Publicação](https://pi-frontend.herokuapp.com/)

**Como usar esse modelo para o Projeto Integrador**

_(Essa parte pode ser apagada depois.)_

1. Faça um fork desse repositório para a sua conta do GitHub.
2. Clone o repositório para o seu computador.
3. Abra o arquivo README.md no seu editor de texto favorito (recomendamos o [Visual Studio Code](https://code.visualstudio.com/)).
4. Tenha instaladas as seguintes extensões:
   - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
   - [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
5. Edite o arquivo README.md com as informações do seu projeto.

# 1. Desenvolvimento

_(Escolha um dos modelos de sistemas para desenvolver o projeto. Apague as informações desnecessárias depois.)_

- As equipes serão avaliadas por cada etapa da documentação e entregas realizadas.
- Cada equipe deverá escolher um sistema para o desenvolvimento das atividades, a partir dos modelos apresentados.

**1.1 Modelos de Sistemas**

**Nessa parte a equipe deve escolher um dos modelos de sistemas para desenvolver o projeto. Ao escolher, escreva uma breve descrição do sistema e o motivo da escolha e pode apagar os outros modelos.**

**1.1.1 Ponto de Vendas (PDV)**

**Gerenciamento de vendas para uma padaria**
A empresa MebbersMotors é uma loja de peças automotivas, vendendo peças para veículos. a loja opera desde 1998, o dono se chama Marcos, e tem 5 funcionários trabalhando (3 atendentes, um almoxarifado e um zelador para a limpeza do local.)a loja opera de forma presencial na loja física. Com o grande crescimento de sua demanda, Marco decide comprar um sistema de gerenciamento para solucionar o maior problema dentro da empresa, a gestão e mobilidade dos produtos que o mesmo vende e os relatórios de forma prática.

# 2. Situação Problema

A empresa MebbersMotors é uma loja de peças automotivas, vendendo peças para veículos. a loja opera desde 1998, o dono se chama Marcos, e tem 5 funcionários trabalhando (3 atendentes, um almoxarifado e um zelador para a limpeza do local.)a loja opera de forma presencial na loja física.
O cliente se dirige ao atendente, solicita um produto, o mesmo se dirige ao estoque(prateleiras), checa se há o produto disponível com o almoxarifado, subtrai as respectivas quantidades dos produtos e por fim entrega ao cliente após o pagamento. O registro das compras é feito com anotação em um caderno, assim como a entrada e saída de produtos e o relatório geral da loja.
O faturamento é realizado de forma mensal, fazendo os cálculos da entrada de dinheiro subtraindo todas as despesas.
Contudo diante dos problemas de gerenciamento de vendas, estoque, empresa necessita de um sistema para possibilitar o gerenciamento e vendas local deixando a compra mais prática, sem a necessidade de consultar fisicamente o estoque, evitando demoras desnecessárias e a possibilidade de não haver peças em estoque.

# 3. Descrição da proposta

O software possibilitará com que a Mebbersmotors faça um atendimento muito mais rápido e preciso, pois assim que o cliente for atendido, o mesmo irá consultar no sistema se o produto está disponível no estoque, por meio do sistema. Contando com três usuários diferentes, o Administrador, fazendo a gestão dos produtos, relatórios e demais informções; Atendente, podendo realizar o pedido do produto ao almoxarifado; e por fim o Almoxarifado, podendo apenas consultar no estoque se há disponibilidade do produto.

# 4. Regras de negócio

Regras de Negócio

RN01: Para realizar um atendimento é necessário abrir uma comanda, sendo uma por CPF
RN02: Para adicionar um produto no carrinho da comanda, é necessário que o produto esteja devidamente cadastrado no sistema da loja.
RN03: Para realizar a compra é necessário uma comanda com pedidos cadastrados ma mesma.
RN04: Para concluir uma compra, é necessário que o pagamento da comanda seja aprovado.
RN05: Os atendentes devem ter um cadastro no sistema, contendo foto, nome e cargo.

# 5. Requisitos funcionais

  Requisitos funcionais 
  
  RF01: O sistema deve identificar o tipo do usuário e autenticá-lo. 
  RF02: O sistema deve ter uma interface diferente para cada tipo de usuário.
  RF03: O sistema deve ser capaz de registrar novos usuários
  RF04: O sistema deve ser capaz de consultar o estoque de produtos disponíveis
  RF05: O sistema deve ser capaz de cadastrar novos produtos no estoque atual.
  RF06: O sistema deve ser capaz de adicionar novos produtos no carrinho

# 6. Requisitos não funcionais



  Requisitos não funcionais 

- **R.N.F. 01 - Navegador homologado:** O sistema deverá ser homologado para os navegadores Google Chrome e Mozilla Firefox.
- **R.N.F. 02 - Processador:** É recomendado para o sistema no mínimo um processador Intel i3, similar ou superior a geração 7100 ou AMD Ryzen 3 da geração similar ou superior ao 3100, para que o servidor funcione em sua melhor performance.
- **R.N.F. 03 - Memória RAM:** é recomendável que o sistema possua no mínimo 2GB de RAM para melhor performance.
- **R.N.F. 04 - Arquitetura:** Será utilizada a arquitetiura MVC para o desenvolvimento do sistema, com uso de uma API REST para comunicação com o banco de dados.
- **R.N.F. 05 - Banco de dados:** O sistema será implementado com o banco de dados MySQL.
- **R.N.F. 06 - Conexão com banco de dados:** Para conexão com o banco de dados, o sistema utilizará a ferramenta de MySQL Connector.
- **R.N.F. 07 - Implementação:** O sistema deverá ser desenvolvido com linguagem Python, Javascript, HTML5, CSS3 e SQL.
- **R.N.F. 08 - Segurança:** Ficará a critério do responsável do estabelecimento a segurança dos acessos ao sistema, tendo consciência das pessoas que possua permissão para acesso.
- **R.N.F. 09 - Ambiente de Desenvolvimento Integrado (IDE):** Para criação do sistema, será utilizado o editor de texto Visual Studio Code.
- **R.N.F. 10 - Disponibilidade:** O sistema irá atender 99% do tempo de uso, somente ocorreria problemas de cadastro, remoção, inserção ou alteração em casos de falta de rede ou energia.
- **R.N.F. 11 - Legais:** O sistema deve atender às exigências da LGPD (Leis Gerais da Proteção de Dados).


# 7. Diagrama de Caso de Uso

 **Diagrama de caso de uso feito em papel e caneta**


---
