FROM gcr.io/oss-fuzz-base/base-builder-go@sha256:604d89aebb3e4d684af51b6b2d84ea8e8f19f2590c2558c258d90a18d057bf25
COPY . $SRC/atlantis
COPY .clusterfuzzlite/build.sh $SRC/build.sh
WORKDIR $SRC/atlantis
