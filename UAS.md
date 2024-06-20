# UAS-SISTER

<h3 >Membuat 6 instance LXC ubuntu 20.04 PHP 7.4</h3>
 ` 
sudo lxc-create -n lxc_php7_1 -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --server images.linuxcontainers.org

sudo lxc-create -n lxc_php7_2 -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --server images.linuxcontainers.org

sudo lxc-create -n lxc_php7_3 -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --server images.linuxcontainers.org

sudo lxc-create -n lxc_php7_4 -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --server images.linuxcontainers.org

sudo lxc-create -n lxc_php7_5 -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --server images.linuxcontainers.org
sudo lxc-create -n lxc_php7_6 -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --server images.linuxcontainers.org
 ` 
 <h3 >Membuat 2 instance LXC debian 10 PHP 5.6 dan 1 instance LXC debian 10 mariadb server</h3>
 sudo lxc-create -n lxc_php5_1 -t download -- --dist debian --release buster --arch amd64 --force-cache --server images.linuxcontainers.org

sudo lxc-create -n lxc_php5_2 -t download -- --dist debian --release buster --arch amd64 --force-cache --server images.linuxcontainers.org

sudo lxc-create -n lxc_mariadb -t download -- --dist debian --release buster --arch amd64 --force-cache --server images.linuxcontainers.org


 <h3 >melakukan konfigurasi menginstal server ssh di setiap lxc. Dalam hal ini kita melakukan beberapa konfigurasi ip seperti gambar di bawah ini. </h3>
 
 ![image](https://github.com/RayhanFurqoni/UAS-SISTER/assets/124054176/10c2f86d-974e-4de4-91e0-7176cbb67b2a)
