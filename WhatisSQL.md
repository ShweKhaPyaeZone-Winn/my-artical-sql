# MySQL Myanmar

**What is MySQL?**
MySQL ဆိုတာ ဘာလဲ?

MySQL ဆိုတာ စနစ်တကျ စုစည်းထားတဲ့ data အစုအ‌ေဝးဖြစ်ပါတ,်
ဖုန်းနံပါတ်တွေ မှတ်ထားတဲ့ ဖုန်းစာအုပ်ကလဲ database ပါဘဲ
အကြိုက်ဆုံးသီချင်းတွေ စုစည်းထားတဲ့ playlist ကလဲ database ပါဘဲ
photo တွေကို သူ့အကန့်နဲ့သူ စုစည်းထားတဲ့ gallary ကလဲ database ပါဘဲ 

ဒါကြောင့် database က နေရာတိုင်းမှာ ရှိနေပါတ,်

data တစ်ခုက အခြား  data  နဲ့ ဆက်နွ,်နေတဲ့ database ကို
**relational database** လို့ ခေါပါတ,်

relational database ကို table တွေနဲ့ ပြပါတ,်
table တွေမှာ rows နဲ့ columns ပါ၀င်တ,်

table တစ်ခုက အခြား  table  တစ်ခုနဲ့ ချိတ်ဆက်တဲ့ အခါမှာ
*one to one*
*one to many*
*many to many* relationship တွေကို အသုံးပြုတ,်

data တွေ အများကြီးကို တစ်ကွဲတစ်ြပားဆီ ထားမဲ့အစား databaseတွေ
tableတွေနဲ့ စနစ်တကျ သိမ်းစည်းထားရင် အလုပ်လုပ်ရာမှာ ပို၍လွ,်ကူစေနိုင်ပါတ,်

ဒါကြောင့် ဒီနေရာမှာ SQl  ကို လိုအပ်လာပါတ,်

**SQL** - structured query language

SQL ဆိုတာ relational database ကို နားလည်ဖို့ အသုံးပြုရတဲ့ ဘာသာစကားတစ်ခုဖြစ်တ,်

SQL မှာ အပိုင်းသုံးပိုင်း ပါ၀င်တ,်
(1)*Data defination language* မှာ database နဲ့ object တွေ တည်ဆောက်ပေးတဲ့  statement  တွေပါတ,်
(2)*Data manipulating language* မှာ database ထဲက data တွေကို အသစ်ထပ်ထည့်တာ ဖျက်ပစ်တာ မျိုး ပြုပြင်ပြောင်းလဲလို့ ရပါတ,်
(3)*Data control language* ဆိုတာ data တွေကို သိမ်းလို့ ရမရ ခွင့်ပြုချက် တောင်းတဲ့ နေရာမှာ အသုံးပြုပါတ,်

MySQl ဆိုတာ My နဲ့ SQL ကို ပေါင်းထားတာပါဘဲ
meaning အရဆိုရင် ကျွန်တော့ရဲ့ SQL ပေါ့

MySQl ဟာ  relational database  ကို manage လုပ်ပေးတဲ့ *database management system* ဖြစ်ပါတ,်
Oracle က ထုတ်လုပ်ထားတဲ့  မည်သူမဆို အသုံးပြုလို့ရတဲ့ software ဖြစ်ပါတ,်
အဲ့ဒီ့အတွက် ပိုက်ဆံပေးဖို့မလိုအပ်ပါဘူး
source code တွေကိုလဲ သင်နဲ့ လိုချင်တဲ့ ပုံစံကို ပြောင်းလဲအသုံပြုနိုင်ပါတ,်

MySQl ဟာ  ပိုက်ဆံမပေးရတဲ့ software ဖြစ်ပေမဲ့လဲ ပိုမြင့်တဲ့ version နဲ့ ကန့်သတ်ထားတဲ့ service ကို ရရှိဖို့ စီးပွားရေးအရ license version တွေ ကို ဝယ်ယူအသုံးပြုနိုင်ပါတ,်

MySQL database ဟာ အခြား database software  တွေထက် တော်တော်လေး လွ,်ကူသောကြောင့် လူသုံးများပါတယ်
UNIX, Linux, Windows စတဲ့ အမျိုးမျိုးသော OS တွေမှာ run နိုင်ပါတယ်
server သို့မဟုတ် desktop ပေါမှာ install လုပ်နိုင်တဲ့ ယုံကြည်စိတ်ချရပီး ကျွမ်းကျင်မြန်ဆန်တဲ့ application ဖြစ်ပါတယ်


**How to play with MySQL**
MySQL ကို ဘယ်လိုလေ့လာကြမလဲ

MySQL ကို MAC installation နဲ့ Cloud9 installation ဆိုပြီး (၂)မျိုး down လို့ ရပါတယ်

အခု ပြောပြသွားမှာကတော့ Cloud9 installation ဖြစ်ပါတယ်

အရင်ဆုံး _goorm.io_ ဆိုပြီး google မှာ ရိုက်ရှာလိုက်ပါ
![goorm](Capture1.png)

ပြီးရင် *sign up* ဆိုတဲ့ symbol ကို ရိုက်နှိပ်ပြီး သူတောင်းဆိုထားတဲ့ 
email address,password,confirm password,full name ကို ရိုက်ထည့်ပီး sign up လုပ်ပါ
![sign_up](Capture2.png)

တကယ်လို့  goorm account ဖွင့်ပြီးပြီ နောက်တစ်ခေါက်ထပ်၀င်ချင်တယ်ဆိုရင် sign up မလုပ်ပဲ   *sign in* ကို နှိပ်ပါ
တောင်းဆိုထားတဲ့ email address နဲ့ password ကို ရိုက်ထည့်ပြီး account ထဲ ဝင်နိုင်ပါပြီ
![sign_in](Capture3.png)

goorm account ထဲ ရောက်ရင် ဘယ်ဘက်က *IDE* ကို နှိပ်ပါ
![ide](Capture4.png)

IDE ထဲ ၀င်ပြီးရင် ညာဘက်ထောင့်က အပြာရောင်နဲ*့ dashboard* ကို နှိပ်ပါ
![dashboard](Capture5.png)

ပြီးရင် *New Container* ကိုနှိပ်ပြီး container တစ်ခု တည်ဆောက်နိုင်ပါဘီ
![container](Capture6.png)

containter တည်ဆောက်ရာတွင်  name  နဲ့ description နေရာမှာ ကိုယ်ကြိုက်ရာ ရိုက်လို့ရပါတယ်
![name](Capture7.png)

ပြီးရင် အသုံးပြုမဲ့ icon ကို ရွေးချယ်ရပါမယ်
*Node.js* ဟာ လူသုံးများပြီး လုံခြုံစိတ်ချရသောကြောင့် node.js ကိုပဲ ရွေးချယ်ပါမယ်
![node.js](Capture8.png)

အောက်ဆုံးတွင် Additional module/package ဆိုတဲ့ နေရာမှာ
*Install MySQl* နဲ့ *Enable mysql-ctl command* ကို ရွေးချယ်ပြီး အမှန်ခြစ်ပါ ထို့နောက် ညာဘက်ထောင့်ဆုံးက create ကိုနှိပ်ပါ
![select](Capture9_LI.jpg)

MySQL installation စတင်ပါပြီ
![install](Capture10.png)

container တည်ဆောက်တာ ပြီးစီးသွားပြီ
![end](Capture11.png)

အခု **mysql-ctl cli** လို့ရိုက်နှိပ်ပြီး MySQL database ကို စရေးလို့ ရပါပြီ
![SQL](Capture12.png)

mysql 
