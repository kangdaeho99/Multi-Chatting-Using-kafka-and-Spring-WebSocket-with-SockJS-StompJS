<!-- # Multi-Chatting-Using-kafka-and-Spring-WebSocket-with-SockJS-StompJS -->

<!--
## ๐ฉ๐ปโ๐ป ํ ์ด Projects

---
-->

<!-- ### ๐ซ Multi-Chatting-Using-kafka-and-Spring-WebSocket-with-SockJS-StompJS(Kafka์ Spring์ ํ์ฉํ์ฌ ์๋ฐฉํฅ ํต์  ๊ตฌํ) -->

## ๐ซ Kafka์ Spring ์ ํ์ฉํ์ฌ ์๋ฐฉํฅ ํต์  ๊ตฌํ
> Spring WebSocket๊ณผ Kafka, SockJS, StompJS๋ฅผ ํ์ฉํ์ฌ ์๋ฐฉํฅ ํต์  ํ๋ก๊ทธ๋จ์ ๋ง๋ค์ด๋ณด์์ต๋๋ค.

<!-- ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f981aa71-2263-4cc0-9229-1567f0bce802/Untitled.png) -->
<img src="https://user-images.githubusercontent.com/48047377/216617569-a220dce7-2994-4c8e-ba01-cfab6d61bbce.png"/>

**ํ๋ก์ ํธ ๊ธฐํ์๋**
- ์ฑํํ๋ก๊ทธ๋จ์์ ์ฑํ ๋ฉ์ธ์ง๋ค์ ์นดํ์นด ๋ธ๋ก์ปค 1๋์ ์ฃผํคํผ๊ฐ ๊ด๋ฆฌํ๋๋ก ํ์ฌ ๋ฐ์ดํฐ๋ฅผ ๋ถ์ฐ์์ผ ์ฒ๋ฆฌํ์ฌ ์๋ฒ๊ณผ๋ถํ๋ฅผ ๋ง๊ณ , ์๋ฒ์์ ์ฑ์ ๋์ด๊ธฐ ์ํ ๋ฐฉ์ ์ค ํ๋์ธ Kafka์ ๋ํด ์์๋ณด๊ณ ์ ๋ง๋ค์ด๋ณด์์ต๋๋ค.
- AWS ํ๋ฆฌํฐ์ด ํ ๋น๋ฌธ์ ๋ก ์นดํ์นด ๋ธ๋ก์ปค๋ 1๋๋ง ์ฌ๋ ธ์ต๋๋ค.
- Spring WebSocket, Kafka, SockJS, StompJS๋ฅผ ํจ๊ป ์ฌ์ฉํด๋ด๋๋ค.

**๊ฐ๋ฐ๋ชฉํ**

- AWS EC2 ์ AML ํ๊ฒฝ์ ํตํด Kafka์ Zookeeper๋ฅผ ๋ฐฐํฌ์ํต๋๋ค.
- Spring Kafka๋ฅผ Java Configuration์ผ๋ก ์ฐ๋ํฉ๋๋ค.
- Spring Kafka์ WebSocket์ ์ฐ๋ํฉ๋๋ค.

**๊ฐ๋ฐ๊ณผ์ **

- Kafka๋ ๋ฌด์์ธ๊ฐ?์ ๋ํ์ฌ ์์๋ณด๊ณ ์ Kafka ๋ ํผ๋ฐ์ค๋ฅผ ์ฐธ์กฐํ์ฌ ๋ธ๋ก๊ทธ์ ๊ธ์ ๋จ๊ฒจ๋ณด์์ต๋๋ค. ([[Spring] Kafka [1] (์นดํ์นด Getting Started)](https://passionfruit200.tistory.com/178))
- Kafka๋ฅผ Spring FrameWork with Java Configuration ํ๊ฒฝ์์ ์คํํด๋ณด๊ณ ์ Spring-Kafka QuickTour ๋ ํผ๋ฐ์ค๋ฅผ ์ฐธ์กฐํ์ฌ ๊ตฌํํด๋ณด์์ต๋๋ค. ( [[Spring] Kafka [2](์นดํ์นด Quick Tour with Java Configuration)](https://passionfruit200.tistory.com/180) )
- WebSocket with STOMP, SOCKJS ๊ฐ์๊ฒฝ์ฐ ์ด์ ์ ๊ตฌํ๊ฒฝํ์ด ์์ด ๊ตฌํํ์ต๋๋ค.
- AWS์ ์ธ๋ฐ์ด๋, ์์๋ฐ์ด๋ ์ค์ ์ ํตํด ์๋ฒ์ ์ ์ํ  ์ ์์ต๋๋ค.
- AWS์์ Kafka ์คํ์ ์ ์ํฌํธ, ์ ์IP ์ค์ (config)ํ์ผ, Zookeeper ์คํ์ ์ ์ํฌํธ, ์ ์IP ์ค์ (config)์ ํตํด ์๋ฒ์ ์ ์ํ  ์ ์์ต๋๋ค.


**์นดํ์นด ๊ตฌ์ฑ๋**
- ์นดํ์นด ๊ตฌ์ฑ๋์๋๋ค. AWS ํ๋ฆฌํฐ์ด๋ก 1๋๋ก ๊ตฌํํ์ต๋๋ค.
<img src="https://user-images.githubusercontent.com/48047377/216774815-00892c77-b519-48b6-91ed-ba7fe917333a.PNG"/>


## ๐ย ๊ธฐ์  ์คํ
> ํ๋ก ํธ์๋ ๊ธฐ์ ์คํ์ ๋ค์๊ณผ ๊ฐ์ต๋๋ค. 
- HTML/CSS, JAVASCRIPT

> ๋ฐฑ์๋ ๊ธฐ์ ์คํ์ ๋ค์๊ณผ ๊ฐ์ต๋๋ค.
- java 1.8
- Spring Framework 5.0.7
- Spring WebSocket (TCP Connection)
- SockJS (WebSocket Emulation)
- STOMPJS (Message Broker)
- Kafka 1.0 (Message Broker)

> ์ธํ๋ผ ๊ตฌ์กฐ๋ ๋ค์๊ณผ ๊ฐ์ต๋๋ค.
- Spring Framework with Github Actions
- AWS EC2 AML, Kafka, ZooKeeper
  
<!--  
## ๊ธฐ์ ์คํ
- **For Kafka :** Spring-Kafka
- **For WebSocket** : Spring-WebSocket, Spring-Messaging, javax.websocket-api,
- **For Data Format** : jackson-databind, jackson-dataformat-xml
### Infrastructure
- Spring Framework with Github Actions
- AWS EC2, Kafka, ZooKeeper
- Apache Tomcat 9.0.30
-->



## ๐โ๐ฆบ ์คํ์ด๋ฏธ์ง

---

<!-- ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b671a44f-ecd1-4dbe-a25f-43fca954bc3e/Untitled.png) -->

[step 0].WebSocket ์๋ฐฉํฅ ํต์  ํ์ธ์ ์ํ ๋ธ๋ผ์ฐ์  ํฌ๋กฌ 1๊ฐ, Internet Explorer 1๊ฐ๋ฅผ ํต๋๋ค.

[step 1].๋ฉ์ธ์ง๋ฅผ ๋ณด๋ด๊ณ ์ ํ๋์๊ฐ โMessage Check! I am sending it!โ๋ผ๊ณ  ๋ฐ์กํฉ๋๋ค.

[step 2].๋๊ฐ์ ๊ฐ์ ๋ฉ์ธ์ง๊ฐ ๋จ๋์ง ํ์ธํฉ๋๋ค.

<img src="https://user-images.githubusercontent.com/48047377/216617535-cf72ddd6-a68b-42cd-8716-0d58ea2f4411.png"/>


[step 3]. Kafka์ ๊ฐ์ด ์ฌ๋ฐ๋ฅด๊ฒ ๋ค์ด๊ฐ๋์ง ํ์ธํฉ๋๋ค.
<!-- ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9d93f602-3c76-4f2e-a95f-812e5fe1d6cc/Untitled.png) -->
<img src="https://user-images.githubusercontent.com/48047377/216617621-f25c93f4-ec87-450d-8882-3d2f2014316f.png"/>
