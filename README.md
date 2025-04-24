# hello
Hello Everyone

If repository is not found in master docker machine
```git clone <repository-url>```

```cd <project-folder>```


# to pull the latest changes from the remote repository
```git pull origin main```

# to create a docker image for a repository with an existing Dockerfile
```docker buildx build -t <any-tagname> .```

# to run the docker image
```docker run -p 3000:3000 <any-tagname>```

# here map any port to machine port