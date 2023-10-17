- string comparison efficient: `keccak256(bytes(my_str)) == keccak256("signed")`  
> Use keccak256 comparison which uses dramatically less gas than character comparison or than  
> loading the StringUtils contract  
