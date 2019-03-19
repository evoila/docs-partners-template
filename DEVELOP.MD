# Extending Documentation
As the Bookbinder Gem is fundamentally broken with the current versions of Ruby, we have created a Docker Container. The container can be run via:

`docker run --rm -p 4567:4567 -v $PWD/:/app enat/bookbinder`

NOTE: Network connectivity is required to run the Docker container.

## Problems
Currently there is one bug we are aware of:
* Auto-reload is not working