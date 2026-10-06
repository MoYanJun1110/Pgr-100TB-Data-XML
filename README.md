# Pgr-100TB-Data-XML
修改 Phigros Data 为100TB

> [!CAUTION]
> **免责声明:** <br>
> 本仓库仅用于对 Phigros 存档文件的技术交流，请勿用于商业用途或破坏游戏公平性。本仓库不涉及更改分数、RKS、暴力解析存档等行为。

---

## 修改教程

> [!CAUTION]
> 1. **本教程不适用于苹果设备。**
> <br>2. **本教程只在 TapTap 上下载的 Phigros 4.0.1 版本进行过测试，不保证其他版本也可使用，后面教程也一并使用此版本作为演示。**
> <br>3. 您的设备必须已经获得 Root 权限，或使用安卓虚拟机。
> <br>4. **请自行承担使用 Root、虚拟机、文件修改等操作带来的风险。**

### 1. 准备工作
需要的软件：
    1. Root 管理器（看你自己喜好，本教程以 Magisk 为例）
    2. [MT管理器](mt.cc)
    3. [TapTap](taptap.cn)
    4. Phigros
    5. 需要修改的键值
2. 使用 `Shizuku` 在 root 下运行。
3. 授权给 MT 管理器。
4. 打开：

```text
/data/user/0/com.PigeonGames.Phigros/shared_prefs/com.PigeonGames.Phigros.v2.playerprefs.xml
```

5. 在 `com.PigeonGames.Phigros.v2.playerprefs.xml` 里填入对应的头像 XML 值。
6. 保存后，移动或删除 MT 管理器自动生成的备份文件即可
