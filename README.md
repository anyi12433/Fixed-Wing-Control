# Fixed-Wing Control: De Havilland Beaver Simulink Project

## 项目概述
本项目基于 **Matlab Simulink** 平台的开源模型 `Fly the de Havilland Beaver`，实现了固定翼飞机的飞行控制系统设计。核心工作包括：

- ✈️ **纵向控制器**（速度/高度）设计与参数整定  
- ✈️ **横向控制器**（滚转/航向）设计与参数整定  
- 🌐 集成 **FlightGear 飞行可视化系统**  
- 📝 对原始模型的针对性修改与功能扩展

---

## 使用说明

### 基本操作流程
1. **硬件准备**  
   `Pilot Joystick`模块可能需要接入手柄编译，否则会报错

2. **数据加载**  
   在Matlab左侧工作区双击加载：
   - `matlab.mat`
   - `aero.mat` 

3. **可视化启动**  
   在资源管理器中双击运行 `runfg.bat` 启动FlightGear可视化窗口

4. **开始仿真**  
   打开SLX文件后点击 **播放键** 启动仿真

> ⚠️ 注意：必须按上述顺序执行操作

---

## 环境依赖
| 组件 | 最低版本要求 |
|------|--------------|
| MATLAB | R2023b+ |
| Simulink + Aerospace Blockset | 必需 |
| FlightGear | 2020.3+ |
| Control System Toolbox | 必需 |

---

## 文档说明
完整修改记录详见项目文档：  
📄 **使用说明.docx**（包含详细参数配置与故障排除指南）
