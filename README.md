




#### 发包打印
```
// 执行 lerna publish
PS C:\Users\zh\works\vue\vue-storybook> lerna publish
lerna notice cli v5.1.6
lerna info current version 0.0.0
lerna info Assuming all packages changed
? Select a new version (currently 0.0.0) (Use arrow keys)
> Patch (0.0.1)
  Minor (0.1.0)
  Major (1.0.0)
  Prepatch (0.0.1-alpha.0)

// 第一次发包打印
PS C:\Users\zh\works\vue\vue-storybook> lerna publish
lerna notice cli v5.1.6
lerna info current version 0.0.1
lerna notice Current HEAD is already released, skipping change detection.
lerna success No changed packages to publish

// 此时没有的发包成功
// git commit后, 再次执行 lerna publish

```