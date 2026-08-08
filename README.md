# جهت حمایت از ما ادرس ولت تتر 💰
TRX  Address :
TB32VoKj7ZBnhN8i83sJ4gzXWQX5yBvToX

BNB Address :
0xEf33cb5ddDB3429bfa68c98Db9C0d644eff9ac87
 
# اموزش نصب :

دستور زیر را در ترمینال خود وارد کرده و یوزر و پسورد ادمین را وارد کنید .

````
bash <(curl -Ls https://raw.githubusercontent.com/HamedAp/Ssh-User-management/master/install.sh --ipv4)
````

جهت آپدیت پنل نیز همان دستور بالا را وارد کرده ( یوزر و پسورد ادمین نیاز نیست - یوزر ها پاک نمیشوند ) 





# SSL Installer ( Only SSL - NOT Panel - Need Domain )

در صورتی که دامنه دارید بعد از دستور نصب ( دقت کنید بعد از دستور نصب )  این دستور را بزنید .


````
bash <(curl -Ls https://raw.githubusercontent.com/HamedAp/Ssh-User-management/master/ssl.sh --ipv4)
````


# Reset Admin Password

اگر نیاز به ریست یوزر و پسورد ادمین دارید این دستور را زده و دوباره دستور نصب را بزنید :

````
mysql -e "use ShaHaN;drop table setting;"
````

# Will Be Added On Next Update 

-Traffic Limit


# Preview
![](screenshot/index.PNG)
![](screenshot/online2.PNG)
![](screenshot/newuser.PNG)
![](screenshot/setting.PNG)
![](screenshot/filtering.PNG)
![](screenshot/menu.PNG)

