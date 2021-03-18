# Login2XploreProject
*Web Form using JsonPowerDB*
The project is based on a web form which accepts data from user and uploads the data into database on submission. The form has been implemented using bootstrap, jquery and javascript. The database used is *JsonPowerDB* which is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

*Benefits of using JsonPowerDB*
* Simplest way to retrieve data in a JSON format.
* Schema-free, Simple to use, Nimble and In-Memory database.
* It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
* It is low level (raw) form of data and is also human readable.
* It helps developers in faster coding, in-turn reduces development cost.

*Release History:*
0.3.2 / 2020-10-08
==================

* Added : Added Plugin API Framework in JsonPowerDB.
* Added : Added a new class APISyntaxValidator to check syntax of request json.
* Added : Added a new APIs for column operation and implement it using pluggable framework:
             Copy Column - It will copy column in database.
             Rename Column - It will rename column in database.
             RemoveColumn - It will remove column in database.
             Change Column type - It will change type of column in database.
* Improved : In Geospatial distance API to pick create time column (sorted in ascending) as time range 
             (by default it should pick the record creation time from the JPDB system file internal 
             recorded time) defined in request fromTime to toTime.
* Fixed : Fixed important bugs.  


*Sample snapshots:*

*Interface :* ![JsonPowerDB Interface]![web-form](https://user-images.githubusercontent.com/44464820/111587137-cce9c680-87e7-11eb-9a25-69958ee522fb.JPG)
![output](https://user-images.githubusercontent.com/44464820/111587152-d2dfa780-87e7-11eb-897a-fb929488d49d.JPG)
![database](https://user-images.githubusercontent.com/44464820/111587165-d70bc500-87e7-11eb-8bad-80e6d0029c60.JPG)

*Data Instances :* 

*Operations performed :*
All CRUD operations can be performed

* *Registration* : Insert Data
* *Show* : Read Data
* *Updation* : Update Data
* *Deletion* : Delete data
