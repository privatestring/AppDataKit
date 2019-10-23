# HashMap浅析
   `HashMap`允许key和value都为null，非线程安全,无序的集合

### 储存方式
   1. 长度8以下为链表储存，8以上为红黑树
   2. `负载因子`：当达到`size*负载因子` 时会进行扩容 `2^n`

# LinkedHashMap浅析
   `LinkedHashMap`是继承 `HashMap` ，解决`HashMap`无序的问题，非线程安全

# TreeMap浅析
   `TreeMap` 是有序的红黑树储存，key不能为空