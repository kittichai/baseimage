# Dockerfile สำหรับ base image Golang ใช้ Alpine
ARG GO_VERSION=1.24.2
FROM golang:${GO_VERSION}-alpine

# อัปเดต package และติดตั้งเครื่องมือที่จำเป็น (ถ้าต้องการ)
RUN apk update && apk add --no-cache \
    ca-certificates \
    && update-ca-certificates