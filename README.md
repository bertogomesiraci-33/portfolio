# 💻 Portfólio Profissional — Iraci Berto Gomes

## 👩‍🎓 Nome da Aluna
**Iraci Berto Gomes**  
Curso Técnico em Desenvolvimento de Sistemas — ETEC / Centro Paula Souza (CPS)

---

## 📖 Descrição do Portfólio
Este projeto é o meu **Portfólio Pessoal e Profissional**, desenvolvido e evoluído na **Agenda 15** da disciplina de **Desenvolvimento de Sistemas I**. A página apresenta meu perfil profissional, minha trajetória acadêmica multidisciplinar (Administração, Logística e Desenvolvimento de Sistemas), as tecnologias que utilizo, meus projetos reais publicados no GitHub e meus canais de contato, utilizando uma identidade visual harmônica em tons neutros (bege, areia e cáqui).

---

## 🛠️ Tecnologias Utilizadas
* **HTML5** (Estruturação semântica das seções `nav`, `section`, `footer`)
* **CSS3** (Estilização personalizada em paleta de tons neutros bege e cáqui, ajuste responsivo do `carousel` e animações `hover`)
* **Bootstrap 5.3.3** (Navbar responsiva `sticky-top`, `Carousel` com efeito `carousel-fade`, Sistema de Grid `row`/`col`, `Cards`, `Badges` e `Buttons`)
* **Devicon** (Ícones vetoriais das tecnologias HTML5, CSS3, Bootstrap, Python, GitHub e VS Code)
* **Git e GitHub Pages** (Versionamento e publicação online do site)

---

## 🌐 Link do Site Publicado (GitHub Pages)
* 🔗 **Link do Site Publicado (GitHub Pages):** [https://bertogomesiraci-33.github.io/portfolio/](https://bertogomesiraci-33.github.io/portfolio/)
* 🔗 **Link do Repositório no GitHub:** [https://github.com/bertogomesiraci-33/portfolio](https://github.com/bertogomesiraci-33/portfolio)

---

## ⚙️ Explicação do Funcionamento do Projeto
O site funciona em formato de página única (*Single Page*) responsiva, adaptando-se automaticamente a celulares, tablets e computadores:
1. **Menu de Navegação (`Navbar`):** Fixado no topo (`sticky-top`), possui links internos com fonte branca destacada (`#perfil`, `#formacao`, `#projetos`, `#contato`) que rolam suavemente até cada seção da página. Em telas menores, converte-se em botão recolhível (*hambúrguer*).
2. **Área de Destaque (`Carousel`):** Posicionada logo abaixo da Navbar, apresenta 3 slides personalizados em tela ampla (`85vh`) com transição suave (`carousel-fade`), combinando a paleta em Bege e Cáqui com ilustrações temáticas de tecnologia e inovação:
   * **Slide 1 (`imagens/slide1.png`):** *Portfólio Profissional & Acadêmico — Iraci Berto Gomes* (Interfaces Digitais, Web e Automação);
   * **Slide 2 (`imagens/slide2.png`):** *Formação Acadêmica & Trajetória — Gestão, Logística & TI* (Conectividade Global, Senac, UNIP e ETEC);
   * **Slide 3 (`imagens/slide3.png`):** *Projetos Reais no GitHub — Soluções Digitais & Web* (Ecossistema de Aplicações e Automação).
3. **Seção de Perfil (`#perfil`):** Apresenta minha foto de perfil circular, resumo profissional, 4 cards de informações rápidas (Localização, Área de interesse, Formação e Objetivo) e 2 cards listando as tecnologias e ferramentas com ícones `Devicon`.
4. **Seção de Formação Acadêmica (`#formacao` — Recurso Novo):** Destaca minha trajetória acadêmica em 3 cards estruturados.
5. **Seção de Projetos (`#projetos`):** Exibe os cards dos meus 6 projetos reais publicados no GitHub (`AGENDA_13`, `AGENDA_11`, `AGENDA_12`, `Novo-simulador`, `projetos` e `nutri-berto`), com botões funcionais que levam diretamente aos sites e repositórios.
6. **Seção de Contato (`#contato`) e Rodapé (`footer`):** Card centralizado com botões diretos para E-mail, GitHub e LinkedIn, seguido pelo rodapé institucional.

---

## ✨ Descrição do Recurso Novo Adicionado
Para evoluir o modelo base construído em aula, adicionei **três melhorias e recursos novos combinados**:
1. **Nova Seção de Formação Acadêmica (`#formacao`) integrada ao Menu de Navegação:** Uma seção exclusiva apresentando minhas três formações:
   * **Técnico em Desenvolvimento de Sistemas** — *ETEC / Centro Paula Souza* (Atualmente estudante);
   * **Tecnólogo em Logística** — *UNIP — Campus Marquês de São Vicente*;
   * **Bacharelado em Administração** — *Senac Santo Amaro*.
2. **Animações Visuais de Hover (`.card-hover`) e Rolagem Suave (`scroll-behavior: smooth`):** Efeito de elevação suave e sombra projetada ao passar o mouse sobre os cards de Formação, Perfil, Projetos e Contato.
3. **Personalização de Design em Paleta de Tons Neutros (Bege, Areia e Cáqui):** Substituição das cores padrões do Bootstrap por uma identidade visual autoral e harmônica em tons neutros (`.titulo-caqui`, `.card-borda-topo-caqui`, `.btn-caqui` e banners personalizados no Carousel e nos Cards).

---

## 🔧 Explicação de Como Esse Recurso Foi Implementado
1. **Implementação da Nova Seção de Formação (`#formacao`):**
   * Na `navbar`, adicionei o link `<li class="nav-item"><a class="nav-link text-white fw-semibold" href="#formacao">Formação</a></li>`.
   * Logo abaixo da seção `<section id="perfil">`, criei a `<section id="formacao">` utilizando o sistema de Grid do Bootstrap (`<div class="row g-4">` com três colunas `<div class="col-md-4">`) e componentes `card` para destacar cada instituição de ensino (ETEC, UNIP Marquês de São Vicente e Senac Santo Amaro).
2. **Implementação da Animação CSS (`hover`) e Identidade Visual Neutra:**
   * Na tag `<style>` dentro do `<head>`, criei a classe `.card-hover` com `transition: transform 0.3s ease, box-shadow 0.3s ease;` e o estado `.card-hover:hover` com `transform: translateY(-8px);`.
   * Criei classes CSS personalizadas (`.bg-neutro-escuro`, `.box-foto-perfil`, `.titulo-caqui`, `.card-borda-topo-caqui` e `.btn-caqui`) aplicando fundo bege claro (`#f6efe2`) em toda a página e destaques em cáqui (`#6e5c3b` e `#7c6a46`).
