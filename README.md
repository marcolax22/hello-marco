# Initio theme for Hugo

![GitHub](https://img.shields.io/github/license/miguelsimoni/hugo-initio.svg?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/miguelsimoni/hugo-initio.svg?style=flat-square)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/miguelsimoni/hugo-initio.svg?style=flat-square)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/miguelsimoni/hugo-initio/main.svg?style=flat-square)
![GitHub closed issues](https://img.shields.io/github/issues-closed/miguelsimoni/hugo-initio.svg?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/miguelsimoni/hugo-initio.svg?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/miguelsimoni/hugo-initio.svg?style=flat-square)
![GitHub watchers](https://img.shields.io/github/watchers/miguelsimoni/hugo-initio.svg?style=flat-square)

### Original Template Info

**Licensing:** Creative Commons (for more options, go to the [original template site](http://www.gettemplate.com/info/initio/))  
**Released:** Feb 21, 2014  
**Last Updated:** Feb 21, 2014  
**Version:** 1.0  
**Bootstrap:** 3.3.4 or higher  
**Libraries:** jQuery  
**Designer:** Sergey Pozhilov  

## Installation

```
$ cd /<your-hugo-site-directory>
$ git submodule add https://github.com/miguelsimoni/hugo-initio.git themes/hugo-initio
```

More info: [hugo setup guide](https://gohugo.io/overview/installing/)

## Configuration

[Live Demo](https://miguelsimoni.github.io/hugo-initio-site/)

[Example Site](https://github.com/miguelsimoni/hugo-initio/tree/master/exampleSite)

[config.toml](https://github.com/miguelsimoni/hugo-initio/tree/master/exampleSite/config.toml)

### Google Analytics

```toml
[params.google.analytics]
    trackerID = "GA-000000000-0"
```

Disable the Google Analytics by leaving `params.google.analytics.trackerID` empty.

### Almost there...

In order to see your site in action, you can run Hugo's built-in local server.

```
$ cd exampleSite
$ hugo server -t ../..
```

Now enter [`http://localhost:1313/`](http://localhost:1313/) in the address bar of your browser.

## Deployment

- [Hosting on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
- [More hosting and deployment options](https://gohugo.io/hosting-and-deployment/)

## License

This port is released under the MIT License. Check the [original theme license](http://www.gettemplate.com/info/initio/) for additional licensing information.

## Thanks

Thanks to [Steve Francia](https://github.com/spf13) for creating Hugo and the awesome community around the project. And also thanks to [Sergey Pozhilov](http://www.gettemplate.com/) for creating this awesome theme.
