## Ghost blogging platform on Google Cloud Run

[Ghost](https://ghost.org/) is a popular Blogging platform written in Node Js. You can find the code on [Github](https://github.com/TryGhost/Ghost). 
This is a repo to run it
on [Google Cloud Run](https://cloud.google.com/run/).

### Run it locally with docker compose

Just do:

```bash
docker-compose up
```

Then go to your browser as `http://localhost:8080`

#### Files

Data folder with `content` and `images` is used as a volume to make adding posts/editing and image uploads work locally and keep it persisted.

### Run it on Google Cloud Run

[![Run on Google Cloud](https://storage.googleapis.com/cloudrun/button.svg)](https://console.cloud.google.com/cloudshell/editor?shellonly=true&cloudshell_image=gcr.io/cloudrun/button&cloudshell_git_repo=https://github.com/geshan/ghost-google-cloud-run.git)
