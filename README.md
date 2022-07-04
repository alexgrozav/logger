# @grozav/logger

Super basic and lightweight JavaScript / TypeScript logger utility with message types, colors and icons by [@alexgrozav](http://github.com/alexgrozav). 

✅ Fully typed

✅ CommonJS and ESM

## Installation
~~~bash
npm i -S @grozav/logger
~~~

## Usage
~~~typescript
import { Logger } from '@grozav/logger';

Logger.info('Heads up! This message needs your attention, but it\'s not super important.');
Logger.success('Well done! You successfully read this important message.');
Logger.warning('Warning! Better check yourself, you\'re not looking too good.');
Logger.danger('Oh snap! Change a few things up and try submitting again.');
Logger.default('Logging through! This message is just informational.');
Logger.log('I\'m basically console.log().');
~~~

## License
ISC
