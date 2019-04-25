# ssl-demo
ssl-demo


keytool -genkey -keystore example.keystore -storepass example -keypass example -dname "CN=localhost, OU=test, O=test, L=test, S=test, C=test" -keyalg EC -sigalg SHA256withECDSA

keytool -export -keystore example.keystore -file examplle-jks.cer -storepass example

keytool -import -keystore example.truststore -file examplle-jks.cer -storepass examplle -keypass examplle -noprompt

