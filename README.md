# Modelo Preditivo para Detecção de URLs de Phishing

Bem-vindo ao repositório do projeto de **Detecção de URLs de Phishing**! Este projeto utiliza técnicas de Machine Learning para prever se uma URL é legítima ou maliciosa (phishing) com base em características extraídas do código-fonte e da própria URL.

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte da disciplina **Big Data para Dados Públicos** no **Insper**. O objetivo principal foi criar um modelo preditivo capaz de diferenciar URLs legítimas de URLs de phishing. A base de dados utilizada foi a **PhiUSIIL Phishing URL Dataset**, disponível no Kaggle.

**Principais Características**:
- Extração de features como comprimento da URL, taxa de continuidade de caracteres e probabilidade de legitimidade de TLD.
- Uso do modelo **Gradient Boosting Trees (GBT)** para classificação.
- Predições com probabilidades detalhadas para maior transparência.

## 🚀 Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **PySpark**: Framework para manipulação de dados em larga escala e Machine Learning.
- **Databricks**: Ambiente de desenvolvimento e execução dos experimentos.
- **MLflow**: Rastreamento e monitoramento do treinamento do modelo.

## 📊 Funcionalidades

- Extração automática de features de URLs.
- Treinamento e validação de modelos de classificação.
- Predição de URLs com probabilidades detalhadas de phishing e legitimidade.

## 🛠️ Como Usar

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/phishing-url-detector.git
   ```
2. Execute os notebooks disponíveis no repositório para realizar o treinamento e validação do modelo.
