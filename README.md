# FL-Logger (Logger Library for Flaapworks)

**Version:** 1.0.0

**Author:** pjvanderberg

## Overview

`fl-logger` is a logging library built as part of Flaapworks, offering seamless integration for logging within the framework. While designed for Flaapworks, it also functions as a standalone logger, providing a flexible solution for logging needs.

## Features

- **Logging Capabilities:** Log messages with different log levels (debug, info, error, etc.).
- **Customizable:** Create multiple loggers with customizable names.
- **Version 1.0.0:** Initial release with fundamental features.

## Installation

To integrate `fl-logger` into your project, follow these steps:

```bash
npm install fl-logger
```

## Usage

```javascript
import Logger from 'fl-logger';

// Create a logger instance with a custom name
const logger = new Logger('Flaapworks');

// Log a debug message
logger.debug('This is my test log');
```

## Contributing

Contributions are highly appreciated! If you have suggestions, found a bug, or want to contribute to `fl-logger`, please feel free to open issues or submit pull requests on [GitHub](https://github.com/Poolchaos/fl-logger).

## License

This project is licensed under the [MIT License](LICENSE).

---

**Flaapworks - Where Innovation Meets Simplicity**
