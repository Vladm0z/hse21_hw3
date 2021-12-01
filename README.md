# hse21_hw3  

# Часть 1  
Ссылка на коллаб - https://colab.research.google.com/drive/14lzDVSKQfnJOXECxgvL4kjQWa07ylIyc?usp=sharing

## Проверка качества чтений из fastQC: сравнительная статистика из multiQC
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_general_statistics.jpg)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_sequence_counts_plot.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_per_base_sequence_quality_plot.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_per_sequence_quality_scores_plot%20(1).png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_per_sequence_gc_content_plot.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_per_base_n_content_plot.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_sequence_duplication_levels_plot.png)
## Общая статистика
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc-status-check-heatmap.png) 
## Подсчет количества чтений, соответствующих одному или более гену 
![image]()
## Таблица с информацией по каждому из 6 образцов  
| ID образца | Тип образца  | Общее кол-во исходных чтений | Кол-во и процент чтений, которые были успешно откартированы на геном (не уникально) | Кол-во и процент чтений, которые были успешно откартированы на геном (уникально) | Общее кол-во чтений, которые попали на гены |
|----------|:-------:|:----------------:|:----------------:|:----------------:|:----------------:|
| **SRR3414629** | reprogr | 0 | 0 | 0 | 0 |
| **SRR3414630** | reprogr | 0 | 0 | 0 | 0 |
| **SRR3414631** | reprogr | 0 | 0 | 0 | 0 |
| **SRR3414635** | control | 0 | 0 | 0 | 0 |
| **SRR3414636** | control | 0 | 0 | 0 | 0 |
| **SRR3414637** | control | 0 | 0 | 0 | 0 |
## all_counts содержит в себе все чтения  
![image]()

# Часть 2. Анализ с помощью DESeq2  
Ссылка на коллаб - https://colab.research.google.com/drive/1g4FF3g77jHX2aIgrExYfrjP7h5bX8G5d?usp=sharing
## MA-plot, показывающий Log2FC для генов  
![image]() 
## Heatmap зависимости экспрессии генов контрольных и репрограммированных образцов
![image]()
## 
