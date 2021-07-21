##  run command: 
    python fit.py [-parameters]
## parameters description
    -data_path 
        path of data used for fitting the model, e.g. ./data/trainingdata.csv
    -random_seed
        random seed
    -lr
        learning rate, default=0.01
    -val_p
        proportion of partition validation set, default=0.2
    -batch_size
        how many data batched for training, default=256:
    -device
        where to train the model, default='cuda'
    -model_num
        number of submodels(MLP\CNN etc. Classifier), default=5
    -input_size
        dimention of input featrue (number of column of input_file), default=10
    -hidden_size
        hidden state's dimention of linear layer, default=64
    -output_size
        whole model's output vector dimention, default=5
    -dropout_p
        probability applied by dropout layer, default=0.2
    -model_save_dir
        model parameter save dir, default='./model/'
    -train_balance
        whether to enhance data, default=True
