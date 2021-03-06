# Metronome

> JavaScript metronome library using Web Audio API

See it in action: https://github.com/heroandtn3/pwa-metronome

## Installation

```
npm i musical-metronome
```

## Usage

```javascript
// ES Module
import { Metronome } from 'musical-metronome';

// CommonJS
const { Metronome } = require('musical-metronome');

//UMD
const Metronome = window.musicalMetronome.Metronome;

const metronome = new Metronome({ tempo: 120 });

metronome.init(); // call on user action, e.g. onClick
setInterval(() => metronome.tick(), 25);
metronome.play();
metronome.stop();
```

See example in `public` directory.

## Development

1. Clone the repo.
2. Install the dependencies
3. Run `npm start` then here you go!

## License

[MIT](https://oss.ninja/mit/developit/)
