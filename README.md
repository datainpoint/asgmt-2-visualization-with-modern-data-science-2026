# asgmt-2-visualization-with-modern-data-science

Assignment 2: Visualization with Modern Data Science 2026.

## 01. Write a SQL statement in `answer_01` that is able to select all columns and records from `election_types`.

```
id	election_type
1	總統/副總統
2	區域立委
3	山地立委
4	平地立委
5	不分區立委
```

## 02. Write a SQL statement in `answer_02` that is able to show the distinct counties from `districts`.

```
distinct_county
南投縣
嘉義市
嘉義縣
基隆市
宜蘭縣
屏東縣
彰化縣
新北市
新竹市
新竹縣
桃園市
澎湖縣
臺中市
臺北市
臺南市
臺東縣
花蓮縣
苗栗縣
連江縣
金門縣
雲林縣
高雄市
```

## 03. Write a SQL statement in `answer_03` that is able to show the distinct towns in Tainan city from `districts`.

```
distinct_town
七股區
下營區
中西區
仁德區
佳里區
六甲區
北區
北門區
南化區
南區
善化區
大內區
學甲區
安南區
安定區
安平區
官田區
將軍區
山上區
左鎮區
後壁區
新化區
新市區
新營區
東區
東山區
柳營區
楠西區
歸仁區
永康區
玉井區
白河區
西港區
關廟區
鹽水區
麻豆區
龍崎區
```

## 04. Write a SQL statement in `answer_04` that is able to show the distinct county names in Taiwan that are NOT part of the so-called "六都" from `districts`.

```
distinct_county
南投縣
嘉義市
嘉義縣
基隆市
宜蘭縣
屏東縣
彰化縣
新竹市
新竹縣
澎湖縣
臺東縣
花蓮縣
苗栗縣
連江縣
金門縣
雲林縣
```

## 05. Write a SQL statement in `answer_05` that is able to show the number of polling places in Taiwan's Election for president in 2024 from `polling_places`.

```
number_of_polling_places
17795
```

## 06. Write a SQL statement in `answer_06` that is able to show the number of legislator candidates, including regional/aboriginal in Taiwan's Election in 2024 from `candidates`.

```
number_of_legislator_candidates
328
```

## 07. Write a SQL statement in `answer_07` that is able to show the votes received by each party from `party_legislators`.

```
party_id	sum_votes
29	4982062
1	4764576
15	3040615
28	353412
25	128613
16	117298
13	95078
35	69818
33	44852
12	43375
27	40288
20	37615
9	19665
5	17423
7	11746
17	10300
```

## 08. Write a SQL statement in `answer_08` that is able to show the threshold of votes(3% of total votes) to receive subsidies of NT$50 for each vote annually until 2028 from `party_legislators`.

```
sum_votes	percentage_threshold	subsidy_threshold
13776736	0.03	413302
```

## 09. Write a SQL statement in `answer_09` that is able to show the parties that will receive subsidies of NT$50 for each vote annually until 2028.

```
party_id	party	sum_votes
29	民主進步黨	4982062
1	中國國民黨	4764576
15	台灣民眾黨	3040615
```

## 10. Write a SQL statement in `answer_10` that is able to show the result of the 2024 president election.

```
number	party	candidate	votes	votes_percentage
1	台灣民眾黨	柯文哲/吳欣盈	3690466	0.2646
2	民主進步黨	賴清德/蕭美琴	5586019	0.4005
3	中國國民黨	侯友宜/趙少康	4671021	0.3349
```
