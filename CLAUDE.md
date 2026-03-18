# 70_WordPress_Codejump_grid 進捗メモ

## 📅 2026-03-18 時点の進捗

### ✅ 完了済み（HTML/CSS）
- `index.html`：トップページ（商品8件グリッド）
- `view_more.html`：商品一覧ページ（12件）
- `detail.html`：商品詳細ページ（画像＋テキスト横並び）
- `about.html`：Aboutページ
- `company.html`：Companyページ（dl/dt/dd ＋ Googleマップiframe）
- `css/work.css`：スタイル全体

### ✅ 完了済み（WordPress環境）
- Local でサイト作成済み（サイト名：phpcodejumpgrid）
- `wp-content/themes/fd/` にテーマフォルダ設置済み
- `themes/fd/style.css`：Theme Name コメント記載済み
- `themes/fd/index.php`：空ファイルで作成済み
- テーマ有効化済み

### ➡ 次にやること（WordPress統合）
1. `header.php` を作る（index.html の `<head>〜</header>` 部分を切り出す）
2. `footer.php` を作る
3. `functions.php` を作る（CSS/JS読み込み）
4. `index.php` をWordPressループに変換
5. `category.php` を作る
6. `single.php` を作る
7. `page.php` を作る

### 📁 参考ソース（見本）
- `source/` フォルダ内に完成形のPHPファイルあり
- Local 管理画面：`http://phpcodejumpgrid.local/wp-admin`
