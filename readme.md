yarn config set yarn-offline-mirror ./npm-packages-offline-cache
yarn config set yarn-offline-mirror-pruning true
mv ~/.yarnrc ./
rm -rf node_modules/ yarn.lock
yarn install
