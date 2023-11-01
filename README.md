<!-- markdownlint-disable MD030 -->

# Flowise Embed React

React library to display flowise chatbot on your website without watermark

## Install

```bash
npm install https://github.com/Aum-Kansara/flowise-embed-no-watermark https://github.com/Aum-Kansara/flowise-embed-react-no-watermark
```

or

```bash
yarn add https://github.com/Aum-Kansara/flowise-embed-no-watermark https://github.com/Aum-Kansara/flowise-embed-react-no-watermark
```

## Import

Full Page Chat

```tsx
import { FullPageChat } from "flowise-embed-react-no-watermark";

const App = () => {
  return (
    <FullPageChat
      chatflowid="your-chatflow-id"
      apiHost="http://localhost:3000"
    />
  );
};
```

Popup Chat

```tsx
import { BubbleChat } from "flowise-embed-react-no-watermark";

const App = () => {
  return (
    <BubbleChat chatflowid="your-chatflow-id" apiHost="http://localhost:3000" />
  );
};
```
