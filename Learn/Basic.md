<link rel=stylesheet href=style.css>

# Blender 基础操作笔记
## 1 官方文档与学习资料
### 1.1 常用链接
#### 官网链接
- [blender 官网](https://www.blender.org/)
- [blender 官方学习文档](https://docs.blender.org/manual/en/latest/)
- [Octance-Blender 免费版](https://home.otoy.com/render/octane-render/demo/#prime)
#### 民间学习资料
- [只剩一瓶辣椒酱-基础建模教程](https://www.bilibili.com/video/BV1zh411Y7LX)
- [只剩一瓶辣椒酱-Octance基础渲染教程](https://www.bilibili.com/video/BV1sV411o7wx)
- [只剩一瓶辣椒酱-Octance百科全书](https://shimo.im/docs/RTRDrkH6DCRXWtd9/read)

### 1.2 常用插件
#### 辅助插件
- [M3 工具](https://www.bilibili.com/video/BV1tb411m7sS)
- [BIT 翻译插件](https://www.150010.xyz/blt)
- [万物有灵STUDIO](https://shimo.im/docs/qjXWwYkGKccgXVgd/read)


## 2 常用快捷键
### 2.0 说明
#### 撰写说明
- 本章所涉及的使用频率为个人使用频率，若原生快捷键与 M3 插件有冲突则不纳入
- 由于 Blender 快捷键极其重要，不常用会忘，故记录了常用快捷键
### 2.1 原生快捷键
> [参考：知乎-演奇](https://zhuanlan.zhihu.com/p/126650481)  
#### 对象操作
- 物体相关操作
  | 快捷键   | 使用频率 | 操作         | 备注                       |
  | -------- | -------- | ------------ | -------------------------- |
  | A        | ★★★      | 全选物体     |                            |
  | B        | ★★★      | 进入框选模式 |                            |
  | W        | ★★       | 切换选择模式 | 对象选择，框选，点选，套选 |
  | Ctrl + I | ★★       | 反选         |                            |
  | X        | ★★★★★    | 删除         | Delete 效果相同            |
  | N        | ★★★      | 属性栏       |                            |
- 控制物体坐标
  | 快捷键 | 使用频率 | 操作       | 备注                    |
  | ------ | -------- | ---------- | ----------------------- |
  | T      | ★★★      | 调出工具栏 |                         |
  | N      | ★★★      | 调出属性栏 |                         |
  | G      | ★★★★★    | 对象移动   | 二次按 X/Y/Z 可固定轴向 |
  | R      | ★★★★★    | 对象旋转   | 二次按 X/Y/Z 可固定轴向 |
  | S      | ★★★★★    | 对象缩放   | 二次按 X/Y/Z 可固定轴向 |
  - 三种变换结束后按鼠标`左键`确定，`右键`取消，可`在键盘上输入数字`进行具体的变换
  - 按住`鼠标中键`可切换轴向
  - `Shift+X/Y/Z`:去除某个轴向
- 切换坐标中心
  | 快捷键 | 使用频率 | 操作                   | 备注 |
  | ------ | -------- | ---------------------- | ---- |
  | <      | ★★★★     | **面板**：方向与坐标系 |      |
  | >      | ★★★★     | **面板**：枢轴点控制   |      |

#### 视角转换
- 摄像机视角
  | 快捷键            | 使用频率 | 操作                 | 备注               |
  | ----------------- | -------- | -------------------- | ------------------ |
  | 0 (小键盘)        | ★★★★     | 切换到摄像机视角     |                    |
  | Ctrl + 0 (小键盘) | ★★★      | 设置摄像机为活动相机 |                    |
  | Shift + ~         | ★★       | 摄像机进入移动模式   |                    |
  | Q                 | ★★       | 相机上升             | 相机需进入移动模式 |
  | E                 | ★★       | 相机下降             | 相机需进入移动模式 |
  | W/A/S/D           | ★★       | 移动                 | 相机需进入移动模式 |
  | 滚轮              | ★★       | 相机移动速度         | 相机需进入移动模式 |

- 视角快捷键
  | 快捷键                  | 使用频率 | 操作               | 备注 |
  | ----------------------- | -------- | ------------------ | ---- |
  | . (小键盘)              | ★★       | 居中物体           |      |
  | 5 (小键盘)              | ★★       | 正交视图           |      |
  | 2/4/6/8 (小键盘)        | ★★       | 视角小幅度旋转     |      |
  | Ctrl + 2/4/6/8 (小键盘) | ★★       | 视角小幅度平移     |      |
  | 1/3/7/9 (小键盘)        | ★★★      | 切换到平行视角     |      |
  | Ctrl + 1/3/7/9 (小键盘) | ★★★      | 切换到平行视角     |      |
  | 鼠标中键                | ★★★★★    | 视角旋转           |      |
  | Shift + 鼠标中键        | ★★★★★    | 视角平移           |      |
  | Alt + 鼠标中键          | ★★       | 平行视角平移       |      |
  | ~                       | ★★       | **面板**：视角选择 |      |

- 窗口控制
  | 快捷键           | 使用频率 | 操作       | 备注                               |
  | ---------------- | -------- | ---------- | ---------------------------------- |
  |                  | ★★       | 分屏       | 鼠标放在两个界面分界上方，点击移动 |
  | Ctrl + Alt + Q   | ★★★★     | 切换四视图 |                                    |
  | Ctrl + Space     | ★★       | 窗口最大化 |                                    |
  | Shift + F5/S6... | ★        | 切换工作区 |

#### 节点快捷键
- 基础控制
  | 快捷键   | 使用频率 | 操作       | 备注 |
  | -------- | -------- | ---------- | ---- |
  | Ctrl + G | ★★★      | 打包节点   |      |
  | Tab      | ★★★      | 进入节点组 |      |

#### 渲染与 IO 操作
- 渲染控制
  | 快捷键  | 使用频率 | 操作                   | 备注             |
  | ------- | -------- | ---------------------- | ---------------- |
  | F12     | ★★★★★    | 对当前相机视角进行渲染 | 不能在渲染模式下 |
  | Alt + S | ★★★★★    | 保存当前渲染图像       |                  |

#### 时间轴
- 

### 2.2 M3 工具(面板)
#### M3 工具面板
- 面板快捷键
  | 快捷键    | 使用频率 | 面板         | 备注 |
  | --------- | -------- | ------------ | ---- |
  | <         | ★★★★     | 方向与坐标系 |      |
  | >         | ★★★★     | 枢轴点控制   |      |
  | ~         | ★★       | 视角选择     |      |
  | Ctrl + S  | ★★★★     | I/O 处理     |      |
  | Shift + S | ★★★      | 游标和原点   |      |
  | PGUP      | ★★★      | 配色与覆盖   |
  | PGON      | ★★★      | 相机和视角   |
- 子栏快捷键
  | 快捷键     | 使用频率 | 子栏     | 备注 |
  | ---------- | -------- | -------- | ---- |
  | Shift  + A | ★★★★★    | 新增物体 |      |
  