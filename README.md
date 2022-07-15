# sigma_landing_page

Sigma Solution

## Design: 
- [Link figma](https://www.figma.com/file/GcJpbnsGjBG7prXhUpSKgd/Sigma_Solution?node-id=0%3A1)

## Công nghệ sử dụng

- HTML5
- CSS Framework: [bootstrap v5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)

## Ngôn ngữ lập trình

- Javascript

## Editor

- Visual Studio Code
- Extension: Live Server

## Linters and Formatters

- Eslint
- Prettier

## Phân chia công việc

| STT | Feature              | Người phụ trách   | Mô tả                    |
| :-: | -------------------- | ----------------- | ------------------------ |
|  1  | Main layout          | Nguyễn Văn Hồng   | Header + Banner + Footer |
|  2  | Home (light)         | Trần Văn Long     | Home page light mode     |
|  3  | Home (dark)          | Lê Mạnh Cường     | Home page dark mode      |
|  4  | Popup (dark + light) | Nguyễn Phương Nam | Popup                    |
|  5  | News (dark + light)  | Phạm Đình Minh    | News page                |
|  6  | Partners (light)     | Lại Tiến Thành    | Partners page light mode |
|  7  | Contact (light)      | Lại Tiến Thành    | Contact page light mode  |
|  8  | Partners (dark)      | Nguyễn Tiến Thuận | Partners page dark mode  |
|  9  | Contact (dark)       | Nguyễn Tiến Thuận | Contact page dark mode   |

\* Lưu ý:

1. Khi code cần chừa ra khe cắm để các feature khác có thể cắm vào.
2. Tất cả các page đều có main layout nên merge request đầu tiên được merge sẽ là main layout. Sau khi có main layout các feature khác cần làm thêm 1 công đoạn là sẽ pull về và copy code main layout và feature của mình.
3. Cấu hình theme mode tại location.search: ?mode=light hoặc ?mode=dark.
4. Light mode sẽ link đến file html của feature light mode (nếu có) và ngược lại.
