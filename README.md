# 📱 Projeto Media Query – Site Responsivo com Menu Dinâmico

Este é um projeto de site responsivo desenvolvido com **HTML5**, **CSS3** (com dois arquivos distintos para estilos) e **JavaScript** para controle interativo do **menu hambúrguer**.  
Ele foi criado com o objetivo de praticar **Media Queries**, **layout adaptável** e **manipulação dinâmica de elementos da interface em diferentes tamanhos de tela**.

> 💡 O foco principal é demonstrar como adaptar a navegação de um site para diferentes dispositivos, especialmente com **menu que aparece/recolhe conforme o tamanho da janela** ou com clique do usuário.

---

## 🌐 Demonstração

🔗 [Veja o site publicado](https://jessica-fuentess.github.io/media-query/)

---

## 🧾 Descrição do Projeto

O projeto simula um site institucional simples com uma estrutura clara e conteúdo fictício. O destaque está no **comportamento do menu**, que se adapta automaticamente ao redimensionamento da janela e pode ser aberto/fechado com um clique no ícone hambúrguer em telas menores.

---

## ✨ Funcionalidades

- 📱 **Layout totalmente responsivo**
- 🍔 **Menu hambúrguer funcional**, feito em JavaScript puro
- 🖱️ O menu recolhe e expande conforme o clique e redimensionamento da tela
- 🎨 Dois arquivos CSS distintos: um para estilos base (mobile first) e outro com media queries
- 🧠 Boa semântica HTML com separação entre estrutura, estilo e comportamento
- 🔠 Tipografia consistente com fontes seguras
- 💡 Boa prática de separação de lógica: HTML + CSS + JS

---

## 📁 Estrutura do Projeto
```bash
media-query/
├── imagens/
│   └── faviconcss.ico    # Ícone da aba do navegador
├── index.html            # Página principal
├── 06projeto1.css        # Estilos principais (Mobile First)
├── 06projeto2.css        # Estilos condicionais com media queries
├── script.js             # Lógica JS para controle do menu
└── README.md             # Documentação do projeto
```
---

## 🧠 Como funciona o menu?

- **Telas menores que 768px**:
  - O menu fica oculto por padrão (`display: none`)
  - Um ícone (menu hambúrguer) é exibido
  - Ao clicar no ícone, o menu aparece ou desaparece com `display: block`
  
- **Telas maiores ou iguais a 768px**:
  - O menu aparece automaticamente
  - O ícone hambúrguer é ocultado

Essa lógica é aplicada tanto por **eventos de clique** (`onclick`) quanto por **detecção de redimensionamento da tela** (`onresize`).

---

## 🧰 Tecnologias utilizadas

- ✅ **HTML5** – marcação semântica e estruturada  
- ✅ **CSS3** – layout responsivo e organizado por arquivos  
- ✅ **Media Queries** – adaptação de layout para diferentes tamanhos  
- ✅ **JavaScript Puro** – manipulação de DOM para exibir/esconder o menu  
- ✅ **Material Symbols Outlined** – para o ícone do menu hambúrguer via Google Fonts  

---

## 👩‍💻 Autora

Desenvolvido por **Jéssica Fuentes** 💜 

Desenvolvedora Front-end em transição de carreira, com foco em criação de interfaces responsivas e funcionais.

🔗 [LinkedIn](https://www.linkedin.com/in/j%C3%A9ssica-fuentes/)  

🔗 [GitHub](https://github.com/Jessica-Fuentess)

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT**. Sinta-se à vontade para usar, modificar e compartilhar com os devidos créditos.

---

✨ Obrigada por conferir este projeto! Se tiver sugestões ou quiser trocar ideias, me envie uma mensagem. 🚀😊
