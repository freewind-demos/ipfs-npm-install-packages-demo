IPFS Npm Install Packages Demo
==============================

安装ipfs相关的库：

```
npm install -g ipfs
npm install -g ipfs-npm
```

时间略长，中途可能会有很多warning，但最终应该可以正常工作。

然后用它来安装本工程：

```
ipfs-npm install
```

相对于正常的`npm`来说，速度还是太慢了，慢几十倍。

运行：

```
ipfs-npm run demo
```

注意：对于常见的库可以找到，但是对于一些依赖比较多的项目，会有不少库找不到，这导致ipfs-npm目前还基本不能实用。
