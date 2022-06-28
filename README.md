# 沿河课堂任意视频播放油猴脚本

## 介绍

允许播放不属于你课程列表的课程，让卷王可以任意听北理的其他课程的录播

## 原理

Hook请求`https://cbiz.yanhekt.cn/v1/auth/permission`，修改返回值

## 引用

[wendux/ajax-hook](https://github.com/wendux/ajax-hook)