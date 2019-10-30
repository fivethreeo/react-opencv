# Razzle With Docker Nginx Example

## How to use
Download the example [or clone it](https://github.com/fivethreeo/react-opencv.git):

```bash
curl https://codeload.github.com/fivethreeo/react-opencv/tar.gz/master | tar -xz react-opencv
cd react-opencv-master
```

Run:

```bash
sudo -E docker-compose -f docker-compose.yml up
```

With a https reverse proxy in front, run:

```bash
export RAZZLE_PUBLIC_SCHEME=https
export RAZZLE_PUBLIC_HOST=localhost
export RAZZLE_PUBLIC_PORT=443

sudo -E docker-compose -f docker-compose.yml up
```
## Idea behind the example
This is a basic, bare-bones example of how to use razzle. It satisfies the entry points
`src/index.js` for the server and and `src/client.js` for the browser.
