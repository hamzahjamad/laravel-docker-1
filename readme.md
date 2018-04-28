## Demo repo for blog re: docker + laravel

- [x] [Part 1 - development](https://medium.com/@shakyShane/laravel-docker-part-1-setup-for-development-e3daaefaf3c)
- [ ] Part 2 - production (coming soon)


## Fixing 'Server Returns Code 500' Error
To fix the code 500 issue, try run the following commands from the root of the project 
- `sudo chgrp -R www-data storage`
- `sudo chgrp -R www-data bootstrap/cache`
- `sudo chmod -R g+w storage`
- `sudo chmod -R g+w bootstrap/cache`