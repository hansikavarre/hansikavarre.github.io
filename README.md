<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Hansika Varre | Portfolio</title>
<style>
:root{
  --bg:#0A0A0A;
  --blue:#007BA7;
  --pink:#FF2D95;
  --card:#141414;
  --line:#262626;
  --text:#F2F2F2;
  --muted:#A0A0A0;
  --blue-soft:#3FB6E0;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:'Segoe UI',system-ui,sans-serif;line-height:1.7}
a{color:var(--blue-soft);text-decoration:none}
a:hover{color:var(--pink)}
.wrap{max-width:1000px;margin:0 auto;padding:0 24px}
section{padding:80px 0}
h2{font-size:2rem;color:var(--blue);margin-bottom:28px}
h2::after{content:"";display:block;width:56px;height:3px;background:var(--pink);margin-top:10px;border-radius:2px}

/* nav */
nav{position:sticky;top:0;z-index:10;background:rgba(10,10,10,.92);border-bottom:1px solid var(--line)}
nav .wrap{display:flex;justify-content:space-between;align-items:center;height:60px}
.logo{font-weight:800;color:var(--text);font-size:1.15rem}
.logo span{color:var(--pink)}
nav ul{display:flex;gap:22px;list-style:none;flex-wrap:wrap}
nav ul a{color:var(--muted);font-size:.95rem}
nav ul a:hover{color:var(--pink)}

/* home */
#home{padding:100px 0 80px}
#home .wrap{display:grid;grid-template-columns:1.3fr 1fr;gap:40px;align-items:center}
#home h1{font-size:clamp(2.2rem,6vw,3.6rem);line-height:1.15}
#home h1 span{color:var(--blue)}
#home p{color:var(--muted);margin:18px 0 26px}
.btn{display:inline-block;padding:12px 26px;border-radius:8px;background:var(--blue);color:#fff;border:2px solid var(--blue);transition:.2s;margin-right:10px}
.btn:hover{background:var(--pink);border-color:var(--pink);color:#fff}
.btn.ghost{background:transparent;color:var(--text);border-color:var(--blue)}
.photo{justify-self:center;width:min(280px,80vw);aspect-ratio:1/1.1;border:3px solid var(--blue);border-radius:20px;box-shadow:12px 12px 0 var(--pink);overflow:hidden;background:var(--card);display:grid;place-items:center}
.photo img{width:100%;height:100%;object-fit:cover}

/* about */
.about-grid{display:grid;grid-template-columns:1.3fr 1fr;gap:36px}
.about-grid p{color:#cfcfcf}
.stats{display:grid;gap:14px}
.stat{background:var(--card);border:1px solid var(--line);border-left:4px solid var(--pink);border-radius:10px;padding:16px 20px}
.stat b{font-size:1.8rem;color:var(--blue);display:block}
.stat span{color:var(--muted);font-size:.92rem}

/* experience card with hover pop */
.exp{position:relative;background:var(--card);border:1px solid var(--line);border-left:4px solid
