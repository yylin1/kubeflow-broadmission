FROM tensorflow/tensorflow:nightly-devel

RUN apt-get update && apt-get install -y --no-install-recommends \
    ca-certificates \
    build-essential \
    git

RUN mkdir -p /opt

RUN git clone https://github.com/tensorflow/benchmarks.git   /opt/tf-benchmarks

#WORKDIR /benchmarks/scripts/tf_cnn_benchmarks
CMD ["/bin/bash"]
