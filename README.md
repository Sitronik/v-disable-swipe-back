# v-disable-swipe-back

## Getting Started

You can install `v-disable-swipe-back` using npm.

```
npm install v-disable-swipe-back
```

Then in main.ts of your ionic vue project

```typescript
import App from './App.vue';

import {DisableSwipeBackDirective} from 'v-disable-swipe-back';

const app = createApp(App)
  .directive('disable-swipe-back', DisableSwipeBackDirective);
```
