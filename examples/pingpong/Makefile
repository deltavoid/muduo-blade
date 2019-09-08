

ROOT_DIR := ../../
SERVER_EXEC := blade-bin/examples/pingpong_server
CLIENT_EXEC := blade-bin/examples/pingpong_client

.PHONY: run_server run_client


run_server:
	cd $(ROOT_DIR) && $(SERVER_EXEC) localhost 1234 20

run_client: 
	cd $(ROOT_DIR) && $(CLIENT_EXEC) localhost 1234 20 10240 40 100

