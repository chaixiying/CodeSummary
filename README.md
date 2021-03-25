## 记录编程的机会 经验 新学到的知识
# map.getOrDefault(key， defaultValue)方法
  从map中根据键key获得对应的值，若没有键值对，则返回一个设置的默认值
![image](https://user-images.githubusercontent.com/60838780/112316131-c8d90f80-8ce5-11eb-8d04-5947dc2df2f0.png)
# 多次循环下需要判断变量是否每次都要初始化
![image](https://user-images.githubusercontent.com/60838780/112316267-e6a67480-8ce5-11eb-9e93-88f22135c6cc.png)
答案是只创建一次对象，因为String类型在java中被设定为一旦创建就不可改变类型，对String类型的改变，都是创建新的String类型。
既然String类型的量是不能改变的，因此可以在进行编译的时候就将其放入字符串常量池中。题目中，三个已经确定的字符串在进行编译的时候就被合并并放入了常量池中，因此只创建一个对象。
# 链表
![image](https://user-images.githubusercontent.com/60838780/112478795-53d20c80-8daf-11eb-9c19-16e91ce91a7e.png)
1)对链表进行遍历的时候，一定要保证所有结点的next属性之前的对象不为空，对多个链表进行遍历在判断条件中一定是“&&”符号。
2)引用数据类型内部存的是地址，将一个引用数据类型赋值给另一个的时候，被赋值的引用数据类型，就指向之前的地址所代表的内容。因此这两个类型完全相同，修改一个地址对对应内容的同时另一个也会随之修改。
3)建立链表时一般需要建立一个头节点，该头节点内部只存储下一个结点的地址，不存储数据

