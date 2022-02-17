# Secure-Folder
Creating Secure Folder Which Opens &amp; Closes With Password!

## How To Use : 
<ol>
  <li>Change The File Extension From .txt to .bat Or Direct Download The .bat File(This .Bat File Already Contain Password -123456)</li>
  <li>Run The .bat File , It Will Give You A Locker Folder, Place Your Files In Folder</li>
  <li>Then Run The .bat File Again! It Will Hide Your Folder And locks It With Your Given Password(To Change Password See Below Section)</li>
  <li>Get .txt File In Src Folder Of This Repository!</li>
  </ol>

## How Make Folder And To Change Password?

1. Go And Edit .Txt File And Find This!

```
set/p "pass=>"    

if NOT %pass%==123456 goto FAIL <-----Change Your Password!
```

2. Then Change The File Extension(Rename) From .txt to .bat, Then Save It! 
3. And Your Secure Folder Is Ready With Your Own Password !

## Advantage Vs Disadvantage

### Advantage

Secure Folder Creates A Secure Folder Vault Where User Can Store Any Important File & Information.

### Disadvantage

This Program Hide And lock The Folder That Cannot Be Found By Using The Normal "Show Hidden File Option"
Disadvantage : If The .bat File is Visible Or Kept Open, Third Person Will Be Able To See The Password If He Want To, So Better To Change The Password Or Hide It or Keep It In Another Folder After Using It.
