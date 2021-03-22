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
<label for="input-name">Search : </label>
<input type="text" name="name" id="input-name" placeholder="Search Amazon"> <br />
<input type="submit" name="submit" style="background:#155783;color:white;font-weight:bold;" onClick="javascript: window.open('https://amznsearch.vercel.app/api/?query=' + document.querySelector('#input-name').value)">
</form>
