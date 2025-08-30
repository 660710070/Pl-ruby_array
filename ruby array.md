# What is Ruby Array 
Array เป็นโครงสร้างข้อมูลชนิดหนึ่ง สามารถใช้เก็บหลายตัวแปรได้ ซึ่งข้อมูลข้างในจะเป็นประเภทเดียวกันหรือหลากหลายประเภทก็ได้ 
### Example
```ruby
b = [1,2,"A",true]
print b
```
<details> <summary>Output</summary>
[1, 2, "A", true]
</details>

# How to Creat a Ruby Array
## วิธีสร้าง Array แบบธรรมดา Ruby
```ruby
a = [1,2,3,"Cat"]
print a
```
<details> <summary>Output</summary>
[1, 2, 3, "Cat"]
</details>

### Example ภาษาอื่นๆ
ภาษา python
```python
ar_ray = [1,"hello",3.14,True]
```
<details> <summary>Output</summary>
[1, 2, 3, "Cat"]
</details>

ภาษา C

```C
int myNum[] = {25,50,75,100};
char fruits[2][10] = {"apple","banana"};
```
ภาษา Java

```Java
int[] nums = {1,2,3};
String[] fruits = {"apple","banana"};
```
## วิธีสร้าง Array แบบว่างเปล่า Ruby
```ruby
my_lovely1 = []
print my_lovely1
```

<details> <summary>Output</summary>
[]
</details>

```ruby
my_lovely2 = Array.new
print my_lovely2
```

<details> <summary>Output</summary>
[]
</details>

```ruby
arr1 = Array.new(3)
print arr1
```

<details> <summary>Output</summary>
[nil,nil,nil]
</details>

```ruby
arr2 = Array.new(3,0)
print arr2
```
<details> <summary>Output</summary>
[0,0,0]
</details>

### Example ภาษาอื่นๆ
ภาษา python
```python
arr = []
print(arr)
```

<details> <summary>Output</summary>
[]
</details>

ภาษา C

```C
ไม่มีอาเรย์ว่างเปล่าโดยตรงต้องสร้างแบบกำหนดเอา
int c[3]={0, 0, 0};
for (int i = 0; i < 3; i++) {
    printf("%d ", c[i]);
}

<details> <summary>Output</summary>
0,0,0
</details>

```
ภาษา Java

```Java
import java.util.Arrays;
int[] arr new int[0]
System.out.println(Arrays.toString(arr));
```
<details> <summary>Output</summary>
[]
</details>

