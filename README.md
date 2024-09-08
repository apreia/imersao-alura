# Aplicação de Pesquisa - Galáxias do Universo

## Descrição
Esta aplicação permite que o usuário realize pesquisas em uma lista de dados, retornando os resultados relacionados à busca. A interface inclui um campo de texto onde o termo de pesquisa pode ser inserido, e os resultados são exibidos dinamicamente abaixo. A aplicação simula uma pesquisa em dados relacionados ao tema "Galáxias do Universo".

## Funcionalidades
- Pesquisa dinâmica: O usuário insere um termo no campo de busca e clica no botão "Pesquisar".
- Filtros de busca: A pesquisa é realizada em campos como título, descrição e tags de cada item.
- Resultados exibidos em formato de lista, com links para mais informações.
- Caso nenhum resultado seja encontrado, uma mensagem é exibida.

## Tecnologias Utilizadas
- **HTML5**: Estruturação da página web.
- **CSS3**: Estilização da interface (referência ao arquivo `styles.css`).
- **JavaScript**: Lógica de pesquisa e manipulação do DOM.
    - O arquivo `app.js` contém a lógica da pesquisa, recebendo os dados do arquivo `dados.js`.
- **Dados**: O arquivo `dados.js` contém uma lista de objetos, cada um representando uma galáxia com informações como título, descrição, tags e links para mais detalhes.

## Como Executar
1. Clone este repositório:
    ```bash
    git clone https://github.com/apreia/imersao-alura
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd seu-repositorio
    ```
3. Abra o arquivo `index.html` em um navegador para visualizar a aplicação.

---

**2024 - Galáxias do Universo**. Todos os direitos reservados.
