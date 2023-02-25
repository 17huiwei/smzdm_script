# 什么值得买每日签到脚本 2023 for 青龙面板

## 使用方法

### 青龙拉库

```bash
ql repo https://github.com/hex-ci/smzdm_script.git "smzdm_checkin.py" "" "" "" "py"
```

建议更改定时为随机时间

### 抓包

尽量使用 Android 手机抓包 `https://user-api.smzdm.com/checkin` 链接，把 cookie 取出来放到青龙面板的 SMZDM_COOKIE 环境变量中，多用户请添加多个同名环境变量即可。

建议使用自己 Android 手机的 user agent，可以添加 SMZDM_USER_AGENT 环境变量，否则使用脚本默认 user agent。

## 注意事项

本仓库发布的脚本及其中涉及的任何解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。您必须在下载后的 24 小时内从计算机或手机中完全删除以上内容。
