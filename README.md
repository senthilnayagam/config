# Config [![wercker status](https://app.wercker.com/status/434dc06bfabf5b12bc5e25bcac109e38/s/ "wercker status")](https://app.wercker.com/project/bykey/434dc06bfabf5b12bc5e25bcac109e38) [![GoDoc](https://godoc.org/github.com/olebedev/config?status.png)](https://godoc.org/github.com/olebedev/config)

Package config provides convenient access methods to configuration
stored as JSON or YAML.

Original version you cat find at [godoc.org](http://godoc.org/github.com/moraes/config).

This version extends the functionality of the original without losing compatibility.
Major features added:

- [`Set(path string, value interface{})`](http://godoc.org/github.com/olebedev/config#Config.Set) method
- [`Env()`](http://godoc.org/github.com/olebedev/config#Config.Env) method, for OS environment variables parsing
- [`Flag()`](http://godoc.org/github.com/olebedev/config#Config.Flag) method, for command line arguments parsing
- [`U`](https://godoc.org/github.com/olebedev/config#Config.UBool) methods

Example and more information you can get [here](http://godoc.org/github.com/olebedev/config).
