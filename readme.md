yarn config set yarn-offline-mirror /tmp/npm-packages-offline-cache<br>
yarn config set yarn-offline-mirror-pruning true<br>
mv ~/.yarnrc ./<br>
rm -rf node_modules/ yarn.lock<br>
yarn install<br>
