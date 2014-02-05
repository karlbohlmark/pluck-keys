# pluck-keys

  pick keys of object

## Installation

    // component
    $ component install karlbohlmark/pluck-keys
    
    // npm
    $ npm install pluck-keys


## API
```javascript
pluckKeys = require('pluck-keys')

name = pluckKeys("firstname", "lastname")

var user = {
  email: "user@domain.com",
  firstname: "Azealia",
  lastname: "Banks",
  password: "yungrapunxel"
}

var nameProps = name(user) // { firstname: "Azealia", lastname: "Banks" }
```
## License

  MIT
