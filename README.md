# 📄 Página de Cadastro

Este projeto foi desenvolvido durante as aulas de **Sass** da **SAMURAIDEV**.

## 🛠️ Tecnologias utilizadas
- **SCSS**
- **JSON**
- **JavaScript** (script de redirecionamento do Sass para CSS)

## 📜 Scripts do projeto
No arquivo `package.json`, os seguintes scripts estão configurados:

```json
"scripts": {
    "start": "npm run sass & lite-server",
    "sass": "sass --watch style.scss style.css"
}
```

## 🚀 Como rodar o projeto
Para iniciar o projeto, siga os passos abaixo:

1. **Certifique-se de ter o Node.js e o npm instalados na sua máquina.**
   - Você pode baixar e instalar pelo site oficial: [https://nodejs.org/](https://nodejs.org/)
   
2. **Instale as dependências do projeto:**
   ```sh
   npm install
   ```
   
3. **Inicie o projeto:**
   ```sh
   npm start
   ```
   Isso iniciará o compilador do SASS e abrirá o projeto no navegador usando o `lite-server`.

### 🔹 Caso queira rodar manualmente:
- Para compilar o SASS sem iniciar um servidor:
  ```sh
  npm run sass
  ```
- Para iniciar o servidor manualmente (se já tiver um compilador de SASS rodando):
  ```sh
  npx lite-server
  ```

### 🔹 Alternativa: Usando o Live Server no VSCode
Se estiver trabalhando com arquivos estáticos e preferir um servidor mais simples:
1. Instale a extensão **Live Server** no VSCode.
2. Abra o arquivo **HTML** no editor.
3. Clique com o botão direito e selecione **Open with Live Server**.
4. Ou utilize o atalho **Alt + L, O** para iniciar rapidamente.

Isso abrirá o navegador automaticamente no `http://127.0.0.1:5500/`.

## 👨‍💻 Desenvolvedor
Projeto realizado por **Bruno Correia**.

