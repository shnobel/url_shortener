## Task:

We need to make an HTTP service to shorten URLs like [Bitly](https://bitly.com/) and other services.

No UI is needed, just make a JSON API service.  
It should be possible: 
- save a short representation of a given URL
- navigate to the previously saved short view and get redirected to the corresponding original URL

### Requirements:

- Programming language: Go
- Provide instructions for launching the application. Ideally (but not necessarily) use containerization with the ability to launch the project with the [`docker-compose up`](https://docs.docker.com/compose/) command
- There are no requirements for the technologies used - you can use any database for persistence

### Complications:

- Written tests (try to achieve coverage of 70% or more)
- Added URL validation to check the correctness of the link
- Added the ability to set custom links so that the user can make them human-readable - [http://bit.ly/avito-auto-be](http://bit.ly/avito-auto-be)
- Load testing was carried out to understand what reading load our service can withstand
- If you suddenly want, you can put together a simple UI and put the service on free hosting - Google Cloud, AWS, and the like.
