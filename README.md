## 1. how to build the dockers
cd docker && ./build_dockerfile.sh

----

## 2. How to run benchmark codes
./run_docker_benchmarks.sh

Note:
- you can modify the number of experiment iterations, the number of epochs, the systems(e.g. cpu, gpu, 4-gpu), the models(mnist_mlp, resnet50, lstm_synthetic), and the frameworks(mxnet, tensorflow).

----

## 3. How to plot the results
- you can refer to a summary_benchmarks.ipynb
