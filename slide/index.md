---
marp: true
title: "weeklyOSM編集の裏側"
author: "三浦広志"
date: "2025-02-15"
institute: "State of the Map Japan 2024"
theme: gaia
---

<!-- スライド1: タイトル -->

![bg right:40% 80%](images/Logo_weeklyOSM.svg)

# weeklyOSM編集の裏側
## State of the Map Japan 2024
### 三浦広志

---

<!-- スライド3: OpenStreetMapとは -->

# OpenStreetMapとは

- **オープンな地図データ**を提供するプロジェクト
- 2004年に**スティーブ・コースト**により設立
- **商業地図とは異なり**、オープンソースの原則に基づく
- **誰でも編集・利用が可能**
- **災害支援や発展途上国の地図整備**にも貢献
- GISやアプリケーション開発に活用

---

<!-- スライド4: 講演者について -->

# 講演者について

- **三浦広志**
    - 一般社団法人 OSMF Japan 代表理事
    - 2007年から日本でOSMの普及活動を開始
    - **翻訳ツールOmegaTのリード開発者**
    - 2022年よりweeklyOSMの編集・翻訳に参加

---

<!-- スライド5: 週刊OSMの目的 -->

# 週刊OSMの目的

- **OSMの最新ニュースを提供**
- 経験者から初心者まで**すべてのOSMメンバー向け**
- **ボランティアによる多言語発信**
- **年間52号 (休みなし) の発行**
- 週刊OSM: https://weeklyosm.eu/

---

<!-- スライド6: 講演の流れ-->

# 週刊OSMのからOpenStreetMapの動向を振り返る

- エポック的な記事
- **今週の画像**
- 編集プロセスを紹介
- 記事になる情報とならない情報とは

---

<!-- スライド7: 取り上げる記事 -->

# WeeklyOSMの記事ハイライト

1. **TomTomがOSM20周年を祝うビデオ公開**
2. **Organic Mapsの4周年**
3. **週刊OSMが10周年を迎える**
4. **ハザードマップゲーム「守れ！サイガイ防衛隊」**
5. **OSM20周年記念記事の紹介**

---

<!-- スライド8: 取り上げる画像 -->

# 印象的な冒頭写真

![State of the Map 2024 集合写真](https://weeklyosm.eu/wp-content/uploads/2024/09/739_all.jpg)

- 2024年9月発行の週刊OSM 739号の「今週の画像」
- **アフリカ・ナイロビで開催されたSotM 2024の集合写真**
- **世界中のOSMメンバーが一堂に会する貴重な場**

---

<!-- スライド9: 記事の編集について -->

# 記事の編集について

- **OSMBC (OpenStreetMap Blog Compiler) を使用**
- **読者や編集者がニュースを投稿**
- **編集者が英語で記事を作成**
- **翻訳者が多言語へ翻訳**
- **毎週日曜日に公開**

---

<!-- スライド10: 記事の編集プロセス図 -->

# 記事の編集プロセス

<div class="mermaid">
graph TD;
  A[ニュースの投稿] -->|OSMBCに登録| B[編集者が英語記事を作成];
  B -->|各国翻訳者が翻訳| C[多言語版記事の作成];
  C -->|推敲と修正| D[最終記事の確定];
  D -->|日曜日に公開| E[週刊OSM発行];
</div>

---

<!-- スライド11: 結論 -->

# 結論

- **週刊OSMはOSMの重要な情報源**
- **多言語での編集は、コミュニティの協力で成り立つ**
- **OpenStreetMapの成長と共に、週刊OSMも発展**
- **記事の投稿・編集にぜひ参加してください！**

---

<!-- スライド12: 連絡先 -->

# 連絡先

- **weeklyOSM**: https://weeklyosm.eu/
- **OSMF Japan**: https://www.osmf.jp/
- **三浦広志**
    - Email: info@osmf.jp
    - Twitter: @miurahr

<!-- Add this anywhere in your Markdown file -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>
