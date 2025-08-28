| Hex Signature                                   | Offset | Extension        | Description                                                   |
|-------------------------------------------------|--------|-----------------|---------------------------------------------------------------|
| 47 49 46 38 37 61 / 47 49 46 38 39 61           | 0      | gif             | Graphics Interchange Format (GIF)                             |
| 49 49 2A 00 (little-endian)                     | 0      | tif, tiff       | Tagged Image File Format (TIFF)                               |
| 4D 4D 00 2A (big-endian)                        | 0      | tif, tiff       | Tagged Image File Format (TIFF)                               |
| 49 49 2B 00 / 4D 4D 00 2B                       | 0      | tif, tiff       | BigTIFF                                                       |
| 49 49 2A 00 10 00 00 00 43 52                   | 0      | cr2             | Canon RAW Format v2 (based on TIFF)                           |
| 66 74 79 70 63 72 78 43 52 (ftypcrx)            | 0      | cr3             | Canon RAW Format v3                                           |
| 80 2A 5F D7                                     | 0      | cin             | Kodak Cineon image                                            |
| 53 44 50 58 (big-endian) / 58 50 44 53 (little) | 0      | dpx             | SMPTE DPX image                                               |
| 76 2F 31 01                                     | 0      | exr             | OpenEXR image                                                 |
| 42 50 47 FB                                     | 0      | bpg             | Better Portable Graphics                                      |
| FF D8 FF DB                                     | 0      | jpg, jpeg       | JPEG (raw, JFIF or Exif)                                      |
| FF D8 FF E0 00 10 4A 46 49 46 00 01             | 0      | jpg, jpeg       | JPEG with JFIF header                                         |
| FF D8 FF EE                                     | 0      | jpg, jpeg       | JPEG (another variant)                                        |
| FF D8 FF E1 ?? ?? 45 78 69 66 00 00             | 0      | jpg, jpeg       | JPEG with Exif header                                         |
| 00 00 00 0C 6A 50 20 20 0D 0A 87 0A             | 0      | jp2, j2k, jpf…  | JPEG 2000                                                     |
| FF 4F FF 51                                     | 0      | jp2, j2k…       | JPEG 2000 codestream                                          |
| 71 6F 69 66 (qoif)                              | 0      | qoi             | Quite OK Image Format (QOI)                                   |
| 89 50 4E 47 0D 0A 1A 0A                         | 0      | png             | Portable Network Graphics (PNG)                               |
| 42 4D                                           | 0      | bmp, dib        | Windows Bitmap (BMP)                                          |
| 38 42 50 53 (8BPS)                              | 0      | psd             | Photoshop Document (Adobe Photoshop)                          |
| 52 49 46 46 ?? ?? ?? ?? 57 45 42 50             | 0      | webp            | WebP image (Google)                                           |
| 46 4C 49 46                                     | 0      | flif            | Free Lossless Image Format (FLIF)                             |
| 44 49 43 4D (DICM)                              | 128    | dcm             | Medical image DICOM                                           |
| 53 49 4D 50 4C 45                               | 0      | fits            | Flexible Image Transport System (FITS)                        |
