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
- Auto Sign-in run successful on Mon Mar 10 01:10:01 UTC 2025
- Auto Sign-in run successful on Tue Mar 11 01:23:03 UTC 2025
- Auto Sign-in run successful on Wed Mar 12 01:21:57 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 01:23:31 UTC 2025
- Auto Sign-in run successful on Fri Mar 14 01:21:54 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 01:21:35 UTC 2025
- Auto Sign-in run successful on Sun Mar 16 01:35:33 UTC 2025
- Auto Sign-in run successful on Mon Mar 17 01:25:17 UTC 2025
- Auto Sign-in run successful on Tue Mar 18 01:23:23 UTC 2025
- Auto Sign-in run successful on Wed Mar 19 01:24:00 UTC 2025
- Auto Sign-in run successful on Thu Mar 20 01:22:47 UTC 2025
- Auto Sign-in run successful on Fri Mar 21 01:24:34 UTC 2025
- Auto Sign-in run successful on Sat Mar 22 01:22:33 UTC 2025
- Auto Sign-in run successful on Sun Mar 23 01:36:23 UTC 2025
- Auto Sign-in run successful on Mon Mar 24 01:26:19 UTC 2025
- Auto Sign-in run successful on Tue Mar 25 01:25:27 UTC 2025
- Auto Sign-in run successful on Wed Mar 26 01:24:31 UTC 2025
- Auto Sign-in run successful on Thu Mar 27 01:24:21 UTC 2025
- Auto Sign-in run successful on Fri Mar 28 01:24:14 UTC 2025
- Auto Sign-in run successful on Sat Mar 29 01:23:42 UTC 2025
- Auto Sign-in run successful on Sun Mar 30 01:38:25 UTC 2025
- Auto Sign-in run successful on Mon Mar 31 01:37:00 UTC 2025
- Auto Sign-in run successful on Tue Apr  1 01:42:46 UTC 2025
- Auto Sign-in run successful on Wed Apr  2 01:26:15 UTC 2025
- Auto Sign-in run successful on Thu Apr  3 01:24:51 UTC 2025
- Auto Sign-in run successful on Fri Apr  4 01:24:43 UTC 2025
- Auto Sign-in run successful on Sat Apr  5 01:23:45 UTC 2025
- Auto Sign-in run successful on Sun Apr  6 01:37:21 UTC 2025
- Auto Sign-in run successful on Mon Apr  7 01:27:32 UTC 2025
- Auto Sign-in run successful on Tue Apr  8 01:25:15 UTC 2025
- Auto Sign-in run successful on Wed Apr  9 01:25:49 UTC 2025
- Auto Sign-in run successful on Thu Apr 10 01:26:35 UTC 2025
- Auto Sign-in run successful on Fri Apr 11 01:26:09 UTC 2025
- Auto Sign-in run successful on Sat Apr 12 01:24:08 UTC 2025
- Auto Sign-in run successful on Sun Apr 13 02:53:16 UTC 2025
- Auto Sign-in run successful on Mon Apr 14 01:37:01 UTC 2025
- Auto Sign-in run successful on Tue Apr 15 01:28:06 UTC 2025
- Auto Sign-in run successful on Wed Apr 16 01:27:34 UTC 2025
- Auto Sign-in run successful on Thu Apr 17 01:26:32 UTC 2025
- Auto Sign-in run successful on Fri Apr 18 01:25:39 UTC 2025
- Auto Sign-in run successful on Sat Apr 19 01:23:24 UTC 2025
- Auto Sign-in run successful on Sun Apr 20 01:39:57 UTC 2025
- Auto Sign-in run successful on Mon Apr 21 01:39:23 UTC 2025
- Auto Sign-in run successful on Tue Apr 22 01:27:07 UTC 2025
- Auto Sign-in run successful on Wed Apr 23 01:27:19 UTC 2025
- Auto Sign-in run successful on Thu Apr 24 01:27:39 UTC 2025
- Auto Sign-in run successful on Fri Apr 25 01:36:28 UTC 2025
- Auto Sign-in run successful on Sat Apr 26 01:25:01 UTC 2025
- Auto Sign-in run successful on Sun Apr 27 01:40:23 UTC 2025
- Auto Sign-in run successful on Mon Apr 28 01:38:51 UTC 2025
- Auto Sign-in run successful on Tue Apr 29 01:36:49 UTC 2025
- Auto Sign-in run successful on Wed Apr 30 01:36:29 UTC 2025
- Auto Sign-in run successful on Thu May  1 01:44:17 UTC 2025
- Auto Sign-in run successful on Fri May  2 01:36:54 UTC 2025
- Auto Sign-in run successful on Sat May  3 01:26:40 UTC 2025
- Auto Sign-in run successful on Sun May  4 01:44:53 UTC 2025
- Auto Sign-in run successful on Mon May  5 01:40:48 UTC 2025
- Auto Sign-in run successful on Tue May  6 01:37:34 UTC 2025
- Auto Sign-in run successful on Wed May  7 01:38:28 UTC 2025
- Auto Sign-in run successful on Thu May  8 01:38:45 UTC 2025
- Auto Sign-in run successful on Fri May  9 01:38:08 UTC 2025
- Auto Sign-in run successful on Sat May 10 01:26:36 UTC 2025
- Auto Sign-in run successful on Sun May 11 01:42:55 UTC 2025
- Auto Sign-in run successful on Mon May 12 01:41:55 UTC 2025
- Auto Sign-in run successful on Tue May 13 01:39:23 UTC 2025
- Auto Sign-in run successful on Wed May 14 01:38:20 UTC 2025
- Auto Sign-in run successful on Thu May 15 01:27:55 UTC 2025
- Auto Sign-in run successful on Fri May 16 01:39:15 UTC 2025
- Auto Sign-in run successful on Sat May 17 01:36:42 UTC 2025
- Auto Sign-in run successful on Sun May 18 01:44:16 UTC 2025
- Auto Sign-in run successful on Mon May 19 01:43:39 UTC 2025
- Auto Sign-in run successful on Tue May 20 01:40:13 UTC 2025
- Auto Sign-in run successful on Wed May 21 01:39:51 UTC 2025
- Auto Sign-in run successful on Thu May 22 01:38:55 UTC 2025
- Auto Sign-in run successful on Fri May 23 01:38:59 UTC 2025
- Auto Sign-in run successful on Sat May 24 01:28:03 UTC 2025
- Auto Sign-in run successful on Sun May 25 01:46:35 UTC 2025
- Auto Sign-in run successful on Mon May 26 01:42:11 UTC 2025
- Auto Sign-in run successful on Tue May 27 01:38:26 UTC 2025
- Auto Sign-in run successful on Wed May 28 01:40:03 UTC 2025
- Auto Sign-in run successful on Thu May 29 01:39:46 UTC 2025
- Auto Sign-in run successful on Fri May 30 01:37:45 UTC 2025
- Auto Sign-in run successful on Sat May 31 01:37:17 UTC 2025
- Auto Sign-in run successful on Sun Jun  1 01:56:03 UTC 2025
- Auto Sign-in run successful on Mon Jun  2 01:44:38 UTC 2025
- Auto Sign-in run successful on Tue Jun  3 01:41:23 UTC 2025
- Auto Sign-in run successful on Wed Jun  4 01:41:48 UTC 2025
- Auto Sign-in run successful on Thu Jun  5 01:40:26 UTC 2025
- Auto Sign-in run successful on Fri Jun  6 01:40:06 UTC 2025
- Auto Sign-in run successful on Sat Jun  7 01:39:26 UTC 2025
- Auto Sign-in run successful on Sun Jun  8 01:48:42 UTC 2025
