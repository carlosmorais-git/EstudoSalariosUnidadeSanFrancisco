# Análise dos Salários da Unidade de San Francisco

## Contexto
Este projeto fictício simula um desafio proposto pelo CEO da Hidden Analysis, que solicitou uma análise urgente sobre os dados salariais da unidade de San Francisco. A missão: extrair insights relevantes a partir de um banco de dados SQL, com o prazo de entrega para o dia seguinte. Mesmo sendo um projeto hipotético, tratei com o mesmo comprometimento e rigor de um case real.

![image](https://github.com/user-attachments/assets/a96fc467-b5b9-4da0-8bf6-8c24dbc77c6f)


## Objetivo
Responder a uma série de perguntas estratégicas:
- Como evoluiu o **salário médio** ao longo dos anos (TotalPay e TotalPayBenefits)?
- Quantos **funcionários** tivemos por ano?
- Qual foi a **maior média salarial** por cargo e em qual ano ocorreu?
- Como evoluiu o **gasto total com salários** (TotalPayBenefits) com o passar dos anos?
- E, com ajuda de IA: **qual será a tendência salarial** para os próximos 5 anos?

## Metodologia Utilizada

1. **Extração dos dados:**
   - Os dados foram simulados como vindos de um banco SQL, estruturados em um DataFrame via Pandas.

2. **Tratamento e Limpeza:**
   - Remoção de inconsistências, nulos e padronização de tipos.
   - Conversão de colunas como `Year`, `BasePay`, `TotalPay`, `TotalPayBenefits` e `JobTitle` para facilitar a análise temporal e categórica.

3. **Análise Exploratória (EDA):**
   - Visualização por gráficos de linha e barras usando matplotlib e seaborn.
   - Comparativos anuais com médias, totais e contagens.

4. **Previsão com Inteligência Artificial:**
   - Utilização de modelos de regressão linear e polinomial para prever a tendência dos salários médios nos próximos 5 anos.
   - Validação com métricas como R² e erro quadrático médio.

## Principais Resultados
- **Salários médios** cresceram de forma consistente ao longo dos anos, com destaque para o ano de maior alta em `20XX`.
- O **número de funcionários** variou pouco, mas cresceu lentamente.
- A **maior média salarial** por cargo ocorreu em `20YY`, para o cargo de `Z`.
- O **gasto total com salários** (TotalPayBenefits) acompanhou o crescimento dos salários médios.
- A previsão mostra um crescimento moderado, mas consistente para os próximos 5 anos.

## Conclusão e Reflexões
Mais do que responder a perguntas, este projeto teve um viés estratégico: cada gráfico e insight foi apresentado como se fosse parte de uma conversa com o CEO, explicando os impactos de cada métrica para a gestão de pessoas e planejamento financeiro da organização.

![image](https://github.com/user-attachments/assets/7f4ab06f-3010-451e-b332-072f52aa9791)


A análise preditiva foi um diferencial que trouxe visão de futuro, algo essencial para empresas que querem se antecipar às tendências e não apenas reagir a elas.

---

## Tecnologias e Ferramentas Utilizadas
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **SQL (simulado)**
- **Modelos preditivos (Regressão linear e polinomial)**

Se você chegou até aqui, obrigado pela leitura! Estou pronto para aplicar esse mesmo cuidado e dedicação em análises reais que gerem valor para as empresas.


