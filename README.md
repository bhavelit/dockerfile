# dockerfile

IMAGETAG=bhanu

docker build -t jaibw/website004:$IMAGETAG .
docker push jaibw/website004:$IMAGETAG
