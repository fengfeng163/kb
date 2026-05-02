作成中
### 默认的包扫描规则
- `@SpringBootApplication`标注的类就是主程序类
- SpringBoot只会扫描主程序所在的包及其下面的包
- 自定义扫描路径。
	- 方式1：`@SpringBootApplication(scanBasePackages="com.example")`
	- 方式2：
	```java
	@SpringBootConfiguration
	@EnableAutoConfiguration
	@CompoentScan("com.example")
	public class MainApplication{
	...
	}
	```

