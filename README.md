# qa-doc-track-challenge
E-commerce app development with user authentication and cart functionality. Includes test cases using step-by-step and BDD methods for comprehensive quality assurance.


Criarei um plano de fluxo de trabalho de desenvolvimento e ciclo de vida de bug, seguido de duas user stories, um mind map de uma user story, dois casos de teste usando a técnica step-by-step e dois casos de teste utilizando BDD.

**Plano de Fluxo de Trabalho de Desenvolvimento e Ciclo de Vida de Bug:**

1. **Requisitos e Planejamento:**
   - Identificação das necessidades do projeto.
   - Planejamento das funcionalidades e correções de bugs a serem implementadas.

2. **Desenvolvimento:**
   - Desenvolvimento das funcionalidades.
   - Criação de casos de teste.

3. **Testes:**
   - Execução de testes funcionais.
   - Identificação de bugs.

4. **Correção de Bugs:**
   - Priorização dos bugs.
   - Desenvolvimento das correções.
   - Testes de regressão para garantir que os bugs foram resolvidos.

5. **Revisão:**
   - Revisão de código.
   - Validação das funcionalidades e correções.

6. **Aprovação:**
   - Aprovação das funcionalidades pelo cliente ou equipe de qualidade.

7. **Implantação:**
   - Implantação das funcionalidades no ambiente de produção.

8. **Monitoramento:**
   - Monitoramento contínuo das funcionalidades em produção.
   - Resolução de bugs que possam surgir após a implantação.

**User Stories:**

**User Story 1:**

- **Título:** Autenticação de Usuário
- **Descrição:** Como um usuário, desejo fazer login no aplicativo com meu e-mail e senha para acessar minha conta.

**User Story 2:**

- **Título:** Adicionar Produto ao Carrinho
- **Descrição:** Como um cliente, desejo adicionar produtos ao meu carrinho de compras para poder fazer uma compra posteriormente.

**Mind Map (para User Story 1):**

[Inserir o Mind Map aqui]

**Casos de Teste (Técnica Step-by-Step):**

**Caso de Teste 1 - User Story 1 - Autenticação de Usuário:**

1. **Pré-condições:** Usuário está na tela de login.
2. **Passos:**
   a. Insira o e-mail válido.
   b. Insira a senha correta.
   c. Clique no botão "Entrar".
3. **Resultado Esperado:** O usuário deve ser autenticado com sucesso e direcionado para a tela principal.

**Caso de Teste 2 - User Story 2 - Adicionar Produto ao Carrinho:**

1. **Pré-condições:** Usuário está logado e na página de produtos.
2. **Passos:**
   a. Selecione um produto.
   b. Clique no botão "Adicionar ao Carrinho".
3. **Resultado Esperado:** O produto deve ser adicionado ao carrinho e a contagem do carrinho deve ser atualizada.

**Casos de Teste (BDD):**

**Caso de Teste 1 - User Story 1 - Autenticação de Usuário:**

```gherkin
Funcionalidade: Autenticação de Usuário

  Cenário: Login com credenciais corretas
    Dado que o usuário está na tela de login
    Quando o usuário insere seu e-mail e senha corretos
    E clica no botão "Entrar"
    Então o usuário deve ser autenticado com sucesso
    E deve ser direcionado para a tela principal
```

**Caso de Teste 2 - User Story 2 - Adicionar Produto ao Carrinho:**

```gherkin
Funcionalidade: Adicionar Produto ao Carrinho

  Cenário: Adicionar um produto ao carrinho
    Dado que o usuário está logado e na página de produtos
    Quando o usuário seleciona um produto
    E clica no botão "Adicionar ao Carrinho"
    Então o produto deve ser adicionado ao carrinho
    E a contagem do carrinho deve ser atualizada
```
