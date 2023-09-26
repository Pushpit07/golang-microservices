Microservices in GoLang

`go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.27`

`go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.2`

`protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative logs.proto`

`docker swarm join --token SWMTKN-1-1ggyzt0ywn52wb07kj7ginu7wepkzeqn71fucgkbx7p3n4k9ka-a543kw1ww6pdrbrosj58gkzrc 192.168.65.3:2377`

`docker swarm join-token manager`

`docker stack deploy -c swarm.yml go-microservices`

`docker service ls`

`docker service scale go-microservices_listener-service=3`

`go test -v .`