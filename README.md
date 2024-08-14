# ai-template-backend-go

## Getting started 

### Running locally in development mode

- Copy all values of .env.example to .env file
- Run the following command line on your local machine

```shell
> docker-compose up -d
> go run main.go
```

### Running on TryDome platform
- Put the Stripe env value (test key can be found in the .env.example file) to env variable section
- Re-deploy service