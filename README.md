# Kendrick Lamar Albums Carousel

Este projeto é uma página web interativa que exibe um carrossel dos álbuns do rapper **Kendrick Lamar**. A página permite que os usuários naveguem entre os álbuns, visualizando informações sobre eles e acessando links externos para saber mais ou ouvir as músicas.

## Demonstração 

![image](https://github.com/user-attachments/assets/802e46cb-7517-4d60-bdbe-fa06842b7ee7)

## Funcionalidades

- Exibição de um carrossel com capas e descrições dos álbuns de Kendrick Lamar.
- Botões para navegar entre os álbuns: "Próximo" e "Anterior".
- Animações suaves entre as transições das imagens e conteúdos.
- Thumbnails (miniaturas) dos álbuns são exibidos abaixo do carrossel principal.
- Links para a página da Wikipedia e Spotify para cada álbum.

## Tecnologias Utilizadas

- **HTML5**: Estrutura básica da página.
- **CSS3**: Estilização, incluindo responsividade e animações.
- **JavaScript**: Controle da funcionalidade do carrossel e interações.

## Estrutura do Projeto

## Estrutura do Projeto

- `index.html`: Estrutura HTML da página.
- `style.css`: Estilos e animações da página.
- `script.js`: Lógica do carrossel e navegação.

### `index.html`
Contém a estrutura principal da página. Inclui uma seção de carrossel, miniaturas dos álbuns, e botões de navegação. Cada item do carrossel tem uma descrição com informações sobre o álbum, o ano de lançamento, e botões para links externos (Wikipedia e Spotify).

### `style.css`
Responsável pela aparência do carrossel e dos outros elementos na página. Aqui estão os principais componentes estilizados:

- **Fonte personalizada**: Usa as fontes "Poppins" e "Ubuntu" do Google Fonts.
- **Layout Responsivo**: Adapta-se a diferentes tamanhos de tela, com estilos específicos para dispositivos móveis.
- **Animações**: Inclui animações para transição de slides e aparição de conteúdo com `@keyframes`.

### `script.js`
Este arquivo contém a lógica de navegação do carrossel, permitindo a rotação dos itens:

- **Botões de navegação (`next` e `prev`)**: Controlam a mudança de slides.
- **Animação de transição**: Utiliza classes CSS para aplicar efeitos visuais ao alternar os itens do carrossel.
- **Timer automático**: Define o tempo de exibição e reseta a animação após cada transição.

## Como Usar

1. Faça o clone do repositório:

   bash
   `git clone https://github.com/henryDiv/KdotPage.git`

2. Navegue até o diretório do projeto:
     <br/>  `cd KdotPage`

3. Abra o arquivo index.html no seu navegador para visualizar a página.

## Melhorias Futuras
- Adicionar navegação automática com um temporizador.
- Melhorar o suporte para dispositivos móveis (layout responsivo).
- Implementar carregamento dinâmico de álbuns via API.


