## 🌐 [English Version of README](README_EN.md)

# Organo

Organo é uma aplicação React que permite a gestão de equipes e colaboradores, com funcionalidades como alterar cores de equipes, favoritar colaboradores e deletar registros. Ele oferece uma interface interativa para criar, modificar e visualizar equipes, seus membros e detalhes.

## 🔨 Funcionalidades do Projeto

- **Cadastro de Colaboradores**: Permite adicionar colaboradores com informações como nome, cargo e foto.
- **Gestão de Equipes**: Criação e personalização de equipes com cores e nomes, além de possibilitar a alteração da cor da equipe.
- **Favoritos**: Marcação de colaboradores favoritos.
- **Exclusão**: Opção de excluir colaboradores de uma equipe.
- **Responsividade**: Layout adaptável para diferentes tamanhos de tela, otimizado para dispositivos móveis e desktop.

### Exemplo Visual do Projeto

![Exemplo Visual do Projeto](https://github.com/user-attachments/assets/60ce2f8a-8aa2-453c-bcf4-9cc1f5b31b01)

## ✔️ Técnicas e Tecnologias Utilizadas

- **React.js**: Framework JavaScript para construção da interface.
- **CSS3**: Estilização dos componentes e layout responsivo.
- **Hex-to-RGBA**: Biblioteca utilizada para converter valores de cores hexadecimais em RGBA, permitindo transparências no fundo das equipes.
- **React Icons**: Biblioteca para utilização de ícones no projeto.
- **UUID**: Biblioteca para geração de IDs únicos para colaboradores e equipes.
- **React DOM**: Renderização dos componentes no navegador.

## 📁 Estrutura do Projeto

- **public/**
  - **favicon.ico**: Ícone do site.
  - **index.html**: Arquivo HTML principal.
  - **imagens/**: Contém as imagens do projeto (logo, ícones das redes sociais, fundo das equipes, etc.).
    - `banner.png`: Imagem do banner principal.
    - `btn-icone.png`: Ícone para botões.
    - `facebook.png`: Ícone do Facebook.
    - `fundo.png`: Imagem de fundo das equipes.
    - `instagram.png`: Ícone do Instagram.
    - `logo.png`: Logo do Organo.
    - `twitter.png`: Ícone do Twitter.
  - **logo192.png**: Logo em tamanho 192x192 pixels.
  - **logo512.png**: Logo em tamanho 512x512 pixels.
  - **manifest.json**: Configuração do manifest para PWA.
  - **robots.txt**: Arquivo de configuração para robôs de busca.

- **src/**
  - **App.js**: Componente principal do projeto que gerencia o estado das equipes e colaboradores.
  - **componentes/**
    - **Banner/**
      - `index.js`: Componente de banner.
      - `banner.css`: Estilos do banner.
    - **Botao/**
      - `index.js`: Componente de botão.
      - `botao.css`: Estilos do botão.
    - **Campo/**
      - `index.js`: Componente de campo de entrada.
      - `campo.css`: Estilos do campo.
    - **Colaborador/**
      - `index.js`: Componente para exibir informações de um colaborador.
      - `colaborador.css`: Estilos do colaborador.
    - **Formulario/**
      - `index.js`: Componente de formulário para cadastro de colaboradores e equipes.
      - `formulario.css`: Estilos do formulário.
    - **ListaSuspensa/**
      - `index.js`: Componente de lista suspensa.
      - `lista-suspensa.css`: Estilos da lista suspensa.
    - **Rodape/**
      - `index.js`: Componente do rodapé.
      - `rodape.css`: Estilos do rodapé.
    - **Time/**
      - `index.js`: Componente para exibir uma equipe e seus colaboradores.
      - `time.css`: Estilos da equipe.
  - **index.css**: Arquivo global de estilos.
  - **index.js**: Arquivo que inicializa e renderiza o projeto no navegador.
  - **setupTests.js**: Configuração de testes para garantir que os componentes estão funcionando corretamente.

- **package.json**: Arquivo de configuração do npm com as dependências do projeto.
- **package-lock.json**: Arquivo de lock do npm para garantir versões consistentes das dependências.
- **README.md**: Documentação do projeto (este arquivo).
- **README_EN.md**: Versão em inglês do README.
- **LICENSE**: Arquivo de licença do projeto.

## 🛠️ Abrir e Rodar o Projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
   - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:

   ```bash
   node -v
   ```

- Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

3. **Instale as Dependências**:
    - Navegue até o diretório do projeto e instale as dependências com o seguinte comando:

   ```bash
   npm install
   ```

4. **Execute o Projeto**:
    - Após a instalação, inicie o servidor local com o comando:

   ```bash
   npm start
   ```

   O projeto estará disponível em `http://localhost:3000`.

## 🌐 Deploy

Para fazer o deploy do projeto, você pode utilizar serviços como o [Vercel](https://vercel.com/) ou [Netlify](https://www.netlify.com/). Siga os passos abaixo para o deploy no Vercel:

1. **Crie uma Conta no Vercel** (se ainda não tiver): [Vercel Signup](https://vercel.com/signup).
2. **Conecte seu Repositório GitHub**: No painel do Vercel, conecte seu repositório GitHub com o projeto.
3. **Selecione o Repositório e Clique em Deploy**: O Vercel automaticamente detectará o framework e criará um deploy para você.
4. **Acesse o Site Publicado**: Após a conclusão do deploy, você receberá um link para acessar o projeto.

