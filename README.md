# 人脸识别系统

**介绍：** 本系统采用人脸1：1验证，使用者需要事先提供证件照，然后在具有摄像头的设备上采集监控照，进行人脸识别即可。

<img src="./pics/gui.png" width=80% alt="demo" />

---

**特性**：
1. 抓拍功能：监控照可随时重新抓拍，并且进行保存。
2. 指示功能：人脸验证时，有进度条指示，优化使用体验。

---

**开发工具：** 
1. 前台（Qt Designer）
2. 耦合（PyQt5）
3. 后台（insightface）

---

**仓库结构**：
1. app.py：程序启动入口。
2. requirements.txt：环境依赖。
3. pics：存放logo以及抓拍的监控照片。
4. client.ui：Qt Designer打包出的前台静态界面。

---

**未来工作**：
1. 自适应分辨率：开放窗口大小调整。
2. 阈值调整：使用者可根据需求自行界定验证标准。

---

**联系作者**：zzh.mailbox@qq.com
