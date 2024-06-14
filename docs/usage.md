# Usage
## Initiate Logger
To use `coreLogger`, simply include the coreLogger.php file and create a new instance of the `Logger` class.

```php

// Import Logger class into the global namespace
// These must be at the top of your script, not inside a function
use LaswitchTech\coreLogger\Logger;

// Load Composer's autoloader
require 'vendor/autoload.php';

// Initiate coreLogger
$Logger = new Logger();
```

## Methods
`coreLogger` provides the following methods to manage configuration files:

- [add()](methods/Logger/add.md)
- [clear()](methods/Logger/clear.md)
- [config()](methods/Logger/config.md)
- [debug()](methods/Logger/debug.md)
- [error()](methods/Logger/error.md)
- [get()](methods/Logger/get.md)
- [info()](methods/Logger/info.md)
- [ip()](methods/Logger/ip.md)
- [isInstalled()](methods/Logger/isInstalled.md)
- [list()](methods/Logger/list.md)
- [log()](methods/Logger/log.md)
- [read()](methods/Logger/read.md)
- [set()](methods/Logger/set.md)
- [success()](methods/Logger/success.md)
- [warning()](methods/Logger/warning.md)
