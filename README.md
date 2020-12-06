# csvimportes
csv文件导入ElasticSearch

## 项目简介：

一个简单的springboot项目，将tmdb数据信息导入ElasticSearch中。

## 版本信息：

SpringBoot 2.3.4

JDK1.8

Elasticsearch7.7.1

## pom文件：

```xml
<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>org.elasticsearch</groupId>
        <artifactId>elasticsearch</artifactId>
        <version>7.7.1</version>
    </dependency>
    <dependency>
        <groupId>org.elasticsearch.client</groupId>
        <artifactId>transport</artifactId>
        <version>7.7.1</version>
    </dependency>
    <dependency>
        <groupId>org.elasticsearch.plugin</groupId>
        <artifactId>transport-netty4-client</artifactId>
        <version>7.7.1</version>
    </dependency>
    <dependency>
        <groupId>com.opencsv</groupId>
        <artifactId>opencsv</artifactId>
        <version>4.2</version>
    </dependency>
    <dependency>
        <groupId>com.alibaba</groupId>
        <artifactId>fastjson</artifactId>
        <version>1.2.58</version>
    </dependency>
</dependencies>
```

