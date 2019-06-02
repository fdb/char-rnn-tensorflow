To run using Paperspace job builder:

1. Choose machine type: you can choose a low-cost instance. I prefer the P100.
2. Choose a container: `tensorflow/tensorflow:latest-gpu-py3`
3. Workspace: `https://github.com/fdb/char-rnn-tensorflow.git`
4. Command: `python3 train.py --data_dir data/font-awesome --num_layers 3 --num_epochs 200 --save_dir /artifacts`
5. Ports: leave empty
6. Custom metrics: leave empty
