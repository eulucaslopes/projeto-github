# projeto-github

Projeto desenvolvido durante o Workshop de GitHub na COTI Informática.

Este repositório contém um projeto front-end simples criado durante o workshop para demonstrar fluxo de trabalho com Git/GitHub e conceitos básicos de desenvolvimento web.

## Tecnologias utilizadas

- HTML
- CSS
- JavaScript

O projeto é estático — não exige compilação ou servidor para execução local.

## Estrutura sugerida do repositório

- index.html
- css/
  - styles.css
- js/
  - script.js
- assets/
  - imagens, fontes, etc.

(Verifique os nomes reais dos arquivos/pastas no repositório.)

## Como abrir e rodar o projeto no Visual Studio Code (VS Code)

Pré-requisitos:

- Visual Studio Code: https://code.visualstudio.com/
- (Opcional) Git: https://git-scm.com/
- (Recomendado) Extensão Live Server para pré-visualização em tempo real

Passos:

1. Clone o repositório (ou faça download do ZIP):

   ```bash
   git clone https://github.com/eulucaslopes/projeto-github.git
   ```

2. Abra a pasta do projeto no VS Code:

   ```bash
   cd projeto-github
   code .
   ```

3. Instale a extensão Live Server (se não já tiver): vá em Extensões e procure por "Live Server".

4. Abra o arquivo `index.html` no editor e clique em "Go Live" (botão no canto inferior direito) ou clique com o botão direito no arquivo e escolha "Open with Live Server".

5. O projeto será aberto no navegador. Qualquer alteração em arquivos HTML/CSS/JS será recarregada automaticamente pelo Live Server.

Alternativa sem extensão (usando Python):

- Se tiver Python 3 instalado, rode um servidor HTTP simples na pasta do projeto:

  ```bash
  python -m http.server 8000
  ```

  Depois abra http://localhost:8000 no navegador.

## Contribuições

Contribuições são bem-vindas. Faça um fork, crie uma branch com sua alteração e envie um pull request.

## Licença

Sinta-se à vontade para usar este código para estudo. Se desejar, adicione uma licença (por exemplo MIT) para tornar os termos explícitos.
