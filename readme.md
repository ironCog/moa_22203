#Refactor mongoose code
* Create a models directory
* Use module.exports
* Require everything correctly

#Add Seeds File
* Add seeds.js file
* Run the seeds file every time the server starts

#Add the Comment model
* Make our errors go away
* Display comments on campground show page

#Comment New/Create
* Discus nested routes
* Add the Comment and create routes
* Add the new Comment form


# Nested RESTful URLs

|name     | url                            |verb  |  desc                                  |
|:-------:|:-------------------------------|:----:|:---------------------------------------|
|INDEX    |/campgrounds                    | GET  |Display a list of all campgrounds       |
|NEW      |/campgrounds/new                | GET  |Display a form to make a new campground |
|CREATE   |/campgrounds                    | POST |Add a new campground to DB              |
|SHOW     |/campgrounds/:id                | GET  |Shows info about one campground         |
|         |                                |      |                                        |
|NEW      |/campgrounds/:id/comments/new   |
|CREATE   |/campgrounds/:id/comments|