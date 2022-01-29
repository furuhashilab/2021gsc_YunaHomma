# 2021gsc_YunaHomma
2021年度古橋ゼミ卒論用リポジトリ
© Furuhashi Laboratory/Yuna　Homma, CC BY 4.0
# GIGAスクール端末での地理空間情報系ウェブサイトアクセス可否とホワイトリスト作り

# Introduce
## 概要
### 本研究の内容
本研究ではGIGAスクール端末での地理空間情報系ウェブサイトアクセス可否とホワイトリスト作りを行います。
GIGAスクール構想とは全国の児童1人に1台のコンピュータと高速ネットワークを準備する文部科学省の取り組みであり、ICT技術の進歩による社会変化の流れに合わせて、小中高等学校などの教育現場で生徒がタブレット端末やパソコンを活用できるようにすることが目的です。
構想当初は、2019年度から5年間かけて整備していく予定でした。しかし、現在の整備状況は新型コロナウイルスによる影響でその必要性が高まったことによって、文部科学省の調査では全国の自治体の約95％以上で整備が完了している状況です。
しかし、前倒しになったことも一つの原因として、ICT教育の新たな課題というのも発見されています。例えば、機器整備や、教員の指導力、学習場面において、自治体ごとに異なるため、全国で格差が生まれる懸念があります。また、各自治体によるセキュリティやインターネットの容量と速度等の通信の安定性への課題についても指摘されています。このような課題がGIGAスクール構想にあることを背景として、本研究ではICT端末の格差について行います。先行事例等今までの解決策としては、機器の整備の拡充、負担を軽減しながら教員の指導力向上、柔軟なセキュリティの構築などを結論としており、一方で本研究では、地理空間のウェブサイトに限定し、アクセス可能であるべきものをまとめることが目的になっているからです。


# Method 
①地理系ウェブサイトを検索する。
②Githubで都道県ごとにissueを作り、市町村別にホワイトリストを作成する。その際、サイト名, リンク, ドメインをリスト化する。
③スプレッドシートにGithubの項目を移し、csv形式にする。

# Result
* [Githubの47都道府県ごとのissue](city.ichihara.chiba.jp/article?articleId=60237db4ece4651c88c19043)
* 


# Discussion
自治体のウェブサイトのサーバーを使用しているのは、市区町村の地図、ハザードマップ、施設一覧等、様々な分野の地図が挙げられる。そのため、自治体独自のドメインをもつ地図が多くあった。それらの様々な分野の地図の中で、小中高生に最も見てもらいたいハザードマップを、ホワイトリストとして主にまとめている。
外郭団体が運営する地理系ウェブサイトは、統合型GISなどのプラットフォーム、観光系の2つが多く見られた。統合型GISで多くの自治体が利用しているのが、我が街マップのドメインであった。我が街マップとは
また、自治体のウェブサイトの中でGoogle Mapを活用している場合もあった。

***
# 参考文献
[参考文献スプレッドシート](https://docs.google.com/spreadsheets/d/1uFUYa_TRjZiMx_JMXzDjasGcj1lEG0bK2O0YUADCxdg/edit#gid=0)


***
# 中間発表
[Medium]()
[スライド](https://docs.google.com/presentation/d/1ad8BFHgjr9OBvdUSHbB6M1GC7PNL7rRG1BY1l6NUzFU/edit?usp=sharing)
