#http://charmander-url.herokuapp.com/

# FreeCodeCamp API Basejump: URL Shortener Microservice
## User stories:
1. I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
2. If I pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain an error instead.
3. When I visit that shortened URL, it will redirect me to my original link.

## Example creation usage:

```js
https://charmander-url.herokuapp.com/new/https://www.google.com
https://charmander-url.herokuapp.com/new/http://foo.com:80
```

## Example creation output:

```js
{"original_url":"http://foo.com:80","short_url":"https://charmander-url.herokuapp.com/8170"}
```

## Usage:

```
https://charmander-url.herokuapp.com/2871
```

### Will redirect to:

```
https://www.google.com/
```
# rafUrlShortener
