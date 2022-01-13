yarn config set yarn-offline-mirror /tmp/npm-packages-offline-cache<br>
mv ~/.yarnrc ./<br>
rm -rf node_modules/ yarn.lock<br>
yarn install<br>



yarn config set yarn-offline-mirror-pruning false<br>
yarn config set "strict-ssl" false -g<br>
