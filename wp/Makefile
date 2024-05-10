.PHONY: config

config: 
	@echo "Configuring WordPress..."
	docker run -v $(PWD):/var/www/html -v $(PWD):/app composer:latest composer install
