# Portfólio de Design Gráfico & Direção de Arte 🚀

Um website moderno, minimalista e de alto impacto visual desenvolvido especialmente para Designers Gráficos, Diretores de Arte e profissionais de Comunicação Visual.

---

## 🌟 Destaques & Funcionalidades

- **Identidade Visual Dark Mode Sofisticada:** Fundo em preto profundo (`#0A0A0A`), grafite refinado (`#121214`), tipografia moderna de display (**Syne** & **Space Grotesk** para títulos impactantes; **Plus Jakarta Sans** para leitura limpa) e detalhes em Laranja Queimado (`#FF5E1A`) de alto contraste.
- **Glassmorphism & Micro-interações:** Navbar flutuante com desfoque de fundo (*backdrop-blur*), luz de cursor ambiente suave no desktop, e transições de hover fluidas.
- **Galeria Masonry Assimétrica:** Suporte nativo para artes em proporções **1:1** (quadradas), **4:5 / 9:16** (verticais para feed/stories/posters) e **16:9** (horizontais e panorâmicas para outdoors/sinalização/banners) **sem cortes forçados**.
- **Barra de Filtros Interativa:** Filtre instantaneamente entre *Todos*, *Identidade Visual*, *Social Media*, *Impressos & Sinalização* e *Infográficos & Apresentações*.
- **Modal Lightbox em Tela Cheia:**
  - Visualização em alta resolução da arte.
  - Painel com: Nome do Projeto/Cliente, Ano, Desafio & Solução Visual, e Ferramentas Utilizadas (CorelDRAW, Photoshop, Illustrator, InDesign, After Effects, Figma).
  - Navegação contínua com setas visuais e atalhos de teclado (`←` Anterior, `→` Próximo, `Esc` Fechar).
  - Botão de solicitação de orçamento direto no WhatsApp já com o nome do projeto selecionado!
- **Seção Bento de Especialidades:** 4 blocos modernos destacando suas principais frentes de atuação e entregáveis.
- **Sobre Mim & Stack:** Apresentação da sua experiência com domínio tanto do rigor gráfico (CorelDRAW / CMYK / Curvas / Grandes Formatos) quanto do digital (Social Media / Branding / Apresentações).
- **Contato Direto & Conversão:** Botão direto para WhatsApp, botão de cópia de e-mail com 1 clique e feedback animado, e links para redes sociais.

---

## 📁 Como Abrir e Testar no seu Computador

Você não precisa instalar Node.js nem rodar compiladores. O site foi construído com tecnologias web modernas (Tailwind CSS via CDN, Lucide Icons e JavaScript Puro).

1. Abra a pasta `C:\Users\marcelo.mendonca\Documents\Portfolio-Designer` no seu explorador de arquivos.
2. Dê um **duplo clique no arquivo `index.html`**. Ele abrirá imediatamente em qualquer navegador (Google Chrome, Edge, Firefox, Brave, Safari).

---

## 🎨 Como Personalizar Seus Dados e Imagens

Abra o arquivo `index.html` em seu editor de código favorito (VS Code, Notepad++, etc.):

### 1. Como Substituir as Imagens Pelas Suas Artes Reais
No final do arquivo `index.html`, localize o bloco:
```javascript
const PROJECTS_DATA = [
  {
    id: 1,
    title: "Lumina Botanicals — Cosméticos Orgânicos",
    category: "identidade-visual", // Opções: "identidade-visual", "social-media", "impressos", "apresentacoes"
    categoryLabel: "Identidade Visual",
    aspect: "aspect-[4/5]", // Opções: "aspect-square" (1:1), "aspect-[4/5]", "aspect-[9/16]", "aspect-[16/9]"
    image: "./assets/minha-arte-1.jpg", // COLOQUE SEU ARQUIVO LOCAL OU LINK AQUI
    client: "Lumina Cosméticos",
    year: "2024",
    description: "Breve explicação do projeto...",
    tools: ["Illustrator", "Photoshop", "InDesign"]
  },
  ...
]
```

> **Dica:** Crie uma pasta chamada `assets` dentro de `Portfolio-Designer` e salve suas imagens exportadas em `.jpg`, `.png` ou `.webp`. Depois, basta apontar `image: "./assets/nome-do-arquivo.jpg"`.

### 2. Como Alterar Seu Número de WhatsApp
No código, busque por `5500999999999` e substitua pelo seu número com DDD (exemplo: `5531999998888`).

### 3. Como Alterar Seu E-mail
Busque por `data-email="contato@marcelomendonca.design"` e insira seu endereço de e-mail real. Ao clicar no botão, ele copiará o seu e-mail automaticamente.

### 4. Como Alterar Suas Redes Sociais
No rodapé e na seção de contato, atualize os links das tags `<a>` para os seus perfis do **Behance**, **Instagram**, **LinkedIn** e **Dribbble**.

---

## 🌐 Como Publicar na Internet Gratuitamente

Para ter seu site online com link compartilhável (ex: `seu-nome.vercel.app` ou seu domínio próprio):

1. **Vercel ou Netlify (Arrastar e Soltar):**
   - Acesse [app.netlify.com/drop](https://app.netlify.com/drop)
   - Arraste a pasta `Portfolio-Designer` para a tela.
   - Em menos de 10 segundos seu site estará no ar com link público HTTPS gratuito!
2. **GitHub Pages:**
   - Crie um repositório no GitHub, envie os arquivos e ative o **Pages** nas configurações.
