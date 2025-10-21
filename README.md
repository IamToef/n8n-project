# 🚀 n8n Self-Hosted Project

Repo này chứa toàn bộ workflow, script và cấu hình docker-compose của hệ thống n8n chạy trên VPS.

## 📂 Cấu trúc
| Thư mục | Mô tả |
|----------|-------|
| `flows/` | Workflow JSON export từ n8n |
| `scripts/` | Các script hỗ trợ backup, import/export |
| `docs/` | Tài liệu hướng dẫn setup |
| `data/` | Dữ liệu n8n & database (được mount qua Docker volume) |

---

## ⚙️ Cách khởi chạy

```bash
cp .env.example .env
docker compose up -d
