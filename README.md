#これは構築環境にエラーがある状態の構築を実施するansibleになります

#apache[12345].ymlはどこかしらでサービスが起動できないような構成をとっています

#apache_seikai.ymlは正しいトムキャットの構築のansibleです

#トムキャットの猫のページを表示することが目的です

#サービスに必要なポートは事前にご自身で確認の上実施してください

#全てのansibleコードは実行可能です

#apache1から順に難易度を設定しているため、1から順に行うことをお勧めします（gitを学習している頃には片手間の問題でしょうが）

#まずは/tmp内のREADME[12345].txtを読み、http://グローバルIP:8080で検索することから始めてください

#エラーログの確認や様々な情報を確認してエラーを解決してください

#正解のansibleコードと問題のansibleコードを比較して問題を解くのは厳禁です

#[/etc/systemd/system/tomcat.service:12] Unknown lvalue 'ExecRestart' in section 'Service'は気にせず
