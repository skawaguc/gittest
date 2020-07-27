# test

github練習用リポジトリ。  
githubの知見を色々書いていく予定。

## README.mdで数式を表現したい

README.mdで数式をmarkdown形式で入力すると、以下のようになってしまう。

$$
    \begin{equation}
        e^{i\theta} = \cos{\theta} +i\sin{\theta}
    \end{equation}
$$

これを回避するためには、数式を画像化して貼る必要がある。  
画像化する際は、[CODECOGS](https://www.codecogs.com/latex/eqneditor.php)というサービスが便利。  
ここで、数式を画像化して、その際のURLを貼り付けると、以下のようになる。

<img src="https://latex.codecogs.com/gif.latex?e^{i\theta}&space;=&space;\cos{\theta}&space;&plus;&space;i\sin{\theta}" />

ただし、この方法では文中に
<img src="https://latex.codecogs.com/gif.latex?e^{i\theta}&space;=&space;\cos{\theta}&space;&plus;&space;i\sin{\theta}" />
と入れるとずれるため、readmeでは数式を書かず、jupyter-notebookとか使うとよいかな。

[jupyter-notebookへのリンク](readme.ipynb)

参考URL：

- [GithubのREADMEとかwikiで数式を書く](http://idken.net/posts/2017-02-28-math_github/)

## Git管理下に置きたくないファイルがある

workspace直下に`.gitignore`ファイルを作成し、当該ファイルパスを記載しておく。  
また、`.gitignore`自身も記載することで、自身も隠すことができる。

参考URL：

- [Visual studio codeで.vscodeディレクトリをgit管理から外す](https://qiita.com/EngTks/items/a4f875956f0b087668f6)
- [リモートブランチに.gitignoreをpushせずに管理する方法](https://qiita.com/Nshota/items/08d423d9681fe9cfd744)
