# OSINT - Find the needle...

## Challenge description:
![2](https://user-images.githubusercontent.com/70543460/96257877-cef2f380-0fc3-11eb-9d20-4c4b7af1b412.png)

<br/><br/>

## Solution:

To solve this challenge, I used ripe.net

![image](https://user-images.githubusercontent.com/70543460/96259187-ed59ee80-0fc5-11eb-961b-39a9459fa1fd.png)

![image](https://user-images.githubusercontent.com/70543460/96259229-fe0a6480-0fc5-11eb-842b-d21fbe1fdb56.png)

<br/><br/>

Using **(RIPE Database Text Search)**, I searched for **194.210**

![image](https://user-images.githubusercontent.com/70543460/96259369-2b571280-0fc6-11eb-8ff0-a9a478a7b04b.png)

<br/><br/>

I got 80 inetnum search results:

![image](https://user-images.githubusercontent.com/70543460/96259791-c4862900-0fc6-11eb-96a7-1ab69e04177f.png)

<br/><br/>

## Note:
![image](https://user-images.githubusercontent.com/70543460/96259631-8d177c80-0fc6-11eb-8305-8789e6c68a56.png)

<br/><br/>

Then I checked every inetnum in the search results pages, and I found this interesting one in page 6:

![image](https://user-images.githubusercontent.com/70543460/96265199-d3240e80-0fcd-11eb-9923-b161634d0636.png)

<br/><br/>

```
66 6c 61 67 7b 75 73 45 5f 41 5f 62 69 67 5f 6d 40 67 6e 33 74 21 7d
```

<br/><br/>


![image](https://user-images.githubusercontent.com/70543460/96267775-e71d3f80-0fd0-11eb-87e1-46cb077b8ea5.png)

<br/><br/>

**flag{usE_A_big_m@gn3t!}**
