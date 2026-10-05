# Dữ liệu

| Mục | Thông tin |
|---|---|
| File | `ufo_sighting_data.csv` (13.710.798 byte) |
| Tên dataset | UFO Sightings around the world |
| Link | https://www.kaggle.com/datasets/camnugent/ufo-sightings-around-the-world |
| Tác giả đăng trên Kaggle | Cam Nugent |
| Nguồn gốc | Báo cáo gửi về NUFORC (National UFO Reporting Center), được repo [planetsig/ufo-reports](https://github.com/planetsig/ufo-reports) tổng hợp; Cam Nugent thêm tên cột và đăng lên Kaggle |
| Giấy phép | CC0: Public Domain |
| Kích thước | 80.332 dòng × 11 cột |

## Lưu ý khi đọc file
File dùng ký tự xuống dòng kiểu Mac cũ (`\r`), nên phải đọc bằng:

    pd.read_csv('data/ufo_sighting_data.csv', lineterminator='\r')
