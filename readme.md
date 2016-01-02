# git-label-packages
> Default label packages for [git-label](https://github.com/jasonbellamy/git-label)


## Getting Started

- Install with [NPM](https://www.npmjs.org/) - `npm install --save git-label-packages`


## Usage

A bunch of default packages are provided to get you started:

- [cla](packages/cla.json)
- [default](packages/default.json) - *default github labels*
- [priority](packages/priority.json)
- [status](packages/status.json)
- [type](packages/type.json)

You can use these packages with both [git-label](https://github.com/jasonbellamy/git-label) and [git-label-cli](https://github.com/jasonbellamy/git-label-cli).


## Developing

If you want to use your own custom labels, you can easily create your own package file(s). 

Packages are just simple JSON arrays that contain an object with a name and hexidecimal color property for each label:

```json
[
  { "name": "bug", "color": "#fc2929" },
  { "name": "duplicate", "color": "#cccccc" },
  { "name": "enhancement", "color": "#84b6eb" },
  { "name": "help wanted", "color": "#159818" },
  { "name": "invalid", "color": "#e6e6e6" },
  { "name": "question", "color": "#cc317c" },
  { "name": "wontfix", "color": "#ffffff" }
]
```


## Related

- [git-label](https://github.com/jasonbellamy/git-label) - API
- [git-label-cli](https://github.com/jasonbellamy/git-label-cli) - CLI


## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality.


## License
Copyright (c) 2016 [Jason Bellamy ](http://jasonbellamy.com)  
Licensed under the MIT license.
