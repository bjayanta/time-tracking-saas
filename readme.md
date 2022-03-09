# Time Tracking App

I am going to build a time tracking SaaS application from scratch using Django and React JS. 

Inspired from [Stein - Code With Stein](https://www.youtube.com/channel/UCfVoYvY8BfTDeF63JQmQJvg).

### Todo list for part 1
- Create a virtual environment and activate it
- Install Django and create an empty project
- Initialize the database and create a super user
- Start the development server and test. Also, log in to the admin area.
- Create a Django app for the core views
- Create the base template file
- Create the front page
- Create a very simple privacy policy and terms of agreements page
- Create a page for showing the different pricing plans

### Todo list for part 2
- Create a new Django app for user profile
- Create view and template for sign up
- Create template for log in 
- Create a simple "my account" page
- Make it possible to log out 
- Make it possible to edit your user profile 

<b>Validate email:</b>

```js
validateEmail(email) {
    if (/^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/.test(email)) {
        return true;
    }

    return false;
}
```

### Todo list for part 3
- Fix small things from previous video 
    - Move sign up view to core app
    - Move templates to the core app (update urls.py)
    - Add the links/info below sign up and log in form 
    Show username in the my account button 
    - Hide the plans link in the menu 
- Create a new Django app for teams 
- Create a view and template for adding teams
- Show your teams on the account page 
- Make it possible to view a team 
- Make it possible to edit a team 

### Todo list for part 4
- Fix a few small things 
    - Add color to the navigation bar 
    - Show userprofile in the admin area 
- Create a new app and models for projects  
- Show a list of projects (Model for adding projects) 
- Show detail view of a project
- Make it possible to edit projects
- Create models for the tasks 
- Show a list of tasks 
- Make it possible to add tasks
- Show detail view of a task 
- Make it possible to edit tasks 

Credit goes to [Code With Stein](https://www.youtube.com/watch?v=Sdbh1uHwcrw&list=PLpyspNLjzwBkm7Y28Gma4F9hl2wpuypgp&index=2).

Thanks
