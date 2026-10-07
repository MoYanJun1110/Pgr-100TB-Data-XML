# Pgr-100TB-Data-XML
修改 Phigros Data 为100TB

> [!CAUTION]
> **免责声明：** <br>
> 本仓库<mark>仅用于</mark>对 Phigros 存档文件的<mark>技术交流</mark>，请勿<mark>用于商业用途或破坏游戏公平性</mark>。本仓库<mark>不涉及</mark>更改分数、RKS、暴力解析存档等行为。
>
> **注意事项：** <br>
> 1. 本教程<mark>不适用</mark>于苹果设备。
> 2. 本教程只在 <mark>TapTap 上下载的 Phigros 4.0.1</mark> 版本进行过测试，<mark>不保证</mark>其他版本也可使用，后面教程也<mark>一并使用此版本作为演示</mark>。
> 3. 您的设备<mark>必须</mark>已经取得 Root 权限，或使用安卓虚拟机。
> 4. 请<mark>自行承担使用 Root、虚拟机、文件修改等操作带来的风险</mark>。

---

## 修改教程

### 1. 准备工作
请提前准备好：<br>
 1. Root 管理器（本教程以 [Magisk](https://github.com/topjohnwu/Magisk) 为例）<br>
 2. [MT管理器](https://mt.cc)<br>
 3. [TapTap](https://taptap.cn)<br>
 4. [Phigros](https://www.taptap.cn/app/165287)<br>
 5. [需要修改的键值](/com.PigeonGames.Phigros.v2.playerprefs.xml)

### 2. 备份存档
 1. 打开 TapTap，检查 Phigros 是否为最新版本，如果不是，请更新
 2. 打开 Phigros，点击右下角的“设置”→“账号与统计”→“立即同步”

### 3. 修改存档
 1. 打开 MT管理器<br>Magisk 弹窗提示是否授予 Root 权限<br>选择是
 2. 打开
```text
/data/user/0/com.PigeonGames.Phigros/shared_prefs/com.PigeonGames.Phigros.v2.playerprefs.xml
```
 3. 打开`com.PigeonGames.Phigros.v2.playerprefs.xml`
 4. 将[需要修改的键值](/com.PigeonGames.Phigros.v2.playerprefs.xml)里对应的键值替换到你的存档里
 5. 点击右上角保存，删除后缀为`bak`的文件即可
