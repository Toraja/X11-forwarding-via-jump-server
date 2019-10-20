# X11 forwarding via jump server

## Instructions
1. Run `generate-key.sh` to generate key.  
   NOTE: Keys generated are password-less.
1. `docker-compose up`
1. `docker-compose exec --env DISPLAY=$DISPLAY origin ssh dest`  
  (Given `DISPLAY` variable is set properly on host)
1. Run `xeyes`
