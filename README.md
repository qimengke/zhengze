# zhengze
正则表达式

 var _str="artyy6";
 var _reg=/^ar{2}t+y{2}6$/g;
 alert(_reg.test(_str));//test方法返回值为boolean类型。符合条件则返回true,否则返回false;test方法是正则表达式对象的方法。
 

 
 
 
  var _str="abce1234abce56";
   var _reg=/abce/;//正则表达式的写法,/......../
 alert(_str.match(_reg));//match方法的返回值:数组类型的元素集合;没有匹配结果的时候返回null
  alert(_str.split(/1234/));//split方法的参数可以是字符串类型分割符,也可以是符合某个规则的正则表达式
