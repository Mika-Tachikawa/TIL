# cloud9でJavaを開発するときのためのメモ

## ファイル名
〇〇.java<br>

## 基本のコード（cloud9にかぎらず）
  public class Hello {<br>
    public static void main (String[] args) {<br>
      System.out.println("表示したい内容");<br>
    }<br>
  }<br>

## コンパイル
~/environment/ $ javac ディレクトリ名/〇〇.java<br>

## 実行
~/environment/ $ java ディレクトリ名.〇〇(コンパイルしたファイル名)<br>
~/environment/ディレクトリ名 $ java 〇〇(コンパイルしたファイル名)<br>
