# Assignment-19.3

val data = List.range(1,101)

 val dataRDD = sc.parallelize(data)

 val dataDF = dataRDD.toDF()

dataDF.write.parquet("data.parquet")

![task1](https://user-images.githubusercontent.com/34162166/38013135-aab43546-3281-11e8-92bb-d6d3aaafde5c.png)

![task 2](https://user-images.githubusercontent.com/34162166/38013139-af5e613e-3281-11e8-903c-98e44a2700c9.png)
