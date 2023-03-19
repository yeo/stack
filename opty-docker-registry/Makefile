gen_pass:
	htpasswd -Bbc auth/registry.password username password-here

sync:
	rsync -ravp --exclude .git . m1:registry/

up:
	docker compose up -d
