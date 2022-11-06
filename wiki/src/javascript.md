# Javascript

## Snippet

```js
// Native
import { Observable } from 'rxjs';

const observable$ = new Observable(observer => {
  let x = 0;

  setInterval(() => {
    observer.next(++x);
  }, 1000);
});

// test push
```