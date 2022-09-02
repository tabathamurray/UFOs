# Detailed Instructions From Your Instructor Team

The objective of this challenge is for you to create multiple search criteria in addition to the date filter you created in this module. When a user enters the search criteria the `app.js` will store the element, value, and the id of the filter that was changed and then filter the dataset and keep only the data that matches search criteria. The search criteria will will be rendered on the webapge. 

## Deliverable 1: Filter UFO Sightings on Multiple Criteria

For the first deliverable, we are asking you to modify your `index.html` by removing the list element that creates the button to click, and adding four new list elements for city, state, country, and shape.  Then you'll need to capture all the elements, values and ids that are changed when the search criteria are entered and then filter the dataset and render the filtered data on the webpage.  

you might find the tasks in this challenge to be slightly difficult. We have provided starter code that they should download, rename as `app.js`, and place it in the js folder of  your UFOs GitHub repository.  

**Important:** Make sure they change the name of your `app.js` file used for the module solution before they rename the `ufo_starteCode.js` file.

First, you'll need to modify your `index.html` file to remove the list element that creates the button and create four new list elements for the additonal search criteria. The search criteria should be similar to this image:

Next, you'll need to use the starter code to complete the challenge. 

  * After they create the variable that will keep track of all the filters as a JavaScript object. you'll need to modify the event listener on line 62 that detects changes on each input element and calls the `updateFilters()` function.

  * In Steps 3-5, you'll need to write code in the `updateFilters();` function to hold all the values and ids of the filters that were changed on user input in the variable they created in Step 1. If you have a difficult time with this part, we have provided a video for them.

  * In Steps 7-10, you'll need to write code in the `filterTable();` function to filter the dataset based on the search critieria that is stored in the filters object.  In this function, you'll need to use the `forEach(([key, value])` as they are looping through the filters and then use the `filter` method to filter the table data based on the value for the row's property.

  * Finally, you'll need to rebuild the table based on the filtered data. 


## Deliverable 2: A written report on the UFO analysis (README.md) 

Again, the goal of the writing assignment is for you to present your findings in a logical manner. As a reminder, you should use appropriate grammar and structure when writing.

For the written analysis, you should use the repository README.md to write your report. The report will contain three sections: an overview of the analysis, results, and summary.

**Overview of Project:** The purpose of this project is to provide a dynamic webpage that is can be filtered based on specific criteria on UFO sightings Dana is looking for. 

**Results:** Dana can specifically filter by any combination of date, city, state, country, or shape. Simply enter the specific details in the filters on the left side of the page, and press "enter." The results in the table on the right side will reflect the searched criteria.

The webpage can be found here: https://tabathamurray.github.io/UFOs/.

**Summary:** One of the main drawbacks is there is no way of knowing what specific parameter to use, and therefore, the end user can wind up with too much data, or too little if trying to use too many filters. Also, because these filters are specific, there is no room for error (typos). Perhaps a drop down filters would be better. This will alleviate any typos Dana, or the end-user, might enter.

The README.md document should be in the home directory of your repository. All links to images should be formatted and displayed where appropriate.

## Submission

Make sure they upload the following to your GitHub repository:

1. The updated `app.js` file with the code for the challenge.
2. The updated `index.html` file in the template folder.
3. The `data.js` file.
4. An updated README.md that has your written analysis.

## Grading Rubric

The [UFOs Grading Rubric](./Resources/Module_11_Challenge_Grading_Rubric.pdf) is provided for you to use when grading you' submissions.

(https://tabathamurray.github.io/UFOs/)
