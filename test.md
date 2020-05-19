将学号姓名的水印图片info.png隐藏在图片频率中
原图片是input.png，加了水印的是test.png
使用工具隐藏：
python encode.py --image input.png --watermark info.png --result test.png
提取：
python decode.py --image test.png --orig input.png --result watermark_result.png


