
# 简介

一个在Spring ,Spring Boot和Spring Cloud 创建微服务系统的简单示例。

A simple example of setting up a microservices system using Spring, Spring Boot and Spring Cloud.

[Microservices(微服务)](http://martinfowler.com/articles/microservices.html) 让一定数量的协作组件来构建大型系统。

allow large systems to be built up from a number of collaborating components. It does at the process level what Spring has always done at the component level: loosely coupled processes instead of loosely coupled components.

Shopping Application

For example imagine an online shop with separate microservices for user-accounts, product-catalog order-processing and shopping carts:

Inevitably there are a number of moving parts that you have to setup and configure to build such a system. How to get them working together is not obvious - you need to have good familiarity with Spring Boot since Spring Cloud leverages it heavily, several Netflix or other OSS projects are required and, of course, there is some Spring configuration “magic”!