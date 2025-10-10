<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ur bro pathan — Stylish Text Generator</title>
<style>
body { margin:0; font-family:'Inter',sans-serif; background:#0f172a; color:#f1f5f9; min-height:100vh; display:flex; justify-content:center; align-items:flex-start; padding:20px; }
.container { width:100%; max-width:960px; }
h1 { text-align:center; font-size:26px; margin-bottom:8px; }
p { text-align:center; color:#94a3b8; margin-top:0; margin-bottom:20px; font-size:15px; }
textarea { width:100%; min-height:100px; padding:12px; border-radius:8px; background:#1e293b; color:white; border:none; font-size:16px; margin-bottom:20px; resize:none; }
.styles { display:grid; grid-template-columns:repeat(auto-fit, minmax(220px,1fr)); gap:10px; }
.style { background:#1e293b; padding:10px 12px; border-radius:10px; cursor:pointer; transition:0.2s; font-size:16px; word-break:break-word; text-align:center; min-height:40px; display:flex; justify-content:center; align-items:center; }
.style:hover { background:#334155; transform:scale(1.02); }
.footer { text-align:center; color:#94a3b8; margin-top:20px; font-size:13px; }
.wa-btn { position: fixed; bottom: 20px; right: 20px; background-color: #25D366; border-radius: 50%; width: 60px; height: 60px; display: flex; justify-content: center; align-items: center; box-shadow: 0 4px 10px rgba(0,0,0,0.3); cursor: pointer; z-index: 1000; transition: transform 0.2s ease; }
.wa-btn:hover { transform: scale(1.1); }
.wa-btn img { width: 35px; height: 35px; }
@media (max-width:600px) { .style { font-size:14px; min-height:35px; } textarea { font-size:14px; } h1 { font-size:22px; } p { font-size:13px; } }
</style>
</head>
<body>
<div class="container">
<h1>ur bro pathan — Stylish Text Generator</h1>
<p>Type your text below and tap any style to copy instantly!</p>
<textarea id="input">Hello from ur bro pathan</textarea>
<div class="styles" id="stylesList"></div>
<div class="footer">Made by <strong>ur bro pathan</strong></div>
</div>
<a href="https://wa.me/447877486623" target="_blank" class="wa-btn" title="Chat on WhatsApp">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
</a>
<script>
const input = document.getElementById('input');
const stylesList = document.getElementById('stylesList');

const fancyMaps = {
  bold:{'a':'𝗮','b':'𝗯','c':'𝗰','d':'𝗱','e':'𝗲','f':'𝗳','g':'𝗴','h':'𝗵','i':'𝗶','j':'𝗷','k':'𝗸','l':'𝗹','m':'𝗺','n':'𝗻','o':'𝗼','p':'𝗽','q':'𝗾','r':'𝗿','s':'𝘀','t':'𝘁','u':'𝘂','v':'𝘃','w':'𝘄','x':'𝘅','y':'𝘆','z':'𝘇','A':'𝗔','B':'𝗕','C':'𝗖','D':'𝗗','E':'𝗘','F':'𝗙','G':'𝗚','H':'𝗛','I':'𝗜','J':'𝗝','K':'𝗞','L':'𝗟','M':'𝗠','N':'𝗡','O':'𝗢','P':'𝗣','Q':'𝗤','R':'𝗥','S':'𝗦','T':'𝗧','U':'𝗨','V':'𝗩','W':'𝗪','X':'𝗫','Y':'𝗬','Z':'𝗭'},
  italic:{'a':'𝘢','b':'𝘣','c':'𝘤','d':'𝘥','e':'𝘦','f':'𝘧','g':'𝘨','h':'𝘩','i':'𝘪','j':'𝘫','k':'𝘬','l':'𝘭','m':'𝘮','n':'𝘯','o':'𝘰','p':'𝘱','q':'𝘲','r':'𝘳','s':'𝘴','t':'𝘵','u':'𝘶','v':'𝘷','w':'𝘸','x':'𝘹','y':'𝘺','z':'𝘻','A':'𝐴','B':'𝐵','C':'𝐶','D':'𝐷','E':'𝐸','F':'𝐹','G':'𝐺','H':'𝐻','I':'𝐼','J':'𝐽','K':'𝐾','L':'𝐿','M':'𝑀','N':'𝑁','O':'𝑂','P':'𝑃','Q':'𝑄','R':'𝑅','S':'𝑆','T':'𝑇','U':'𝑈','V':'𝑉','W':'𝑊','X':'𝑋','Y':'𝑌','Z':'𝑍'},
  smallCaps:{'a':'ᴀ','b':'ʙ','c':'ᴄ','d':'ᴅ','e':'ᴇ','f':'ꜰ','g':'ɢ','h':'ʜ','i':'ɪ','j':'ᴊ','k':'ᴋ','l':'ʟ','m':'ᴍ','n':'ɴ','o':'ᴏ','p':'ᴘ','q':'ǫ','r':'ʀ','s':'s','t':'ᴛ','u':'ᴜ','v':'ᴠ','w':'ᴡ','x':'x','y':'ʏ','z':'ᴢ'}
};

const emojiList=['🔥','✨','💫','💖','🌸','⭐','💥','🌟','❤️','💎','💀','🎯','🎉','🥶','⚡','🌈','🌻','🐉','💚','😎'];

// Function to map characters for fancy styles
function mapChars(text,map){ return text.split('').map(c=>map[c]||c).join(''); }

// 120+ styles dynamically replacing user text
const styles = [
t=>t, t=>t.toUpperCase(), t=>t.toLowerCase(),
t=>mapChars(t,fancyMaps.bold), t=>mapChars(t,fancyMaps.italic), t=>mapChars(t,fancyMaps.smallCaps),
t=>`♡ ${t} ♡`, t=>`❀ ${t} ❀`, t=>`▂▃▅▇█ ${t} █▇▅▃▂`,
t=>`(•_•) ${t} (•_•)`, t=>`¯\\_(ツ)_/¯ ${t} ¯\\_(ツ)_/¯`,
t=>`𐌄𐋄𐌀𐌌𐌐𐌋𐌄 ${t} 𐌕𐌄𐋄𐌕`,
t=>`▄︻デ ${t} ═══━一`, t=>`❀·ᰄ· ${t} ·ᰄ·❀`, t=>`❀ꗥ～ꗥ❀ ${t} ❀ꗥ～ꗥ❀`,
t=>`✨${t}✨`, t=>`💖${t}💖`, t=>`🌸${t}🌸`, t=>`⭐${t}⭐`, t=>`💥${t}💥`,
t=>`▁▂▃▄▅▆▇█ ${t} █▇▆▅▄▃▂▁`,
t=>`•°•.°• ${t} •°•.°•`, t=>`❁❀❁ ${t} ❁❀❁`,
t=>`★彡 ${t} 彡★`, t=>`✿✾✿ ${t} ✿✾✿`, t=>`♡✧ ${t} ✧♡`, t=>`♪♫ ${t} ♫♪`,
...emojiList.map(e=>t=>`${e} ${t} ${e}`)
];

// Update all styles when typing
function update(){
stylesList.innerHTML='';
const val = input.value || 'Hello from ur bro pathan';
styles.forEach(fn=>{
const div=document.createElement('div');
div.className='style';
div.textContent=fn(val);
div.addEventListener('click',()=>{
navigator.clipboard.writeText(div.textContent).then(()=>{
div.style.background='#10b981';
setTimeout(()=>div.style.background='#1e293b',600);
}).catch(()=>alert('Copy failed'));
});
stylesList.appendChild(div);
});
}

input.addEventListener('input', update);
update();
</script>
</body>
</html>
