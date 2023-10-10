# Leetcode-review

## 各种初始化
### 初始化 Hashmap
**创建一个空的Hashmap**  
Map\<Character, Integer> map = new HashMap<>();

### 初始化 HashSet
**创建一个空的HashSet**  
Set\<Integer> set = new HashSet<>();

### 初始化 Array
**创建一个空的Array**  
int[] number = new int[5];
	
### 初始化 Stack
**创建一个空的Stack**  
Stack\<Character> stack = new Stack<>();
	
### 初始化 Queue
**创建一个空的Queue**  
Queue\<String> queue = new LinkedList<>();

### 初始化 StringBuild  
**创建一个空的StringBuilder**  
StringBuilder string = new StringBuilder();  
string.append("a");

### 初始化 linkedList	
**创建一个空的linkedList**  
LinkedList\<Integer> linkedList = new LinkedList<>();  
**创建一个带有初始元素的linkedList**  
LinkedList\<String> linkedList = new LinkedList<>(Arrays.asList("element1", "element2", "element3"));

### 初始化 ArrayList  
**创建一个空的ArrayList**  
ArrayList\<String> myList = new ArrayList<>();  
**创建一个带有初始元素的ArrayList**  
ArrayList\<Integer> numbers = new ArrayList<>(Arrays.asList(1, 2, 3, 4, 5));  

## String相关操作  
**大写转小写**  
string.toLowerCase()  
**去掉特殊字符**  
string.replaceAll("[^A-Za-z0-9]","");   
**把别的类型转换成string**  
String s = String.valueOf(x); // Convert to String  
**把string转换成char数组**  
string.toCharArray()   
**得到string中的指定字符**  
string.charAt(i)  
**得到string的大小**  
string.length()    

## Arrays相关操作
对数组从小到大排序  
Arrays.sort(nums);  
对二维数组进行排序  
Arrays.sort(intervals, (a, b) -> Integer.compare(a[0], b[0]));  
	
## Binary相关操作  
100是2进制数，转化
Integer.parseInt(100,2)


## Map相关操作
 map.put(string.charAt(i), map.getOrDefault(string.charAt(i), 0) + 1);  
 
遍历全部  
for (Map.Entry<Integer, Integer> entry : map.entrySet()) {  
  System.out.println("Key = " + entry.getKey() + ", Value = " + entry.getValue());  
}
		
遍历key
for (Integer key : map.keySet()) {  
	System.out.println("Key = " + key);  
}
		
遍历value
for (Integer value : map.values()) {  
			System.out.println("Value = " + value);  
		}

## method
Leetcode 1492:在找公约数的时候只用找到n/2就够了， 而且再简化的话只用找到sqrt（n）就好了

