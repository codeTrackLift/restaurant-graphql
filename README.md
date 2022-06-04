# <img src='https://codetracklift.github.io/codeTrackLift/logos/mitxPro_logoStacked.jpg' alt='MIT xPro logo' height='30'>  GraphQL Restaurant Data Exercise 

<img src='./pics/graphQlLogo.png' alt='GraphQL logo' height='50'>

Creating multi-tier applications means building multiple API endpoints to handle different data operations. The more complex your application becomes, the harder it is to maintain all these endpoints. GraphQL aims to reduce this complexity by providing a simpler view of data and making it easier to query it. 

Your task is to set up GraphQL for your restaurant data and then add mutations to get and update these data. 

The starter files include the restaurant data in JSON format and a predefined build schema for GraphQL. You need to go through this code to understand what each query or mutation should look like.

To accomplish this task, you need to implement the following methods under the “root” object: 

- restaurant: This gets a single restaurant based on a provided ID. 
- restaurants: This gets a list of all restaurants. 
- setrestaurant: This creates a new restaurant. 
- deleterestaurant: This deletes a restaurant based on the provided id.
- editrestaurant: This updates a restaurant based on the provided id.

> Instructions:

After completing the task, run the GraphQL interface and submit a file with screenshots showing all five queries and mutations highlighted above, along with a link to your GitHub repo that houses the code for this activity.

> Screenshots
### Get Single Restaurant

<img src='./pics/getSingleRestaurant.png' alt='GraphQL query' width='500'>

### Get All Restaurants
<img src='./pics/getAllRestaurants.png' alt='GraphQL query' width='500'>

### Set Restaurant
<img src='./pics/setNewRestaurant1of2.png' alt='GraphQL query' width='500'>
<img src='./pics/setNewRestaurant2of2.png' alt='GraphQL query' width='500'>

### Delete Restaurant
<img src='./pics/deleteRestaurant1of2.png' alt='GraphQL query' width='500'>
<img src='./pics/deleteRestaurant2of2.png' alt='GraphQL query' width='500'>

### Edit Restaurant
<img src='./pics/editRestaurant1of2.png' alt='GraphQL query' width='500'>
<img src='./pics/editRestaurant2of2.png' alt='GraphQL query' width='500'>

## MIT License

Copyright (c) 2022 Pete Chu <img src='https://codetracklift.github.io/codeTrackLift/logos/giphyPharma2Code.gif' alt='codeByPete logo' width='25'> ***[codeByPete](https://www.codebypete.com/)***

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.