# 🍫 Felicidade é Brigadeiro - Doces Artesanais

<p align="center">
  <img src="./img/logo 2.png" alt="Felicidade é Brigadeiro Logo" width="200">
</p>

<p align="center">
  <strong>Sistema WEB institucional e catálogo digital desenvolvido como Projeto Prático Acadêmico.</strong><br>
  Plataforma responsiva para divulgação, engajamento e captação de encomendas de doces premium via WhatsApp.
</p>

---

## 🌐 Endereço de Deploy (Acesso Online)
> **⚠️ ATENÇÃO AVALIADORES:** O sistema encontra-se publicado e totalmente funcional na nuvem através do link abaixo:
>
> 🔗 **[Clique aqui para acessar o Sistema em Produção](https://SEU-LINK-AQUI.vercel.app)** *(Substitua pelo link final do seu Deploy)*

---

## 🎥 Vídeo de Apresentação do Projeto
Apresentação completa das funcionalidades da plataforma, dinâmica de desenvolvimento do grupo e arquitetura utilizada (Mínimo de 5 minutos):

🎬 **[Assistir Apresentação no YouTube](https://youtube.com/seu-link-aqui)** *(Substitua pelo link do vídeo do seu grupo)*

---

## 📝 Sobre o Projeto Acadêmico
Este sistema foi desenvolvido como parte integrante das disciplinas de **Projeto em Desenvolvimento de Sistemas / Projeto Prático em Sistemas**, atendendo a uma demanda real do mercado por meio de um **Projeto Profissional**. 

O objetivo principal foi criar uma landing page com arquitetura moderna, focada na experiência do usuário (UX/UI), alta performance de carregamento e integração nativa com ferramentas de comunicação instantânea para impulsionar um negócio local fundado em 2007.

### ✨ Principais Funcionalidades Implementadas
- **Navegação Suave Personalizada (`SPA-like`):** Sistema customizado de rolagem via JavaScript (`requestAnimationFrame` com curva `easeOutCubic`) para transições fluidas de 1.2 segundos entre as seções, evitando saltos bruscos.
- **Catálogo de Produtos Dinâmico:** Vitrine interativa estruturada em CSS Grid exibindo 9 produtos em destaque com tratamentos de imagem reativos (`hover effects`).
- **Integração Automatizada com WhatsApp:** Captação de cliques nos botões de encomenda com geração dinâmica de strings codificadas (`encodeURIComponent`) que enviam o nome exato do produto escolhido direto para o chat da empresa.
- **Responsividade Total (Mobile-First):** Media queries otimizadas para readequação completa do Header, Grid de produtos e colunas do Footer em dispositivos móveis e tablets.

---

## 🛠️ Tecnologias e Arquitetura

O projeto foi construído utilizando tecnologias nativas da Web para garantir máxima performance, sem a sobrecarga de frameworks pesados:

- **HTML5:** Estruturação semântica da página (`<header>`, `<main>`, `<section>`, `<footer>`).
- **CSS3:** Estilização avançada com uso de Grid Layout, Flexbox, efeitos de transição fluidos, variáveis de cores institucionais (tons de Vinho Escuro, Rosa e Creme Suave) e fontes tipográficas importadas da Google Fonts (*Playfair Display* e *Poppins*).
- **JavaScript (Vanilla JS):** Lógica de animação de scroll, manipulação de eventos do DOM e integração de links da API do WhatsApp.
- **Cloud Computing (Provedor de Hospedagem):** *[Inserir o nome do provedor utilizado, ex: Vercel / AWS / Netlify]* para entrega rápida global.

---

## 📂 Estrutura de Diretórios do Repositório

```text
├── img/                             # Banco de mídias e assets visuais
│   ├── logo 2.png                   # Logotipo principal do cabeçalho
│   ├── logo.png                     # Selo institucional da seção sobre
│   ├── banner.png                   # Imagem de fundo da seção Hero
│   └── [demais imagens de doces]    # Fotos do catálogo de produtos
├── index.html                       # Código-fonte estrutural (HTML)
├── style.css                        # Folha de estilo e responsividade (CSS)
└── README.md                        # Documentação do repositório (Este arquivo)
