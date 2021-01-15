# pycharm-settings-mac
Mac OS PyCharm settings.

## 配置

```xml
<?xml version="1.0"?>
<ruleset name="CustomStandard">
  <rule ref="PSR2">
    <!-- 隐藏命名空间反白 -->
    <!-- <exclude name="PSR1.Classes.ClassDeclaration.MissingNamespace"/> -->
    <!-- 隐藏行代码字符数超出反白 --> 
    <exclude name="Generic.Files.LineLength"/>
  </rule>
  <rule ref="PSR1">
    <!-- 隐藏蛇形命名法反白 -->
    <exclude name="PSR1.Methods.CamelCapsMethodName.NotCamelCaps"/>
  </rule>
</ruleset>
```

## 使用方法

![image](uploads/7070070c7c243c5fe5b202433fd36fb5/image.png)

1. `phpstorm > Preferences > Inspections `, 展开 `PHP > Quality tools`, 选中 `PHP_CodeSniffer validation`, 点击右侧的 `Coding standard` 的 `...`, 选择保存的文件. 
2. 点击右侧的 `Coding standard` 的下拉框, 选择 `custom`.
