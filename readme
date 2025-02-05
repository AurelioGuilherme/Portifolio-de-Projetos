# Análise Fatorial Exploratória - Consumo Mundial de Energia

## Descrição do Projeto
Este projeto realiza uma **Análise Fatorial Exploratória (AFE)** para identificar estruturas latentes em dados de consumo mundial de energia. O objetivo é reduzir a dimensionalidade de 55 variáveis relacionadas a energia (renovável, fóssil, nuclear, etc.) e agrupá-las em fatores subjacentes. O dataset utilizado é o [World Energy Consumption](https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption), disponível no Kaggle.

## Principais Etapas
1. **Pré-processamento**:
   - Seleção de 55 variáveis quantitativas contínuas.
   - Substituição de valores ausentes (`NaN`) por zero (simplificação para fins didáticos).
   - Padronização dos dados com `StandardScaler`.

2. **Pressupostos da AFE**:
   - **Correlação entre variáveis**: Análise de matriz de correlação.
   - **Adequação dos dados**: Teste de Esfericidade de Bartlett e Medida de Adequação da Amostra (KMO).

3. **Análise Fatorial**:
   - Determinação do número de fatores via critério de Kaiser (autovalores > 1) ou análise do scree plot.
   - Rotação Varimax para interpretação dos fatores.

## Requisitos
- Python 3.8+
- Bibliotecas:
  ```bash
  pandas matplotlib seaborn numpy scikit-learn factor-analyzer ipywidgets
  ```


## Como Reproduzir
1. Clone o repositório:

    ```bash
    git clone https://github.com/AurelioGuilherme/analise_fatorial_energia.git
    cd analise_fatorial_energia
    ```

2. Crie um ambiênte virtual:

   ```bash
    python -m venv .venv
   ```

3. Ative o ambiênte virtual:

  ```bash
  .venv\Scripts\activate
  ```

4. Instale as dependências listadas no arquivo `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

5. Execute o Jupyter Notebook `Analise_fatorial.ipynb`

