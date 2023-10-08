# Ansible 101: Ubuntu/Debian Sunucuları için Nginx ve PostgreSQL Kurulumu

Bu repo, [linuxpedi.com](https://linuxpedi.com)’da yayınlanan Ansible yazısında kullanılan örnek projenin bir parçasıdır. Proje, Ansible'ın temel bileşenlerini - inventory, playbooks, roles, tasks, handlers, templates, ve variables - tanıtır ve bir Ubuntu/Debian sunucusunda Nginx kurulumunu otomatikleştirmek için bu bileşenleri nasıl kullanacağınızı gösterir.

## Özellikler

- Nginx otomatik kurulumu ve konfigurasyon.
- Ansible best practices'e uygun proje yapılandırması.

## Kurulum

1. `inventory.ini` dosyasını kendi ortamınıza göre güncelleyin.
2. Sunucunuzu yapılandırmak için aşağıdaki komutu çalıştırın:
    **ansible-playbook playbook.yml**

## Katılım

Hata bildirimleriniz, önerileriniz ve iyileştirme talepleriniz için GitHub Issues ve Pull Requests kullanabilirsiniz. Daha fazla Ansible role ve örneği eklemek için katkıda bulunabilirsiniz.

## Lisans

Bu proje, MIT Lisansı altında lisanslanmıştır. Detaylar için [`LICENCE`](LICENCE) dosyasına bakınız.
