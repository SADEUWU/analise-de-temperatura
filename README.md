# Análise de Dados de Temperatura 🌡️  

Este projeto realiza uma análise estatística de dados de temperatura, aplicando distribuições probabilísticas e testes de aderência para verificar o ajuste dos dados a modelos teóricos.  

## 📊 **Funcionalidades**  
- Carregamento e limpeza de dados de temperatura.  
- Ajuste de distribuições (Weibull, Normal, t-Student).  
- Testes de bondade de ajuste (Anderson-Darling, Cramér-von Mises).  
- Visualização com histogramas e curvas de densidade.  

## ⚙️ **Tecnologias Utilizadas**  
- Python 3  
- Bibliotecas: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`  

## 📂 **Estrutura do Código**  
```plaintext
/analise-temperatura  
│── dados/  
│   └── temperaturas.csv  
│── scripts/  
│   └── analise_temperatura.py  
│── resultados/  
│   └── graficos/  
│── README.md
  
🚀 Como Executar
Clone o repositório:

bash
git clone [URL_DO_REPO]  
Instale as dependências:

bash
pip install pandas numpy scipy matplotlib seaborn  
Execute o script:

bash
python scripts/analise_temperatura.py  
📝 Resultados
Os dados se ajustam melhor à distribuição Weibull (teste Anderson-Darling: p-valor = 0.XX).

Gráficos gerados em /resultados/graficos/:

Histograma com curva de densidade.

QQ-plot para normalidade.

📚 Referências
Documentação do SciPy: https://docs.scipy.org/

Livro: "Estatística Prática para Cientistas de Dados" (Python).

