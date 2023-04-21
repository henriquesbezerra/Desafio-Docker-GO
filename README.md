
# to build image
docker build . -t henriquesbezerra/fullcycle   


# cmd to build image
docker build -t <hub-user>/<repo-name>[:<tag>]

# cmd to tag image
docker tag <existing-image> <hub-user>/<repo-name>[:<tag>]

# cmd to publish imag
docker push <hub-user>/<repo-name>:<tag>