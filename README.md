# This repo demos the linter not working in docker

If you run `pants test ::` it runs the test in docker as prescribed by the BUILD file. If you run `pants lint ::` though, it ignores the docker_environment other than to print a warning saying that the docker_environment will be ignored. 
