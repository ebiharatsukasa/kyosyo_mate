■ figmaリンク
https://www.figma.com/file/BaXInUfwCKFp8vtqC02B7c/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0-1&t=9qrkiJEpzoTeg0De-0

■ サービス概要
新たな建築と出会い、訪れた建築を記録したい人に
建築に関する情報の収集、記録機能を提供する
建築特化型サービスarchimateです

■メインのターゲットユーザー
建築学生、美大生、建築に興味はあるけど知識はあまり無い人
自分がこれまでに訪れた建築を記録したい人
色んな建築を見に行きたいけど、具体的にどこに行けばいいのかわからず、とりあえずググってみるも良い情報が得られず困っている人

■ユーザーが抱える課題
建築について検索しても、まとめサイトの薄い情報か過度に難解な情報ばかりで気軽に行ける建築の情報が手に入らない
自分がこれまでに行った建築の情報が埋もれてしまい、自分でも把握できない

■解決方法
ユーザーは、自分が行った建築を記録できる
ユーザーは、他のユーザーが記録した建築を閲覧できる

■実装予定の機能
・未ログインユーザー
	・未ログインユーザー用のトップページを表示できる
		・使い方の説明を見ることができる
		・人気の建築を一覧表示できる
	・ログインできる
		・ゲストログインできる
		・ソーシャルログインできる
	・サインアップできる
		・ソーシャルサインアップできる

・ログインユーザー
	・トップページを表示できる
		・訪れた建築を記録できる
		・他のユーザーが記録した建築をランダムで表示できる
		・他のユーザーが記録した建築を検索できる
			・名称、所在地、設計者から検索できる
			・シチュエーション（一人でゆったり、デート、家族みんなで）から検索できる
			・特徴（眺望good、木質空間、コンクリート、直線美、曲線美、不朽の名作、、、）から検索できる
		・建築のメモを表示できる
		・Like/Nopeできる
	・メニューを表示できる
		・ユーザーが記録した建築を一覧表示、詳細表示、編集、削除できる
		・ユーザーが記録した建築の数に応じて、色分けされた日本地図を表示する（東京の建築を一つ記録したら東京が白から水色に、二つ記録したら黄色、5つ記録したらオレンジ、、みたいな感じ）
		・ユーザーが記録した建築の数をレベルに反映する（建築学科一年生〜世界の巨匠みたいな感じ）
		・Likeした建築を一覧表示、詳細表示、削除、検索できる
		・Likeした建築の住所からマップに遷移できる	
		・マイページを表示できる
			・プロフィールを編集、削除できる

・管理ユーザー
	・ユーザーの一覧、編集、削除、検索ができる
	・建築の一覧、編集、削除、検索ができる
	・Likeの一覧、編集、削除、検索ができる
	・Situationの一覧、編集、削除、検索ができる
	・Featureの一覧、編集、削除、検索ができる

■なぜこのサービスを作りたいのか？
建築学生時代、なかなか実際に見に行ける建築の情報を集めることができませんでした。
マップから付近の建築を探せるサービスは既にあるが、CGMではなくメディアであるため、サービス上で写真を見ることができず使っていて楽しくない。
建築専門誌のオンラインサービスもあるが、情報量は優れている一方でユーザービリティが低く、サブスク料金も高価で敷居が高い。
もっと気軽に建築の情報を得たい。
加えて、自分がこれまでに訪れた建築を記録していくことで達成感が得られるようなサービスが欲しい。
そんな想いから、本サービスを作ろうと思いました。

■スケジュール
企画〜技術調査：3/22 〆切
README〜ER図作成：4/6 〆切
メイン機能実装：5/14 〆切
β版をRUNTEQ内リリース（MVP）：5/15 〆切
本番リリース：5/31