[![platform](https://img.shields.io/badge/platform-Node--RED-red)](https://nodered.org)
[![npm](https://img.shields.io/npm/v/node-red-contrib-primitive-status.svg)](https://www.npmjs.com/package/node-red-contrib-chatgpt)
[![downloads](https://img.shields.io/npm/dt/node-red-contrib-primitive-status.svg)](https://www.npmjs.com/package/node-red-contrib-chatgpt)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/HaroldPetersInskipp/node-red-contrib-/blob/main/LICENSE)

## node-red-contrib-chatgpt

A Node-RED node that interacts with OpenAI machine learning models like "ChatGPT".

### Quick Start

Install with the built in <b>Node-RED Palette manager</b> or using npm:
```
npm install node-red-contrib-chatgpt
```

## Help

### Set `msg.topic` to a string with the value of `completion`, `image`, or `edit`.

### 1. If `msg.topic` is set to `completion`:

`msg.payload` should be a well-written prompt that provides enough information for the model to know what you want and how it should respond. Its success generally depends on the complexity of the task and quality of your prompt. A good rule of thumb is to think about how you would write a word problem for a middle schooler to solve.

### 2. If `msg.topic` is set to `image`:

`msg.payload` should be a prompt of text description of the desired image.

### 3. If `msg.topic` is set to `edit`:

`msg.payload` should be a prompt of text to use as a starting point for the edit.

### Example

None for now sorry, maybe submit a pull request with one.

## Links

* [NodeRED](https://flows.nodered.org/node/node-red-contrib-chatgpt)
* [Libraries.io](https://libraries.io/npm/node-red-contrib-chatgpt)
* [npm](https://www.npmjs.com/package/node-red-contrib-chatgpt)

### Bugs reports and feature requests

Please report any issues or feature requests at <a href="https://github.com/HaroldPetersInskipp/node-red-contrib-chatgpt/issues">GitHub</a>.
