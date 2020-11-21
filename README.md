# SORMAS-data-generator
Goal of this project is to generate and import credible test data into SORMAS. This is usable for:
1. showcases and demos
1. performance testing
1. [SORMAS-Stats](https://github.com/hzi-braunschweig/SORMAS-Stats)
1. a replacement of the SORMAS dev mode

# Caveats
* Very early stage of development, DO NOT CONNECT IT TO A PRODUCTION SYSTEM
* Only works with SORMAS version 1.49.1 because of this [issue](https://github.com/hzi-braunschweig/SORMAS-Project/issues/3293)


# Run it
`docker-compose up -d`: This will start a minimal stack of [SORMAS-Docker](https://github.com/hzi-braunschweig/SORMAS-Docker) which receives the generated data
`$data-gen: ./gen-client.sh && source venv/bin/activate && python main.py`
 