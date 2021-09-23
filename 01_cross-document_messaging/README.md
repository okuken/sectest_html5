# Cross-document messaging

```
python -m http.server 9991 --directory ./origin1 &
python -m http.server 9992 --directory ./origin2 &
python -m http.server 9999 --directory ./origin9 &
```
-> http://localhost:9991/parent.html

Trap site:  
-> http://localhost:9999/parent.html

## Notes
* https://html.spec.whatwg.org/multipage/web-messaging.html#web-messaging
* https://developer.mozilla.org/ja/docs/Web/API/Window/postMessage
