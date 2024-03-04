## Arrays

`int[] result = new int[20];`
This will create an array of size 20.

## HashMap

// Declaration
`Map<Integer, Integer> hashMap = new HashMap<>();`

// Put
`hashMap.put(key, value)`

// Retrieve
`hashmap.get(key)`
`hashMap.getOrDefault(key, 0)` // this is more helpful

// Other important methods
```java
hashMap.containsKey(key); // if key exists. Returns true/false.
hasmMap.containsValue(value); // if value exists. Returns true/false.
hashMap.remove(key); // remove the key.
hashMap.size(); //size of hashMap.
hashMap.isEmpty(); // if hashMap is empty.
hashMap.keySet(); // key set of hashMap.
hashMap.values(); // Collection of values. 
```

// Populate HashMap using char frequency

```java
Map<Character, Integer> m = new HashMap<>();

for (char c:charString.toCharArray()) {
    m.put(c, m.getOrDefault(c, 0)+1);
}
```