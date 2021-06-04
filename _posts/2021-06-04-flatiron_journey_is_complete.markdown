---
layout: post
title:      "Flatiron Journey is Complete"
date:       2021-06-04 20:22:03 +0000
permalink:  flatiron_journey_is_complete
---

With the completion of my final project, I have finished the Flatiron software engineering prorgam, the next step for me is to continue learing and strengthing my skills as a programmer while looking for an opportunity to begin my career in this industry. 

I am proud to say that I feel very confident in my ability to write clean and effective code both in the frontend and backend, but after going through the project review I noticed some areas I must improve on, specifically in React and Redux. One thing I struggled to understand was the redux thunk middleware I used in my project. Thunk was something I just thought of as something I needed for my redux store to work, but actually understanding what the middleware does makes everything I worked on so much clearer. The project review made me realize that calling the dispatch function in the component will make redux return a function with the dispatch method and state as an argument. Dispatch will then be called again inside of the thunk function to trigger the reducer and updated the redux store. this idea was very hard for me to grasp, but knowing how my code is working and flowing in this manner was an important lesson to learn.

setState is another method I gained more understanding of after this review, I knew how to use setState and the way it works, but I didn't know why I needed to use only this method when I wanted to change state in my component. Basically, trying to update the state directly won't change or update the DOM, since this way of changing state won't trigger the re-render function. Using setState will trigger the re-render function and update the DOM while the user changes state as they interact with the components on the browser. Knowing this was crucial for me, now I know changing the state directly is not an option.

Lastly, I learned that I need to be more comfortable using containers in my project to store my redux logic instead of placing this logic in my presentational components. Now that I have seen my completed project, implementing a couple of containers would have made my code look much neater and more organized. 

Completing this program is an incredibly satisfying experience. I have learned a great deal, but there is still so much for me to learn and work on to become the programmer I strive to be. My plan is to continue working on my own projects using the languages I worked in Flatiron, as well as others such as Java, and become comfortable creating a project with unique features. Not only do I want to work on my ability to code these projects, I want to be able to verbalize the code I have much better. I believe this is a weak spot for me since I am still relatively new to programming, but with practice I am confident I can improve this weakness of mine quickly. 

