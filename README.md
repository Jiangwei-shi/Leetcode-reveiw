# Leetcode-reveiw

## 各种初始化
初始化Hashmap

Map<Character, Integer> map = new HashMap<>();
map.put(c, counts.getOrDefault(c, 0) + 1)

初始化 数组

int[] number = new int[5];

## String相关操作
String string
1.string.toLowerCase()
2.string.replaceAll("[^A-Za-z0-9]","");

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

