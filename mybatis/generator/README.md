最简单使用mybatis generator方法，pom只需要添加plugin，除了自动添加的spring-boot-starter dependency无需添加其他dependency，src/main/resources添加generatorConfig.xml，即可生成entity、dao、mapperXML，没有service和controller，

添加dependency搜索org.mybatis.spring.boot.starter，org.mybatis.generator/.core/maven-plugin，

参考：
Mybatis代码生成器Mybatis-Generator使用详解 https://www.cnblogs.com/throwable/p/12046848.html
generatorConfig_template来源注：虽然这篇号称是最完整配置详解，还是有不足不处！https://blog.csdn.net/testcs_dn/article/details/77881776
请对照参考另一篇：MyBatis Generator 详解https://blog.csdn.net/wangshfa/article/details/45149907
