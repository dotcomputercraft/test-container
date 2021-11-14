# demo: webapp in Google Cloud Run

## Contents
- `main.go` and `go.mod`: the actual helloworld web application written in golang
- `Dockerfile`: configuration to run the app in a docker container

### Building this builder

To build this builder with the default version, run the following command in this directory.
```sh
$ gcloud builds submit --config=cloudbuild.yaml
```
