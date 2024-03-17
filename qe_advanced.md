# QLExpress Advanced

Type keyword `qe` to enter `qlexpress` focused mode.

### clear action histories

```java
top.myrest.myflow.db.MyDb.INSTANCE.removeAllData("top.myrest.myflow.action.my.ActionHistoryDoc");
```

### clear clipboards

```java
top.myrest.myflow.db.MyDb.INSTANCE.removeAllData("top.myrest.myflow.clipboard.ClipboardDoc");
```

### clear database all data

```java
top.myrest.myflow.db.MyDb.INSTANCE.clearAllData();
```
