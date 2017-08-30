# go-whosonfirst-names-tools

Go command line tools for working with names in Who's On First documents.

## Install

You will need to have both `Go` (specifically a version of Go more recent than 1.6 so let's just assume you need [Go 1.8](https://golang.org/dl/) or higher) and the `make` programs installed on your computer. Assuming you do just type:

```
make bin
```

All of this package's dependencies are bundled with the code in the `vendor` directory.

## Tools

_Please write me_

### wof-names-validate

```
./bin/wof-names-validate -mode repo /usr/local/data/whosonfirst-data
16:56:14.320098 [wof-names-validate] WARNING Feature ID 102147495 has an invalid language tag 'eng_p'
16:56:24.165599 [wof-names-validate] WARNING Feature ID 85892915 has an invalid language tag 'eng_p'
16:59:14.273177 [wof-names-validate][index] STATUS directory /usr/local/data/whosonfirst-data/data 4m30.089235929s
```

Ensure that all the `name:` properties for a WOF document can be parsed by the [go-whosonfirst-names](https://github.com/whosonfirst/go-whosonfirst-names) `tags.NewLangTag` function.

## See also

* https://github.com/whosonfirst/go-whosonfirst-names
