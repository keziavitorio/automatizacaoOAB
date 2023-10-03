# Automatização de Processos OAB

Este é um projeto em Python que automatiza a consulta de processos da Ordem dos Advogados do Brasil (OAB) no site do Tribunal de Justiça de Minas Gerais (TJMG) usando Selenium. Ele permite pesquisar processos com base no número da OAB e estado, extrair informações relevantes de cada processo e armazená-las em um arquivo Excel.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter os seguintes pré-requisitos instalados:

- Python (versão 3.x)
- Biblioteca Selenium
- Webdriver para o Chrome
- Biblioteca openpyxl

Você pode instalar as bibliotecas Python necessárias usando o pip:

```bash
pip install selenium openpyxl
````
## Como usar

- Clone o repositório ou faça o download do código.
- Certifique-se de ter o WebDriver do Chrome instalado e atualizado. Você pode baixá-lo aqui.
- Execute o arquivo Python com o código fornecido.
  
````
python seu_codigo.py

````
1. O script abrirá uma instância do Chrome e navegará até o site de consulta pública da OAB.
2. Ele preencherá o número da OAB e selecionará o estado.
3. Clique no botão "Pesquisar" para obter informações sobre os processos.
4. Para cada processo encontrado, o script coletará informações, como número do processo, data de distribuição e últimas movimentações.
5. Essas informações serão armazenadas em um arquivo Excel chamado "dados.xlsx", separadas por processo.
   
Certifique-se de ajustar o número da OAB e o estado de acordo com suas necessidades.

## Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter detalhes.

Sinta-se à vontade para contribuir, relatar problemas ou fazer melhorias neste projeto. Obrigado por usar a automação de processos da OAB!
