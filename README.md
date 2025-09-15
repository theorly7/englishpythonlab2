# Lab-2
## Laboratory Work №2

**Task**

Using the attached file ```books.csv``` OR ```books-en.csv```, complete the following:  
* Output the number of records where the ```Title``` field string is longer than 30 characters.  
* Implement a book search by author, using the result limitation according to your variant.  
* Implement a generator of bibliographic references in the format ```<author>. <title> - <year>``` for 20 records. The records are chosen arbitrarily. Save the list as a separate text file with line numbering.  

Using the attached file ```currency.xml```, complete the following:  
* Parse the file and extract the data according to your variant. Perform type conversions if necessary.  

**Additional Task:**  
* Output a list of all tags without repetitions (for ```books-en.csv``` – a list of publishers without repetitions).  
* The 20 most popular books.  

| Variants | Restrictions books.csv | Restrictions books-en.csv | XML |
| -------- | ---------------------- | ------------------------- | --- |
| 1 | Up to 150 rubles | Up to 150 rubles | Dictionary "Name - Value" |
| 2 | Up to 2016 year | 1991 and 1996 year | Two separate lists: Name and Value |
| 3 | Only 2014, 2016 and 2017 year | Up to 1990 year | List of Name, but only for currencies with Nominal=1 |
| 4 | Up to 200 rubles | Up to 200 rubles | Dictionary "NumCode - CharCode" |
| 5 | None | None | Two separate lists: CharCode and Value |
| 6 | From 150 rubles | From 150 rubles | Average Value |
| 7 | From 2016 to 2018 year | From 1991 to 1995 year | List of CharCode, but only for currencies with Nominal=10 or Nominal=100 |
| 8 | Only 2015 and 2018 year | books-en – from 1997 to 2000 year | Dictionary "CharCode - Nominal" |
| 9 | From 200 rubles | From 200 rubles | Two separate lists: NumCode and CharCode |
| 10 | From 2018 year | From 2000 year | Dictionary "Name - CharCode" |

**Links**  
* About CSV format: https://blog.skillfactory.ru/glossary/csv/  
* About xml.dom library: https://docs.python.org/3/library/xml.dom.minidom.html  
* About XML format: https://help.reg.ru/support/hosting/razmeshcheniye-sayta-otobrazheniye-v-brauzere/chto-takoye-format-xml  
