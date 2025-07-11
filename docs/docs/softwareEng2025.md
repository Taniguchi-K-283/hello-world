---
layout: page
title: "software Eng. lecture note
permalink: /docs/docs/softwareEng2025
---

<!-- これまでに学んだソフトウェア工学の内容をまとめる -->
はじめに、ソフトウェア工学とは、「品質」、「コスト」、「納期」の最適なバランスを実現するための手法・方法論のことである。
コードを記述する技術であるプログラミングとは違い、ソフトウェア工学は主に開発コストや、スケジュール調整を取り扱う。IT人材の不足やDXの推進などにより、ソフトウェア工学の重要性は高まってきている。

次に、実際のソフトウェア開発の流れを説明する。
まずはじめに必要なのは要件定義である。要件定義には、作成するシステムの目的や機能だけでなく、運用の方法や開発スケジュールなども含まれており、プロジェクト全体の流れを明らかにするという目的がある。実装する機能と実装しない機能を明らかにしたり、プロジェクトの関係者と円滑に開発を進めたりするために必要である。
実際に開発を進めるにあたって、開発中のソフトウェアを評価する手法も存在する。品質（Quality）、コスト（Cost)、納期（Delivery)の頭文字をとったQCDは、そのソフトウェアが使用される場面において優先される部分に重きを置くという考え方である。他にも、ソフトウェアの品質やバグに関係する「Hyrumの法則」や、必要な機能が見えてきた段階でシステム規模を概算することができるファンクションポイント（FP）法もある。
ソフトウェアの開発プロセスはおおまかに、４つの型に分けられる。
ウォーターフォール型は順番にプロセスを進めていく手法で進捗管理が容易、成果物が明確というメリットがあるが、機能追加や要件変更が行われてしまった場合には後工程にしわ寄せが集中してしまうというリスクもある。
スパイラルモデルはプログラム開発を小さなフェーズに分割して、フェーズごとにプロトタイプによるデモンストレーションを行いフィードバックを得て、次のプロセスに反映するという手法でプロトタイプ作成に想定外の作業量が発生するリスクが存在する。
反復型はソフトウェアを機能分割し、これを「反復」と呼ぶ単位で管理するという、積み上げ方式の開発手法で、部分的に完成させていくので顧客の要求を取り入れやすく、部分的な納品が可能というメリットがあるが、分割のための作業や管理業務が増えるたり、全体像が見えづらいといったデメリットもある。
アジャイルプロセスは変化に対応して無駄を廃し、最適な手法で動くソフトウェアの提供を優先するという開発方法であるで、ウォーターフォール型開発プロセスでは想定されていなかったできるだけ決定を遅らせて、できるだけ早く提供することを実現している。

また、開発スケジュールの管理も重要である
WBSはWork Brakedown Structureの略でプロジェクト目標を達成し、必要な要素成果物を生成するために、プロジェクトチームが実行する作業を、要素成果物を主体に階層的に要素分解したものである。プロジェクトを細かな作業（Work）に分解（Breakdown）した 構成図（Structure）のことであり、作業を細かく分解し作業順に並べるという方法である。
スコープが明確になり、やらない作業とやるべき作業が洗い出せることが大きなメリットであり、プロジェクト実施時はWBSに則り実行するのみなので、円滑に進めることができる

以上のようにプロジェクトの開発、管理には様々な手法が用いられているのである。