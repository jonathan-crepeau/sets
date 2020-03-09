# Lightening Learn - SETS!

## Overview
The Set object lets you store values of any type, whether primitive values or object references. This makes them very similar to arrays, except for one key difference -- sets will only store unique values! That is, no duplicate values can be contained in a Set object. While the ES6 version of Javascript formally introduced a native Set object for that language, languages like Python have included native Set objects for a much longer amount of time. Lastly, Set objects are special in that they will not throw an error if you try to add a duplicate value to the list -- it will simply ignore the value and continue.

## Example 1
Let's say you have an array that includes the first name of every user who logged onto your website in the last 24 hours. If the user logged in more than once in that 24-hour period, their name will be added to the array multiple times.

names = ['aliza', 'ali', 'jo', 'ali', 'ryan', 'andre', 'lauren', 'ali', 'brock', 'lauren']

You can use the Set object, specifically it's constructor, to produce a Set which will only include each unique first name once -- which allows you to get an accurate number of how many users logged in during that 24-hour period.

let mySet = new Set(names = ['aliza', 'ali', 'jo', 'ali', 'ryan', 'andre', 'lauren', 'ali', 'brock', 'lauren']);
console.log(mySet)

#### RETURNS:
['aliza', 'ali', 'jo', 'ryan', 'andre', 'lauren', 'brock']

## Example 2
Set.has(value)


#### Third-Party APIs
- [PetFinder](https://www.petfinder.com/developers/v2/docs/)

## Contributors
• Ryan Sherring / Web Developer - [Github](https://github.com/jasonToups)

• Jonathan Crepeau / Web Developer - [Github](https://github.com/jonathan-crepeau)
