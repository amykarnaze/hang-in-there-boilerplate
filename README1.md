# Hang In There

A boilerplate repository designed to teach individuals how to create posters from an array of quotes, titles, and images. This  repository will document.querySelector, event Listeners, and functions to navigate a page. This includes making your own poster using a form and using buttons to hide and move between pages. Creating an object from a class is utilized as well.

## Set Up

1. Fork this repository
2. Go to settings and turn on GitHub Pages for this repository
3. All teammates: clone down this repository
4. `cd` into the repository
5. Run `open index.html` to view it in the browser

## Progression

### Iteration 0 - Main Page

https://media.giphy.com/media/l0cg5JNaBj8f8MRmwI/giphy.gif

- When the page loads, we should see a poster with a randomly selected image, title, and quote

### Iteration 1 - Switching Views

Form page:
https://media.giphy.com/media/l0cg5JNaBj8f8MRmwI/giphy.gif


- When a user clicks the "Make Your Own Poster" button, we should see the form, and the main poster should be hidden
- When a user clicks the "View Saved Posters" button, we should see the saved posters area, and the main poster should be hidden
- When a user clicks the "Nevermind, take me back!" or "Back to Main" buttons, we should only see the main poster section
- In summary: Be able to switch between the three views (main poster, form, and saved posters) on the correct button clicks

## Iteration 2 - Creating a New Poster

Form being filled out:
https://media.giphy.com/media/l0cg5JNaBj8f8MRmwI/giphy.gif

Once poster is saved:
https://media.giphy.com/media/WUD74FcJ7MzscVj1CX/giphy.gif

- On the new poster form view, users should be able to fill out the three input fields and then hit the save button
- When the save button is clicked, several things will happen:
  - Save the submitted data into the respective arrays (image URL into the images array, etc) so that future random posters can use the user-created data
  - Use the values from the inputs to create a new instance of our Poster class
  - Change back to the main poster view (hiding the form view again)
  - Display the newly created poster image, title, and quote in the main view

## Iteration 3 - Saving & Viewing Posters

Saved posters view:

- When a user clicks the "Save This Poster" button, the current main poster will be added to the `savedPosters` array.

Project spec & rubric: (https://frontend.turing.io/projects/module-1/hang-in-there.html)

Project Page: https://github.com/amykarnaze/hang-in-there-boilerplate

Project contributors:
Amy Karnaze https://github.com/amykarnaze
Jim Charnesky https://github.com/BigBike96
