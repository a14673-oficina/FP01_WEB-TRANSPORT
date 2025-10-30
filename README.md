# Sistema de Gestão de Projetos Ferroviários Portugueses

## Português (Portugal)

### Descrição Geral
Este é um website de demonstração para um projeto focado na **melhoria da infraestrutura ferroviária portuguesa**. O objetivo é apresentar os projetos em curso e futuros, a equipa responsável e os contactos da empresa, a **B&P Transport**. O site utiliza uma estrutura simples e focada para comunicar de forma clara os esforços de modernização das linhas portuguesas.

### Funcionalidades Principais
O website é uma aplicação estática com três páginas principais:
*   **Início (index.html)**: Presumivelmente a página principal (não fornecida), que serve como ponto de entrada e introdução ao projeto.
*   **Projetos (projetos.html)**: Lista os projetos de melhoria da infraestrutura ferroviária, como "Integração Multimodal de Transportes", "Modernização da Frota Ferroviária" e "Expansão da Linha Regional Norte".
*   **Contactos (contactos.html)**: Apresenta a informação de contacto geral da empresa (morada, emails, telefones) e um mapa de localização.
*   **Equipa de Projeto (contactos2.html)**: Apresenta os membros da equipa com os respetivos contactos individuais (Ana Costa, Rui Pereira, Sofia Marques).

### Estrutura do Código
O website é composto por ficheiros HTML simples com estilos CSS incorporados na tag `<style>` e referências a fontes externas.
*   **HTML Modular**: Cada página (`contactos.html`, `contactos2.html`, `projetos.html`) tem uma estrutura de cabeçalho (`header`), conteúdo principal (`main`) e rodapé (`footer`) bem definida.
*   **Design Responsivo Básico**: A utilização de `grid-template-columns: repeat(auto-fit, minmax(220px, 1fr))` no CSS sugere uma adaptação básica a diferentes tamanhos de ecrã.
*   **Navegação Consistente**: Todas as páginas incluem uma barra de navegação com links para "Início", "Projetos" e "Contacto".

### Desafios e Soluções (Futuros de Melhoria)
*   **Melhoria da Experiência do Utilizador (UX)**: O design atual é funcional, mas pode ser melhorado com a separação do CSS para um ficheiro externo (`style.css`) para maior manutenção e carregamento mais rápido.
*   **Integração de Dados Reais**: Atualmente, os dados dos projetos são estáticos. Uma melhoria futura seria a integração com uma API ou base de dados para gerir dinamicamente os projetos e o seu estado de avanço.
*   **Consolidação de Contactos**: As duas páginas de contactos (`contactos.html` e `contactos2.html`) poderiam ser fundidas numa única página para simplificar a navegação.

### Como Usar
1.  **Clone o repositório** (assumindo que o código está no GitHub, conforme o pedido do utilizador).
2.  **Abra os ficheiros HTML** (`index.html`, `projetos.html`, `contactos.html`, `contactos2.html`) diretamente no seu navegador.
3.  **Navegue** entre as páginas através do menu no cabeçalho.

---

# Portuguese Rail Projects Management System

## English

### Overview
This is a demonstration website for a project focused on the **improvement of the Portuguese railway infrastructure**. The goal is to present current and future projects, the responsible team, and the contact information for the company, **B&P Transport**. The site uses a simple and focused structure to clearly communicate the modernization efforts of the Portuguese lines.

### Main Features
The website is a static application with three main pages:
*   **Home (index.html)**: Presumably the main page (not provided), serving as the entry point and introduction to the project.
*   **Projects (projetos.html)**: Lists the railway infrastructure improvement projects, such as "Multimodal Transport Integration", "Modernization of the Rail Fleet", and "Expansion of the Northern Regional Line".
*   **Contacts (contactos.html)**: Presents the company's general contact information (address, emails, phone numbers) and a location map.
*   **Project Team (contactos2.html)**: Features the team members with their respective individual contacts (Ana Costa, Rui Pereira, Sofia Marques).

### Code Structure
The website consists of simple HTML files with CSS styles embedded within the `<style>` tag and references to external fonts.
*   **Modular HTML**: Each page (`contactos.html`, `contactos2.html`, `projetos.html`) has a well-defined structure of a header, main content, and footer.
*   **Basic Responsive Design**: The use of `grid-template-columns: repeat(auto-fit, minmax(220px, 1fr))` in the CSS suggests a basic adaptation to different screen sizes.
*   **Consistent Navigation**: All pages include a navigation bar with links to "Home", "Projects", and "Contact".

### Challenges and Solutions (Future Improvements)
*   **Improved User Experience (UX)**: The current design is functional but can be enhanced by separating the CSS into an external file (`style.css`) for better maintainability and faster loading.
*   **Real Data Integration**: Currently, project data is static. A future improvement would be integration with an API or database to dynamically manage projects and their progress status.
*   **Contact Consolidation**: The two contact pages (`contactos.html` and `contactos2.html`) could be merged into a single page to simplify navigation.

### How to Use
1.  **Clone the repository** (assuming the code is on GitHub, as requested by the user).
2.  **Open the HTML files** (`index.html`, `projetos.html`, `contactos.html`, `contactos2.html`) directly in your browser.
3.  **Navigate** between the pages using the menu in the header.
