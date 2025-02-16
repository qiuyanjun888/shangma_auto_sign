## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Mon Dec 30 01:21:21 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 01:18:41 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 01:25:19 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 01:18:27 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 01:19:19 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 01:17:45 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 01:25:06 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 01:22:38 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 01:19:54 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 01:19:26 UTC 2025
- Auto Sign-in run successful on Thu Jan  9 01:18:57 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 01:21:21 UTC 2025
- Auto Sign-in run successful on Sat Jan 11 01:19:40 UTC 2025
- Auto Sign-in run successful on Sun Jan 12 01:26:18 UTC 2025
- Auto Sign-in run successful on Mon Jan 13 01:23:16 UTC 2025
- Auto Sign-in run successful on Tue Jan 14 01:16:01 UTC 2025
- Auto Sign-in run successful on Wed Jan 15 01:17:42 UTC 2025
- Auto Sign-in run successful on Thu Jan 16 01:17:08 UTC 2025
- Auto Sign-in run successful on Fri Jan 17 01:16:41 UTC 2025
- Auto Sign-in run successful on Sat Jan 18 01:14:54 UTC 2025
- Auto Sign-in run successful on Sun Jan 19 01:22:34 UTC 2025
- Auto Sign-in run successful on Mon Jan 20 01:18:22 UTC 2025
- Auto Sign-in run successful on Tue Jan 21 01:16:52 UTC 2025
- Auto Sign-in run successful on Wed Jan 22 01:18:47 UTC 2025
- Auto Sign-in run successful on Thu Jan 23 01:17:13 UTC 2025
- Auto Sign-in run successful on Fri Jan 24 01:17:25 UTC 2025
- Auto Sign-in run successful on Sat Jan 25 01:13:36 UTC 2025
- Auto Sign-in run successful on Sun Jan 26 01:19:40 UTC 2025
- Auto Sign-in run successful on Mon Jan 27 01:18:35 UTC 2025
- Auto Sign-in run successful on Tue Jan 28 01:17:08 UTC 2025
- Auto Sign-in run successful on Wed Jan 29 01:16:58 UTC 2025
- Auto Sign-in run successful on Thu Jan 30 01:16:13 UTC 2025
- Auto Sign-in run successful on Fri Jan 31 01:17:32 UTC 2025
- Auto Sign-in run successful on Sat Feb  1 01:21:30 UTC 2025
- Auto Sign-in run successful on Sun Feb  2 01:21:07 UTC 2025
- Auto Sign-in run successful on Mon Feb  3 01:18:18 UTC 2025
- Auto Sign-in run successful on Tue Feb  4 01:17:29 UTC 2025
- Auto Sign-in run successful on Wed Feb  5 01:18:38 UTC 2025
- Auto Sign-in run successful on Thu Feb  6 01:18:50 UTC 2025
- Auto Sign-in run successful on Fri Feb  7 01:18:42 UTC 2025
- Auto Sign-in run successful on Sat Feb  8 01:16:28 UTC 2025
- Auto Sign-in run successful on Sun Feb  9 01:22:18 UTC 2025
- Auto Sign-in run successful on Mon Feb 10 01:19:46 UTC 2025
- Auto Sign-in run successful on Tue Feb 11 01:18:17 UTC 2025
- Auto Sign-in run successful on Wed Feb 12 01:18:36 UTC 2025
- Auto Sign-in run successful on Thu Feb 13 01:19:08 UTC 2025
- Auto Sign-in run successful on Fri Feb 14 01:18:48 UTC 2025
- Auto Sign-in run successful on Sat Feb 15 01:17:59 UTC 2025
- Auto Sign-in run successful on Sun Feb 16 01:24:52 UTC 2025
