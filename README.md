# GRACE_GMT_scripts

本项目包括两部分的GRACE绘图脚本，使用语言为GMT6。一个是绘制全球的GRACE TWSA，一个为绘制区域的GRACE TWSA，分别位于global文件夹（global_tws.bat）和study_area文件夹（stydy_area_gws.bat）中。除此之外，study_area还包含另外一个脚本study_area_et.bat可用于绘制研究区域的其它数据，其它示例xyz数据放于`/study_area/GWTrend/`文件夹中。

注意：1）xyz数据是通过`/study_area/GWTrend/GRACE_mat2xyz.m`脚本生成，详细用法和输出数据在该脚本中有具体介绍；2）在global_tws.bat脚本中使用到了GMT6自带的陆地掩膜，只支持721×1440矩阵大小的xyz数据，生成xyz数据的mat数据也必须为721×1440矩阵。

