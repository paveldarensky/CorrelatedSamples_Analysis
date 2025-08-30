# 📊 CorrelatedSamples_Analysis

Analysis of **correlated samples** demonstrating generation, correlation calculation, hypothesis testing, and confidence intervals.  
Анализ **коррелированных выборок** с генерацией данных, вычислением коэффициентов корреляции, проверкой гипотез и построением доверительных интервалов.

---

## 📌 About / О проекте

🎓 Developed as part of a course on post-statistical methods of machine learning.  
💡 Focuses on generating correlated samples with controlled correlation coefficients, performing scatterplot analysis, computing sample correlation coefficients, and applying hypothesis testing and Fisher Z-transformation for confidence intervals.  
📦 Implemented in R.

🎓 Разработано в рамках курса по статистическим методам машинного обучения.  
💡 Исследование генерации коррелированных выборок с заданными коэффициентами корреляции, построение диаграмм рассеяния, вычисление выборочных коэффициентов корреляции, проверка гипотез и построение доверительных интервалов с использованием Z-преобразования Фишера.  
📦 Реализация на R.

---

## 🔧 Features / Возможности

- 🔹 Generation of correlated samples \(X1, X2, X3\) with predefined correlation coefficients \(r1\) and \(r2\)  
  Генерация коррелированных выборок \(X1, X2, X3\) с заданными коэффициентами корреляции \(r1\) и \(r2\)

- 📉 Scatterplots of X1 vs X2 and X1 vs X3 with correlation values annotated  
  Диаграммы рассеяния X1-X2 и X1-X3 с указанием коэффициентов корреляции

- 🧮 Sample correlation coefficients computation (\(r_1^\), \(r_2^\))  
  Вычисление выборочных коэффициентов корреляции (\(r_1^\), \(r_2^\))

- 🔍 Hypothesis testing for correlation significance using Student's t-test  
  Проверка гипотезы о значимой корреляционной связи с помощью t-критерия Стьюдента

- 📐 Confidence interval calculation for correlation coefficients using Fisher Z-transformation  
  Построение доверительных интервалов для коэффициентов корреляции с помощью Z-преобразования Фишера

---

## 📁 Structure / Структура

- `X1, X2, X3` — generated samples  
  Сгенерированные выборки X1, X2, X3

- `scatterplots` — scatterplots visualizing correlations  
  Диаграммы рассеяния для наглядного анализа корреляции

- `r_hat` — sample correlation coefficients  
  Выборочные коэффициенты корреляции

- `t_statistics` — t-statistics for correlation testing  
  Статистика Стьюдента для проверки гипотез

- `CI_r` — confidence intervals for correlation coefficients  
  Доверительные интервалы коэффициентов корреляции

---

## 📊 Output / Результаты

- Scatterplots of X1-X2 and X1-X3  
- Sample correlation coefficients \(r_1^\), \(r_2^\)  
- t-statistics for correlation significance  
- 95% confidence intervals for correlation coefficients  

- Диаграммы рассеяния X1-X2 и X1-X3  
- Выборочные коэффициенты корреляции \(r_1^\), \(r_2^\)  
- Статистика t для проверки значимости корреляции  
- Доверительные интервалы 95% для коэффициентов корреляции
