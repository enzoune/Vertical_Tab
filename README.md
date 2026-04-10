# 📑 Vertical Tabs System (Abas Verticais)

> Um componente de interface dinâmico e performático que utiliza lógica declarativa em CSS para gerenciar a alternância de conteúdos, eliminando a dependência de scripts externos.

## 📖 Sobre o Projeto

Este projeto integra o meu portfólio de estudos em **Programação Full-Stack**. O objetivo foi construir um sistema de **Abas Verticais** que ofereça uma navegação intuitiva e fluida, ideal para dashboards, seções de FAQ ou painéis de configuração.

A implementação foca na separação rigorosa de responsabilidades e no uso de técnicas avançadas de CSS para controle de estado de interface.

## ✨ Destaques e Diferenciais Técnicos

* **Arquitetura "No-JS":** Utilização da técnica de seletores de rádio (`input type="radio"`) para gerenciar o estado ativo das abas, garantindo uma interface extremamente leve e rápida.
* **Interatividade via Labels:** Uso estratégico de elementos `<label>` vinculados a IDs específicos, permitindo que ícones e textos funcionem como gatilhos de navegação.
* **Navegação Iconográfica:** Integração da biblioteca **Font Awesome (v5.15.2)** para fornecer pistas visuais (affordances) que facilitam a usabilidade.
* **Estrutura de Conteúdo Modular:** Organização do conteúdo em blocos independentes dentro da classe `.text-content`, facilitando a escalabilidade do componente.
* **Indicador Visual Dinâmico:** Inclusão de um elemento `.indicator` projetado para fornecer feedback visual imediato sobre a aba selecionada.
* **Organização Profissional:** Código estruturado com foco em manutenibilidade, separando a marcação estrutural (`index.html`) da lógica de estilo (`css/style.css`).

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação e lógica de estado nativa via rádio.
* **CSS3:** Gerenciamento de layout, transições de conteúdo e animações do indicador.
* **Font Awesome:** Iconografia para suporte visual e experiência do usuário.
