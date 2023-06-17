Dataset **kcow1** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/a/m/6w/TYnaJFiQcyav1jBpQ2BEypXETSgSNUwnGil4fErKoeuXPXcmoWqA4OkcLQlIqxtLOsT4NgFES0QNuMy0UDu6wFUTRdrVMfJe2MBvr6i1qv1GNJA8SfCwjwFXPgZr.tar)

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