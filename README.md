# adambatkin.dev (2023-)

This is the source code to my personal website!

It's been a few years since I last made something front-end completely from scratch so I've kept it nice and simple. The only post-processing part is removing all the tailwind classes that aren't used in the webpage. Nice bit of fresh air away from the JavaScript frameworks of current!

## Building

As mentioned above, there's no framework to worry about. All you need to do is just build a production tailwind css stylesheet:
```
$ npx tailwindcss -i ./assets/css/site.css -o ./css/site.css --minify
```
(and if you're editing it, replace --minify with --watch for real-time compilation when you make a change)
```
$ npx tailwindcss -i ./assets/css/site.css -o ./css/site.css --watch
```

## Licence

It's the MIT licence, read the full licence text in [LICENCE.md](LICENCE.md) or understand it at [tl;drLegal](https://www.tldrlegal.com/license/mit-license)