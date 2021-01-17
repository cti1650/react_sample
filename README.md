# React_sample

React でWEBアプリを作成する際のテンプレート

## ローカルへのコピー

以下を clone  
```bash
git clone https://github.com/cti1650/react_sample.git
```

## リポジトリを複製する

1. Git Bash を開いてください。

2. リポジトリのベアクローンを作成します。   
   ```bash
   git clone --bare https://github.com/cti1650/react_sample.git
   ```

3. 新しいリポジトリをミラープッシュします。(--mirror 以降は複製先のリポジトリを指定)  
   ```bash
   cd react_sample.git
   git push --mirror [複製先リポジトリURL]
   ```

4. 先ほど作成した一時ローカルリポジトリを削除します。  
   ```bash
   cd ..
   rm -rf react_sample.git
   ```
   
5. 先ほど作成した複製先のリポジトリをクローンします。  
   ```bash
   git clone [複製先リポジトリURL]
   ```
   
6. 必要な機能をインストールする。  
   ```bash
   npm install
   ```
   
7. 動作確認  
   ```bash
   npm start
   ```
   
   ブラウザでhttp://localhost:3000/を開く

## 参考サイト
> [GitHubでCloneでもForkでもなくリポジトリの複製が欲しい](https://qiita.com/taquaki-satwo/items/f8482c45dc91b6df9d34)
> [Reactの基礎を学ぶ](https://qiita.com/tsuuuuu_san/items/58f82201ded0da420201)

---

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
