# Contributing

Contributions are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the [license of this project](../LICENSE).

## Submitting a pull request

1. [Fork](https://github.com/qdm12/vintedrop/fork) and clone the repository
1. Create a new branch `git checkout -b my-branch-name`
1. Modify the code
1. Ensure the following passes

    ```go
    CGO_ENABLED=1 go test -race ./...
    golangci-lint run
    ```

1. Commit your modifications
1. Push to your fork and [submit a pull request](https://github.com/qdm12/vintedrop/compare)

## Resources

- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)

## Contributors
