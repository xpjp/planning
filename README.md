# XP-JP Planning

このリポジトリは`xpjp organization`の各リポジトリに割り振る前の議論、相談を
行うために設けました。

## 使用方法

- Code: 特に決まってはいませんが、議事録を収めることを提案します。
- Issues: おそらくここがメインです。どのリポジトリで受け持つかといった議論、
  計画を行います。Issueを立てるのではなくProjectsのカードをIssueに変換する
  手順を勧めます。
- Pull requests: 仮にCodeを議事録として使うのであれば、会議参加者による承認や
  内容の調整をここで行うのが良いでしょう。
- Projects: **このリポジトリのものは使用しません。** [XP-JP横断プロジェクト](
  https://github.com/orgs/xpjp/projects/1)を使用します。
- Wiki: ラボメンバーリストやプロジェクトリストなど組織レベルのメモはここに
  書きましょう。

## [WIP] ワークフロー

1. Discordなどで上がった意見を[XP-JP横断プロジェクト](
   https://github.com/orgs/xpjp/projects/1)の`Inbox 📬`にカードを登録します。
1. 該当するリポジトリが明確である場合はそのリポジトリのIssueに、そうでない場合は
   このリポジトリのIssueに変換し、カードを`Planning 🗪`に移動します。
1. このリポジトリのIssueになったものは、Issueでの議論が終わり割り当てる
   リポジトリが決まった時点で新規のカードを作るステップに戻り、このIssueは
   クローズします。(Projectsの該当するカードも`Done 💪`に移動します)
1. 割り当てられたリポジトリにて議論(`Planning 🗪`)、議論が不要または完了したら担当者が
   作業を開始します(`In progress 🍳`)。コードの改修についてはプルリクエストを
   使いましょう。
1. 作業が終了したらIssueをクローズし、カードを`Done 💪`に移動します。
   作業終了報告は依頼元(Discordなどで)に報告すべきではありますが、
   このワークフローには含めません。

## カードまたはIssue作成のルール

- カードは必ず該当するプロジェクト(リポジトリ)のIssueと紐付けること（該当するプロジェクト(リポジトリ)が無い場合は[planning](https://github.com/xpjp/planning)
を利用)
- Issueには必ず該当するラベルを付けること。
   
## カードステータスのルール

- カード(Issue)を担当する人は必ずIssue担当者に自分にすること。
- 着手中のカードは、[planning](https://github.com/xpjp/planning)上で(以下省略)`In progress 🍳`の状態にすること。
- 完了カードは、`Done 💪`の状態にすること。
- 何かしらの理由で中断しているカードは`Inbox 📬`または`Planning 🗪`の状態にすること。（担当から外れる場合は担当者も外すこと)

## [planning](https://github.com/xpjp/planning)から該当するプロジェクト(リポジトリ)にカードを変更する場合のルール

- 該当するプロジェクト(リポジトリ)にカードを新規作成する。
- [planning](https://github.com/xpjp/planning)のカードを`Done 💪`の状態にする。

***

# 使用例
## やってほしいことや意見がある場合
1. [XP-JP横断プロジェクト](
   https://github.com/orgs/xpjp/projects/1)の`Inbox 📬`にカードを作る。
1. 該当するプロジェクト(リポジトリ)のIssueにする。（該当するプロジェクト(リポジトリ)が無い場合は[planning](https://github.com/xpjp/planning)を利用)
1. 該当するラベル(Labels)を付ける。  
※ Issueには達成条件（ゴール）を明確にすること。

## カード(Issue)の担当になる場合
1. Issueの担当者(Assignees)に自分を指定する。
1. 着手を開始したらカードを`In progress 🍳`に設定する。
1. 作業が完了したらDiscordで連絡すると共にカードを`Done 💪`に設定する。  
   ※ 何かしらの理由で中断する場合は、カードを`Inbox 📬`または`Planning 🗪`に戻す。（担当から外れる場合は担当者も外すこと)
