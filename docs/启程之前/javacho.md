---
title: Java的选择和安装
sidebar_position: 1
---

顾名思义,Java版Minecraft需要安装 Java 才能运行。

<details>
  <summary>JRE 和 JDK 是什么? 我该怎么选择?</summary>

JRE(Java Runtime Enviroment) 是 Java 的运行环境。面向 Java 程序的使用者，而不是开发者。如果你仅下载并安装了 JRE，那么你的系统只能运行 Java 程序。JRE 是运行 Java 程序所必须环境的集合，包含 JVM 标准实现及 Java 核心类库。它包括 Java 虚拟机、Java 平台核心类和支持文件。它不包含开发工具(编译器、调试器等)

JDK(Java Development Kit) 又称 J2SDK(Java2 Software Development Kit)，是 Java 开发工具包，它提供了 Java 的开发环境(提供了编译器 javac 等工具，用于将 java 文件编译为 class 文件)和运行环境(提 供了 JVM 和 Runtime 辅助包，用于解析 class 文件使其得到运行)。如果你下载并安装了 JDK，那么你不仅可以开发 Java 程序，也同时拥有了运行 Java 程序的平台。JDK 是整个 Java 的核心，包括了 Java 运行环境(JRE)，一堆 Java 工具 tools.jar 和 Java 标准类库 (rt.jar)

**总结: 需要启动Minecraft用JRE就行**

</details>

### 选择版本

:::warning
部分Mod对Java版本有强制要求,如[ModernUI](https://www.mcmod.cn/class/2454.html)
:::

| Minecraft 版本  | 最低版本    | 推荐版本    |
| ------------- | ------- | ------- |
| 1.0 - 1.11.2  | Java 6  | Java 8  |
| 1.12 - 1.16.4 | Java 8  | Java 11 |
| 1.16.5        | Java 8  | Java 16 |
| 1.17 - 1.17.1 | Java 16 | Java 17 |
| 1.18 - 1.20.4 | Java 17 | Java 21 |
| 1.20.5 - 1.21 | Java 21 | Java 21 |

### 下载

| Java 版本 | 名称            | Windows                                                                                                                                                         |
|:-------:|:-------------:| --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Java 8  | Zulu 8        | [点击下载](https://res.fastmirror.net/directlink/1/Java%20%E7%8E%AF%E5%A2%83/OpenJDK/Azul%20Zulu/zulu8.76.0.17-ca-fx-jdk8.0.402-win_x64.msi)                                                                                                                                                        |
| Java 11 | Dragonwell 11 | [点击下载](https://res.fastmirror.net/directlink/1/Java%20%E7%8E%AF%E5%A2%83/OpenJDK/Alibaba%20Dragonwell/Alibaba_Dragonwell_Extended_11.0.21.18.9_x64_windows.zip) |
| Java 17 | Zulu 17       | [点击下载](https://res.fastmirror.net/directlink/1/Java%20%E7%8E%AF%E5%A2%83/OpenJDK/Azul%20Zulu/zulu17.48.15-ca-fx-jdk17.0.10-win_x64.msi)                         |
| Java 21 | Zulu 21       | [点击下载](https://res.fastmirror.net/directlink/1/Java%20%E7%8E%AF%E5%A2%83/OpenJDK/Azul%20Zulu/zulu21.32.17-ca-fx-jdk21.0.2-win_x64.msi)                          |

:::tip提示

Linux用户请使用包管理器安装

:::



:::danger危险

请不要使用32位Java

:::

