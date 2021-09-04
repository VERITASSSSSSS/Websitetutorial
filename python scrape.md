
# Python Beautiful Soup
##INDENTS

print(soup.prettify())

  

##WITH TAG

match  =soup.title

print(match)

  

##NO TAG

match  =soup.title.text

print(match)

  

##FIND CLASS_

match  =soup.find('div', class_='footer')

print(match)


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ0MTM5NjExNV19
-->