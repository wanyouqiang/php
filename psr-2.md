### 页面宽度在80字符左右，最大限制在120个字符

### 缩进要使用4个空格，不要使用tab键

### namespace声明命名空间后空一行

### use使用命名空间后空一行

    `
    	namespace Abc\Foo;
    	// 空格
    	use App\Controller;
    	// 空格
    `

### 类名后大括号要单独一行，方法名后大括号也要单独一行

    `
    	// 类后的大括号要单独一行
    	class Book
    	{
    		// 方法后的大括号也要单独一行
    		public function showTitle()
    		{

    		}
    	}
    `

### 控制结构的大括号要与关键字在同一行

    `
    	if (x > 10) {
    		echo "x > 10";
    	}
    `

### 可见性(visibility)必须声明在类与方法的前面, final,abstract必须要放在visibility前面，static放在visibility后面

### 如果一个文件只包含PHP代码，则可以省略?>结束标记符

### 在一行中不能出现多行语句

### 在非空行中不能出现多余的空格

### PHP的关键字必须以小写字母的形式出现，true,false,null等常量也要使用小写字母

### 函数参数之前要以逗号加空格间隔