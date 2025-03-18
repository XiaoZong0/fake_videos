# Hellomeme
## 驱动方式
video驱动image
## 环境部署
autodl3090
## 批量生成
1.在batch_inference_video.py中修改以下参数

REFERENCE_IMAGE_DIR = "/root/autodl-tmp/reference_image/man_10000_flux.1_512_512_3.5_15_RandomSeed"  # 参考图片目录

DRIVING_VIDEO_DIR = "driving_video"      # 驱动视频目录

OUTPUT_DIR = "/root/autodl-tmp/HelloMeme/output_results_new"            # 输出目录

2.python batch_inference_video.py
