## hotwire

A CORS enabled wrapper on the Hotwire API.

Created for use on a project for [Middlebury College CS465](go.middlebury.edu/infovis) requiring AJAX access to the Hotwire API.

### Use

Use the same exact URL as with Hotwire, only with `hotwire.herokuapp.com` prepended in place of `api.hotwire.com`.

HTTP and HTTPS protocols are supported.

You still need an `apikey`!

### Example

```js
var url = "http://hotwire.herokuapp.com/v1/tripstarter/air?apikey=APIKEY&origin=PHL&dest=SFO&format=json&sort=date",
    xhr = new XMLHttpRequest();

xhr.open("GET", url, true);
xhr.send(null);
```