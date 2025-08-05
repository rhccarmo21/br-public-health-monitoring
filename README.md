# BR Public Health Monitoring

Monitoramento e predição de indicadores de saúde pública no Brasil

## 🌡️ Visão Geral

Este projeto tem como objetivo monitorar, analisar e prever indicadores de saúde pública no Brasil, utilizando dados epidemiológicos oficiais. O sistema busca:

- Acompanhar tendências de doenças e agravos
- Identificar surtos e epidemias em estágio inicial
- Prever demanda por serviços de saúde
- Analisar disparidades regionais
- Monitorar cobertura vacinal e outros indicadores preventivos

## 📊 Fontes de Dados

O projeto utiliza dados oficiais de saúde pública:

- [DATASUS/TabNet](http://tabnet.datasus.gov.br/)
- [SIVEP-Gripe](https://opendatasus.saude.gov.br/dataset/srag-2021-a-2023)
- [Sistema de Informação de Agravos de Notificação (SINAN)](https://portalsinan.saude.gov.br/)
- [IBGE - Indicadores Sociais](https://www.ibge.gov.br/estatisticas/sociais.html)
- [Ministério da Saúde - Painéis](https://www.gov.br/saude/pt-br)

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas/Numpy
- Scikit-learn/Statsmodels
- Matplotlib/Seaborn
- Plotly/Dash
- SQL/PostgreSQL (para armazenamento)
- Airflow (para pipelines de dados)

## 📂 Estrutura do Projeto

```
br-public-health-monitoring/
├── data/
│   ├── raw/                 # Dados brutos baixados das fontes
│   ├── processed/           # Dados tratados e normalizados
│   └── outputs/             # Bases consolidadas para análise
├── notebooks/               # Análises exploratórias
├── scripts/
│   ├── data_processing/     # Scripts de ETL
│   ├── modeling/            # Modelos preditivos
│   └── visualization/       # Geração de dashboards
├── docs/                    # Documentação técnica
├── requirements.txt         # Dependências
└── README.md                # Este arquivo
```

## 🚀 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/br-public-health-monitoring.git
   cd br-public-health-monitoring
   ```

2. Configure o ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate    # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute o pipeline de dados:
   ```bash
   python scripts/data_processing/main_pipeline.py
   ```

5. Para visualizações interativas:
   ```bash
   python scripts/visualization/dashboard.py
   ```

## 📈 Principais Indicadores Monitorados

- Doenças de notificação compulsória
- Síndromes respiratórias (incluindo COVID-19)
- Coeficientes de mortalidade
- Cobertura vacinal
- Internações por causas evitáveis
- Acesso a serviços básicos de saúde

## 🤝 Contribuição

Contribuições são bem-vindas seguindo o fluxo:

1. Abra uma issue descrevendo sua proposta
2. Faça um fork do projeto
3. Crie uma branch para sua feature (`git checkout -b feature/nova-analise`)
4. Commit suas mudanças (`git commit -m 'Adiciona análise de cobertura vacinal'`)
5. Push para a branch (`git push origin feature/nova-analise`)
6. Abra um Pull Request

## 📄 Licença

Distribuído sob licença MIT. Veja `LICENSE` para mais informações.

## ✉️ Contato

Equipe de Saúde Pública - saude.publica@exemplo.com

Link do Projeto: [https://github.com/seu-usuario/br-public-health-monitoring](https://github.com/seu-usuario/br-public-health-monitoring)