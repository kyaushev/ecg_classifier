# Классификации ЭКГ

Этот репозиторий содержит Jupyter-ноутбуки для проекта классификации ЭКГ, в котором исследуются как классические методы машинного обучения, так и подходы на основе больших языковых моделей (LLM).

## Ноутбуки

*   [**`data_analysys.ipynb`**](https://github.com/kyaushev/ecg_classifier/blob/main/data_analysys.ipynb  ): Первичный анализ данных, очистка, генерация и отбор признаков.
*   [**`compare_classic.ipynb`**](https://github.com/kyaushev/ecg_classifier/blob/main/compare_classic.ipynb  ): Сравнение классических моделей машинного обучения (SVM, Логистическая регрессия, Random Forest, XGBoost) с использованием вложенной кросс-валидации.
*   [**`llmcpp_test.ipynb`**](https://github.com/kyaushev/ecg_classifier/blob/main/llmcpp_test.ipynb  ): Первоначальные эксперименты с LLM с использованием `llama.cpp`.
*   [**`vllm_test.ipynb`**](https://github.com/kyaushev/ecg_classifier/blob/main/vllm_test.ipynb  ): Тестирование и примеры для решения на основе LLM с использованием vLLM и вызова инструментов (Tool Calling).
