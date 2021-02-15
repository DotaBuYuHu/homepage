# BuYuHu Homepage
This's BuYuHu's homepage, and this repo contains the frontend code. www.dotabuyuhu.com
## Design Diagram
![alt text](https://github.com/DotaBuYuHu/homepage/blob/master/image/designDiagram2.0.png?raw=true)
## ScoreTracker UI
![alt text](https://github.com/DotaBuYuHu/homepage/blob/master/image/scoreTracker.png?raw=true)
## Route 53
Route 53 route to an EC2 instance. And the domain is from GoDaddy.
## API Gateway
We have two endpoints GET & POST. 
* Simple of GET Response:
```
{
    "matchContent": [
         {
            "MonthTableId": "score-2-2021",
            "Winner": "Autismy,element蛙呱呱,赵德柱,全能莽夫戴维德,幸福啪啪啪",
            "MatchId": "1613118059337",
            "Loser": "Aren,地鼠,Lala,木幕的执着,Grandson Liu"
        }	  
    ]
}
```
* Simple of POST payload:
```
{
    "MonthTableId": "score-2-2021",
    "Winner": "Autismy,element蛙呱呱,赵德柱,全能莽夫戴维德,幸福啪啪啪",
    "MatchId": "1613118059337",
    "Loser": "Aren,地鼠,Lala,木幕的执着,Grandson Liu"
}
```
## DynamoDB
![alt text](https://github.com/DotaBuYuHu/homepage/blob/master/image/dynamodb.png?raw=true)
