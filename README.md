# 3D 俄罗斯方块 (Tetris 3D)

经典 Blockout 风格 3D 方块消除游戏，支持网页版和安卓版。

## 网页版

直接用浏览器打开 `tetris3d.html` 即可游玩。

**操作方式：**
- **移动：** ← → ↑ ↓
- **旋转Y轴：** Q / A
- **旋转X轴：** W / S
- **旋转Z轴：** E / D
- **硬降：** 空格
- **暂停：** P / Esc

## 安卓版

安卓版位于 `android/` 目录，预编译 APK 在 `android/release/tetris3d.apk`。

### 直接安装
下载 `android/release/tetris3d.apk` 传到手机安装即可。

### 从源码编译
1. 用 Android Studio 打开 `android/` 目录
2. Sync Gradle
3. Build → Build APK(s)

**触屏操作：**
- **滑动：** 移动方块
- **点击左侧：** 旋转 X 轴
- **点击中间：** 旋转 Y 轴
- **点击右侧：** 旋转 Z 轴
- **双指滑动：** 水平→旋转Z / 垂直→旋转X
- **底部按钮：** 硬降
- **系统返回键：** 暂停

## 难度模式
- **基础：** 平面方块（经典俄罗斯方块形状）
- **中级：** +凸起方块（5格立体形状）
- **困难：** 全3D形状（完全立体多连块）

## 技术栈
- Three.js (r128) — 3D 渲染
- Android WebView — 安卓端封装
