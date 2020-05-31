---
layout: post
title:  "Learning Http4s with Doobie-Postgressql in Scala Chapter1"
date:   2020-05-31 08:21:05 +1000
categories: Scala
---

I would like to use scala http4s with Doobie-Postgressql to build APIs. 
How do I create a scala project? 
```sh
https://docs.scala-lang.org/getting-started/intellij-track/building-a-scala-project-with-intellij-and-sbt.html
```
There is a git repo for me to follow 
```sh
https://github.com/heaton/hello-http4s
```
Today I learned how to connect postgres database by following guidelines
```sh
https://tpolecat.github.io/doobie/docs/01-Introduction.html
```
I also used DataGrip to connect the database  
I ran the program locally and see the result returned from the get api 
```sh
http://127.0.0.1:8080/country/AFG
```
This is a beginning chapter for myself to build a microservice. 
In the upcoming time I am going to invest time to build this program by myself.