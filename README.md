# react-embed-youtube

[![Build Status](https://travis-ci.org/n1ckdm/react-embed-youtube.svg?branch=master)](https://travis-ci.org/n1ckdm/react-embed-youtube)

A responsive YouTube component that for React.

## Install

With npm:

```bash
npm install --save react-embed-youtube
```

With Yarn:

```bash
yarn add react-embed-youtube
```

## Usage

```jsx
import YouTube from 'react-embed-youtube'

...

<YouTube id='CWu29PRCUvQ' start={124} stop={130} />
```

## Options

- `aspectRatio`: Set an aspect ratio or percentage. Default: `"16:9"`
- `prependSrc`: Prepends a string to the embed URL (before the YouTube ID). Default: `"https://www.youtube.com/embed/"`
- `start`: Chooses a start time for the video.
- `stop`: Chooses a stop time for the video.
- `appendSrc`: Appends a string to the embed URL. Default: `""`
