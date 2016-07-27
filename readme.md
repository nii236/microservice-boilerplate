# Project Name

This was a result of the work from my [nii-finance project](https://github.com/nii236/nii-finance).

It aims to get a developer up and running with the bare minimum required to run a microservice with:

- Message broker
- Message transport
- Service discovery/registry
- Configuration
- Web API
- Metrics and instrumentation
- Sidecar proxy
- Centralised logging
- Centralised database (relational and time-series)

It is up to the developer to add containers to the `docker-compose.yml` file to add new services.

## Dependencies

- [Docker](docker.com)

## Installation and Usage

```
git clone git@github.com:nii236/microservice-boilerplate.git
docker-compose up
open localhost:8080
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
