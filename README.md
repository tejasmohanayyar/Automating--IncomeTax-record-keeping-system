# Automating the record keeping process of transactions for ITR filing purposes.

* Bank statements do not give us the payee name, sender name and remarks that were written while executing a transaction. This makes it very difficult for us to communicate to our CA regarding what each transaction was made for. To mitigate this problem we would take screenshots of every transaction we made.

* These transactions would then be manually recorded into a register. I created this python project to automate this record keeping process. What would usually take days for making all the records has now been automated and the process is able to extract all the relevant fields from the screenshots and give us an excel file that can be used for ITR purposes within a minute.

* The program is extracting information from 3 different types of images and hence I had to write seperate code for each type of image. While this method is not completely fool proof it is mostly working on all images thus making the ITR filing process much more efficient in our house.

* Since transactional data is confidential I have not shared images or the document. Within the jupyter files you can see a small sample of each pandas dataframe for each image.

* The sole motivation behind this project was to save time and reduced the laborious task of manually recording the transactions.

