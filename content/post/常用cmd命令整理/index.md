---
title: "常用cmd命令整理"
description: 
#完稿日期，格式如下
date: 2022-11-15
license: CC-BY-NC-SA
draft: false
tags:
    - 计维黎德成
categories:
    - 软件
---

## cmd启动方式
- `win`+`r`  打开运行
- 输入 `cmd ` 后 `ctrl`+`shift`+`enter` 以**管理员身份**运行

## 修机常用命令
- `ping` **检查网络连通性**
- `manage-bde` **Bitlocker管理**  
> `manage-bde -status` *查看加密状态*  
> `manage-bde -protectors C: -get` *查看C盘密钥*  
> `manage-bde -off C:` *解密并关闭C盘**Bitlocker***

- `regedit` **打开注册表编辑器**
- `devmgmt.msc` **打开设备管理器**
- `diskmgmt` **打开硬盘管理工具**
- `msconfig` **打开系统配置**  
- `ipconfig` **查看本地网络设置**  
> `ipconfig /renew` *请求新的IP地址*  
> `ipconfig /flushdns` *刷新DNS缓存*
- `osk` **打开屏幕软键盘**
- `shutdown -s` **关机**

## 修机高级命令
- `sfc /SCANNOW` **扫描系统文件完整性并修复**
- `systeminfo` **查看计算机详细信息**
- `nslookup 网址` **解析网址IP地址，用来检查本地DNS设置**
- `dxdiag` **DX检测工具**
- `chkdsk 盘符: /F` **修复磁盘错误,可用于尝试修复U盘**