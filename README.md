# regular-expressions

Sites para testar Expressões Regulares:

https://regexr.com/

https://regex101.com/

https://www.regexpal.com/


```
grep -Po 'https?\:\/\/(www\.)?([a-zA-Z0-9][a-zA-Z0-9\-]*)\.([a-zA-Z0-9]{2,63})\/?([a-zA-Z0-9][a-zA-Z0-9\-]*)?' access-logs | sort -r| uniq

() 		Capturing Group
? 		Optional
[a-zA-Z0-9]	Lower Case | Upper Case | Numbers
[a-zA-Z0-9\-]	Lower Case | Upper Case | Numbers | Digits
* 		Match 0 or more of the preceding token
```


email:

```
grep -Po "[a-zA-Z0-9\-]+@[a-zA-Z0-9][a-zA-Z0-9\-]*\.[a-zA-Z0-9][a-zA-Z0-9\-]{2,63}" customer-data.txt 
```
