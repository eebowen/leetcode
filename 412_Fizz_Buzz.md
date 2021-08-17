## Algorithm 1:
### Naive Solution

1. initialize a string vector or string array.
2. Iterate on the numbers from 1 ...N.
3. initialize a string
4. For every number, check if the number is divisible by 3, add Fizz to string.
5. Check if the number is divisible by 5, add Buzz.
6. Else, string = to_String(number)

C++
```c++
class Solution {
public:
    vector<string> fizzBuzz(int n) {
        vector<string> result;
        for(int i=1; i<=n; i++){
            
            bool divisible_by_3 = (i%3 == 0);
            // cout << "divisible_by_3" << divisible_by_3 <<endl;
            bool divisible_by_5 = (i%5 == 0);
            string oneString;
            
            if(divisible_by_3){
                oneString += "Fizz";
            }
            if(divisible_by_5){
                oneString += "Buzz";
            }
            if(oneString.empty()){
                oneString = to_string(i);
            }
            result.push_back(oneString);
        }
        return result;
        
    }
};
```
Python
```python
class Solution:
    def fizzBuzz(self, n: int) -> List[str]:
        ans = [];
        
        for num in range(1, n+1):
            
            divisible_by_3 = (num % 3 == 0)
            divisible_by_5 = (num % 5 == 0)
            
            oneString = ""
            
            if divisible_by_3:
                oneString += "Fizz"
            if divisible_by_5:
                oneString += "Buzz"
            if not oneString:
                oneString = str(num)
            
            ans.append(oneString)
        
        return ans
```

---

## Algorithm 2:
### Hashmap Solution

- Create a hash map for each number-word pair, so it's easy to add more word without adding if statements
- Hashmap:
  - python: dictionary {}
  - c++: unordered_map<string, int> umap; or map<string, int> umap;
  - c++ order of the unordered_map can vary each time when loop through, so use map.

C++
```c++
class Solution {
public:
    vector<string> fizzBuzz(int n) {
        vector<string> result;
        map<int, string> word_map
            = {{3, "Fizz"},
               {5, "Buzz"}};
        
        for(int i=1; i<=n; i++){
            string oneString = "";
            
            // loop all word in dict
            for(auto key:word_map){
                if((i % key.first) == 0){
                    oneString += key.second;
                }
            }
                if(oneString.empty()){
                    oneString = to_string(i);
                }
            result.push_back(oneString);
        }
        return result;

    }
};
```

Python
```python
class Solution:
    def fizzBuzz(self, n: int) -> List[str]:
        word_dict = {3: "Fizz", 5: "Buzz"}
        ans = []
        for num in range(1, 1+n):
            
            one_string = ""
            
            for key in word_dict.keys():
                if num % key == 0:
                    one_string += word_dict[key]
            
            if not one_string:
                one_string = str(num)
            
            ans.append(one_string)
                    
        return ans
```

