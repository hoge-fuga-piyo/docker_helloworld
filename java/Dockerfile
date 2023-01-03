FROM eclipse-temurin:17.0.5_8-jdk

# 作業用のディレクトリを作成
WORKDIR /work

# ローカルのHelloWorld.javaというファイルをDockerコンテナ上の作業用ディレクトリにコピー
COPY ./HelloWorld.java /work

# コンパイル
RUN javac HelloWorld.java

# 実行
CMD java HelloWorld