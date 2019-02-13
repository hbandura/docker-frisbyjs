# docker-frisbyjs
Docker image for frisbyjs testing

## Usage

Run `docker run -v mytestfolder:/workdir/__tests__:ro hbandura/frisbyjs [jest params]`

If you need to change the jest config file, mount the workdir directly:
`docker run -v myworkdir:/workdir:ro hbandura/frisbyjs [jest params]` where `myworkdir` holds your `jest.config.js` file, plus all tests.
