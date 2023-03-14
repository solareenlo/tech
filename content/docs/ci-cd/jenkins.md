# Jenkinsとは
- オンプレミスのCI/CDツール.
- Jenkinsが全てのビルドプロセスの自動化を行うものではない.
- テストやデプロイなどの各フェーズはそれぞれ専用のツールで自動化を行い, Jenkinsはどういったタイミングでどのツールを呼び出すのかを指示し, エラーが出たら即座にフィードバックを行う処理をする.
- **公式サイト:** https://jenkins.io