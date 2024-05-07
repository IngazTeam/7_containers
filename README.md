
#!/bin/bash

# Project Zero
echo "Accessing project_zero..."
cd project_zero

echo "Running commands for project_zero..."
docker-compose up -d
docker-compose run --rm composer install
docker-compose run --rm artisan key:generate

# Project One
echo "Accessing project_one..."
cd ../project_one

echo "Running commands for project_one..."
docker-compose up -d
docker-compose run --rm composer install
docker-compose run --rm artisan key:generate

# Add more projects as needed, following the same pattern

# Project Two
echo "Accessing project_two..."
cd ../project_two

echo "Running commands for project_two..."
docker-compose up -d
docker-compose run --rm composer install
docker-compose run --rm artisan key:generate

# Add more projects as needed, following the same pattern


# Project There
echo "Accessing project_there..."
cd ../project_there

echo "Running commands for project_there..."
docker-compose up -d
docker-compose run --rm composer install
docker-compose run --rm artisan key:generate

# Add more projects as needed, following the same pattern


# Project Fourth
echo "Accessing project_there..."
cd ../project_fourth

echo "Running commands for project_fourth..."
docker-compose up -d
docker-compose run --rm composer install
docker-compose run --rm artisan key:generate

# Add more projects as needed, following the same pattern


# Project Fifth
echo "Accessing project_fifth..."
cd ../project_fifth

echo "Running commands for project_fifth..."
docker-compose up -d
docker-compose run --rm composer install
docker-compose run --rm artisan key:generate

# Add more projects as needed, following the same pattern


# Project Sixth
echo "Accessing project_sixth..."
cd ../project_sixth

echo "Running commands for project_sixth..."
docker-compose up -d
docker-compose run --rm composer install
docker-compose run --rm artisan key:generate

# Add more projects as needed, following the same pattern
