# BentoBox

## 关于 BentoBox

### 简介

Bentobox 是许多岛屿游戏的前置插件，比如 AcidIsland 和 BSkyBlock。它可提供像岛屿创建、团队管理、岛屿保护等的功能。当然这些游戏和功能需要附属插件来支撑。管理员可以自定义他们需要的功能。

## 扩展
Bentobox 目前提供以下游戏模式：
* [**AcidIsland**](https://github.com/BentoBoxWorld/AcidIsland): 你被困在一个被酸水包围的小岛上!
* [**AOneBlock**](https://github.com/BentoBoxWorld/AOneBlock): 你脚下有且只有一块魔力方块.
* [**Boxed**](https://github.com/BentoBoxWorld/Boxed): 你被包围在一个狭小的空间内，你想要自由，所以你需要完成任务.
* [**BSkyBlock**](https://github.com/BentoBoxWorld/BSkyBlock): ASkyBlock 的续作.
* [**CaveBlock**](https://github.com/BentoBoxWorld/CaveBlock): 地下世界!
* [**SkyGrid**](https://github.com/BentoBoxWorld/SkyGrid): 由空气方块分隔的无数方块组成的世界 - 冒险开始!

官方扩展列表：
* [**见此贴**](https://www.mcbbs.net/thread-846318-1-1.html)

还有一些官方/第三方扩展未列出!

## 文档

* 见此贴: [https://www.mcbbs.net/thread-1009602-1-1.html](https://www.mcbbs.net/thread-1009602-1-1.html)
* 开发人员文档: [Javadocs](https://bentoboxworld.github.io/BentoBox/)

## 下载

### Webtool
A [webtool](https://download.bentobox.world/) 可以帮助你建立起你的服务器.

### 直链
* [进入下载页面（汉化版）](https://github.com/BentoBoxChina/BentoBox/releases)

### 开发人员工具
* [Jenkins](https://ci.codemc.org/job/BentoBoxWorld/job/BentoBox/) (**未经测试且可能不稳定的版本**)
* [Javadocs](https://bentoboxworld.github.io/BentoBox/)

### 汉化版有bug？
请在 [issue tracker](https://github.com/BentoBoxChina/BentoBox/issues) 上反馈.

## API

BentoBox uses Maven, and its Maven repository is kindly provided by [CodeMC](https://codemc.org).

### Maven
```xml
<repositories>
  <repository>
    <id>codemc-repo</id>
    <url>https://repo.codemc.org/repository/maven-public/</url>
  </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>world.bentobox</groupId>
    <artifactId>bentobox</artifactId>
    <version>PUT-VERSION-HERE</version>
    <scope>provided</scope>
  </dependency>
</dependencies>
```

### Gradle
```groovy
repositories {
  maven { url "https://repo.codemc.org/repository/maven-public/" }
}

dependencies {
  compileOnly 'world.bentobox:bentobox:PUT-VERSION-HERE'
}
```
