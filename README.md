# phone-verification
Phone Verification using Twilio API for both SMS and Voice options

![alt text](https://raw.githubusercontent.com/anup756/phone-verification/master/images/twilio-logo-red.png)

###### Things you need:

1. Twilio Account SID
2. Twilio Authentication Token
3. Twilio Number
4. Twilio Application SID (Optional)
5. Twilio Agent Number (Optional)

If you use maven, you need to add this dependency in your *pom.xml* file:
```xml
<dependency>
  <groupId>com.twilio.sdk</groupId>
  <artifactId>twilio</artifactId>
  <version>(7.0,7.9)</version>
</dependency>
```
For verification, we will generate 7 digit random number (unique) and once verified, add that number to the user created. This step is after the user creates an account and when the account is still locked.
![alt text](https://raw.githubusercontent.com/anup756/phone-verification/master/images/phoneverification.png)
