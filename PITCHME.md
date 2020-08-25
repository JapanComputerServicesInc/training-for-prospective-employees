# 2020/08/26
## インターンシップ

---

### 今日やること😇

- LINE Botを使ってチャットボットをつくろう💪 |

---

### チャットボットって何🤔？

- なんか送ったらなんか返してくれるやつ |

+++

### 例えば

- [LINEで使えるチャットボット15選。トーク画面でピザ注文や再配達依頼ができる！](https://mag.app-liv.jp/archive/64844) |

---

### そんな簡単に作れるの😯？

- つくれます😇 |

---

### どんなものを作るの😣？

- あなたのやることを教えてくれるチャットボット🤗 |

---

### どんなものを作るの😣？

- 1. やりたいことをあらかじめいくつか登録しておく |

- 2. チャットボットに「今日何すればいい？」と質問する |

- 3. 1.で書いたやりたいことのいずれかをBotが返してくれる |

---

### 全体のイメージ

<img src="https://crowi.jcslabs.net/uploads/attachment/5d91998448525b4b3e33564d/4dce076993cf55a04fec408a9650e025.png" style="max-width: 100%;">

---

## やってみよう！

---

### 1. スプレッドシートにやりたいことを書く

+++

- 「スプレッドシート」と検索して、一番上に出てきたリンクをクリック

<img src="https://crowi.jcslabs.net/uploads/attachment/5d91998448525b4b3e33564d/7ab595b5f24fa56a4d4221dd21690912.png" style="max-width: 80%;">

+++

- A列の一番上から下に向かってやりたいことを3つ書く

<img src="https://crowi.jcslabs.net/uploads/attachment/5d91998448525b4b3e33564d/abced4f6160ac7a48b3c8209d8541b5d.png" style="max-width: 80%;">

+++

- D1のセルに 「`=TEXTJOIN("、",TRUE,A:A)`」 と入力する
  - A列に書いたやりたいことが読点（、）区切りで表示される |

<img src="https://crowi.jcslabs.net/uploads/attachment/5d9235ff48525b4b3e335658/e9af860aa52e7b9c3c945830c75b686f.png" style="max-width: 80%;">

---

### 2. LINE Botとともだちになる

+++

- 別途配布するQRコードを読み取って友達登録する

---

### 3. Google Apps Scriptを開く

+++

- 「ツール」 => 「スクリプトエディタ」をクリック

<img src="https://crowi.jcslabs.net/uploads/attachment/5d91998448525b4b3e33564d/2f68c517c1dac56e9bfa6cbb68b0066a.png" style="max-width: 80%;">

+++

- 今日はここでプログラミングをします
  - プログラミングまでもう少し! |

---

### 4. Google Apps Scriptの場所をLINE Botに教える

+++

- 「公開」 => 「ウェブアプリケーションとして導入...」をクリック

<img src="https://crowi.jcslabs.net/uploads/attachment/5d91998448525b4b3e33564d/03880ba1027b3dedc4f10fbb8c2b301d.png" style="max-width: 80%;">

+++

- 適当なプロジェクト名を入力してOKをクリック

<img src="https://crowi.jcslabs.net/uploads/attachment/5d91998448525b4b3e33564d/84f6fb9e595a28d5cd8f509fdf380b8a.png" style="max-width: 80%;">

+++

- 「Who has access to the app:」を「Anyone, even anonymous」にして「Deploy」をクリック

<img src="https://i.imgur.com/7GLDUAc.png" style="max-width: 60%;">

+++

- 「Current web app URL」を教えて下さい

<img src="https://i.imgur.com/6lMuv6k.png" style="max-width: 80%;">

--- 

### . Let's プログラミング！
- 詳細は別資料で👋 |

---
