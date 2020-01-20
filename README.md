# Gift List 

## Setup

### Running the application
To run the application one option is to run `docker-compose up`

### Running the frontend tests

#### Unit Tests
`docker-compose exec gift-list-frontend  ng test --watch=false`
#### E2E Tests
`docker-compose exec gift-list-frontend ng e2e --port 4202`

### Connecting to database
> Note be sure to have psql up-to-date or the connection will complain about some socket
> connection errors

`psql postgres://postgres:password@127.0.0.1:5432/postgres`