# Web Scraping Automóveis - Python

Este projeto foi desenvolvido para treinar meus conhecimentos de Python, focando em web scraping e manipulação de threads. O objetivo é extrair números de telefone de anúncios de automóveis em um site específico e salvar esses números em um arquivo CSV.

## Funcionalidades

- **Requisição HTTP**: Realiza a requisição de páginas de anúncios de carros.
- **Parsing HTML**: Usa o BeautifulSoup para parsear e extrair informações da página HTML.
- **Extração de Links**: Identifica links para anúncios individuais.
- **Extração de Telefone**: Faz a extração de números de telefone presentes nas descrições dos anúncios, utilizando expressões regulares.
- **Multithreading**: Utiliza múltiplas threads para acelerar o processo de extração de telefones.

## Tecnologias

- **Python 3.x**
- **BeautifulSoup**: Para parsear o HTML das páginas.
- **Requests**: Para realizar requisições HTTP.
- **Re**: Para uso de expressões regulares.
- **Threading**: Para otimizar o processo com execução paralela.

## Como usar

1. **Instalar dependências**:
   Certifique-se de que você tenha o Python 3.x instalado e depois instale as bibliotecas necessárias:

   ```bash
   pip install requests beautifulsoup4

2. **Rodar o script: Basta executar o script Python**:

    ```bash
    python nome_do_arquivo.py

  O script irá:
  
  - Acessar o site https://django-anuncios.solyd.com.br/automoveis/
  - Extrair os links dos anúncios.
  - Para cada anúncio, buscar os números de telefone na descrição.
  - Salvar os números encontrados no arquivo ```telefones.csv```.
- 
## Arquivos
- ```telefones.csv```: Arquivo gerado com os números de telefone encontrados.
  
## Contribuições
Este projeto foi desenvolvido com fins de aprendizado e prática. No entanto, se você tiver sugestões ou melhorias, sinta-se à vontade para abrir um pull request ou issue.

## Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais informações.
