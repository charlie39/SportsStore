# SportsStore




An online sports store with *pwa features* where you can place order and purchase sports goodies. The data is serverd from http server via a REST API which is consumed by the appliction.


*for the pwa features, place your ssl certificates in ssl directory and set httpEnabled in the server.js to true.


*You can replace the placeholder data in serverdata.json and instead store in a database like mongodb.



# get started
> 1. Clone the repo:

>    `git clone https://github.com/charlie39/SportsStore.git`

> 2. Go to project directory

>     `cd SportsStore`

> 3. Install the dependencies:

>     `npm install`






# creating Docker image

> 1. In the project directory, run:

>  `docker build . -t sportstore -f dockerfile`

> 2. Run the docker container:

>  `docker run -p 80:8081 sportsstore`



*the data.js is a mock data for development

---------------------------------------------------------------------------
