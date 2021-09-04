# জাভাস্ক্রিপ্ট ব্যাসিক থেকে প্রো


```javascript
Zero to Hero ~ The Ultimate Javascript Guideline
```


### জাভাস্ক্রিপ্ট কোথায়, কিভাবে যুক্ত করতে হয় ? 


কোডে দুইভাবে জাভাস্ক্রিপ্ট যুক্ত করা যায় যথা - 

**1. HTML পেজের মধ্যেই Script ট্যাগ দিয়ে যুক্ত করা যায়।**
```javascript
<script type="text/javascript">

//JS code goes here
//এখানে সকল জাভাস্ক্রিপ্ট কোড বসবে

</script>

 ```

-এভাবে যুক্ত করার অসুবিধা হচ্ছে - কোড দেখতে এবং মেইনটেইন করতে অনেক প্যারা খেতে হয়। তবে ছোট-খাটো স্ক্রিপ্ট হলে, HTML ফাইলের মধ্যেই লিখে ফেলা ভাল। 


**2. External জাভাস্ক্রিপ্ট ফাইলের মাধ্যমে**

```javascript
<script src="myscript.js"></script>
```

এখানে myscript.js এর লোকেশন ইচ্ছামত দিয়ে দেওয়া যাবে। এক্সটার্নালি Javascript ফাইল তিনভাবে যুক্ত করা যায়

1. With a full URL (a full web address)
```javascript
<script src="https://www.w3schools.com/js/myScript.js"></script>
```
2. With a file path (like  /js/ )
```javascript
<script src="/js/myScript.js"></script>
```
3. Without any path

```javascript
<script src="myscript.js"></script>
```

এভাবে জাভাস্ক্রিপ্ট যুক্ত করার সুবিধা হচ্ছে 

-কোড মেইনটেইন করা সহজ হয়
- HTML এবং Javascript আলাদা থাকায়, এরর খুঁজে বের করতে সহজ হয়
- Javascript ক্যাশড হয়ে থাকলে, পেজের লোডিং স্পীড বেড়ে যায় 


## জাভাস্ক্রিপ্টে দুইভাবে কমেন্ট দেওয়া যায়

>- // Single Line Comment
>- /* Multiple Line Comment */

## জাভাস্ক্রিপ্টে তিনভাবে ভ্যারিয়েবল ডিক্লেয়ার করা যায় 

1. const
2. var
3. let

#### const এর ব্যবহার 
- **Cannot be reassigned and not accessible before they appear within the code.** 
- **Variables defined with let must be Declared before use**


Variables defined with const cannot be Redeclared.

Variables defined with const cannot be Reassigned.
```javascript
const PI = 3.141592653589793;
PI = 3.14;      // This will give an error
PI = PI + 10;   // This will also give an error
```
Variables defined with const have Block Scope.
