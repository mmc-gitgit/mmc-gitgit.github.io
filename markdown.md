<!-- /markdwn.md -->

### item: learn (some) markdown (nb github flavoured markdown aka GFM)
there is a ton of details & 'similar but different' cases; 
aside from GFM, there are a ton of different implementations  
that are also 'similar but different' ...

my intention is to be able to write sorta readable markdown that produces  
html that will be rendered as a not ridiculously unreadable web page

Catch-22: you kinda need to be good at html, before you start trying to use  
markdown to generate it for you... chicken AND egg

`"*"       introduces an unordered list`

*    italic            enclose the _word or phrase_ in a pair of underscores
*    bold              enclose the **item** in a pair of double asterisks
*    header            for header 'n', prefix the line with n octothorpes  
                       --- causes line breaks
<!-- cannot get "https://sub.comain/" to render as plain text -->
*    inline link  
            \[text\]\(\https\:\/\/sub.domain/ "tooltip"\)  
        eg [DuckDuckGo](https://www.duckduckgo.com "search engine") 
*    reference link    tba
*    blockquote        begin each source line with right angle (greater than)
*    soft break        2 trailing spaces (see header above)
*    inline image link	(eg) ![a nice pic of a green tree frog](./frog.jpg "ribbit")  
                       --- so, an inline link with a bang prefix  
                       --- squares enclose the alt= text
*    unordered list    begin each item line with star space: '* item'
* *  -- nesting: eg '* * level 2 item' etc
* *  second level 2 item
1.   ordered list (github is not same as tutorial)
1.   use numbers eg "1. first" with variable leading space, and
1.   at least a single space after the '.'
1.   more stuff
1.   nesting is unobvious (have not sorted it)...
     1.  first
     1.  second
     1.  third
*    comment             tba
*    escape				 backslash
*    line break      	 tba
*    indentation  		 tba
