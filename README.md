# duix.ai

## highlights
- 2d数字人推理引擎，可在android/ios等边缘侧设备上一键部署，并且内置了两个形象，可直接使用看到效果。
- 支持二次开发，丰富的sdk接口，用户可根据sdk文档开发自己专属需求。
- 完全开源，底层推理及上层商业化应用逻辑整套流程源码开放。

### 目录结构   
```
duix-android: android demo       
GJLocalDigitalDemo: ios demo  
```     

<p align="center">
  <img src="res/女.png" width=200/>
  <img src="res/男.png" width=200/>
</p>

内置的2个模特，模板和AI模型包可以通过公网地址下载。    
[女 链接地址](https://cdn.guiji.ai/duix/digital/model/1712034391673/bendi1_0329.zip)
[男 链接地址](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1706009711636/liangwei_540s.zip)

### 使用说明 
android参考 [README.md](./duix-android/dh_aigc_android/README.md)    
ios参考 [GJLocalDigitalSDK.md](./GJLocalDigitalDemo/GJLocalDigitalDemo/GJLocalDigitalSDK.md)

### Acknowledgements
-音频特征我们借鉴了 [wenet](https://github.com/wenet-e2e/wenet)  

### 如果有定制需求或技术支持，请在讨论区留言，更多详细信息请访问 [**硅基智能**]官网(https://www.guiji.ai)