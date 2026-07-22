# Demo API

\# DemoApi



Repository dùng để demo và kiểm thử ApiGuard.



\## Mục đích



Repository này mô phỏng một dự án có (Swagger).



Khi có Pull Request:



\- GitHub Actions sẽ chạy ApiGuard

\- ApiGuard sẽ so sánh Swagger của main và Pull Request

\- Nếu phát hiện Breaking Changes sẽ tạo báo cáo và comment vào Pull Request.



\## Files



\- swagger.json : OpenAPI Specification

\- apiguard.json : cấu hình ApiGuard

\- .github/workflows/compare.yml : GitHub Actions

