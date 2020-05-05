.. title: First Post by Nikola
.. slug: first-post-by-nikola
.. date: 2020-05-05 00:25:44 UTC+09:00
.. tags: 
.. category: tool
.. link: 
.. description: Nikolaのテスト
.. type: text


概要
-----

段落１のテスト
あいうえお


段落２のテスト
かきくけこ

サンプルコード
```
print('hello world')
```

Webサーバの仕組み
--------------------

1. これはNikolaのテストです

   段落１のテスト
   あいうえお

   段落２のテスト
   かきくけこ

   サンプルコード

   This is a simple examples:
   ::

      res = []
      for entry in entries:
         title = entry['title']
         pub = entry['published'] if entry.get('published', None) else entry.get('updated', None)
         pub = pub[ : pub.find('T')] if pub.find('T') >= 0 else pub
         res.append([title, pub])

      res = sorted(res, key=lambda item: item[1], reverse=True)
      res = res[:int(max_num)]

      for item in res:
         print(f'{item[1] if item[1] else ""} / {item[0]}')


2. 箇条書きのテスト

   1. 項目１
      最初にUbuntuをセットアップする
      仮想マシン上で作業する

      .. image:: /images/frontispiece.jpg

   2. 項目２
      Webサーバをセットアップする


3. bulleted listのサンプル

   - Server
     + Web Server
     + AE Server
   - Frontend

終わりに

