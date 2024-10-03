# UOL Notícias - Projeto Web

## Descrição
Este projeto apresenta uma estrutura básica para um site de notícias do UOL, com páginas de cadastro e uma página de notícias. O objetivo é fornecer um layout responsivo e interativo, focando em uma boa experiência do usuário.

## Estrutura do Projeto
O projeto contém duas páginas principais:

1. **Cadastro (`cadastro.html`)**:
   - Formulário para inscrição com campos para e-mail, senha, nome completo, CPF, telefone e CEP.
   - Opção para seleção de meio de pagamento com cartões de crédito.
   - Informações sobre a assinatura UOL.
   - Estilo definido no arquivo `cadastro.css`.

2. **Notícias (`noticia.html`)**:
   - Exibe notícias com título, autor, data e conteúdo.
   - A página inclui uma seção para a opinião sobre finanças.
   - Estilo definido no arquivo `noticia.css`.

## Tecnologias Utilizadas
- HTML5
- CSS3

## Estilo e Layout
Os estilos são organizados em arquivos CSS separados (`cadastro.css`, `noticia.css`, entre outros), otimizando a manutenção e a legibilidade do código.

## Requisitos para Rodar a Aplicação
Para executar a aplicação localmente, você precisará:

1. Um navegador web para visualizar as páginas HTML.
2. Conexão com a internet para carregar o Font Awesome e qualquer imagem externa utilizada.

## Documentação
### Problemas e Funcionalidades
Os problemas e funcionalidades do projeto são rastreados através de issues.

### Documentação do Código
Os principais arquivos HTML e CSS estão documentados com comentários no código-fonte para facilitar a compreensão e manutenção.

## Pull Request e Processo de Merge

- Todo o código na branch main deve ser mesclado a partir da develop via Pull Requests.
- Não é permitido realizar commits diretamente na branch main.
- Issues devem ser vinculadas aos commits.

## Releases

As releases são geradas sempre que a branch `develop` é estabilizada e suas alterações são mescladas à branch `main`, garantindo que o código na `main` esteja sempre pronto para produção. Cada release é revisada, documentada e versionada.
