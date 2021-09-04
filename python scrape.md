
# Python Beautiful Soup

## INDENTS

    print(soup.prettify())

## WITH TAG

    match  =soup.title
    print(match)


## NO TAG

    match  =soup.title.text
    print(match)


## FIND CLASS_

    match  =soup.find('div', class_='footer')
    print(match)

## FIND ALL (LOOP)

    for  article  in  soup.find_all('div',class_='article'):
    
    headline  =  article.h2.a.text
    print(headline)
    
    summary  =  article.p.text
    print(summary)
    
    print()


> Written with [StackEdit](https://stackedit.io/).

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4NDE1OTc2OTNdfQ==
-->