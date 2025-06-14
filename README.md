猫が猫であるように、犬が犬であるように、全身全霊、僕でありたい。

# 使用技術
## Front-end
- ✅Flutter: SubaruがGoogleの技術になれることが出来る; Mobile展開がしやすい
- React/Next.js: 既に存在するコードが使える
- Svelte
## Back-end
- ✅Firebase: SubaruがGoogleの技術になれることが出来る; Google OAuth, Flutterとの相性がよさそう; 安そう
- NestJS
- Cloudflare?
## Web-app deployment
- Vercel
- Cloudflare
- GCP

# 機能
- 時間割
- 検索
  - お気に入り授業リスト
- ログインで時間割を保存: Google OAuth?
  - 成績分布などもICU Net IDで認証済みの人のみに提供する．
- 学生による授業評価
  - 単位の取りやすさだけでなく，ディスカッショントピックの与えられ方，課題とコース目標の一貫性，評価方法の透明性や授業外部でのサポート体制など，学生目線で多面的に評価．
  - 評価項目は，flutter ver.1 release後にsurveyしたり，事前のユーザ調査と先生や他大学の類似システムと比較する．
  - core valueは「取りやすい単位を取る」でなく，「各学生が学びたいことにまっすぐに向き合うための手伝いをする」．先生のやる気が無い授業などが，学生の率直な意見から明らかになるように．その際，公開されているTESのデータも参照する．
  - アカデミアでの4年間の最良のパートナーでありたい
- 成績分布
- 次の授業と場所をプッシュ通知
- 友達と時間割を共有？
- 空き教室検索：open data
- 多言語対応？: i18n

# TODOs
- [ ] [Flutter Tutorial](https://codelabs.developers.google.com/codelabs/flutter-codelab-first#0)を'完全に理解'する
- [ ] ClearなPrivacy Policy：他のICU生にも役立つデータ活用を．いかなる場合でも学生から収集したデータを売らない！データのアクセス権を明確に．

# 参考に出来そうなサイト
- [NUSMods](https://nusmods.com/timetable/sem-2)
- [Berkeley Time](https://berkeleytime.com)
- [Twin:te](https://app.twinte.net/)
