# cirl-assignments

## Usage Instructions

1. Pull the latest version of `ggsolver` from `https://github.com/abhibp1993/ggsolver.git`. 

2. Pull the latest version of `cirl-assignments` from `https://github.com/abhibp1993/cirl-assignments.git`.

3. Pull the latest version of docker image `abhibp1993/ggsolver` using `docker pull abhibp1993/ggsolver`.

4. Run `docker run -it -p 8888:8888 -v <path to ggsolver>:/home/ggsolver 
   -v <path to cirl-assignments>:/home/cirl-assignments abhibp1993/ggsolver`

5. Run `cd /home/cirl-assignments/`

6. Run `jupyter notebook --allow-root --ip 0.0.0.0`

7. Use the link with `127.0.0.1/...` to open jupyter notebook on browser.



