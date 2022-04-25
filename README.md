# QrCode_py
create a qrcode in py
import pyqrcode
import png
from pyqrcode import QRCode
link ="your link please!"
url =pyqrcode.create(link)
url.png("your project name.png",scale=8)
print("DONE!")
