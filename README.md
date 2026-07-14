# meu-primeiro-projeto-qa
Meu Primeiro Passo em QA: Cenários de Teste com BDD

Seja bem-vindo(a) ao meu repositório! Este é o meu primeiríssimo projeto focado na área de **Quality Assurance (QA)**. 

Criei este espaço para documentar minha transição de carreira e aplicar os conhecimentos que estou adquirindo no curso de QA da **DIO (Digital Innovation One)**, começando do absoluto zero.

 Sobre o Projeto
Antes de aprender a automatizar com código, entendi que um bom QA precisa dominar o **pensamento analítico**. Por isso, este projeto foca na escrita de cenários de teste para uma **Tela de Login**, utilizando a metodologia **BDD (Behavior-Driven Development)** e a sintaxe Gherkin (Dado, Quando, Então).

O objetivo é garantir que o sistema se comporte corretamente tanto em fluxos de sucesso quanto em casos de erro de usuário.

📝 Casos de Teste Mapeados

Cenário 1: Login realizado com sucesso (Fluxo Positivo)
* **Dado** que eu estou na página de login do sistema
* **Quando** eu preencho o campo de e-mail com um usuário válido
* **E** preencho o campo de senha com a senha correta
* **E** clico no botão "Entrar"
* **Então** o sistema deve me autenticar e me direcionar para a tela principal (Dashboard).

Cenário 2: Tentativa de login com senha incorreta (Fluxo Negativo)
* **Dado** que eu estou na página de login do sistema
* **Quando** eu insiro um e-mail válido
* **E** insiro uma senha incorreta
* **E** clico no botão "Entrar"
* **Então** o sistema não deve permitir o acesso e deve exibir a mensagem: *"Usuário ou senha inválidos"*.

Cenário 3: Validação de campo obrigatório (E-mail vazio)
* **Dado** que eu estou na página de login do sistema
* **Quando** eu deixo o campo de e-mail em branco
* **E** preencho o campo de senha com qualquer valor
* **E** clico no botão "Entrar"
* **Então** o sistema deve exibir um alerta visual informando: *"O campo e-mail é obrigatório"*.

🛠️ Competências Desenvolvidas neste Passo
* Noções básicas de Engenharia de Software e Qualidade.
* Escrita de cenários de teste focados na experiência do usuário.
* Introdução à metodologia ágil com BDD.
* Utilização básica do GitHub para controle de portfólio.

🎯 Próximos Passos nos Meus Estudos
- [ ] Concluir o módulo de Lógica de Programação na DIO.
- [ ] Adicionar cenários de teste para uma **Tela de Cadastro** e **Carrinho de Compras**.
- [ ] Aprender os conceitos básicos de testes de API.
