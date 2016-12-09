This works on docker for Mac

Run the Ozark image

docker run -ti -p 4848:4848 -p 8080:8080 glassfish/ozark
Open browser window at http://localhost:8080/samples

Use http://localhost:4848/ to log into GF console using username:admin password:ozark.
