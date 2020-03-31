# Regex tutorial
**Regular expressions** (regex or regexp) are extremely useful in extracting information from any text by searching for one or more matches of a specific search pattern 
and some of it 
1. **Basic topics**
* Anchors — ^ and $
- ^The        matches any string that starts with The -> Try it!
- end$        matches a string that ends with end
- ^The end$   exact string match (starts and ends with The end)
- roar        matches any string that has the text roar in it
******************************
2. **Intermediate topics**
* Grouping and capturing — ()
- a(bc)           parentheses create a capturing group with value bc -> Try it!
- a(?:bc)*        using ?: we disable the capturing group -> Try it!
- a(?<foo>bc)     using ?<foo> we put a name to the group -> Try it!
******************************
2. **Advanced topics**
* Back-references — \1
- ([abc])\1              using \1 it matches the same text that was matched by the first capturing group -> Try it!
- ([abc])([de])\2\1      we can use \2 (\3, \4, etc.) to identify the same text that was matched by the second (third, fourth, etc.) capturing group -> Try it!
- (?<foo>[abc])\k<foo>   we put the name foo to the group and we reference it later (\k<foo>). The result is the same of the first regex -> Try it!

# Grid -generates a block-level grid
1. display
2. grid-template-columns / grid-template-rows
3. grid-column-start
      grid-column-end
        grid-row-start
           grid-row-end  
and alot more that help in css styling 