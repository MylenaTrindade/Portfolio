# 🌟 Portifólio - Mylena Mendonça

Bem-vindo ao meu portfólio pessoal! Este é um site desenvolvido para apresentar minha trajetória acadêmica, projetos e competências como estudante de Engenharia de Software na Universidade de Brasília (UnB).

## 📋 Sobre o Projeto

Este portfólio é um site estático desenvolvido com HTML, CSS e JavaScript, onde compartilho:

- **Informações pessoais e de contato**
- **Sobre mim**: Minha trajetória e paixões
- **Objetivos profissionais e pessoais**
- **Competências técnicas**: Linguagens de programação, tecnologias e idiomas
- **Projetos desenvolvidos**: Com descrições detalhadas e links para repositórios

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura do site
- **CSS3**: Estilização e layout responsivo
- **JavaScript**: Interatividade (funcionalidade "Ler mais")
- **Font Awesome**: Ícones para contato e redes sociais

## 📁 Estrutura do Projeto

```
Portfolio/
├── index.html          # Página principal
├── style.css           # Arquivo de estilos
├── README.md           # Documentação do projeto
└── images/             # Pasta com imagens
    ├── git_icon.png    # Ícone do GitHub
    ├── logo.jpeg       # Logo pessoal
    └── unbook.png      # Imagem do projeto UNBook
```

## 🚀 Como Rodar o Projeto

### Opção 1: Servidor HTTP Local (Recomendado)

1. **Navegue até a pasta do projeto:**
   ```bash
   cd /caminho/para/Portfolio
   ```

2. **Inicie um servidor HTTP local:**
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Ou Python 2
   python -m SimpleHTTPServer 8000
   
   # Ou Node.js (se tiver instalado)
   npx http-server -p 8000
   ```

3. **Acesse no navegador:**
   ```
   http://localhost:8000
   ```

### Opção 2: Abrir Diretamente no Navegador

1. **Navegue até a pasta do projeto**
2. **Abra o arquivo `index.html` diretamente no seu navegador preferido**

### Opção 3: VS Code Live Server

1. **Instale a extensão "Live Server" no VS Code**
2. **Clique com o botão direito no arquivo `index.html`**
3. **Selecione "Open with Live Server"**

## ✨ Funcionalidades

- **Design Responsivo**: Adaptado para diferentes tamanhos de tela
- **Navegação Interna**: Links para seções específicas da página
- **Interatividade**: Botões "Ler mais" para expandir detalhes dos projetos
- **Contato Direto**: Link para envio de e-mail
- **Links Externos**: Acesso direto aos repositórios no GitHub

## 🎯 Projetos em Destaque

### 📚 UNBook
Plataforma para troca e doação de livros dentro da UnB, desenvolvida durante a disciplina de Desenvolvimento de Software.

### 💬 Gossip Girl UnB
Site de fofocas universitárias desenvolvido em Python, HTML, CSS e JavaScript como parte do curso de Orientação a Objetos.

### 🧌 Munchkin
Jogo inspirado no universo Munchkin para Sistemas de Banco de Dados 1. Aplica conceitos de bancos relacionais de forma prática e gamificada.

### 🧳 Touristeer
App que ajuda turistas a explorar destinos de forma personalizada, sugerindo rotas e pontos de interesse.

### 🚛 HackaTruck
Repositório com códigos e projetos desenvolvidos no HackaTruck, programa itinerante de tecnologia e criação de aplicativos iOS.

### 🍲 UniFood
App que conecta estudantes a restaurantes locais, permitindo explorar opções e fazer pedidos de forma prática.

### 🌟 Portfólio Pessoal
Este próprio site! Desenvolvido com HTML, CSS e JavaScript responsivo para apresentar projetos e competências.

## 📞 Contato

- **E-mail**: mylenamendonca6@gmail.com
- **Telefone**: (61) 994500966
- **Instagram**: @mymendoncaa

## 🌐 Como Fazer Deploy

### Opção 1: GitHub Pages (Recomendado - GRATUITO)

1. **Certifique-se de que o projeto está no GitHub:**
   ```bash
   git add .
   git commit -m "Atualizando portfólio"
   git push origin main
   ```

2. **Configure o GitHub Pages:**
   - Vá para o repositório no GitHub
   - Clique em "Settings" → "Pages"
   - Em "Source", selecione "Deploy from a branch"
   - Escolha "main" branch e "/ (root)"
   - Clique em "Save"

3. **Acesse seu site:**
   ```
   https://mylenatrindade.github.io/Portfolio/
   ```

### Opção 2: Netlify (GRATUITO)

1. **Acesse [netlify.com](https://netlify.com)**
2. **Conecte com GitHub ou faça upload manual da pasta**
3. **Configure:**
   - Build command: (deixe vazio)
   - Publish directory: (deixe vazio ou "./")
4. **Deploy automático:** A cada push no GitHub, o site atualiza automaticamente

### Opção 3: Vercel (GRATUITO)

1. **Acesse [vercel.com](https://vercel.com)**
2. **Conecte com GitHub**
3. **Importe o repositório Portfolio**
4. **Deploy automático:** Configuração zero necessária

### Opção 4: Surge.sh (GRATUITO)

1. **Instale o Surge:**
   ```bash
   npm install -g surge
   ```

2. **Faça o deploy:**
   ```bash
   cd /caminho/para/Portfolio
   surge
   ```

3. **Siga as instruções:** Escolha um domínio personalizado ou use o gerado

### 🎯 Recomendação

**Use GitHub Pages** para começar - é gratuito, fácil de configurar e perfeito para portfólios pessoais!

## 🔧 Melhorias Futuras

- [ ] Adicionar mais projetos
- [ ] Implementar tema escuro/claro
- [ ] Adicionar animações CSS
- [ ] Criar versão em inglês
- [ ] Adicionar seção de blog/artigos
- [ ] Configurar domínio personalizado

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar como referência para seu próprio portfólio!

---

⭐ **Desenvolvido com 💜 por Mylena Mendonça** ⭐

*Última atualização: Agosto 2025*