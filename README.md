# 📰 Notícias Cidade — Portal de Notícias

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)

O **Notícias Cidade** é um portal de notícias desenvolvido com **HTML5 e CSS3**, focado em **organização de conteúdo**, **layout modular** e **boas práticas de estruturação front-end**.  
O projeto simula um site jornalístico completo, com múltiplas editorias, destaques, entrevistas e navegação intuitiva.

---

## 💻 Tecnologias Utilizadas

- **HTML5 semântico**
- **CSS3**
- **Layout baseado em colunas (1, 2 e 3 colunas)**
- **Font Awesome** (ícones sociais)
- **Favicon personalizado**
- **Design clássico inspirado em portais jornalísticos**

---

## 🧠 Destaques Técnicos do Projeto

### ✅ Estrutura HTML bem organizada
- Uso claro de **containers**, **seções lógicas** e **hierarquia visual**
- Separação entre:
  - Cabeçalho (`#topo`)
  - Navegação
  - Conteúdo principal
  - Colunas laterais
  - Rodapé

### ✅ Layout dinâmico por classes no `<body>`
O layout da página é controlado apenas alterando o **ID do body**, permitindo:
- `#uma-coluna`
- `#duas-colunas`
- `#tres-colunas`

Isso demonstra:
- **Reutilização de código**
- **Escalabilidade**
- **Boa arquitetura CSS**

```html
<body id="tres-colunas" class="home">
```


### ✅ Navegação inteligente com estado ativo

O menu identifica automaticamente a página ativa usando seletores avançados:
```Css
body.economia #navegacao a#economia {
    background: #de003e;
}
```
✔ Sem JavaScript

✔ Apenas CSS bem estruturado

✔ Excelente prática de front-end


### ✅ Tipografia e legibilidade

- Fonte sem serifa (Trebuchet MS)

- Hierarquia clara com h1, h2, h3

- Destaques visuais com cores contrastantes

### ✅ Organização visual por componentes

O site é dividido em caixas reutilizáveis:

```Css
.caixa {
    background: #f3f3f3;
    border: 1px solid #ccc;
}
```

Isso facilita:

✔ Manutenção

✔Expansão futura

✔ Padronização visual

### ✅ Listas de notícias otimizadas

- Imagem + título + resumo

- Hover interativo

- Cursor intuitivo

- Excelente UX para portais de conteúdo

### ✅ Rodapé moderno com Flexbox

Mesmo em um layout clássico, o rodapé utiliza Flexbox, mostrando domínio de técnicas modernas:

```Css
#rodape {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 15px;
}
```

Inclui:

✔ Créditos do autor

✔ Links profissionais

✔ Ícones sociais

---

## 🚀 Funcionalidades do Portal

1. Menu de navegação com editoria 

2.  Destaques principais com imagem 

3. Notícias recentes organizadas por categoria 

4. Coluna de entrevistas 

5. Formulário de newsletter 

6. Rodapé com links profissionais de contato 

7. Layout adaptável (1, 2 ou 3 colunas)

---

## 🛠 Demonstração Desktop

### Página Inicial
<img width="786" height="905" alt="image" src="https://github.com/user-attachments/assets/d2d1d7c6-0068-4d74-b682-260d03a2a4e8" />

### Página de Conteúdo (Economia)
<img width="754" height="840" alt="image" src="https://github.com/user-attachments/assets/3fc4b7d6-b415-437d-8017-a082eb54ec6c" />

---

## 🗂 Estrutura do Projeto
 
```bash
noticias-cidade/
│
├── Css/
│   └── noticia-da-cidade.css
│
├── Imagens/
│   ├── logo.png
│   ├── fundo.png
│   ├── icon NC.png
│   ├── demo-home.png
│   └── demo-economia.png
│
├── Html/
│   ├── index.html
│   ├── brasil.html
│   ├── economia.html
│   ├── internacional.html
│   ├── ciencia.html
│   └── saude.html
│
└── README.md
```

---

## 👨‍💻 Autor

Desenvolvido por João Gonçalves

🔗 [LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-gon%C3%A7alves01/)

🐙 [GitHub](https://github.com/joao-GON)

---


## ✨ Considerações Finais

Este projeto demonstra:

- Base sólida em HTML e CSS

- Domínio de layouts clássicos

- Organização de código

- Boas práticas de front-end

- Pensamento estrutural e escalável

- É um excelente projeto para portfólio, especialmente para vagas de Front-End Júnior / Estágio.








