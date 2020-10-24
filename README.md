# test-lerna

## Launch verdaccio
```bash
 verdaccio
 ```
 and add the repository to the main package.json file in order to publish easily

 ## Modify packages 
 ```bash
 # Change version using
 lerna version --conventional-commits -y
 # Publish changed package from version in package.json file
 lerna publish from-package  --dist-tag latest -y
 ```

