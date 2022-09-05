# Express.js-Note-Taker

## Table of Contents

1. [Description](#description)
2. [Resources](#resources)
3. [Visuals](#visuals)
4. [Author and Acknowledgements](#author-and-acknowledgements)

## Decription

The assignement requires students to use existing starter code to create an application that can be used to write and save notes. This application will use an Express.js back end. The application will save and retrieve data from a JSON file. It is my task to code the back end, connect the two, and then deploy the entire application to Heroku.

## Resources

- [LIVE SITE]()

- [Repository](https://github.com/Cinderbeast/Express.js-Note-Taker)

- [Heroku] (https://dry-dawn-71235.herokuapp.com/)


## Visuals

![Note Taker Screenshot]()

## Author and Acknowledgements

Code created by University of Utah Bootcamp, edited by Cindy

## Bonus

You haven’t learned how to handle DELETE requests, but this application offers that functionality on the front end. As a bonus, try to add the DELETE route to the application using the following guideline:

* `DELETE /api/notes/:id` should receive a query parameter that contains the id of a note to delete. To delete a note, you'll need to read all notes from the `db.json` file, remove the note with the given `id` property, and then rewrite the notes to the `db.json` file.
