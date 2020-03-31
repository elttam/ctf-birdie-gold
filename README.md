# Overview

**Title:** Birdie Gold  
**Category:** Crypto  
**Flag:** `libctf{2896a04a-1adc-4bf3-a254-b69daee1189e}`  
**Difficulty:** Medium

# Usage

The following will pull the latest 'elttam/ctf-birdie-gold' image from DockerHub, run a new container named 'libctfso-birdie-gold', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-birdie-gold \
  elttam/ctf-birdie-gold:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-birdie-gold' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-birdie-gold:latest
```
