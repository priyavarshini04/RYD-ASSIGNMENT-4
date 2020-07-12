# RYD-ASSIGNMENT-4
 Do it has image based questions or not
 
 
Simple file type checking
import filetype

def main():
    kind = filetype.guess('tests/fixtures/sample.jpg')
    if kind is None:
        print('Cannot guess file type!')
        return

    print('File extension: %s' % kind.extension)
    print('File MIME type: %s' % kind.mime)

if __name__ == '__main__':
    main()
   
Supported types
Image
jpg - image/jpeg
jpx - image/jpx
png - image/png
gif - image/gif
webp - image/webp
cr2 - image/x-canon-cr2
tif - image/tiff
bmp - image/bmp
jxr - image/vnd.ms-photo
psd - image/vnd.adobe.photoshop
ico - image/x-icon
heic - image/heic

Archive
epub - application/epub+zip
zip - application/zip
tar - application/x-tar
rar - application/x-rar-compressed
gz - application/gzip
bz2 - application/x-bzip2
7z - application/x-7z-compressed
xz - application/x-xz
pdf - application/pdf
exe - application/x-msdownload
swf - application/x-shockwave-flash
rtf - application/rtf
eot - application/octet-stream
ps - application/postscript
sqlite - application/x-sqlite3
nes - application/x-nintendo-nes-rom
crx - application/x-google-chrome-extension
cab - application/vnd.ms-cab-compressed
deb - application/x-deb
ar - application/x-unix-archive
Z - application/x-compress
lz - application/x-lzip
Font
woff - application/font-woff
woff2 - application/font-woff
ttf - application/font-sfnt
otf - application/font-sfnt
    
