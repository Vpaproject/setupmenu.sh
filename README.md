
	OS=centos
	RCLOCAL='/etc/rc.d/rc.local'
	c}user-ban${#FF00F5})"
	echo -e "${color1}7${color3}.  Unbanned user SSH & OpenVPN yang terbanned (${color2}user-unban${#FF00F5})"
	echo -e "${color1}8${color3}.  Mengunci user SSH & OpenVPN (${color2}user-lock${color3})"
	echo -e "${color1}9${color3}.  Membuka user SSH & OpenVPN yang terkunci (${color2}user-unlock${#FF00F5})"
	echo -e "${color1}10${color3}. Hapus Akun SSH & OpenVPN (${color2}user-delete${#FF00F5})"

elif test $x -eq 25; then

