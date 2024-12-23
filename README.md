# GendalfJS

## Overview

A lightweight Javascript library that allows you to use Gendalf ASCII animation without any video and audio files. You can put it as easter egg or loading page or error page or just for fun.

The source video file you can find here: https://www.youtube.com/watch?v=Xy73FP65dNA

## Features

- **FUNNY ASCII IMAGE:** Display and ASCII image of Gendalf in any element of the page, provided by user. No pictures, just ascii code.
- **AUDIO MEME:** Provide audio form 100-hours of Gendalf video. No mp3 files, just base64-encoded format.

# Installation

Copy code and init the new Gendalf instance:

```js
new Gendalf();
```

# Usage

It takes 3 arguments:

```js
// id (attach ASCII to getElementById)
// query (attach ASCII to querySelector)
selector,
  // type of DOM attaching
  // 0 - headless, log ASCII only
  // 1 - use getElementById for provided selector value
  // 2 - use querySelector for provided selector value
  // 3 - create new div element ad attach it to body
  // default is 3
  (type = 3),
  // enable audio
  // default is disabled
  (audio = false);
```

Example:

```js
// set ASCII to console, just to debug
new Gendalf(,0);
// add ASCII to specific ID
new Gendalf("gendalfId", 1);
// add ASCII to specific class
new Gendalf(".gendalfClass", 2);
// add ASCII to specific classes (default view classes of Momentum Chrome extension)
new Gendalf(".three-col-layout.app-container.clock.center-clock.has-dash-icon", 2)
// attach ASCII to new element and append it to a body
new Gendalf(,3);
```

## Contributing

We welcome contributions from the community! If you would like to contribute, please follow these steps:

- Fork the repository.

- Create a new branch for your feature or bug fix.

- Make your changes and commit them.

- Push your changes to your forked repository.

- Create a pull request to the main repository.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

Feel free to customize this template to fit the specifics of your project. If you need any help with additional details or sections, just let me know! 😊
