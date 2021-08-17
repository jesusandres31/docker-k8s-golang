- provide a list of urls

- loop through urls, report status

- run inside Kubernetes (docker container, k8s deployment file)

- command:
  set PING_URLS=https://google.com,https://twitterXXX.com & go run main.go
  docker run --rm --env PING_URLS=https://youtube.com jesusandres31/ping-service
