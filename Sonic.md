# Sonic
## 驱动方式
audio驱动image
## 环境部署
autodl 3090
## 批量生成
1.在batch_generate.sh中修改以下参数

image_dir="/root/autodl-tmp/sonic_image"  # 图片目录

audio_file="/root/autodl-tmp/a.wav"                     # 驱动语音文件

output_dir="/root/autodl-tmp/sonic_output"               # 输出目录

2.bash batch_generate.sh
