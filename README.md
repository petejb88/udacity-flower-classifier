# python_projects

Part of the AI Programming with Python nandegree.

train.py:
- Use transfer learning, based on one of the Torchvision pretrained models, to produce a model trained to classify flower images
- saves model as checkpoint

predict.py:
- loads checkpoint to (re)create model, trained as above
- predicts flower name for given image file path

cat_to_name.json:
- dictionary of categorical outputs of the model with their associated flower names

