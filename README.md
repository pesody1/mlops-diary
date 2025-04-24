# mlops-diary

# MLOps Day 1 - EC2 실습

## 🔑 실습 목표
- AWS EC2 생성
- 키페어 (.pem) 생성 및 보안그룹 설정 ((++ mlops-key.pem))
- SSH 접속 테스트
- Python 설치

## 📌 IP 주소
- 퍼블릭 IP: `54.180.150.10`

## ✅ 실행한 명령어
```bash
chmod 400 mlops-key.pem
ssh -i mlops-key.pem ubuntu@54.180.150.10
sudo apt update
sudo apt install python3 -y
