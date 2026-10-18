<p align="center"><img src="assets/icons/concat_logo_128.png" width="96" alt="Mika Studio"></p>

<h1 align="center">Mika Studio</h1>

<p align="center">Trình chỉnh sửa video miễn phí cho Windows, macOS và Linux.<br>
A free video editor for Windows, macOS and Linux.</p>

## Giới thiệu

Mika Studio là một bản sửa đổi của [Concat](https://github.com/jub0t/concat), trình chỉnh sửa video mã nguồn mở. Mọi thứ chạy trên máy bạn: không cần tài khoản, không watermark, không tải video lên mạng.

- Cắt, ghép, chia clip, đổi tốc độ, nhiều track
- Phụ đề tự động, chạy offline
- **Dịch phụ đề sang tiếng Anh** từ bất kỳ ngôn ngữ nào (mới trong Mika Studio)
- Chuyển chữ thành giọng nói, xóa phông nền, keyframe
- Hơn 170 hiệu ứng, bộ lọc, chuyển cảnh
- Xuất video H.264, HEVC, AV1, tới 4K 60fps

## Tải về

Vào mục **Releases** của repo này và chọn file cho máy bạn:

| Máy | File |
|---|---|
| Windows | `MikaStudio-…-windows-x86_64-setup.exe` hoặc `.msi` |
| macOS (chip Apple) | `MikaStudio-…-macos-arm64.dmg` |
| macOS (chip Intel) | `MikaStudio-…-macos-x86_64.dmg` |
| Linux | `.deb`, `.rpm` hoặc `.AppImage` |

Bản build chưa có chữ ký số. Trên Windows, nếu SmartScreen chặn, bấm **More info › Run anyway**. Trên macOS, nếu máy không cho mở, chạy:

```
xattr -dr com.apple.quarantine "/Applications/Mika Studio.app"
```

## Tạo bản phát hành mới

1. Vào **Releases › Draft a new release**.
2. Tạo tag theo dạng `v<phiên bản>-mika.<số>`, ví dụ `v0.2.7-mika.1`. Phiên bản phải khớp dòng `version` trong `src/Cargo.toml`.
3. Bấm **Publish release**. GitHub Actions sẽ build bản Windows, macOS và Linux rồi đính kèm vào release, mất khoảng 30 đến 60 phút.

## Giấy phép

Mika Studio dựa trên Concat của Jareer và những người đóng góp cho Concat, phát hành theo giấy phép [AGPL-3.0-or-later](LICENSE). Mã nguồn của Mika Studio cũng theo giấy phép đó. "Concat" và logo Concat là nhãn hiệu của dự án Concat; Mika Studio không phải bản chính thức của Concat và không được dự án Concat bảo trợ. README gốc của Concat nằm ở [README.concat.md](README.concat.md).
