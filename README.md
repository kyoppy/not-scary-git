# こわくない 「確定申告」
## このテキストの目的
- 対象者
    - 確定申告を初めて行う人
    - 慣れていない人
    - 毎年やってるけど、よく分かってない人
- ゴール
    - 自分自身で確定申告が行えるようになる
    - 正しい節税で、確定申告における納税額を減らす
- GitHubで管理する理由
    - GitHubの差分管理を活用し、久しぶりに見たときに変更点を分かりやすくする
    - 記述が正しくない箇所をFork & pull-requestでみんなで改善していけるようにするため

## 確定申告の概要
- 確定申告とは?
    - 以下のことを行うイベント
        - 1.事業の収益を算出
        - 2.収益を元に、支払う所得税と消費税を算出
        - 3.所得税と消費税を支払う
- 確定申告の時期
    - 2月16日 ~ 3月15日 (土日祝の場合は翌営業日)
    - 所得税法 第120条 で定められている

- 1回の確定申告における領収書・請求書の有効期間 : 1月 ~ 12月
    - 【例】2025年3月に確定申告を行う場合 : 2024年1月 ~ 2024年12月

## 時期別のイベントリスト
|時期|イベント|
|:--|:--|
|**なるはや** ※やっていない人のみ|e-Taxのアカウント作成 ([解説](./content/e-tax.md#Taxのアカウント作成方法))|
|**なるはや** ※やっていない人のみ|ねんきんネットのアカウント作成 ([解説](./content/nenkin.md#ねんきんネットのアカウント作成))|
|**なるはや** |マイナンバーカードの電子申請ができるかを確認 ([解説](./content/mynumber.md#マイナンバーカードの電子申請ができるかを確認する方法))|
|1月 ~ 12月|領収書を会計システムに登録|
|1月 ~ 12月|収入を会計システムに登録|
|12月末|健康保険料の納付証明書が届く ([解説](./content/hoken.md#12月末に届く納付証明書))|
|12月末|ねんきんネットから国民年金の控除証明書を発行 ([解説](./content/nenkin.md#ねんきんネットから控除証明書を発行する方法))|
|翌年 1月|税務署からの書類が届く ([解説](./content/zeimu.md#1月に税務署から届く確定申告に必要な資料))|
|翌年 1月 ~ 2月|会計システムで確定申告の資料を作成 ([解説]())|
|翌年 2月中旬 ~ 3月中旬|e-tax経由で確定申告の資料を提出 ([解説]())|

## 控除
- 控除とは?
    - 所得税や住民税の負担を軽減する仕組み
- 控除の種類
    - 所得控除 : 総所得から所得控除を差し引くことで課税対象額を現象させる
        |控除の種類|概要|
        |:--|:--|
        |[基礎控除](./content/kojo.md#基礎控除)|すべての納税者が受けられる控除|
        |[配偶者控除と配偶者特別控除](./content/kojo.md#配偶者控除と配偶者特別控除)|配偶者(一定の所得以下)がいる場合の控除|
        |[扶養控除](./content/kojo.md#扶養控除)|扶養親族がいる場合の控除|
        |[医療費控除](./content/kojo.md#医療費控除)|1年間の医療費が一定額を超えた場合の控除|
        |[社会保険料控除](./content/kojo.md#社会保険料控除)|健康保険・年金などの支払い分を控除|
        |[生命保険料控除](./content/kojo.md#生命保険料控除)|生命保険や個人年金の支払い分を控除|
        |[地震保険料控除](./content/kojo.md#地震保険料控除)|地震保険の支払い分を控除|
        |[寄附金控除](./content/kojo.md#寄附金控除)|ふるさと納税や特定の寄付をした場合の控除|
        |[小規模企業共済等掛金控除](./content/kojo.md#小規模企業共済等掛金控除)|小規模企業共済等掛金控除に支払った金額を全額控除にできる|
        |[青色申告特別控除](./content/kojo.md#青色申告特別控除)|特定の条件を満たして青色申告を行った場合に受けられる控除|
        
    - 税額控除 : 計算された税額そのものを直接差し引く (所得控除より効果的)
        |控除の種類|概要|
        |:--|:--|
        |[住宅借入金等特別控除](./content/kojo.md#住宅借入金等特別控除)|住宅ローンを利用して家を購入した場合に一定額を控除|
        |[配当控除](./content/kojo.md#配当控除)|上場株式などの配当所得に対する税額控除|
        |[外国税額控除](./content/kojo.md#外国税額控除)|海外で税金を支払った場合、日本の税額から控除|
        |[政党寄附控除](./content/kojo.md#政党寄附控除)|政党や政治団体への寄附をした場合に適用|
## 経費
- 概要
    - 仕事で使用するために必要な支出
    - 確定申告の所得税を計算する際に売上から引くため、節税効果がある
- 経費とする場合の基本ルール
    - 仕事に必要な経費であること ※ 仕事との関連性があればOK
    - 領収書・レシートを保存すること
        - 保存期間
            - 青色申告の場合 : **7年**
            - 白色申告の場合 : 5年
    - 適正な割合で按分(あんぶん)すること
        - 家賃や電気代など、私生活と共同の部分は仕事で使用した割合で計上する
- 経費にできないもの
    - 個人の税金
        - 例 : 所得税、住民税、健康保険料
    - 罰金や反則金
    - 私生活に関する支出
- 経費の例
    ||控除とする際のカテゴリー<br>(勘定科目)|経費としての<br>按分割合の例|
    |:--|:--|--:|
    |電車賃|旅費交通費|10割|
    |仕事に関係する外食|交際費|10割|
    |家賃|地代家賃|5割|
    |電気代|水道光熱費|5割|
    |携帯通信費|通信費|5割|
    |自宅のネット料金|通信費|5割|
    |ホームページサーバー利用料金|通信費|10割|
    |メールサーバー利用料金|通信費|10割|
    |Googleドライブ追加料金|通信費|10割|
    |会計ソフト利用料|通信費|10割|
    |仕事用PC購入費用|工具器具備品|10割|
    |仕事用PC用マウス購入費用|工具器具備品|10割|
    - 注意
        - 仕事に使う場合でも、衣類は基本的に経費にできません。
            - 参考 : [マネーフォワード 衣装代の経費について](https://biz.moneyforward.com/accounting/basic/64462/#i-6)
## 収める所得税の計算方法
1. 課税所得の算出
    ```
    課税所得 = 総所得金額 - 経費 - 所得控除の合計
    ```
2. 収める所得税を算出 part1
    ```
    収める所得税 =  課税所得 × 所得税率 - 控除額
    ```
    - 所得税率
        - 概要
            - 課税所得の金額で決まる
        - 早見表
            |課税所得金額|税率|控除額|
            |:--|--:|--:|
            |1,000円 ~ 194万9,000円|5%|0円|
            |195万円 ~ 329万9,000円|10%|9万7,500円|
            |330万円 ~ 694万9,000円|20%|42万7,500円|
            |695万円 ~ 899万9,000円|23%|63万6,000円|
            |900万円 ~ 1,799万9,000円|33%|153万6,000円|
            |1,800万円 ~ 3,999万9,000円|40％|279万6,000円|
            |4,000万円 ~ |45％|479万6,000円|
        - 大事なポイント
            - 控除を活用して、課税所得金額をなるべく最大になるようにして、収める所得税を少なくする
                - 例えば、 課税所得が200万円なら、控除を活用して194万9,000円以下に収めた方がお得
3. 収める所得税を算出 part2
    ```
    収める所得税 =  収める所得税 - 税額控除の合計
    ```
- メモ : 収める所得税は、所得税額ともいう
## 節税の一例
- 一般的な節税
    - e-Taxでの確定申告を行う ([青色申告特別控除](./content/kojo.md#青色申告特別控除))
    - 小規模企業共済に加入する ([小規模企業共済等掛金控除](./content/kojo.md#小規模企業共済等掛金控除))
- 経費に関する節税
    - PCなどが30万円未満の場合は、「少額減価償却資産特例」を活用することでその年だけで減価償却を行える ([解説](./content/zeimu.md#少額減価償却資産の特例))
## Q&A

## その他
- 更新履歴の確認は [コチラ](https://github.com/kyoppy/dont-be-afraid-of-git/commits/main/) から ([操作方法](./content/github.md#GitHubの変更履歴を確認する方法))
- 改修を依頼する場合は [コチラ](https://github.com/kyoppy/dont-be-afraid-of-git/issues) から ([操作方法](./content/github.md#GitHubから改修を依頼する場合))