
# Study Pull Request de Domingo

Este repositório foi criado para a aula prática de Pull Request. O objetivo é que você, aluno, aprenda a colaborar com projetos open source no GitHub. Siga os passos abaixo para completar esta atividade.

## Passos para Contribuir

1. **Faça um Fork deste Repositório**
   - Clique no botão de **Fork** no canto superior direito desta página.
   - Isso irá criar uma cópia deste repositório na sua conta do GitHub.

2. **Clone o Repositório Forkado**
   - No seu terminal, clone o repositório forkado para o seu ambiente local.
   ```bash
   git clone https://github.com/seu-usuario/study-pull-request.git
   ```

3. **Crie uma Branch**
   - Navegue até o diretório do repositório clonado.
   - Crie uma nova branch para adicionar seu nome ao projeto.
   ```bash
   git checkout -b feat/adicionei-meu-username
   ```

4. **Crie sua Pasta**
   - No diretório `src/student/`, crie uma nova pasta com o seu username do github (username).
   - Dentro dessa pasta, crie um arquivo `README.md` com o seguinte conteúdo:

   ```md
   # Nome - DEV

   - **GitHub**: [Click aqui](https://github.com/seu-usuario)
   - **LinkedIn**: [CLick aqui](https://www.linkedin.com/in/seu-usuario/)
   ```

   **Exemplo:**

   ```md
   # Lucas Correa - DEV

   - **GitHub**: [lucascorreaa](https://github.com/lucascorreaa)
   - **LinkedIn**: [Lucas Correa](https://www.linkedin.com/in/lucas-correa/)
   ```

5. **Commit e Push**
   - Após adicionar seu `README.md`, faça o commit das suas mudanças.
   ```bash
   git add .
   git commit -m "feat: adicionei meu username"
   ```
   - Faça o push da sua branch para o repositório remoto.
   ```bash
   git push origin feat/adicionei-meu-username
   ```

6. **Abra um Pull Request**
   - No GitHub, navegue até o repositório forkado.
   - Você verá um botão para abrir um **Pull Request**. Clique nele.
   - No título do Pull Request, utilize o seguinte formato:
     ```
     feat: adicionei meu username
     ```
   - Envie o Pull Request para revisão.

## Exemplo de Estrutura

A estrutura do repositório após a sua contribuição deve ser similar ao seguinte:

```
src/
└── student/
    ├── lucascorreaa/
    │   └── README.md
    └── username/
        └── README.md
```

## Exemplo de Pull Request

Há um exemplo de Pull Request já disponível no repositório. Sinta-se à vontade para consultá-lo como referência.

---

Se você seguir todos os passos corretamente, seu Pull Request será revisado e, se estiver tudo certo, será aceito! Boa sorte e bom aprendizado!
