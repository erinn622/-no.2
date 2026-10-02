# Canvas Studio — Final Prototype

一个面向图片拼贴、自由绘画和视觉创作的纯前端 Web 编辑器。

## 已实现

- 自定义画布尺寸与比例
- 多图片导入
- 独立图层系统
- 图层显示/隐藏、上下移动、删除
- 图层透明度
- 图片拖动
- 图片四角缩放
- Shift 等比缩放
- 图片旋转手柄
- X/Y/宽/高/旋转精确变换
- 铅笔、钢笔、水彩、马克笔、蜡笔、橡皮
- 吸管取色
- 平滑自由路径
- 画笔大小、透明度、平滑度
- 羊皮纸、水彩纸、宣纸、素描纸纹理
- 50 步撤销/重做历史
- 画布缩放和平移
- PNG / SVG 导出
- `.cstudio` 项目文件导出
- 键盘快捷键
- 响应式基础布局

## 使用

直接打开 `index.html` 即可。

## GitHub Pages

1. 新建 GitHub Repository
2. 上传 `index.html` 与 `README.md`
3. Settings → Pages
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main` / root
6. 保存后等待 GitHub Pages 部署

## 产品化下一阶段

如果继续开发，建议拆分为 React + TypeScript + Vite，并将 Canvas 渲染、图层状态、历史记录、导出模块分离。进一步加入 IndexedDB 自动保存、PWA、Apple Pencil Pointer Events 压感、Bezier 路径、选区/蒙版、混合模式、滤镜、智能拼图布局和云端项目同步。
