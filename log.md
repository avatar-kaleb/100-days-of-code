# 100 Days Of Code - Log

### Day 1: December 30th, 2018

**Today's Progress**: Began process of creating new form to add mental models to the mental model dictionary with high re-use of code, increasing maintainability.

**Thoughts:** I really think the Mental Model flow isn't bad, but the code standards will need to be updated as I've learned more with React, so in the near future, that will be one of the tasks I have :).

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)


### Day 2: December 31th, 2018

**Today's Progress**: Updated a page's props to destructuring to pass them down to correct pages. Added the ability to upload a new image using FileInput on ReactMD by creating a new firebase storage controller! Good day!

**Thoughts:** I added a bit of tech debt to our backlog to update controller apis or ui to use suspense for success/error/loading progress.

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 3: January 1st, 2019

**Today's Progress**: Updated the logic for the Create New Mental Model form to generate unique image names based on mental model titles (only allowed to select files once a title has been created). Secondly, if the title is created after a user selects an image, it will update the key as well. Began looking into generating unique keys on firebase paths instead of doing it on my own - will continue that tomorrow.

**Thoughts:** Creating great forms takes a bit of time, especially when adding in custom logic, needing validation, and removing duplicate code! I'm looking forward to see how this form actually ends up working out, hoping to craft some beautiful code :).

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 4: January 3rd, 2019

**Today's Progress**: Updated creating a mental model to now use a unique ID, which resulted in starting to mess with how we get the title of a mental model by that new ID. 

**Thoughts:** I still have some cleanup to do this weekend, and will definitely be focusing on that as the MentalModelEditor component is beginning to get a bit logic heavy.

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)


### Day 5: January 7th, 2019

**Today's Progress**: Continued updating the add new mental model functionality. The admin screen works fine, but not for regular users. I'm looking into adding a redirect to happen if a user tries to access a mental model editing screen on a mental model they didn't create. For now, I think I'll let Firebase handle after exploring it a bit today.

**Thoughts:** I'll be cleaning up the different poc type code I created these last few days to solidify the addition of the new mental models. The last steps will be to create some validation before pushing it out!

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 6: January 8th, 2019

**Today's Progress**: Continued updating the add new mental model functionality. First, I created a new way to add in firebase DB data about the user to a high order component, now allowing us to access both the firebase auth data alongside the db data. Happy about this! Second, I integrated that functionality to update UI when a user is in a route they shouldn't be :D.

**Thoughts:** I believe this will end up being pretty cool once the logic is finished and I clean up the code from all this exploration, looking forward to the end result for sure!!

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 7/8: January 9/10th, 2019

**Today's Progress**: Allowed users to delete mental models once they add one. Added some new functionality for new mental models like navigating to pages on submit succes, little things like that :D.

**Thoughts:** Deployed the POC code for new MMDs to prod, we'll see what people do :D.

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 9: January 13th, 2019

**Today's Progress**: Updated my personal site's styling to fix a mobile issue. Worked to change the rich text editor for the mental model dictionary, since the one I was using doesn't support Android.

**Thoughts:** Once I fix the new RTE code, will be adding validation to the form for people.

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 10: January 13th, 2019

**Today's Progress**: Fixed the mobile issue for rich text editors on the app, added some quick and easy validations to let users know why they can't submit.

**Thoughts:** Next stop - doing another hard look at the code to see what improvements I can make !

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 11/12: January 18-19th, 2019

**Today's Progress**: Added CI/CD for automated deployment with Firebase and Bitbucket Pipelines, added a dev environment to use for developers to test features with locally, and updated documents!

**Thoughts:** Need to get back to cleaning up the code, making sure all comments make sense, and be ready for better collaboration.

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 12/13: January 20-21th, 2019

**Today's Progress**: I cleaned up the code for mental model dictionary, documented standards, and tried to make sure all code followed it. I added stylelint to help catch SCSS standards, then followed that up by adding a tab layout to the main dictionary page. User's can now explore mental models, see their favorites, and edit their authored mental models quick and easy!

**Thoughts:** I'm progressing well on the features - feel like once I have a good base, then I'll look forward to checking out the little things that will make the app wonderful to use.

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 14: January 22nd, 2019

**Today's Progress**: I updated the routes to all use React Suspense and React Lazy, added new styles, and made the explore page / view mental model routes public.

**Thoughts:** Good day!

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)

### Day 15: January 23rd, 2019

**Today's Progress**: Created a basic feedback form that submits into firebase, added in a react error boundary, and hopefully fixed service worker error.

**Thoughts:** Learned quite a bit about the new features in react the last few days, looking forward to diving deeper into Firebase APIs the rest of this week to better handle success / errors.

**Link to work:** [Mental Model Dictionary](http://mentalmodeldictionary.com)
