# Cálculo de Métricas de Avaliação de Aprendizado

## Objetivo:
  Calcular as principais métricas para avaliação de modelos de classificação de dados:
      
      - Sensibilidade
      - Especificidade
      - Acurácia
      - Precisão e 
      - F-score

## Métricas Utilizada:  
  Matriz utilizada para os cálculos das métricas.

  <img width="906" height="667" alt="image" src="https://github.com/user-attachments/assets/362da87f-e996-4ca7-9ebf-8c34f6f356c3" />

    VP: verdadeiros positivos.
    FN: falsos negativos.
    FP: falsos positivos.
    VN: verdadeiros negativos.
    P: precisão.
    S: sensibilidade.
    N: total de elementos.

## Valores utilizados
    VP = 42
    FN = 18
    FP = 8
    VN = 132

## Cálculo de Métricas
### Sensibilidade = VP / (VP + FN)
    Mede a proporção de casos positivos reais que foram corretamente identificados pelo modelo.
  
    Sensibilidade = 42 / (42 + 18) ≅ 0,7 ou ≅ 70%

### Especificidade = VN / (VN + FP)
    Mede a proporção de casos negativos reais que foram corretamente identificados pelo modelo.
    
    Especificidade = 132 /(132 + 8) ≅ 0,94 ou ≅ 94%

### Acurácia = (VP + VN) / (VP + FN + FP + VN)
    Mede a proporção total de previsões corretas (tanto positivas quanto negativas) em relação ao número total de casos.

    Acuracia = (42 + 132) / (42 + 18 + 8 + 132) = 174 / 200 = 0,87 ou = 87%
