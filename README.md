# Advanced-Python
## 1. Import Data
[Advanced Python Импорт CSV файла.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20%D0%98%D0%BC%D0%BF%D0%BE%D1%80%D1%82%20CSV%20%D1%84%D0%B0%D0%B9%D0%BB%D0%B0.ipynb)

takes data [from](https://video.ittensive.com/python-advanced/data-5283-2019-10-04.utf.csv)
and makes the frame (table of data). Using this frame, the program calculates the average number of fire engine calls per month in one district of Moscow, rounding to integers
## 2. Multi-source data
[Advanced Python Объединение данных и сортировка по индексам.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Объединение%20данных%20и%20сортировка%20по%20индексам.ipynb)

[Get data on unemployment in Moscow](https://video.ittensive.com/python-advanced/data-9753-2019-07-25.utf.csv)

Combine this data with the indexes (Month/Year) and the data from the previous assignment (firefighter calls) for the Central Administrative District:
[https://video.ittensive.com/python-advanced/data-5283-2019-10-04.utf.csv](https://video.ittensive.com/python-advanced/data-5283-2019-10-04.utf.csv)

Find the value of the UnemployedMen field in the month when there were the least number of calls in the Central Administrative District.
## 3. Data extraction
[Advanced Python Выделение данных.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Выделение%20данных.ipynb)

[Get data on unemployment in Moscow](https://video.ittensive.com/python-advanced/data-9753-2019-07-25.utf.csv)

Find the percentage of people with disabilities (UnemployedDisabled) among all unemployed people (UnemployedTotal) that became less than 2%.
## 4. Prediction for 2020
[Advanced Python Предсказание на 2020 год.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Предсказание%20на%202020%20год.ipynb)

[Get data on unemployment in Moscow](https://video.ittensive.com/python-advanced/data-9753-2019-07-25.utf.csv)

Group the data by year, and if there are fewer than 6 values in a year, discard those years.  
Construct a linear regression model by year of the average value of the ratio of UnemployedDisabled to UnemployedTotal (the percentage of people with disabilities) for the month and answer what value is expected for the percentage of unemployed people with disabilities in 2020 if the current policy of the city of Moscow is maintained?   
Round up the answer to a hundredth. For example, 2.32

## 5. API data retrieval
[Advanced Python Импорт данных JSON и API.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Импорт%20данных%20JSON%20и%20API.ipynb)

Explore [Yandex Geocoder API](https://tech.yandex.ru/maps/geocoder/doc/desc/concepts/input_params-docpage/) and get an API key for it in the developer's cabinet.  
Perform a query to the API and find out the longitude of the point on the map (Point) for the city of Samara.  
Note: activation of the Yandex Geocoder key may take several hours (up to a day).  
As a backup you can use this key - 3f355b88-81e9-4bbf-a0a4-eb687fdea256 - it is only for this task!

## 6. Obtaining stock quotes
[Advanced Python Получение котировок.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Получение%20котировок.ipynb)

Get stock quotes from [the page](https://mfd.ru/marketdata/?id=5&group=16&mode=3&sortHeader=name&sortOrder=1&selectedDate=01.11.2019) and find which ticker had the maximum increase in the number of trades (as a percentage) for November 1, 2019.

## 7. Parsing an online store
[Advanced Python Парсинг интернет-магазина.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Парсинг%20интернет-магазина.ipynb)

Using parsing data from beru.ru marketplace, find how many liters is the total volume of Saratov 263 and Saratov 452 refrigerators different?  
For parsing you can use the mirror of beru.ru page with the results for Saratov [refrigerators at the address](https://video.ittensive.com/data/018-python-advanced/beru.ru/)

## 8. Uploading results to the database
[Advanced Python Загрузка результатов в БД.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Загрузка%20результатов%20в%20БД.ipynb)

Collect data about Saratov refrigerator models from beru.ru marketplace: URL, name, price, size, total volume, refrigerator volume.  
Create the appropriate tables in a SQLite database and load the resulting data into the beru_goods table.  
For parsing, you can use the mirror beru.ru page with the results for [Saratov refrigerators](https://video.ittensive.com/data/018-python-advanced/beru.ru/)

## 9. Data visualization type
[Advanced Python Выбор типа визуализации.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Выбор%20типа%20визуализации.ipynb)

[Download data on the USE in recent years](https://video.ittensive.com/python-advanced/data-9722-2019-10-14.utf.csv)

Select the data for the academic year 2018-2019.  
**Select the chart type to display the results by Moscow administrative district,** build the selected chart for the number of students who wrote the USE with 220 points or higher.  
**Select the type of chart and build it for the districts** of the Northwestern Administrative District of Moscow for the number of students who wrote the USE with 220 points or higher.

## 10. Marathon results
[Advanced Python Разбор данных с марафона.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Разбор%20данных%20с%20марафона.ipynb)

[Download the results of the marathon](https://video.ittensive.com/python-advanced/marathon-data.csv)

Calculate half and full distance times to seconds.  
**Find which data series are correlated** (using the pairplot chart in Seaborn).  
**Find the correlation coefficient** for these data series using scipy.stats.pearsonr.  
**Construct a jointplot plot for the correlated data.**

## 11. Moving averages on the stock charts
[Advanced Python Визуализация графиков акций.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Визуализация%20графиков%20акций.ipynb)

[Используя данные индекса РТС за последние годы](https://video.ittensive.com/python-advanced/rts-index.csv)  
Plot **separate graphs of the closing (Close) ** index by day for 2017, 2018, 2019 in a single X-axis.  
Add **the 20-day exponential average for the 2017 Max value** to the graph.  
**Find the last date** when the exponential average of the maximum daily value (Max) in 2017 was greater than the corresponding Close value in 2019 (this is the last intersection of the 2019 chart and the chart for the 2017 average).

## 12. Russian cultural heritage
[Advanced Python Объекты культурного наследия в России.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Объекты%20культурного%20наследия%20в%20России.ipynb)

Explore the data set on the objects of cultural heritage of Russia ([as a zip-archive](https://video.ittensive.com/python-advanced/data-44-structure-4.csv.gz)):  
and build a background map of the number of objects in each region of Russia, using [geo-data](https://video.ittensive.com/python-advanced/russia.json)  
Выведите для каждого региона количество объектов в нем.  
Посчитайте число объектов культурного наследия в Татарстане.

## 13. PDF build
[Advanced Python Многостраничный PDF.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Многостраничный%20PDF.ipynb)

Using [data](https://video.ittensive.com/python-advanced/data-7361-2019-11-28.utf.json) on library attendance in Moscow neighborhoods construct a pie chart of total attendance (NumOfVisitors) for the 20 most popular districts of Moscow.  
Create a PDF report using the [file](https://video.ittensive.com/python-advanced/title.pdf) as the first page. On the second page, print the summary chart, the most popular district of Moscow and the number of library visitors in it.

## 14. Moscow heraldic symbols
[Advanced Python Геральдические символы Москвы.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Геральдические%20символы%20Москвы.ipynb)

Generate a PDF document from [a list of flags](https://video.ittensive.com/python-advanced/data-102743-2019-11-13.utf.csv) and coats of arms of Moscow districts.  
On each page of the document, print the name of the heraldic symbol (Name), its description (Description) and its image (Picture).  
To show the images use [the address https://op.mos.ru/MEDIA/showFile?id=XXX](https://op.mos.ru/MEDIA/showFile?id=XXX)  
where XXX is the value of the Picture field in the dataset. For example:  
https://op.mos.ru/MEDIA/showFile?id=8466da35-6801-41a9-a71e-04b60408accb  
If you have problems downloading images from op.mos.ru, you can add a setting to the code to force the use of additional types of encryption in the protocol SSL/TLS.  
`requests.packages.urllib3.util.ssl_.DEFAULT_CIPHERS = 'ALL:@SECLEVEL=1'`

## 15. Multipage report
[Advanced Python Финальный отчет.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Финальный%20отчет.ipynb)

Using [data](https://video.ittensive.com/python-advanced/data-107235-2019-12-02.utf.json) on activities in Moscow parks  
Create a PDF report in which you output:  
1. Diagram of the distribution of the number of activities by park, the top 10 most active  
2. Table of activities for all parks in the form of Activity-Schedule-Park

## 16. Automatic reports
[Advanced Python Автоматический отчет.ipynb](https://github.com/Mycken/Advanced-Python/blob/main/Advanced%20Python%20Автоматический%20отчет.ipynb)

Compile a report on the 2018-2019 USE results, using [data](https://video.ittensive.com/python-advanced/data-9722-2019-10-14.utf.csv) 
and send it in HTML format to support@ittensive.com, using only Python.  
The report should include:  
- total number of honors students (students who received more than 220 points on the USE in Moscow),  
- distribution of the top scorers by Moscow districts,  
-  name of the school with the best USE results in Moscow.  

Distribution diagram should be inserted into HTML via data:URI format (base64 encoding).  
Optional: attach a PDF document of the same content (duplicate letter) to the report.
