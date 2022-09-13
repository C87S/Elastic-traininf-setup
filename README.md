# Elastic-training-setup

Sets up an instance of the Elastic stack, 2 nodes and kibana.

1. Install docker and docker compose
2. Copy docker-compose and .env to working directory
3. Modify values in .env to suit requirements
4. **sysctl -w vm.max_map_count=262144** in terminal
5. sudo docker compose up -d



