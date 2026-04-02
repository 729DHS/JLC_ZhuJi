# STM32F407 项目示例

## 项目介绍

本项目旨在使用嘉立创筑基派+STM32F407VET6+VScode+STM32CubeIDE for VScode插件+CubeMX技术栈，提供STM32 HAL库裸机和FreeRTOS实时操作系统的项目示例。

## 目录结构

```text
JLC_ZhuJi/
├── FreeRTOS/                # FreeRTOS 实时操作系统示例
│   ├── F01_Blink_1/         # RTOS 任务：LED 闪烁
│   └── F02_Encoder_PWM_LED_1/ # RTOS 任务：编码器读取与 PWM 控制
└── HAL/                     # HAL 库裸机示例
    ├── H01_Blink_1/         # 裸机：LED 闪烁
    └── H02_PWM_LED_01/      # 裸机：PWM 呼吸灯
```

## 示例说明

### HAL 库裸机示例

- **H01_Blink_1**：基础的 LED 闪烁示例，展示如何使用 HAL 库控制 GPIO。
- **H02_PWM_LED_01**：PWM 呼吸灯示例，展示如何使用 HAL 库配置和控制 PWM。

### FreeRTOS 示例

- **F01_Blink_1**：基于 FreeRTOS 的 LED 闪烁示例，展示如何创建和管理 RTOS 任务。
- **F02_Encoder_PWM_LED_1**：编码器读取与 PWM 控制示例，展示如何在 RTOS 环境下处理输入和输出。

## 环境配置

### 必要工具

1. **VSCode**：代码编辑器
2. **STM32CubeIDE for VScode 插件**：提供 STM32 开发支持
3. **STM32CubeMX**：用于生成初始化代码
4. **ARM GCC 工具链**：用于编译代码
5. **OpenOCD**：用于调试和烧录

### 配置步骤

1. 安装 VSCode
2. 在 VSCode 中安装 STM32CubeIDE 插件
3. 安装 STM32CubeMX
4. 安装 ARM GCC 工具链
5. 安装 OpenOCD

### 参考教程

- [爽！手把手教你用VSCode开发STM32【大人，时代变啦！！！】](https://www.bilibili.com/video/BV1QfbpzGENy/?share_source=copy_web&vd_source=712659704199d1772ad2d034e3e5f4c1)
- [无需配置！STM32 + VS Code最好的开发方式：XRobot 官方教程第0节——STM32 开发环境](https://www.bilibili.com/video/BV1SHnAztE11/?share_source=copy_web&vd_source=712659704199d1772ad2d034e3e5f4c1)

## 使用指南

1. **克隆项目**：将项目克隆到本地
2. **打开示例**：在 VSCode 中打开相应的示例目录
3. **构建项目**：使用 VSCode 中的构建功能编译项目
4. **烧录程序**：使用 OpenOCD 将编译好的程序烧录到开发板
5. **调试程序**：使用 VSCode 的调试功能进行调试

## 硬件说明

- **开发板**：嘉立创筑基派
- **MCU**：STM32F407VET6
- **主要外设**：LED、编码器、PWM 输出

## 文档资源

- [嘉立创天空星筑基板文档](https://wiki.lckfb.com/zh-hans/fdb/)
- [嘉立创天空星STM32F407文档](https://wiki.lckfb.com/zh-hans/tkx/tkx-stm32f407vxt6/beginner/)
- [FreeRTOS 官方文档](https://www.freertos.org/Documentation/RTOS_book.html)

## 贡献

欢迎贡献代码和改进！如果您有任何问题或建议，请通过以下方式联系：

- 邮箱：**guo_114@outlook.com**

## 许可证

本项目采用 MIT 许可证，详见 LICENSE 文件。

---

**作者**：729DHS
**日期**：2026-04-02
**版本**：1.0.0