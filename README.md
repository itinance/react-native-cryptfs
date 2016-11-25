# react-native-cryptfs
This library provides native file enryption and decryption for ReactNative-Apps (RSA, AES)


- !! Under DEVELOPMENT !! -

The purpose of this library is not to reinvent the wheel. Instead we want to provide bindings between native crypto libraries to the react-native level.

Something like this:

```
function decryptFile( algorythm, sourcePath, destinationPath, key);
```
or
```
function decryptFile( algorythm, sourcePath, destinationPath, publicKey, privateKey)
```

Contributors are welcome.
