# CoCreate-geolocation

CoCreate actions for the browser Geolocation API.

## Install

```sh
yarn add @cocreate/geolocation
```

Or load the browser bundle from `https://cdn.CoCreateJS.com/geolocation/latest/CoCreate-geolocation.min.js`.

## Usage

Use the geoLocation action methods getCurrentPosition, watchPosition, and clearWatch. The browser may request permission and requires a secure context.

```html
<button actions="geoLocation.getCurrentPosition">Get location</button>
```

See [`demo/index.html`](demo/index.html) and the [documentation](docs/index.html).
