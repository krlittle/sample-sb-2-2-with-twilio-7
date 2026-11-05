# sample-sb-2-2-with-twilio-7

Sends a text message over REST.

## Stack

- Spring Boot 2.2.4.RELEASE
- Java 8
- Gradle 6.0.1
- Twilio 7.38.0

## Build

```
./gradlew build
```

## Run

```
./gradlew bootRun
```

Set `TWILIO_ACCOUNT_SID`, `TWILIO_AUTH_TOKEN` and `TWILIO_FROM_NUMBER` first.

```
curl -X POST localhost:8080/texts -d to=+15550002222 -d body=hello
```
