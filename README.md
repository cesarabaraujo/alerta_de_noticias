![Foto de Capa](https://github.com/cesarabaraujo/capa_perfil/blob/main/_ca1c26d8-7e8e-423b-9a52-58f06fdfea22.jpeg)


# Gerador Automático de Alertas a partir de Notícias em Python

## Visão Geral:

Este projeto tem como objetivo criar um gerador de alertas a partir de links de notícias específicas. Utiliza o módulo `requests` para realizar requisições HTTP, faz web scraping com BeautifulSoup e utiliza o `urlparse` para extrair informações do domínio. As informações extraídas incluem o nome do site, o título da matéria e um trecho que menciona uma palavra-chave específica.

## Motivação:

O projeto surgiu da necessidade de otimizar o processo de geração de alertas para matérias que mencionam clientes da equipe de monitoramento. Ainda há espaço para melhorias no código, como, por exemplo, lidar com domínios que possuem padrões diferentes.

## Funcionalidades Principais:

Este projeto pode ser utilizado como uma ferramenta por equipes de relações públicas, monitoramento e clippagem.

Para usar o código, adicione o link da matéria que deseja extrair em `link_materia` e o termo que deseja buscar no corpo da matéria em `palavra_chave`. A função retornará o parágrafo que contém o link. Adicione o nome do cliente ou da conta atendida em `nome_do_cliente`.

Além disso, é possível personalizar o modelo de alerta dentro da função `criar_alerta`, na variável `modelo_alerta`.

Observação: Alguns sites, principalmente pequenos blogs, podem apresentar erros devido a dificuldades de acesso aos seus domínios.



