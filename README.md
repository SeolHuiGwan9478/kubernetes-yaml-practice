# Kubernetes Study Repository

<div align="center">
  <img width="150" alt="image" src="https://github.com/user-attachments/assets/f3cba15a-3461-43e7-af50-0713eb6482e0" />
</div>


## 📋 개요

이 레포지토리는 쿠버네티스(Kubernetes) 학습을 위한 실습용 YAML 예시 파일들을 모아둔 저장소입니다.

쿠버네티스의 다양한 리소스들을 실제로 배포하고 테스트해보면서 학습할 수 있도록 각 리소스별로 정리된 YAML 파일들을 제공합니다.

## 🎯 목적

- 쿠버네티스의 주요 리소스들에 대한 실습 예제 제공
- 각 리소스의 기본 구조와 설정 방법 학습
- 실제 운영 환경에서 사용할 수 있는 베스트 프랙티스 예시

## 📚 학습 자료

자세한 학습 내용과 이론은 아래 링크를 참조해주세요:

**[Cloud Club Activity - Kubernetes Study Guide](https://ddongdong-e.notion.site/Cloud-Club-Acitivity-27773721853f4150bce7294d9b6bca05?source=copy_link)**

## 🚀 사용 방법

1. 레포지토리를 클론합니다:
```bash
git clone <repository-url>
cd kubernetes-study
```

2. 각 디렉토리별로 YAML 파일을 확인하고 필요에 따라 수정합니다.

3. kubectl 명령어로 리소스를 배포합니다:
```bash
kubectl apply -f <yaml-file-name>
```

4. 배포된 리소스를 확인합니다:
```bash
kubectl get all
```

## 📝 주요 학습 리소스

- **Pods**: 쿠버네티스의 가장 작은 배포 단위
- **Services**: 파드 간 네트워킹 및 로드 밸런싱
- **Deployments**: 파드의 배포 및 관리
- **ConfigMaps & Secrets**: 설정 및 민감한 데이터 관리
- **Persistent Volumes**: 영구 스토리지 관리
- **Ingress**: 외부 트래픽 라우팅
- **Namespaces**: 리소스 격리
- **RBAC**: 역할 기반 접근 제어

## 🔧 필수 도구

- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [minikube](https://minikube.sigs.k8s.io/docs/start/) 또는 다른 쿠버네티스 클러스터

## 📖 학습 순서 권장

1. Namespaces
2. Pods
3. Services
4. ConfigMaps & Secrets
5. Deployments
6. Persistent Volumes
7. Ingress
8. RBAC

## 🤝 기여하기

이 레포지토리는 학습 목적으로 만들어졌습니다. 개선사항이나 추가하고 싶은 예제가 있다면 언제든지 Pull Request를 보내주세요!

## 📄 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다.

---

**Happy Learning Kubernetes! 🚀**
