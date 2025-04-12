# spring-ai-quickstart-openai

This is an example of a simple Spring AI application that connects to
OpenAI LLMs.

## Requirements
* OpenAI API key configured in `src/main/resources/application.properties`

## Run the application

```
./mvnw spring-boot:run
```

## Test the application

```
http :8080

HTTP/1.1 200 
Connection: keep-alive
Content-Length: 227
Content-Type: text/plain;charset=UTF-8
Date: Tue, 11 Apr 2025 08:05:00 GMT
Keep-Alive: timeout=60

I am an AI language model created by OpenAI, designed to assist with a
variety of questions and tasks. I can provide information, answer
questions, and engage in conversation on a wide range of topics.
How can I help you today?
```

## References
* [Spring AI OpenAI Chat](https://docs.spring.io/spring-ai/reference/api/chat/openai-chat.html)
* [OpenAI API Docs](https://platform.openai.com/docs/overview)
* [Get started with Spring AI and OpenAI](https://nevenc.com/get-started-with-spring-ai-and-openai)
