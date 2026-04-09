<div id="userInfo" style="display:none; margin:18px 0; padding:14px; background:rgba(255,255,255,0.15); border-radius:18px; text-align:center; box-shadow:0 4px 15px rgba(147,197,253,0.3);">
    مرحباً، <span id="userEmail" style="font-weight:bold; color:#60a5fa;"></span>
    <div style="margin-top:10px;">
        <button id="logoutBtn" style="width:auto; padding:8px 24px; background:#ef4444;">خروج</button>
    </div>
</div>

<hr>

<h2>💰 Income PRO • Blue</h2>

<input type="number" id="amount" placeholder="المبلغ" step="any">
<select id="currency">
    <option value="usd">دولار أمريكي $</option>
    <option value="syp">ليرة سورية ل.س</option>
</select>
<input type="number" id="rate" placeholder="سعر الصرف" value="1" step="any" min="0">
<select id="category">
    <option value="">اختر الفئة</option>
    <option value="راتب">راتب شهري</option>
    <option value="مشروع">عمل حر / مشروع</option>
    <option value="استثمار">استثمار</option>
    <option value="هدية">هدية</option>
    <option value="اخرى">أخرى</option>
</select>
<input type="text" id="note" placeholder="ملاحظات (اختياري)">
<input type="date" id="entryDate">

<select id="filter">
    <option value="all">الكل</option>
    <option value="day">اليوم</option>
    <option value="month">هذا الشهر</option>
</select>
<input type="text" id="search" placeholder="🔍 بحث..." >

<button id="addBtn">إضافة إيراد</button>

<h3 id="totals"></h3>
<div id="list" aria-live="polite"></div>
<canvas id="chart" aria-label="مخطط الإيرادات" role="img"></canvas>

<div style="display:flex; gap:14px; margin-top:25px;">
    <button id="pdfBtn" style="flex:1;">📄 تقرير PDF فاخر</button>
    <button id="backupBtn" style="flex:1;">💾 Backup</button>
    <button id="importBtn" style="flex:1;">📤 Import</button>
</div>