# 홍보

## AlphaFold2를 넘어서

- AlphaFold2는 분명히 유용한 도구이다.
- 그러나 너무 많은 memory를 요구한다.
- Monomer의 경우 gaming 제품군으로 충분함.
- Multimer 추론의 경우 residue의 개수가 굉장히 많음.
- DeepMind의 원본 구현은 NVIDIA A100 80GB에서도 2048개 이상의 residue를 처리하지 못함.
- 백지장도 맞들면 낫다.
- 분산처리를 구현한다.

## MegaFold

- 여러개의 GPU를 사용한다.

![pipeline](pipeline.pdf)

- (a) AF에서 자주 등장하는 구조. (b) Model 병렬화.

![par](par.pdf)

## 광고

오늘 poster 발표합니다!

![poster](poster.png)
