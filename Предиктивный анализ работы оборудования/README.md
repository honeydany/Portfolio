# Предиктивный анализ работы оборудования
## Задача
Проанализировать информацию с датчиков о работе оборудования, разработать математическую модель определения аномальной работы компрессора 250А с применением машинного обучения
## Используемые инструменты
tensorflow (keras), sklearn, pandas, matplotlib, numpy, seaborn
## Вывод
* Оба подхода к моделированию (модель PCA+расстояние Махаланобиса и модель автоэнкодера) дают схожие результаты, который позволяют выявить предстоящую неисправность задолго до фактического отказа 
* Основное различие заключается в том, как определить подходящее пороговое значение для выявления аномалий, чтобы избежать многих ложных срабатываний при нормальных условиях эксплуатации
