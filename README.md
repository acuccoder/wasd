# wasd

it's a package manager.

it does stuff.

## usage

```shell
$ wasd sync
$ wasd search pkg
$ wasd install pkg-name
```

### publishing a package

```shell
$ wasd publish pkg-name-1.0.0 --repo-dir ./repo --repo-base https://repo-url.com/ 
```

For example, 

`./wasd publish hello-bin-1.0.0 --repo-dir ./repo --repo-base http://localhost:8080z`

deps

- a relatively new version of python3
- internet access
