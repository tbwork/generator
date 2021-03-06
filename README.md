## MyBatis Generator Extended (MBG-Ex)  [中文说明](https://github.com/tbwork/mbg-ex/blob/master/ReadMeCh.md)

This version of MBG supports to specify the package of example files (e.g., XXXExample), rather than put them together with model files which is the standard way of [the offical MBG](https://github.com/mybatis/generator).

From MBG to MBG-Ex, you just need to modify two parts of **generator configuration file**:

### DOCTYPE Modification

```
<!DOCTYPE generatorConfiguration PUBLIC "-//mybatis.org//DTD MyBatis Generator Configuration 1.0//EN" "https://raw.githubusercontent.com/tbwork/tbwork.github.io/master/dtd/mybatis-generator-config_1_0.dtd" >
```

## ExampleGenerator Configuration

```
  <!-- Example Class -->
  <javaExampleGenerator targetPackage="org.xxx.example" targetProject="../src/main/java">
      <property name="enableSubPackages" value="true" />
  </javaExampleGenerator>
```

## Released Jar

Here is the released jar package already for direct use. See [Release-1.0.0](https://github.com/tbwork/mbg-ex/tree/master/release).
