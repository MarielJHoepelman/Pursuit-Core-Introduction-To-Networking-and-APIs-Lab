# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
```
www.youtube.com/
returns 200-OK: request succeded. 
```
2. 301
``` 
www.timewarnercable.com redirects to www.spectrum.net. 
```
3. 400
4. 401
```
www.mentesenlared.com
returns 401-Unauthorized: request not valid. (Website is private. Only admin can see content)  
```
5. 403
6. 404
```
http://api.viewers-guide.hbo.com/
```
7. 418
8. 500


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
```
https://catfact.ninja/
https://catfact.ninja/fact?max_length=140
{
"fact": "In multi-cat households, cats of the opposite sex usually get along better.",
"length": 75
}
```
2. A list of 150 random users in English.
```
https://randomuser.me/api/?results=150&nat=us
```
3. The current stock price of Microsoft. (IEX API)
4. The 5 year history of Apple stock prices (IEX API)
5. All the Swift language repos on Github with Pursuit in their name
```
https://api.github.com/search/repositories?q=pursuit+in:name+language:swift
```
6. A list of all Pokemon
```
https://pokeapi.co/api/v2/pokemon/?limit=820
```
7. A list of all items in Fortnite
```
https://fortnite-api.theapinetwork.com/items/list
```
8. A list of all Game of Thrones Episodes.
9. A list of all songs with "Love" in the title.
10. All information about Petyr Baelish from the Game of Thrones books
11. All the movies Leonardo Dicaprio has acted in
