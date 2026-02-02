# 📊 Análise Estatística de Rentabilidade: Planos Surf vs. Ultimate (Megaline)

## 🎯 Objetivo do Projeto
Análise do comportamento de consumo de clientes da empresa de telecomunicações **Megaline** para determinar qual dos planos tarifários (**Surf** ou **Ultimate**) gera maior receita. O foco central é a realização de uma análise preliminar baseada em dados de **500 clientes**, utilizando testes estatísticos para validar hipóteses sobre a lucratividade de cada plano e apoiar a tomada de decisão do departamento comercial sobre o orçamento de publicidade.

## 📈 Resultado (Preencher após a conclusão dos testes)
- **Identificação do Perfil de Consumo**: Determinação das médias de consumo de minutos, mensagens e dados por plano.
- **Validação Estatística**: Realização de testes de hipóteses que confirmaram (ou rejeitaram) se a receita média entre os planos **Ultimate** e **Surf** é significativamente diferente.
- **Análise Regional**: Comparação da receita média entre usuários da região de **NY-NJ** em relação às demais regiões.
- **Insight de Negócio**: Recomendação estratégica sobre qual plano deve receber maior investimento em marketing com base na rentabilidade observada.

## 🛠️ Ferramentas Utilizadas
- **Linguagem**: Python
- **Bibliotecas**:
  - Pandas (manipulação de dados)
  - Matplotlib/Seaborn (visualização)
  - SciPy (estatística)
- **Ambiente**: Jupyter Notebook / VS Code

## 📚 O que Aprendi
- **Tratamento e Fusão de Dados**: Consolidação de múltiplas tabelas (chamadas, mensagens, internet e usuários) para criação de um dataframe mestre por usuário/mês.
- **Transformação de Dados de Negócio**: Aplicação de regras de arredondamento específicas do setor de telecomunicações (minutos e GB) para cálculo de cobranças.
- **Estatística Descritiva**: Cálculo e interpretação de média, variância e desvio padrão para entender a dispersão do comportamento do cliente.
- **Testes de Hipóteses (Inferência)**: Formulação de hipóteses nulas ($H_0$) e alternativas ($H_1$), escolha do nível de significância ($\alpha$) e aplicação do **Teste T de Student** para comparação de médias.

## 🚀 Melhorias Futuras
- **Análise de Churn**: Identificação de padrões que levam ao cancelamento do plano (coluna `churn_date`).
- **Sazonalidade**: Estudo da variação de consumo ao longo dos meses do ano para prever picos de demanda.
- **Segmentação por Faixa Etária**: Análise de como a idade do usuário influencia a escolha do plano e o volume de dados consumidos.

---

*Projeto desenvolvido como parte do módulo de Análise de Dados.*
