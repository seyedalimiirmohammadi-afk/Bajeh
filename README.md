<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<title>فرم آنلاین گارانتی صنعت وارنا</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body { font-family: Tahoma, sans-serif; direction: rtl; margin:0; padding:0; background:#f2f2f2;}
.container { max-width:900px; margin:20px auto; background:#ffffff; padding:20px; border:2px solid #b2d8b2; border-radius:12px;}
h2 { color:#2a7d2a; text-align:center; margin-bottom:20px;}
label { display:block; margin-top:12px; font-weight:bold;}
input, select, textarea { width:100%; padding:10px; margin-top:5px; box-sizing:border-box; border:1px solid #b2d8b2; border-radius:6px; }
input[type="file"] { padding:3px; }
button { margin-top:20px; padding:12px; width:100%; background-color:#2a7d2a; color:white; border:none; font-size:17px; border-radius:8px;}
button:hover { background-color:#1f5c1f; cursor:pointer;}
#contract { background:#e6f2e6; padding:12px; border-radius:8px; margin-bottom:15px; max-height:400px; overflow:auto;}
#amount { font-weight:bold; color:#2a7d2a; margin-top:5px; }
.section { border-top:1px solid #b2d8b2; padding-top:15px; margin-top:15px; }
</style>
</head>
<body>

<div class="container">
<h2>شرکت فنی و مهندسی صنعت وارنا<br>قرارداد رسمی خدمات گارانتی دستگاه‌های صدور کارت</h2>

<div id="contract">
<b>ماده ۱ – موضوع قرارداد:</b> ارائه خدمات گارانتی سالیانه برای دستگاه‌های صدور کارت مدل‌های Evolis PPL4, Evolis Dualys 3, QB10, Hodo, Smart 50, Smart 51 مطابق سطح گارانتی انتخابی.<br><br>

<b>ماده ۲ – سطوح گارانتی:</b><br>
🔶 طلایی: بازبینی، سرویس و تعمیر کامل قطعات، ارسال مواد مصرفی جهت تمیزکاری، پشتیبانی تلفنی، پاسخ حداکثر ۳ روز کاری.<br>
⚪️ نقره‌ای: بازبینی و تعمیر قطعات اصلی، پشتیبانی تلفنی، پاسخ حداکثر ۵ روز کاری.<br>
🟤 برنزی: بررسی و تعمیر اولیه، پشتیبانی تلفنی، پاسخ حداکثر ۷ روز کاری.<br><br>

<b>ماده ۳ – هزینه خدمات:</b><br>
Evolis PPL4/Dualys3/QB10: طلایی ۴,۰۰۰,۰۰۰ / نقره‌ای ۳,۶۰۰,۰۰۰ / برنزی ۳,۲۴۰,۰۰۰ تومان<br>
Hodo: طلایی ۲,۰۰۰,۰۰۰ / نقره‌ای ۱,۹۰۰,۰۰۰ / برنزی ۱,۸۰۵,۰۰۰ تومان<br>
Smart 50: طلایی ۵,۰۰۰,۰۰۰ / نقره‌ای ۴,۵۰۰,۰۰۰ / برنزی ۴,۰۵۰,۰۰۰ تومان<br>
Smart 51: طلایی ۶,۰۰۰,۰۰۰ / نقره‌ای ۵,۴۰۰,۰۰۰ / برنزی ۴,۸۶۰,۰۰۰ تومان<br>
پرداخت ۵۰٪ ابتدای قرارداد و ۵۰٪ شش ماه بعد.<br><br>

<b>ماده ۴ – شرایط کلی:</b><br>
۱. هزینه قطعات مصرفی بر عهده طرف دوم.<br>
۲. هزینه ارسال و دریافت بر عهده طرف دوم، مگر نیاز به ارسال مجدد.<br>
۳. ضربه، آب‌خوردگی و نوسانات برق شامل گارانتی نمی‌گردد و هزینه جداگانه محاسبه می‌شود.<br>
۴. خدمات حضوری در محل ارائه نمی‌شود.<br><br>

<b>ماده ۵ – فعال‌سازی:</b> پس از بارگذاری عکس دستگاه و عکس رسید پرداخت به شماره حساب ۱۰۰۰۱۴۳۰۷۳۸۷۱ یا کارت ۶۲۷۷۶۰۱۳۶۳۲۵۱۶۶۹ به نام سید علی میرمحمدی و تأیید پرداخت.<br><br>

<b>ماده ۶ – مشخصات طرف دوم:</b> نام مسئول، کد باجه، کد ملی، آدرس، شماره تماس.<br><br>

<b>ماده ۷ – مدت قرارداد:</b> یک سال از تاریخ فعال‌سازی.<br><br>

<b>ماده ۸ – سایر موارد:</b> توافق طرفین ملاک عمل خواهد بود.
</div>

<div class="section">
<label>نام مسئول باجه:</label><input type="text" id="name" required>
<label>کد باجه:</label><input type="text" id="code" required>
<label>کد ملی:</label><input type="text" id="national" required>
<label>آدرس:</label><input type="text" id="address" required>
<label>شماره تماس:</label><input type="text" id="phone" required>
</div>

<div class="section">
<label>مدل دستگاه:</label>
<select id="model" onchange="updateAmount()">
<option value="Evolis PPL4">Evolis PPL4</option>
<option value="Evolis Dualys 3">Evolis Dualys 3</option>
<option value="QB10">QB10</option>
<option value="Hodo">Hodo</option>
<option value="Smart 50">Smart 50</option>
<option value="Smart 51">Smart 51</option>
</select>

<label>سطح گارانتی:</label>
<select id="level" onchange="updateAmount()">
<option value="Gold">طلایی</option>
<option value="Silver">نقره‌ای</option>
<option value="Bronze">برنزی</option>
</select>

<p>مبلغ گارانتی: <span id="amount">۰ تومان</span></p>
</div>

<div class="section">
<label>بارگذاری عکس دستگاه:</label>
<input type="file" id="devicePhoto" accept="image/*" required>

<label>بارگذاری عکس رسید پرداخت:</label>
<input type="file" id="receiptPhoto" accept="image/*" required>
</div>

<button onclick="generatePDF()">تولید PDF قرارداد</button>

<script src="https://rawcdn.githack.com/eKoopmans/html2pdf/master/dist/html2pdf.bundle.js"></script>
<script>
const prices = {
  "Evolis PPL4": {"Gold":4000000,"Silver":3600000,"Bronze":3240000},
  "Evolis Dualys 3": {"Gold":4000000,"Silver":3600000,"Bronze":3240000},
  "QB10": {"Gold":4000000,"Silver":3600000,"Bronze":3240000},
  "Hodo": {"Gold":2000000,"Silver":1900000,"Bronze":1805000},
  "Smart 50": {"Gold":5000000,"Silver":4500000,"Bronze":4050000},
  "Smart 51": {"Gold":6000000,"Silver":5400000,"Bronze":4860000}
};

function updateAmount(){
  const model = document.getElementById('model').value;
  const level = document.getElementById('level').value;
  const amount = prices[model][level];
  document.getElementById('amount').innerText = amount.toLocaleString() + " تومان";
}

function generatePDF(){
    const name=document.getElementById('name').value;
    const code=document.getElementById('code').value;
    const national=document.getElementById('national').value;
    const address=document.getElementById('address').value;
    const phone=document.getElementById('phone').value;
    const model=document.getElementById('model').value;
    const level=document.getElementById('level').value;
    const devicePhoto=document.getElementById('devicePhoto').files[0];
    const receiptPhoto=document.getElementById('receiptPhoto').files[0];

    if(!name||!code||!national||!address||!phone||!devicePhoto||!receiptPhoto){
        alert("تمام فیلدها و عکس‌ها را پر کنید.");
        return
