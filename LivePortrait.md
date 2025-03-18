# LivePortrait
## 驱动方式
video驱动image
## 环境部署
盈都大厦3090
## 批量生成
1.在batch_generate.sh中修改以下参数

SOURCE_DIR="face_generated"          # 源图片目录

DRIVING_DIR="driving_video_2"          # 驱动视频目录

OUTPUT_ROOT="output_videos"          # 输出根目录

2. bash batch_generate.sh
