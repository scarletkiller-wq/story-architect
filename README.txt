Story Architect v0.5 PWA — iPad / PC 対応

【重要】このZIPはPWA配布用の一式です。
index.htmlだけを開いてもPWAとしてインストールできません。
公開URLをHTTPSで配信する必要があります。

【無料公開例：GitHub Pages】
1. GitHubで新しいリポジトリを作成（公開時はPublic）。
2. ZIP内の index.html, sw.js, manifest.webmanifest, icons フォルダを同じ階層にアップロード。
3. Settings > Pages > Build and deployment > Deploy from a branch を選択。
4. Branch: main / (root) を指定して保存。
5. 表示された https://<ユーザー名>.github.io/<リポジトリ名>/ をiPadのSafariで開く。
6. Safariの共有メニューから「ホーム画面に追加」を選択。
7. いちどオンラインで起動し読み込みを完了すると、オフラインで再起動可能。

【プロジェクトの取り扱い】
データは各端末・各サイトURL内のブラウザ保存領域に保存されます。
PCとiPadのデータは自動同期されません。
旧版HTMLのプロジェクトを移行するには旧版で「書出」→新版で「読込」。
定期的にJSON書出をしてバックアップしてください。
保存領域はブラウザの設定や空き容量などで消える可能性があります。

【セキュリティ】
GitHub PagesをPublicで利用する場合、アプリのプログラムは公開されます。
作品データは本人が明示的に公開・アップロードしない限り自動では公開されません。

【更新】
新バージョンを同じURLにアップロードしSafariで再読み込みします。
オフラインキャッシュが残る場合はSafariでオンライン再読込してください。
