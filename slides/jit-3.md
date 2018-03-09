##  JITコンパイラ

* Just in Time Compiler: その場でコード生成する
  * インタプリタの即時実行性
  * コンパイラの実行効率
  * インタプリタとコンパイラのいいとこ取り
* 歴史的には Java→Javascript と研究の主戦場が移った
* **LLVM で JIT を実装する**のが今の流行
  * BEAMはコード生成でLLVMを利用している