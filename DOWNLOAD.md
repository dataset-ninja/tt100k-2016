Dataset **Tsinghua Tencent 2016** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://www.dropbox.com/scl/fi/ery6sgxupndagiri6rzex/tsinghua-tencent-2016-DatasetNinja.tar?rlkey=y1kldw0dlwb57vjcrsxslyv6f&dl=1)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Tsinghua Tencent 2016', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://cg.cs.tsinghua.edu.cn/traffic-sign/data_model_code/data.zip).