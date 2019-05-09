```flow
st=>start: 画面入力
e=>end: 画面出力
op1=>operation: 入力チェック
cond=>condition: Yes
or No?
op2=>operation: データ登録
para=>parallel: エラーメッセージ

st->op1->cond
cond(yes)->op2->e
cond(no)->para
para(path2)->e


```

