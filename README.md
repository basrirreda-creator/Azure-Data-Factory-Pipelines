# Azure Data Factory Pipelines

⚙️ Orchestration de pipelines ETL complexes avec Azure Data Factory

## 📊 Statistiques

- **45** pipelines ETL
- **500 GB** de données traitées quotidiennement
- **99.95%** de disponibilité
- **65%** de réduction des temps d'exécution
- **42%** d'optimisation des coûts

## 🎯 Architecture

Data Sources (SQL Server, APIs)
↓
Azure Data Factory
↓
Transformations (Data Flows)
↓
Azure SQL DW
↓
Power BI / Analytics

## 🛠️ Technologies

- Azure Data Factory
- SQL Server
- Data Flows
- Python
- Power BI

## 🚀 Installation

```bash
git clone https://github.com/reda-basrir/azure-data-factory-pipelines.git
cd azure-data-factory-pipelines
pip install -r requirements.txt

# Configurer Azure CLI
az login
az account set --subscription <subscription-id>
