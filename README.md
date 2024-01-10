# インストールと設定ファイル適用スクリプト

このスクリプトは、Zsh、Tmux、Emacs、および `tmux-mem-cpu-load` をインストールし、指定の GitHub リポジトリからそれぞれの設定ファイルを取得・適用します。

## 使用方法

1. このリポジトリをクローンします。

```bash
git clone [https://github.com/your_github_username/your_scripts_repo.git](https://github.com/long-910/dotfiles.git)
cd dotfiles
```

2. `install_and_configure.sh` スクリプトを実行可能にします。

```bash
chmod +x install_and_configure.sh
```

3. スクリプトを実行します。

```bash
./install_and_configure.sh
```

4. スクリプトが実行されると、Zsh、Tmux、Emacs、および `tmux-mem-cpu-load` がインストールされ、それぞれの設定ファイルが指定の GitHub リポジトリから取得・適用されます。

## 注意事項

- このスクリプトは Debian ベースのシステム（例: Ubuntu）を対象としています。他のディストリビューションを使用している場合は、スクリプトを適切に修正してください。
- GitHub リポジトリの URL やファイルパスは、各自の設定に合わせて変更してください。
- スクリプトを実行すると、既存の設定ファイルがあればバックアップを作成し、新しいファイルで上書きします。十分に注意して使用してください。

## `tmux-mem-cpu-load` の追加情報

`tmux-mem-cpu-load` は Tmux でメモリと CPU の使用状況を表示するツールです。インストール後、Tmux を起動した際に画面の右下にメモリ使用量と CPU 使用率が表示されます。

## ライセンス

このスクリプトは MIT ライセンスのもとで提供されています。詳細については [LICENSE](LICENSE) をご覧ください。
