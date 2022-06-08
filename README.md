# football
## task 1

Есть информация по результативности (кол-во забитых голов) игры футболистов в некоторой лиге. Можно взять любую лигу, данные за прошлые годы есть в открытом доступе.
У каждого футболиста есть цена контракта. Имея ограниченный бюджет на команду, необходимо подобрать команду с максимальной результативностью на следующие N матчей.
Выбрать модель для решения задачи, обосновать выбор модели, показать эффективность работы модели.

There is information on the effectiveness (number of goals scored) of the game of football players in a certain league. You can take any league, data for past years is publicly available. Each player has a contract price. Having a limited budget for a team, it is necessary to select a team with maximum performance for the next N matches. Choose a model to solve the problem, justify the choice of the model, show the effectiveness of the model.

Синтетические данные для задачи: (data)
https://drive.google.com/file/d/1--XsaVup_MXJBIGVeODLBcy7EDBjK2_f/view?usp=sharing
https://drive.google.com/file/d/1-2tBX0Mc8i-g2VEv-W9_YvLfiW1u-gQ4/view?usp=sharing

Реализация доступна по ссылке: 
https://colab.research.google.com/drive/1PhjHNONSgL7zjF5fHURGu1F8p8KYPQ4s?usp=sharing

## task 2

2. Есть фотография куска футбольного поля. Необходимо определить, есть ли на фото футболист и стоит ли он или не стоит (сидит/лежит).
Задачу можно решить, используя открытые библиотеки.

There is a photo of a piece of a football field. It is necessary to determine whether there is a footballer in the photo and whether he is standing or not standing (sitting / lying down).
The problem can be solved using open libraries.

готовое решение по определению позы человека на основе  модели openvino: https://github.com/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch
тестовые фото для запуска (data): https://drive.google.com/drive/folders/1BIB1lboJPj_jW1BB6qUgpP6E5XAMkora?usp=sharing

запуск модели: python demo.py --model human-pose-estimation-3d.pth --images 'your_photo'
примеры результатов по фото для запуска: https://drive.google.com/drive/folders/1tl9Su8kmkh2BTIO_zk2C35bmmcujEA2K?usp=sharing

