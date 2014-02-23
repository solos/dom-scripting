all: clean update

clean:
	@echo "Cleaning..."
	sudo rm -r /usr/share/nginx/www/solos/*

update:
	@echo "Updating..."
	sudo cp -r ./* /usr/share/nginx/www/solos/
	@echo "Done..."
