```
keytool -genkey -keyalg RSA -storepass 123456 -keypass 123456 -validity 36500 -alias cas.example.com 
-keystore tomcat.jks -dname "CN=cas.example.com,OU=github,O=luojiash,L=ShenZhen,ST=GuangDong,C=CN"

keytool -exportcert -alias cas.example.com -keystore tomcat.jks  -file tomcat.crt -storepass 123456
```