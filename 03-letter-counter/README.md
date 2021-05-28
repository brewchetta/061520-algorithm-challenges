# Letter Counter

Build a function / method that receives the name of a city as a string. The function / method needs to return a string that shows how many times each letter shows up in the string by using pluses (+).

For example:

`letters("Chicago")  -->  "c:++, h:+, i:+, a:+, g:+, o:+"`

As you can see, the letter c is shown only once, but with 2 pluses.

The return string should include only the letters (not the dashes, spaces, apostrophes, etc). The different letters are separated by a comma (,) and space as seen in the example above.

Note that the return string must list the letters in order of their first appearance in the original string.

More examples:

`letters("Bangkok")    -->  "b:+, a:+, n:+, g:+, k:++, o:+"`
`letters("Las Vegas")  -->  "l:+, a:++, s:++, v:+, e:+, g:+"`
`letters("St. Louis")  -->  "s:++, t+, l:+, o:+, u:+, i:+"`
