# AceBook

## User Experience (Video Demo)

<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="demo/demo-poster-image.png">
    <source src="demo/Acebook-demo.mp4" type="video/mp4">
  </video>
</figure>

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
