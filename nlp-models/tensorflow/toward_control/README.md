
<img src="https://github.com/zhedongzheng/finch/blob/master/nlp-models/assets/control-vae.png" height='300'>


```
├── base
│   └── base_model.py   
│   └── base_trainer.py   
│
├── configs
│   └── config.py   
│
├── data               
│   └── imdb        
│       └── vae_pipeline.py
│       └── wake_sleep_pipeline.py
│
├── log             
│   └── example.py
│
├── mains              
│   └── pretrain.py   # first run this
│   └── train.py      # then run this
│  
├── model              
│   └── discriminator.py
│   └── encoder.py
│   └── generator.py
│   └── vae.py
│   └── wake_sleep.py
│
├── trainer              
│   └── vae_trainer.py
│   └── wake_sleep_trainer.py
│
├── utils             
│   └── gumbel.py
│   └── modified.py
│
├── vocab
│   └── imdb
│       └── imdb_vocab.py
```
