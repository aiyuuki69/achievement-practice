
# GitHub Achievements 入門ガイド

GitHub初心者向けに、2つのアチーブメント「YOLO」と「Pull Shark」の取得方法を紹介します。
このガイドでは、実際にリポジトリを作成し、Pull Requestを作成・Mergeすることで、GitHubの基本操作を学びます。

## 1. 用語の説明

まずは、GitHubでよく使われる用語を覚えましょう。

| 用語 | 説明 |
|---|---|
| GitHub | ソースコードやファイルを管理・共有できるサービス |
| Repository（リポジトリ） | ファイルやプログラムを保存する場所 |
| Commit（コミット） | ファイルの変更内容を記録すること |
| Branch（ブランチ） | メインの作業場所とは別に作る作業用の場所 |
| Pull Request（プルリクエスト） | 自分の変更を取り込んでもらうための申請 |
| Merge（マージ） | Pull Requestの変更を取り込むこと |
| Fork（フォーク） | 他の人のリポジトリを自分のアカウントにコピーすること |
| Review（レビュー） | Pull Requestの変更内容を確認すること |

### 基本的な作業の流れ

1. Branchを作成する
2. ファイルを編集する
3. Commitする
4. Pull Requestを作成する
5. Mergeする

この流れを覚えれば、GitHubでの基本的な開発作業ができるようになります。

---

## 2. 今回取得するアチーブメント

### YOLO

![YOLO](https://github.githubassets.com/images/modules/profile/achievements/yolo-default.png)

自分が作成したPull Requestを、コードレビューなしでMergeすると取得できるアチーブメントです。

取得条件：
- 自分でPull Requestを作成する
- 承認レビューを受けずにMergeする

### Pull Shark

![Pull Shark](https://github.githubassets.com/images/modules/profile/achievements/pull-shark-default.png)

自分が作成したPull RequestがMergeされると取得できるアチーブメントです。

取得条件：

| ランク | 必要なMerge数 |
|---|---:|
| Default | 2件 |
| Bronze | 16件 |
| Silver | 128件 |
| Gold | 1,024件 |

まずは2件のMergeを目指しましょう。

---

## 3. リポジトリを準備する

リポジトリの準備方法は2種類あります。

新しくリポジトリを作成しても、既存のリポジトリをForkしても構いません。

### 方法A：新しくリポジトリを作成する

初心者にはこちらがおすすめです。

1. GitHubにログインする
2. 画面右上の「＋」をクリックする
3. 「New repository」をクリックする
4. Repository nameに `github-achievement-practice` と入力する
5. Publicを選択する
6. 「Add a README file」にチェックを入れる
7. 「Create repository」をクリックする

これで準備完了です。

### 方法B：既存のリポジトリをForkする

既存のリポジトリを利用したい場合はこちらです。

1. Forkしたいリポジトリを開く
2. 画面右上の「Fork」をクリックする
3. 自分のアカウントを選択する
4. 「Create fork」をクリックする

これで自分のアカウントにリポジトリがコピーされます。

Forkした自分のリポジトリを使って作業してください。

---

## 4. YOLOを取得する

自分のリポジトリを使って作業します。

### STEP 1：Branchを作成する

リポジトリのBranch選択欄から新しいBranchを作成します。

Branch名：

`yolo-practice`

### STEP 2：README.mdを編集する

README.mdを開き、鉛筆マークをクリックします。

ファイルの最後に次の文章を追加します。
※サンプルです。自由に入力してください。

```text
Hello GitHub!
This is my first YOLO achievement practice.
```

### STEP 3：Commitする

画面下部の「Commit changes」をクリックします。

これで変更内容が記録されます。

### STEP 4：Pull Requestを作成する

1. 「Compare & pull request」をクリックする
2. タイトルに `Add YOLO practice message` と入力する
3. 「Create pull request」をクリックする

これでPull Requestが作成されます。

### STEP 5：レビューなしでMergeする

YOLOのポイントは、自分のPull RequestをコードレビューなしでMergeすることです。

1. Pull Requestの内容を確認する
2. 承認レビューを受けずにMerge可能な状態であることを確認する
3. 「Merge pull request」をクリックする
4. 「Confirm merge」をクリックする

これでYOLOの取得条件を満たす操作が完了です。

---

## 5. Pull Sharkを取得する

Pull Sharkは、自分が作成したPull Requestが2件Mergeされると最初のランクを取得できます。

先ほどのYOLO用Pull Requestも条件を満たせば1件としてカウントされます。

つまり、あと1件のPull RequestをMergeすればOKです。

### STEP 1：2つ目のBranchを作成する

Branch名：

`pull-shark-practice`

### STEP 2：README.mdを編集する

次の文章を追加します。
※サンプルです。自由に入力してください。

```text
This is my second Pull Request!
I am practicing GitHub achievements.
```

### STEP 3：Commitする

「Commit changes」をクリックします。

### STEP 4：Pull Requestを作成する

1. 「Compare & pull request」をクリックする
2. タイトルに `Add Pull Shark practice message` と入力する
3. 「Create pull request」をクリックする

### STEP 5：Mergeする

Pull Requestの内容を確認してMergeします。

これで2件目のPull RequestがMergeされました。

Pull Sharkの最初の取得条件を満たすことができます。

---

## 6. 取得状況をチェックする

### YOLO

- [ ] リポジトリを準備した
- [ ] Branchを作成した
- [ ] README.mdを編集した
- [ ] Commitした
- [ ] Pull Requestを作成した
- [ ] コードレビューなしでMergeした

### Pull Shark

- [ ] 1件目のPull RequestをMergeした
- [ ] 2件目のPull RequestをMergeした
- [ ] 自分のPull Requestが2件Mergeされていることを確認した

---

## 7. アチーブメントを確認する

GitHubのプロフィールを開いて確認しましょう。

以下のURLの「ユーザー名」を自分のGitHubユーザー名に変更してください。

https://github.com/ユーザー名?tab=achievements

取得条件を満たしていても、表示まで時間がかかる場合があります。

少し時間を置いてから確認してみましょう。

---

## 8. 注意事項

- 練習には自分が管理できるリポジトリを使用しましょう。
- 他人のリポジトリに無断で変更を加えないようにしましょう。
- アチーブメント目的で意味のないPull Requestを大量に作らないようにしましょう。
- 実際のチーム開発や本番環境では、レビューを省略しないでください。
- GitHubの仕様変更によって取得条件が変わる可能性があります。

---

## 9. まとめ

今回の基本操作は次の4つです。

**Branch → Commit → Pull Request → Merge**

この操作を2回繰り返すことで、Pull Sharkの最初の取得条件を満たせます。

さらに、1回目のPull RequestをコードレビューなしでMergeすれば、YOLOも目指せます。

まずは自分の練習用リポジトリで挑戦してみましょう。

GitHubの基本操作を覚えながら、アチーブメント取得を楽しみましょう！