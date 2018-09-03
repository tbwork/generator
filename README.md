## MyBatis Generator Extended (MBG-Ex)

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
