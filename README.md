# Praças de Pedágios de Minas Gerais

Este projeto foi desenvolvido para realizar a raspagem de dados de pedágios no estado de Minas Gerais a partir do site emsampa.com.br. Através de um script em Python, os dados são extraídos automaticamente, organizados e salvos em um arquivo Excel para fácil acesso e análise.

FUNCIONALIDADES PRINCIPAIS

1. Raspagem de Dados de Pedágios
O sistema realiza a raspagem de dados de várias praças de pedágio em Minas Gerais, extraindo informações como:

Rodovia, KM, Localidade, Número de Eixos e Valor da tarifa (Desde)

2. Integração com o Pandas
Os dados extraídos são organizados em um DataFrame do Pandas, facilitando a manipulação e análise dos dados antes de serem exportados.

3. Exportação para Excel
O sistema salva automaticamente os dados raspados em um arquivo Excel, permitindo uma análise posterior em ferramentas como Microsoft Excel, Google Sheets, ou qualquer outro software compatível.

TECNOLOGIAS UTILIZADAS

1. Python: Linguagem principal utilizada para a automação do processo de raspagem.

2. Requests: Utilizado para realizar requisições HTTP e obter o conteúdo HTML da página.

3. BeautifulSoup: Biblioteca para realizar o parse do HTML e extrair os dados das tabelas.

4. Pandas: Utilizado para organizar os dados em formato de DataFrame e realizar a exportação para Excel.

5. OpenPyXL: Biblioteca auxiliar do Pandas para salvar os dados em arquivos Excel.


COMO FUNCIONA

O script acessa a página emsampa.com.br e faz uma requisição para obter o conteúdo HTML.
Através da biblioteca BeautifulSoup, ele percorre as tabelas que contêm os dados de pedágio.
Os dados são extraídos (rodovia, KM, localidade, eixos e tarifa) e organizados em uma lista de dicionários.
A lista é convertida em um DataFrame do Pandas.
Os dados são salvos em um arquivo Excel chamado PracasMG.xlsx.

CONCLUSÃO

Este projeto automatiza a coleta de informações sobre pedágios em Minas Gerais, oferecendo uma maneira simples de extrair e organizar dados úteis diretamente de uma página web. O sistema é eficiente e permite a exportação dos dados para um formato amplamente utilizado, facilitando a análise e o armazenamento dessas informações.
