# flutter_getx_simple_news_app

**Source API:**

- OpenWeather: [link]([https://newsapi.org/](https://openweathermap.org/api))

**Packages using:**

- get: [link](https://pub.dev/packages/get)
- http: [link](https://pub.dev/packages/http)
- geolocator: [link]([https://pub.dev/packages/http](https://pub.dev/packages/geolocator))
### Application structure
                    
```
.
├── android                         - It contains files required to run the application on an Android platform.
├── assets                          - It contains all images and fonts of your application.
├── ios                             - It contains files required to run the application on an iOS platform.
├── lib                             - Most important folder in the application, used to write most of the Dart code.
    
    ├── constants                   - It contains static constant class file.
    ├── controller                  - It manage state of the model and resultan data.
    ├── models                      - It contains class / objects created specifically.
    ├── service                     - It connects app to the 'outside world'.
    ├── screen                      - It contains widgets of the screens.
    ├── main.dart                   - Starting point of the application.
```


