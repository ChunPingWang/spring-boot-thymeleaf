### 安裝 SDKMAN
https://blog.miniasp.com/post/2022/09/17/Useful-tool-SDKMAN#google_vignette

### 透過 SDKMAN 安裝 JDK
```
sdk list java
sdk install java 21.0.6-ms
```

### 下載程式碼
```
git clone https://github.com/ChunPingWang/spring-boot-thymeleaf.git

cd spring-boot-thymeleaf
```

### 編譯與執行
```
# 執行方法 1
./mvnw clean package

ls -al target/serving-web-content-complete-0.0.1-SNAPSHOT.jar

java -jar target/serving-web-content-complete-0.0.1-SNAPSHOT.jar

# 執行方法 2
./mvnw spring-boot:run

# 結束方式
control鍵 + c


```
