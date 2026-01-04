```
 hh      bb      kk                             iii
 hh      bb      kk  kk           aa aa nn nnn      mm mm mmmm    eee
 hhhhhh  bbbbbb  kkkkk           aa aaa nnn  nn iii mmm  mm  mm ee   e
 hh   hh bb   bb kk kk          aa  aaa nn   nn iii mmm  mm  mm eeeee
 hh   hh bbbbbb  kk  kk _______  aaa aa nn   nn iii mmm  mm  mm  eeeee
```
# USO
La función se emplea así:
``` zsh
    $ hbk_anime input.vid ½ (output.m4v)
```

dónde:
> ***input.vid:*** *`path/file`*
>> *archivo de video para transformar.*

> ***½:*** *`INT`*
>> *un número que represente cuál es el subtítulo a trabajar.* Se puede obtener la información con *`mediainfo input.vid`*

> ***output.m4v:*** (opt)*`path/file`*
>> *definir la ubicación y/o nombre del archivo de salida (es necesario añadir la extension ***.m4v*** al final).*
>>> *De no establecerse, por defecto la salida tendrá el mismo nombre y ubicación que el archivo de entrada, pero con extención m4v.*

ejemplo:
``` zsh
    $ hbk_anime Descargas/\[ASW\]\ One\ Piece\ -\ 1126\ \[1080p\ HEVC\]\[20652293\].mkv 3 S21E38.m4v
```

# DEPENDENCIAS
`zsh`
> el script fue realizado con zsh en mente

`mpv`
> para reproducir hbk.opus

`HandBrakeCLI`
> dar las dimenciones y quemar el subtítulo

`vaapi`
> imprescindible

`ffmpeg`
> compresión y formato final

---
225DL Ａｌｅｓｓａｎｄｒｉｎｈｏ  ｄａ  Ｓｅｒｒａ

