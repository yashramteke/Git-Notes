\*\*\*\*\*\*Create a repository to github\*\*\*\*\*\*\*\*\*



Step 1: Create a folder on local system.



Step 2: Open Git Bash.



Step 3: Open GitHub Website and create repository in website.

&nbsp;	When creating repository in website name should be same as per local system. 

&nbsp;	(local system par jo folder name hai same name website ke repo par hona chahiye)



Step 4: Copy https link from GitHub. Link is in newly created repository or GitHub will provided.

&nbsp;	(http link may different as per repository. in my case this link is generated.)



Step 5: In Git Bash run this command and paste https link 

&nbsp;	Example:

&nbsp;	git remote add origin https://github.com/yashramteke/Git-Notes.git

&nbsp;	< -this is command- > < -----------this is https link----------- >



Step 6: After that run this command

&nbsp;	git branch -M main

&nbsp;	(when you execute step 5, your default branch name is **master**. When you execute step 6 your branch name will change to **main.** this is compulsory )







आगे जब भी तुम इस फोल्डर में कोई नया बदलाव करोगे, तो तुम्हें बस इन तीन आसान स्टेप्स को दोहराना होगा:



&nbsp;   git add . (नयी files को Git में add करने के लिए)



&nbsp;   git commit -m "Your message" (changes को save करने के लिए)



&nbsp;   git push (changes को GitHub पर भेजने के लिए)









git status - agar local me kuchh badlav kiye hai to origin par save nahi hote . to local par kitane badlav huye hai ye dekhane ke liye command hai 



git add - ye command se hamare changes staging mode me aate hai ( git status ke baad git add execute karna hai. agar git status execute ke baad bohot sare changes dikh rahe hai to git add . ye command bhi run kar sakte ho isase eksathh sare changes staging mode me aate hai aur agar ek ek karke karna hai to git add aur is command ke samane file name likhna hoga with extention )



git commit -m " yaha par jo changes kiye hai wo likhana hai taki hame pata chale ki kab kya change hua "

(git add ke baad git commit karana compulsory hai)



git push - last me hame ye command run karani hai . github par changes ho gaye hai.

