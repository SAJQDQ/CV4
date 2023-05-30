# CV_4
На основе ноутбука с примером из лекции (segmentation.ipynb) написать свою версию Unet (заготовка для задачи - segmentation_by_hands.ipynb) - слои должны создаваться вручную, работа ведется с датасетом oxford_iiit_pet. Глобально менять архитектуру сети нельзя. Можно добавлять слои (но только вручную), менять функции активации, функцию ошибки, размеры batch и количество эпох. Цель - добиться от нейросети из segmentation_by_hands точности не ниже, чем для нейросети из segmentation при 20 эпохах.

1. Имортируем нужные библиотеки и подгружаем датасет  

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_1.png)  

2. Загружаем и нормализуем изображения  

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_2.png)  

3. Задаем параметры для обучения модели и загружаем обучающие и тестовые изображения  

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_3.png)  

4. Расширение данных перед обучением модели  

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_4.png)  

5. Визуализируем случайное изображение и его маску из обучающего набора данных  

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_5.png)  

6. Прописываем, какие слои будут в нашей модели U-Net и определяем её для сегментации изображений  

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_6.png)  
![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_7.png)  

7. Визуализация архитектуры модели  

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.png) 

8. Создаём маски сегментации

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_8.png)  

9. Обучаем модели   

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_9.png)  

10. Итоговый результат   

![image info](https://github.com/SAJQDQ/CV4/blob/main/CV4%20png/Screenshot_10.png) 
