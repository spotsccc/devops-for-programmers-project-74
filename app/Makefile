setup:
	npm ci

start:
	npm start

dev:
	docker-compose -f ../docker-compose.override.yml up

lint:
	npx eslint .

test:
	docker-compose -f ../docker-compose.yml up --abort-on-container-exit --exit-code-from app

heroku-logs:
	heroku logs --tail

prepare-env:
	cp -n .env.example .env
