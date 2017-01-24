# GCC on Docer

* Ubuntu 17.04
* gcc-7
  * g++-7

## Usage
```sh
docker run -it -v ${your app dir}:/app/ amaya382/gcc bash
```

or

```sh
docker run -v ${your app dir}:/app/ amaya382/gcc ${your build command with gcc}
```
