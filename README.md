# Wine for Laravel
A wine package for Laravel development and deployment.

Note: Make sure you have `alias wine="node wine"` set in your bash profile. Otherwise, you will have to run `$ node wine` for every command.
# Installation

* Install wine. Instructions at https://grape-juice.org.
* `wine inst laravel-wine`
* Set your `"wineryfile"` to `"./winery/winery.js"` in your `wine.json`.
```json 
{
  "wine" : {
    "wineryfile" : "./winery/winery.js"
  }
}
```

# Usage

### Starting development application
```bash
$ wine app
```

### Deployment
```bash
$ wine upgrade
```

### Optimize
```bash
$ wine optimize
```

#

TODO: Add fix.sh