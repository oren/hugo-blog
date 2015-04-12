# Hugo Blog with Docker

## Setup 

    git clone git@github.com:oren/hugo-blog.git
    cd hugo-blog/site
    git clone git@github.com:spf13/hugoThemes.git

## Run

    docker-compose up -d

or

    docker-compose run --service-ports app hugo server -t nofancy

(from some reason the themes are not working)
 
 open [http://localhost:1313](http://localhost:1313)
