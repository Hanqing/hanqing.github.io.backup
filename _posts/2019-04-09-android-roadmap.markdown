---
layout: post
title:  "Android技术栈"
date:   2019-04-09 16:50:59
author: Hanqing
categories: tech
cover:  "/assets/instacode.png"
---

# Android技术栈

- Android
  - 四大组件
	- Activity启动/启动模式/Fragment设计
	- Service启动/启动方式
	- BroadcastReceiver注册方式/优先级
	- ContentProvider安装过程
  - 进程通信
	- Binder机制
	- AMS/PMS/WMS
	- 进程保活/优先级
  - 线程通信
	- 消息机制：Handler/Message/MessageQueue/ThreadLocal
	- AsyncTask/HandlerThread/IntentService
  - UI
	- View绘制原则/测量原则
	- 事件派发机制
	- [ListView](https://blog.csdn.net/zwjemperor/article/details/52564098)/RecyclerView缓存机制
	- Choreographer/Vsync
  - 深入机制
	- App安装流程
	- App启动流程
	- App打包流程
	- 动态加载机制
	- 资源加载机制
	- SO加载机制 
  - 性能优化
	- 内存泄露、内存优化
	- 启动速度优化
	- 布局优化：过度绘制
	- ANR
	- 性能监控
	- [APK瘦身](https://blog.csdn.net/zwjemperor/article/details/52541264)
  - 容器化
	- 模块化
	- 插件化
	  - 类加载机制/multidex
	  - 四大组件启动过程
	  - InstantRun原理
	- hybrid
	  - ReactNative/Weex
	  - 免安装
  - 热修复
	- hook系
	- ClassLoader系
  - 开源库
	- 网络：Okhttp/Retrofit/Vollery
	- 图片加载：Fresco/Glide/Picasso/ImageLoader
	- 事件总线：EventBus
	- 动画：Lottie
  - 安全
	- 数字签名/加密算法
	- 安全编码
	- 混淆
	- 反编译/加固
  - Android版本新特性
	- [Android N分屏适配](https://blog.csdn.net/zwjemperor/article/details/52337106)
  - 其它
	- JNI原理
	- Dalvik/ART
	- Gradle/Grovvy plugin
	- Git使用
- Java
  - 语言
	- 泛型
	- 注解
	- 动态代理
	- 异常
  - 集合
	- 基础集合：HashMap/ArrayList
	- 并发集合：ConcurrentHashMap
	- Android集合：SparseArray
  - 并发
	- 线程状态/同步机制/死锁
	- volatile/notify/wait
	- 线程池
  - 虚拟机
	- 内存区域/分配机制
	- 类加载
	- 垃圾回收机制
- 计算机基础
  - 网络基础
	- TCP/IP：握手/挥手/拥塞控制/流量控制
	- HTTP：请求/响应/缓存
	- HTTPS原理
	- WebSocket
  - 操作系统
	- 进程与线程
	- 内存分配
  - 数据库
	- 关系型/非关系型
	- 事务
	- 索引
	- 升级/降级
  - 算法
	- 数据结构：链表/二叉树/红黑树
	- 思想：动态规划/分治/回溯/贪心
	- 排序/查找
- 设计模式
  - 设计原则
  - 常用设计模式：单例/观察者等
  - 源码中的设计模式 
	- JDK
	- Android
  - 架构模式：MVC/MVP/MVVM

