# 吳承儒
# 智慧商務系
## 助理教授

# 安裝步驟手冊

## 系統需求
- 作業系統：Windows, macOS, Linux
- Python 版本：3.6 以上
- Node.js 版本：12 以上

## 安裝步驟

### 1. 克隆專案
首先，使用以下指令將專案克隆到本地端：
```bash
git clone https://github.com/your-repo/your-project.git
cd your-project

python -m venv venv
source venv/bin/activate  # 對於 macOS/Linux
venv\Scripts\activate  # 對於 Windows

pip install -r requirements.txt

npm install
DATABASE_URL=your_database_url
SECRET_KEY=your_secret_key

python manage.py migrate

python manage.py runserver