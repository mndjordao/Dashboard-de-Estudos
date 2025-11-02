# 📊 Dashboard de Estudos


![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![Status: Em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)

Este projeto é um dashboard simples para adicionar e listar cursos, focado 100% na prática dos fundamentos do desenvolvimento Front-End. O objetivo é construir uma aplicação do zero, manipulando o DOM diretamente com JavaScript, aplicando conceitos de HTML e CSS.


## 🔗 Preview

Você pode ver o projeto em ação e testá-lo diretamente no seu navegador:

**[🔗 Ver Demonstração ](https://mndjordao.github.io/dashboard-estudos/)**

*(O link acima só vai funcionar depois que você ativar o GitHub Pages - veja como abaixo!)*

## ✨ Funcionalidades

O projeto implementa as seguintes funcionalidades:

* **Adição de Cursos:** Formulário para adicionar novos cursos à lista.
* **Renderização Dinâmica:** A lista de cursos é criada dinamicamente com JavaScript, manipulando o DOM (`createElement`, `appendChild`).
* **Feedback de UX:** Um balão de notificação flutuante (feito com CSS `position: fixed` e `transition`) aparece para confirmar o sucesso da operação.
* **Melhoria de UX com Hover:** O balão de notificação pausa seu timer de desaparecimento (`setTimeout`, `clearTimeout`) quando o usuário passa o mouse sobre ele, garantindo a leitura.


## 🚀 Roadmap

Este projeto está em desenvolvimento ativo. As próximas funcionalidades planejadas estão sendo gerenciadas na aba ["Projects"](https://github.com/mndjordao/dashboard-estudos/projects) e incluem:

-   [ ] **Persistência de Dados:** Implementar `localStorage` para que os cursos não desapareçam ao atualizar a página.
-   [ ] **Excluir Itens:** Adicionar um botão 'X' em cada curso para removê-lo da lista.
-   [ ] **Status do Curso:** Implementar a lógica de status (Pendente, Em Andamento, Concluído) que já está no HTML.
-   [ ] **Refatoração:** Melhorar a estrutura do código e aplicar mais conceitos de CSS moderno (como Grid ou Flexbox) no layout geral.


## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica para o conteúdo.
* **CSS3:** Estilização, animações de `transition` e posicionamento avançado (`fixed`, `transform`).
* **JavaScript:** Linguagem principal para toda a lógica, manipulação do DOM e gerenciamento de eventos.


## 🏁 Como Rodar o Projeto

Como é um projeto estático (apenas Front-End), você não precisa de nenhuma instalação complexa:

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/mndjordao/dashboard-estudos.git](https://github.com/mndjordao/dashboard-estudos.git)
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd dashboard-estudos
    ```
3.  Abra o arquivo `index.html` diretamente no seu navegador.
