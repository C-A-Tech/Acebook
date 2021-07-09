# AceBook

Acebook is a facebook inspired social media platform built with Ruby on Rails and PostgreSQL as a relational database.

Features include:
  - Sign up
  - Log in and out
  - Upload a post with or without an image
  - Like and comment on other peoples posts
  - Delete your own posts or comments
  - Invite a user to become friends
  - Accept or reject friend requests
  - View other users profiles (shows all their posts)
  - Switch to dark mode
  - Edit my profile details such as name and email
  - Display a nickname as opposed to a full name
  - Upload a profile picture
  
## Video Demo of User Experience

https://user-images.githubusercontent.com/69041095/125094545-42e1a880-e0cb-11eb-8b11-fe7831419c27.mp4



## Quickstart

First, clone this repository. Then:

```bash
> bundle install
> bin/rails db:create
> bin/rails db:migrate

> bundle exec rspec # Run the tests to ensure it works
> bin/rails server # Start the server at localhost:3000
```

## Troubleshooting

If you don't have Node.js installed yet, you might run into this error when running rspec:

```
ExecJS::RuntimeUnavailable:
  Could not find a JavaScript runtime. See https://github.com/rails/execjs for a list of available runtimes.
 ```

Rails requires a Javascript runtime to work. The easiest way is to install Node by running `brew install node` - and then run `bundle exec rspec` again
.

https://guarded-lake-46388.herokuapp.com/
