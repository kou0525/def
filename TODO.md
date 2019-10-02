関数：コードの再利用
その1: "hello world" と出力するだけの関数
引数なし
返り値なし
def hello():
    print("hello world")

その2:
引数あり
返り値なし
def say_hello(name):
    print(f"Hi {name}")

say_hello("Bob") # Hi Bob
say_hello("Tom") # Hi Tom