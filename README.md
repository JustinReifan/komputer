2.  SHARING DENGAN CARA CLI
tak jauh beda dengan yang GUI, hanya saja dengan cara CLI kita melibatkan command/perintah di terminal, pertama kita buka dulu Terminal Ctrl+Alt+T, setelah itu ketikan perintah sudo su masukan password ubuntu, lalu ketikan perintah gedit(spasi)/etc/samba/smb.conf.

setelah mengetikan perintah tersebut, akan langsung terbuka jendela baru samba config berbasis text, scroll kebawah lalu ketikan perintah seperti dibawah
[SharingUbuntu]  > nama yang disharingkan
path = /home/(nama komputer Ubuntu)/Dokumen/sharing > path folder yang disharingkan
browsable = yes
guest ok = yes
read only = no
create mask = 0777
jika sudah lalu klik save,

kembali lagi ke terminal, sekarang kita ketikan perintah untuk membuat folder tadi sharingkan dengan perintah mkdir(spasi)/home/(nama komputer)/Dokumen/sharing lalu enter, selanjutnya ketikan perintah untuk merestart samba caranya ketikan /etc/init.d/samba(spasi)restart lalu enter.

jika semuanya ok berarti samba berhasil di restart dengan configurasi tadi, terakhir ketikan perintah chmod 777(spasi)/home/(nama komputer)/Dokumen/sharing perintah ini di gunakan agar client bisa mengakses penuh pada folder yang sedang disharingkan.

sekarang cek folder tersebut, dengan cara buka cmd dan ketikan \\192.168.148.2(ip komputer ubuntu) jika sudah ada berarti sharing sudah berhasil,



 sekarang anda dapat menshare file apapun melalui folder tersebut.
Sharing selesai !!.
