# Cloudreso Lyrics

Kho lưu file `.lrc` (lyrics đồng bộ theo timestamp) cho ứng dụng Cloudreso.

Repo này cần để **public** để [jsDelivr](https://www.jsdelivr.com/) có thể serve file qua CDN.

## Cách dùng

Mỗi file lrc được truy cập qua jsDelivr theo dạng:

```
https://cdn.jsdelivr.net/gh/<username>/cloudreso-lyrics@main/<playlist>/<track>.lrc
```

Ví dụ:

```
https://cdn.jsdelivr.net/gh/<username>/cloudreso-lyrics@main/madihu/co-em.lrc
```

## Cấu trúc thư mục

Mỗi thư mục con tương ứng với 1 playlist/nghệ sĩ, chứa các file `.lrc` đặt tên trùng với track.
