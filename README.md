# contena

kontena-cli in a wrapper that just works

## Install

```
git clone git@github.com:matti/contena && contena/bin/install
```

## Usage

```
contena login http://master.example.com

contena service ls    # persists login information!
contena app build     # docker socket included!
contena app deploy    # current working directory mapped!
```

## Advanced Usage

```
KONTENA_VERSION=0.15.3 contena version
KONTENA_VERSION=edge contena version
```
