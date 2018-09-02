# environment
環境用のリポジトリ

# zsh
homebrewを使って入れる
homebrewは各自で入れる

・brew install zsh

・sudo vi /etc/shells
shellsの中に「/usr/local/bin/zsh」を追記

chsh -s /usr/local/bin/zsh
　ログインシェル変更のコマンド

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  Oh-my-zshをインストール（zshのフレームワーク）

~/.zshrcをリポジトリからダウンロードし、保存