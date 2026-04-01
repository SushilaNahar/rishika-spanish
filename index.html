import { useState, useEffect } from "react";

const LEVELS = [
  {
    id:0, icon:"👨‍👩‍👧", color:"#FF6B6B",
    title:"Mi Familia", subtitle:"Family words",
    words:[
      {es:"mi familia",en:"my family"},{es:"mi padre",en:"my father"},
      {es:"mi madre",en:"my mother"},{es:"mis padres",en:"my parents"},
      {es:"mi hermano",en:"my brother"},{es:"mi hermana",en:"my sister"},
      {es:"mi abuelo",en:"my grandfather"},{es:"mi abuela",en:"my grandmother"},
      {es:"mis abuelos",en:"my grandparents"},{es:"mi tia",en:"my aunt"},
    ],
    sentences:[
      {q:"Ella es mi ___.",blank:"hermana",options:["hermana","hermano","madre","tia"]},
      {q:"El es mi ___.",blank:"padre",options:["padre","madre","hermano","abuelo"]},
      {q:"Ellos son mis ___.",blank:"abuelos",options:["abuelos","padres","hermanos","hijos"]},
      {q:"Ella es mi ___.",blank:"madre",options:["madre","hermana","abuela","tia"]},
    ]
  },
  {
    id:1, icon:"🔢", color:"#4D96FF",
    title:"Los Numeros", subtitle:"Numbers 1-20",
    words:[
      {es:"uno",en:"one"},{es:"dos",en:"two"},{es:"tres",en:"three"},
      {es:"cuatro",en:"four"},{es:"cinco",en:"five"},{es:"seis",en:"six"},
      {es:"siete",en:"seven"},{es:"ocho",en:"eight"},{es:"nueve",en:"nine"},
      {es:"diez",en:"ten"},{es:"veinte",en:"twenty"},
    ],
    sentences:[
      {q:"Uno + uno = ___.",blank:"dos",options:["dos","tres","cuatro","uno"]},
      {q:"Cinco + cinco = ___.",blank:"diez",options:["diez","cinco","ocho","veinte"]},
      {q:"Diez + diez = ___.",blank:"veinte",options:["veinte","nueve","doce","once"]},
      {q:"Tres + tres = ___.",blank:"seis",options:["seis","siete","ocho","cinco"]},
    ]
  },
  {
    id:2, icon:"🎨", color:"#C77DFF",
    title:"Los Colores", subtitle:"Colours",
    words:[
      {es:"rojo",en:"red"},{es:"azul",en:"blue"},{es:"verde",en:"green"},
      {es:"amarillo",en:"yellow"},{es:"naranja",en:"orange"},{es:"morado",en:"purple"},
      {es:"rosa",en:"pink"},{es:"blanco",en:"white"},{es:"negro",en:"black"},
    ],
    sentences:[
      {q:"El sol es ___.",blank:"amarillo",options:["amarillo","azul","verde","rojo"]},
      {q:"El cielo es ___.",blank:"azul",options:["azul","rojo","negro","verde"]},
      {q:"La hierba es ___.",blank:"verde",options:["verde","rosa","morado","naranja"]},
      {q:"La noche es ___.",blank:"negro",options:["negro","blanco","gris","rojo"]},
    ]
  },
  {
    id:3, icon:"🤸", color:"#FF9F43",
    title:"El Cuerpo", subtitle:"Body parts",
    words:[
      {es:"la cabeza",en:"head"},{es:"los ojos",en:"eyes"},{es:"la nariz",en:"nose"},
      {es:"la boca",en:"mouth"},{es:"las orejas",en:"ears"},{es:"los brazos",en:"arms"},
      {es:"las manos",en:"hands"},{es:"las piernas",en:"legs"},{es:"los pies",en:"feet"},
    ],
    sentences:[
      {q:"Veo con los ___.",blank:"ojos",options:["ojos","pies","brazos","orejas"]},
      {q:"Escucho con las ___.",blank:"orejas",options:["orejas","manos","piernas","ojos"]},
      {q:"Camino con las ___.",blank:"piernas",options:["piernas","manos","orejas","nariz"]},
      {q:"Como con la ___.",blank:"boca",options:["boca","nariz","cabeza","mano"]},
    ]
  },
  {
    id:4, icon:"🏠", color:"#6BCB77",
    title:"La Casa", subtitle:"Rooms at home",
    words:[
      {es:"la cocina",en:"kitchen"},{es:"el bano",en:"bathroom"},
      {es:"el dormitorio",en:"bedroom"},{es:"la sala",en:"living room"},
      {es:"el jardin",en:"garden"},{es:"la puerta",en:"door"},
      {es:"la ventana",en:"window"},{es:"la mesa",en:"table"},{es:"la cama",en:"bed"},
    ],
    sentences:[
      {q:"Duermo en el ___.",blank:"dormitorio",options:["dormitorio","bano","jardin","sala"]},
      {q:"Cocinamos en la ___.",blank:"cocina",options:["cocina","sala","cama","ventana"]},
      {q:"Las flores estan en el ___.",blank:"jardin",options:["jardin","bano","dormitorio","mesa"]},
      {q:"Veo la tele en la ___.",blank:"sala",options:["sala","cocina","jardin","puerta"]},
    ]
  },
  {
    id:5, icon:"🍎", color:"#FFB347",
    title:"La Comida", subtitle:"Food and drinks",
    words:[
      {es:"el pan",en:"bread"},{es:"la leche",en:"milk"},{es:"el agua",en:"water"},
      {es:"la manzana",en:"apple"},{es:"el arroz",en:"rice"},{es:"el pollo",en:"chicken"},
      {es:"las verduras",en:"vegetables"},{es:"el queso",en:"cheese"},{es:"el huevo",en:"egg"},
    ],
    sentences:[
      {q:"Bebo ___ por la manana.",blank:"leche",options:["leche","arroz","queso","pan"]},
      {q:"Como una ___ verde.",blank:"manzana",options:["manzana","pollo","huevo","leche"]},
      {q:"El ___ es blanco.",blank:"arroz",options:["arroz","agua","pan","queso"]},
      {q:"Las ___ son buenas.",blank:"verduras",options:["verduras","manzana","leche","pan"]},
    ]
  },
  {
    id:6, icon:"🐶", color:"#FF6B6B",
    title:"Los Animales", subtitle:"Animals",
    words:[
      {es:"el perro",en:"dog"},{es:"el gato",en:"cat"},{es:"el pajaro",en:"bird"},
      {es:"el pez",en:"fish"},{es:"el caballo",en:"horse"},{es:"la vaca",en:"cow"},
      {es:"el elefante",en:"elephant"},{es:"el leon",en:"lion"},{es:"el conejo",en:"rabbit"},
    ],
    sentences:[
      {q:"El ___ nada en el agua.",blank:"pez",options:["pez","caballo","conejo","pajaro"]},
      {q:"El ___ es el rey de la selva.",blank:"leon",options:["leon","elefante","perro","gato"]},
      {q:"La ___ nos da leche.",blank:"vaca",options:["vaca","caballo","pajaro","gato"]},
      {q:"El ___ salta muy alto.",blank:"conejo",options:["conejo","perro","elefante","pajaro"]},
    ]
  },
  {
    id:7, icon:"🎒", color:"#4D96FF",
    title:"La Escuela", subtitle:"School things",
    words:[
      {es:"el libro",en:"book"},{es:"el cuaderno",en:"notebook"},{es:"el lapiz",en:"pencil"},
      {es:"la pluma",en:"pen"},{es:"la mochila",en:"backpack"},{es:"la regla",en:"ruler"},
      {es:"el borrador",en:"eraser"},{es:"el maestro",en:"teacher"},{es:"el escritorio",en:"desk"},
    ],
    sentences:[
      {q:"Escribo con el ___.",blank:"lapiz",options:["lapiz","libro","mochila","regla"]},
      {q:"Leo el ___ en clase.",blank:"libro",options:["libro","borrador","cuaderno","escritorio"]},
      {q:"Llevo mis cosas en la ___.",blank:"mochila",options:["mochila","pluma","regla","lapiz"]},
      {q:"El ___ ensena en la escuela.",blank:"maestro",options:["maestro","cuaderno","lapiz","borrador"]},
    ]
  },
];

const S = {
  page:{minHeight:"100vh",background:"#FFF8F0",fontFamily:"sans-serif"},
  header:{background:"linear-gradient(135deg,#FF6B6B,#FFD93D)",padding:"18px 16px",textAlign:"center"},
  h1:{fontSize:"1.6rem",fontWeight:900,color:"white",margin:0},
  sub:{fontSize:"0.85rem",color:"rgba(255,255,255,0.9)",fontWeight:700},
  wrap:{maxWidth:460,margin:"0 auto",padding:"16px"},
  card:{display:"flex",alignItems:"center",gap:12,background:"white",borderRadius:16,padding:14,marginBottom:10,boxShadow:"0 3px 12px rgba(0,0,0,0.08)",cursor:"pointer"},
  wbtn:{width:"100%",padding:14,background:"linear-gradient(135deg,#FF6B6B,#FFB347)",color:"white",border:"none",borderRadius:14,fontWeight:900,fontSize:"0.95rem",cursor:"pointer"},
};

function Bar({n,t}){
  return(
    <div style={{marginBottom:14}}>
      <div style={{fontSize:"0.75rem",color:"#ccc",marginBottom:4}}>{n} of {t}</div>
      <div style={{height:9,background:"#eee",borderRadius:10,overflow:"hidden"}}>
        <div style={{height:"100%",width:`${Math.round(n/t*100)}%`,background:"linear-gradient(90deg,#FF6B6B,#FFD93D)",borderRadius:10,transition:"width 0.4s"}}/>
      </div>
    </div>
  );
}

function Flash({level,onNext}){
  const [i,setI]=useState(0);
  const [fl,setFl]=useState(false);
  const w=level.words;
  return(
    <div>
      <Bar n={i+1} t={w.length}/>
      <div onClick={()=>setFl(f=>!f)} style={{cursor:"pointer",marginBottom:14}}>
        <div style={{borderRadius:20,padding:"44px 20px",textAlign:"center",background:fl?"linear-gradient(135deg,#6BCB77,#FFD93D)":"linear-gradient(135deg,#4D96FF,#C77DFF)",boxShadow:"0 6px 20px rgba(0,0,0,0.12)"}}>
          <div style={{fontSize:"1.8rem",fontWeight:900,color:"white"}}>{fl?w[i].en:w[i].es}</div>
          <div style={{fontSize:"0.78rem",color:"rgba(255,255,255,0.8)",marginTop:10}}>{fl?"tap to flip back":"tap to see English"}</div>
        </div>
      </div>
      <div style={{display:"flex",alignItems:"center",justifyContent:"center",gap:20,marginBottom:16}}>
        <button onClick={()=>{setI(x=>Math.max(0,x-1));setFl(false);}} disabled={i===0} style={{background:"white",border:"none",borderRadius:"50%",width:42,height:42,cursor:i===0?"not-allowed":"pointer",opacity:i===0?0.3:1,boxShadow:"0 2px 8px rgba(0,0,0,0.1)"}}>←</button>
        <span style={{fontWeight:800,color:"#bbb"}}>{i+1}/{w.length}</span>
        <button onClick={()=>{setI(x=>Math.min(w.length-1,x+1));setFl(false);}} disabled={i===w.length-1} style={{background:"white",border:"none",borderRadius:"50%",width:42,height:42,cursor:i===w.length-1?"not-allowed":"pointer",opacity:i===w.length-1?0.3:1,boxShadow:"0 2px 8px rgba(0,0,0,0.1)"}}>→</button>
      </div>
      <button onClick={onNext} style={S.wbtn}>Next: Fill in the Blank ✏️</button>
    </div>
  );
}

function Fill({level,onNext}){
  const [i,setI]=useState(0);
  const [chosen,setChosen]=useState(null);
  const [opts]=useState(()=>level.sentences.map(s=>[...s.options].sort(()=>Math.random()-0.5)));
  const q=level.sentences[i];
  function go(){if(i<level.sentences.length-1){setI(x=>x+1);setChosen(null);}else onNext();}
  return(
    <div>
      <Bar n={i+1} t={level.sentences.length}/>
      <div style={{background:"white",borderRadius:18,padding:"22px 18px",boxShadow:"0 3px 14px rgba(0,0,0,0.08)",marginBottom:12,textAlign:"center"}}>
        <div style={{fontSize:"1.1rem",fontWeight:800,lineHeight:1.9}}>{q.q.replace("___",chosen?`[ ${chosen} ]`:"______")}</div>
        {chosen&&<div style={{marginTop:8,fontWeight:700,fontSize:"0.85rem",color:chosen===q.blank?"#2d7a3a":"#c0392b"}}>{chosen===q.blank?"Correct! ✅":"Answer: "+q.blank}</div>}
      </div>
      <div style={{display:"grid",gridTemplateColumns:"1fr 1fr",gap:8,marginBottom:10}}>
        {opts[i].map(opt=>{
          let bg="white",bdr="#eee",col="#2d2d2d";
          if(chosen){if(opt===q.blank){bg="#f0fff4";bdr="#6BCB77";col="#2d7a3a";}else if(opt===chosen){bg="#fff0f0";bdr="#FF6B6B";col="#c0392b";}}
          return(<button key={opt} onClick={()=>!chosen&&setChosen(opt)} style={{padding:"13px 8px",border:`3px solid ${bdr}`,borderRadius:12,background:bg,fontWeight:800,fontSize:"0.95rem",cursor:chosen?"default":"pointer",color:col}}>{opt}</button>);
        })}
      </div>
      {chosen&&<button onClick={go} style={S.wbtn}>{i<level.sentences.length-1?"Next →":"Next: Match 🔗"}</button>}
    </div>
  );
}

function Match({level,onDone}){
  const words=level.words.slice(0,6);
  const [lefts]=useState(()=>[...words].sort(()=>Math.random()-0.5));
  const [rights]=useState(()=>[...words].sort(()=>Math.random()-0.5));
  const [selEs,setSelEs]=useState(null);
  const [selEn,setSelEn]=useState(null);
  const [matched,setMatched]=useState([]);
  const [bad,setBad]=useState([]);

  useEffect(()=>{
    if(!selEs||!selEn)return;
    const w=words.find(x=>x.es===selEs);
    if(w&&w.en===selEn){setMatched(m=>[...m,selEs]);setSelEs(null);setSelEn(null);}
    else{setBad([selEs,selEn]);setTimeout(()=>{setBad([]);setSelEs(null);setSelEn(null);},500);}
  },[selEs,selEn]);

  const mEns=matched.map(es=>words.find(w=>w.es===es)?.en);
  const allDone=matched.length===words.length;

  function lStyle(es){
    const d=matched.includes(es),s=selEs===es,b=bad.includes(es);
    return{padding:"11px 8px",borderRadius:10,fontWeight:800,fontSize:"0.83rem",border:`3px solid ${d?"#6BCB77":s?"#4D96FF":b?"#FF6B6B":"#eee"}`,background:d?"#f0fff4":s?"#f0f8ff":b?"#fff0f0":"white",color:d?"#2d7a3a":"#2d2d2d",cursor:d?"default":"pointer",pointerEvents:d?"none":"auto"};
  }
  function rStyle(en){
    const d=mEns.includes(en),s=selEn===en,b=bad.includes(en);
    return{padding:"11px 8px",borderRadius:10,fontWeight:800,fontSize:"0.83rem",border:`3px solid ${d?"#6BCB77":s?"#4D96FF":b?"#FF6B6B":"#eee"}`,background:d?"#f0fff4":s?"#f0f8ff":b?"#fff0f0":"white",color:d?"#2d7a3a":"#2d2d2d",cursor:d?"default":"pointer",pointerEvents:d?"none":"auto"};
  }

  return(
    <div>
      <Bar n={matched.length} t={words.length}/>
      <p style={{textAlign:"center",color:"#bbb",fontSize:"0.82rem",marginBottom:12}}>Tap Spanish, then its English match!</p>
      <div style={{display:"grid",gridTemplateColumns:"1fr 1fr",gap:8,marginBottom:12}}>
        <div style={{display:"flex",flexDirection:"column",gap:8}}>
          {lefts.map(w=><button key={w.es} onClick={()=>!matched.includes(w.es)&&setSelEs(e=>e===w.es?null:w.es)} style={lStyle(w.es)}>{w.es}</button>)}
        </div>
        <div style={{display:"flex",flexDirection:"column",gap:8}}>
          {rights.map(w=><button key={w.en} onClick={()=>!mEns.includes(w.en)&&setSelEn(e=>e===w.en?null:w.en)} style={rStyle(w.en)}>{w.en}</button>)}
        </div>
      </div>
      {allDone&&<><div style={{textAlign:"center",padding:12,borderRadius:12,marginBottom:10,fontWeight:800,background:"#f0fff4",color:"#2d7a3a"}}>All matched! Well done Rishika! 🎉</div><button onClick={onDone} style={S.wbtn}>Complete Level ✓</button></>}
    </div>
  );
}

export default function App(){
  const [done,setDone]=useState([]);
  const [lvIdx,setLvIdx]=useState(null);
  const [mode,setMode]=useState("flash");

  function markDone(i){if(!done.includes(i))setDone(d=>[...d,i]);setLvIdx(null);}

  if(lvIdx===null){
    return(
      <div style={S.page}>
        <div style={S.header}>
          <div style={S.h1}>🌟 Aprende Espanol!</div>
          <div style={S.sub}>Rishika's Spanish Journey</div>
        </div>
        <div style={S.wrap}>
          <div style={{textAlign:"center",fontSize:"1.1rem",fontWeight:900,color:"#FF6B6B",margin:"14px 0"}}>Choose Your Level 🗺️</div>
          {LEVELS.map((lv,i)=>{
            const unlocked=i===0||done.includes(i-1);
            const completed=done.includes(i);
            return(
              <div key={i} onClick={()=>unlocked&&(setLvIdx(i),setMode("flash"))} style={{...S.card,border:`3px solid ${completed?"#6BCB77":"transparent"}`,opacity:unlocked?1:0.4,cursor:unlocked?"pointer":"not-allowed"}}>
                <div style={{fontSize:"1.8rem"}}>{lv.icon}</div>
                <div style={{flex:1}}>
                  <div style={{fontWeight:900,color:lv.color}}>Level {i+1}: {lv.title}</div>
                  <div style={{fontSize:"0.78rem",color:"#aaa"}}>{lv.subtitle}</div>
                </div>
                <div>{completed?"✅":unlocked?"▶️":"🔒"}</div>
              </div>
            );
          })}
        </div>
      </div>
    );
  }

  const level=LEVELS[lvIdx];
  return(
    <div style={S.page}>
      <div style={{background:"linear-gradient(135deg,#FF6B6B,#FFD93D)",padding:"14px 16px"}}>
        <div style={{display:"flex",alignItems:"center",gap:10,marginBottom:10}}>
          <button onClick={()=>setLvIdx(null)} style={{background:"rgba(255,255,255,0.3)",border:"none",borderRadius:"50%",width:36,height:36,color:"white",fontWeight:900,fontSize:"1rem",cursor:"pointer"}}>←</button>
          <div style={{fontWeight:900,color:"white"}}>{level.icon} {level.title}</div>
        </div>
        <div style={{display:"flex",gap:6}}>
          {["flash","fill","match"].map(m=>(
            <button key={m} onClick={()=>setMode(m)} style={{flex:1,padding:"8px 4px",border:"none",borderRadius:10,cursor:"pointer",fontWeight:800,fontSize:"0.72rem",background:mode===m?"white":"rgba(255,255,255,0.3)",color:mode===m?"#FF6B6B":"white"}}>
              {m==="flash"?"🃏 Cards":m==="fill"?"✏️ Fill":"🔗 Match"}
            </button>
          ))}
        </div>
      </div>
      <div style={S.wrap}>
        {mode==="flash"&&<Flash level={level} onNext={()=>setMode("fill")}/>}
        {mode==="fill"&&<Fill level={level} onNext={()=>setMode("match")}/>}
        {mode==="match"&&<Match level={level} onDone={()=>markDone(lvIdx)}/>}
      </div>
    </div>
  );
}
