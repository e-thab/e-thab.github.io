---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
## Website Testing

This is content on my github.io page. Hello, you are reading this. Lorem, ipsum, etc.

- This is a list on my website
- This is the second entry in a list on my website

Here's some code:
```
## A Pythagorean triplet is a set of three natural numbers, a < b < c, for which,
##
##                      a2 + b2 = c2
##
## For example, 32 + 42 = 9 + 16 = 25 = 52.
##
## There exists exactly one Pythagorean triplet for which a + b + c = 1000.
## Find the product abc.

for a in range(1, 333+1):
    for b in range(a+1, 500+1):
        c = 1000 - (a + b)
        
        if a**2 + b**2 == c**2:
            print(f"{a}^2 + {b}^2 = {c}^2")
            print(f"{a} + {b} + {c} = 1000")
            print(f"abc = {a*b*c}")
```

Thanks for visiting.