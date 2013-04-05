daisuke-archetype-quickstart
============================

What is this?
-------------

各種Eclipseの設定ファイルも含む、Javaプロジェクトのひな形を生成するためのApache Maven用archetypeです。

- pomに汎用的なライブラリを自動設定します。(Google guava / slf4j等)
- Spring, Hibernate
- Eclipseコンパイラやコードフォーマッタ等の設定
- eclipse-cs (Checkstyle) や Findbugs の設定


How to use?
-----------

- [Maven release repository](http://maven.xet.jp/release/)
- [Maven snapshot repository](http://maven.xet.jp/snapshot/)

    mvn3 archetype:generate \
        -DarchetypeRepository=http://maven.xet.jp/release \
        -DarchetypeGroupId=jp.xet.archetype \
        -DarchetypeArtifactId=daisuke-archetype-quickstart \
        -DarchetypeVersion=1.4 $*

