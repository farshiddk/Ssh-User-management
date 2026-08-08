# جهت حمایت از ما ادرس ولت تتر 💰
TRX  Address :
TAD97HP3yk22eVSWMSkDaEgvdMbbBXuHSK

BNB Address :
0xdEc2d2315E31228f6900498683aaF8756F8451E4
 
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

