<a href="http://https://www.twilio.com/.com"><img src="https://www.bizahoy.com/resource/wp-content/uploads/sites/2/elementor/thumbs/Twilio-Logo-1-o6ls9rqpp2oa50hulcri8k8ribzeqd3phv54nagwck.png" title="Twilio Logo" alt="Twilio Logo">

</a>


<!-- [![FVCproductions](https://avatars1.githubusercontent.com/u/4284691?v=3&s=200)](http://fvcproductions.com) -->

***https://www.twilio.com/.com***

# Send SMS in Your Spring Boot App

> In this tutorial, find complete sample code to send an SMS in Java through Spring Boot and display callback messages using WebSockets.

> #TwilioSMS #Websockets


## Table of Contents 


- [Installation](#installation)
- [SUPPORT](#SUPPORT)



## Installation

- All the `code` required to get started
- Images of what it should look like

### Clone

- Clone this repo to your local machine using `https://github.com/PoojaChirp/WebSocketsSMS`

### Setup

- Add the following dependencies in your build.gradle file
---

```javascript
dependencies {
    implementation 'org.springframework.boot:spring-boot-starter-websocket'
    implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
    implementation group: "com.twilio.sdk", name: "twilio", version : "7.47.2"
    testImplementation('org.springframework.boot:spring-boot-starter-test') {
        exclude group: 'org.junit.vintage', module: 'junit-vintage-engine'
    }
}

```

---


> Make sure to have Java 8 or later JDK

> ngrok allows you to expose a web server running on your local machine to the internet. By informing the port #, we can expose the localhost

```shell
$ ./ngrok http 8080
```

> Run the app by entering the following commands in the terminal

```shell
$ ./gradlew bootRun
```

> Test the app by sending a SMS through localhost:8080
---

## Support

Reach out to me at one of the following places!

- email psrinath@twilio.com
- For more details and documentation twilio.com

---

