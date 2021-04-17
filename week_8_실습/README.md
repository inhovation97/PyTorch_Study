# VGG & resnet - transfer learning
> transfer learning에서는 통상적으로 SGD를 쓴다는 것에 의문을 가지고, 논문을 참고하여 Adam으로 성능을 내봄. [(블로그 포스팅)](https://inhovation97.tistory.com/32)   
>       
> cifar10 데이터를 90% 이상의 성능을 내보려고 많이 노력했고, 위 논문을 통해 얻은 하이퍼 파라미터로 resnet 50기준 84% 정도의 성능이 나왔음   
>    
> 더 좋은 성능을 위해 많은 고민을 했는데, lr scheduler를 뺴고나니 98% 까지 높은 성능을 얻어냄.   
### **Adaptive optimizer인 Adam에 lr scheduler는 오히려 학습에 있어서 나쁜 영향을 미쳤던 것임**
