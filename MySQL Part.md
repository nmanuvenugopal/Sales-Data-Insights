* After installing the MySQL, we need to import the data to the server. We have to import the data by using the sql dump file "db_dump.sql". We need to upload this dump
file and select import option.
![image](https://user-images.githubusercontent.com/99719105/219357985-a38daaee-1bdb-4f95-8997-1a38d40a4757.png)

* If it was successfully imported then if we refresh the database section then we can see the newly uploaded database and related tables in that particular sql dump file.

# The following are the some of the sample quries that i have carried out:
* Selecting the all the record of the transaction table.
![image](https://user-images.githubusercontent.com/99719105/219361860-4d074f31-c50e-4a1c-9ecf-49386f047e05.png)

* Selecting the top 5 records of the transaction table.
![image](https://user-images.githubusercontent.com/99719105/219362037-aa6ccde3-05a8-4cc4-857a-a5ac0ea7aaf1.png)

* Selecting the transaction that is done at Chennai (we need a where clause for this).
![image](https://user-images.githubusercontent.com/99719105/219362443-ff7ec33d-d20f-4573-b284-26b23163627c.png)
![image](https://user-images.githubusercontent.com/99719105/219362680-1ef9fe4d-0b26-4536-a2ce-8680bb98f3e6.png)

* Another way of selecting the transaction that is done at Chennai (we need a Join and Where clause for this).
![image](https://user-images.githubusercontent.com/99719105/219363741-e2b08ace-8dc0-44ba-b2e7-dca0f3c54e19.png)

* Selecting the transaction that is done in the year 2020 (Join the date and transaction table and date table will have year, just include the year we want with 
where clause. .
![image](https://user-images.githubusercontent.com/99719105/219365281-44275a13-d860-415a-b7bc-640cde28ffc7.png)

* Selecting the records that is done at Chennai and in the year 2020 (apart from Join statement we should use "and" statement in the where clause).
![image](https://user-images.githubusercontent.com/99719105/219402533-844848dd-f340-4fae-a05c-da1e4be98445.png)


