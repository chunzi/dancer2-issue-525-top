
see <https://github.com/PerlDancer/Dancer2/issues/525>

start the server:

    perl bin/app.pl

test:

    chunzi@dock:~$ curl -XGET http://localhost:3000/
    top
    chunzi@dock:~$ curl -XPOST http://localhost:3000/
    top
    chunzi@dock:~$ curl -XPOST http://localhost:3000/sub
    chunzi@dock:~$ curl -XGET http://localhost:3000/sub
    top

