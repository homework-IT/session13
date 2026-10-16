# Base image JRE 21 siêu nhẹ, tối ưu tài nguyên và tốc độ khởi động
FROM eclipse-temurin:21-jre-alpine

WORKDIR /app

# Sao chép file jar đã build
COPY build/libs/*.jar app.jar

# Khai báo cổng ứng dụng
EXPOSE 8080

# Chạy ứng dụng
ENTRYPOINT ["java", "-jar", "app.jar"]