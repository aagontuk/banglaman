## যা আছে ##

1. [পরিচিতি](https://github.com/aagontuk/banglaman#পরিচিতি)
2. [ইনস্টল করার উপায়](https://github.com/aagontuk/banglaman#ইনস্টল-করার-উপায়)
3. [ব্যবহার](https://github.com/aagontuk/banglaman#ব্যবহার)
4. [টার্মিনালে বাংলা](https://github.com/aagontuk/banglaman#টার্মিনালে-বাংলা)
  * [টার্মিনালে বাংলা দেখা](https://github.com/aagontuk/banglaman#টার্মিনালে-বাংলা-দেখা)
  * [টার্মিনালে বাংলা লেখা](https://github.com/aagontuk/banglaman#টার্মিনালে-বাংলা-লেখা)
5. [যোগ দিতে চাই](https://github.com/aagontuk/banglaman#যোগ-দিতে-চাই)
6. [ভবিষ্যৎ পরিকল্পনা](https://github.com/aagontuk/banglaman#ভবিষ্যৎ-পরিকল্পনা)

</br>

## পরিচিতি ##

লিনাক্স / ইউনিক্স এর একটি অসাধারন ব্যপার হচ্ছে ম্যানুয়ালগুলো ( man page )। প্রায় সব কমান্ড এবং সফ্টওয়্যারের সাথেই একটা ম্যানুয়াল বা নির্দেশিকা দেয়া থাকে। এই নির্দেশিকাতেই বলে দেয়া থাকে কমান্ডটি বা সফ্টওয়্যারটি কি কাজ করে, এর কি কি অপশন আছে, এর কি কি কনফিগারেশন ভ্যারিয়েবল আছে, কোন কোন ফাইল এডিট করে সেগুলোর মান পরিবর্তব করা যাবে, কিভাবে করতে হবে; ঐ কমান্ড বা সফ্টওয়্যার সম্পর্কিত প্রায় সবকিছু। শুধু তাই না, কনফিগারেশন ফাইলগুলোরও ম্যানুয়াল আছে( যেমন: sudoers, login.def ইত্যাদি )। এমনকি ইউনিক্স / লিনাক্স এর ফাইল সিস্টেম, কিভাবে বুট হয় এরকম সিস্টেমের ভেতরকার ব্যপার স্যপার নিয়েও ম্যানুয়াল আছে। আর এ সবকিছুই সিস্টেমে দিয়ে দেয়া থাকে! এর জন্য কোন বই কিনতে হবে না বা ইন্টারনেটে খোঁজাখুঁজি করতে হবে না। শুধু man কমান্ডটি ব্যবহার করলেই হবে!

কেমন হয় যদি এই সব ম্যানুয়ালগুলো পড়া যায় আমাদের প্রিয় মাতৃভাষা বাংলাতেই? এই ধারণাটিকে বাস্তবে রূপ দিতেই বাংলাম্যান ( banglaman ) এর আগমন!

</br>

## ইনস্টল করার উপায় ##

প্রথমে রিপোজিটোরিটি ক্লোন করে নিন:

`tux@banglapc:~$ git clone https://github.com/aagontuk/banglaman.git`

অথবা যদি [SSH সেটআপ](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) করা থাকে তবে:

`tux@banglapc:~$ git clone git@github.com:aagontuk/banglaman.git`

এবার প্রজেক্ট ফোল্ডারে যান:

`tux@banglapc:~$ cd banglaman`

এখানে দেখুন install নামে একটি শেল স্ক্রিপ্ট দেয়া আছে। এটি চালান। ইনস্টল করতে সুপার ইউজার ক্ষমতা থাকতে হবে। su দিয়ে রুট ইউজার হয়ে নিন অথবা sudo ব্যাবহার করুন:

`tux@banglapc:~$ sudo ./install`

আশাকরি আপনার সিস্টেমে বাংলাম্যান ইনস্টল হয়ে গেছে!

</br>

## ব্যবহার ##

টার্মিনালে `banglaman banglaman` দিয়ে দেখুন!

</br>

## টার্মিনালে বাংলা ##


#### টার্মিনালে বাংলা দেখা ####

বাংলাম্যান ব্যবহার করতে হলে আপনাকে বাংলা দেখা যায় এরকম একটি টার্মিনাল ব্যবহার করতে হবে। দুঃখজনক ব্যপার হচ্ছে এখনও সব টার্মিনালে বাংলা দেখা যায় না। আপনার টার্মিনালে যদি বাংলা ঠিকভাবে দেখা না যায় তবে বাংলা সমর্থন করে এরকম একটি টার্মিনাল ইনস্টল করে নিন। নিচের তালিকা দেখুন:

যেসব টার্মিনাল ঠিকভাবে বাংলা দেখা যায় তাদের তালিকা:

* [konsole](https://konsole.kde.org/)

যেসব টার্মিনাল বাংলা এখনও ঠিকভাবে দেখা যায় না তাদের তালিকা:

* [Linux Console](https://en.wikipedia.org/wiki/Linux_console) | [কারণ](http://unix.stackexchange.com/questions/273061/linux-console-cant-display-any-language-other-than-english-while-the-terminal-u)
* [gnome-terminal](https://help.gnome.org/users/gnome-terminal/stable/) | [কারণ](http://askubuntu.com/questions/630598/terminal-and-python-console-isnt-showing-bangla)

</br>

#### টার্মিনালে বাংলা লেখা ####

সাধারনত যেসব টার্মিনালে ঠিকভাবে বাংলা দেখা যায়, সেগুলোতে বাংলা লেখাও যায়। জনপ্রিয় কিছু কমান্ডলাইন টেক্সট এডিটরে বাংলা লেখালেখির অবস্থা:

* **vim**: বাংলা ঠিকভাবে দেখা যায় এবং বাংলা লেখাও যায়। তবে লেখার সময় কিছু কিছু অক্ষর ঠিকভাবে দেখা যায় না। যেমন া - কার, ি - কার, যুক্তবর্ণ ঠিকভাবে দেখা যায় না।
* **emacs**: বাংলা ঠিকভাবে দেখা যায় এবং লেখা যায়।

</br>

## যোগ দিতে চাই ##

[![Join the chat at https://gitter.im/banglamans/Lobby](https://badges.gitter.im/banglamans/Lobby.svg)](https://gitter.im/banglamans/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

এই প্রকল্পে আপনার অংশগ্রহণ খুবই গুরুত্বপূর্ণ। অনেকভাবে আপনি এই প্রকল্পে অবদান রাখতে পারেন। প্রকল্প সম্পর্কিত যেকোন মতামত এবং পরামর্শ দিতে পারেন। যেকোন ধরণের ভুলত্রুটি সংশোধন করতে পারেন। banglaman সফটওয়্যারের ডেভেলপমেন্টে অবদান রাখতে পারেন। এবং সবচেয়ে গুরুত্বপূর্ণ যে কাজ সেগুলো হচ্ছে নতুন ম্যানুয়াল লিখতে পারেন; অনুবাদ করতে পারেন; যে ম্যানুয়ালগুলো লেখা আছে আছে সেগুলোর ভুলত্রুটি সংশোধন করতে পারেন; যেগুলো সম্পূর্ণ হয়নি সেগুলো সম্পূর্ণ করতে পারেন।

##### নতুন ম্যানুয়াল যোগ করব #####
প্রথমে [এখানে](https://github.com/aagontuk/banglaman/tree/master/banglamans) দেখে নিন আপনি যে ম্যানুয়াল লিখবেন/অনুবাদ করবেন বলে ঠিক করেছেন সেটা আগেই লিখে ফেলা হয়েছে কিনা। যদি আগেই লিখে ফেলা হয়ে থাকে, তাহলে সেটা সম্পাদনা বা সম্পূর্ণ করার কাজ করতে পারেন। আর যদি না থাকে, তাহলে আর দেরি কেন? banglaman এ যোগ করে ফেলুন আপনার লেখা নতুন একটি বাংলা ম্যানুয়াল! 

##### লেখার এবং অনুবাদের ধরণ কি রকম হবে #####
যেভাবে লিখলে এবং অনুবাদ করলে ম্যানুয়ালটা স্পষ্ট বোঝা যাবে। এক্ষেত্রে নিচের বিষয়গুলো খেয়াল রাখা যেতে পারে:

* এটি লিনাক্স ম্যানুয়ালগুলো বাংলায় লেখার প্রজেক্ট। এক্ষেত্রে কেউ চাইলে সম্পূর্ণ ম্যানুয়াল নিজেই লিখতে পারে। অথবা ইংরেজি ম্যানুয়াল থেকে অনুবাদ করতে পারে। বা দুটোই করতে পারে। তাই বাংলা ম্যানুয়াল একদম ইংরেজি ম্যানুয়াল এর অনুরূপ হওয়া জরুরী নয়।
* ম্যানুয়ালের গঠন ইংরেজি ম্যানুয়াল এর গঠনের মত রাখা যেতে পারে।
* অনুবাদ করার ক্ষেত্রে আক্ষরিক অনুবাদ নয়; ভাব অনুবাদ করতে হবে।
* অনুবাদ করার সময় ভাষার প্রঞ্জলতার দিকে খেয়াল রাখতে হবে। পাঠক যেন চোখ না কুচকিয়েই ম্যানুয়ালটি পড়ে ফেলতে পারেন। কোন একটি ইংরেজি শব্দের অনুবাদ করতে গিয়ে যদি মনে হয় বাংলা অনুবাদের চেয়ে ইংরেজি শব্দই বেশি প্রাঞ্জল এবং বোধগম্য হবে; সেক্ষেত্রে ইংরেজি শব্দটিই রাখা যেতে পারে(যেমন: ফাইল, ফোল্ডার)।
* বাংলা ম্যানুয়ালের অনুবাদ হুবুহু ইংরেজি ম্যানুয়ালের মত হতে হবে না। কোন বিষয় স্পষ্ট করে তোলার জন্য যদি অধিক ব্যাখ্যার প্রয়োজন হয় তবে অধিক ব্যাখ্যা দেয়া যেতে পারে। তবে স্পষ্ট করে তোলার জন্য যতটুকু প্রয়োজন ততটুকু। যাতে পাঠক পড়ে সহজেই বুঝতে পারে।
* তবে খেয়াল রাখতে হবে কোনভাবে যেন ম্যানুয়ালের সঠিকতা নষ্ট না হয়। বা মূল বিষয়ের ভুল ব্যাখ্যা তৈরি না হয়।

আরও বিস্তারিত নির্দেশনার জন্য [CONTRIBUTE](https://github.com/aagontuk/banglaman/blob/master/CONTRIBUTE) ফাইলটি দেখুন।

<br>

## ভবিষ্যৎ পরিকল্পনা ##
