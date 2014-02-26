# npmlist

Sugar wrapped `npm list --depth=0`

Project initiated using [nblocks](https://github.com/geekjuice/nblocks)


# Why?
Current npm's (v1.4.3 and v.1.4.4) list (ls) function at depth=0 is broken. Plus
this looks aesthetically better than the original (such colors. oooohh~)


## Usage

Installation

```sh
  $ npm install -g npmlist
```

Usage (sans color)

```sh
  $ npmlist
  Installed npm packages: (global)

  bower....................[1.2.8]
  brewcleaner..............[1.1.0]
  chai.....................[1.9.0]
  coffee-script............[1.7.1]
  connect.................[2.13.0]
  dispatch-proxy...........[0.1.2]
  express..................[3.4.8]
  gulp.....................[3.5.2]
  mocha...................[1.17.1]
  nodemon.................[1.0.15]
  npm......................[1.4.4]
  yo.......................[1.1.2]

  $ npmlist local
  Installed npm packages: (local)

  chai....................[1.9.0]
  coffee-script...........[1.7.1]
  gulp....................[3.5.2]
  gulp-clean..............[0.2.4]
  gulp-coffee.............[1.4.1]
  gulp-plumber............[0.5.6]
  mocha..................[1.17.1]
```


## Credits

[nblocks](https://github.com/geekjuice/nblocks)


## License

Copyright &copy; Nicholas Hwang <nick.joosung.hwang@gmail.com>
