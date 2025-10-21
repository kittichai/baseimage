# Dockerfile สำหรับ base image Golang
ARG GO_VERSION=1.19.3
FROM golang:${GO_VERSION}

# อัปเดต package และติดตั้งเครื่องมือที่จำเป็น (ถ้าต้องการ)
RUN apt-get update && apt-get install -y \
    ca-certificates \
    && rm -rf /var/lib/apt/lists/*