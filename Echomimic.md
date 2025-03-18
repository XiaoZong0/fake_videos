# Echomimic
## 驱动方式
audio驱动image
## 环境部署
autodl 3090
## 批量生成
1.在infer_audio2vid.py中修改以下参数

image_dir = Path("/root/autodl-tmp/echomimic_image")  # 参考图像位置
audio_path = Path("/root/autodl-tmp/a.wav")   # driving_audio位置

2.python infer_audio2vid.py

3. 生成之后需要写脚本，把生成的视频中我们需要的部分挑选出来（尚未完成）
