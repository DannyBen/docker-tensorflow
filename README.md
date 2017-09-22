Tensorflow Pyhon3 Docker Image
==================================================

Usage
--------------------------------------------------

With docker compose:

```yaml
version: '3'

services:
  bash: &default
    image: dannyben/tensorflow
    volumes: 
    - ./app:/app

  python:
    <<: *default
    entrypoint: python
```


