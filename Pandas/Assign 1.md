**1 .** Write a Pandas program to create and display a one-dimensional array-like object containing an array of data using Pandas module. 

**2\.** Write a Pandas program to convert a Panda module Series to Python list and it's type. 

**3\.** Write a Pandas program to add, subtract, multiple and divide two Pandas Series. 

Sample Series: \[2, 4, 6, 8, 10\], \[1, 3, 5, 7, 9\]

**4\.** Write a Pandas program to compare the elements of the two Pandas Series. 

Sample Series: \[2, 4, 6, 8, 10\], \[1, 3, 5, 7, 10\]

**5\.** Write a Pandas program to convert a dictionary to a Pandas series. 

Sample Series:

Original dictionary:

{'a': 100, 'b': 200, 'c': 300, 'd': 400, 'e': 800}

Converted series:

a 100

b 200

c 300

d 400

e 800

dtype: int64

**6\.** Write a Pandas program to convert a NumPy array to a Pandas series. 

Sample Series:

NumPy array:

\[10 20 30 40 50\]

Converted Pandas series:

0 10

1 20

2 30

3 40

4 50

dtype: int64

**7\.** Write a Pandas program to change the data type of given a column or a Series. 

Sample Series:

Original Data Series:

0 100

1 200

2 python

3 300.12

4 400

dtype: object

Change the said data type to numeric:

0 100.00

1 200.00

2 NaN

3 300.12

4 400.00

dtype: float64

**8\.** Write a Pandas program to convert the first column of a DataFrame as a Series. 

Sample Output:

Original DataFrame

col1 col2 col3

0 1 4 7

1 2 5 5

2 3 6 8

3 4 9 12

4 7 5 1

5 11 0 11

1st column as a Series:

0 1

1 2

2 3

3 4

4 7

5 11

Name: col1, dtype: int64

\<class 'pandas.core.series.Series'\>

**9\.** Write a Pandas program to convert a given Series to an array. 

Sample Output:

Original Data Series:

0 100

1 200

2 python

3 300.12

4 400

dtype: object

Series to an array

\['100' '200' 'python' '300.12' '400'\]

**10\.** Write a Pandas program to convert a Series of lists to one Series. 

Sample Output:

Original Series of list

0 \[Red, Green, White\]

1 \[Red, Black\]

2 \[Yellow\]

dtype: object

One Series

0 Red

1 Green

2 White

3 Red

4 Black

5 Yellow

dtype: object

**11\.** Write a Pandas program to sort a given Series. 

Sample Output:

Original Data Series: 0 100

1 200

2 python

3 300.12

4 400

dtype: object

0 100

1 200

3 300.12

4 400

2 python

dtype: object

**12\.** Write a Pandas program to add some data to an existing Series. 

Sample Output:

Original Data Series:

0 100

1 200

2 python

3 300.12

4 400

dtype: object

Data Series after adding some data:

0 100

1 200

2 python

3 300.12

4 400

0 500

1 php

dtype: object

**13\.** Write a Pandas program to create a subset of a given series based on value and condition. 

Sample Output:

Original Data Series:

0 0

1 1

2 2

3 3

4 4

5 5

6 6

7 7

8 8

9 9

10 10

dtype: int64

Subset of the above Data Series:

0 0

1 1

2 2

3 3

4 4

5 5

dtype: int64

**14\.** Write a Pandas program to change the order of index of a given series. 

Sample Output:

Original Data Series:

A 1

B 2

C 3

D 4

E 5

dtype: int64

Data Series after changing the order of index:

B 2

A 1

C 3

D 4

E 5

dtype: int64

**15\.** Write a Pandas program to create the mean and standard deviation of the data of a given Series. 

Sample Output:

Original Data Series:

0 1

1 2

2 3

3 4

4 5

5 6

6 7

7 8

8 9

9 5

10 3

dtype: int64

Mean of the said Data Series:

4.818181818181818

Standard deviation of the said Data Series:

2.522624895547565

**16\.** Write a Pandas program to get the items of a given series not present in another given series. 

Sample Output:

Original Series:

sr1:

0 1

1 2

2 3

3 4

4 5

dtype: int64

sr2:

0 2

1 4

2 6

3 8

4 10

dtype: int64

Items of sr1 not present in sr2:

0 1

2 3

4 5

dtype: int64

**17\.** Write a Pandas program to get the items which are not common of two given series. 

Sample Output:

Original Series:

sr1:

0 1

1 2

2 3

3 4

4 5

dtype: int64

sr2:

0 2

1 4

2 6

3 8

4 10

dtype: int64

Items of a given series not present in another given series:

0 1

2 3

4 5

5 6

6 8

7 10

dtype: int64

**18\.** Write a Pandas program to compute the minimum, 25th percentile, median, 75th, and maximum of a given series. 

Sample Output:

Original Series:

0 3.000938

1 11.370722

2 14.612143

3 8.990256

4 13.925283

5 12.056875

.... 17 14.118931

18 8.247458

19 5.526727

dtype: float64

Minimum, 25th percentile, median, 75th, and maximum of a given series:

\[ 3.00093811 8.09463867 10.23353705 12.21537733 14.61214321\]

**19\.** Write a Pandas program to calculate the frequency counts of each unique value of a given series. 

Sample Output:

Original Series:

0 1

1 7

2 1

3 6

4 9

5 1

... 29 2

30 9

31 1

32 2

33 9

34 2

35 9

36 0

37 0

38 4

39 8

dtype: object

Frequency of each unique value of the said series.

0 9

2 7

9 6

1 5

6 3

8 3

7 3

3 2

4 1

5 1

dtype: int64

**20\.** Write a Pandas program to display the most frequent value in a given series and replace everything else as 'Other' in the series. 

Sample Output:

Original Series:

0 3

1 1

2 1

3 3

4 2

5 2

6 1

7 2

8 3

9 1

10 2

11 2

12 2

13 3

14 3

dtype: int64

Top 2 Freq: 2 6

3 5

1 4

dtype: int64

0 Other

1 Other

2 Other

3 Other

4 2

5 2

6 Other

7 2

8 Other

9 Other

10 2

11 2

12 2

13 Other

14 Other

dtype: object

**21\.** Write a Pandas program to find the positions of numbers that are multiples of 5 of a given series. 

Sample Output:

Original Series:

0 1

1 9

2 8

3 6

4 9

5 7

6 1

7 1

8 1

dtype: int64

Positions of numbers that are multiples of 5:

\[\]

**22\.** Write a Pandas program to extract items at given positions of a given series. 

Sample Output:

Original Series:

0 2

1 3

2 9

3 0

4 2

5 3

... 19 0

20 2

21 3

dtype: object

Extract items at given positions of the said series:

0 2

2 9

6 8

11 0

21 3

dtype: object

**23\.** Write a Pandas program to get the positions of items of a given series in another given series. 

Sample Output:

Original Series:

0 1

1 2

2 3

3 4

4 5

5 6

6 7

7 8

8 9

9 10

dtype: int64

0 1

1 3

2 5

3 7

4 10

dtype: int64

Positions of items of series2 in series1:

\[0, 2, 4, 6, 9\]

**24\.** Write a Pandas program to convert the first and last character of each word to uppercase in each word of a given series. 

Sample Output:

Original Series:

0 php

1 python

2 java

3 c\#

dtype: object

First and last character of each word to uppercase:

0 PhP

1 PythoN

2 JavA

3 C\#

dtype: object

**25\.** Write a Pandas program to calculate the number of characters in each word in a given series. 

Sample Output:

Original Series:

0 Php

1 Python

2 Java

3 C\#

dtype: object

Number of characters in each word in the said series:

0 3

1 6

2 4

3 2

dtype: int64

**26\.** Write a Pandas program to compute the difference of differences between consecutive numbers of a given series. 

Sample Output:

Original Series:

0 1

1 3

2 5

3 8

4 10

5 11

6 15

dtype: int64

Difference of differences between consecutive numbers of the said series:

\[nan, 2.0, 2.0, 3.0, 2.0, 1.0, 4.0\]

\[nan, nan, 0.0, 1.0, \-1.0, \-1.0, 3.0\]

**27\.** Write a Pandas program to convert a series of date strings to a timeseries. 

Sample Output:

Original Series:

0 01 Jan 2015

1 10-02-2016

2 20180307

3 2014/05/06

4 2016-04-12

5 2019-04-06T11:20

dtype: object

Series of date strings to a timeseries:

0 2015-01-01 00:00:00

1 2016-10-02 00:00:00

2 2018-03-07 00:00:00

3 2014-05-06 00:00:00

4 2016-04-12 00:00:00

5 2019-04-06 11:20:00

dtype: datetime64\[ns\]

**28\.** Write a Pandas program to get the day of month, day of year, week number and day of week from a given series of date strings. 

Sample Output:

Original Series:

0 01 Jan 2015

1 10-02-2016

2 20180307

3 2014/05/06

4 2016-04-12

5 2019-04-06T11:20

dtype: object

Day of month:

\[1, 2, 7, 6, 12, 6\]

Day of year:

\[1, 276, 66, 126, 103, 96\]

Week number:

\[1, 39, 10, 19, 15, 14\]

Day of week:

\['Thursday', 'Sunday', 'Wednesday', 'Tuesday', 'Tuesday', 'Saturday'\]

**29\.** Write a Pandas program to convert year-month string to dates adding a specified day of the month. 

Sample Output:

Original Series:

0 Jan 2015

1 Feb 2016

2 Mar 2017

3 Apr 2018

4 May 2019

dtype: object

New dates:

0 2015-01-11

1 2016-02-11

2 2017-03-11

3 2018-04-11

4 2019-05-11

dtype: datetime64\[ns\]

**30\.** Write a Pandas program to filter words from a given series that contain atleast two vowels. 

Sample Output:

Original Series:

0 Red

1 Green

2 Orange

3 Pink

4 Yellow

5 White

dtype: object

Filtered words:

1 Green

2 Orange

4 Yellow

5 White

dtype: object

**31\.** Write a Pandas program to compute the Euclidean distance between two given series. 

Euclidean distance

From Wikipedia,

In mathematics, the Euclidean distance or Euclidean metric is the "ordinary" straight-line distance between two points in Euclidean space. With this distance, Euclidean space becomes a metric space. The associated norm is called the Euclidean norm.

Sample Output:

Original series:

0 1

1 2

2 3

3 4

4 5

5 6

6 7

7 8

8 9

9 10

dtype: int64

0 11

1 8

2 7

3 5

4 6

5 5

6 3

7 4

8 7

9 1

dtype: int64

Euclidean distance between two said series:

16.492422502470642

**32\.** Write a Pandas program to find the positions of the values neighboured by smaller values on both sides in a given series. 

Sample Output:

Original series:

0 1

1 8

2 7

3 5

4 6

5 5

6 3

7 4

8 7

9 1

dtype: int64

Positions of the values surrounded by smaller values on both sides:

\[1 4 8\]

**33\.** Write a Pandas program to replace missing white spaces in a given string with the least frequent character. 

Sample Output:

Original series:

abc def abcdef icd

c 3

d 3

3

b 2

e 2

a 2

f 2

i 1

dtype: int64

abcidefiabcdefiicd

**34\.** Write a Pandas program to compute the autocorrelations of a given numeric series. 

From Wikipedia:

Autocorrelation, also known as serial correlation, is the correlation of a signal with a delayed copy of itself as a function of delay. Informally, it is the similarity between observations as a function of the time lag between them.

Sample Output:

Original series:

0 13.207262

1 4.098685

2 \-1.435534

3 13.626760

... 13 \-2.346193

14 17.873884

dtype: float64

Autocorrelations of the said series:

\[-0.38, 0.1, \-0.43, 0.03, 0.35, \-0.2, 0.04, \-0.59, 0.34, 0.11\]

**35\.** Write a Pandas program to create a TimeSeries to display all the Sundays of given year. 

Sample Output:

All Sundays of 2019:

0 2020-01-05

1 2020-01-12

2 2020-01-19

3 2020-01-26

4 2020-02-02

5 2020-02-09

..... 48 2020-12-06

49 2020-12-13

50 2020-12-20

51 2020-12-27

dtype: datetime64\[ns\]

**36\.** Write a Pandas program to convert given series into a dataframe with its index as another column on the dataframe. 

Sample Output:

index 0

0 A 0

1 B 1

2 C 2

3 D 3

4 E 4

**37\.** Write a Pandas program to stack two given series vertically and horizontally. 

Sample Output:

Original Series:

0 0

1 1

2 2

3 3

4 4

5 5

6 6

7 7

8 8

9 9

dtype: int64

0 p

1 q

2 r

3 s

4 t

5 u

6 v

7 w

8 x

9 y

dtype: object

Stack two given series vertically and horizontally:

0 1

0 0 p

1 1 q

2 2 r

3 3 s

4 4 t

5 5 u

6 6 v

7 7 w

8 8 x

9 9 y

**38\.** Write a Pandas program to check the equality of two given series. 

Sample Output:

Original Series:

0 1

1 8

2 7

3 5

4 6

5 5

6 3

7 4

8 7

9 1

dtype: int64

0 1

1 8

2 7

3 5

4 6

5 5

6 3

7 4

8 7

9 1

dtype: int64

Check 2 series are equal or not?

0 True

1 True

2 True

3 True

4 True

5 True

6 True

7 True

8 True

9 True

dtype: bool

**39\.** Write a Pandas program to find the index of the first occurrence of the smallest and largest value of a given series. 

Sample Output:

Original Series:

0 1

1 3

2 7

3 12

4 88

5 23

6 3

7 1

8 9

9 0

dtype: int64

Index of the first occurrence of the smallest and largest value of the said series:

9

4

**40\.** Write a Pandas program to check inequality over the index axis of a given data frame and a given series. 

Sample Output:

Original DataFrame:

W X Y Z

0 68.0 78.0 84 86

1 75.0 75.0 94 97

2 86.0 NaN 89 96

3 80.0 80.0 86 72

4 NaN 86.0 86 83

Original Series:

0 68.0

1 75.0

2 86.0

3 80.0

4 NaN

dtype: float64

Check for inequality of the said series & dataframe:

W X Y Z

0 False True True True

1 False False True True

2 False True True True

3 False False True True

4 True True True True

