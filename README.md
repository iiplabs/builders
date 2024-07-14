# builders

## Docker based builder

docker build --tag builders:0.0.1 --file Dockerfile .

## Run Python scripts through builder

docker run -v $PWD:/workdir -w /workdir --rm builders:0.0.1 /bin/bash -c "python3 getpasswordhash.py"
