# kubesecret

### examples 

```
# help
$ ./build/kubesecret.darwin-amd64 --help

# list secrets (uses kubctl)
$ ./build/kubesecret.darwin-amd64 list --help
$ ./build/kubesecret.darwin-amd64 list

# get secret (uses kubctl)
$ ./build/kubesecret.darwin-amd64 get --help
$ ./build/kubesecret.darwin-amd64 get <SECRET_NAME>

# base64-decode secret

$ ./build/kubesecret.darwin-amd64 base64-decode --help
$ cat /some-project/secret.yaml | ./build/kubesecret.darwin-amd64 base64-decode
$ ./build/kubesecret.darwin-amd64 get <SECRET_NAME> | ./build/kubesecret.darwin-amd64 base64-decode
```


### graalvm docs
- https://medium.com/graalvm/understanding-class-initialization-in-graalvm-native-image-generation-d765b7e4d6ed