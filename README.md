# 🤖 Chatbot AI Biết SQL – Truy Vấn CSDL Với LangChain + GPT + SQLite

Chatbot này có khả năng **hiểu ngôn ngữ tự nhiên tiếng Việt**, **tự sinh câu lệnh SQL**, và **truy vấn trực tiếp cơ sở dữ liệu SQLite**.  
Dự án đơn giản, chạy được ngay trên Google Colab mà **không cần backend hay server phức tạp**.

## 📂 Danh sách file

| Tên file | Mô tả |
|----------|------|
| `Chatbot_sql.ipynb` | Notebook chính để chạy chatbot, tích hợp LangChain, GPT và giao diện Gradio. |
| `create_data.ipynb` | Tạo cơ sở dữ liệu mẫu `products.db` gồm bảng `products` và `categories`. |
| `products.db` | Cơ sở dữ liệu SQLite mẫu dùng cho truy vấn. |

## 🧠 Công nghệ sử dụng

- [LangChain](https://www.langchain.com/)
- [OpenAI GPT (gpt-4)](https://platform.openai.com/)
- [SQLite](https://www.sqlite.org/)
- [Gradio](https://gradio.app/) – tạo giao diện tương tác

## 🚀 Tính năng nổi bật

✅ Hiểu ngôn ngữ tự nhiên tiếng Việt  
✅ Truy vấn cơ sở dữ liệu thông qua SQL Agent  
✅ Tự động chọn ví dụ phù hợp (Few-shot Prompting + Semantic Search)  
✅ Giao diện đơn giản, thân thiện với người dùng

## 💬 Ví dụ truy vấn chatbot

- "Liệt kê các sản phẩm giá dưới 300k"
- "Danh mục Thời Trang Nam có những gì?"
- "Có bao nhiêu danh mục sản phẩm?"

## 📦 Cài đặt & chạy thử

Chạy trên Google Colab
1. Mở `Chatbot_sql.ipynb` trên [Colab](https://colab.research.google.com/)
2. Chạy từng cell theo thứ tự
3. Giao diện Gradio sẽ hiện ra, có thể hỏi chatbot trực tiếp


