ss -antp|grep 2003|grep ESTAB  | awk '{print }' | awk -F: '{print }'| sort |uniq -c  |sort -n


## links

http://geolite.maxmind.com/download/geoip/database/GeoLite2-City.mmdb.gz
http://geolite.maxmind.com/download/geoip/database/GeoLite2-Country.mmdb.gz
