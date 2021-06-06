# wk13WHW

# React Requests - Pirate API Quiz

# Requesting All Pirates

*Question 1*

*Which component is responsible for requesting all the pirates?*

Answer: Pirate container, requestAll(), in react.

*Question 2*

*Which hook do we use to carry out the requestAll() method and when does it get triggered?*

Answer:UseEffect hook, triggered by handle findPiriateById.

*Question 3*

*The requestAll() method creates a new instance of Request in order to gain the functionality to carry out various forms of request. Where is the Request class?*

Answer:The request class is in the helper file.


*Question 4*

*Which method are we using from the Request class here?*

Answer:Get, post and delete.

*Question 5

*The PirateList component is in charge of rendering a list of pirate components. What is the pirateNodes function returning?*

Answer:The index of each pirate.


# Viewing a Single Pirate

*Question 1*

*In the browser, when we click on one of the pirates names in the pirate list, our app renders a PirateDetail component. PirateDetail is in charge of rendering the information for a single pirate. But where is it getting its props passed down from?*

Answer:From the Pirate class imported into Pirate detail.

*Question 2*
 ```js
 if (!pirate){
  return "Loading..."
}
 ```
*What is the purpose of this code in PirateDetail?*

Answer:To return a loading / waiting statement when something other than a pirate property is routed.


*Question 3*

*In PirateDetail, to delete a pirate, we have a button with a listener "onClick" which triggers a function called "handleDelete". The handleDelete function uses a function onDelete. Where is it receiving onDelete from?*

Answer:The handleDelete hook within the PirateDetail component.


# Bonus Points Questions

*Question 1*

*In PirateContainer, what does Promise.all return?*

Answer:Promise all returns all the fetches data requested from the API, returns all the data fetched in an array formatted object.


*Question 2*

*Ideally, we want our state to live at the top of our component chain, except in one other scenario. This is when our component contains a, what?*

Answer:When we have a promise? Asynchornicity?
