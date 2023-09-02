--- vue模版编译流程

template -> 语法分析（tokenize） -> 词法分析（parse 得到模版ast）-> transform（模版ast转换成javascript ast）
-> jsAST -> generate（通过jsAST生成渲染函数）-> 渲染函数