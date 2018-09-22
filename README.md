# CocoaLumberjack documentation
CocoaLumberjack Documentation https://CocoaLumberjack.github.io
This repository hosts the in source documentation for [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack). You can view this at [CocoaLumberjack.github.io](https://CocoaLumberjack.github.io).

## Maintenance

The documentation is auto-generated using [Jazzy](https://github.com/realm/jazzy).

#### Install jazzy

```
[sudo] gem install jazzy
```

#### Generate the CocoaLumberjack documentation

```
jazzy \        
  --objc \
  --author CocoaLumberjack \
  --github_url https://github.com/CocoaLumberjack/CocoaLumberjack \
  --github-file-prefix https://github.com/CocoaLumberjack/CocoaLumberjack/tree/3.4.1 \
  --module-version 3.4.1 \
  --umbrella-header Classes/CocoaLumberjack.h \  
  --framework-root . \
  --module CocoaLumberjack \
  -o ../CocoaLumberjack/github.io
```

(assuming CocoaLumberjack and CocoaLumberjack.github.io live in the same folder)