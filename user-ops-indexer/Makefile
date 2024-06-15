version = v1.2.0

run: 
	USER_OPS_INDEXER__CONFIG=./user-ops-indexer-server/config/base.toml cargo run --bin user-ops-indexer-server

build:
	docker build ./ -t ghcr.io/cogi-technology/user-ops-indexer:${version}

push:
	docker push ghcr.io/cogi-technology/user-ops-indexer:${version}