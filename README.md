# test-lerna

## Launch verdaccio
```bash
 verdaccio
 ```
 and add the repository to the main package.json file in order to publish easily

 ## Modify packages 
 ```bash
 # Publish changed package from version in package.json file
 lerna publish from-package  --dist-tag latest -y
 ```

