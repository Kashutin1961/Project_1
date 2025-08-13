# Анализ резюме HeadHunter

Проект по визуализации и анализу данных резюме соискателей из базы HeadHunter.  
Цель — выявить зависимости между возрастом, уровнем образования, опытом работы и ожидаемой зарплатой.

---

## Структура проекта

PROJECT-1/
├── Data/ 				# Исходные датасеты (игнорируются Git) 
├── Plots/ 				# Сохранённые графики (игнорируются Git) 
├── images/ 				# PNG-графики для отображения на GitHub 
├── Project-1.Ноутбук.ipynb 		# Основной Jupyter-ноутбук анализа 
├── Project-1.Ноутбук-шаблон.ipynb 	# Шаблон для повторного использования 
├── requirements.txt 			# pip-зависимости 
├── environment.yml 			# Полная спецификация Conda окружения 
├── requirements_backup.txt 		# Резервная копия pip-зависимостей 
├── environment_backup.yml 		# Резервная копия Conda окружения 
├── README.md 				# Описание проекта 
└── .gitignore 				# Исключает временные и большие файлы

---

---

## Установка окружения

### Через Conda (рекомендуется)

```bash
conda env create -f environment.yml
conda activate Conda_VS_SkillsFactory_mac

### Через pip
pip install -r requirements.txt

⚠️ Убедитесь, что у вас установлен Python 3.13.5
📌 environment.yml включает как Conda, так и pip-зависимости

## Описание окружения
Ядро: Python 3.13.5, Jupyter, IPython
Анализ данных: NumPy, Pandas, SciPy, Statsmodels
Визуализация: Plotly, Seaborn, Matplotlib, Kaleido
Геоаналитика: GeoPandas, PyProj, Shapely, Pyogrio
Базы данных: psycopg2, psycopg2-binary
Веб-автоматизация: Selenium, Webdriver Manager
Утилиты: dotenv, orjson, xmltodict, tqdm, tabulate
Качество кода: Ruff, Pylint, Isort

## Воспроизводимость
Все зависимости зафиксированы в environment.yml и requirements.txt
Гафики экспортируются в PNG через Kaleido для отображения на GitHub
Используется .gitignore для исключения временных и больших файлов
Рекомендуется запускать ноутбуки в Conda-окружении для избежания конфликтов

## Запуск проекта
После активации окружения, запустите Jupyter:
jupyter lab

## Рекомендации по улучшению
Добавить README_en.md для англоязычных пользователей
Включить пример запуска ноутбука с демонстрацией графиков
Добавить badge-статусы (Python version, environment health)
В будущем — контейнеризация через Docker для полной переносимости

## Обратная связь
Если вы нашли ошибку или хотите предложить улучшение — создайте issue или pull request. Проект открыт для развития и доработки.

