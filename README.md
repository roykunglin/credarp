# Set up Environment

Install ruby before everthing.

```
$ bundle install
$ rake preview
```

Browsse [http://localhost:4000](http://localhost:4000).

# Manual:

## Create a post:

Example：

```
$ rake post title="Tittle"
```
Check your _post/ directory. You will see the file named like : `2013-08-11-tittle.md`

After create the post, you can edit it.

### (Optional) set post date:

```
$ rake post title="Title" [date="2013-10-06"]
```

## Preview:

```
$ rake preview
```

Browsse [http://localhost:4000](http://localhost:4000).

## Deploy

Commit all of your files and push to master and run the command below:
```
$ rake build    # Compile all files into the build directory
$ rake publish  # Build and publish to Github Pages
```

# Contributors

- [@garylai1990](http://github.com/garylai1990)
- [@roykunglin](http://github.com/roykunglin)

