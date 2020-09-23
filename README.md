<div align="center">

## Easiest GET/POST vars\.\.\.


</div>

### Description

This is the easiest way to access all of your GET and/or POST vars. It is the fastest and least amount of code...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Steven Pratt](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/steven-pratt.md)
**Level**          |Intermediate
**User Rating**    |3.8 (19 globes from 5 users)
**Compatibility**  |PHP 4\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__8-33.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/steven-pratt-easiest-get-post-vars__8-936/archive/master.zip)





### Source Code

```
<?
// This is uses the foreach function, which is
// more resource-efficient than while(list...
// The first line grabs the post vars, and
// the second line grabs the get vars...
foreach($_POST as $key=>$val){ $$key = $val; }
foreach($_GET as $key=>$val){ $$key = $val; }
?>
```

