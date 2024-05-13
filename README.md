# CMA-ES-SIM
Covariance matrix Adaptation Evolution Strategy (CMA-ES)

A more detailed README will be added soon.

The algorithm is base on [CMA-ES paper](https://arxiv.org/pdf/1604.00772) (long version) by Nikolaus Hansen. 

To test the program, execute either `python test_SL.py CMA-ES` or `python test_RL.py CMA-ES` from within the test folder. Additional options are available in the test_SL.py and test_RL.py files, as well as within the configuration files located in the config folder.

To facilitate comparisons, an ANN runner built with PyTorch is also available. To use it, uncomment the line start_config_path = "./config/config_ann/SL/" in either test_SL.py or test_RL.py, and comment out the corresponding SNN configuration line start_config_path = "./config/config_snn/SL/"

A more complete version with more algorithms and more examples is also available at: https://github.com/OlivierBelan/Evo-Sim (mainly NeuroEvolution algorithms)