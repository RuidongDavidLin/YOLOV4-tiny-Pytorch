# 记录我自己图像识别的学习过程（计划使用pytorch和yolo，yolo的版本未定）

## Pytorch
安装指令，注意自己设备的Python的版本，在下面网址中有不同Python版本的文件，cp39表示是Python3.9.X版本的（目前还没有支持Python3.10版本的）
> pip install torch==1.9.0+cpu torchvision==0.10.0+cpu torchaudio==0.9.0 -f https://download.pytorch.org/whl/torch_stable.html

还有就是注意pip的版本，我之前使用22.X版本的pip时，出现了一些问题，还是不建议更新至最新版本
 
 在安装的过程中，可能会遇到网络问题下面为终端走代理的指令（Windows Power Shell）,我用的是SSR，端口号为1080，这个看自己的电脑设置
 >  $env:HTTP_PROXY="https://127.0.0.1:1080"
 >  $env:HTTP_PROXY="http://127.0.0.1:1080"
 
 可以使用以下指令来查看自己的安装的依赖的版本
> pip list
