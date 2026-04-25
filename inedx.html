<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
<title>پخش شبکه تلویزیونی</title>
<style>
html, body { margin:0; padding:0; width:100%; height:100%; background:black; font-family:Tahoma, sans-serif; display:flex; justify-content:center; align-items:center; overflow:hidden; }
#startScreen { position:absolute; width:100%; height:100%; background:black; display:flex; justify-content:center; align-items:center; flex-direction:column; z-index:50; }
#startBtn { padding:12px 24px; font-size:20px; font-weight:bold; color:white; background:#007bff; border:none; border-radius:8px; cursor:pointer; transition:0.3s; }
#startBtn:hover { background:#0056b3; }
#tvWrapper { display:none; position: relative; width:95vw; max-width:960px; aspect-ratio:16/9; transition: all 0.5s ease; }
#tvScreen { width:100%; height:100%; background:black; border:2px solid white; border-radius:16px; box-shadow:0 0 30px rgba(255,255,255,0.4); overflow:hidden; position:relative; }
video { width:100%; height:100%; object-fit:contain; }
#logo { position:absolute; top:10px; right:10px; height:45px; opacity:0.75; z-index:10; transition: all 0.5s ease; }
#liveText { position:absolute; top:calc(10px + 45px); right:10px; width:45px; text-align:center; color:white; font-size:12px; font-weight:bold; z-index:10; transition: all 0.5s ease; }
#iconLeft { position:absolute; top:10px; left:10px; height:35px; z-index:10; transition: all 0.5s ease; }
#iconLeft video { width:auto; height:100%; object-fit:cover; }
#subtitle { position:absolute; bottom:0; left:0; width:100%; height:32px; background: rgba(0,0,0,0.65); display:flex; align-items:center; overflow:hidden; z-index:20; border-radius:0 0 16px 16px; transition: all 0.5s ease; }
#scrollText { display:inline-block; white-space:nowrap; padding-left:100%; animation: scrollLeftToRight 18s linear infinite; color:white; font-size:14px; font-weight:bold; transition: all 0.5s ease; }
@keyframes scrollLeftToRight { 0% { transform: translateX(-100%); } 100% { transform: translateX(100%); } }
#rotateBtn { position:absolute; bottom:8px; right:8px; width:20px; height:20px; font-size:14px; border:none; border-radius:4px; background:#007bff; color:white; cursor:pointer; z-index:30; display:flex; justify-content:center; align-items:center; transition: all 0.5s ease; }
</style>
</head>
<body>

<div id="startScreen">
  <button id="startBtn">پخش شبکه</button>
</div>

<div id="tvWrapper">
  <div id="tvScreen">
    <video id="tvVideo" autoplay playsinline></video>
    <img id="logo" src="https://s6.uupload.ir/files/inshot_۲۰۲۵۰۸۱۰_۰۴۳۶۳۷۷۴۰_9t33.png" alt="لوگو">
    <div id="liveText"></div>
    <div id="iconLeft">
      <video autoplay loop muted playsinline>
        <source src="https://s6.uupload.ir/filelink/HhSgH3Fw9iSW_87fba98eb7/inshot_۲۰۲۵۰۸۱۳_۲۲۰۵۰۲۶۱۰_leeu.mp4" type="video/mp4">
      </video>
    </div>
    <div id="subtitle">
      <div id="scrollText">با افتخار میزبان شما در پخش شبکه تلویزیونی اینترنتی اهوازما  | شبکه اینترنتی اهوازما با افتخار ویژه مردم کلانشهر اهواز،حمیدیه، باوی و سایر مردم خوزستان در عرصه رسانه اینترنتی خدمتگزاری میکند  </div>
    </div>
  </div>
  <button id="rotateBtn">🔲</button>
</div>

<script>
const startScreen = document.getElementById('startScreen');
const startBtn = document.getElementById('startBtn');
const tvWrapper = document.getElementById('tvWrapper');
const tvVideo = document.getElementById('tvVideo');
const rotateBtn = document.getElementById('rotateBtn');
let expanded = false;

// 20 ردیف زماندار (Manual)
const scheduledPlaylist = [
  {title:"زماندار 1", src:"https://example.com/scheduled1.mp4", startTime:"00:00:00", duration:00},
  {title:"زماندار 2", src:"https://example.com/scheduled2.mp4", startTime:"01:00:00", duration:00},
  {title:"زماندار 3", src:"https://example.com/scheduled3.mp4", startTime:"02:00:00", duration:00},
  {title:"زماندار 4", src:"https://example.com/scheduled4.mp4", startTime:"03:00:00", duration:00},
  {title:"زماندار 5", src:"https://example.com/scheduled5.mp4", startTime:"04:00:00", duration:00},
  {title:"زماندار 6", src:"https://example.com/scheduled6.mp4", startTime:"05:00:00", duration:00},
  {title:"زماندار 7", src:"https://example.com/scheduled7.mp4", startTime:"06:00:00", duration:00},
  {title:"زماندار 8", src:"https://example.com/scheduled8.mp4", startTime:"07:00:00", duration:00},
  {title:"زماندار 9", src:"https://example.com/scheduled9.mp4", startTime:"08:00:00", duration:00},
  {title:"زماندار 10", src:"https://example.com/scheduled10.mp4", startTime:"09:00:00", duration:00},
  {title:"زماندار 11", src:"https://example.com/scheduled11.mp4", startTime:"10:00:00", duration:00},
  {title:"زماندار 12", src:"https://example.com/scheduled12.mp4", startTime:"11:00:00", duration:00},
  {title:"زماندار 13", src:"https://example.com/scheduled13.mp4", startTime:"12:00:00", duration:00},
  {title:"زماندار 14", src:"https://example.com/scheduled14.mp4", startTime:"13:00:00", duration:00},
  {title:"زماندار 15", src:"https://example.com/scheduled15.mp4", startTime:"14:00:00", duration:00},
  {title:"زماندار 16", src:"https://example.com/scheduled16.mp4", startTime:"15:00:00", duration:00},
  {title:"زماندار 17", src:"https://example.com/scheduled17.mp4", startTime:"16:00:00", duration:00},
  {title:"زماندار 18", src:"https://example.com/scheduled18.mp4", startTime:"17:00:00", duration:00},
  {title:"زماندار 19", src:"https://example.com/scheduled19.mp4", startTime:"18:00:00", duration:00},
  {title:"زماندار 20", src:"https://example.com/scheduled20.mp4", startTime:"19:00:00", duration:00}
];

// 60 ردیف متغیر / زنجیره‌ای (Manual)
const chainPlaylist = [
  {title:"متغیر 1", src:"https://s6.uupload.ir/filelink/AOMCIOSSIsIN_8cc65cbf00/inshot_۲۰۲۵۰۹۲۶_۱۵۰۰۱۷۸۵۰_izbp.mp4", duration:39},
  {title:"متغیر 2", src:"https://example.com/chain2.mp4", duration:00},
  {title:"متغیر 3", src:"https://example.com/chain3.mp4", duration:00},
  {title:"متغیر 4", src:"https://example.com/chain4.mp4", duration:00},
  {title:"متغیر 5", src:"https://example.com/chain5.mp4", duration:00},
  {title:"متغیر 6", src:"https://example.com/chain6.mp4", duration:00},
  {title:"متغیر 7", src:"https://example.com/chain7.mp4", duration:00},
  {title:"متغیر 8", src:"https://example.com/chain8.mp4", duration:00},
  {title:"متغیر 9", src:"https://example.com/chain9.mp4", duration:00},
  {title:"متغیر 10", src:"https://example.com/chain10.mp4", duration:00},
  {title:"متغیر 11", src:"https://example.com/chain11.mp4", duration:00},
  {title:"متغیر 12", src:"https://example.com/chain12.mp4", duration:00},
  {title:"متغیر 13", src:"https://example.com/chain13.mp4", duration:00},
  {title:"متغیر 14", src:"https://example.com/chain14.mp4", duration:00},
  {title:"متغیر 15", src:"https://example.com/chain15.mp4", duration:00},
  {title:"متغیر 16", src:"https://example.com/chain16.mp4", duration:00},
  {title:"متغیر 17", src:"https://example.com/chain17.mp4", duration:00},
  {title:"متغیر 18", src:"https://example.com/chain18.mp4", duration:00},
  {title:"متغیر 19", src:"https://example.com/chain19.mp4", duration:00},
  {title:"متغیر 20", src:"https://example.com/chain20.mp4", duration:00},
  {title:"متغیر 21", src:"https://example.com/chain21.mp4", duration:00},
  {title:"متغیر 22", src:"https://example.com/chain22.mp4", duration:00},
  {title:"متغیر 23", src:"https://example.com/chain23.mp4", duration:00},
  {title:"متغیر 24", src:"https://example.com/chain24.mp4", duration:00},
  {title:"متغیر 25", src:"https://example.com/chain25.mp4", duration:00},
  {title:"متغیر 26", src:"https://example.com/chain26.mp4", duration:00},
  {title:"متغیر 27", src:"https://example.com/chain27.mp4", duration:00},
  {title:"متغیر 28", src:"https://example.com/chain28.mp4", duration:00},
  {title:"متغیر 29", src:"https://example.com/chain29.mp4", duration:00},
  {title:"متغیر 30", src:"https://example.com/chain30.mp4", duration:00},
  {title:"متغیر 31", src:"https://example.com/chain31.mp4", duration:00},
  {title:"متغیر 32", src:"https://example.com/chain32.mp4", duration:00},
  {title:"متغیر 33", src:"https://example.com/chain33.mp4", duration:00},
  {title:"متغیر 34", src:"https://example.com/chain34.mp4", duration:00},
  {title:"متغیر 35", src:"https://example.com/chain35.mp4", duration:00},
  {title:"متغیر 36", src:"https://example.com/chain36.mp4", duration:00},
  {title:"متغیر 37", src:"https://example.com/chain37.mp4", duration:00},
  {title:"متغیر 38", src:"https://example.com/chain38.mp4", duration:00},
  {title:"متغیر 39", src:"https://example.com/chain39.mp4", duration:00},
  {title:"متغیر 40", src:"https://example.com/chain40.mp4", duration:00},
  {title:"متغیر 41", src:"https://example.com/chain41.mp4", duration:00},
  {title:"متغیر 42", src:"https://example.com/chain42.mp4", duration:00},
  {title:"متغیر 43", src:"https://example.com/chain43.mp4", duration:00},
  {title:"متغیر 44", src:"https://example.com/chain44.mp4", duration:00},
  {title:"متغیر 45", src:"https://example.com/chain45.mp4", duration:00},
  {title:"متغیر 46", src:"https://example.com/chain46.mp4", duration:00},
  {title:"متغیر 47", src:"https://example.com/chain47.mp4", duration:00},
  {title:"متغیر 48", src:"https://example.com/chain48.mp4", duration:00},
  {title:"متغیر 49", src:"https://example.com/chain49.mp4", duration:00},
  {title:"متغیر 50", src:"https://example.com/chain50.mp4", duration:00},
  {title:"متغیر 51", src:"https://example.com/chain51.mp4", duration:00},
  {title:"متغیر 52", src:"https://example.com/chain52.mp4", duration:00},
  {title:"متغیر 53", src:"https://example.com/chain53.mp4", duration:00},
  {title:"متغیر 54", src:"https://example.com/chain54.mp4", duration:00},
  {title:"متغیر 55", src:"https://example.com/chain55.mp4", duration:00},
  {title:"متغیر 56", src:"https://example.com/chain56.mp4", duration:00},
  {title:"متغیر 57", src:"https://example.com/chain57.mp4", duration:00},
  {title:"متغیر 58", src:"https://example.com/chain58.mp4", duration:00},
  {title:"متغیر 59", src:"https://example.com/chain59.mp4", duration:00},
  {title:"متغیر 60", src:"https://example.com/chain60.mp4", duration:00}
];

function getTimestampForToday(hhmmss){
  const [hh, mm, ss] = hhmmss.split(":").map(Number);
  const now = new Date();
  return new Date(now.getFullYear(), now.getMonth(), now.getDate(), hh, mm, ss).getTime();
}

function getCurrentScheduled(){
  const now = Date.now();
  for(let vid of scheduledPlaylist){
    const start = getTimestampForToday(vid.startTime);
    const end = start + vid.duration*1000;
    if(now>=start && now<end) return {...vid, elapsed:(now-start)/1000};
  }
  return null;
}

function getCurrentChain(){
  const now = Date.now();
  const totalDuration = chainPlaylist.reduce((acc,v)=>acc+v.duration,0);
  const elapsedInCycle = ((now/1000)%totalDuration);
  let acc=0;
  for(let vid of chainPlaylist){
    if(elapsedInCycle<acc+vid.duration) return {...vid, elapsed:elapsedInCycle-acc};
    acc+=vid.duration;
  }
  return {...chainPlaylist[0], elapsed:0};
}

function playVideoLive(src, startFrom=0){
  if(tvVideo.src !== src){
    tvVideo.src = src;
    tvVideo.load();
  }
  tvVideo.currentTime = startFrom;
  tvVideo.play().catch(()=>{ console.log("صدا ممکن است مسدود شود"); });
}

function startPlayback(){
  function loop(){
    const scheduledNow = getCurrentScheduled();
    if(scheduledNow){
      playVideoLive(scheduledNow.src, scheduledNow.elapsed);
    } else {
      const chainNow = getCurrentChain();
      playVideoLive(chainNow.src, chainNow.elapsed);
    }
  }
  loop();
  setInterval(loop, 19000);
}

startBtn.addEventListener('click', ()=>{
  startScreen.style.display='none';
  tvWrapper.style.display='block';
  startPlayback();
});

rotateBtn.addEventListener('click', ()=>{
  if(!expanded){
    const w = window.innerWidth;
    const h = window.innerHeight;
    tvWrapper.style.width = h*0.95+'px';
    tvWrapper.style.height = w*0.95+'px';
    tvWrapper.style.position = 'fixed';
    tvWrapper.style.top='50%';
    tvWrapper.style.left='50%';
    tvWrapper.style.transform='translate(-50%,-50%) rotate(90deg)';
    tvWrapper.style.transformOrigin='center center';
    expanded=true;
    rotateBtn.innerText='◀';
  } else {
    tvWrapper.style.width='95vw';
    tvWrapper.style.height='calc(95vw*9/16)';
    tvWrapper.style.position='relative';
    tvWrapper.style.top='auto';
    tvWrapper.style.left='auto';
    tvWrapper.style.transform='none';
    expanded=false;
    rotateBtn.innerText='🔲';
  }
});
</script>

</body>
</html>
