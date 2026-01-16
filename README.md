## pixelbatch-svgo-offline

Remove everything keeping only package.json and README.md

1. Run to create npm cache in npm-cache directory: 
   `npm install   --cache=$PWD/npm-cache   --prefer-offline   --no-audit   --no-fund`
 
2. Run to verify deps are satified from generated cache:
   `npm install --offline --cache=$PWD/npm-cache --no-audit --no-fund`
   It will create node_module directory, we can remove it.
