## Upstream versions

Check https://pages.github.com/versions/

## Building EventMachine on the m1

```
bundle config set --global build.eventmachine --with-ldflags="-Wl,-undefined,dynamic_lookup"
```

## Building and testing

```
./bin/jekyll serve --watch 
```
