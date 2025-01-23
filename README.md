# multiple-go-modules

## Versioning

Create module specific versions using `git tag moduleName/semver`

Example
```
git tag clogger/v1.0.0
git push origin clogger/v1.0.0
```

## How to use modules
To `get` just a specific module within your Go project, do `go get github.com/praveenk007/multiple-go-modules/<module>@<version>`

Example:
```
go get github.com/praveenk007/multiple-go-modules/cerror@v1.0.0
```
