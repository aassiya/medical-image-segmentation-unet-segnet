# medical-image-segmentation-unet-segnet

Бинарная семантическая сегментация дерматоскопических изображений кожи (датасет PH2 из 200 снимков). 

Реализованы с нуля функции потерь - BCE (с математическим выводом численно стабильной формулы), Dice Loss и Focal Loss. 

Обучены и сравнены две архитектуры: SegNet (на основе энкодера VGG-16 с MaxUnpool2d в декодере) и U-Net со skip-connections. 

**Метрика качества** - IoU (Jaccard Index). 

**Стек**: PyTorch, torchmetrics, scikit-image.
