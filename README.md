# jol_jak
### 1. 참고 내용
https://learnopencv.com/how-to-convert-a-model-from-pytorch-to-tensorrt-and-speed-up-inference/
<br>위의 주소 내용을 참조해주면 됩니당!

### 2. 원본 파일
https://github.com/spmallick/learnopencv/tree/master/PyTorch-ONNX-TensorRT

### 3. onnx 파일은 첨부 안 했어유!

### 4. pytorch_model_forwardtime
우리 실습 내용에서는 execution time을 구해야 하는데 원본에는 없길래.. 나름 검색해서 추가해본 파일! 맞는지는 모름...ㅎㅎ :D 참고만 plz

### 5. 내가 쓴 colab 환경
<img width="213" alt="colab 환경" src="https://user-images.githubusercontent.com/68731647/117491053-a4da4080-afaa-11eb-8f03-b906d5c6d28f.png">

### 6. tmi
그 시간 계산하는 부분에서 1000 나눠줬는데 나눠주는 게 맞는 건지 아닌지 100이나 10으로 나눠줘야 하는지는 모르겠다 ^_^... 흐흐
<br> 그런데 2번에서 1000으로 나눠줘야 time으로 구했을 때(1번)랑 거의 같길래 1000으로 나눴습니다.
