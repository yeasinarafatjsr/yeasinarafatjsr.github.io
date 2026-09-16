<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Technology Quiz - Knowledge World</title>

<style>
*{box-sizing:border-box}

body{
    margin:0;
    font-family:Arial,"Noto Sans Bengali",sans-serif;
    background:#f1f5f9;
    color:#0f172a;
}

header{
    background:linear-gradient(135deg,#0f766e,#2563eb);
    color:white;
    padding:25px 15px;
    text-align:center;
}

header h1{margin:0 0 8px;font-size:30px}
header p{margin:0}

.container{
    max-width:700px;
    margin:25px auto;
    padding:15px;
}

.card{
    background:white;
    padding:25px;
    border-radius:18px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.hidden{display:none}

.option{
    display:block;
    padding:15px;
    margin:12px 0;
    border:2px solid #e2e8f0;
    border-radius:12px;
    cursor:pointer;
    font-size:17px;
}

.option input{margin-right:10px}

button{
    border:0;
    border-radius:10px;
    padding:13px 20px;
    font-size:16px;
    font-weight:bold;
    cursor:pointer;
    margin:5px;
}

.start-btn{background:#2563eb;color:white}
.next-btn{background:#16a34a;color:white}
.submit-btn{background:#dc2626;color:white}
.restart-btn{background:#7c3aed;color:white}
.home-btn{background:#475569;color:white}

.progress{
    color:#64748b;
    font-weight:bold;
    margin-bottom:15px;
}

.stats{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:12px;
    margin:20px 0;
}

.stat{
    background:#f8fafc;
    padding:15px;
    border-radius:12px;
    text-align:center;
}

.result-box{text-align:center}

.result-number{
    font-size:42px;
    font-weight:bold;
    color:#2563eb;
}

.feedback{
    padding:12px;
    border-radius:10px;
    margin-top:15px;
    font-weight:bold;
}

.correct{
    background:#dcfce7;
    color:#166534;
}

.wrong{
    background:#fee2e2;
    color:#991b1b;
}

label{
    display:block;
    margin:10px 0;
    font-size:17px;
}

footer{
    text-align:center;
    padding:25px;
    color:#64748b;
}
</style>
</head>

<body>

<header>
<h1>💻 Technology Quiz</h1>
<p>Knowledge World</p>
</header>

<div class="container">

<div id="startScreen" class="card">

<h2>🧠 Technology Quiz শুরু করুন</h2>

<p>
এখানে মোট <b>৫০টি প্রশ্ন</b> আছে।
আপনি যতগুলো প্রশ্ন জানেন, ততগুলো উত্তর দিতে পারেন।
</p>

<hr>

<h3>Negative Marking</h3>

<label>
<input type="radio" name="negative" value="yes" checked>
হ্যাঁ — ভুল উত্তরের জন্য -0.25
</label>

<label>
<input type="radio" name="negative" value="no">
না — ভুল উত্তরের জন্য কোনো নম্বর কাটা হবে না
</label>

<br>

<button class="start-btn" onclick="startQuiz()">
🚀 Quiz শুরু করুন
</button>

<br>

<button class="home-btn" onclick="goHome()">
🏠 Quiz Dashboard
</button>

</div>


<div id="quizScreen" class="card hidden">

<div class="progress" id="progress"></div>

<h2 id="question"></h2>

<div id="options"></div>

<div id="feedback"></div>

<br>

<button class="next-btn" onclick="nextQuestion()">
পরের প্রশ্ন →
</button>

<button class="submit-btn" onclick="submitQuiz()">
🏁 Quiz Submit
</button>

</div>


<div id="resultScreen" class="card hidden">

<div class="result-box">

<h2>🎉 Quiz শেষ!</h2>

<p>আপনার Score</p>

<div class="result-number" id="score"></div>

<div class="stats">

<div class="stat">
<b>✅ সঠিক</b>
<div id="correctCount">0</div>
</div>

<div class="stat">
<b>❌ ভুল</b>
<div id="wrongCount">0</div>
</div>

<div class="stat">
<b>⭕ উত্তর দেওয়া হয়নি</b>
<div id="unansweredCount">0</div>
</div>

<div class="stat">
<b>📚 মোট প্রশ্ন</b>
<div>50</div>
</div>

</div>

<button class="restart-btn" onclick="restartQuiz()">
🔄 আবার শুরু করুন
</button>

<button class="home-btn" onclick="goHome()">
🏠 Quiz Dashboard
</button>

</div>
</div>

</div>

<footer>
© Knowledge World | তৈরি করেছেন ইয়াছিন
</footer>


<script>

const questions = [

{
q:"CPU-এর পূর্ণরূপ কী?",
options:[
"Central Processing Unit",
"Computer Personal Unit",
"Central Program Utility",
"Computer Processing Utility"
],
answer:0
},

{
q:"কম্পিউটারের প্রধান মেমোরি কোনটি?",
options:["RAM","Mouse","Keyboard","Monitor"],
answer:0
},

{
q:"RAM-এর পূর্ণরূপ কী?",
options:[
"Random Access Memory",
"Read Access Machine",
"Random Application Memory",
"Read And Memory"
],
answer:0
},

{
q:"ROM-এর পূর্ণরূপ কী?",
options:[
"Read Only Memory",
"Random Only Memory",
"Read Open Memory",
"Run Only Machine"
],
answer:0
},

{
q:"কম্পিউটারের তথ্য স্থায়ীভাবে সংরক্ষণে কোনটি ব্যবহার করা হয়?",
options:["Storage","Mouse","Speaker","Webcam"],
answer:0
},

{
q:"SSD কী?",
options:[
"এক ধরনের Storage Device",
"এক ধরনের Monitor",
"এক ধরনের Keyboard",
"এক ধরনের Printer"
],
answer:0
},

{
q:"ইন্টারনেট কী?",
options:[
"বিশ্বব্যাপী সংযুক্ত কম্পিউটার নেটওয়ার্ক",
"একটি Keyboard",
"একটি Operating System",
"একটি Game"
],
answer:0
},

{
q:"WWW-এর পূর্ণরূপ কী?",
options:[
"World Wide Web",
"World Web Window",
"Wide World Web",
"Web World Wide"
],
answer:0
},

{
q:"Website দেখার জন্য কোন Software ব্যবহার করা হয়?",
options:[
"Web Browser",
"Calculator",
"Paint",
"Notepad"
],
answer:0
},

{
q:"নিচের কোনটি Web Browser?",
options:["Chrome","Windows","Android","Linux"],
answer:0
},

{
q:"Google-এর Search Engine-এর নাম কী?",
options:["Google Search","Chrome","Android","Drive"],
answer:0
},

{
q:"Email কী কাজে ব্যবহার করা হয়?",
options:[
"ইলেকট্রনিক বার্তা পাঠাতে",
"কম্পিউটার পরিষ্কার করতে",
"ছবি প্রিন্ট করতে",
"ব্যাটারি চার্জ করতে"
],
answer:0
},

{
q:"Wi-Fi কী?",
options:[
"তারবিহীন নেটওয়ার্ক প্রযুক্তি",
"একটি Operating System",
"একটি Printer",
"একটি Battery"
],
answer:0
},

{
q:"Bluetooth সাধারণত কী কাজে ব্যবহার করা হয়?",
options:[
"স্বল্প দূরত্বে ডিভাইস সংযোগে",
"ইন্টারনেট বন্ধ করতে",
"কম্পিউটার ঠান্ডা করতে",
"স্ক্রিন পরিষ্কার করতে"
],
answer:0
},

{
q:"USB-এর পূর্ণরূপ কী?",
options:[
"Universal Serial Bus",
"United System Bus",
"Universal System Board",
"User Serial Board"
],
answer:0
},

{
q:"Keyboard কী ধরনের Device?",
options:["Input Device","Output Device","Storage Device","Network Device"],
answer:0
},

{
q:"Monitor কী ধরনের Device?",
options:["Input Device","Output Device","Storage Device","Power Device"],
answer:1
},

{
q:"Mouse কী কাজে ব্যবহার করা হয়?",
options:[
"কম্পিউটারে নির্দেশ দিতে ও নির্বাচন করতে",
"শুধু শব্দ শোনাতে",
"ছবি প্রিন্ট করতে",
"ইন্টারনেট তৈরি করতে"
],
answer:0
},

{
q:"Printer-এর কাজ কী?",
options:[
"ডিজিটাল তথ্য কাগজে ছাপানো",
"ইন্টারনেট চালানো",
"ভিডিও ধারণ করা",
"শব্দ রেকর্ড করা"
],
answer:0
},

{
q:"Operating System-এর উদাহরণ কোনটি?",
options:["Windows","Google","YouTube","Facebook"],
answer:0
},

{
q:"Android কী?",
options:[
"একটি Mobile Operating System",
"একটি Printer",
"একটি Browser",
"একটি Keyboard"
],
answer:0
},

{
q:"Linux কী?",
options:[
"একটি Operating System",
"একটি Social Media",
"একটি Search Engine",
"একটি Camera"
],
answer:0
},

{
q:"Microsoft Word কী কাজে ব্যবহার করা হয়?",
options:[
"Document তৈরি ও সম্পাদনা করতে",
"শুধু গান শুনতে",
"শুধু ছবি তুলতে",
"শুধু Internet চালাতে"
],
answer:0
},

{
q:"Excel সাধারণত কী কাজে ব্যবহার করা হয়?",
options:[
"Spreadsheet ও হিসাবের কাজে",
"ভিডিও কল করতে",
"গান শুনতে",
"ছবি তুলতে"
],
answer:0
},

{
q:"PowerPoint কী কাজে ব্যবহার করা হয়?",
options:[
"Presentation তৈরি করতে",
"Virus তৈরি করতে",
"Internet বন্ধ করতে",
"File মুছতে"
],
answer:0
},

{
q:"PDF-এর পূর্ণরূপ কী?",
options:[
"Portable Document Format",
"Personal Data File",
"Public Document File",
"Portable Data Folder"
],
answer:0
},

{
q:"Cloud Storage কী?",
options:[
"অনলাইনে তথ্য সংরক্ষণের ব্যবস্থা",
"কম্পিউটারের Fan",
"এক ধরনের Mouse",
"এক ধরনের Monitor"
],
answer:0
},

{
q:"Google Drive কী?",
options:[
"Cloud Storage Service",
"Web Browser",
"Operating System",
"Keyboard"
],
answer:0
},

{
q:"YouTube কী ধরনের Platform?",
options:[
"ভিডিও শেয়ারিং Platform",
"Operating System",
"Search Engine মাত্র",
"Antivirus"
],
answer:0
},

{
q:"Social Media-এর উদাহরণ কোনটি?",
options:["Facebook","Windows","Linux","Excel"],
answer:0
},

{
q:"AI-এর পূর্ণরূপ কী?",
options:[
"Artificial Intelligence",
"Automatic Internet",
"Advanced Information",
"Artificial Internet"
],
answer:0
},

{
q:"AI-এর বাংলা অর্থ কী?",
options:[
"কৃত্রিম বুদ্ধিমত্তা",
"স্বয়ংক্রিয় ইন্টারনেট",
"কম্পিউটার স্মৃতি",
"ডিজিটাল ছবি"
],
answer:0
},

{
q:"Machine Learning কী?",
options:[
"কম্পিউটারকে তথ্য থেকে শেখানোর একটি পদ্ধতি",
"এক ধরনের Keyboard",
"এক ধরনের Printer",
"
