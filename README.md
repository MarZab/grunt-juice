# grunt-juice

## Getting Started
This plugin requires Grunt `~0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-juice --save-dev
```

## Example grunt config
```javascript
juice: {
    options: {},
    dist: {
        files: [{
            src: "source/emails/template.html",
            dest: 'public/emails/template.html'
        }]
    }
}
```
