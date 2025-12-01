# Laboratorio-Azure-Language-Studio-
Para este laboratório, utilizei o recurso Sentiment Analysis + Opinion Mining do Azure Language Studio.

Análise de Sentimentos e Opiniões – Azure Language Studio

Resumo dos Resultados em Tabela

🧩 Tabela Geral – Resumo das Sentenças
| **Sentença** | **Texto**                                                              | **Sentimento** | **Positivo** | **Neutro** | **Negativo** | **Target Detectado**   | **Assessment**                 |
| ------------ | ---------------------------------------------------------------------- | -------------- | ------------ | ---------- | ------------ | ---------------------- | ------------------------------ |
| **1**        | O sistema trava o tempo inteiro e isso está prejudicando meu trabalho. | Negativo       | 0%           | 6%         | 94%          | sistema                | prejudicando (negativo – 100%) |
| **2**        | Já tentei várias vezes resolver com o suporte, mas ninguém responde.   | Negativo       | 1%           | 18%        | 80%          | — *(não identificado)* | —                              |
| **3**        | Minha experiência está sendo péssima.                                  | Negativo       | 0%           | 1%         | 99%          | experiência            | péssima (negativo – 100%)      |


📝 Tabela de Targets e Opiniões (Opinion Mining)

| **Sentença** | **Target (Alvo)** | **Assessment** | **Sentimento do Assessment** | **Confiança** |
| ------------ | ----------------- | -------------- | ---------------------------- | ------------- |
| 1            | sistema           | prejudicando   | Negativo                     | 100%          |
| 3            | experiência       | péssima        | Negativo                     | 100%          |

📈 Tabela de Análise por Emoção (geral)

Esta tabela interpreta os resultados em termos emocionais, útil para relatórios qualitativos.

| **Sentença** | **Emoção Predominante**         | **Intensidade** | **Justificativa**                  |
| ------------ | ------------------------------- | --------------- | ---------------------------------- |
| 1            | Frustração / Irritação          | Alta            | Sistema trava + prejudica trabalho |
| 2            | Desesperança / Descontentamento | Média           | Suporte não responde               |
| 3            | Insatisfação / Decepção         | Muito Alta      | “pessíma” → intensidade absoluta   |

Localização das Imagens

| **Sentença** | **Arquivo**             |
| ------------ | ----------------------- |
| 1            | `/images/sentence1.png` |
| 2            | `/images/sentence2.png` |
| 3            | `/images/sentence3.png` |


🧠 Conclusões da Análise

As três sentenças foram classificadas como negativas.

O Azure identificou adequadamente os alvos (targets) e suas avaliações (assessments).

O sentimento negativo tem alta confiança em todas as frases, indicando consistência do modelo.

A ferramenta destacou corretamente termos negativos como “prejudicando” e “péssima”, refletindo problemas de experiência do usuário.


