Dataset **kcow1** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/w/v/qG/GO3ABO5VJWVrj07DeZYD7YTqFOhiCA3pEhAyAFKlbfJoAtPfkkTIZ6tfp99PwImXNKt33huJMCGD4kv9ZGQnYe4DK71XNYGbCyMFF4ZJycpC2qIMVgmCUtPSvy7P.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='kcow1', dst_path='~/dtools/datasets/kcow1.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/sungho/kcow1/dataset/2/download)