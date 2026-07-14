# Meu Primeiro Projeto de QA - Testes de Login

Escolhi testar uma tela de login simulada usando o formato "Dado / Quando / Então".

## O que foi avaliado?
Para criar os cenários abaixo, pensei no comportamento esperado da tela de login:
* O caminho feliz (quando tudo dá certo).
* Os caminhos de erro (quando o usuário digita algo errado ou esquece um campo).

## Cenários de Teste

### Cenário 1: Login com sucesso (Caminho Feliz)
* **Dado** que eu estou na página de login
* **Quando** eu digito o meu e-mail correto
* **E** digito a minha senha correta
* **E** clico no botão "Entrar"
* **Então** eu entro na minha conta com sucesso.

### Cenário 2: Senha errada
* **Dado** que eu estou na página de login
* **Quando** eu digito o meu e-mail correto
* **E** digito uma senha errada
* **E** clico no botão "Entrar"
* **Então** o sistema mostra a mensagem: "Usuário ou senha inválidos".

### Cenário 3: Deixar o e-mail em branco
* **Dado** que eu estou na página de login
* **Quando** eu não digito nada no campo de e-mail
* **E** digito a minha senha
* **E** clico no botão "Entrar"
* **Então** o sistema mostra o aviso: "O campo e-mail é obrigatório".

### Cenário 4: E-mail em formato inválido
* **Dado** que eu estou na página de login
* **Quando** eu digito um e-mail sem o "@" (exemplo: "usuario.com")
* **E** digito a minha senha
* **E** clico no botão "Entrar"
* **Então** o sistema mostra o aviso: "Por favor, insira um e-mail válido".

