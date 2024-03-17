# QLExpress高级应用

输入关键字`qe`进入`qlexpress`专注模式。

### 清空动作历史

```java
top.myrest.myflow.db.MyDb.INSTANCE.removeAllData("top.myrest.myflow.action.my.ActionHistoryDoc");
```

### 清空剪贴板

```java
top.myrest.myflow.db.MyDb.INSTANCE.removeAllData("top.myrest.myflow.clipboard.ClipboardDoc");
```

### 清空数据库所有数据

```java
top.myrest.myflow.db.MyDb.INSTANCE.clearAllData();
```
