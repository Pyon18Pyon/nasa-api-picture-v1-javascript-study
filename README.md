# nasa-api-picture-v1-javascript-study

This project was completed as part of the Udemy course, [JavaScript Web Project: 20 Projects to Build Your Portfolio](https://www.udemy.com/course/javascript-web-projects-to-build-your-portfolio-resume/).

## What it does?

This app is incorporating the NASA API to get random astronomy pictures of the day. If we click on an image we can view the full resolution version of that image in a new tab. There is a **Favorites** button so it is able to store our favorite pictures. Click the **Load More** button to load more pictures. 

## Key features

- The results are formatted into cards with an image title.
- Ability to add images to the favorites which is accomplished by using localStorage.
- When **Add To Favorites** button is clicked a little pop up comes up and notifies us that the image has been added to favorites. If we click the same image again the pop up doesn't come up because it has already been added to the favorites object.
- Ability to remove images from the favorite page.
- Has the option to go back to the main page.
- Loading animation.
- When scroll down the page and press **Load More** it will scroll back up to the top of the page with 10 fresh images.
- These images are lazy loaded in order to improve performance.
- Mobile responsive.
