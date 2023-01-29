# DLS_project
порядок запуска: 
1) ноутбук с обучением модели на распознавание боксов
2) прогон начального датасета и вырезание боксов
3) загрузка нового датасета для обучения модели предсказания текста
4) 
P.S. 
их можно совместить, чтобы не делать датасет боксов. для этого нужно скачать обычный датасет и совместить две модели, при это детектор уже должен быть обучен, чтобы в recognition часть попадали обрезанные боксы. Ну и конечно для этого после предсказания детектора картинки перед подачей нужно приводить к одному размеру. Но это я к сожалению не успел сделать, но это в общем то не сложно и быстро делается.

P.P.S
входные размеры картинок для первой и второй модели - 480;480 и 100;32 (w, h)


датасеты:

ссылка на изначальный CCPD датасет - https://drive.google.com/file/d/1zTsjpnFx-8Cl3HhS5iGB3iH_aPAv6ueQ/view?usp=sharing

ссылка на датасет с обрезанными боксами - https://drive.google.com/file/d/1ypMZzqUI30pNOPtbKcsMif5Vn5Nwc8EI/view?usp=sharing




ноутбуки:

ссылка на ноутбук с детектором боксов - https://colab.research.google.com/drive/1OTdJdkb_pSTeb-T2WX_gpk5WlZRr4Dmj?usp=sharing

ссылка на ноутбук с распознаванием текста - https://colab.research.google.com/drive/1lXNmlg040pGLM9zx_xvmWUOUgdClsoGg?usp=sharing




веса моделей:

ссылка на скачивание весов модели для детекции боксов - https://drive.google.com/file/d/1ZFwLS7bqgmOGyHK9aIkYBRjKubLrpo6Y/view?usp=sharing

ссылка на скачивание весов модели для распознавания текста - https://drive.google.com/file/d/17HDMfK-wsRfvXRnw8oZmdLvcSJ11rv4x/view?usp=sharing
