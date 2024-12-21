# Visit counter API

**Profile Visits**
![Simple Visit Counter](https://nullocrix.pythonanywhere.com/api/github/Your-GitHub-Username)

# Usage

**Default usage**
- Default color is ```green```

| Description  | Version | Parameters   |              Query              |
| :---         | :---:  |          :---          |              :---               |
| Default usage  | `V.1`  | /api/github/username        |                  |
| Color selection | `V.1`  | /api/github/username     | /api/github&textcolor="green"              |
| Style selection | `V.2 N/A`  | N/A | N/A |

```example:```
```Markdown
![Simple Visit Counter](https://nullocrix.pythonanywhere.com/api/github/Your-GitHub-Username)
```
#
**Custom Color**
- Available colors ```red```, ```green```, ```blue```.
![Simple Visit Counter](https://nullocrix.pythonanywhere.com/api/github/Your-GitHub-Username&textcolor="green")
![Simple Visit Counter](https://nullocrix.pythonanywhere.com/api/github/Your-GitHub-Username&textcolor="red")
![Simple Visit Counter](https://nullocrix.pythonanywhere.com/api/github/Your-GitHub-Username&textcolor="blue")

## Version V.1
<p align="left">
  <p>The counter is in SVG format. On the next update. The default SVG format will be replaced with a JSON response <code>{"200 OK": "12345678"}</code></p>

**Next update V.2 ⚙️🔧**
- Added features, ```Style selection``` and ```hex rgb colors```.
- Bug fixes from ```/api/github/{query}```
