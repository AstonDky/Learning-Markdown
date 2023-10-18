# 第8章 图像的阈值处理
 ##  8.1 图像像素值单一化 threshold()  方法
  ### 语法：retval, dst = cv2.threshold (src,thresh, maxval, type)
        1.retval ： 处理时采用的阈值
        2.dst ： 经过阈值处理后的图像
        3.src ： 被处理的图像
        4.thresh ： 阈值 125-150 最佳
        5.maxval ：阈值处理采用的最大值
        6.type  ： 阈值处理类型
            { cv2.THRESH_
                1.BINATY  二值化
                2.BINARY_INV 反二值化
                3.TOZERO 低于阈值零处理
                4.TOZERO_INV 超出阈值零处理
                5.TRUNC    截断阈值处理  }

                               


