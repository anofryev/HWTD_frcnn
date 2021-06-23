На основе https://github.com/broadinstitute/keras-rcnn

- `train_frcnn.py` для обучения. Пример использования:
`python train_frcnn.py -p /path/to/pascalvoc/`
  
- simple_parser.py - альтернативный спооб представления данных для обучения:

Пример:
/data/imgs/img_001.jpg,837,346,981,456,cow

В общем виде для запуска обучения на упрощенном формате:
`python train_frcnn.py -o simple -p my_data.txt`

- `test_frcnn.py` - для олучения прогнозов Пример запуска:
    `python test_frcnn.py -p /path/to/test_data/`