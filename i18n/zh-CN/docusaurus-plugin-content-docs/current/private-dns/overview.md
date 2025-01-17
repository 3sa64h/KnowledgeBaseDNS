---
title: 概览
sidebar_position: 1
---

:::info

With AdGuard DNS, you can set up your private DNS servers to resolve DNS requests and block ads, trackers, and malicious domains before they reach your device

快捷链接： [试用 AdGuard DNS](https://adguard-dns.io/dashboard/)

:::

# 私人 AdGuard DNS

![Private AdGuard DNS dashboard main](https://cdn.adtidy.org/public/Adguard/Blog/private_adguard_dns/main.png)

## 什么是私人 AdGuard DNS?

Private AdGuard DNS is a DNS server that, in addition to benefits of a public DNS server (such as traffic encryption and domain blocklists), provides features like flexible customization, DNS statistics and parental control and is easily managed through a handy dashboard.

## Why you need Private AdGuard DNS

Today, you can connect anything to the Internet: TVs, refrigerators, smart bulbs, or speakers. But along with the undeniable conveniences you get trackers and ads. A simple browser-based ad blocker will not protect you in this case, but AdGuard DNS, which you can set up to filter traffic, block content and trackers, has a system-wide effect.

We already have [public AdGuard DNS](../public-dns/overview.md) and [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome). These solutions work fine for some users, but for others, the public AdGuard DNS lacks the flexibility of configuration, while the AdGuard Home lacks simplicity. That's where private AdGuard DNS comes into play. It has the best of both worlds: it offers customizability, control and information - all through a simple easy-to-use dashboard.

## 私人和公共 AdGuard DNS的区别

Here is a simple comparison of features available in Public AdGuard DNS and Private AdGuard DNS servers.

| 公共 AdGuard DNS | 私人 AdGuard DNS                    |
| -------------- | --------------------------------- |
| DNS流量加密        | DNS流量加密                           |
| 自带的域名封锁清单      | 可自定义的域名封锁清单                       |
| -              | 可以 导入/导出 自定义 DNS 过滤规则             |
| -              | 请求统计（看看您的 DNS 请求到哪里去：哪些国家，哪些公司等等） |
| -              | 详细的查询日志                           |
| -              | 家长控制                              |

## 如何配置私人 AdGuard DNS

1. 前往 [AdGuard DNS 仪表盘](https://adguard-dns.io/dashboard/)（如果没有登录，请使用您的 AdGuard 账号登录）
2. 单击“连接设备”并按照屏幕上的说明进行操作。

> Supported platforms: - Android - iOS - Windows - Mac - Linux - Routers - Gaming consoles

## 私人 AdGuard DNS的特点

### 封锁清单管理

With "Blocklists" feature you can set which domains you want to block and which you don't. Сhoose from wide variety of blocklists for different purposes.

![Private AdGuard DNS dashboard blocklists](https://cdn.adtidy.org/public/Adguard/Blog/private_adguard_dns/blocklists.png)

### 用户规则

For times when pre-installed *Blocklists* with thousands of rules are not enough, we have a handy function called "User rules". Here you can add custom rules manually to block/unblock a certain domain or import custom rules lists (check out [DNS filtering rules syntax](../general/dns-filtering-syntax.md)). You can export the lists.

![Private AdGuard DNS dashboard user rules](https://cdn.adtidy.org/public/Adguard/Blog/private_adguard_dns/import.png)

### 统计

In "Statistics" tab you can see all the summarized statistics on DNS queries made by devices connected to your Private AdGuard  DNS. It shows the total number and geography of requests, the number of blocked requests, the list of companies the requests were addressed to, requests types and top requested domains.

![Private AdGuard DNS dashboard statistics](https://cdn.adtidy.org/public/Adguard/Blog/private_adguard_dns/statistics.png)

### 流量终点

This feature shows you where DNS requests sent by your devices go. On top of seeing the map of request destinations, you can filter the information by date, device and country.

![Private AdGuard DNS dashboard traffic](https://cdn.adtidy.org/public/Adguard/Blog/private_adguard_dns/traffic_destination.png)

### 公司

This tab allows you to quickly check which companies send the most requests, and which companies have the most blocked requests.

![Private AdGuard DNS dashboard companies](https://cdn.adtidy.org/public/Adguard/Blog/private_adguard_dns/companies.png)

### 查询日志

This is a detailed log where you can check out the information on every single request and also sort requests by status, type, company, device, time, country.

![Private AdGuard DNS dashboard query log](https://cdn.adtidy.org/public/Adguard/Blog/private_adguard_dns/query_log.png)

### 家长控制

To protect your child from online content you deem inappropriate, set up and activate the *Parental control* option. In addition to options such as "adult content" blocking and safe search, we've added the ability to manually specify domains for blocking and set a schedule for the *Parental control* to work accordingly.

![Private AdGuard DNS dashboard Parental Control](https://cdn.adtidy.org/public/Adguard/Blog/private_adguard_dns/parental_control.png)

> 如果您还没有私人 AdGuard DNS，您可以在[官网](https://adguard-dns.io/)上获得它。
