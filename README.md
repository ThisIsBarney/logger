# @thisisbarney/logger

a winston logger setup. Conform to winston config.

log file will be stored in process.env.LOG_PATH, or the app root by default.

```javascript
import logger from '@thisisbarney/logger';

logger(level, content);
```