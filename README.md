# fukll[index.html](https://github.com/user-attachments/files/32670164/index.html)
<!DOCTYPE html>
<html lang="zh-TW" class="h-full">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>福岡鬆一下 2026/10/15~10/21</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;500;700&family=Quicksand:wght@600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        peach: {
                            50: '#fdf8f6',
                            100: '#fbe8e3',
                            200: '#f7d2c8',
                            300: '#f0b3a1',
                            400: '#e5856b',
                            500: '#d96142',
                            600: '#c54929',
                            700: '#a33b20',
                        },
                        cream: '#fffaf5',
                        warmdark: '#4a3b32'
                    },
                    fontFamily: {
                        sans: ['"Noto Sans TC"', '"Quicksand"', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Noto Sans TC', sans-serif;
            background-color: #fcf8f5;
            color: #4a3b32;
        }
        .hide-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .hide-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="h-full flex flex-col max-w-md mx-auto shadow-2xl relative overflow-hidden bg-cream">

    <!-- Top Header -->
    <header class="bg-gradient-to-r from-peach-400 to-peach-500 text-white p-4 shadow-md sticky top-0 z-30 flex justify-between items-center rounded-b-2xl">
        <div>
            <h1 class="text-xl font-bold tracking-wide flex items-center gap-2">
                <span>✈️</span> 福岡鬆一下
            </h1>
            <p class="text-xs text-peach-100 font-medium mt-0.5">2026/10/15 (三) ~ 10/21 (二) • 七天六夜</p>
        </div>
        <button onclick="openLinkModal()" class="bg-white/20 hover:bg-white/30 text-white px-3 py-1.5 rounded-full text-xs font-medium backdrop-blur-sm transition flex items-center gap-1 shadow-sm">
            <i class="fa-solid fa-link text-[10px]"></i> 編輯地圖
        </button>
    </header>

    <!-- Main Content Container -->
    <main id="main-container" class="flex-1 overflow-y-auto pb-24 pt-3 px-3 hide-scrollbar">
        
        <!-- ================= TAB 1: 航班 (Flights) ================= -->
        <div id="tab-flights" class="tab-content space-y-4">
            <div class="bg-amber-50 border border-amber-200 text-amber-800 p-3 rounded-xl text-xs flex items-start gap-2 shadow-sm">
                <i class="fa-solid fa-circle-info mt-0.5 text-amber-600"></i>
                <div>
                    <span class="font-bold">航班小叮嚀：</span>出發前請確認護照效期 (6個月以上)，並提前於線上填寫 Visit Japan Web 以加速通關。
                </div>
            </div>

            <!-- Departure Ticket -->
            <div class="bg-white rounded-2xl shadow-md overflow-hidden border border-peach-100">
                <div class="bg-peach-500 text-white px-4 py-2.5 flex justify-between items-center text-sm font-bold">
                    <span class="flex items-center gap-2"><i class="fa-solid fa-plane-departure"></i> 去程航班 (IT720)</span>
                    <span class="bg-white/20 text-xs px-2.5 py-1 rounded-full">10/15 (三)</span>
                </div>
                <div class="p-4 space-y-3">
                    <div class="flex justify-between items-center border-b border-dashed border-gray-200 pb-3">
                        <div>
                            <p class="text-2xl font-bold text-gray-800">14:25</p>
                            <p class="text-xs text-gray-500">台灣桃園機場 (TPE)</p>
                        </div>
                        <div class="text-center text-peach-400">
                            <i class="fa-solid fa-plane text-lg rotate-90"></i>
                            <p class="text-[10px] text-gray-400 mt-1">約 2h 25m</p>
                        </div>
                        <div class="text-right">
                            <p class="text-2xl font-bold text-gray-800">17:50</p>
                            <p class="text-xs text-gray-500">福岡機場 (FUK)</p>
                        </div>
                    </div>
                    <div class="flex justify-between items-center text-xs bg-peach-50 p-2.5 rounded-xl">
                        <div><span class="text-gray-500">座位：</span><strong class="text-peach-700">23F, 24F</strong></div>
                        <div><span class="text-gray-500">航廈：</span><strong class="text-gray-700">第一航廈起飛 / 國際線抵達</strong></div>
                    </div>
                    <details class="group">
                        <summary class="text-xs text-peach-600 font-medium cursor-pointer list-none flex items-center justify-between pt-1">
                            <span>💡 去程安檢與入境注意事項</span>
                            <i class="fa-solid fa-chevron-down transition-transform group-open:rotate-180"></i>
                        </summary>
                        <div class="text-xs text-gray-600 space-y-1.5 mt-2 pt-2 border-t border-gray-100 bg-gray-50 p-2.5 rounded-xl">
                            <p>• 建議起飛前 2.5 小時抵達桃園機場辦理報到。</p>
                            <p>• 隨身行李禁止攜帶超過 100ml 液體、高壓噴霧等。</p>
                            <p>• 抵達福岡機場後跟隨指引搭乘免費接駁車至國內線地鐵站轉乘或搭計程車。</p>
                        </div>
                    </details>
                </div>
            </div>

            <!-- Return Ticket -->
            <div class="bg-white rounded-2xl shadow-md overflow-hidden border border-peach-100">
                <div class="bg-stone-700 text-white px-4 py-2.5 flex justify-between items-center text-sm font-bold">
                    <span class="flex items-center gap-2"><i class="fa-solid fa-plane-arrival"></i> 回程航班 (IT241)</span>
                    <span class="bg-white/20 text-xs px-2.5 py-1 rounded-full">10/21 (二)</span>
                </div>
                <div class="p-4 space-y-3">
                    <div class="flex justify-between items-center border-b border-dashed border-gray-200 pb-3">
                        <div>
                            <p class="text-2xl font-bold text-gray-800">10:25</p>
                            <p class="text-xs text-gray-500">福岡機場 (FUK)</p>
                        </div>
                        <div class="text-center text-stone-400">
                            <i class="fa-solid fa-plane text-lg -rotate-90"></i>
                            <p class="text-[10px] text-gray-400 mt-1">約 1h 30m</p>
                        </div>
                        <div class="text-right">
                            <p class="text-2xl font-bold text-gray-800">11:55</p>
                            <p class="text-xs text-gray-500">台灣桃園機場 (TPE)</p>
                        </div>
                    </div>
                    <div class="flex justify-between items-center text-xs bg-stone-50 p-2.5 rounded-xl">
                        <div><span class="text-gray-500">起飛航廈：</span><strong class="text-stone-700">國際線航廈</strong></div>
                        <div><span class="text-gray-500">建議抵達：</span><strong class="text-stone-700">08:15 前到機場</strong></div>
                    </div>
                    <details class="group">
                        <summary class="text-xs text-stone-600 font-medium cursor-pointer list-none flex items-center justify-between pt-1">
                            <span>💡 回程與免稅店注意事項</span>
                            <i class="fa-solid fa-chevron-down transition-transform group-open:rotate-180"></i>
                        </summary>
                        <div class="text-xs text-gray-600 space-y-1.5 mt-2 pt-2 border-t border-gray-100 bg-gray-50 p-2.5 rounded-xl">
                            <p>• 當天早上建議 08:15 從飯店搭計程車出發，約 15 分鐘直達國際線。</p>
                            <p>• 福岡機場國際線免稅店不大，若要買伴手禮建議提早排隊或在博多車站先買好。</p>
                            <p>• 行李重量請務必提前確認，避免超重。</p>
                        </div>
                    </details>
                </div>
            </div>
        </div>

        <!-- ================= TAB 2: 每日行程 (Daily Itinerary) ================= -->
        <div id="tab-itinerary" class="tab-content hidden space-y-4">
            
            <!-- Day Selector Bar (Moved to Top) -->
            <div class="flex overflow-x-auto gap-2 pb-2 hide-scrollbar sticky top-0 bg-cream z-20 pt-1 shadow-sm">
                <button onclick="switchDay(1)" class="day-btn px-4 py-2 rounded-xl text-xs font-bold whitespace-nowrap bg-peach-500 text-white shadow-sm transition" data-day="1">Day 1 抵達</button>
                <button onclick="switchDay(2)" class="day-btn px-4 py-2 rounded-xl text-xs font-bold whitespace-nowrap bg-white text-gray-600 border border-peach-200 hover:bg-peach-50 transition" data-day="2">Day 2 藥院燒肉</button>
                <button onclick="switchDay(3)" class="day-btn px-4 py-2 rounded-xl text-xs font-bold whitespace-nowrap bg-white text-gray-600 border border-peach-200 hover:bg-peach-50 transition" data-day="3">Day 3 熊野一日遊</button>
                <button onclick="switchDay(4)" class="day-btn px-4 py-2 rounded-xl text-xs font-bold whitespace-nowrap bg-white text-gray-600 border border-peach-200 hover:bg-peach-50 transition" data-day="4">Day 4 天神採買</button>
                <button onclick="switchDay(5)" class="day-btn px-4 py-2 rounded-xl text-xs font-bold whitespace-nowrap bg-white text-gray-600 border border-peach-200 hover:bg-peach-50 transition" data-day="5">Day 5 由布院一日遊</button>
                <button onclick="switchDay(6)" class="day-btn px-4 py-2 rounded-xl text-xs font-bold whitespace-nowrap bg-white text-gray-600 border border-peach-200 hover:bg-peach-50 transition" data-day="6">Day 6 買麵包/天神</button>
                <button onclick="switchDay(7)" class="day-btn px-4 py-2 rounded-xl text-xs font-bold whitespace-nowrap bg-white text-gray-600 border border-peach-200 hover:bg-peach-50 transition" data-day="7">Day 7 賦歸</button>
            </div>

            <!-- Day Panels -->
            <div id="day-panels" class="space-y-4 pt-1">
                
                <!-- DAY 1 -->
                <div class="day-panel space-y-3" data-day-content="1">
                    <div class="bg-peach-100 text-peach-800 p-3 rounded-xl text-xs font-bold flex items-center justify-between">
                        <span>📅 10/15 (三) 第一天：飛向福岡・入住休息</span>
                        <span class="text-peach-600">預估車資: ¥260~1,260</span>
                    </div>

                    <!-- Hotel Voucher Upload & Preview Box (Explicitly in Day 1) -->
                    <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-200 space-y-3">
                        <div class="flex items-center justify-between">
                            <h3 class="text-xs font-bold text-gray-800 flex items-center gap-1.5">
                                <i class="fa-solid fa-hotel text-peach-500"></i> 飯店入住憑證 (Hotel Voucher)
                            </h3>
                            <span class="text-[10px] bg-peach-50 text-peach-700 px-2 py-0.5 rounded-full font-medium">入住必備</span>
                        </div>
                        
                        <div id="voucher-dropzone" ondragover="handleDragOver(event)" ondragleave="handleDragLeave(event)" ondrop="handleDrop(event)" class="border-2 border-dashed border-peach-200 hover:border-peach-400 bg-peach-50/40 rounded-xl p-4 text-center transition cursor-pointer relative">
                            <input type="file" id="hotel-voucher-input" onchange="handleFileSelect(event)" class="hidden" accept="image/png, image/jpeg, application/pdf">
                            <label for="hotel-voucher-input" class="cursor-pointer space-y-1 block">
                                <i class="fa-solid fa-cloud-arrow-up text-2xl text-peach-400"></i>
                                <p class="text-xs font-bold text-gray-700">點擊上傳或拖曳憑證至此</p>
                                <p class="text-[10px] text-gray-400">支援 PNG, JPG, PDF 檔案 (建議 5MB 以內)</p>
                            </label>
                        </div>

                        <div id="voucher-preview-container" class="hidden border border-gray-100 bg-gray-50 p-3 rounded-xl space-y-2">
                            <div class="flex justify-between items-center">
                                <span class="text-[11px] font-bold text-gray-700 flex items-center gap-1">
                                    <i class="fa-solid fa-paperclip text-peach-500"></i> 已上傳憑證預覽
                                </span>
                                <button onclick="removeVoucher()" class="text-[10px] text-red-500 hover:underline flex items-center gap-0.5">
                                    <i class="fa-solid fa-trash-can"></i> 移除/重新上傳
                                </button>
                            </div>
                            <div id="voucher-img-preview" class="hidden">
                                <img id="voucher-img-element" onclick="openFullImage()" src="" alt="Hotel Voucher" class="w-full max-h-48 object-cover rounded-lg shadow-sm cursor-zoom-in border border-gray-200">
                                <p class="text-[9px] text-gray-400 text-center mt-1">點擊圖片可放大查看大圖</p>
                            </div>
                            <div id="voucher-pdf-preview" class="hidden bg-white p-3 rounded-lg border border-gray-200 flex items-center justify-between">
                                <div class="flex items-center gap-2 overflow-hidden">
                                    <i class="fa-solid fa-file-pdf text-red-500 text-xl shrink-0"></i>
                                    <span id="voucher-filename-display" class="text-xs font-medium text-gray-700 truncate"></span>
                                </div>
                                <a id="voucher-pdf-link" href="#" target="_blank" class="bg-peach-500 text-white text-[11px] px-3 py-1 rounded-lg font-medium shrink-0 hover:bg-peach-600 transition">
                                    開啟 PDF
                                </a>
                            </div>
                        </div>

                        <div class="space-y-1.5 pt-1">
                            <label class="text-[10px] font-bold text-gray-500">訂房備註 (預約號/Password/房型等):</label>
                            <textarea id="hotel-voucher-notes" placeholder="在此輸入訂房序號、Check-in 注意事項、房型資訊..." class="w-full text-xs p-2.5 rounded-xl border border-gray-200 focus:outline-none focus:border-peach-500 bg-gray-50 h-16 resize-none" oninput="saveVoucherNotes()"></textarea>
                        </div>
                    </div>

                    <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                        <div class="flex items-start gap-3">
                            <span class="bg-peach-500 text-white text-xs font-bold px-2 py-1 rounded-lg">14:25</span>
                            <div>
                                <h3 class="text-sm font-bold text-gray-800">桃園機場起飛 (IT720)</h3>
                                <p class="text-xs text-gray-500">座位 23F, 24F，展開難忘的福岡假期！</p>
                            </div>
                        </div>
                        <div class="border-l-2 border-peach-200 ml-4 pl-4 space-y-3">
                            <div>
                                <span class="text-xs font-bold text-peach-600">17:50 降落福岡機場</span>
                                <p class="text-xs text-gray-600 mt-0.5">完成入境審查與領取行李。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">18:30 - 19:15 前往飯店</span>
                                <p class="text-xs text-gray-600 mt-0.5">搭乘國內線接駁車轉地下鐵機場線至「博多站」 (¥260/人) 或搭計程車直達飯店 (~¥1,000)。</p>
                                <div class="flex gap-2 mt-2">
                                    <a href="https://maps.app.goo.gl/DvRteta1W1AVgtqT8" target="_blank" class="bg-peach-50 text-peach-700 px-3 py-1.5 rounded-lg text-xs font-medium hover:bg-peach-100 transition flex items-center gap-1">
                                        <i class="fa-solid fa-map-location-dot"></i> SG 博多旅居飯店導航
                                    </a>
                                </div>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">19:30 入住與晚餐</span>
                                <p class="text-xs text-gray-600 mt-0.5">於飯店附近超商或博多站周邊輕鬆享用晚餐，儲存體力準備隔天行程。</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- DAY 2 -->
                <div class="day-panel hidden space-y-3" data-day-content="2">
                    <div class="bg-peach-100 text-peach-800 p-3 rounded-xl text-xs font-bold flex items-center justify-between">
                        <span>📅 10/16 (四) 第二天：藥院散策 & 美味燒肉</span>
                        <span class="text-peach-600">預估車資: ¥630~800</span>
                    </div>

                    <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                        <div class="text-xs bg-gray-50 p-2.5 rounded-xl text-gray-600">
                            🚶‍♂️ <strong>今日交通：</strong>10:00 從旅館出發，步行約 8-10 分鐘至博多站或搭地鐵前往藥院。
                        </div>

                        <div class="flex items-start gap-3">
                            <span class="bg-peach-500 text-white text-xs font-bold px-2 py-1 rounded-lg">10:00</span>
                            <div>
                                <h3 class="text-sm font-bold text-gray-800">旅館出發</h3>
                                <p class="text-xs text-gray-500">悠閒早晨，準備前往藥院商圈。</p>
                            </div>
                        </div>
                        <div class="border-l-2 border-peach-200 ml-4 pl-4 space-y-3">
                            <div>
                                <span class="text-xs font-bold text-peach-600">11:00 葉隱烏龍麵午餐</span>
                                <p class="text-xs text-gray-600 mt-0.5">品嚐福岡超高人氣的手打Q彈烏龍麵！</p>
                                <div class="flex gap-2 mt-2">
                                    <a href="https://maps.app.goo.gl/tHJ5sGRQmrtPerTL8" target="_blank" class="bg-peach-50 text-peach-700 px-3 py-1.5 rounded-lg text-xs font-medium hover:bg-peach-100 transition flex items-center gap-1">
                                        <i class="fa-solid fa-utensils"></i> 葉隱烏龍麵導航
                                    </a>
                                </div>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">12:15 - 17:30 藥院質感散策</span>
                                <p class="text-xs text-gray-600 mt-0.5">藥院一帶充滿精緻雜貨店、咖啡廳與選品店，慢步調享受午後時光。</p>
                                <div class="flex gap-2 mt-2">
                                    <a href="https://maps.app.goo.gl/rioR8kGCdeHo7Y6L7" target="_blank" class="bg-gray-100 text-gray-700 px-3 py-1.5 rounded-lg text-xs font-medium hover:bg-gray-200 transition flex items-center gap-1">
                                        <i class="fa-solid fa-store"></i> 藥院商圈景點地圖
                                    </a>
                                </div>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">18:30 晚餐：藥院燒肉 (推薦 18:30 時段)</span>
                                <p class="text-xs text-gray-600 mt-0.5">預約 18:30 吃完約 20:00，周邊地鐵與店家皆有營業，從容返回飯店不趕時間！</p>
                                <p class="text-[11px] text-gray-500 mt-1">地址：福岡県福岡市中央区渡辺通2丁目2-8 デンエンビル 2F</p>
                                <div class="flex gap-2 mt-2">
                                    <a href="https://maps.app.goo.gl/rioR8kGCdeHo7Y6L7" target="_blank" class="bg-peach-50 text-peach-700 px-3 py-1.5 rounded-lg text-xs font-medium hover:bg-peach-100 transition flex items-center gap-1">
                                        <i class="fa-solid fa-fire"></i> 燒肉店導航
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- DAY 3 -->
                <div class="day-panel hidden space-y-3" data-day-content="3">
                    <div class="bg-peach-100 text-peach-800 p-3 rounded-xl text-xs font-bold flex items-center justify-between">
                        <span>📅 10/17 (五) 第三天：熊野座神社 & 阿蘇火山一日遊</span>
                        <span class="text-peach-600">一日遊包車方案</span>
                    </div>

                    <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                        <div class="text-xs bg-amber-50 p-2.5 rounded-xl text-amber-800">
                            🍱 <strong>貼心提醒：</strong>一日遊行程緊湊，建議早上在博多站超商買飯糰或麵包帶著走，以免午餐排隊壓縮景點時間！
                        </div>

                        <div class="flex items-start gap-3">
                            <span class="bg-peach-500 text-white text-xs font-bold px-2 py-1 rounded-lg">07:10</span>
                            <div>
                                <h3 class="text-sm font-bold text-gray-800">由旅館出發步行</h3>
                                <p class="text-xs text-gray-500">步行約 10-12 分鐘至博多車站築紫口。</p>
                                <div class="flex gap-2 mt-2">
                                    <a href="https://share.google/37R9QGXKA67WAtZQiHakata" target="_blank" class="bg-peach-50 text-peach-700 px-3 py-1.5 rounded-lg text-xs font-medium hover:bg-peach-100 transition flex items-center gap-1">
                                        <i class="fa-solid fa-location-arrow"></i> 博多站築紫口集合點導航
                                    </a>
                                </div>
                            </div>
                        </div>

                        <div class="border-l-2 border-peach-200 ml-4 pl-4 space-y-3">
                            <div>
                                <span class="text-xs font-bold text-peach-600">07:40 羅森 博多車站築紫口集合出發</span>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">10:00 上色見熊野座神社 (自由活動 1.5小時)</span>
                                <p class="text-xs text-gray-600 mt-0.5">神祕且充滿綠意苔蘚的神社參道，宛如走入精靈系動漫場景。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">12:00 阿蘇火山 (自由活動 1.5小時)</span>
                                <p class="text-xs text-gray-600 mt-0.5">壯麗的火山地形與中岳火口景觀，現場自理午餐。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">14:30 黑川溫泉 (自由活動 1.5小時)</span>
                                <p class="text-xs text-gray-600 mt-0.5">散策古風溫泉街，品嚐在地名物布丁或享受足湯。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">18:00 返回博多解散</span>
                                <p class="text-xs text-gray-600 mt-0.5">抵達羅森 福岡東方飯店解散，步行回飯店休息晚餐。</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- DAY 4 -->
                <div class="day-panel hidden space-y-3" data-day-content="4">
                    <div class="bg-peach-100 text-peach-800 p-3 rounded-xl text-xs font-bold flex items-center justify-between">
                        <span>📅 10/18 (六) 第四天：天神商圈大肆採買日</span>
                        <span class="text-peach-600">預估車資: ¥420</span>
                    </div>

                    <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                        <div class="text-xs bg-gray-50 p-2.5 rounded-xl text-gray-600">
                            🚇 <strong>今日交通：</strong>10:00 從旅館出發步行至博多站，搭乘地下鐵至「天神站」 (~¥210)。
                        </div>

                        <div class="flex items-start gap-3">
                            <span class="bg-peach-500 text-white text-xs font-bold px-2 py-1 rounded-lg">10:00</span>
                            <div>
                                <h3 class="text-sm font-bold text-gray-800">旅館出發</h3>
                            </div>
                        </div>
                        <div class="border-l-2 border-peach-200 ml-4 pl-4 space-y-3">
                            <div>
                                <span class="text-xs font-bold text-peach-600">10:30 - 12:30 天神地下街 & 百貨採買</span>
                                <p class="text-xs text-gray-600 mt-0.5">大丸、三越、PARCO、天神地下街盡情購物。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">12:30 - 13:30 午餐時間</span>
                                <p class="text-xs text-gray-600 mt-0.5">天神商圈自由覓食美味午餐。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">13:30 - 18:00 藥妝與選品雜貨掃貨</span>
                                <p class="text-xs text-gray-600 mt-0.5">持續在天神與中洲川端一帶逛街血拚。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">18:30 晚餐與返回</span>
                                <p class="text-xs text-gray-600 mt-0.5">於天神或博多站享用晚餐後搭地鐵返回飯店整理戰利品。</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- DAY 5 -->
                <div class="day-panel hidden space-y-3" data-day-content="5">
                    <div class="bg-peach-100 text-peach-800 p-3 rounded-xl text-xs font-bold flex items-center justify-between">
                        <span>📅 10/19 (日) 第五天：由布院 & 野生動物園一日遊</span>
                        <span class="text-peach-600">一日遊包車方案</span>
                    </div>

                    <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                        <div class="text-xs bg-amber-50 p-2.5 rounded-xl text-amber-800">
                            🍱 <strong>貼心提醒：</strong>今日行程包含動物園與由布院，建議早餐備妥輕食帶著走！
                        </div>

                        <div class="flex items-start gap-3">
                            <span class="bg-peach-500 text-white text-xs font-bold px-2 py-1 rounded-lg">07:30</span>
                            <div>
                                <h3 class="text-sm font-bold text-gray-800">由旅館出發步行</h3>
                                <p class="text-xs text-gray-500">步行至博多車站築紫口集合點。</p>
                            </div>
                        </div>

                        <div class="border-l-2 border-peach-200 ml-4 pl-4 space-y-3">
                            <div>
                                <span class="text-xs font-bold text-peach-600">08:00 博多站築紫口出發</span>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">10:00 海地獄溫泉 (自由活動 30分鐘)</span>
                                <p class="text-xs text-gray-600 mt-0.5">欣賞夢幻湛藍的別府地獄溫泉奇景與特色蒸氣。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">12:00 Kyushu Wildlife Park African Safari (2小時)</span>
                                <p class="text-xs text-gray-600 mt-0.5">搭乘叢林巴士近距離餵食猛獸，園區內自理午餐。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">14:30 湯布院町/金鱗湖 (2小時)</span>
                                <p class="text-xs text-gray-600 mt-0.5">漫步童話小鎮湯之坪街道、欣賞湖面氤氳的金鱗湖美景。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">18:00 返回博多解散</span>
                                <p class="text-xs text-gray-600 mt-0.5">抵達羅森 福岡東方飯店解散，返回飯店晚餐。</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- DAY 6 -->
                <div class="day-panel hidden space-y-3" data-day-content="6">
                    <div class="bg-peach-100 text-peach-800 p-3 rounded-xl text-xs font-bold flex items-center justify-between">
                        <span>📅 10/20 (一) 第六天：法國麵包掃貨日 & 博多採買</span>
                        <span class="text-peach-600">預估車資: ¥210~420</span>
                    </div>

                    <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                        <div class="text-xs bg-gray-50 p-2.5 rounded-xl text-gray-600">
                            🚇 <strong>今日交通：</strong>10:00 從旅館出發，步行或搭地鐵至祇園/中洲一帶。
                        </div>

                        <div class="flex items-start gap-3">
                            <span class="bg-peach-500 text-white text-xs font-bold px-2 py-1 rounded-lg">10:00</span>
                            <div>
                                <h3 class="text-sm font-bold text-gray-800">旅館出發</h3>
                            </div>
                        </div>
                        <div class="border-l-2 border-peach-200 ml-4 pl-4 space-y-3">
                            <div>
                                <span class="text-xs font-bold text-peach-600">10:30 購買人氣法國麵包！</span>
                                <p class="text-xs text-gray-600 mt-0.5">前往您指定必買的超人氣法國麵包店採購，可留作隔天早餐或帶回台灣享用。</p>
                                <div class="flex gap-2 mt-2">
                                    <a href="https://maps.app.goo.gl/GWj35DhyeneQNgKy9" target="_blank" class="bg-peach-50 text-peach-700 px-3 py-1.5 rounded-lg text-xs font-medium hover:bg-peach-100 transition flex items-center gap-1">
                                        <i class="fa-solid fa-bread-slice"></i> The Full Full Hakata 導航
                                    </a>
                                </div>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">12:30 - 13:30 午餐時間</span>
                                <p class="text-xs text-gray-600 mt-0.5">博多車站周邊自由覓食。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">14:00 - 18:00 最後衝刺採買與打包</span>
                                <p class="text-xs text-gray-600 mt-0.5">AMU Plaza、博多阪急、Yodobashi Camera 伴手禮最後補貨與行李整理。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">18:30 晚餐與休息</span>
                                <p class="text-xs text-gray-600 mt-0.5">享用美味晚餐後回飯店打包行李。</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- DAY 7 -->
                <div class="day-panel hidden space-y-3" data-day-content="7">
                    <div class="bg-peach-100 text-peach-800 p-3 rounded-xl text-xs font-bold flex items-center justify-between">
                        <span>📅 10/21 (二) 第七天：福岡賦歸・平安返台</span>
                        <span class="text-peach-600">計程車資: 約 ¥1,500</span>
                    </div>

                    <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                        <div class="bg-amber-50 border border-amber-200 p-3 rounded-xl text-xs space-y-2">
                            <p class="font-bold text-amber-900 flex items-center gap-1"><i class="fa-solid fa-taxi"></i> 最後一天計程車攻略：</p>
                            <p class="text-amber-800">• <strong>叫車方法：</strong>請飯店櫃檯協助叫車，或使用 Go Taxi App，亦可於飯店門口攔車。</p>
                            <p class="text-amber-800">• <strong>向司機說的話：</strong>直接出示或唸出以下日文即可精準抵達：</p>
                            <div class="bg-white p-2 rounded-lg border border-amber-300 font-bold text-center text-amber-900 text-sm">
                                「福岡空港国際線までお願いします」<br>
                                <span class="text-[10px] font-normal text-gray-500">(Fukuoka Kūkō Kokusaisen made onegaishimasu)</span>
                            </div>
                        </div>

                        <div class="flex items-start gap-3">
                            <span class="bg-peach-500 text-white text-xs font-bold px-2 py-1 rounded-lg">07:30</span>
                            <div>
                                <h3 class="text-sm font-bold text-gray-800">起床與最後檢查</h3>
                                <p class="text-xs text-gray-500">檢查護照、隨身行李與戰利品是否齊全。</p>
                            </div>
                        </div>
                        <div class="border-l-2 border-peach-200 ml-4 pl-4 space-y-3">
                            <div>
                                <span class="text-xs font-bold text-peach-600">08:15 飯店搭計程車出發</span>
                                <p class="text-xs text-gray-600 mt-0.5">從 SG 博多旅居飯店出發直達福岡機場國際線航廈（約 15 分鐘）。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">08:40 抵達福岡機場國際線</span>
                                <p class="text-xs text-gray-600 mt-0.5">辦理登機手續、過安檢、免稅店最後血拚。</p>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-peach-600">10:25 搭機返回台灣 (IT241)</span>
                                <p class="text-xs text-gray-600 mt-0.5">11:55 平安降落桃園國際機場，結束美好福岡之旅！</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>

        <!-- ================= TAB 3: 交通 + 住宿 (Transport & Accommodation) ================= -->
        <div id="tab-transport" class="tab-content hidden space-y-4">
            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                <div class="flex justify-between items-start">
                    <div>
                        <span class="bg-peach-100 text-peach-700 text-[10px] font-bold px-2 py-0.5 rounded-full">主住宿地點</span>
                        <h3 class="text-base font-bold text-gray-800 mt-1">SG 博多旅居飯店</h3>
                        <p class="text-xs text-gray-500 mt-0.5">SG RESIDENCE INN HAKATA</p>
                    </div>
                    <i class="fa-solid fa-hotel text-2xl text-peach-400"></i>
                </div>
                <p class="text-xs text-gray-600">📍 2 Chome-17-20 Toko, Hakata Ward, Fukuoka, 812-0008 日本</p>
                <div class="flex gap-2 pt-1">
                    <a href="https://maps.app.goo.gl/DvRteta1W1AVgtqT8" target="_blank" class="bg-peach-500 text-white px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-600 transition flex items-center gap-1.5 shadow-sm">
                        <i class="fa-solid fa-map-location-dot"></i> Google 地圖導航
                    </a>
                </div>
            </div>

            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                <h3 class="text-sm font-bold text-gray-800 flex items-center gap-2">
                    <span>🏪</span> 旅館周遭便利商店 (深夜補給站)
                </h3>
                <div class="grid grid-cols-1 gap-2 pt-1">
                    <div class="flex items-center justify-between bg-gray-50 p-2.5 rounded-xl">
                        <div class="flex items-center gap-2.5">
                            <span class="w-2.5 h-2.5 rounded-full bg-blue-500"></span>
                            <span class="text-xs font-bold text-gray-700">FamilyMart 全家便利商店</span>
                        </div>
                        <a href="https://maps.app.goo.gl/EcpgBrgqNZdakuzV9" target="_blank" class="bg-white border border-gray-200 text-peach-600 px-2.5 py-1 rounded-lg text-xs font-medium hover:bg-peach-50 transition">
                            導航 <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                    <div class="flex items-center justify-between bg-gray-50 p-2.5 rounded-xl">
                        <div class="flex items-center gap-2.5">
                            <span class="w-2.5 h-2.5 rounded-full bg-orange-500"></span>
                            <span class="text-xs font-bold text-gray-700">7-Eleven 超商</span>
                        </div>
                        <a href="https://maps.app.goo.gl/rPp8e7AP2BiUntS29" target="_blank" class="bg-white border border-gray-200 text-peach-600 px-2.5 py-1 rounded-lg text-xs font-medium hover:bg-peach-50 transition">
                            導航 <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                    <div class="flex items-center justify-between bg-gray-50 p-2.5 rounded-xl">
                        <div class="flex items-center gap-2.5">
                            <span class="w-2.5 h-2.5 rounded-full bg-blue-400"></span>
                            <span class="text-xs font-bold text-gray-700">LAWSON 羅森超商</span>
                        </div>
                        <a href="https://maps.app.goo.gl/DhuQ1pAgRc3QnbkB9" target="_blank" class="bg-white border border-gray-200 text-peach-600 px-2.5 py-1 rounded-lg text-xs font-medium hover:bg-peach-50 transition">
                            導航 <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>
            </div>

            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                <div class="flex justify-between items-center">
                    <div>
                        <span class="text-[10px] font-bold text-peach-600 bg-peach-50 px-2 py-0.5 rounded-full">重要集合點</span>
                        <h3 class="text-sm font-bold text-gray-800 mt-1">博多車站築紫口 (Chikushi Exit)</h3>
                    </div>
                    <i class="fa-solid fa-train text-xl text-peach-400"></i>
                </div>
                <p class="text-xs text-gray-600">一日遊集合與乘車主要地標，距離旅館步行約 10-12 分鐘。</p>
                <div class="flex gap-2 pt-1">
                    <a href="https://share.google/37R9QGXKA67WAtZQiHakata" target="_blank" class="bg-peach-50 text-peach-700 px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-100 transition flex items-center gap-1.5">
                        <i class="fa-solid fa-map-location-dot"></i> 博多站築紫口地圖導航
                    </a>
                </div>
            </div>

            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-2">
                <h3 class="text-sm font-bold text-gray-800 flex items-center gap-2">
                    <span>💴</span> 每日交通與車資預估速查
                </h3>
                <ul class="text-xs text-gray-600 space-y-1.5 pt-1">
                    <li>• <strong>Day 1：</strong> 機場至博多/飯店 (地鐵 ¥260 或計程車 ~¥1,000)</li>
                    <li>• <strong>Day 2：</strong> 市區地鐵/巴士移動 (~¥630 - ¥800)</li>
                    <li>• <strong>Day 3：</strong> 熊野火山一日遊 (套裝行程已含車資)</li>
                    <li>• <strong>Day 4：</strong> 天神商圈地鐵來回 (~¥420)</li>
                    <li>• <strong>Day 5：</strong> 由布院一日遊 (套裝行程已含車資)</li>
                    <li>• <strong>Day 6：</strong> 買麵包與市區移動 (~¥210 - ¥420)</li>
                    <li>• <strong>Day 7：</strong> 飯店至機場計程車 (~¥1,500)</li>
                </ul>
            </div>
        </div>

        <!-- ================= TAB 4: 行李清單 (Packing List) ================= -->
        <div id="tab-packing" class="tab-content hidden space-y-4">
            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-4">
                <div class="flex justify-between items-center">
                    <div>
                        <span class="bg-peach-100 text-peach-700 text-[10px] font-bold px-2 py-0.5 rounded-full">七天六夜極致詳細清單</span>
                        <h3 class="text-sm font-bold text-gray-800 mt-1">🧳 超詳細出國行李與準備清單</h3>
                    </div>
                    <button onclick="resetPacking()" class="text-[11px] text-gray-400 hover:text-peach-600 transition">重置勾選</button>
                </div>
                <p class="text-xs text-gray-500">點擊方框勾選已完成項目，分類打包安心出發！</p>

                <div id="packing-list-container" class="space-y-4 pt-1">
                    <!-- Dynamic detailed packing list generated by JS -->
                </div>
            </div>
        </div>

        <!-- ================= TAB 5: 帳務 (Expense Splitter & Personal Expenses) ================= -->
        <div id="tab-expense" class="tab-content hidden space-y-4">
            
            <!-- Shared Expense Splitter Card -->
            <div class="bg-gradient-to-br from-peach-500 to-peach-600 text-white p-4 rounded-2xl shadow-md space-y-3">
                <h3 class="text-sm font-bold flex items-center gap-2">
                    <span>💰</span> 旅遊共用分帳 (Lucy & Rigo 平分)
                </h3>
                <div class="grid grid-cols-2 gap-3 pt-1">
                    <div class="bg-white/10 backdrop-blur-sm p-3 rounded-xl">
                        <p class="text-[10px] text-peach-100">共用總支出</p>
                        <p class="text-lg font-bold mt-0.5" id="total-shared-amount">¥0</p>
                    </div>
                    <div class="bg-white/10 backdrop-blur-sm p-3 rounded-xl">
                        <p class="text-[10px] text-peach-100">分帳結算結果</p>
                        <p class="text-xs font-bold mt-1" id="settlement-summary-text">尚無分帳記錄</p>
                    </div>
                </div>
            </div>

            <!-- Add Shared Expense Form -->
            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                <h4 class="text-xs font-bold text-gray-800">➕ 記錄共用消費 (誰先出 / 平分)</h4>
                <form id="shared-expense-form" onsubmit="addSharedExpense(event)" class="space-y-2.5">
                    <div>
                        <label class="text-[10px] text-gray-500">消費項目名稱</label>
                        <input type="text" id="shared-title" required placeholder="例如：計程車費 / 燒肉晚餐" class="w-full text-xs p-2.5 rounded-xl border border-gray-200 focus:outline-none focus:border-peach-500 bg-gray-50">
                    </div>
                    <div class="grid grid-cols-2 gap-2">
                        <div>
                            <label class="text-[10px] text-gray-500">金額 (日幣 ¥)</label>
                            <input type="number" id="shared-amount" required placeholder="5000" class="w-full text-xs p-2.5 rounded-xl border border-gray-200 focus:outline-none focus:border-peach-500 bg-gray-50">
                        </div>
                        <div>
                            <label class="text-[10px] text-gray-500">誰先代付的？</label>
                            <select id="shared-payer" class="w-full text-xs p-2.5 rounded-xl border border-gray-200 focus:outline-none focus:border-peach-500 bg-gray-50">
                                <option value="Lucy">Lucy 先出</option>
                                <option value="Rigo">Rigo 先出</option>
                            </select>
                        </div>
                    </div>
                    <button type="submit" class="w-full bg-peach-500 hover:bg-peach-600 text-white py-2.5 rounded-xl text-xs font-bold transition shadow-sm">
                        新增共用帳務
                    </button>
                </form>
            </div>

            <!-- Shared Expense List -->
            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                <div class="flex justify-between items-center">
                    <h4 class="text-xs font-bold text-gray-800">📋 共用消費明細</h4>
                    <button onclick="clearSharedExpenses()" class="text-[11px] text-red-500 hover:underline">清空全部</button>
                </div>
                <div id="shared-expense-list" class="space-y-2 max-h-48 overflow-y-auto">
                    <!-- Populated dynamically -->
                </div>
            </div>

            <!-- Personal Expense Recorder Card -->
            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3 pt-2">
                <div class="flex justify-between items-center border-t border-gray-100 pt-3">
                    <h4 class="text-xs font-bold text-gray-800">🛍️ 個人專屬記帳 (自己花了多少)</h4>
                    <span class="text-xs font-bold text-peach-600" id="personal-total-amount">個人總計: ¥0</span>
                </div>
                
                <form id="personal-expense-form" onsubmit="addPersonalExpense(event)" class="space-y-2.5">
                    <div class="grid grid-cols-2 gap-2">
                        <div>
                            <label class="text-[10px] text-gray-500">記在誰的名下</label>
                            <select id="pers-owner" class="w-full text-xs p-2.5 rounded-xl border border-gray-200 focus:outline-none focus:border-peach-500 bg-gray-50">
                                <option value="Lucy">Lucy 的個人花費</option>
                                <option value="Rigo">Rigo 的個人花費</option>
                            </select>
                        </div>
                        <div>
                            <label class="text-[10px] text-gray-500">金額 (日幣 ¥)</label>
                            <input type="number" id="pers-amount" required placeholder="2000" class="w-full text-xs p-2.5 rounded-xl border border-gray-200 focus:outline-none focus:border-peach-500 bg-gray-50">
                        </div>
                    </div>
                    <div>
                        <label class="text-[10px] text-gray-500">個人消費項目/戰利品</label>
                        <input type="text" id="pers-title" required placeholder="例如：藥妝 / 衣服 / 伴手禮" class="w-full text-xs p-2.5 rounded-xl border border-gray-200 focus:outline-none focus:border-peach-500 bg-gray-50">
                    </div>
                    <button type="submit" class="w-full bg-stone-700 hover:bg-stone-800 text-white py-2.5 rounded-xl text-xs font-bold transition shadow-sm">
                        記一筆個人花費
                    </button>
                </form>

                <div id="personal-expense-list" class="space-y-2 max-h-48 overflow-y-auto pt-2">
                    <!-- Populated dynamically -->
                </div>
            </div>

        </div>

        <!-- ================= TAB 6: 許願池 (Wishlist) ================= -->
        <div id="tab-wishlist" class="tab-content hidden space-y-4">
            <div class="bg-white p-4 rounded-2xl shadow-sm border border-peach-100 space-y-3">
                <div class="flex justify-between items-center">
                    <div>
                        <span class="bg-peach-100 text-peach-700 text-[10px] font-bold px-2 py-0.5 rounded-full">自訂地圖標記</span>
                        <h3 class="text-sm font-bold text-gray-800 mt-1">✨ 福岡許願池與景點清單</h3>
                    </div>
                    <a href="https://maps.app.goo.gl/ZFNKmKVrjR6SjeeX7" target="_blank" class="bg-peach-50 text-peach-700 px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-100 transition flex items-center gap-1">
                        <i class="fa-solid fa-map"></i> 原始地圖
                    </a>
                </div>
                <p class="text-xs text-gray-500">將您在地圖上標記想去的店鋪與景點匯整於此，點擊按鈕即可一鍵導航！</p>

                <div class="space-y-2 pt-2" id="wishlist-container">
                    <div class="bg-gray-50 p-3 rounded-xl flex items-center justify-between">
                        <div>
                            <h4 class="text-xs font-bold text-gray-800">葉隱烏龍麵</h4>
                            <p class="text-[10px] text-gray-500">超Q彈手打烏龍麵（第二天順路午餐）</p>
                        </div>
                        <a href="https://maps.app.goo.gl/tHJ5sGRQmrtPerTL8" target="_blank" class="bg-peach-500 text-white px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-600 transition shadow-sm">
                            導航
                        </a>
                    </div>
                    <div class="bg-gray-50 p-3 rounded-xl flex items-center justify-between">
                        <div>
                            <h4 class="text-xs font-bold text-gray-800">The Full Full Hakata 法國麵包</h4>
                            <p class="text-[10px] text-gray-500">第六天必買法國麵包帶回台灣</p>
                        </div>
                        <a href="https://maps.app.goo.gl/GWj35DhyeneQNgKy9" target="_blank" class="bg-peach-500 text-white px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-600 transition shadow-sm">
                            導航
                        </a>
                    </div>
                    <div class="bg-gray-50 p-3 rounded-xl flex items-center justify-between">
                        <div>
                            <h4 class="text-xs font-bold text-gray-800">燒肉上 (藥院)</h4>
                            <p class="text-[10px] text-gray-500">第二天晚餐預約燒肉</p>
                        </div>
                        <a href="https://maps.app.goo.gl/rioR8kGCdeHo7Y6L7" target="_blank" class="bg-peach-500 text-white px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-600 transition shadow-sm">
                            導航
                        </a>
                    </div>
                    <div class="bg-gray-50 p-3 rounded-xl flex items-center justify-between">
                        <div>
                            <h4 class="text-xs font-bold text-gray-800">SG 博多旅居飯店</h4>
                            <p class="text-[10px] text-gray-500">七天六夜溫馨住宿點</p>
                        </div>
                        <a href="https://maps.app.goo.gl/DvRteta1W1AVgtqT8" target="_blank" class="bg-peach-500 text-white px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-600 transition shadow-sm">
                            導航
                        </a>
                    </div>
                    <div class="bg-gray-50 p-3 rounded-xl flex items-center justify-between">
                        <div>
                            <h4 class="text-xs font-bold text-gray-800">博多車站築紫口</h4>
                            <p class="text-[10px] text-gray-500">一日遊集合地點</p>
                        </div>
                        <a href="https://share.google/37R9QGXKA67WAtZQiHakata" target="_blank" class="bg-peach-500 text-white px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-600 transition shadow-sm">
                            導航
                        </a>
                    </div>
                </div>
            </div>
        </div>

    </main>

    <!-- Custom Link Editor Modal -->
    <div id="link-modal" class="fixed inset-0 bg-black/50 z-50 hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl p-5 w-full max-w-sm space-y-4 shadow-xl">
            <h3 class="text-sm font-bold text-gray-800 flex items-center gap-2">
                <span>🔗</span> 編輯與自訂地圖連結
            </h3>
            <p class="text-xs text-gray-500">如果您想更改或新增許願池地圖連結，請直接在此輸入：</p>
            <div class="space-y-3">
                <div>
                    <label class="text-[10px] text-gray-500">地標名稱</label>
                    <input type="text" id="custom-place-name" placeholder="例如：某某人氣咖啡廳" class="w-full text-xs p-2.5 rounded-xl border border-gray-200 bg-gray-50">
                </div>
                <div>
                    <label class="text-[10px] text-gray-500">Google Map 連結</label>
                    <input type="text" id="custom-place-url" placeholder="https://maps.app.goo.gl/..." class="w-full text-xs p-2.5 rounded-xl border border-gray-200 bg-gray-50">
                </div>
            </div>
            <div class="flex gap-2 pt-2">
                <button onclick="closeLinkModal()" class="flex-1 bg-gray-100 hover:bg-gray-200 text-gray-700 py-2 rounded-xl text-xs font-medium transition">取消</button>
                <button onclick="saveCustomPlace()" class="flex-1 bg-peach-500 hover:bg-peach-600 text-white py-2 rounded-xl text-xs font-bold transition">新增至許願池</button>
            </div>
        </div>
    </div>

    <!-- Image Modal for Full View -->
    <div id="image-modal" class="fixed inset-0 bg-black/80 z-50 hidden flex items-center justify-center p-4" onclick="closeFullImage()">
        <img id="modal-img-element" src="" class="max-w-full max-h-full rounded-xl shadow-2xl object-contain">
    </div>

    <!-- Bottom Navigation Bar -->
    <nav class="absolute bottom-0 left-0 right-0 bg-white border-t border-peach-100 py-2 px-3 flex justify-around items-center z-30 shadow-lg rounded-t-2xl">
        <button onclick="switchTab('flights')" class="nav-btn flex flex-col items-center gap-1 text-peach-500 transition" data-tab="flights">
            <i class="fa-solid fa-plane text-base"></i>
            <span class="text-[10px] font-medium">航班</span>
        </button>
        <button onclick="switchTab('itinerary')" class="nav-btn flex flex-col items-center gap-1 text-gray-400 hover:text-peach-500 transition" data-tab="itinerary">
            <i class="fa-solid fa-calendar-days text-base"></i>
            <span class="text-[10px] font-medium">行程</span>
        </button>
        <button onclick="switchTab('transport')" class="nav-btn flex flex-col items-center gap-1 text-gray-400 hover:text-peach-500 transition" data-tab="transport">
            <i class="fa-solid fa-hotel text-base"></i>
            <span class="text-[10px] font-medium">住宿+交通</span>
        </button>
        <button onclick="switchTab('packing')" class="nav-btn flex flex-col items-center gap-1 text-gray-400 hover:text-peach-500 transition" data-tab="packing">
            <i class="fa-solid fa-suitcase text-base"></i>
            <span class="text-[10px] font-medium">行李</span>
        </button>
        <button onclick="switchTab('expense')" class="nav-btn flex flex-col items-center gap-1 text-gray-400 hover:text-peach-500 transition" data-tab="expense">
            <i class="fa-solid fa-wallet text-base"></i>
            <span class="text-[10px] font-medium">帳務</span>
        </button>
        <button onclick="switchTab('wishlist')" class="nav-btn flex flex-col items-center gap-1 text-gray-400 hover:text-peach-500 transition" data-tab="wishlist">
            <i class="fa-solid fa-star text-base"></i>
            <span class="text-[10px] font-medium">許願池</span>
        </button>
    </nav>

    <!-- JavaScript Logic -->
    <script>
        // Tab Switching
        function switchTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));
            document.getElementById(`tab-${tabId}`).classList.remove('hidden');

            document.querySelectorAll('.nav-btn').forEach(btn => {
                btn.classList.remove('text-peach-500');
                btn.classList.add('text-gray-400');
            });
            event.currentTarget.classList.remove('text-gray-400');
            event.currentTarget.classList.add('text-peach-500');
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Day Switching
        function switchDay(dayNum) {
            document.querySelectorAll('.day-panel').forEach(panel => {
                panel.classList.add('hidden');
            });
            document.querySelector(`[data-day-content="${dayNum}"]`).classList.remove('hidden');

            document.querySelectorAll('.day-btn').forEach(btn => {
                btn.classList.remove('bg-peach-500', 'text-white', 'shadow-sm');
                btn.classList.add('bg-white', 'text-gray-600', 'border', 'border-peach-200');
            });
            const activeBtn = document.querySelector(`[data-day="${dayNum}"]`);
            activeBtn.classList.remove('bg-white', 'text-gray-600', 'border', 'border-peach-200');
            activeBtn.classList.add('bg-peach-500', 'text-white', 'shadow-sm');
        }

        // Voucher Upload & Handling
        function handleFileSelect(event) {
            const file = event.target.files[0];
            if (file) processVoucherFile(file);
        }

        function handleDragOver(e) {
            e.preventDefault();
            e.stopPropagation();
            document.getElementById('voucher-dropzone').classList.add('bg-peach-100/60');
        }

        function handleDragLeave(e) {
            e.preventDefault();
            e.stopPropagation();
            document.getElementById('voucher-dropzone').classList.remove('bg-peach-100/60');
        }

        function handleDrop(e) {
            e.preventDefault();
            e.stopPropagation();
            document.getElementById('voucher-dropzone').classList.remove('bg-peach-100/60');
            const file = e.dataTransfer.files[0];
            if (file) processVoucherFile(file);
        }

        function processVoucherFile(file) {
            if (file.size > 8 * 1024 * 1024) {
                alert("檔案較大，建議上傳 5MB 以下之憑證圖片或 PDF。");
            }

            const reader = new FileReader();
            reader.onload = function(e) {
                const fileData = {
                    name: file.name,
                    type: file.type,
                    dataUrl: e.target.result
                };
                try {
                    localStorage.setItem('fukuoka_hotel_voucher_filedata', JSON.stringify(fileData));
                    renderVoucherPreview(fileData);
                } catch (err) {
                    alert("儲存檔案失敗：檔案過大超過瀏覽器儲存限制。");
                }
            };
            reader.readAsDataURL(file);
        }

        function renderVoucherPreview(fileData) {
            if (!fileData || !fileData.dataUrl) return;

            const previewContainer = document.getElementById('voucher-preview-container');
            const dropzone = document.getElementById('voucher-dropzone');
            const imgPreview = document.getElementById('voucher-img-preview');
            const imgEl = document.getElementById('voucher-img-element');
            const pdfPreview = document.getElementById('voucher-pdf-preview');
            const filenameDisplay = document.getElementById('voucher-filename-display');
            const pdfLink = document.getElementById('voucher-pdf-link');

            previewContainer.classList.remove('hidden');
            dropzone.classList.add('hidden');

            if (fileData.type.startsWith('image/')) {
                imgPreview.classList.remove('hidden');
                pdfPreview.classList.add('hidden');
                imgEl.src = fileData.dataUrl;
            } else {
                pdfPreview.classList.remove('hidden');
                imgPreview.classList.add('hidden');
                filenameDisplay.innerText = fileData.name || "飯店入住憑證.pdf";
                pdfLink.href = fileData.dataUrl;
            }
        }

        function removeVoucher() {
            if (confirm("確定要移除現有的入住憑證嗎？")) {
                localStorage.removeItem('fukuoka_hotel_voucher_filedata');
                document.getElementById('voucher-preview-container').classList.add('hidden');
                document.getElementById('voucher-dropzone').classList.remove('hidden');
                document.getElementById('hotel-voucher-input').value = '';
            }
        }

        function openFullImage() {
            const imgSrc = document.getElementById('voucher-img-element').src;
            if (imgSrc) {
                document.getElementById('modal-img-element').src = imgSrc;
                document.getElementById('image-modal').classList.remove('hidden');
            }
        }

        function closeFullImage() {
            document.getElementById('image-modal').classList.add('hidden');
        }

        function saveVoucherNotes() {
            const notes = document.getElementById('hotel-voucher-notes').value;
            localStorage.setItem('fukuoka_hotel_voucher_notes', notes);
        }

        function loadVoucherData() {
            const savedNotes = localStorage.getItem('fukuoka_hotel_voucher_notes');
            if (savedNotes) {
                document.getElementById('hotel-voucher-notes').value = savedNotes;
            }
            const savedFileData = localStorage.getItem('fukuoka_hotel_voucher_filedata');
            if (savedFileData) {
                try {
                    renderVoucherPreview(JSON.parse(savedFileData));
                } catch(e) {
                    console.error("無法載入憑證", e);
                }
            }
        }

        // Detailed Packing List Data
        const detailedPackingCategories = [
            {
                category: "📄 證件與重要檔案 (隨身攜帶)",
                items: [
                    { id: 101, text: "護照正本 (效期需大於 6 個月)", checked: false },
                    { id: 102, text: "虎航機票電子憑證 / 訂位代號", checked: false },
                    { id: 103, text: "SG 博多旅居飯店住宿預約單", checked: false },
                    { id: 104, text: "一日遊預約憑證 (熊野一日遊、由布院一日遊)", checked: false },
                    { id: 105, text: "Visit Japan Web QR Code 截圖 (入境與海關)", checked: false },
                    { id: 106, text: "信用卡 (至少 2 張不同發卡組織，如吉鶴卡、CUBE卡)", checked: false },
                    { id: 107, text: "日幣現金 (每人準備 ¥30,000 ~ ¥40,000 應付小店與餐飲)", checked: false }
                ]
            },
            {
                category: "📶 電子與通訊設備",
                items: [
                    { id: 201, text: "日本上網卡 / 開通 eSIM (7天上網吃到飽或足量方案)", checked: false },
                    { id: 202, text: "手機 (已下載 Google Maps、Go Taxi 等旅遊App)", checked: false },
                    { id: 203, text: "大容量行動電源 (須放隨身行李，不可託運)", checked: false },
                    { id: 204, text: "充電線 (Type-C / Lightning 等)", checked: false },
                    { id: 205, text: "多孔 USB 充電頭 (旅館插座共用)", checked: false }
                ]
            },
            {
                category: "👗 衣物與穿搭 (10月中旬秋季・洋蔥式穿法)",
                items: [
                    { id: 301, text: "好走好穿的布鞋 / 運動鞋 (每天步行數萬步必備)", checked: false },
                    { id: 302, text: "7天份內衣褲 / 免洗褲", checked: false },
                    { id: 303, text: "7天份襪子 (建議厚薄適中、吸汗舒適)", checked: false },
                    { id: 304, text: "短袖或薄長袖上衣 (白天舒適)", checked: false },
                    { id: 305, text: "輕便外套 / 風衣 / 針織衫 (早晚溫差 15°C~24°C 微涼)", checked: false },
                    { id: 306, text: "長褲 / 休閒褲 (適合戶外一日遊活動)", checked: false },
                    { id: 307, text: "睡衣 / 居家服 (飯店內穿著)", checked: false }
                ]
            },
            {
                category: "💊 藥品與個人衛生",
                items: [
                    { id: 401, text: "個人常備藥品 (感冒藥、腸胃藥、止痛藥、暈車藥)", checked: false },
                    { id: 402, text: "OK繃 / 人工皮 (鐵腿或磨腳時急救)", checked: false },
                    { id: 403, text: "女性生理用品", checked: false },
                    { id: 404, text: "保養品 / 護唇膏 / 乳液 (10月日本秋天較為乾燥)", checked: false },
                    { id: 405, text: "個人盥洗保養小樣 / 卸妝用品", checked: false }
                ]
            },
            {
                category: "🎒 隨身雜物與其他",
                items: [
                    { id: 501, text: "輕便隨身小背包 / 托特包 (逛街與一日遊裝隨身物品)", checked: false },
                    { id: 502, text: "摺疊傘 / 輕量雨具 (應付秋天偶陣雨)", checked: false },
                    { id: 503, text: "分裝夾鏈袋 / 購物袋 (裝藥妝或備用)", checked: false },
                    { id: 504, text: "空行李箱 (準備第六天裝滿法國麵包與戰利品回台)", checked: false }
                ]
            }
        ];

        function loadPackingList() {
            let savedState = JSON.parse(localStorage.getItem('fukuoka_detailed_packing')) || {};
            const container = document.getElementById('packing-list-container');
            container.innerHTML = '';

            detailedPackingCategories.forEach(cat => {
                const sectionDiv = document.createElement('div');
                sectionDiv.className = "bg-gray-50 p-3.5 rounded-2xl space-y-2 border border-peach-100";
                
                let html = `<h4 class="text-xs font-bold text-peach-700 pb-1 border-b border-gray-200">${cat.category}</h4><div class="space-y-1.5 pt-1">`;
                
                cat.items.forEach(item => {
                    const isChecked = savedState[item.id] || false;
                    html += `
                        <label class="flex items-start gap-2.5 cursor-pointer hover:bg-peach-50/50 p-1 rounded transition">
                            <input type="checkbox" ${isChecked ? 'checked' : ''} onchange="togglePacking(${item.id})" class="w-4 h-4 mt-0.5 accent-peach-500 rounded shrink-0">
                            <span class="text-xs ${isChecked ? 'line-through text-gray-400' : 'text-gray-700 font-medium'}">${item.text}</span>
                        </label>
                    `;
                });
                html += `</div>`;
                sectionDiv.innerHTML = html;
                container.appendChild(sectionDiv);
            });
        }

        function togglePacking(id) {
            let savedState = JSON.parse(localStorage.getItem('fukuoka_detailed_packing')) || {};
            savedState[id] = !savedState[id];
            localStorage.setItem('fukuoka_detailed_packing', JSON.stringify(savedState));
            loadPackingList();
        }

        function resetPacking() {
            if(confirm("確定要重置所有行李勾選狀態嗎？")) {
                localStorage.removeItem('fukuoka_detailed_packing');
                loadPackingList();
            }
        }

        // Shared & Personal Expense Functions
        function loadExpensesData() {
            loadSharedExpenses();
            loadPersonalExpenses();
        }

        function loadSharedExpenses() {
            let expenses = JSON.parse(localStorage.getItem('fukuoka_shared_expenses')) || [];
            const listContainer = document.getElementById('shared-expense-list');
            listContainer.innerHTML = '';
            
            let total = 0;
            let paidLucy = 0;
            let paidRigo = 0;

            if(expenses.length === 0) {
                listContainer.innerHTML = `<p class="text-xs text-gray-400 text-center py-2">尚無共用分帳記錄</p>`;
            }

            expenses.forEach((exp, idx) => {
                total += Number(exp.amount);
                if(exp.payer === 'Lucy') paidLucy += Number(exp.amount);
                if(exp.payer === 'Rigo') paidRigo += Number(exp.amount);

                const itemDiv = document.createElement('div');
                itemDiv.className = "flex justify-between items-center bg-gray-50 p-2.5 rounded-xl text-xs";
                itemDiv.innerHTML = `
                    <div>
                        <p class="font-bold text-gray-800">${exp.title}</p>
                        <p class="text-[10px] text-gray-400">代付者: <span class="text-peach-600 font-medium">${exp.payer}</span></p>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="font-bold text-gray-700">¥${Number(exp.amount).toLocaleString()}</span>
                        <button onclick="deleteSharedExpense(${idx})" class="text-gray-300 hover:text-red-500"><i class="fa-solid fa-trash text-[11px]"></i></button>
                    </div>
                `;
                listContainer.appendChild(itemDiv);
            });

            document.getElementById('total-shared-amount').innerText = `¥${total.toLocaleString()}`;

            const half = total / 2;
            const diff = paidLucy - half;
            const summaryText = document.getElementById('settlement-summary-text');
            if (expenses.length === 0) {
                summaryText.innerText = "尚無分帳記錄";
            } else if (Math.abs(diff) < 1) {
                summaryText.innerText = "目前兩人完美打平！";
            } else if (diff > 0) {
                summaryText.innerText = `Rigo 應給 Lucy ¥${Math.round(diff).toLocaleString()}`;
            } else {
                summaryText.innerText = `Lucy 應給 Rigo ¥${Math.round(-diff).toLocaleString()}`;
            }
        }

        function addSharedExpense(e) {
            e.preventDefault();
            const title = document.getElementById('shared-title').value;
            const amount = document.getElementById('shared-amount').value;
            const payer = document.getElementById('shared-payer').value;

            let expenses = JSON.parse(localStorage.getItem('fukuoka_shared_expenses')) || [];
            expenses.push({ title, amount, payer });
            localStorage.setItem('fukuoka_shared_expenses', JSON.stringify(expenses));

            document.getElementById('shared-title').value = '';
            document.getElementById('shared-amount').value = '';
            loadSharedExpenses();
        }

        function deleteSharedExpense(index) {
            let expenses = JSON.parse(localStorage.getItem('fukuoka_shared_expenses')) || [];
            expenses.splice(index, 1);
            localStorage.setItem('fukuoka_shared_expenses', JSON.stringify(expenses));
            loadSharedExpenses();
        }

        function clearSharedExpenses() {
            if(confirm("確定清空所有共用分帳記錄嗎？")) {
                localStorage.removeItem('fukuoka_shared_expenses');
                loadSharedExpenses();
            }
        }

        function loadPersonalExpenses() {
            let persExpenses = JSON.parse(localStorage.getItem('fukuoka_personal_expenses')) || [];
            const listContainer = document.getElementById('personal-expense-list');
            listContainer.innerHTML = '';

            let persTotal = 0;
            if(persExpenses.length === 0) {
                listContainer.innerHTML = `<p class="text-xs text-gray-400 text-center py-2">尚無個人消費記帳</p>`;
            }

            persExpenses.forEach((exp, idx) => {
                persTotal += Number(exp.amount);
                const itemDiv = document.createElement('div');
                itemDiv.className = "flex justify-between items-center bg-gray-50 p-2.5 rounded-xl text-xs";
                itemDiv.innerHTML = `
                    <div>
                        <p class="font-bold text-gray-800">${exp.title} <span class="text-[9px] bg-peach-100 text-peach-700 px-1.5 py-0.5 rounded ml-1">${exp.owner}</span></p>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="font-bold text-gray-700">¥${Number(exp.amount).toLocaleString()}</span>
                        <button onclick="deletePersonalExpense(${idx})" class="text-gray-300 hover:text-red-500"><i class="fa-solid fa-trash text-[11px]"></i></button>
                    </div>
                `;
                listContainer.appendChild(itemDiv);
            });

            document.getElementById('personal-total-amount').innerText = `個人總計: ¥${persTotal.toLocaleString()}`;
        }

        function addPersonalExpense(e) {
            e.preventDefault();
            const owner = document.getElementById('pers-owner').value;
            const amount = document.getElementById('pers-amount').value;
            const title = document.getElementById('pers-title').value;

            let persExpenses = JSON.parse(localStorage.getItem('fukuoka_personal_expenses')) || [];
            persExpenses.push({ owner, amount, title });
            localStorage.setItem('fukuoka_personal_expenses', JSON.stringify(persExpenses));

            document.getElementById('pers-amount').value = '';
            document.getElementById('pers-title').value = '';
            loadPersonalExpenses();
        }

        function deletePersonalExpense(index) {
            let persExpenses = JSON.parse(localStorage.getItem('fukuoka_personal_expenses')) || [];
            persExpenses.splice(index, 1);
            localStorage.setItem('fukuoka_personal_expenses', JSON.stringify(persExpenses));
            loadPersonalExpenses();
        }

        // Wishlist & Modal Handling
        function openLinkModal() {
            document.getElementById('link-modal').classList.remove('hidden');
        }

        function closeLinkModal() {
            document.getElementById('link-modal').classList.add('hidden');
            document.getElementById('custom-place-name').value = '';
            document.getElementById('custom-place-url').value = '';
        }

        function saveCustomPlace() {
            const name = document.getElementById('custom-place-name').value;
            const url = document.getElementById('custom-place-url').value;
            if(!name || !url) {
                alert("請填寫完整的名稱與 Google Map 連結");
                return;
            }

            let customWishlist = JSON.parse(localStorage.getItem('fukuoka_custom_wishlist')) || [];
            customWishlist.push({ name, url });
            localStorage.setItem('fukuoka_custom_wishlist', JSON.stringify(customWishlist));

            closeLinkModal();
            loadWishlist();
            alert("成功新增至許願池！");
        }

        function loadWishlist() {
            let customWishlist = JSON.parse(localStorage.getItem('fukuoka_custom_wishlist')) || [];
            const container = document.getElementById('wishlist-container');
            
            customWishlist.forEach(item => {
                const div = document.createElement('div');
                div.className = "bg-peach-50/60 p-3 rounded-xl flex items-center justify-between border border-peach-200";
                div.innerHTML = `
                    <div>
                        <h4 class="text-xs font-bold text-gray-800">${item.name} <span class="text-[9px] bg-peach-200 text-peach-800 px-1.5 py-0.5 rounded">自訂</span></h4>
                        <p class="text-[10px] text-gray-500">使用者自訂許願地標</p>
                    </div>
                    <a href="${item.url}" target="_blank" class="bg-peach-500 text-white px-3 py-1.5 rounded-xl text-xs font-medium hover:bg-peach-600 transition shadow-sm">
                        導航
                    </a>
                `;
                container.appendChild(div);
            });
        }

        window.onload = function() {
            loadVoucherData();
            loadPackingList();
            loadExpensesData();
            loadWishlist();
        }
    </script>
</body>
</html>
