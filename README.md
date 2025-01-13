# Aplicativo e Dashboard IMDb 🎥📊

## Descrição
Este repositório contém uma série de ferramentas e protótipos voltados para a **catalogação**, **análise** e **organização** de filmes, séries e livros. Ele é composto por planilhas, aplicativos e dashboards criados em Python e Google Sheets, projetados para facilitar o gerenciamento e a exploração de dados relacionados ao universo cinematográfico.

---

## Componentes do Repositório

### 1. **Planilha de Filmes, Séries e Livros**
- **Descrição**: Uma planilha em Google Sheets para organizar e catalogar seus filmes, séries e livros.
- **Recursos**:
  - Colunas para gênero, notas, média, status de assistido e outras informações relevantes.
  - Filtros para facilitar a navegação e análise.
  - Design colorido e intuitivo.
    
 
<div align="center">
    <img src="https://github.com/dsilvaphy/Aplicativo-e-Dashboard-IMDB/blob/main/captura_planilha.png" alt="printmapas" width="850" height="160">
</div>


### 2. **Aplicativo `app_mira`**
- **Descrição**: Um aplicativo que funciona com uma API para armazenar e gerenciar sua lista de filmes. Além disso, permite adicionar informações extras aos filmes.
- **Principais Recursos**:
  - **Upload da sua lista de filmes**.
  - Retorno de informações adicionais sobre os filmes.
  - Adicionar notas, sentimentos, status de assistido e onde foi assistido.
  - Interface simples para manipulação de dados

<div align="center">
    <img src="https://github.com/dsilvaphy/Aplicativo-e-Dashboard-IMDB/blob/main/captura_app.png" alt="printmapas" width="550" height="450">
</div>
  
### 3. **Planilha IMDb (`imdb.xlsx`)**
- **Descrição**: Uma planilha com filmes aleatórios do IMDb usada como base para higienização e análise.
- **Uso no código**: Esta planilha é processada pelo script `higienizacao_e_dashboard`.

### 4. **Código `higienizacao_e_dashboard`**
- **Descrição**: Script em Python que realiza:
  1. **Higienização dos dados**:
     - Limpeza e preparação dos dados da planilha IMDb.
  2. **Criação de uma nova planilha (Gêneros)**:
     - Separação de filmes que possuem mais de um gênero em diferentes linhas.
  3. **Dashboard Interativo**:
     - Um dashboard criado com bibliotecas Python para análise visual dos filmes.
     - Inclui gráficos de lançamentos por ano e filtros para explorar dados de forma interativa.

<div align="center">
    <img src="https://github.com/dsilvaphy/Aplicativo-e-Dashboard-IMDB/blob/main/captura_dashboard2.png" alt="printmapas" width="550" height="350">
</div>

<div align="center">
    <img src="https://github.com/dsilvaphy/Aplicativo-e-Dashboard-IMDB/blob/main/captura_dashboard1.png" alt="printmapas" width="550" height="350">
</div>

---

## Tecnologias Utilizadas
- **Google Sheets**: Organização de dados em planilhas.
- **Python**:
  - Bibliotecas utilizadas: `pandas`, `plotly`, entre outras.
  - Scripts para processamento e visualização de dados.
- **API**: Integração com o aplicativo `app_mira` para armazenamento e manipulação de dados.

---

## Como Usar

1. **Planilha de Filmes, Séries e Livros**:
   - Abra no Google Sheets.
   - Comece a adicionar e organizar seus filmes, séries e livros.

2. **Aplicativo `app_mira`**:
   - Execute o script `app_mira.py` para subir sua lista de filmes.
   - Preencha informações adicionais diretamente no aplicativo.

3. **Planilha IMDb e Script de Higienização**:
   - Abra o arquivo `higienizacao_e_dashboard.py`.
   - Certifique-se de que as bibliotecas necessárias estão instaladas.
   - Execute o script para:
     - Higienizar os dados.
     - Gerar a planilha de gêneros.
     - Visualizar o dashboard interativo.


---

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir um `pull request` ou relatar problemas na aba de `issues`.

---

## 📄 Licença

Este projeto está licenciado sob a **Creative Commons Attribution-NonCommercial 4.0 International License**. Não é permitido usar o código para fins comerciais.

Veja a licença completa [CC BY-NC 4.0](/creativecommons.org/licenses/by-nc/4.0/deed.pt-br).

---

Divirta-se explorando e organizando seus filmes! 🍿🎬
