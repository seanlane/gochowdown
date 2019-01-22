default:
	hugo server

build:
	hugo --destination docs/

debug:
	hugo server -D

deploy:
	rm -r docs/
	hugo --destination docs/
	git add docs/
	git commit -m "Update live site"
	git push

update-theme:
	git submodule update --remote --merge
