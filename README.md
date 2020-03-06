Python基础
1.1 标识符
  第一个字符必须是字母表中字母或下划线 _ 。
  标识符的其他的部分由字母、数字和下划线组成。
  标识符对大小写敏感。
  注：关键字不能用作标识符名称（Python中的关键字有['False', 'None', 'True', 'and', 'as', 'assert', 'break', 'class', 'continue', 'def',    'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or',  'pass', 'raise', 'return', 'try', 'while', 'with', 'yield'])
1.2 注释
  Python中单行注释以#开头，多行注释可以用多个 # 号，还有 ''' 和 """。
1.3 行与缩进
  python中使用缩进来表示代码块，不需要使用大括号 {} 。缩进的空格数是可变的，但是同一个代码块的语句必须包含相同的缩进空格数，否则会出错。
1.4 数字类型
  python中数字有四种类型：整数、布尔型、浮点数和复数。
  int (整数), 如 1, 只有一种整数类型 int，表示为长整型。
  bool (布尔), 如 True。
  float (浮点数), 如 1.23、3E-2
  complex (复数), 如 1 + 2j、 1.1 + 2.2j
1.5 字符串
  python中单引号和双引号使用完全相同。
  使用三引号('''或""")可以指定一个多行字符串。
  转义符 '\'
  反斜杠可以用来转义，使用r可以让反斜杠不发生转义。 如 r"this is a line with \n" 则\n会显示，并不是换行。
  按字面意义级联字符串，如"this " "is " "string"会被自动转换为this is string。
  字符串可以用 + 运算符连接在一起，用 * 运算符重复。
  Python 中的字符串有两种索引方式，从左往右以0开始，从右往左以-1开始。
  Python中的字符串不能改变。
  Python 没有单独的字符类型，一个字符就是长度为 1 的字符串。
  字符串的截取的语法格式如下：变量[头下标:尾下标:步长]。
