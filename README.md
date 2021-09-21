# react-images-upload with support for state persistence

This is a modded version of [react-images-upload](https://github.com/JakeHartnell/react-images-upload) with support for persisting state (setting state from props).

## Installation

```bash
npm install --save 'https://gitpkg.now.sh/ftruzzi/react-images-upload/src/component'
```

## Usage

There is a new prop called `files`, and the `defaultImages` props has been renamed to `pictures`.

```JSX
<ImageUploader
  files={files}
  pictures={pictures}
  onChange={(files, pictures) => saveYourStateSomewhere(files, pictures)}
  ...
/>
```
