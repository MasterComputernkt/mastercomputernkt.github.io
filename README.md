<html b:css='false' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
    <meta content='width=device-width, initial-scale=1.0' name='viewport'/>
    <meta content='text/html; charset=UTF-8' http-equiv='Content-Type'/>
    <title><data:blog.pageTitle/></title>
<!-- Tailwind CSS (Using &amp; for XML safety) -->
    <script src='https://cdn.tailwindcss.com'></script>
    
    <!-- Font Awesome Icons -->
    <link href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css' rel='stylesheet'/>
    
    <!-- Google Fonts - Hind Siliguri for Bengali typography -->
    <link href='https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&amp;display=swap' rel='stylesheet'/>

    <!-- Custom Style Sheet in CDATA block -->
    <style type='text/css'>
    /*<![CDATA[*/
        body {
            font-family: 'Hind Siliguri', sans-serif;
        }
        .bg-brand-blue { background-color: #0b3c5d; }
        .bg-brand-gold { background-color: #d4af37; }
        .text-brand-gold { color: #d4af37; }
        .border-brand-gold { border-color: #d4af37; }
        .glow-effect {
            box-shadow: 0 0 15px rgba(212, 175, 55, 0.3);
        }
    /*]]>*/
    </style>
</head>
<body class='bg-slate-50 text-slate-800 flex flex-col min-h-screen'>

    <!-- Top Announcement Bar -->
    <div class='bg-gradient-to-r from-blue-950 via-slate-900 to-indigo-950 text-white text-xs md:text-sm py-2 px-4 shadow-inner'>
        <div class='max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2 text-center sm:text-left'>
            <div class='flex items-center gap-2'>
                <span class='bg-red-600 text-white text-[10px] font-bold px-2 py-0.5 rounded uppercase tracking-wider'>অনুমোদিত</span>
                <span>গণপ্রজাতন্ত্রী বাংলাদেশ সরকার অনুমোদিত একটি বিশ্বস্ত প্রতিষ্ঠান (Since 2006)</span>
            </div>
            <div class='flex items-center gap-4 text-xs font-semibold'>
                <a class='hover:text-amber-400 transition flex items-center gap-1' href='tel:01711319161'>
                    <i class='fas fa-wrench text-amber-400'></i> ০৭১১-৩১৯১৬১ (সার্ভিসিং)
                </a>
                <span class='text-slate-600'>|</span>
                <a class='hover:text-amber-400 transition flex items-center gap-1' href='tel:01730168046'>
                    <i class='fas fa-graduation-cap text-amber-400'></i> ০১৭৩০-১৬৮০৪৬ (ভর্তি)
                </a>
            </div>
        </div>
    </div>

    <!-- Navigation Header -->
    <header class='bg-white border-b border-slate-200 sticky top-0 z-50 shadow-sm'>
        <div class='max-w-7xl mx-auto px-4 py-3 flex justify-between items-center'>
            <!-- Logo Section -->
            <a class='flex items-center gap-3 group' href='/'>
                <div class='w-12 h-12 md:w-14 md:h-14 rounded-full bg-slate-900 border-2 border-amber-500 flex flex-col items-center justify-center text-amber-400 shadow-md group-hover:scale-105 transition transform'>
                    <i class='fas fa-desktop text-base md:text-lg'></i>
                    <span class='text-[7px] md:text-[8px] font-bold tracking-widest uppercase leading-none mt-0.5'>Master</span>
                </div>
                <div>
                    <h1 class='text-lg md:text-2xl font-bold text-slate-900 leading-tight group-hover:text-blue-700 transition'>মাষ্টার কম্পিউটার</h1>
                    <p class='text-xs font-semibold text-blue-700'>এন্ড ট্রেনিং সেন্টার — নাঙ্গলকোট</p>
                </div>
            </a>

            <!-- Menu Navigation -->
            <nav class='hidden lg:flex items-center gap-6 font-semibold text-sm text-slate-700'>
                <a class='hover:text-blue-600 transition py-1 border-b-2 border-transparent hover:border-blue-600' href='#home'>হোম</a>
                <a class='hover:text-blue-600 transition py-1 border-b-2 border-transparent hover:border-blue-600' href='#services'>সেবাসমূহ</a>
                <a class='hover:text-blue-600 transition py-1 border-b-2 border-transparent hover:border-blue-600' href='#products'>পণ্যসমূহ</a>
                <a class='hover:text-blue-600 transition py-1 border-b-2 border-transparent hover:border-blue-600' href='#training'>ট্রেনিং কোর্স</a>
                <a class='hover:text-blue-600 transition py-1 border-b-2 border-transparent hover:border-blue-600' href='#contact'>যোগাযোগ</a>
            </nav>

            <!-- Action Buttons -->
            <div class='flex items-center gap-2'>
                <a class='bg-green-600 hover:bg-green-700 text-white font-bold text-xs md:text-sm px-3 md:px-4 py-2 rounded-lg flex items-center gap-2 shadow transition' href='https://wa.me/8801711319161' target='_blank'>
                    <i class='fab fa-whatsapp text-base'></i> <span class='hidden sm:inline'>হোয়াটসঅ্যাপে চ্যাট</span>
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Banner Section -->
    <section class='bg-gradient-to-br from-slate-900 via-blue-950 to-slate-900 text-white py-12 px-4 relative overflow-hidden' id='home'>
        <div class='max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-12 gap-8 items-center'>
            <!-- Banner Content -->
            <div class='lg:col-span-7 space-y-5 text-center lg:text-left'>
                <div class='inline-flex items-center gap-2 bg-amber-500/20 border border-amber-500/40 text-amber-300 px-3 py-1 rounded-full text-xs md:text-sm font-semibold'>
                    <i class='fas fa-star text-amber-400'></i> আপনার প্রযুক্তি ও বিশ্বস্ততার সেরা ঠিকানা
                </div>
                <h2 class='text-3xl md:text-5xl font-extrabold leading-tight tracking-normal'>
                    মাষ্টার কম্পিউটার <br/><span class='text-amber-400'>এন্ড ট্রেনিং সেন্টার</span>
                </h2>
                <p class='text-slate-300 text-base md:text-lg max-w-2xl mx-auto lg:mx-0'>
                    কম্পিউটার, ল্যাপটপ, সিসি ক্যামেরা ও নেটওয়ার্কিং সরঞ্জাম ক্রয়, দ্রুততম সময়ে সার্ভিসিং এবং ক্যারিয়ার গড়ার সেরা কম্পিউটার প্রশিক্ষণ সেবা।
                </p>

                <!-- Key Highlights -->
                <div class='grid grid-cols-3 gap-3 pt-2 text-center max-w-lg mx-auto lg:mx-0'>
                    <div class='bg-white/5 border border-white/10 p-2.5 rounded-xl backdrop-blur-sm'>
                        <i class='fas fa-laptop-code text-amber-400 text-xl md:text-2xl mb-1'></i>
                        <p class='text-xs font-semibold'>মানসম্মত প্রশিক্ষণ</p>
                    </div>
                    <div class='bg-white/5 border border-white/10 p-2.5 rounded-xl backdrop-blur-sm'>
                        <i class='fas fa-screwdriver-wrench text-amber-400 text-xl md:text-2xl mb-1'></i>
                        <p class='text-xs font-semibold'>দ্রুত সার্ভিসিং</p>
                    </div>
                    <div class='bg-white/5 border border-white/10 p-2.5 rounded-xl backdrop-blur-sm'>
                        <i class='fas fa-box-open text-amber-400 text-xl md:text-2xl mb-1'></i>
                        <p class='text-xs font-semibold'>সুলভ মূল্যে পণ্য</p>
                    </div>
                </div>

                <div class='flex flex-wrap gap-3 justify-center lg:justify-start pt-3'>
                    <a class='bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold px-6 py-3 rounded-xl shadow-lg transition transform hover:-translate-y-0.5' href='#training'>
                        <i class='fas fa-graduation-cap mr-1'></i> নতুন ব্যাচে ভর্তি
                    </a>
                    <a class='bg-blue-600 hover:bg-blue-700 text-white font-bold px-6 py-3 rounded-xl shadow-lg transition transform hover:-translate-y-0.5' href='#products'>
                        <i class='fas fa-shopping-bag mr-1'></i> পণ্য সমূহ দেখুন
                    </a>
                </div>
            </div>

            <!-- Banner Visual Frame (Emulating the Poster Visual) -->
            <div class='lg:col-span-5'>
                <div class='bg-gradient-to-b from-blue-900 to-indigo-950 p-6 md:p-8 rounded-2xl border-2 border-amber-500/50 shadow-2xl relative text-center space-y-4'>
                    <div class='absolute -top-3 left-1/2 transform -translate-x-1/2 bg-red-600 text-white text-[11px] font-bold px-4 py-1 rounded-full uppercase tracking-wider shadow'>
                        ভর্তি চলছে!
                    </div>
                    <div class='w-20 h-20 mx-auto rounded-full bg-slate-950 border-2 border-amber-400 flex items-center justify-center text-amber-400 shadow-xl'>
                        <i class='fas fa-award text-3xl'></i>
                    </div>
                    <h3 class='text-2xl font-bold text-amber-400'>দক্ষ সেবা ও সততার প্রতিশ্রুতি</h3>
                    <p class='text-slate-300 text-xs md:text-sm leading-relaxed'>
                        পুরাতন বোর্ড অফিস সংলগ্ন (নাঙ্গলকোট কেন্দ্রীয় জামে মসজিদের উত্তর পার্শ্বে), নাঙ্গলকোট, কুমিল্লা।
                    </p>
                    <div class='pt-2 border-t border-slate-700/60 flex flex-col gap-2 text-xs font-semibold text-amber-300'>
                        <div><i class='fas fa-phone-alt text-green-400 mr-1'></i> সার্ভিসিং: ০৭১১-৩১৯১৬১</div>
                        <div><i class='fas fa-phone-alt text-amber-400 mr-1'></i> ট্রেনিং: ০১৭৩০-১৬৮০৪৬</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class='py-14 bg-white' id='services'>
        <div class='max-w-7xl mx-auto px-4'>
            <div class='text-center max-w-2xl mx-auto mb-10 space-y-2'>
                <h2 class='text-2xl md:text-4xl font-extrabold text-slate-900'>আমাদের সেবাসমূহ</h2>
                <p class='text-slate-600 text-sm md:text-base'>আমরা আপনার যেকোনো প্রযুক্তিগত সহায়তা ও ক্যাটারিং-এ আছি সবসময় পাশে!</p>
            </div>

            <div class='grid grid-cols-1 md:grid-cols-3 gap-6'>
                <!-- Service 1 -->
                <div class='bg-slate-50 border border-slate-200 rounded-2xl p-6 hover:border-blue-500 hover:shadow-xl transition group flex flex-col justify-between'>
                    <div>
                        <div class='w-14 h-14 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center text-2xl mb-4 group-hover:bg-blue-600 group-hover:text-white transition'>
                            <i class='fas fa-cart-shopping'></i>
                        </div>
                        <h3 class='text-xl font-bold text-slate-900 mb-2'>💻 পণ্য বিক্রয়</h3>
                        <p class='text-slate-600 text-sm leading-relaxed'>
                            কম্পিউটার, ল্যাপটপ, সিসি ক্যামেরা ও ওয়াইফাই এর সকল প্রকার সরঞ্জাম পাইকারি ও খুচরা মূল্যে সুলভে পাওয়া যায়।
                        </p>
                    </div>
                    <a class='mt-6 inline-flex items-center text-sm font-bold text-blue-600 hover:text-blue-800' href='#products'>
                        পণ্যসমূহ তালিকা <i class='fas fa-arrow-right ml-2 text-xs'></i>
                    </a>
                </div>

                <!-- Service 2 -->
                <div class='bg-slate-50 border border-slate-200 rounded-2xl p-6 hover:border-amber-500 hover:shadow-xl transition group flex flex-col justify-between'>
                    <div>
                        <div class='w-14 h-14 bg-amber-100 text-amber-600 rounded-xl flex items-center justify-center text-2xl mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition'>
                            <i class='fas fa-screwdriver-wrench'></i>
                        </div>
                        <h3 class='text-xl font-bold text-slate-900 mb-2'>🛠️ নির্ভরযোগ্য সার্ভিসিং</h3>
                        <p class='text-slate-600 text-sm leading-relaxed'>
                            যেকোনো কম্পিউটার, ল্যাপটপ ও প্রিন্টারের দ্রুত, টেকসই এবং নির্ভরযোগ্য সার্ভিসিং প্রদান করা হয়।
                        </p>
                    </div>
                    <a class='mt-6 inline-flex items-center text-sm font-bold text-amber-600 hover:text-amber-800' href='tel:01711319161'>
                        সার্ভিসিং এর জন্য কল করুন <i class='fas fa-phone ml-2 text-xs'></i>
                    </a>
                </div>

                <!-- Service 3 -->
                <div class='bg-slate-50 border border-slate-200 rounded-2xl p-6 hover:border-green-500 hover:shadow-xl transition group flex flex-col justify-between'>
                    <div>
                        <div class='w-14 h-14 bg-green-100 text-green-600 rounded-xl flex items-center justify-center text-2xl mb-4 group-hover:bg-green-600 group-hover:text-white transition'>
                            <i class='fas fa-user-graduate'></i>
                        </div>
                        <h3 class='text-xl font-bold text-slate-900 mb-2'>🎓 কম্পিউটার প্রশিক্ষণ</h3>
                        <p class='text-slate-600 text-sm leading-relaxed'>
                            আইটি খাতে নিজেকে স্বাবলম্বী করতে সরকারি মানের কম্পিউটার প্রশিক্ষণ কেন্দ্র।
                        </p>
                    </div>
                    <a class='mt-6 inline-flex items-center text-sm font-bold text-green-600 hover:text-green-800' href='#training'>
                        কোর্স সমূহ দেখুন <i class='fas fa-arrow-right ml-2 text-xs'></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Product Catalog Grid Section -->
    <section class='py-14 bg-slate-100 border-y border-slate-200' id='products'>
        <div class='max-w-7xl mx-auto px-4'>
            <div class='flex flex-col md:flex-row md:items-end justify-between mb-10 gap-4'>
                <div>
                    <span class='text-blue-600 font-bold text-xs uppercase tracking-widest'>পণ্য ক্যাটালগ</span>
                    <h2 class='text-2xl md:text-4xl font-extrabold text-slate-900 mt-1'>কম্পিউটার এক্সেসরিজ ও পার্টস</h2>
                </div>
                <div class='text-slate-600 text-sm'>
                    পাইকারি ও খুচরা সুলভ মূল্যে উপলব্ধ
                </div>
            </div>

            <!-- Grid Items from Prompt Image 2 list -->
            <div class='grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-4'>
                
                <!-- Monitor -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-desktop'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>মনিটর</h4>
                        <p class='text-[11px] text-slate-500'>Monitor</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20Monitor%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- CPU -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-server'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>সিপিইউ (System Unit)</h4>
                        <p class='text-[11px] text-slate-500'>Desktop CPU Case</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20System%20Unit%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- Keyboard -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-keyboard'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>কীবোর্ড</h4>
                        <p class='text-[11px] text-slate-500'>Keyboard</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20Keyboard%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- Mouse -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-mouse'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>মাউস</h4>
                        <p class='text-[11px] text-slate-500'>Mouse</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20Mouse%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- Laptop -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-laptop'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>ল্যাপটপ</h4>
                        <p class='text-[11px] text-slate-500'>Laptop</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20Laptop%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- Printer -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-print'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>প্রিন্টার</h4>
                        <p class='text-[11px] text-slate-500'>Printer</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20Printer%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- Router -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-wifi'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>ওয়াইফাই রাউটার</h4>
                        <p class='text-[11px] text-slate-500'>Router</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20Router%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- SSD -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-microchip'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>এসএসডি (SSD)</h4>
                        <p class='text-[11px] text-slate-500'>Solid State Drive</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20SSD%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- RAM -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-memory'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>র‍্যাম (RAM)</h4>
                        <p class='text-[11px] text-slate-500'>RAM Memory</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20RAM%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- CCTV Camera -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-video'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>সিসি ক্যামেরা</h4>
                        <p class='text-[11px] text-slate-500'>CCTV Setup</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20CCTV%20Camera%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- UPS -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-battery-three-quarters'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>ইউপিএস (UPS)</h4>
                        <p class='text-[11px] text-slate-500'>UPS Power</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20UPS%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

                <!-- Graphics Card -->
                <div class='bg-white p-4 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition text-center flex flex-col justify-between items-center group'>
                    <div class='w-12 h-12 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-xl mb-2 group-hover:bg-blue-600 group-hover:text-white transition'>
                        <i class='fas fa-gamepad'></i>
                    </div>
                    <div>
                        <h4 class='font-bold text-slate-900 text-sm'>গ্রাফিক্স কার্ড</h4>
                        <p class='text-[11px] text-slate-500'>Graphics Card</p>
                    </div>
                    <a class='mt-3 w-full bg-slate-100 hover:bg-green-600 hover:text-white text-slate-700 text-xs font-semibold py-1.5 rounded transition flex items-center justify-center gap-1' href='https://wa.me/8801711319161?text=আমি%20Graphics%20Card%20সম্পর্কে%20জানতে%20চাই' target='_blank'>
                        <i class='fab fa-whatsapp'></i> অর্ডার/দাম
                    </a>
                </div>

            </div>
        </div>
    </section>

    <!-- Computer Training Center Section -->
    <section class='py-14 bg-gradient-to-r from-blue-900 via-indigo-950 to-slate-900 text-white' id='training'>
        <div class='max-w-7xl mx-auto px-4'>
            <div class='text-center max-w-2xl mx-auto mb-10 space-y-2'>
                <span class='bg-amber-500 text-slate-950 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-widest'>ভর্তি চলছে!</span>
                <h2 class='text-3xl md:text-4xl font-extrabold text-white'>কম্পিউটার প্রশিক্ষণ কোর্সসমূহ</h2>
                <p class='text-slate-300 text-sm md:text-base'>আইটি খাতে ক্যারিয়ার গড়ে নিজেকে আত্মনির্ভরশীল করুন</p>
            </div>

            <div class='grid grid-cols-1 md:grid-cols-3 gap-6'>
                <!-- Course 1 -->
                <div class='bg-white/10 border border-white/10 rounded-2xl p-6 backdrop-blur-md flex flex-col justify-between'>
                    <div>
                        <div class='text-amber-400 text-3xl mb-3'><i class='fas fa-file-word'></i></div>
                        <h3 class='text-xl font-bold text-white mb-2'>অফিস অ্যাপ্লিকেশন কোর্স</h3>
                        <p class='text-slate-300 text-sm leading-relaxed mb-4'>
                            MS Word, MS Excel, PowerPoint, Bangla &amp; English Typing এবং ইন্টারনেট ব্যবহারের খুঁটিনাটি।
                        </p>
                    </div>
                    <div class='border-t border-white/10 pt-4 flex justify-between items-center'>
                        <span class='text-xs text-amber-300 font-semibold'>মেয়াদ: ৩-৬ মাস</span>
                        <a class='bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs px-3 py-1.5 rounded-lg transition' href='tel:01730168046'>ভর্তি হতে কল করুন</a>
                    </div>
                </div>

                <!-- Course 2 -->
                <div class='bg-white/10 border border-white/10 rounded-2xl p-6 backdrop-blur-md flex flex-col justify-between'>
                    <div>
                        <div class='text-amber-400 text-3xl mb-3'><i class='fas fa-palette'></i></div>
                        <h3 class='text-xl font-bold text-white mb-2'>গ্রাফিক্স ডিজাইন বেসিক</h3>
                        <p class='text-slate-300 text-sm leading-relaxed mb-4'>
                            Photoshop ও Illustrator এর মাধ্যমে ব্যানার, পোস্টার, লোগো ও ছবি এডিটিং শেখানো হয়।
                        </p>
                    </div>
                    <div class='border-t border-white/10 pt-4 flex justify-between items-center'>
                        <span class='text-xs text-amber-300 font-semibold'>মেয়াদ: ৩ মাস</span>
                        <a class='bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs px-3 py-1.5 rounded-lg transition' href='tel:01730168046'>ভর্তি হতে কল করুন</a>
                    </div>
                </div>

                <!-- Course 3 -->
                <div class='bg-white/10 border border-white/10 rounded-2xl p-6 backdrop-blur-md flex flex-col justify-between'>
                    <div>
                        <div class='text-amber-400 text-3xl mb-3'><i class='fas fa-wrench'></i></div>
                        <h3 class='text-xl font-bold text-white mb-2'>হার্ডওয়্যার ও ট্রাবলশুটিং</h3>
                        <p class='text-slate-300 text-sm leading-relaxed mb-4'>
                            কম্পিউটার এসেম্বলিং, উইন্ডোজ ইন্সটলেশন, সফটওয়্যার সেটআপ ও বেসিক ট্রাবলশুটিং।
                        </p>
                    </div>
                    <div class='border-t border-white/10 pt-4 flex justify-between items-center'>
                        <span class='text-xs text-amber-300 font-semibold'>মেয়াদ: ২-৩ মাস</span>
                        <a class='bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs px-3 py-1.5 rounded-lg transition' href='tel:01730168046'>ভর্তি হতে কল করুন</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Location and Contact Section -->
    <section class='py-14 bg-white' id='contact'>
        <div class='max-w-7xl mx-auto px-4'>
            <div class='text-center max-w-2xl mx-auto mb-10'>
                <h2 class='text-3xl font-extrabold text-slate-900'>যোগাযোগ ও ঠিকানা</h2>
                <p class='text-slate-600 text-sm mt-1'>সরাসরি সেন্টারে এসে যোগাযোগ করতে পারেন</p>
            </div>

            <div class='grid grid-cols-1 md:grid-cols-2 gap-8 items-start'>
                <!-- Address Details -->
                <div class='space-y-4'>
                    <div class='bg-slate-50 border border-slate-200 p-5 rounded-xl flex items-start gap-4'>
                        <div class='w-10 h-10 bg-blue-600 text-white rounded-lg flex items-center justify-center shrink-0 text-lg'>
                            <i class='fas fa-location-dot'></i>
                        </div>
                        <div>
                            <h4 class='font-bold text-slate-900 text-base'>ঠিকানা:</h4>
                            <p class='text-slate-600 text-sm mt-1 leading-relaxed'>
                                পুরাতন বোর্ড অফিস সংলগ্ন (নাঙ্গলকোট কেন্দ্রীয় জামে মসজিদের উত্তর পার্শ্বে), নাঙ্গলকোট, কুমিল্লা।
                            </p>
                        </div>
                    </div>

                    <div class='bg-slate-50 border border-slate-200 p-5 rounded-xl flex items-start gap-4'>
                        <div class='w-10 h-10 bg-amber-500 text-slate-950 rounded-lg flex items-center justify-center shrink-0 text-lg'>
                            <i class='fas fa-map-signs'></i>
                        </div>
                        <div>
                            <h4 class='font-bold text-slate-900 text-base'>সহজ লোকেশন নির্দেশিকা:</h4>
                            <p class='text-slate-600 text-sm mt-1 leading-relaxed'>
                                নাঙ্গলকোট কেন্দ্রীয় জামে মসজিদ গেইট থেকে ৫০ মিটার পশ্চিমে এসে ১০০ মিটার উত্তরে, অথবা নাঙ্গলকোট কাঁচা বাজারের দক্ষিণ পার্শ্বে অবস্থিত পুরাতন বোর্ড অফিসের উত্তর পাশের গলি।
                            </p>
                        </div>
                    </div>

                    <div class='bg-slate-50 border border-slate-200 p-5 rounded-xl flex items-start gap-4'>
                        <div class='w-10 h-10 bg-green-600 text-white rounded-lg flex items-center justify-center shrink-0 text-lg'>
                            <i class='fas fa-headset'></i>
                        </div>
                        <div class='space-y-1'>
                            <h4 class='font-bold text-slate-900 text-base'>যোগাযোগ:</h4>
                            <p class='text-slate-700 text-sm'>
                                🛠️ <strong>সার্ভিসিং তথ্য:</strong> <a class='text-blue-600 hover:underline font-bold' href='tel:01711319161'>০৭১১-৩১৯১৬১</a> (জিয়াউর রহমান বিপ্লব)
                            </p>
                            <p class='text-slate-700 text-sm'>
                                🎓 <strong>ট্রেনিং ভর্তি/পরামর্শ:</strong> <a class='text-blue-600 hover:underline font-bold' href='tel:01730168046'>০১৭৩০-১৬৮০৪৬</a>
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Blogger Required Main Section Injection -->
                <div class='bg-slate-50 border border-slate-200 p-6 rounded-xl space-y-4'>
                    <h4 class='font-bold text-slate-900 text-lg border-b border-slate-200 pb-2'>ব্লগ ও আপডেট</h4>
                    <!-- Mandatory Blogger Widget Container -->
                    <b:section class='main' id='main' showaddelement='yes'>
                        <b:widget id='Blog1' locked='false' title='Blog Posts' type='Blog'/>
                    </b:section>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class='bg-slate-950 text-slate-400 mt-auto py-8 border-t border-slate-800 text-sm'>
        <div class='max-w-7xl mx-auto px-4 text-center space-y-3'>
            <div class='flex justify-center items-center gap-2 text-white font-bold text-base'>
                <i class='fas fa-desktop text-amber-400'></i> মাষ্টার কম্পিউটার এন্ড ট্রেনিং সেন্টার
            </div>
            <p class='text-xs text-slate-400 max-w-md mx-auto'>
                পুরাতন বোর্ড অফিস সংলগ্ন (নাঙ্গলকোট কেন্দ্রীয় জামে মসজিদের উত্তর পার্শ্বে), নাঙ্গলকোট, কুমিল্লা।
            </p>
            <p class='text-xs text-slate-500 pt-2'>
                &copy; 2006 - 2026 Master Computer &amp; Training Center. All rights reserved.
            </p>
        </div>
    </footer>

</body>
</html>
