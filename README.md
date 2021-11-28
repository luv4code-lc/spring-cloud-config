# Spring Cloud Config Application

#In this file i have adding Asymmetric Encryption of Properties  to cratation keytool code 

{keytool -genkeypair -alias appEncryptionKey -keyalg RSA -keysize 4096 -sigalg SHA512withRSA \ 
-dname 'CN=Config Server,OU=Spring Cloud,O=Luv4code'  \ 
-keypass 1q2w3e4r -keystore appEncryptionKey.jks -storepass 1q2w3e4r}
