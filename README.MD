# 🛠️ Проект: Бинарная классификация для предиктивного обслуживания оборудования

## 📌 Описание проекта
Цель проекта — разработать модель машинного обучения, которая предсказывает, произойдет ли отказ промышленного оборудования (`Target = 1`) или нет (`Target = 0`).  
Проект включает анализ данных, обучение моделей, визуализацию результатов и реализацию удобного интерфейса в виде **Streamlit-приложения** с несколькими страницами.

## 📊 Датасет
Используется датасет **[AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/predictive+maintenance+data)**.  
Характеристики:
- 10 000 записей
- 14 признаков: телеметрия, условия эксплуатации, идентификаторы, целевая переменная (`Machine failure`)
- Подходит для задач бинарной классификации и предиктивного обслуживания

## 🚀 Установка и запуск

### 🔧 1. Клонировать репозиторий
```bash
git clone https://github.com/VARWA/predictive_maintenance_project
cd predictive_maintenance_project
```
### 🧪 2. Создать и активировать виртуальное окружение (рекомендуется)
```
python3 -m venv venv
source venv/bin/activate
```
### 📦 3. Установить зависимости
```bash
pip install -r requirements.txt
```
### ▶️ 4. Запустить приложение
```bash
streamlit run app.py
```
### 📁 Структура репозитория
```
├── app.py                  # Главный файл запуска Streamlit-приложения
├── analysis_and_model.py   # Страница анализа данных и обучения модели
├── presentation.py         # Страница с презентацией проекта
├── requirements.txt        # Список Python-зависимостей
├── data/                   # Папка с датасетом
├── video/                  # Папка с демонстрационным видео
└── README.md               # Описание проекта
```
### 🎥 Видео-демонстрация
**[Ссылка на видео](video/demo.mp4)**.  


