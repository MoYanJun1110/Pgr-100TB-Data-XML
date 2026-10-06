# Pgr-100TB-Data-XML
修改 Phigros Data 为100TB

> [!WARNING]
> **免责声明:** <br>
> 本仓库仅用于对 Phigros 存档文件的技术交流，请勿用于商业用途或破坏游戏公平性。本仓库不涉及更改分数、RKS、暴力解析存档等行为。

> [!CAUTION]
> 请自行承担使用 Root、虚拟机、文件修改等操作带来的风险。

---

## 修改教程

您的设备必须已经获得 Root 权限，或使用安卓虚拟机，苹果设备是不可以的

1. 虚拟机开启 root。
2. 使用 `Shizuku` 在 root 下运行。
3. 授权给 MT 管理器。
4. 打开：

```text
/data/user/0/com.PigeonGames.Phigros/shared_prefs/com.PigeonGames.Phigros.v2.playerprefs.xml
```

5. 在 `com.PigeonGames.Phigros.v2.playerprefs.xml` 里填入对应的头像 XML 值。
6. 保存后，移动或删除 MT 管理器自动生成的备份文件即可。
   也可以把`com.PigeonGames.Phigros.v2.playerprefs.xml`文件属性改成只读（但目前无法确定会不会影响上传存档）
