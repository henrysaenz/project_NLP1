# WNatural Language Processing (NLP) Project #1

- Perform an Exploratory Data Analysis (EDA) for the provided dataset.
- Implement the classification algorithms (RNN, LSTM, GRU, and Bidirectional LSTM) for sentiment analysis using roman-urdu language dataset.
- Perform hyperparameter tuning for RNN, LSTM, GRU, and Bidirectional LSTM considering the following hyperparameters in your pipeline:

### Hyperparameter Grids

#### RNN

```python
param_grid_rnn = {
    'units': [32, 64, 128],
    'num_layers': [1, 2],
    'dropout': [0.2, 0.3],
    'learning_rate': [0.001, 0.005, 0.01],
    'batch_size': [32, 64],
    'sequence_length': [50, 100],
    'epochs': [10, 20, 30]
}
```

#### LSTM

```python
param_grid_lstm = {
    'lstm_units': [64, 128, 256],
    'num_lstm_layers': [1, 2, 3],
    'dropout_rate': [0.2, 0.3, 0.5],
    'learning_rate': [0.001, 0.005, 0.01],
    'batch_size': [32, 64, 128],
    'sequence_length': [50, 100, 200],
    'epochs': [20, 50, 100],
    'embedding_dim': [100, 200, 300]
}
```

#### GRU

```python
param_grid_gru = {
    'gru_units': [64, 128, 256],
    'num_gru_layers': [1, 2],
    'dropout_rate': [0.2, 0.3, 0.5],
    'learning_rate': [0.001, 0.005, 0.01],
    'batch_size': [32, 64, 128],
    'sequence_length': [50, 100, 200],
    'epochs': [20, 50, 100],
    'embedding_dim': [100, 200, 300]
}
```

#### Bidirectional LSTM

```python
param_grid_bilstm = {
    'lstm_units': [32, 64, 128],
    'num_lstm_layers': [1, 2],
    'dropout_rate': [0.3, 0.5],
    'learning_rate': [0.001, 0.005],
    'batch_size': [32, 64],
    'sequence_length': [50, 100],
    'epochs': [20, 50],
    'embedding_dim': [100, 200]
}
```


Check out the content pages bundled with this sample book to see more.

```{tableofcontents}
```
