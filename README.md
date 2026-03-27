# 📊 Indicador de PRDO - Dashboard Logístico

Este projeto é uma ferramenta web estática desenvolvida para facilitar o monitoramento do indicador **PRDO (Outbound Delivery Order)** na operação logística. A aplicação permite que o usuário faça o upload de extrações brutas do ERP (SAP EWM/JD Edwards) e visualize os dados de forma organizada e persistente no navegador.

## 🚀 Funcionalidades

- **Leitura de Excel (XLSX/XLS):** Processamento de arquivos diretamente no front-end utilizando a biblioteca `SheetJS`.
- **Persistência Local:** Utilização de `localStorage` para manter os últimos dados carregados mesmo após fechar o navegador.
- **Interface Minimalista:** Focada em legibilidade e rapidez para tomada de decisão.
- **Renderização Dinâmica:** Criação automática de tabelas com base nas colunas do arquivo enviado.

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3:** Estrutura e estilização customizada.
- **JavaScript (ES6+):** Lógica de manipulação de DOM e processamento de arquivos.
- **SheetJS (xlsx.js):** Biblioteca para parsing de planilhas Excel.
- **GitHub Pages:** Hospedagem rápida e acessível.

## 💡 Contexto de Desenvolvimento

Este projeto foi criado como parte dos meus estudos em **Análise e Desenvolvimento de Sistemas (ADS)**. Busquei aplicar conceitos de manipulação de dados e automação para resolver um problema real de acompanhamento de KPIs logísticos. 

*Nota: O desenvolvimento contou com o auxílio de ferramentas de IA para otimização da lógica de tratamento de binários de arquivos, demonstrando minha capacidade de utilizar tecnologias emergentes para acelerar a entrega de soluções.*

## 📂 Como utilizar

1. Clone o repositório ou baixe o arquivo `index.html`.
2. Abra o arquivo em qualquer navegador moderno.
3. Clique em "ATUALIZAR PLANILHA" e selecione sua extração de PRDO.
4. Os dados serão exibidos em tela e salvos automaticamente no seu navegador.
