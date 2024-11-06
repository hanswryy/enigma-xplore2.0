## Who am I?

This one is fun I actually like forensic.
<img width="509" alt="image" src="https://github.com/user-attachments/assets/247263df-39b3-4e28-b6f2-d5f38cd3c24d">

Looking at the challenge file (a .txt), at a glance it looks like gibberish, but if you see the first string it say png, so it might be some image .png file.
<img width="655" alt="image" src="https://github.com/user-attachments/assets/9e1537ed-6629-4317-8b6c-c8822935b7b0">

So I just change the extension to .png and it actually an image. also fake flag .png.
![forensic](https://github.com/user-attachments/assets/ed735ef1-10de-4f43-a652-75a851841ad8)

First thing you can do is to use exiftool, you can either install it or just use online exiftool on google.
<img width="1033" alt="image" src="https://github.com/user-attachments/assets/ac7a622e-450d-45a3-acce-0dfeb44baef5">

Scroll down a little bit and you can see the License is on base64 which is very sus.
<img width="993" alt="image" src="https://github.com/user-attachments/assets/642e384e-ab8b-40c6-b147-3489fbcafedd">

Decoding using cyberchef with base64 works fine, and we got the flag.
<img width="765" alt="image" src="https://github.com/user-attachments/assets/3dd976ed-2832-4406-8aef-94601de627b6">

```
EnXp{t4Ntr4_f1e5t4}
```
