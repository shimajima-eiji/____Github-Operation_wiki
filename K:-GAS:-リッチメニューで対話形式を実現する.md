https://github.com/shimajima-eiji/--GAS_v5_LINEWizard

1. リッチメニューの入力内容を正しく判断する必要があるため、まずは入力の受け皿を設定する。
1. 環境変数を書き換えて、ユーザーの入力を受け取る（不正な入力やタイムオーバーを弾くのは別途）
1. 完了したら処理を完了し、環境変数を廃棄する

処理したい内容によって環境変数のステータスを書き換えるだけで、ほとんどの機能追加に対応できるはず。  
運用面を考えるとさまざまな課題（特に保守面）があるが、インターフェースにこだわらないならGoogleフォームがベストだと考える。
