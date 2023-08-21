PROTO_DIR = proto
PACKAGE = shiva-proto
all:
	protoc -I${PROTO_DIR} --go_opt=module=${PACKAGE} --go_out=. ${PROTO_DIR}/*.proto
