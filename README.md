# Swagger-Bootstrap-UI 

## 简介  
`Swagger-Bootstrap-UI`是`Swagger`的前端UI实现,目的是替换`Swagger`默认的UI实现`Swagger-UI`,使文档更友好一点儿....  
`Swagger-Bootstrap-UI` 只是`Swagger`的UI实现,并不是替换`Swagger`功能,所以后端模块依然是依赖`Swagger`的,需要配合`Swagger`的注解达到效果。
在`Swagger-Bootstrap-UI`提供如下特性：  
- 锚点定位到制定接口;
- 关键字搜索接口;
- 多层级返参类型缩进表格展示;
- 自定义json参数名驼峰或下划线格式。


## 功能  
* 接口文档说明,效果图如下：  
![](https://static-ali.ihansen.org/img/swagger-doc/ec8a86ad-8038-4ee2-8264-5c0491fc285c.png)  
* 在线调试功能,效果图如下:  
![](https://static-ali.ihansen.org/img/swagger-doc/170a4932-ee45-4ed7-9583-5239eb76aeff.png)   

## 在线演示    
[api.ihansen.org](https://api.ihansen.org/swagger-doc.html)  

## 使用说明  
### 1.首先需要引入swagger的配置包信息,如下：
```xml
<dependency>
  <groupId>io.springfox</groupId>
  <artifactId>springfox-swagger2</artifactId>
  <version>${swagger.version}</version>
</dependency>

<!-- 这里swagger-ui是swagger的默认实现,这个jar可以不用引入,使用下面的swagger-bootstrap-ui替代-->
<dependency>
  <groupId>io.springfox</groupId>
  <artifactId>springfox-swagger-ui</artifactId>
  <version>${swagger.version}</version>
</dependency>
```

### 2.maven项目中引用`swagger-bootstrap-ui`的jar包依赖,如下：
```xml
<dependency>
   <groupId>org.ihansen.mbp</groupId>
   <artifactId>swagger-bootstrap-ui</artifactId>
   <version>1.7</version>
</dependency>
```
### 3.其他配置和原`Swagger`保持一致即可。
