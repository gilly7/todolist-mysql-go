# todolist-mysql-go
A classic and simple Golang API server that connects to a Frontend page.
The Golang API server uses:

- MySQL as the database
- GORM as ORM to interacting with the database
- Request router using gorilla/mux
- Logrus for logging
- 

# Build a Todolist API Server in Golang
How our entire app works
- Step 1: Bootstrap a project
- Step 2: Connect to MySQL DB
- Step 3: Auto migrate TodoItem ORM Model
- Step 4: Create Todo Item operation
- Step 5: Continue with the rest of CRUD operations
- Step 6: Connect with Frontend
- Step 7: Build the package

# The specifications for our API Server are:

- It listens to port 8000 on localhost
- It has 5 endpoints: healthz, createItem, getCompletedItems, getIncompleteItems, updateItemand deleteItem
- TodoItem model consists of Id, Description and Completed status attributes.
- The web frontend will execute AJAX requests to localhost:8000 for all operations. Check this JS script to see how it works first. The initial code was made by themaxsandelin . [https://github.com/sdil/todo/tree/master/resources/js]
# Voila!! A little end-to-end demonstration
# Don’t Stop Learning

Inspired by [https://www.fadhil-blog.dev/blog/golang-todolist/]
