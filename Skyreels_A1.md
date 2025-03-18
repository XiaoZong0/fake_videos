# Skyreels_A1
## 驱动方式
video驱动image
## 环境部署
autodl3090
## 批量生成
1.在batch_inference_video.py中修改以下参数

image_dir = "/root/autodl-tmp/skyreels_image"

driving_dir = "/root/autodl-tmp/skyreels_driving_video"

output_dir = "/root/autodl-tmp/skyreels_output"

2.python batch_inference_video.py

3.将生成的视频写脚本转移到一个文件夹中（尚未完成）
