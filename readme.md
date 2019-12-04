- I write a docker-compose file to do the whole thing. 

  Just run `sudo docker-compose -f docker-compose.yml up -d`

  Then all dockers are on their way!

  Test with `sudo docker run -it --net=host --rm dplsming/sockshop-test:0.1 http://localhost:80 correctness`

  All things will be working well.

- 

