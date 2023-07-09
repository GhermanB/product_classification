# Классификация товаров маркетплейса 05.2022
**Быстро, точно, эффективно**  :)



Простейшая классификация названий и текстовых описаний товаров на основе BERT ([DeepPavlov/rubert-base-cased](https://huggingface.co/DeepPavlov/rubert-base-cased)).
Большое количество лейблов - более 1200

Модель после дообучения доступна по ссылке:
[GoogleDrive](https://drive.google.com/drive/folders/1R6uy41OWqFmZlyaUd4bPS6iLhH9aMzR4?usp=sharing)

Ноутбук доступен по ссылке:
[GoogleColab](https://colab.research.google.com/drive/1wzY0p8_MtZqJx_g_5KuvUSJKJ7bIKYHI?usp=sharing)


## Возможно потребуются библиотеки:

- Transformers
- Sklearn
- Torch
- Pyarrow

```sh
!pip install transformers torch sklearn pyarrow
```



## Промежуточные и финальные результаты обучения
  
##
##

| Эпоха | Валидация |
| ------ | ------ |
| 1 эпоха | F1: 0.71 |
| 2 эпоха | F1: 0.81 |
| 3 эпоха | F1: 0.84 |
| 4 эпоха | F1: 0.85 |
| Тест-сет | F1: 0.85 |
| Окончательно | hF1: 0.93 |

> Обучение заняло 4 часа на PNY Quadro P5000
