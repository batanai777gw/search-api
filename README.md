#batanai gwanyanya
This api contains images i will be using to fetch and display on my Next.js-lazy-loading-search-sorting web application (also available on my GitHub). The application displays images, searching for a specific image(s) using key words and sorting them either in asc or dsc order. Find information on how to use docker for your applications below. Credits to @Scalable Scripts youtube channel for providing this api and programming tutorials.



# Usage

Make sure to install docker first https://www.docker.com/products/docker-desktop. After you installed docker run these commands

```
docker-compose up -d
```
Then after the images are pulled and are running run this command
```
docker exec backend /bin/sh start.sh
```
The API is ready to be consumed on `http://localhost:8000`
