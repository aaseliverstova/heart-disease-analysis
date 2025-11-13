# heart-disease-analysis

# Анализ данных о сердечных заболеваниях

Проект по анализу датасета Heart Disease UCI для прогнозирования коронарной болезни сердца.

## Структура проекта

- `data/heart_disease_uci.csv` - исходные данные
- `notebooks/heart-disease-analysis.ipynb` - основной ноутбук с анализом

## Описание данных

Датасет содержит 920 наблюдений с 16 признаками:
- **Демографические**: age, sex
- **Медицинские показатели**: trestbps, chol, thalch, oldpeak
- **Симптомы**: cp, exang, fbs
- **Диагностические**: restecg, slope, ca, thal
- **Целевая переменная**: num (степень поражения артерий)

## Быстрый старт

```bash
# Клонировать репозиторий
git clone https://github.com/yourusername/heart-disease-analysis.git

# Запустить Jupyter
jupyter notebook
