## INSTALL SCRIPT 
Masukkan perintah dibawah untuk menginstall Autoscript Premium
- Langkah Pertama
```
echo -e "net.ipv6.conf.all.disable_ipv6 = 1\nnet.ipv6.conf.default.disable_ipv6 = 1\nnet.ipv6.conf.lo.disable_ipv6 = 1" >> /etc/sysctl.conf && sysctl -p
```
- Langkah Kedua
```
apt update -y && apt upgrade -y --fix-missing && apt install -y xxd bzip2 wget curl sudo build-essential bsdmainutils screen dos2unix && update-grub && apt dist-upgrade -y && sleep 2 && reboot
```
- Langkah Ketiga
```
screen -S setup-session bash -c "wget -q https://raw.githubusercontent.com/nsstore14/instalasi/main/setup.sh && chmod +x setup.sh && ./setup.sh; read -p 'Tekan enter untuk keluar...'"
```
- Jika Terjadi Disconnect Saat Proses Penginstallan Gunakan Perintah ini
- Bisa juga Di Tinggal Ngopi Dll Lalu Tinggal Menghubungkan Ulang
```
screen -r -d setup
```

## UPDATE
```
wget https://raw.githubusercontent.com/nsstore14/instalasi/main/update.sh && chmod +x update.sh && ./update.sh
```
### rebuild deb 10 selain do

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 10 && reboot</code></pre>
### rebuil deb 11

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 11 && reboot</code></pre>
### rebuild deb 12

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 12 && reboot</code></pre>
### rebuild ubuntu 20.04

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 20.04 && reboot</code></pre>
### rebuild ubuntu 22

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 22.04 && reboot</code></pre>
### rebuild ubuntu 24

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 24.04 && reboot</code></pre>

### Rebuild ubuntu 25
```
curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 25.04 && reboot
```


# pilih salah satu repo utk mempercepat proses instalasi 
#id 1
```
[[ -e $(which curl) ]] && if [[ -z $(cat /etc/resolv.conf | grep "8.8.8.8") ]]; then cat <(echo "nameserver 8.8.8.8") /etc/resolv.conf > /etc/resolv.conf.tmp && mv /etc/resolv.conf.tmp /etc/resolv.conf; fi && curl -LksS -4 "https://raw.githubusercontent.com/izulx1/repo/master/repoindo.sh" -o repoindo && chmod +x repoindo && ./repoindo id1
```
#id 2
```
[[ -e $(which curl) ]] && if [[ -z $(cat /etc/resolv.conf | grep "8.8.8.8") ]]; then cat <(echo "nameserver 8.8.8.8") /etc/resolv.conf > /etc/resolv.conf.tmp && mv /etc/resolv.conf.tmp /etc/resolv.conf; fi && curl -LksS -4 "https://raw.githubusercontent.com/izulx1/repo/master/repoindo.sh" -o repoindo && chmod +x repoindo && ./repoindo id2
```
#id 3
```
[[ -e $(which curl) ]] && if [[ -z $(cat /etc/resolv.conf | grep "8.8.8.8") ]]; then cat <(echo "nameserver 8.8.8.8") /etc/resolv.conf > /etc/resolv.conf.tmp && mv /etc/resolv.conf.tmp /etc/resolv.conf; fi && curl -LksS -4 "https://raw.githubusercontent.com/izulx1/repo/master/repoindo.sh" -o repoindo && chmod +x repoindo && ./repoindo id3
```
# sg
```
[[ -e $(which curl) ]] && if [[ -z $(cat /etc/resolv.conf | grep "8.8.8.8") ]]; then cat <(echo "nameserver 8.8.8.8") /etc/resolv.conf > /etc/resolv.conf.tmp && mv /etc/resolv.conf.tmp /etc/resolv.conf; fi && curl -LksS -4 "https://raw.githubusercontent.com/izulx1/repo/master/repoindo.sh" -o repoindo && chmod +x repoindo && ./repoindo sg
```
#ori
```
[[ -e $(which curl) ]] && if [[ -z $(cat /etc/resolv.conf | grep "8.8.8.8") ]]; then cat <(echo "nameserver 8.8.8.8") /etc/resolv.conf > /etc/resolv.conf.tmp && mv /etc/resolv.conf.tmp /etc/resolv.conf; fi && curl -LksS -4 "https://raw.githubusercontent.com/izulx1/repo/master/repoindo.sh" -o repoindo && chmod +x repoindo && ./repoindo ori
```