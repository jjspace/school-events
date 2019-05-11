# school-events

A task tracker built mainly for tracking homework for classes

Originally built before my freshman year of college. It's undergone a couple versions since then but as of the beginning of this repository it's still fairly close to the original. (that should hopefully change soon)

## Dev Notes

A `config.js` file is expected and used to house the Google API key and current class list. It should be located at `src/js/config.js`.
The contents should declare the following variables: `CLIENT_ID`, `SCOPES`, and `CLASSLIST`
Below is an example:

```javascript
//Client ID from project in the google Developer Console
var CLIENT_ID = '*apiKey*';

// Desired scopes to request from the api
var SCOPES = ["https://www.googleapis.com/auth/calendar"];

let CLASSES = ['CS 380', 'CS 472', 'IDM 100', 'IDM 240', 'WRIT 225'];
```

## Contributing

The short answer: Please Don't

The long answer: This is a personal project that I developed to help with my personal task/homework tracking. Any changes and updates to it I like to design and implement myself so I don't want contributions from others. I also don't want anyone taking my code and using it elsewhere which is why there's (currently) intentionally no license.