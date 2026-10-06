# 双向 DC-DC 电源开发

个人自学项目，记录双向 DC-DC 电源从需求分析、方案选择到硬件、固件、仿真和测试的开发过程。

当前阶段：项目框架已建立，电气指标和技术方案待确定。尚无可运行固件、完整电路设计或实测结果。

## 开发目标

- 梳理两端口间双向能量传输的需求与工作模式。
- 完成拓扑比较、器件选型、原理图与 PCB 设计。
- 实现采样、PWM、控制算法、状态管理与保护逻辑。
- 通过仿真和实验记录验证设计，并保存学习笔记。

## 目录

| 路径 | 内容 |
| --- | --- |
| [docs/requirements.md](docs/requirements.md) | 电气指标与需求 |
| [docs/roadmap.md](docs/roadmap.md) | 开发阶段与检查项 |
| [docs/learning-log.md](docs/learning-log.md) | 学习和开发记录 |
| [hardware/](hardware/) | 原理图、PCB、BOM |
| [firmware/](firmware/) | 控制器固件与构建说明 |
| [simulation/](simulation/) | 功率级与控制环路仿真 |
| [tests/](tests/) | 测试计划与记录 |

## 开始使用

1. 填写 `docs/requirements.md`，确定两端口电压、功率和隔离需求。
2. 按 `docs/roadmap.md` 推进方案比较和设计。
3. 把已有文件放入对应目录，在该目录的 README 中补充工具版本、打开或构建方式。
4. 在 `docs/learning-log.md` 中记录结论、问题和依据。

## 项目状态与许可

所有待定参数均使用“待定”标记，计划项不代表已完成功能。暂未指定开源许可证；公开仓库本身不授予使用或分发许可。
