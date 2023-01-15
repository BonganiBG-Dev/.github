<h1 align="center"> PC Part Hunter </h1>
<p align="center">
  FInd the best prices on PC Parts in South Africa
</p>
<div align="center">
    <a>
        <img src="https://img.shields.io/website?style=for-the-badge&up_color=lightgrey&up_message=offline&url=https%3A%2F%2Fshields.io" alt="Website">
    </a>
</div>



## Table of Content 
- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
	- [Services](#services)
		- [Web Scraper](#web-scraper)
		- [Product Filter](#product-filter)
		- [Product API](#product-api)
		- [Frontend Application](#frontend-application)
- [Updates](#updates)


## Overview 
Welcome to PC Part Hunter, we aim to be the one stop shop for browsing new PC parts in South Africa. As PC hardware geeks, it can get very complicated finding the best deals on PC parts and the task is made harder when services like [PC Part Picker](https://pcpartpicker.com) only cater to the US and European market

## Features
#### Current
- Product listing
- Price comparison
- Build product lists
- View product specs

#### Upcoming 
- PC build configuration 
	- Select different parts 
	- Get suggestions on cheapest website to get each part 
- Price to performance build 
	- Automatically generate best price to performance build based on available stock 
	- User generated build comparions 


## Architecture 
The system is built using a microservice architecture. There are currently 4 services involved in the whole system.

#### Services
1. [Scraping Service](https://github.com/PC-Part-Hunter/web-scraper)
2. [Filtering Service](https://github.com/PC-Part-Hunter/parts-filter)
3. [API](https://github.com/PC-Part-Hunter/api)
4. [Frontend Application](https://github.com/PC-Part-Hunter/frontend)

The goal for the system is to add more advanced features to the [Filtering Service](https://github.com/PC-Part-Hunter/parts-filter) down the line so isolating it from the [Scraping Service](https://github.com/PC-Part-Hunter/web-scraper) and the [API](https://github.com/PC-Part-Hunter/api) will allow for that to happen. 


## Updates
Although the system works, it is not yet production ready. A release date has not yet been set, but stay tuned for updates, you can [contact](#contact) us on our unofficial channels to get updates

## Contact 
- [Instagram](https://www.instagram.com/killshiftgamer/)
- [Twitter](https://mobile.twitter.com/killshiftgamers)
- [Email](bonganibg@proton.me)
