## 配列
1. 次の項目について○か×かで答えてください。
 -  配列変数を宣言をすると、自動的に配列の要素が確保される。
 -  配列要素を初期化するにはnew演算子を使う。
 -  配列要素の数は、プログラムを実行する前に決まった数でなくともよい。

2. 次のコードはどこかまちがっていますか? 誤りがあれば、指摘してくださ
~~~ Java
class SampleP2
{
  public static void main (String[] args)
  {
    int [] test;
    test =
    new int [5];
    test[0] = 80;
    test[1] = 60;
    test[2] = 22;
    test[3] = 50;
    test[4] = 75;
    test[5] = 100;
    for (int i=0; i<5; i++) {
      System.out.println((i+1) + "番目の人の点数は" + test [i] + "です。");
    }
  }
}
~~~

3.次の実行結果となるように、ア~キから選んでコードを完成してください。
~~~ Java
class SampleP3
  public static void main(String [] args)
  {

  }
~~~
