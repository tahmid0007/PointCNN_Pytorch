# PointCNN_Pytorch
# run the yml file inside conda to create a separate environment with all dependencies
# In lower spec PC, set num_workers = 0 and batch size 1 in config.py
# txt_ dataloader.zip -> load data bypassing the h5,npy intermediary
# visualize.zip -> get whole room predictions and unnormalized visualisatoin not per block normed squashed visuals
# When using txt dataloader directly, the path in the config file should be to the raw Stanford3dDataset_v1.2_Aligned_Version folder with area subfolders, not any txt file with explicit h5 paths as in normal dataloader
