## serverless-chat
Serverless backend chat app with Go Lambdas
## Local Development
1. Install go (`go1.17`)
2. Run `go mod download` 


### Invoking Lambda functions
1. `sls invoke -f hello`
2. `sls invoke -f world`

### Deploy
#### run `make deploy`
Creates fresh build and deploy with `sls deploy --verbose`