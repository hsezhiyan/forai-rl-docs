========
Usage
========

To start training::

	$ python train.py --sys ... --hparams ... --output_dir ...

Run tensorboard to visualize training::

	$ tensorboard --logdir ...

Test agent::

	$ python train.py --sys ... --hparams ... --output_dir ... --training False --render True

The sys command can be one of two options: ``local`` or ``tpu`` for GCP enabled tpu training. A list of environments and hyperparameters can be found under ``rl/rl/hparams``. A full training and evaluation example can be found in the tutorial section.