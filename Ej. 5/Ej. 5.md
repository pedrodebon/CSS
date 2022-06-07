0. li:first-child
1. p:not(p[class])
2. li:nth-of-type(2n+3)
3. div>*
4. span[data-item]
5. p~span
6. form>*:not(*[disabled]) (solucion optimizada ":enabled")
7. #one, #two, #five, #six, #nine
8. a+span
9. #foo > .foo
10. div > div >span + code:not(code[class]) (solucion optimizada: "div div span + code:not(.foo)")