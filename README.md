# 知识导入基础编程题

## 实现路径

- 题目1：

  - 1.1：'src/main/java/com/ksyun/whgc/yinruiyi/StringUtils.java'下的 reverse() 函数
  - 1.2：'src/main/java/com/ksyun/whgc/yinruiyi/StringUtils.java'下的 countLetters() 函数
  - 1.3：'src/main/java/com/ksyun/whgc/yinruiyi/StringUtils.java'下的 printMostFrequentLetters() 函数
  - 1.4：'src/main/java/com/ksyun/whgc/yinruiyi/StringUtils.java'下的 longestSubstring() 函数
  
- 题目2：

  - 2.1：

    - 'src/main/java/com/ksyun/whgc/yinruiyi/Student.java'

      定义一个学生类，包括姓名、年龄、住址和出生年月等属性，使用了@Property注解来标注每个属性的名称

    - 'src/main/java/com/ksyun/whgc/yinruiyi/Property.java'

      使用@Retention和@Target注解来指定注解的生命周期和使用范围，并定义了一个name属性来表示属性的名称
    
  - 2.2：'src/main/java/com/ksyun/whgc/yinruiyi/CollectionUtils.java'，定义一个工具类来输出集合对象


------

## 测试方法

- 题目1：

  - 1.1：'src/test/java/TestStringUtils.java'，输入/输出样例：

    ```
    请输入原始字符串：Hello World!
    反转的字符串为: !dlroW olleH
    ```

  - 1.2：'src/test/java/TestStringUtils.java'，输入/输出样例：
  
    ```
    请输入原始字符串：Hello World!
    每个字母出现的次数: { =1, !=1, r=1, d=1, e=1, W=1, H=1, l=3, o=2}
    ```
  
  - 1.3：'src/test/java/TestStringUtils.java'，输入/输出样例：
  
    ```
    请输入原始字符串：Hello World!
    出现次数最多的字母是：l，它出现了 3 次。
    ```
  
  - 1.4：'src/test/java/TestStringUtils.java'，输入/输出样例：
  
    ```
    请输入原始字符串：abbcabcbb
    不含有重复字符的最长子串：bca
    ```
  
- 题目2：'src/test/java/TestStudent.java'，输出样例，students.xlsx文件在Excel中打开：

  | 姓名 | 年龄 |      住址      |   出生年月    |
  | :--: | :--: | :------------: | :-----------: |
  | 张三 |  18  |  北京市海淀区  | 2023年4月20日 |
  | 李四 |  20  | 上海市浦东新区 | 2023年4月20日 |
  | 王五 |  22  |  广州市天河区  | 2023年4月20日 |
  

------

## Git 提交信息

- 提交记录 1：commit id：“@ruiyi0118” <906063940@qq.com>，提交时间：Fri Apr 21 09:02:15 2023 +0800

- 提交记录 2：commit id：“@ruiyi0118” <906063940@qq.com>，提交时间：Fri Apr 21 09:06:04 2023 +0800

- 提交记录 3：commit id：“@ruiyi0118” <906063940@qq.com>，提交时间：Fri Apr 21 09:09:00 2023 +0800

- 提交记录 4：commit id：“@ruiyi0118” <906063940@qq.com>，提交时间：Fri Apr 21 09:15:26 2023 +0800
- 提交记录 5：commit id：“@ruiyi0118” <906063940@qq.com>，提交时间：Fri Apr 21 09:18:57 2023 +0800
- 提交记录 6：commit id：“@ruiyi0118” <906063940@qq.com>，提交时间：
