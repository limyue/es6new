es6新增知识
1.let定义变量
  const定义常量
2.模板字符串
  ·常量${变量}常量·
3.参数默认值
  function show(a,b=5){}
4.箭头函数
  var show=(a,b=5)=>(a+b)
5.函数this
  指的函数定义时的this
6.对象的编写
  var a=3;
  var obj={
    a,
    b(){}
  }
  var obj2={
    c=4
  }
  Object.assign(obj2,obj);
  console.log(obj2);
  console.log(Object.keys(obj2));
