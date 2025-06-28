# 📊 Análise Quantitativa com PCA: Score do PC1 vs SPY

Este projeto aplica **Análise de Componentes Principais (PCA)** sobre uma carteira com 10 ações americanas, comparando o **comportamento do PC1 (primeiro componente principal)** com o **índice SPY** (ETF que representa o S&P 500). A normalização e acumulação dos valores permitem observar **co-movimento e correlação com o risco sistêmico de mercado**.

---

## 🎯 Objetivo

Verificar se o **PC1 da carteira** representa o **fator de mercado**, ou seja, se ele se comporta de forma semelhante ao SPY ao longo do tempo.

---

## 🔍 Resultado

✅ **O score acumulado do PC1 acompanha de perto o retorno acumulado do SPY** (ambos normalizados como Z-score).  
Isso sugere que:

- O PC1 está capturando o movimento do mercado.
- A carteira analisada possui forte exposição ao fator de risco sistêmico.
- A PCA pode ser usada como ferramenta de **análise de fatores implícitos** e **risk decomposition**.

---

## 🛠️ Tecnologias usadas

- `Python`
- `pandas`
- `numpy`
- `yfinance`
- `scikit-learn`
- `matplotlib`

---

## 🧪 Execução

```bash
pip install yfinance pandas numpy matplotlib scikit-learn
