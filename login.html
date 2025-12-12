<!doctype html>
<html>
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width,initial-scale=1"/>
  <title>Astrologer Login</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,#f6f7fb,#f0f2f5);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial}
    .card{width:100%;max-width:420px;background:white;border-radius:14px;padding:28px;box-shadow:0 10px 30px rgba(11,17,30,.08);border:1px solid rgba(10,10,10,0.03)}
    h1{margin:0 0 8px;font-size:20px}
    .muted{color:#6b7280;font-size:13px;margin-bottom:16px}
    label{display:block;font-size:13px;color:#374151;margin-top:8px}
    input{width:100%;padding:10px 12px;border-radius:10px;border:1px solid #e6e6e6;margin-top:6px;font-size:15px;box-sizing:border-box}
    .btn{display:inline-block;margin-top:18px;padding:10px 14px;background:linear-gradient(90deg,#fb8b55,#f8cfa7);border-radius:999px;color:#111;border:0;font-weight:700;cursor:pointer}
    .error{color:#b91c1c;margin-top:10px;font-size:13px;display:none}
    .small{font-size:12px;color:#6b7280;margin-top:12px}
  </style>
</head>
<body>
  <div class="card" role="main" aria-labelledby="title">
    <h1 id="title">Astrologer Login</h1>
    <div class="muted">Sign in with your astrologer account</div>

    <label for="user">Username</label>
    <input id="user" autocomplete="username" placeholder="Gautam">

    <label for="pass">Password</label>
    <input id="pass" type="password" autocomplete="current-password" placeholder="••••••••">

    <div><button id="login" class="btn">Sign in</button></div>
    <div id="err" class="error">Invalid credentials</div>
    <div class="small">Tip: initial account — username <strong>Gautam</strong> password <strong>Gautam12</strong></div>
  </div>

<script>
/*
 Simple client-side auth for static dashboard.
 Users are stored in the USERS object (username => password).
 It's easy to add users by editing this file.
*/
const USERS = {
  "Gautam": "Gautam12"
};

const userInput = document.getElementById('user');
const passInput = document.getElementById('pass');
const loginBtn = document.getElementById('login');
const err = document.getElementById('err');

function setSession(username){
  localStorage.setItem('astro_session', JSON.stringify({ user: username, ts: Date.now() }));
  // go to dashboard
  window.location.href = './dashboard.html';
}

loginBtn.addEventListener('click', ()=>{
  const u = (userInput.value || '').trim();
  const p = (passInput.value || '').trim();
  if(!u || !p){ err.textContent='Enter username and password'; err.style.display='block'; return; }
  if(USERS[u] && USERS[u] === p){
    err.style.display='none';
    setSession(u);
  } else {
    err.textContent='Invalid username or password';
    err.style.display='block';
  }
});

// allow enter to submit
passInput.addEventListener('keydown', (e)=>{ if(e.key==='Enter') loginBtn.click(); });

// if already logged in, redirect to dashboard
(function(){
  try{
    const s = JSON.parse(localStorage.getItem('astro_session')||'null');
    if(s && s.user && USERS[s.user]){ window.location.href = './dashboard.html'; }
  } catch(e){}
})();
</script>
</body>
</html>
