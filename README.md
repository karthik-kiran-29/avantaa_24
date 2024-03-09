# Karpagam Chat Forum

This is a simple chat forum web application built using HTML, CSS, and JavaScript. The purpose of this application is to provide users with a platform to exchange messages in a chat-like interface. The interface is designed to be user-friendly and visually appealing.

## Features

1. **Chat Interface:** The main chat interface is displayed in the `#chat-container` div. Messages are displayed in a vertical layout with the sender's name and message content.

2. **Message Input:** Users can type their messages in the input field provided under the `#message-input` div. The input field has been styled for a better user experience.

3. **Send Message:** Users can send messages by clicking the "Send" button. The `sendMessage()` function handles sending messages and appending them to the chat container.

4. **Blockchain Integration:** This application also includes a basic implementation of a blockchain using JavaScript. Each message sent through the chat is added as a block to the blockchain. The blockchain logic ensures the integrity of the messages by validating the chain.

## Styling

The CSS included in the `<style>` section of the HTML document provides styling to enhance the visual appeal of the chat forum. It includes font styles, colors, spacing, and box shadows to make the interface more attractive.

## Dependencies

- **CryptoJS:** This application utilizes the CryptoJS library to perform cryptographic operations for hashing data within the blockchain.
- **jQuery:** The jQuery library is included for DOM manipulation and event handling.

## Usage

To use the chat forum, simply open the HTML file in a web browser. You can type your message in the input field and click the "Send" button to send messages. The chat interface will display the messages in real-time.

**Note:** This application is a basic prototype and may require further development for additional features and security enhancements.
