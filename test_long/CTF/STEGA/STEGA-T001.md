# STEGA-T001

---

kali系统工具:

| 工具名           | 命令                                               | 备注                        |
| ---------------- | -------------------------------------------------- | --------------------------- |
| binwalk          | binwalk [目标图片]                                 | 分析文件内的包含的文件类型  |
| foremost         | foremost -t 提取文件后缀 -i [目标图片] -o 输出路径 | 分离出各种文件类型          |
| F5-steganography | java Extract [目标图片绝对路径] -p 123456          | 检测F5算法隐写              |
| outguess         | outguess -r [目标图片绝对路径] [信息存放的文本]]   | (需要安装)检测guess算法隐写 |



windows系统工具:

| 工具名        | 使用                                             | 功能               |
| ------------- | ------------------------------------------------ | ------------------ |
| Stegsolve.jar | 分析data Extract的red blue green,看是否为LSB隐写 | LSB隐写,三原色分析 |
| audacity      | 查看音带,摩斯电码转换                            | 音频隐写           |
|               |                                                  |                    |
