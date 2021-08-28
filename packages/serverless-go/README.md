## serverless-go
## Local Development
1. Install go (`go1.17`)
2. Run `go mod download` 


### Makefile commands
#### `make deploy`
Create fresh build and deploy with `sls deploy --verbose`
### Invoking Lambda functions
1. `sls invoke -f hello`
2. `sls invoke -f world`