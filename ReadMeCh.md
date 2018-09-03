## MyBatis Generator Extended (MBG-Ex)

该版本的MBG支持用户单独指定存放Example文件的包和目录，官网上只能把Example和Model放一起。这是应对实际中把数据库model和example（操作指导类）分开存放的场景。
从MBG迁移到MBG-Ex，您只需修改配置文件的2个地方：

### 指定新的DOCTYPE

```
<!DOCTYPE generatorConfiguration PUBLIC "-//mybatis.org//DTD MyBatis Generator Configuration 1.0//EN" "https://raw.githubusercontent.com/tbwork/tbwork.github.io/master/dtd/mybatis-generator-config_1_0.dtd" >
```

## 指定Example类的包和地址

```
  <!-- Example Class -->
  <javaExampleGenerator targetPackage="org.xxx.example" targetProject="../src/main/java">
      <property name="enableSubPackages" value="true" />
  </javaExampleGenerator>
```

## 需要的Jar包

参考：[Release-1.0.0](https://github.com/tbwork/mbg-ex/tree/master/release) 
