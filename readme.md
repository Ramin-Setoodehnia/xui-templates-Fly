<p align="center">
  <a href="https://github.com/dev-ir/xui-templates-Fly" target="_blank" rel="noopener noreferrer" >
    <img src="https://github.com/dev-ir/xui-templates-Fly/blob/master/screenshot.png" alt="SubPage screenshots" width="800" height="auto">
  </a>
</p>

# Usage

```bash
sudo git clone https://github.com/dev-ir/xui-templates-Fly.git /opt/DVHOST/views/templates/FlySubscription/
sudo sed -i 's/^TEMPLATE_NAME=.*/TEMPLATE_NAME=FlySubscription/' /opt/DVHOST/dvhost.config
```

<details>
  <summary>Click for configuration file manual</summary>

```
nano /opt/DVHOST/dvhost.config
```
# Template name 
```
# Replace Template name 
TEMPLATE_NAME=FlySubscription
```
</details>


Now you can restart your XUI Panel Subscription Template :
```
systemctl restart DVHOST_TEMPLATE
systemctl status DVHOST_TEMPLATE
```


# استفاده

ابتدا فایل رو به سرور بفرستید. با دستور زیر میتونید این کارو بکنید:

```bash
sudo git clone https://github.com/dev-ir/xui-templates-Fly.git /opt/DVHOST/views/templates/FlySubscription/
sudo sed -i 's/^TEMPLATE_NAME=.*/TEMPLATE_NAME=FlySubscription/' /opt/DVHOST/dvhost.config
```

<details>
  <summary>📝 روش جایگزین: اضافه کردن مستقیم به فایل</summary>


سپس دستور زیر وارد کنید تا وارد تنظیمات اصلی شوید

```
nano /opt/DVHOST/dvhost.config
```

حالا میبایست نام پوسته جایگزین پوسته پیشفرض کنید
```
# Replace Template name 
TEMPLATE_NAME=FlySubscription
```
</details>

حالا سرویس ری‌استارت کنید:
```
systemctl restart DVHOST_TEMPLATE
systemctl status DVHOST_TEMPLATE
```
## 🙏 Support with Crypto 
**We don't need financial support, only Star (⭐) is enough, thank you.**
- USDT (TRC20): `TVUqVMoCEe5DVUoxmPg8MwmgcHvZLqLjr4`

## 📧 Join Telegram Channel

TG : https://t.me/+EpErnDsDPhw3ZThk
