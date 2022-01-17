https://imgura-album.h4ck3r.quest/

Feel free to share some memes with me :D

You need to execute /readflag to get the flag.

--

Deployment guide
With docker

docker-compose up --build
That's all.

Without docker

Install PHP 8
Install composer, see https://getcomposer.org/download/
Install required packages
cd ./src && /path/to/composer.phar install
Run the server
cd ./src/html && php -S localhost:8000
Hint:
Why this author choose Flight framework to build this CTF challenge?
