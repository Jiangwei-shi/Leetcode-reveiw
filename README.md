# Leetcode-reveiw

## 各种初始化
### 初始化 Hashmap
**创建一个空的Hashmap**  
Map<Character, Integer> map = new HashMap<>();

### 初始化 HashSet
**创建一个空的HashSet**  
Set<Integer> set = new HashSet<>();

### 初始化 Array
**创建一个空的Array**  
int[] number = new int[5];
	
### 初始化 Stack
**创建一个空的Stack**  	
Stack<Character> stack = new Stack<>();
	
### 初始化 Queue
**创建一个空的Queue**  
Queue<String> queue = new LinkedList<>();
	
### 初始化 linkedList	
**创建一个空的linkedList**  
LinkedList<Integer> linkedList = new LinkedList<>();  
**创建一个带有初始元素的linkedList**  
LinkedList<String> linkedList = new LinkedList<>(Arrays.asList("element1", "element2", "element3"));

### 初始化 ArrayList  
**创建一个空的ArrayList**  
ArrayList<String> myList = new ArrayList<>();  
**创建一个带有初始元素的ArrayList**  
ArrayList<Integer> numbers = new ArrayList<>(Arrays.asList(1, 2, 3, 4, 5));  

## String相关操作
String string  
1.string.toLowerCase()  
2.string.replaceAll("[^A-Za-z0-9]","");  
3.String s = String.valueOf(x); // Convert to String  
4.string.toCharArray()

## Arrays相关操作
int[] nums  
Arrays.sort(nums);  
对二维数组进行排序  
Arrays.sort(intervals, (a, b) -> Integer.compare(a[0], b[0]));  
为了不用for loop查找Array。可以放入hashmap中查找  
例子：  
[two sum](https://leetcode.com/problems/two-sum/description/)	

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

