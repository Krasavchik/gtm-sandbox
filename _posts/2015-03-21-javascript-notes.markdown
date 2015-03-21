---
layout: post
title:  "my JavaScript Notes"
date:   2015-03-21 14:00:00
---

##Common operators used in JavaScrip Language:

###Addition

```
> 6 + 2
```

###Soustraction

```
> 6 - 2
```

###Multiplication

```
> 6 * 2
```

###Division

```
> 6 / 2
```

###Modulus

```
> 43 % 10
```

Will return 3 (remainder of 43 / 10)

##Grouping operations

```
> ( 5 + 7 ) * 3
```

will return 36

```
> ( 3 * 4 ) + 3 - 12 / 2
```

will return 9


##Comparators

They will __return a boolean value__.

```
> 4 > 7
```

will return false

```
> 4 == 7
```

will return false
(double equal sign to test equality)

```
> 4 != 7
```

will return true
(double equal sign to test inequality)

```
> 4 <= 7
```

will return true

##Strings

```
> "We are the winners"
```

Use of quotes to signify it is a string.

###Concatenation of strings

```
> "We are" + " the winners"
```

will return "We are the winners"

```
> "There are " + 3 * 12 + " winners"
```

will return "There are 36 winners"

###Specials characters inside string

\t : tab jump
\ : escaping
\n : new line

###String comparisons

```
> "We are" == "We are"
```

will return true

```
> "We are" != "we are"
```

will return true
Javascript is __case-sensitive__.

```
> "We are".length
```

will return 6
(this is the .length property)
the .length property incorporates spaces and non-alphabetical characters.

##Variables

```
> var hellYeah = 3
```

```
> hellYeah += 4
```

Value of hellYeah is 7
