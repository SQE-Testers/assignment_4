## Performance Requirements

- Cache should be enabled on all layers of application, including (Service Worker), application-api (nginx output cache) and app (SSR output cache).

- The system should use Google Cloud CDN.

- The system should use HTTP/2 Push to reduce the latency by loading resources even before the browser knows it will need them.

- The system should use Lazy Loading to prevent or delay the loading of non-critical resources until they are needed.

- The application shall be a progressive Web Application to deliver a native-like user experience.

- The application should use nuxt.js/pwa module to deal with offline caching.

- The system should be doing tasks in threads and in one of the threads web workers will be executing scripts in the background without interfering the user interface.


