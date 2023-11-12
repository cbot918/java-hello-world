# Java Hello World

0. 安裝一下 JDK8, JRE8 (有可能這兩個是一次裝好, 或是 java11 java17 應該都 ok, 反正先有再說 xD), 設定一下 JAVA_HOME (可參考網路教學)

   0.1 `javac -version` 看一下 編譯器版本

   0.2 `java -version` 看一下 runtime 版本

1. vscode 先裝 java 的 extension ( 找最多的那個裝 )

2. Hello World 流程

   2.1 開個 Main.java

   2.2 輸入 hello world 程式碼 ( 可參考檔案 helloworld.md )

   2.3 編譯指令 `javac Main.java`

   2.4 執行指令 `java Main`

   2.5 正確執行出有 Hello World 就 ok

3. 練習做個 module

   3.1 `mkdir src`

   3.2 在 src folder 裡面開個 Hello.java

   3.3 放入 Class Hello 的內容( 參考 src/Hello.java )

4. Main.java import module

   4.1 加個 `import src.Hello` (參考 1)

   4.2 創建物件 hello

   4.3 call 函式 Cheer()

   4.4 javac Main.java

   4.5 java Main

   4.6 成功輸出文字 就成功啦！
