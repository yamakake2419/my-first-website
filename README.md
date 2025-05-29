# my-first-website
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>私の最初のホームページ</title>
    <style>
        /* ここからCSS */
        body {
            background-color: #e0f7fa; /* 背景色：薄い青色 */
            color: #333333;           /* 文字色：濃い灰色 */
            font-family: sans-serif;  /* フォントの種類（ゴシック体など） */
            margin: 20px;             /* ページ全体の余白 */
            line-height: 1.6;         /* 行間の高さ */
        }

        h1 {
            text-align: center;       /* 見出しを中央揃えにする */
            color: #00796b;           /* 見出しの色を少し変えてみる（任意） */
        }

        .container {
            max-width: 800px;         /* コンテンツの最大幅 */
            margin: 0 auto;           /* 中央揃え */
            padding: 20px;
            background-color: #ffffff; /* コンテンツエリアの背景を白に（任意） */
            border-radius: 8px;       /* 角を少し丸める（任意） */
            box-shadow: 0 2px 4px rgba(0,0,0,0.1); /* 軽い影をつける（任意） */
        }

        p {
            margin-bottom: 10px;      /* 段落の下の余白 */
        }

        strong {
            font-weight: bold;        /* 太字 */
        }
        /* ここまでCSS */
    </style>
</head>
<body>

    <div class="container">
        <h1>ようこそ！</h1>

        <p><strong>名前：</strong> <span>[自分の名前に置き換える]</span></p>
        <p><strong>学部学科：</strong> <span>[自分の学科に置き換える]</span></p>
        <p><strong>趣味：</strong> <span>[自分の趣味を入力]</span></p>

        <p>
            このページは私の最初のホームページです。<br>
            HTMLとCSSを使って作成しました。
        </p>
    </div>

</body>
</html>
Use code with caution.
Html
解説と使い方：
上記のコード全体をコピーします。
テキストエディタ（メモ帳、Visual Studio Code、Sublime Textなど）を開き、新しいファイルに貼り付けます。
ファイルを保存します。ファイル名は index.html や myprofile.html のように、拡張子を .html にしてください。
情報を置き換える:
[自分の名前に置き換える] の部分を、ご自身の名前に書き換えてください。
[自分の学科に置き換える] の部分を、ご自身の学部学科に書き換えてください。
[自分の趣味を入力] の部分を、ご自身の趣味に書き換えてください。
保存したHTMLファイルをウェブブラウザ（Google Chrome, Firefox, Edgeなど）で開くと、作成したページが表示されます。
CSSのポイント：
body セレクタ: ページ全体のスタイルを指定します。
background-color: #e0f7fa;: 背景色を薄い青に設定。
color: #333333;: 基本の文字色を濃い灰色に設定。
font-family: sans-serif;: 文字のフォントを指定。
margin: 20px;: ページの周囲に余白を設定。
line-height: 1.6;: 行の高さを調整して読みやすくします。
h1 セレクタ: <h1> タグ（「ようこそ！」）のスタイルを指定します。
text-align: center;: テキストを中央揃えにします。
color: #00796b;: 見出しの色を少し濃いめの青緑にしてみました（これは任意です。不要であれば削除しても、body の色が適用されます）。
.container セレクタ: 自己紹介のコンテンツを囲むためのdiv要素に適用されるスタイルです。
max-width: 800px;: コンテンツが広がりすぎないように最大幅を設定。
margin: 0 auto;: コンテナ自体をページの中央に配置。
padding: 20px;: コンテナの内側に余白を設定。
background-color: #ffffff;: コンテンツ部分の背景を白にして、本文を読みやすくしました（任意）。
border-radius: 8px;, box-shadow: ...;: 見た目を少し良くするための装飾です（任意）。
p セレクタ: <p> タグ（段落）のスタイルを指定します。
margin-bottom: 10px;: 段落の下に少し余白を設けます。
strong セレクタ: <strong> タグ（「名前：」など）のスタイルを指定します。
font-weight: bold;: 文字を太字にします。
このコードで、ご要望の自己紹介ページが作成できます。
さらに変更したい点があれば、お気軽にお知らせください。
