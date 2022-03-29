# Customized Fork of react-notion-x

Refer to the original documentation [here](https://github.com/NotionX/react-notion-x)

## Extended Features

- Exports `text` component to be passed as a config.

## Install

```bash
yarn add customized-react-notion-x
```

## Usage

Once you have created your own custom `Text` component, you can pass it to the Notion Renderer components:

```tsx
<NotionRenderer
  recordMap={page.blocks}
  components={{
    text: Text
  }}
/>
```
