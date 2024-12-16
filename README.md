# Data Collect

## Descrição do Projeto
O projeto **Data Collect** é uma coleção de scripts desenvolvidos para coletar e organizar dados de diferentes fontes, como:

- **ResidentEvil**: Coleta de dados relevantes sobre o jogo.
- **JovemNerd**: Extração de informações de episódios do Jovem Nerd.
- **TabNews**: Extração de conteúdos do site Tab News.

Os dados são armazenados em diferentes formatos, como JSON, CSV e Parquet, para facilitar a análise e o uso em diferentes contextos.

## Estrutura do Projeto
- **ResidentEvil/**: Scripts e dados coletados relacionados à franquia Resident Evil.
- **jovemNerd/**: Scripts para extração de episódios do Jovem Nerd.
  - **data/episodios/json/**: Dados extraídos em formato JSON.
- **tab-news/**: Scripts para coleta de conteúdos do site Tab News.
  - **data/contents/json/**: Dados extraídos em formato JSON.

## Requisitos
Para rodar este projeto, você precisará de:

- Python 3.8 ou superior.
- Dependências listadas no arquivo `requirements.txt` (caso exista).

## Como Utilizar
1. Clone este repositório:
   ```bash
   git clone https://github.com/D-Salge/data-collect.git
   cd data-collect
   ```

2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute os scripts de coleta de dados:
   - Para ResidentEvil:
     ```bash
     python ResidentEvil/collect.py
     ```
   - Para JovemNerd:
     ```bash
     python jovemNerd/episodios.py
     ```
   - Para TabNews:
     ```bash
     python tab-news/basic_content.py
     ```

## Exemplos de Saída
Os dados coletados serão salvos em diretórios organizados dentro de cada pasta fonte:
- **JSON**: Arquivos com dados em formato legível e estruturado.
- **CSV** e **Parquet**: Arquivos para análise mais avançada.

## Contribuição
Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este projeto.

## Contato
[GitHub - D-Salge](https://github.com/D-Salge)
