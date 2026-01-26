<!DOCTYPE html>
<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>SHAWIK  | Secure Bridge</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@24,400,1,0" />
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        primary: '#135bec',
                        secondary: '#00d084',
                        darkBg: '#0a0f18',
                        cardBg: '#141c2c'
                    }
                }
            }
        }
    </script>
    <style>
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(12px); }
        .pp-gradient { background: linear-gradient(135deg, #003087 0%, #009cde 100%); }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        
        .loader-ring {
            border: 3px solid rgba(19, 91, 236, 0.1);
            border-top: 3px solid #135bec;
            border-radius: 50%;
            width: 40px; height: 40px;
            animation: spin 1s linear infinite;
        }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
        
        .notification-pulse {
            animation: pulse-ring 2s cubic-bezier(0.455, 0.03, 0.515, 0.955) infinite;
        }
        @keyframes pulse-ring {
            0% { transform: scale(0.33); opacity: 1; }
            80%, 100% { transform: scale(1); opacity: 0; }
        }
    </style>
</head>
<body class="bg-slate-50 dark:bg-darkBg text-slate-900 dark:text-white transition-colors duration-500 overflow-hidden font-sans">

    <div id="app-shell" class="relative h-screen w-full max-w-[480px] mx-auto bg-white dark:bg-darkBg shadow-2xl flex flex-col">
        
        <!-- Header -->
        <header class="flex items-center justify-between px-6 py-4 z-40">
            <div class="flex items-center gap-2.5">
                <div class="size-9 bg-primary flex items-center justify-center rounded-xl shadow-lg shadow-primary/20">
                    <span class="material-symbols-rounded text-white text-xl">account_balance_wallet</span>
                </div>
                <h1 class="font-extrabold text-xl tracking-tight italic">PAY<span class="text-primary">PAL</span></h1>
            </div>
            <div class="flex items-center gap-3">
                <button onclick="toggleNotification()" class="relative size-10 glass rounded-full flex items-center justify-center border border-slate-200 dark:border-white/5">
                    <span class="material-symbols-rounded text-xl">notifications</span>
                    <span class="absolute top-0 right-0 size-3 bg-primary rounded-full border-2 border-white dark:border-darkBg"></span>
                    <span class="absolute top-0 right-0 size-3 bg-primary rounded-full notification-pulse"></span>
                </button>
                <button onclick="toggleTheme()" class="size-10 glass rounded-full flex items-center justify-center border border-slate-200 dark:border-white/5">
                    <span id="t-icon" class="material-symbols-rounded text-xl">dark_mode</span>
                </button>
            </div>
        </header>

        <!-- Main Content -->
        <main class="flex-1 overflow-y-auto hide-scrollbar px-6 pb-28">
            
            <!-- Balance Card -->
            <div class="mt-4 mb-6">
                <p class="text-slate-500 dark:text-slate-400 text-[10px] font-bold tracking-[0.2em] uppercase mb-1">Mirror Balance</p>
                <div class="flex items-baseline gap-2">
                    <h2 class="text-4xl font-extrabold tracking-tight">UGX <span id="balance-val">76,000,000</span></h2>
                    <span class="material-symbols-rounded text-slate-400 text-lg">visibility_off</span>
                </div>
                <div id="status-badge" class="mt-2 inline-flex items-center gap-1 bg-slate-100 dark:bg-white/5 px-2 py-0.5 rounded-full border border-slate-200 dark:border-white/5">
                    <span class="material-symbols-rounded text-slate-400 text-xs">link_off</span>
                    <span class="text-slate-400 text-[9px] font-bold uppercase tracking-wider">Bridge Offline</span>
                </div>
            </div>

            <!-- Action Buttons -->
            <div class="grid grid-cols-2 gap-3 mb-8">
                <button onclick="openWithdraw()" class="flex items-center justify-center gap-2 bg-primary text-white py-4 rounded-2xl font-bold shadow-lg shadow-primary/25 active:scale-95 transition-all">
                    <span class="material-symbols-rounded">north_east</span>
                    Withdraw
                </button>
                <button class="flex items-center justify-center gap-2 bg-slate-100 dark:bg-cardBg py-4 rounded-2xl font-bold border border-slate-200 dark:border-white/5 active:scale-95 transition-all">
                    <span class="material-symbols-rounded">add</span>
                    Top Up
                </button>
            </div>

            <!-- Connect Card (Fixed Visibility) -->
            <div id="connection-zone" class="mb-8">
                <div class="pp-gradient rounded-3xl p-6 shadow-xl relative overflow-hidden group">
                    <div class="relative z-10">
                        <div class="flex items-center gap-3 mb-4">
                            <div class="bg-white p-1.5 rounded-lg shadow-md">
                                <svg width="22" height="22" viewBox="0 0 24 24" fill="none"><path d="M20.007 6.44c-.21-1.65-1.35-2.85-3.09-2.85h-7.65c-.51 0-.93.39-.99.87L7.017 18.51c-.03.27.18.51.45.51h3.36c.45 0 .84-.33.9-.78l.03-.21 1.05-6.66c.06-.45.45-.78.9-.78h1.23c2.73 0 4.86-1.11 5.49-4.29.18-.9-.03-1.62-.42-1.86z" fill="#003087"></path><path d="M18.817 10.32c-.63 3.18-2.76 4.29-5.49 4.29h-1.23c-.45 0-.84.33-.9.78l-1.05 6.66-.03.21c-.03.27.18.51.45.51h3.36c.45 0 .84-.33.9-.78l.03-.21 1.05-6.66c.06-.45.45-.78.9-.78h.09c2.73 0 4.86-1.11 5.49-4.29.18-.9-.03-1.62-.42-1.86-.33.24-.75.39-1.23.39h-.45z" fill="#009cde"></path></svg>
                            </div>
                            <span class="text-white font-bold tracking-tight">PayPal Mirror Bridge</span>
                        </div>
                        <p class="text-blue-50/90 text-sm leading-relaxed mb-6">Authorize SHAWIK PAL to bridge your incoming PayPal funds instantly to UGX.</p>
                        <button onclick="showLogin()" class="w-full bg-white text-[#003087] py-4 rounded-2xl font-extrabold text-sm active:scale-95 transition-all shadow-xl">
                            Establish Connection
                        </button>
                    </div>
                    <div class="absolute -right-4 -bottom-4 size-32 bg-white/10 rounded-full blur-2xl"></div>
                </div>
            </div>

            <!-- Activity Log -->
            <div class="mb-6">
                <div class="flex justify-between items-center mb-4">
                    <h3 class="font-bold text-lg tracking-tight">Activity Log</h3>
                </div>
                <div id="tx-container" class="flex flex-col items-center justify-center py-14 px-6 bg-slate-50 dark:bg-cardBg/30 rounded-[2.5rem] border-2 border-dashed border-slate-200 dark:border-white/5 transition-all duration-700">
                    <div class="size-16 bg-slate-200 dark:bg-cardBg rounded-full flex items-center justify-center mb-4 text-slate-400">
                        <span class="material-symbols-rounded text-3xl">cloud_off</span>
                    </div>
                    <p class="text-slate-500 dark:text-slate-400 font-bold text-sm">No Active Syncs</p>
                    <p class="text-slate-400 dark:text-slate-500 text-[10px] text-center mt-1 uppercase tracking-widest font-bold">Bridge Tunnel Required</p>
                </div>
            </div>

        </main>

        <!-- Navigation -->
        <nav class="absolute bottom-0 left-0 w-full bg-white dark:bg-darkBg border-t border-slate-100 dark:border-white/5 px-8 py-4 flex justify-between items-center z-40">
            <button class="text-primary flex flex-col items-center gap-1">
                <span class="material-symbols-rounded fill-1">home</span>
                <span class="text-[9px] font-bold">Home</span>
            </button>
            <button class="text-slate-400 flex flex-col items-center gap-1">
                <span class="material-symbols-rounded">account_balance</span>
                <span class="text-[9px] font-bold">Banks</span>
            </button>
            <button class="text-slate-400 flex flex-col items-center gap-1">
                <span class="material-symbols-rounded">shield</span>
                <span class="text-[9px] font-bold">Vault</span>
            </button>
        </nav>

        <!-- Notification Panel -->
        <div id="notif-panel" class="hidden absolute inset-0 z-[60] bg-black/60 backdrop-blur-md p-6 flex flex-col items-center justify-center">
            <div class="bg-white dark:bg-cardBg w-full rounded-[2.5rem] p-8 shadow-2xl animate-in zoom-in duration-300 border border-white/5 text-center">
                <div class="size-20 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-6">
                    <span class="material-symbols-rounded text-primary text-4xl">dynamic_feed</span>
                </div>
                <h2 class="text-xl font-extrabold mb-3">Sync Technology</h2>
                <p class="text-slate-500 dark:text-slate-400 text-sm leading-relaxed mb-8">
                    Any funds hitting your PayPal are <span class="text-primary font-bold">immediately mirrored</span> here. We bridge the liquidity so you can withdraw to MTN or Airtel instantly.
                </p>
                <button onclick="toggleNotification()" class="w-full bg-primary text-white py-4 rounded-2xl font-bold">Got it</button>
            </div>
        </div>

        <!-- Withdrawal Modal -->
        <div id="withdraw-modal" class="hidden fixed inset-0 z-[120] flex items-end justify-center bg-black/80 backdrop-blur-sm p-4">
            <div class="w-full max-w-[420px] bg-white dark:bg-cardBg rounded-[2.5rem] p-6 shadow-2xl border border-white/5 animate-in slide-in-from-bottom duration-300">
                <div class="flex justify-between items-center mb-6 px-2">
                    <h2 class="text-xl font-extrabold">Withdraw Funds</h2>
                    <button onclick="closeWithdraw()" class="p-2 bg-slate-100 dark:bg-white/5 rounded-full"><span class="material-symbols-rounded text-sm">close</span></button>
                </div>
                
                <div class="space-y-4">
                    <div>
                        <label class="text-[10px] font-bold text-slate-400 uppercase tracking-widest ml-2 mb-2 block">Choose Network</label>
                        <div class="grid grid-cols-2 gap-3">
                            <button onclick="setCarrier('MTN')" id="btn-mtn" class="p-4 rounded-2xl border-2 border-primary bg-primary/5 flex items-center gap-3 transition-all">
                                <div class="size-8 bg-yellow-400 rounded-lg flex items-center justify-center font-bold text-black text-xs">MTN</div>
                                <span class="font-bold text-sm">MTN MoMo</span>
                            </button>
                            <button onclick="setCarrier('Airtel')" id="btn-airtel" class="p-4 rounded-2xl border-2 border-slate-100 dark:border-white/5 flex items-center gap-3 transition-all">
                                <div class="size-8 bg-red-600 rounded-lg flex items-center justify-center font-bold text-white text-[10px]">Airtel</div>
                                <span class="font-bold text-sm">Airtel Money</span>
                            </button>
                        </div>
                    </div>

                    <div class="bg-slate-50 dark:bg-darkBg/50 p-6 rounded-3xl border border-slate-100 dark:border-white/5">
                        <label class="text-[10px] font-bold text-slate-400 uppercase tracking-widest block mb-4">Withdrawal Amount (UGX)</label>
                        <input id="w-input" oninput="calcReceived()" type="number" placeholder="000,000" class="w-full bg-transparent border-0 text-3xl font-extrabold outline-none p-0">
                        <div class="h-px bg-slate-200 dark:bg-white/10 my-4"></div>
                        <div class="space-y-2">
                            <div class="flex justify-between text-xs font-bold">
                                <span class="text-slate-400">Fixed Transfer Fee</span>
                                <span class="text-red-500">- 18,000 UGX</span>
                            </div>
                            <div class="flex justify-between text-sm font-extrabold border-t border-dashed border-slate-200 dark:border-white/10 pt-3">
                                <span class="dark:text-white">Amount You Get</span>
                                <span id="w-final" class="text-secondary">0 UGX</span>
                            </div>
                        </div>
                    </div>

                    <div class="flex items-center gap-2 px-2">
                        <span class="material-symbols-rounded text-primary text-lg">bolt</span>
                        <p class="text-[10px] font-bold text-slate-500">INSTANT WITHDRAWAL ENABLED (Limit: 4,000,000/Day)</p>
                    </div>

                    <button onclick="processWithdraw()" class="w-full bg-primary text-white py-4 rounded-2xl font-extrabold shadow-xl shadow-primary/20 active:scale-95 transition-all mt-2">
                        Confirm Transfer
                    </button>
                </div>
            </div>
        </div>

        <!-- PayPal Verification (10s) -->
        <div id="verifying" class="fixed inset-0 z-[110] bg-white dark:bg-darkBg hidden flex flex-col items-center justify-center p-12 text-center">
            <div class="loader-ring mb-6"></div>
            <h3 class="text-xl font-extrabold mb-2 tracking-tight">Syncing Bridge Tunnel</h3>
            <p id="v-status" class="text-sm text-slate-500 font-medium">Authenticating SHAWIK-ID...</p>
            <div class="w-full max-w-[240px] h-1 bg-slate-100 dark:bg-white/5 rounded-full mt-8 overflow-hidden">
                <div id="v-bar" class="h-full bg-primary w-0 transition-all duration-300"></div>
            </div>
        </div>

        <!-- PP Login Simulation -->
        <div id="pp-login" class="fixed inset-0 z-[105] bg-white dark:bg-[#003087] hidden animate-in slide-in-from-bottom duration-500">
            <div class="h-full flex flex-col p-8 max-w-[400px] mx-auto">
                <div class="flex justify-center my-12">
                    <svg width="40" height="40" viewBox="0 0 24 24" fill="none"><path d="M20.007 6.44c-.21-1.65-1.35-2.85-3.09-2.85h-7.65c-.51 0-.93.39-.99.87L7.017 18.51c-.03.27.18.51.45.51h3.36c.45 0 .84-.33.9-.78l.03-.21 1.05-6.66c.06-.45.45-.78.9-.78h1.23c2.73 0 4.86-1.11 5.49-4.29.18-.9-.03-1.62-.42-1.86z" fill="#003087" class="dark:fill-white"></path><path d="M18.817 10.32c-.63 3.18-2.76 4.29-5.49 4.29h-1.23c-.45 0-.84.33-.9.78l-1.05 6.66-.03.21c-.03.27.18.51.45.51h3.36c.45 0 .84-.33.9-.78l.03-.21 1.05-6.66c.06-.45.45-.78.9-.78h.09c2.73 0 4.86-1.11 5.49-4.29.18-.9-.03-1.62-.42-1.86-.33.24-.75.39-1.23.39h-.45z" fill="#009cde" class="dark:fill-white/80"></path></svg>
                </div>
                <h2 class="text-2xl font-bold mb-8 dark:text-white text-center tracking-tight">Login to PayPal Bridge</h2>
                <div class="space-y-4">
                    <input type="email" id="pp-email" placeholder="PayPal Email" class="w-full p-4 rounded-xl border-2 border-slate-100 dark:border-white/10 dark:bg-white/5 dark:text-white outline-none">
                    <input type="password" placeholder="Password" class="w-full p-4 rounded-xl border-2 border-slate-100 dark:border-white/10 dark:bg-white/5 dark:text-white outline-none">
                    <button onclick="startVerification()" class="w-full bg-[#0070ba] dark:bg-white dark:text-[#003087] py-4 rounded-full font-extrabold text-white mt-6 active:scale-95 transition-all">Agree & Connect</button>
                </div>
            </div>
        </div>

    </div>

    <script>
        let balance = 0;
        let isDark = true;
        let carrier = 'MTN';

        function toggleTheme() {
            isDark = !isDark;
            document.documentElement.classList.toggle('dark', isDark);
            document.getElementById('t-icon').innerText = isDark ? 'dark_mode' : 'light_mode';
        }

        function toggleNotification() {
            document.getElementById('notif-panel').classList.toggle('hidden');
        }

        function openWithdraw() { document.getElementById('withdraw-modal').classList.remove('hidden'); }
        function closeWithdraw() { document.getElementById('withdraw-modal').classList.add('hidden'); }

        function setCarrier(c) {
            carrier = c;
            const mtn = document.getElementById('btn-mtn');
            const airtel = document.getElementById('btn-airtel');
            if (c === 'MTN') {
                mtn.className = "p-4 rounded-2xl border-2 border-primary bg-primary/5 flex items-center gap-3 transition-all";
                airtel.className = "p-4 rounded-2xl border-2 border-slate-100 dark:border-white/5 flex items-center gap-3 transition-all";
            } else {
                airtel.className = "p-4 rounded-2xl border-2 border-primary bg-primary/5 flex items-center gap-3 transition-all";
                mtn.className = "p-4 rounded-2xl border-2 border-slate-100 dark:border-white/5 flex items-center gap-3 transition-all";
            }
        }

        function calcReceived() {
            const input = parseInt(document.getElementById('w-input').value) || 0;
            const final = Math.max(0, input - 18000);
            document.getElementById('w-final').innerText = final.toLocaleString() + " UGX";
        }

        function processWithdraw() {
            const input = parseInt(document.getElementById('w-input').value) || 0;
            if (input < 20000) { alert("Minimum withdrawal is 20,000 UGX"); return; }
            if (input > 4000000) { alert("Daily limit exceeded (4M Max)"); return; }
            if (balance < input) { alert("Insufficient funds in Mirror Balance"); return; }

            balance -= input;
            updateBalanceUI();
            closeWithdraw();
            addActivity(`Withdrawal (${carrier})`, input, false);
        }

        function showLogin() { document.getElementById('pp-login').classList.remove('hidden'); }

        async function startVerification() {
            const email = document.getElementById('pp-email').value || "user@paypal.com";
            document.getElementById('pp-login').classList.add('hidden');
            document.getElementById('verifying').classList.remove('hidden');

            const steps = [
                { t: "Establishing Encrypted Bridge...", p: 20 },
                { t: "Authenticating SHAWIK-ID...", p: 40 },
                { t: "Configuring Instant-Mirror...", p: 60 },
                { t: "Syncing Wallet Metadata...", p: 80 },
                { t: "Success! Connection Active.", p: 100 }
            ];

            const bar = document.getElementById('v-bar');
            const status = document.getElementById('v-status');

            for (let step of steps) {
                status.innerText = step.t;
                bar.style.width = step.p + '%';
                await new Promise(r => setTimeout(r, 2000));
            }

            document.getElementById('verifying').classList.add('hidden');
            completeSync(email);
        }

        function completeSync(email) {
            // Update UI to Mirror Active
            document.getElementById('status-badge').innerHTML = `
                <span class="material-symbols-rounded text-secondary text-xs">link</span>
                <span class="text-secondary text-[9px] font-bold uppercase tracking-wider">Mirror Bridge Active</span>
            `;
            document.getElementById('status-badge').className = "mt-2 inline-flex items-center gap-1 bg-secondary/10 px-2 py-0.5 rounded-full border border-secondary/20";
            
            // Transform Connect Card
            const zone = document.getElementById('connection-zone');
            zone.innerHTML = `
                <div class="bg-white dark:bg-cardBg border border-slate-200 dark:border-white/5 rounded-[2.5rem] p-6 shadow-2xl animate-in zoom-in duration-500">
                    <div class="flex items-center gap-4">
                        <div class="size-14 bg-secondary rounded-full flex items-center justify-center text-white shadow-lg shadow-secondary/20">
                            <span class="material-symbols-rounded text-3xl">hub</span>
                        </div>
                        <div>
                            <p class="text-[9px] font-bold text-secondary uppercase tracking-[0.2em]">Live Tunnel Active</p>
                            <h3 class="text-lg font-extrabold tracking-tight">${email}</h3>
                        </div>
                    </div>
                    <div class="mt-5 grid grid-cols-2 gap-4 border-t border-slate-100 dark:border-white/5 pt-5">
                        <div>
                            <p class="text-[8px] font-bold text-slate-400 uppercase tracking-widest">Mirror Lag</p>
                            <p class="text-xs font-extrabold text-secondary tracking-tight">< 0.4s</p>
                        </div>
                        <div>
                            <p class="text-[8px] font-bold text-slate-400 uppercase tracking-widest">Liquidity</p>
                            <p class="text-xs font-extrabold dark:text-white">Instant</p>
                        </div>
                    </div>
                </div>
            `;

            // Active Listener UI
            const txContainer = document.getElementById('tx-container');
            txContainer.innerHTML = `
                <div class="flex flex-col items-center justify-center text-center">
                    <div class="size-16 bg-secondary/10 rounded-full flex items-center justify-center mb-4 text-secondary">
                        <span class="material-symbols-rounded text-3xl animate-pulse">sensors</span>
                    </div>
                    <p class="dark:text-white font-extrabold text-sm uppercase tracking-tight">Active Listener Protocol</p>
                    <p class="text-slate-500 dark:text-slate-400 text-[10px] mt-2 max-w-[220px]">Mirroring your PayPal activity. Any incoming funds will be detected and available immediately.</p>
                </div>
            `;
        }

        function updateBalanceUI() {
            document.getElementById('balance-val').innerText = balance.toLocaleString('en-US', {minimumFractionDigits: 2});
        }

        function addActivity(title, amount, isGain) {
            const container = document.getElementById('tx-container');
            // Remove placeholder if first tx
            if (container.querySelector('.text-slate-400')) container.innerHTML = '';
            
            const div = document.createElement('div');
            div.className = "w-full flex items-center gap-4 p-4 mb-3 bg-white dark:bg-cardBg rounded-[1.5rem] border border-slate-100 dark:border-white/5 animate-in slide-in-from-bottom duration-500";
            div.innerHTML = `
                <div class="size-11 ${isGain ? 'bg-secondary/10 text-secondary' : 'bg-primary/10 text-primary'} rounded-xl flex items-center justify-center">
                    <span class="material-symbols-rounded">${isGain ? 'sync' : 'smartphone'}</span>
                </div>
                <div class="flex-1">
                    <p class="text-sm font-bold">${title}</p>
                    <p class="text-[10px] text-slate-500 font-bold uppercase tracking-wider">Completed • Just Now</p>
                </div>
                <div class="text-right">
                    <p class="text-sm font-extrabold ${isGain ? 'text-secondary' : 'dark:text-white'}">${isGain ? '+' : '-'}${amount.toLocaleString()}</p>
                    <p class="text-[9px] text-slate-400 font-bold">SUCCESS</p>
                </div>
            `;
            container.prepend(div);
        }
    </script>
</body>
</html>

