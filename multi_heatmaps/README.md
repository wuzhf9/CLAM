将图片放在./multi_heatmaps/slides文件夹下
修改./multi_heatmaps/heatmap_demo_dataset.csv文件，该文件包含./multi_heatmaps/slides文件夹下每张slide的id以及label
其余配置信息在./multi_heatmaps/config_template.yaml文件下
运行代码CUDA_VISIBLE_DEVICES=0,1 python create_multi_heatmaps.py --config_file config_template.yaml
