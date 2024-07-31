
# Các bước thực hiện

## Bước 1: Thực hiện trích xuất dữ liệu
Chạy file "mdpi_crawler.ipynb"
```bash
  run D:/trang/doan/DoAn1/mdpi_crawler/mdpi_crawler.ipynb
```
Sau khi chạy xong, ta sẽ thu được data trong folder output gồm:
- papers: folder chứa các file bài báo theo chủ đề
- subject: chứa các chủ để
- journalID: chứa các journal
## Bước 2: Thực hiện ETL job
- Extract:
```bash
  run D:/trang/doan/DoAn1/mdpi_crawler/etl/mdpi_extract.ipynb
```
- Transform:
```bash
  run D:/trang/doan/DoAn1/mdpi_crawler/etl/mdpi_transform.ipynb
```
- Load:
```bash
  run D:/trang/doan/DoAn1/mdpi_crawler/etl/mdpi_storage.ipynb
```
