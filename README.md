# 本仓库为Hands-On Red Team Tactics中文翻译

## 前言
红队用于通过对组织执行模拟攻击来增强安全性，以便检测网络和系统漏洞。本书首先概述了测试和红色团队，然后介绍了一些最新的测试工具。然后，您将继续探索Metasploit并掌握Armitage。一旦你学习了基础知识，你就会了解Cobalt Strike的基本知识，用法以及如何设置Cobalt Strike的团队服务器。在使用Cobalt Strike进行攻击之前，您将学习一些常见的代理技术以及如何通过SSH进行代理。本指南演示了使用Cobalt Strike进行后期利用的高级方法，并向您介绍了命令和控制服务器（C2）和重定向器。所有这些都将帮助您使用Beacons和Data Exfiltration实现持久性，并且还使您有机会在Active Directory和域控制器上的红队活动期间运行该方法以使用像Empire这样的红队工具。

在本书的最后，您将学习高级渗透测试工具，通过加密通道获取反向shell的技术以及用于后期利用的过程。除此之外，您还将探索Empire等框架，包括维护持久访问，保持无法追踪，以及通过不同的C2隐蔽通道获得反向连接。

## 这本书的受众
如果您是IT专业人士、测试人员、安全顾问或对IT安全领域感兴趣的道德黑客，并希望在渗透测试中有所突破，那么这本书就适合您。如果有渗透测试的基本知识那更好。

## 这本书涵盖了什么
Chapter 1, 红队和渗透测试，帮助您了解整个行业中不同的测试标准，我们将详细介绍PTES标准的七个阶段。

Chapter 2, Pentesting 2018, introduces you to MSF Payload Creator (MSFPC). 我们还将研究除了有效负载文件之外由MSFPC生成的资源文件的使用。

Chapter 3, 前戏 – Metasploit基础，向您介绍团队服务器和Armitage客户端，包括Armitage的设置和使用。

Chapter 4, Cobalt Strike入门，首先探讨红队演练以及可用于攻击计划的网络杀伤链概念。然后本章向您介绍Cobalt Strike，这是一个用于红队运作的工具。

Chapter 5, 反弹shell，探讨了使用各种工具的反向连接和反向shell连接。此外，我们将使用Metasploit尝试不同的有效负载以获得反向shell连接。

Chapter 6, 跳板，深入了解端口转发及其用途。我们还将了解跳板及其用途，然后介绍通过SSH进行端口转发的方法。

Chapter 7, Empire时代 - 开始，向您介绍Empire及其基本原理。我们还将介绍Empire的基本用法以及Windows，Linux和OSX的后期开发基础知识。

Chapter 8, Empire时代 - 拥有域控，深入研究Empire的一些更高级用法，以获得对域控的访问权限。

Chapter 9, Cobalt Strike - 红队运营，向您介绍Cobalt Strike的监听模块及其类型和用法。

Chapter 10, C2 - 木偶大师，介绍了命令和控制（C2）服务器，并讨论了如何在红队中操作和使用它们。

Chapter 11, 混淆C2s - 引入重定向器，向您介绍重定向器以及为什么需要混淆C2的原因。我们还介绍了如何以安全的方式对C2进行模糊处理，以便我们可以保护我们的C2免受蓝队检测。

Chapter 12, 实现持久性控制，使用Armitage内置的漏洞利用模块，我们将学习如何通过Empire在Windows，Linux和macOS机器上实现同样的功能。

Chapter 13, 数据传输，讨论了使用Netcat，OpenSSL和PowerShell等简单工具传输数据的一些基本方法。接下来，我们跳转到使用基于文本的隐写术转换数据以避免检测，以及查看CloakifyFactory工具的用法。
