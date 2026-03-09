# Welcome to My Api
***

## Task
The challenge was to build a high-performance, secure REST API for a dataset of over 1,000 volcanoes. 
The primary hurdles were implementing JWT authentication, providing OpenAPI (Swagger) documentation, and 
meeting strict performance requirements for large data retrieval.

## Description
I developed a Ruby on Rails API using JWT for secure user sessions and Redis for server-side caching. 
By wrapping the volcano index in a Rails.cache block, I reduced database load and achieved near-instant 
response times for the 1,000+ record dataset.

## Installation
Clone & Install: bundle install

Database Setup: bin/rails db:prepare

Start Services: * Start Redis: redis-server --daemonize yes

Start Rails: bin/rails s -p 3001

## Usage
Authentication: Send a POST request to /login with credentials to receive a JWT.

Data: Use the token to access GET /volcanoes.

Documentation: View the full API specification at [THE_URL]/swagger/swagger.yaml.
```
./my_project argument1 argument2
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
