# Portfólio de Julio Guedes

Bem-vindo ao meu portfólio! Aqui você encontrará informações sobre meus projetos e habilidades como Front-end Developer. Este portfólio foi desenvolvido usando HTML, CSS e JavaScript.

## Estrutura do Projeto

O projeto é composto por três arquivos principais:

- `index.html`
- `style.css`
- `script.js`

### `index.html`

O arquivo HTML contém a estrutura principal do portfólio, incluindo:

- **Header**: Exibe o nome, cargo e imagem de perfil, além de links para redes sociais.
- **Main**: Seção com cards que detalham projetos e links relevantes.
- **Footer**: Contém uma nota de copyright.

### `style.css`

O arquivo CSS fornece a estilização do portfólio, com destaque para:

- **Animação de Fundo**: Gradiente animado para o header e seção de projetos.
- **Menu Hambúrguer**: Estilo e animação para o menu de navegação.
- **Cards de Projetos**: Estilização e efeitos de hover para os cards dos projetos.

### `script.js`

O arquivo JavaScript inclui a função para fechar o menu hambúrguer ao clicar em um item do menu:

```javascript
function closeMenu() {
    document.getElementById('toggle').checked = false;
}


