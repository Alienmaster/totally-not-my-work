README

This is a copy of the RC3-2D-World for personal use.

How to Use:

Step 1: Serve the files via HTTPS, e.g. copy all files on a webspace with a HTTPS-URL (notice: the Header "Access-Control-Allow-Origin: *" needs to be set, therefor I added a .htaccess in the files)
Step 2: Go to https://play.workadventu.re/_/global/www.example.org/rwd-cache-lobby.maps.at.rc3.world-main.json-4c22f00e.new.json (if you serve your files under https://www.example.org/)
Step 3: there is no step 3 - ENJOY

If you have no webspace, you can serve the files from your local computer, e.g. via caddy (caddyserver.com) and localtunnel. Therefor execute the following command in the file directory:

caddy run
npm install -g localtunnel
lt --port 8000
