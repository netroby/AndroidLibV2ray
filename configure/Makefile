pbSource := $(shell echo *.proto)
#%.pb.go:%.proto
#	protoc --go_out=. $^

pb: clean
	protoc --go_out=. $(pbSource)
	@echo "Done"

clean:
	-rm *.pb.go
