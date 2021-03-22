# Amzn-Search  
An API by which you can easily get Amazon search results into JSON fromat.

### Usage:  

```
https://amznsearch.herokuapp.com/api/?query={your-query-here}
```  
Example: https://amznsearch.herokuapp.com/api/?query=macbook+pro  

------------------------------------------  

### Connect:
* [Updates Channel](https://t.me/asprojects)  
* [Support Group](https://t.me/assupportchat)  

----------------------------------------------------------  


<form id="name">
<label for="input-name">Name </label>
<input type="text" name="name" id="input-name" placeholder="Search Amazon">
<input type="submit" name="submit" onClick="javascript: window.open('https://amznsearch.herokuapp.com/api/?query=' + document.querySelector('#input-name').value)">
</form>
