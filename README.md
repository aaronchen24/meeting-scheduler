# Meeting-Scheduler

This application allows groups of people to coordinate the best mutual time to meet up. Each member registers an account and store his or her best times to meet up. The website collects all of the data from every member and displays the best times to meet using a gradient color scale. The darker the color, the more people that can meet at that time. When the user hovers over a date, on the side will appear two lists: one with who is available at the time and one with who is not available. Lastly, because a gradient color scheme prevents people with colorblindness from effectively using the application, the best times and dates will explicitly be stated.

Possible additional features:  
Best/available locations as well . 
Link to Google Calendar, automatically block out times at which user has events --> then have user deselect other times at which they're busy
Email users once time is decided
JavaScript to instantly display feedback
3D visualization??
Allow users to prefer certain available times

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

Taking in user input successfully, calculating correctly the best time, and displaying the result (as well as the input pages of the website) in correct, aesthetically pleasing HTML/CSS.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

All of the above, plus allowing users to create accounts and edit their inputs, as well as JavaScript that allows instant feedback, based on what others have inputted, when the user enters their input.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

All of the above, plus creating visualizations of calendars where different colors represent different levels of group availability, and having these visualizations update automatically as the user changes their input.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

The first step will be creating a web application using Flask with a few page routes, most importantly an index page and a results page. To store the data that we will be receiving from users, we will want to create a SQL database that will track user availability. In order to implement the functionality of the web app pages, it will be important to create corresponding HTML templates, having the one for the index page include a form that’ll ask for times during which the user is available. We will also create a CSS page in order to style the website in an aesthetically pleasing way. We will need to research different form types that will efficiently allow for users to input their schedules into the database. In addition, for the more complex parts of the project, we will want to research different ways to generate and display graphics that illustrate the ideal meeting times of a group. Ideally everyone will work on every part of the project; however, if we need to segment the workload, one person can work in Python to create the web app, a second person can create the HTML and CSS portions, while the third person can look into the JavaScript and data visualization parts of the project.
