# Using Nokogiri to Scrape Websites AND Fetching Data From APIS

## What is Scraping?
  - Using HTML tags, ids, and CSS names to select specific objects

## Techniques for Scraping
  - Determine your models, then look at the page to see what information you need
  - Break down the website into pieces you want information from
    – DO NOT go for individuals details, go for elements that CONTAIN all the details that you need to make an instance
    - We want to select elements that help us make one instance at a time (of whatever class we've decided to make)
    - When we want to find something by a class name, the css selector requires a '.' before the name of the class
    - For IDs, it requires a "#"
  - Find a common selector attribute between all of them (usually a class name), and use it to select all of them
  - Iterate over all collected objects and pull the information that you want, using another attribute selector

# Requirements for Project
  - Has-many-belongs-to relationship
  - How to Scrape "1 layer deeper"

# Review class
- Artist
- Album
- Genre
- Reviewer
- Date


## What are APIs
  - The term API is used to mean lots of things: sometimes it can mean documentation, sometimes it can mean an endpoint where you get a bunch of data (the way we're going to use it today). It stands for "Application Programming Interface"
  - APIs that are 'endpoints' that return data for us usually have documentation on how to use them. Sometimes you need to apply to get a KEY to use an API, sometimes you're limited to the amount of free requests you can make and then have to pay
  - All API endpoints return information in a different pattern, but the return value is usually an array or a hash

https://dev.to/flippedcoding/what-is-the-difference-between-a-uri-and-a-url-4455


#
