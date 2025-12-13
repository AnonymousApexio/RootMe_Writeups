# HTML - Disabled Buttons
---
**Category:** Web-Client  
**Points:** 5  
**Difficulty:** Very Easy  
**Link:** https://www.root-me.org/en/Challenges/Web-Client/HTML-disabled-buttons

## 📋 Description:
A form is disabled and can not be used. It’s up to you to find a way to use it.

## 🔍 Reconnaissance:
1. Opened the challenge page  
![Image of the page](screen.png)
2. Right-clicked and selected "View Page Source"
3. Scanned through the HTML code

## 🛠️ Tools Used:
- Web DevTools (Opera GX)

## 🚀 Solution:

### Step 1:
Right-clicked on the page and selected "View Page Source".

### Step 2:
Scanned through the HTML and found a hidden comment:

```html
<form action="" method="post" name="authform">
        <div>
            <input disabled="" type="text" name="auth-login" value="">
            <input disabled="" type="submit" value="Member access" name="authbutton">
        </div>
</form>
```

### Step 3:
Delete the disabled attribute.

### Step 4:
Typed a random input into the auth-login input and pressed on "authbutton".

### Step 5:
Get the flag and solve the challenge:  
"Member access granted! The validation password is X"