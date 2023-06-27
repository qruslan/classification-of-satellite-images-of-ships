## Сравнение архитектур нейронных сетей для задачи классификации снимков кораблей со спутника

Dataset: https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery

Stack: python, numpy, pandas, matplotlib, tensorflow, keras

В сравнение использовались модели: VGG19, Xception, Inceptionv3, ResNet50v2, DenseNet169, NASNetLarge.

Все модели предобучены на наборе данных ImageNet.

Лучший результат показали:
    
    - ResNet50v2   acc = 0.9925
    
    - DenseNet169  acc = 0.9950
