# HappyTree API - Website Estático

Este diretório contém o site estático de documentação da API HappyTree.

## 📁 Estrutura de Arquivos

```
docs/
├── happytree.html    # Página principal do site
├── styles.css    # Estilos CSS do site
├── script.js     # JavaScript interativo
└── README.md     # Este arquivo
```

## 🚀 Como Visualizar

### Opção 1: Abrir Diretamente no Navegador

Simplesmente abra o arquivo `happytree.html` em seu navegador favorito:

```bash
# Linux
xdg-open docs/happytree.html

# macOS
open docs/happytree.html

# Windows
start docs/happytree.html
```

### Opção 2: Usar um Servidor Web Local

Para uma melhor experiência, especialmente se estiver testando recursos que requerem um servidor:

#### Usando Python 3:
```bash
cd docs
python3 -m http.server 8000
```
Acesse: http://localhost:8000

#### Usando Node.js (http-server):
```bash
npm install -g http-server
cd docs
http-server -p 8000
```
Acesse: http://localhost:8000

#### Usando PHP:
```bash
cd docs
php -S localhost:8000
```
Acesse: http://localhost:8000

### Opção 3: Usar a Extensão Live Server do VS Code

1. Instale a extensão "Live Server" no VS Code
2. Clique com o botão direito em `happytree.html`
3. Selecione "Open with Live Server"

## 🎨 Características do Site

### Design

- **Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Moderno**: Interface limpa e profissional com gradientes e animações
- **Acessível**: Navegação por teclado e labels ARIA

### Seções Principais

1. **Home/Hero**: Apresentação inicial com badges e CTAs
2. **About**: Explicação do que é a HappyTree API
3. **Features**: Recursos principais da API
4. **Use Cases**: Casos de uso ideais
5. **Usage**: Tutorial passo a passo com exemplos de código
6. **Installation**: Instruções para Maven e Gradle
7. **Documentation**: Links para recursos e documentação
8. **Code Examples**: Exemplos completos com tabs interativas
9. **Stats**: Estatísticas da API
10. **Contributing**: Como contribuir
11. **Footer**: Links e informações de contato

### Funcionalidades JavaScript

- **Menu Mobile**: Menu responsivo para dispositivos móveis
- **Navegação Suave**: Scroll suave entre seções
- **Botão Copy Code**: Copiar código com um clique
- **Back to Top**: Botão para voltar ao topo
- **Animações**: Animações ao scroll com Intersection Observer
- **Tabs Interativas**: Diferentes exemplos de código em abas
- **Active Nav Links**: Destaque automático da seção atual

## 🎯 Personalizações

### Cores

As cores principais podem ser alteradas no arquivo `styles.css` nas variáveis CSS:

```css
:root {
    --primary-color: #4CAF50;
    --secondary-color: #2196F3;
    --accent-color: #FF9800;
    --dark-bg: #1a1a2e;
    --darker-bg: #16213e;
    /* ... */
}
```

### Conteúdo

Todo o conteúdo está no arquivo `happytree.html` e pode ser facilmente editado para adicionar:

- Novos exemplos de código
- Mais casos de uso
- Tutoriais adicionais
- Links para recursos externos

## 📦 Dependências

O site utiliza:

- **Google Fonts**: Inter (texto) e Fira Code (código)
- **Sem frameworks**: JavaScript vanilla puro
- **Sem jQuery**: Zero dependências externas

Todas as funcionalidades são implementadas com JavaScript nativo, tornando o site leve e rápido.

## 🌐 Deploy

### GitHub Pages

Para hospedar no GitHub Pages:

1. Faça commit dos arquivos na pasta `docs/`
2. Vá em Settings > Pages no GitHub
3. Selecione a branch `main` e a pasta `/docs`
4. O site estará disponível em: `https://[usuario].github.io/happytree/`

### Netlify

Para deploy no Netlify:

1. Conecte seu repositório ao Netlify
2. Configure o diretório de publicação como `docs`
3. Deploy automático a cada push

### Vercel

Para deploy no Vercel:

1. Importe o projeto no Vercel
2. Configure o diretório de saída como `docs`
3. Deploy automático configurado

## 📱 Compatibilidade

O site é compatível com:

- ✅ Chrome/Edge (últimas versões)
- ✅ Firefox (últimas versões)
- ✅ Safari (últimas versões)
- ✅ Opera (últimas versões)
- ✅ Navegadores móveis (iOS Safari, Chrome Mobile)

## 🤝 Contribuindo

Para contribuir com melhorias no site:

1. Faça suas alterações nos arquivos HTML/CSS/JS
2. Teste localmente
3. Commit e push para o repositório
4. Crie um Pull Request

## 📄 Licença

Este site de documentação segue a mesma licença MIT do projeto HappyTree.

---

**Desenvolvido com 💚 para a comunidade HappyTree**
