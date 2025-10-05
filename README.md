# Pkl module for Butane spec Fedora CoreOS v1.6.0

## Publish

1. run tests `pkl eval examples/example.pkl`
2. commit and tag `git tag fcos_butane.v1.6.0@$VERSION`
3. change version in `PklProject`
4. package the project `pkl project package --allowed-resources "https"`
5. create release on github
