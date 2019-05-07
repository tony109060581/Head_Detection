# Head_Detection
Just Head Detection
# Test steps
## step1
Download model and put it to "model/"  [BaiDu CLoud](https://pan.baidu.com/s/1RbegT4LnyOdy7ZjP-UtxnA) [cnf2]
## step2
Download opencv_dll and put it to current directory [BaiDu Cloud](https://pan.baidu.com/s/143Ia9lH9BXNiv-hSPSu4Bw)
## step3
Set parameters:
`HeadDet.exe img_path thresh(0-1)`
```cpp
like:    HeadDet.exe images/ 0.24  (for imgdir)
```
# Algorithm efficiency
| Image Size | Speed | CPU |
|:------:|:------:|:------:|
| Any resolution image  | 600ms | i7-8750H @2.20GHz |

# Example result
![image](https://github.com/samylee/Head_Detection/blob/master/results/1.jpg)
![image](https://github.com/samylee/Head_Detection/blob/master/results/3.jpg)
![image](https://github.com/samylee/Head_Detection/blob/master/results/5.jpg)
![image](https://github.com/samylee/Head_Detection/blob/master/results/7.jpg)
![image](https://github.com/samylee/Head_Detection/blob/master/results/9.jpg)
# Reference
https://blog.csdn.net/samylee
