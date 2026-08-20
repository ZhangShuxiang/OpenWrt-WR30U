kai ji hou zi ji xiu gai mi ma
(echo Aa56781234; sleep 1; echo Aa56781234) | passwd > /dev/null
uci set wireless.@wifi-iface[1].key="56781234"
