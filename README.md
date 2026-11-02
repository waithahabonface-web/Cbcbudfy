# Cbcbudfy
For learning experience for all students 
<!DOCTYPE html>  <html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Elimu CBC - Guardian Portal &amp; Capitation Statement</title>  
  <link rel="preconnect" href="https://fonts.googleapis.com">  
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>  
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">  
  <script src="https://cdn.tailwindcss.com"></script>  
  <script>  
    tailwind.config = {  
      theme: {  
        extend: {  
          fontFamily: {  
            sans: ['Plus Jakarta Sans', 'sans-serif'],  
          },  
          colors: {  
            brand: {  
              50: '#eefaf2',  
              100: '#d7f3e2',  
              200: '#b0e7c6',  
              500: '#137547',  
              600: '#0e5b37',  
              700: '#0b472b',  
            }  
          }  
        }  
      }  
    }  
  </script>  
</head>  
<body class="bg-[#f0f3ff] text-slate-800 font-sans antialiased min-h-screen pb-24 selection:bg-emerald-200">    <!-- Mobile Container Wrapper -->    <div class="max-w-md mx-auto min-h-screen bg-[#f9f9ff] shadow-xl relative border-x border-slate-200">  <!-- Top Navigation Header -->  
<header class="bg-white/95 backdrop-blur-md border-b border-slate-200 sticky top-0 z-30 px-4 py-3">  
  <div class="flex items-center justify-between">  
    <div class="flex items-center space-x-2.5">  
      <div class="w-8 h-8 rounded-xl bg-brand-500 text-white flex items-center justify-center font-extrabold text-sm shadow-sm">  
        🇰🇪  
      </div>  
      <div>  
        <div class="flex items-center space-x-1.5">  
          <span class="font-extrabold text-slate-900 text-sm tracking-tight">Elimu CBC</span>  
          <span class="text-[9px] font-bold px-1.5 py-0.5 rounded bg-emerald-100 text-emerald-800 uppercase tracking-wider">MoE v2.4</span>  
        </div>  
        <span class="text-[10px] text-slate-500 font-medium">NEMIS Verified Portal</span>  
      </div>  
    </div>  

    <!-- Grade Selector Pill -->  
    <button id="open-grade-modal" class="flex items-center space-x-1.5 px-2.5 py-1 rounded-full bg-slate-100 hover:bg-slate-200 border border-slate-200 transition text-xs font-bold text-brand-700">  
      <span class="w-2 h-2 rounded-full bg-brand-500 animate-pulse"></span>  
      <span>Grade 7 (JSS)</span>  
      <svg class="w-3.5 h-3.5 text-slate-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>  
    </button>  
  </div>  

  <!-- Learner / Guardian Role Segmented Control -->  
  <div class="mt-3 p-1 bg-slate-100 rounded-xl grid grid-cols-2 text-xs font-bold gap-1">  
    <button type="button" class="py-1.5 rounded-lg text-slate-600 hover:text-slate-900 transition flex items-center justify-center space-x-1">  
      <span>🎓</span>  
      <span>Learner View</span>  
    </button>  
    <button type="button" class="py-1.5 rounded-lg bg-white text-brand-700 shadow-xs flex items-center justify-center space-x-1">  
      <span>🛡️</span>  
      <span>Guardian View</span>  
    </button>  
  </div>  
</header>  

<!-- Main Content Area -->  
<main class="px-4 py-4 space-y-4">  

  <!-- Student & Guardian Verified Header Card -->  
  <div class="bg-white rounded-2xl p-4 border border-slate-200 shadow-xs space-y-3">  
    <div class="flex items-start justify-between">  
      <div class="flex items-center space-x-3">  
        <div class="w-12 h-12 rounded-2xl bg-gradient-to-tr from-brand-600 to-emerald-400 text-white flex items-center justify-center font-bold text-lg shadow-sm">  
          AW  
        </div>  
        <div>  
          <div class="flex items-center space-x-1.5">  
            <h2 class="text-base font-extrabold text-slate-900">Amani Wanjiku</h2>  
            <span class="px-1.5 py-0.5 rounded text-[10px] font-bold bg-emerald-100 text-emerald-800">Grade 7 East</span>  
          </div>  
          <p class="text-xs text-slate-600 font-mono">UPI: 10428901-04 • MoE: #20401052</p>  
          <p class="text-[11px] text-slate-500">Green Park Comprehensive School (Westlands)</p>  
        </div>  
      </div>  
      <span class="p-1.5 bg-emerald-50 text-emerald-700 rounded-full text-xs font-bold border border-emerald-200">  
        ✓ Active  
      </span>  
    </div>  

    <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-xs">  
      <div class="text-slate-600">  
        <span class="text-slate-400 font-medium">Guardian:</span> <strong class="text-slate-800 font-semibold">Grace Mwangi</strong> (+254 722 490 154)  
      </div>  
      <button class="text-brand-600 font-bold hover:underline text-[11px]">Linked Ward</button>  
    </div>  
  </div>  

  <!-- Weekly Attendance Tracker -->  
  <div class="bg-white rounded-2xl p-4 border border-slate-200 shadow-xs space-y-3">  
    <div class="flex items-center justify-between">  
      <div class="flex items-center space-x-2">  
        <div class="w-7 h-7 rounded-lg bg-emerald-100 text-emerald-800 flex items-center justify-center text-xs font-bold">  
          📅  
        </div>  
        <div>  
          <h3 class="text-xs font-extrabold text-slate-900">Weekly Biometric Attendance</h3>  
          <p class="text-[10px] text-slate-500">Term 1 • Week 6 (Mon 10 – Fri 14)</p>  
        </div>  
      </div>  
      <div class="text-right">  
        <span class="text-sm font-black text-emerald-700">100%</span>  
        <span class="block text-[9px] text-slate-500 font-semibold">5/5 Present</span>  
      </div>  
    </div>  

    <!-- Attendance Days Strip -->  
    <div class="grid grid-cols-5 gap-1.5 text-center">  
      <div class="p-2 rounded-xl bg-emerald-50 border border-emerald-200">  
        <span class="text-[10px] font-bold text-slate-500 block">Mon</span>  
        <span class="text-xs font-black text-emerald-700 block">07:18</span>  
        <span class="text-[9px] text-emerald-600 font-medium">In Class</span>  
      </div>  
      <div class="p-2 rounded-xl bg-emerald-50 border border-emerald-200">  
        <span class="text-[10px] font-bold text-slate-500 block">Tue</span>  
        <span class="text-xs font-black text-emerald-700 block">07:12</span>  
        <span class="text-[9px] text-emerald-600 font-medium">In Class</span>  
      </div>  
      <div class="p-2 rounded-xl bg-emerald-50 border border-emerald-200">  
        <span class="text-[10px] font-bold text-slate-500 block">Wed</span>  
        <span class="text-xs font-black text-emerald-700 block">07:25</span>  
        <span class="text-[9px] text-emerald-600 font-medium">In Class</span>  
      </div>  
      <div class="p-2 rounded-xl bg-emerald-50 border border-emerald-200">  
        <span class="text-[10px] font-bold text-slate-500 block">Thu</span>  
        <span class="text-xs font-black text-emerald-700 block">07:15</span>  
        <span class="text-[9px] text-emerald-600 font-medium">In Class</span>  
      </div>  
      <div class="p-2 rounded-xl bg-emerald-500 text-white font-bold shadow-xs">  
        <span class="text-[10px] text-emerald-100 block">Fri</span>  
        <span class="text-xs font-black block">07:20</span>  
        <span class="text-[9px] text-emerald-100 font-medium">Present</span>  
      </div>  
    </div>  

    <!-- SMS Alert Notice & Teacher Note -->  
    <div class="bg-slate-50 rounded-xl p-3 border border-slate-100 space-y-2 text-xs">  
      <div class="flex items-center justify-between text-slate-600">  
        <span class="flex items-center space-x-1.5 text-[11px]">  
          <span>📱</span>  
          <span>Morning Gate SMS dispatched at <strong>07:22 AM</strong></span>  
        </span>  
        <span class="text-[10px] text-emerald-700 font-bold">Delivered</span>  
      </div>  
      <div class="pt-2 border-t border-slate-200/60 flex items-start space-x-2">  
        <span class="text-sm">👩‍🏫</span>  
        <div class="flex-1">  
          <span class="text-[10px] font-bold text-slate-800">Tr. Kamau (Class Teacher):</span>  
          <p class="text-[11px] text-slate-600 leading-tight">  
            "Amani completed all practical Pre-Tech safety procedures today with exemplary precision."  
          </p>  
        </div>  
        <button class="px-2 py-1 bg-emerald-600 hover:bg-emerald-700 text-white text-[10px] font-bold rounded-lg shrink-0">  
          WhatsApp  
        </button>  
      </div>  
    </div>  
  </div>  

  <!-- Government Capitation & Financial Statement Card -->  
  <div class="bg-white rounded-2xl p-4 border border-slate-200 shadow-xs space-y-3.5">  
    <div class="flex items-center justify-between">  
      <div>  
        <div class="text-[10px] font-extrabold uppercase tracking-wider text-slate-400">MoE Capitation &amp; Levies</div>  
        <h3 class="text-sm font-extrabold text-slate-900">Term 1 Account Statement</h3>  
      </div>  
      <span class="px-2.5 py-1 rounded-full text-xs font-extrabold bg-emerald-100 text-emerald-800">  
        Cleared (KES 0.00)  
      </span>  
    </div>  

    <!-- Statement Balance Box -->  
    <div class="bg-gradient-to-r from-emerald-50 to-teal-50 border border-emerald-200 rounded-2xl p-3.5 text-center">  
      <span class="text-[10px] font-bold uppercase text-slate-500 tracking-wider">Current Outstanding Balance</span>  
      <div class="text-2xl font-black text-emerald-900 mt-0.5">KES 0.00</div>  
      <p class="text-[10px] text-emerald-700 mt-1 font-medium">  
        Account verified in good standing • Reconciled on NEMIS  
      </p>  
    </div>  

    <!-- Government Capitation Itemized List -->  
    <div class="space-y-2">  
      <div class="flex items-center justify-between text-xs font-bold text-slate-800">  
        <span>MoE Free Day Secondary (FDSE)</span>  
        <span class="text-emerald-700">KES 15,042 / yr (100% Gov Funded)</span>  
      </div>  

      <div class="space-y-1.5 text-xs text-slate-600 bg-slate-50 p-2.5 rounded-xl border border-slate-100">  
        <div class="flex justify-between">  
          <span>• Tuition &amp; CBC KICD Coursebooks</span>  
          <span class="font-mono font-semibold text-slate-800">KES 4,000</span>  
        </div>  
        <div class="flex justify-between">  
          <span>• Pre-Tech &amp; Science Labs Maintenance</span>  
          <span class="font-mono font-semibold text-slate-800">KES 3,500</span>  
        </div>  
        <div class="flex justify-between">  
          <span>• Co-Curricular &amp; National Sports</span>  
          <span class="font-mono font-semibold text-slate-800">KES 2,000</span>  
        </div>  
        <div class="flex justify-between">  
          <span>• Integrated Infrastructure Grant</span>  
          <span class="font-mono font-semibold text-slate-800">KES 5,542</span>  
        </div>  
      </div>  
    </div>  

    <!-- Approved BOM / PTA Levies -->  
    <div class="space-y-2 pt-1 border-t border-slate-100">  
      <div class="flex items-center justify-between text-xs font-bold text-slate-800">  
        <span>Approved PTA / Lunch Contributions</span>  
        <span class="text-xs text-slate-500">M-Pesa Verified</span>  
      </div>  

      <div class="space-y-1.5 text-xs text-slate-600">  
        <div class="flex justify-between items-center py-1 border-b border-slate-100">  
          <div>  
            <div class="font-semibold text-slate-800">Term 1 Hot Lunch Program</div>  
            <div class="text-[10px] text-slate-400 font-mono">Ref: QJD4812KLS • 12 Jan 2025</div>  
          </div>  
          <span class="font-mono font-bold text-slate-900">KES 4,500 <span class="text-emerald-600 font-sans text-[10px]">✓</span></span>  
        </div>  
        <div class="flex justify-between items-center py-1">  
          <div>  
            <div class="font-semibold text-slate-800">CBC Agricultural Practical Kit</div>  
            <div class="text-[10px] text-slate-400 font-mono">Ref: QKD9923KRA • 20 Jan 2025</div>  
          </div>  
          <span class="font-mono font-bold text-slate-900">KES 1,800 <span class="text-emerald-600 font-sans text-[10px]">✓</span></span>  
        </div>  
      </div>  
    </div>  

    <!-- Statement Actions -->  
    <div class="grid grid-cols-2 gap-2 pt-2">  
      <button class="py-2.5 px-3 bg-brand-500 hover:bg-brand-600 text-white rounded-xl text-xs font-bold flex items-center justify-center space-x-1.5 transition shadow-xs">  
        <span>📥</span>  
        <span>Download PDF</span>  
      </button>  
      <button class="py-2.5 px-3 bg-slate-100 hover:bg-slate-200 text-slate-800 rounded-xl text-xs font-bold flex items-center justify-center space-x-1.5 transition">  
        <span>💳</span>  
        <span>Pay M-Pesa</span>  
      </button>  
    </div>  
  </div>  

</main>  

<!-- Fixed Bottom Tab Bar -->  
<nav class="fixed bottom-0 max-w-md w-full bg-white border-t border-slate-200 px-4 py-2.5 flex justify-around items-center z-20">  
  <a href="#" class="flex flex-col items-center text-brand-600 text-[10px] font-bold">  
    <span class="text-lg">📖</span>  
    <span>Curriculum</span>  
  </a>  
  <a href="#" class="flex flex-col items-center text-slate-400 hover:text-slate-600 text-[10px] font-medium">  
    <span class="text-lg">🤖</span>  
    <span>AI Tutor</span>  
  </a>  
  <a href="#" class="flex flex-col items-center text-slate-400 hover:text-slate-600 text-[10px] font-medium">  
    <span class="text-lg">📊</span>  
    <span>Assessment</span>  
  </a>  
  <a href="#" class="flex flex-col items-center text-slate-400 hover:text-slate-600 text-[10px] font-medium">  
    <span class="text-lg">📹</span>  
    <span>Tutor Studio</span>  
  </a>  
  <a href="#" class="flex flex-col items-center text-slate-400 hover:text-slate-600 text-[10px] font-medium">  
    <span class="text-lg">👤</span>  
    <span>Profile</span>  
  </a>  
</nav>  

<!-- Global Grade Switcher Modal (Overlay) -->  
<div id="grade-modal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-xs z-50 flex flex-col justify-end hidden">  
  <div class="bg-white rounded-t-3xl p-5 max-w-md w-full mx-auto max-h-[85vh] overflow-y-auto space-y-4 shadow-2xl">  
    <div class="w-12 h-1.5 bg-slate-200 rounded-full mx-auto"></div>  

    <div class="flex items-center justify-between">  
      <div>  
        <h3 class="text-base font-extrabold text-slate-900">CBC Grade Switcher</h3>  
        <p class="text-xs text-slate-500">2-6-3-3-3 System (Grades 1–12)</p>  
      </div>  
      <button id="close-grade-modal" class="w-8 h-8 rounded-full bg-slate-100 text-slate-600 hover:bg-slate-200 flex items-center justify-center font-bold text-sm">  
        ✕  
      </button>  
    </div>  

    <!-- Grade Tiers -->  
    <div class="space-y-3">  
      <div>  
        <span class="text-[11px] font-bold text-brand-700 uppercase tracking-wider block mb-1.5">Junior Secondary School (JSS)</span>  
        <div class="grid grid-cols-3 gap-2">  
          <div class="p-3 rounded-xl border-2 border-brand-500 bg-brand-50 text-left cursor-pointer">  
            <div class="text-xs font-black text-brand-800">Grade 7</div>  
            <div class="text-[10px] text-brand-600 font-semibold">Active Selection</div>  
          </div>  
          <div class="p-3 rounded-xl border border-slate-200 bg-white text-left hover:border-slate-400 cursor-pointer">  
            <div class="text-xs font-bold text-slate-800">Grade 8</div>  
            <div class="text-[10px] text-slate-500">Second Year JSS</div>  
          </div>  
          <div class="p-3 rounded-xl border border-slate-200 bg-white text-left hover:border-slate-400 cursor-pointer">  
            <div class="text-xs font-bold text-slate-800">Grade 9</div>  
            <div class="text-[10px] text-slate-500">KJSEA Candidate</div>  
          </div>  
        </div>  
      </div>  

      <div>  
        <span class="text-[11px] font-bold text-slate-500 uppercase tracking-wider block mb-1.5">Upper Primary (Grades 4–6)</span>  
        <div class="grid grid-cols-3 gap-2">  
          <div class="p-3 rounded-xl border border-slate-200 bg-white text-left hover:border-slate-400 cursor-pointer">  
            <div class="text-xs font-bold text-slate-800">Grade 4</div>  
            <div class="text-[10px] text-slate-500">8 Strands</div>  
          </div>  
          <div class="p-3 rounded-xl border border-slate-200 bg-white text-left hover:border-slate-400 cursor-pointer">  
            <div class="text-xs font-bold text-slate-800">Grade 5</div>  
            <div class="text-[10px] text-slate-500">8 Strands</div>  
          </div>  
          <div class="p-3 rounded-xl border border-slate-200 bg-white text-left hover:border-slate-400 cursor-pointer">  
            <div class="text-xs font-bold text-slate-800">Grade 6</div>  
            <div class="text-[10px] text-emerald-600 font-semibold">KPSEA Exam</div>  
          </div>  
        </div>  
      </div>  

      <div>  
        <span class="text-[11px] font-bold text-slate-500 uppercase tracking-wider block mb-1.5">Foundational (Grades 1–3)</span>  
        <div class="grid grid-cols-3 gap-2">  
          <div class="p-3 rounded-xl border border-slate-200 bg-white text-left hover:border-slate-400 cursor-pointer">  
            <div class="text-xs font-bold text-slate-800">Grade 1</div>  
            <div class="text-[10px] text-slate-500">5 Strands</div>  
          </div>  
          <div class="p-3 rounded-xl border border-slate-200 bg-white text-left hover:border-slate-400 cursor-pointer">  
            <div class="text-xs font-bold text-slate-800">Grade 2</div>  
            <div class="text-[10px] text-slate-500">5 Strands</div>  
          </div>  
          <div class="p-3 rounded-xl border border-slate-200 bg-white text-left hover:border-slate-400 cursor-pointer">  
            <div class="text-xs font-bold text-slate-800">Grade 3</div>  
            <div class="text-[10px] text-slate-500">MLP Diagnostic</div>  
          </div>  
        </div>  
      </div>  
    </div>  

    <button id="confirm-grade" class="w-full py-3 bg-brand-500 hover:bg-brand-600 text-white rounded-xl font-bold text-xs shadow-sm transition">  
      Confirm Grade Context  
    </button>  
  </div>  
</div>

  </div>    <script>  
    // Simple Modal Toggle Script  
    const openBtn = document.getElementById('open-grade-modal');  
    const closeBtn = document.getElementById('close-grade-modal');  
    const confirmBtn = document.getElementById('confirm-grade');  
    const modal = document.getElementById('grade-modal');  
  
    openBtn.addEventListener('click', () => modal.classList.remove('hidden'));  
    closeBtn.addEventListener('click', () => modal.classList.add('hidden'));  
    confirmBtn.addEventListener('click', () => modal.classList.add('hidden'));  
  </script>  </body>  
</html> give hmtl to deploy to ship.page
