# BBN-Q.github.io
BBN-Q landing page

https://bbn-q.github.io/

BBN-Q is the Raytheon BBN Technologies quantum group's collection of open source code.  Inside you'll fine instrumentation software, HDL firmware, simulation code and other things we find useful around the lab.

## Updates

The `code.md` and `research.md` files are basically markdown. You can edit them and then just push to the master branch to update the site. The research page is a copy of the Raython page.

## Building

### Local Development

1. Check that you have Ruby 2.1.0 or higher installed.

```
$ ruby --version
> ruby 2.X.X
```

If you don't have Ruby installed, install [Ruby 2.1.0 or higher](https://www.ruby-lang.org/en/downloads/).

2. Install Bundler

```
$ gem install bundler
```

3. Install all dependencies

```
$ bundle install
```

4. Build/serve the site locally

```
$ ./start_local.sh
```

This loads the site at `localhost:5555`.
