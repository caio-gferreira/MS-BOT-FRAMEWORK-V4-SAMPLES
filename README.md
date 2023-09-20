# Miscrosoft Bot Framework V4
Microsoft's Bot Framework is a development platform that simplifies the creation, deployment, and management of bots. It provides a wide range of tools, SDKs, and services that enable developers to create highly interactive bots for various platforms such as websites, messaging apps, and virtual assistants. With the Bot Framework, developers can leverage artificial intelligence and machine learning to build intelligent bots capable of understanding and responding to user interactions in a natural way.

## Prerequisites
- NodeJS v18.14.1
- TypeScript 5.2.2

## Create new bot

You need create a directory for your project
### 1 - Install Yeoman Generator
The Yeoman Generator is a tool that automates project setup, adhering to best practices and providing useful components. It can create structures for web projects, such as website skeletons, Angular apps, Node.js applications, and more. For more information, click here: https://yeoman.io.

 ```bash
 npm install -g yo
 ```

### 2 - Install botbuilder generator.
```bash
npm install -g generator-botbuilder
```

### 3 - Run Botbuilder and create new bot
```bash
yo botbuilder
```
#### Answer the questions to create bot
```
? What's the name of your bot? my-chat-bot
? What will your bot do? Demonstrate the core capabilities of the Microsoft Bot Framework
? What programming language do you want to use? Typescript
? Which template would you like to start with? Empty Bot
? Looking good.  Shall I go ahead and create your new bot? Yes
```
## References
- https://learn.microsoft.com/en-us/azure/bot-service/index-bf-sdk?view=azure-bot-service-4.0
- https://yeoman.io