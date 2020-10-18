# OSINT - Ringback to your attacker

## Challenge description:
![7](https://user-images.githubusercontent.com/70543460/96375850-36f03800-1184-11eb-9e6a-6c5262a7ff30.png)

<br/><br/>

## Solution:

First of all, thanks to my teammate KOOLI, because he solved most of this challenge 💪

...

<br/><br/>

We were given an ip address in the challenge description (**139.83.9.11**)

<br/><br/>

### To make a long story short, I will mention the solution directly:

<br/><br/>

My teammate found a geographic location when he checked the "**Historical Whois**":

(**38.129775 -6.976331**)

(https://stat.ripe.net/widget/historical-whois#w.resource=139.83.9.11%2F32&w.time=2020-10-18T18%3A02%3A19)


![image](https://user-images.githubusercontent.com/70543460/96375998-17a5da80-1185-11eb-8d07-d7bf8e424c72.png)


![image](https://user-images.githubusercontent.com/70543460/96376113-b599a500-1185-11eb-8fe4-0bfc0c16ac45.png)

<br/><br/>

I checked the **Google Maps Street View** there, and I found the number:

(https://www.google.com/maps/@38.1297321,-6.976297,3a,23.7y,323.94h,105.09t/data=!3m7!1e1!3m5!1s3shX9SWSVB1hYw1qdLNPTg!2e0!6s%2F%2Fgeo1.ggpht.com%2Fcbk%3Fpanoid%3D3shX9SWSVB1hYw1qdLNPTg%26output%3Dthumbnail%26cb_client%3Dmaps_sv.tactile.gps%26thumb%3D2%26w%3D203%26h%3D100%26yaw%3D352.73495%26pitch%3D0%26thumbfov%3D100!7i13312!8i6656)

<br/><br/>
![image](https://user-images.githubusercontent.com/70543460/96376258-77e94c00-1186-11eb-9ee3-94b1c7511e95.png)
<br/><br/>

**flag{964035528}**
