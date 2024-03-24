## *Expert System based on predicate logic using **[pyDatalog](https://sites.google.com/site/pydatalog/home)** library & Google Colab environment*
*The system will infer family realationships based on a family tree in a csv file*

***Steps:***

1- Install pyDatalog library using pip.

2- Import pyDatalog and csv library.

3- Create terms using pyDatalof.create_terms().

4- Open csv file in read mode then load its contents into variable **rows** usin csv.DictReader class.

5- Loop throw **rows** and load facts to agent's ***Knowledge Base*** .

6- Building rules that agent will use for reasoning.

7- Initiate queries to assert facts.
