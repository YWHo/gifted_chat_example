# example-gifted-chat

This is the example from https://github.com/FaridSafi/react-native-gifted-chat/tree/master/example-gifted-chat
(Also added the example of using 'adaptivecards-reactnative')

Lots of people using `react-native-gifted-chat` might want to know that...

1. There are so many render props could use, but what should I pass?
2. How could I customize each component, but leaving its functionality.

> For example, said that you want to customize the `send button`, when you pass your own component to `renderSend`, after that you will lose the functionality of clean up text when a message has been sent.

---

For anyone who wants to know how to use the render Props properly.

##### Such as:

- renderInputToolbar
- renderActions
- renderComposer
- renderSend
- renderAvatar
- renderBubble
- renderSystemMessage
- renderMessage
- renderMessageText
- renderCustomView

<img src="https://i.imgur.com/dbkc7I4.png" alt="Example for customize components" width="300">

## How this project was created:

Command: `npx expo-cli init gifted_chat_example --npm`

### Addition modules after the project was generated
1. `npm install react-native-gifted-chat`

## How to run
1. `npm install`
2. `npm start`

