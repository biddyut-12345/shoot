:root{--bg:#0b1220;--panel:#111827;--accent:#ffdd57;--muted:#9ca3af}
*{box-sizing:border-box;font-family:Inter,Segoe UI,Arial,San-serif}
html,body{height:100%;margin:0}
body{background:linear-gradient(180deg,var(--bg),#071022);color:#fff;overflow:hidden}
#gameCanvas{display:block;background:linear-gradient(#0b1b2a,#08111a);width:100vw;height:100vh}
#ui{position:fixed;left:12px;top:12px;z-index:10;display:flex;gap:10px;align-items:center}
#score,#lives{background:rgba(0,0,0,0.4);padding:6px 10px;border-radius:6px;font-weight:600}
#startBtn{padding:6px 10px;border-radius:6px;border:0;background:var(--accent);color:#111;font-weight:700;cursor:pointer}
#startBtn:active{transform:translateY(1px)}

.centerMsg{position:fixed;left:50%;top:50%;transform:translate(-50%,-50%);color:var(--accent);font-size:20px;text-align:center}
