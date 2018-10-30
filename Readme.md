# Object-Detection

* Using Object-Detection utils from tensorlfow

### Retrieve object_detection API

- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/utils`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/core`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/data`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/protos`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/test_images`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/builders`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/anchor_generators`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/models`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/box_coders`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/predictors`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/matchers`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/meta_architectures`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/data_decoders`
- `svn checkout https://github.com/tensorflow/models/trunk/research/object_detection/samples`

- `svn checkout https://github.com/tensorflow/models/trunk/research/slim/nets`

### Install

- `protoc object_detection/protos/*.proto --python_out=.`
