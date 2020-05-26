# QtFtpClient
Prosty klient FTP oparty o framework Qt

![Qt FTP Client - Linux](qtftp_linux.png) ![Qt FTP Client - Windows](qtftp_win.png)

# Zależności

* QFtp (https://github.com/qt/qtftp)

Instalacja biblioteki zgodnie z instrukcją w powyższym repozytorium.

### Uwaga

Jeżeli biblioteka nie jest widoczna przez Qt Creator, należy w katalogu, do którego została rozpakowana, przejść do folderu `src/qftp/src` i w pliku `qftp.pro` dodać poniższą linię:

`CONFIG -= create_pri`

i powtórzyć proces.
