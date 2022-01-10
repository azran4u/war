yarn config set yarn-offline-mirror /tmp/npm-packages-offline-cache<br>
mv ~/.yarnrc ./<br>
rm -rf node_modules/ yarn.lock<br>
yarn install<br>
