## Performance Requirements


- 1.1 Largest Contentful paint of the E-Commerce store should be less than 2 seconds to make a better User Experience.

    - 1.1.1 First Contentful Paint of E-Commerce store should be less than 1.8 seconds to provide an immediate feedback to the user that the page is actually loading.

- 1.2 First Input delay should less than 100ms to make a good first impression.

- 1.3 Cumulative Layout Shift should be less than 0.1 second to provide a much stable layout to customer.

- 1.4 Cache should be enabled on all layers of application, including (Service Worker), application-api (nginx output cache) and app (SSR output cache).

- 1.5 The system should use Google Cloud CDN to get P(90) responses within 2 seconds of request.

- 1.6 The system should use HTTP/2 Push to reduce the latency by 3 seconds by loading resources even before the browser knows it will need them.

- 1.7 The system should use Lazy Loading to prevent or delay the loading of non-critical resources until all the content which has priortity higher than 5 are loaded.

- 1.8 E-Commerce application should be running under HTTPS which uses TLS (SSL) to encrypt normal HTTP requests and responses to meet the requirements of Progressive Web Application.

- 1.9 E-Commerce application should have Web App Manifest and Service Worker to pass the baseline criteria of Progressive Web Application.

- 1.10 The application should use nuxt.js/pwa module to deal with offline caching.

- 1.11 The system should be doing tasks in more than 2 threads and in one of the threads web workers will be executing scripts in the background without interfering the user interface.


