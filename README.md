<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<title>فرم آنلاین گارانتی صنعت وارنا</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body { font-family: Tahoma, sans-serif; direction: rtl; margin:0; padding:0; background:#f2f2f2;}
.container { max-width:800px; margin:20px auto; background:#ffffff; padding:20px; border:2px solid #b2d8b2; border-radius:10px;}
h2 { color:#2a7d2a; text-align:center;}
label { display:block; margin-top:10px; font-weight:bold;}
input, select, textarea { width:100%; padding:8px; margin-top:5px; box-sizing:border-box; }
button { margin-top:20px; padding:10px; width:100%; background-color:#2a7d2a; color:white; border:none; font-size:16px; border-radius:5px;}
button:hover { background-color:#1f5c1f; cursor:pointer;}
#contract { background:#e6f2e6; padding:10px; border-radius:5px; margin-bottom:15px;}
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

<b>ماده ۵ – فعال‌سازی:</b> پس از بارگذاری عکس دستگاه و رسید پرداخت به شماره حساب ۱۰۰۰۱۴۳۰۷۳۸۷۱ یا کارت ۶۲۷۷۶۰۱۳۶۳۲۵۱۶۶۹ به نام سید علی میرمحمدی و تأیید پرداخت.<br><br>

<b>ماده ۶ – مشخصات طرف دوم:</b> نام مسئول، کد باجه، کد ملی، آدرس، شماره تماس.<br><br>

<b>ماده ۷ – مدت قرارداد:</b> یک سال از تاریخ فعال‌سازی.<br><br>

<b>ماده ۸ – سایر موارد:</b> توافق طرفین ملاک عمل خواهد بود.
</div>

<label>نام مسئول باجه:</label><input type="text" id="name" required>
<label>کد باجه:</label><input type="text" id="code" required>
<label>کد ملی:</label><input type="text" id="national" required>
<label>آدرس:</label><input type="text" id="address" required>
<label>شماره تماس:</label><input type="text" id="phone" required>

<label>مدل دستگاه:</label>
<select id="model">
<option value="Evolis PPL4">Evolis PPL4</option>
<option value="Evolis Dualys 3">Evolis Dualys 3</option>
<option value="QB10">QB10</option>
<option value="Hodo">Hodo</option>
<option value="Smart 50">Smart 50</option>
<option value="Smart 51">Smart 51</option>
</select>

<label>سطح گارانتی:</label>
<select id="level">
<option value="Gold">طلایی</option>
<option value="Silver">نقره‌ای</option>
<option value="Bronze">برنزی</option>
</select>

<label>بارگذاری عکس دستگاه:</label>
<input type="file" id="devicePhoto" accept="image/*" required>

<label>رسید پرداخت مرحله اول:</label>
<input type="text" id="receipt" required>

<button onclick="generatePDF()">تولید PDF قرارداد</button>
</div>

<!-- کتابخانه html2pdf داخلی -->
<script src="https://rawcdn.githack.com/eKoopmans/html2pdf/master/dist/html2pdf.bundle.js"></script>

<script>
function generatePDF(){
    const name=document.getElementById('name').value;
    const code=document.getElementById('code').value;
    const national=document.getElementById('national').value;
    const address=document.getElementById('address').value;
    const phone=document.getElementById('phone').value;
    const model=document.getElementById('model').value;
    const level=document.getElementById('level').value;
    const receipt=document.getElementById('receipt').value;
    const photoFile=document.getElementById('devicePhoto').files[0];
    if(!name||!code||!national||!address||!phone||!receipt||!photoFile){
        alert("تمام فیلدها و عکس دستگاه را پر کنید.");
        return;
    }
    const reader=new FileReader();
    reader.onload=function(e){
        const div=document.createElement('div');
        div.innerHTML=document.getElementById('contract').innerHTML+
        `<p>نام مسئول باجه: ${name}</p>
         <p>کد باجه: ${code}</p>
         <p>کد ملی: ${national}</p>
         <p>آدرس: ${address}</p>
         <p>شماره تماس: ${phone}</p>
         <p>مدل دستگاه: ${model}</p>
         <p>سطح گارانتی: ${level}</p>
         <p>رسید پرداخت: ${receipt}</p>
         <img src="${e.target.result}" style="width:200px;">`;
        html2pdf().from(div).set({margin:10, filename:`Garanti_${model}_${name}.pdf`, html2canvas:{scale:2}}).save();
    };
    reader.readAsDataURL(photoFile);
}
</script>

</body>
</html>
