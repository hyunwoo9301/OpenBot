## OpenBot [![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/hyunwoo9301/OpenBot/blob/master/LICENSE)

Web-based API Server like 'IBM Watson Conversation API', 'Microsoft Language Understanding Intelligence Service'

OpenBot & OpenNLU provides what you need to build retrieval-based korean chatbot. 

[OpenBot](https://github.com/hyunwoo9301/OpenBot) is able to configure dialog to, manage conversation information of user and handle exceptions.

[OpenNLU](https://github.com/hyunwoo9301/OpenNLU) is able to recognize intent and entity using DNN models.

## Overview
![default](https://user-images.githubusercontent.com/20318775/35503799-85a729aa-0524-11e8-8807-1cf3a6f11d63.png)

## Installation and Settings
### setting requirements
- Set OpenNLU ip & port (ServerConfig.java)

### build requirements
- Spring Framework 4.3.9 RELEASE
- lombok

### execute requirements
- Apache Tomcat 7.0

## Projects based on OpenBot & OpenNLU
### [KONKUK BOT](https://www.youtube.com/watch?v=se6ngTUQdxk)

## Samples
### Sample Request
```json
{
	"userKey":"{userkey}",
	"text":"안녕하세요"
}
```

### Sample Response
```json
{
	"text": "안녕하세요 무엇을 도와드릴까요?"
}
```


## Metadata
<!--
![dialogmap](https://user-images.githubusercontent.com/20318775/35508658-857f28f0-0534-11e8-8386-bcc690e15563.png)
![usermap](https://user-images.githubusercontent.com/20318775/35508667-8c03dce8-0534-11e8-8ad0-ef313fe006b4.png)
-->
