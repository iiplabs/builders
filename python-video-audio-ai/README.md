# python-video-audio-ai

## Additional Docker notes

### Docker based builder

docker build --tag videoai:0.0.1 --file Dockerfile .

### Run Python scripts through builder

docker run -v $PWD:/workdir -w /workdir --rm videoai:0.0.1 /bin/bash -c "python3 myPythonScript.py"
