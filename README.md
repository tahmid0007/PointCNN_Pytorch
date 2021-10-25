# PointCNN_Pytorch 
### This repo has (**adali PCNN train (2ways) + visualise inference (whole rooms not normed blocks))
### Environment:
Run the yml file inside conda to create a separate environment with all dependencies. The command itself can also be found inside the yml.
### Run: what is what
run.py is the main file.
v1.zip/v2.zip are the latest version of the base repo with same file structure with updated scripts
Generic name in this sereis: ###v(N).zip
## v1_txt_ dataloader.zip
load data directly from txt bypassing the h5,npy intermediary.
Generic name in this sereis: ###v(N)_txt_ dataloader.zip
## v2_visualize.zip
get whole room predictions and unnormalized visualisatoin not per block normed squashed visuals. run_visualize3D.py inside is the main script to run. However, data_class_unnormalized.py is the script that has all the core functinos to read only the unique blocks inside a room in a non overlapping way.
When using txt dataloader directly, the path in the config file should be to the raw Stanford3dDataset_v1.2_Aligned_Version folder with area subfolders, not any txt file with explicit h5 paths as in normal dataloader.
Generic name in this sereis: ###v(N)_visualize.zip
### In lower spec PC, set num_workers = 0 and batch size 1 in config.py
