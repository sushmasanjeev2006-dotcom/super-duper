import React, { useEffect, useRef, useState } from 'react';
import { motion } from 'framer-motion';

const WALLPAPER = 'https://static.animecorner.me/2023/07/rezero-s3-scaled.jpg';
const BRACELET_IMG = 'https://i.pinimg.com/originals/9a/19/21/9a192164d7f0f2dea3b4b182c221d97d.jpg';
const CREDENTIALS = { user: 'Shub@princess', pass: 'Fast-text' };

function createSparkles(x, y, count = 12) {
  const hueBase = Math.floor(Math.random() * 60) + 200;
  for (let i = 0; i < count; i++) {
    const s = document.createElement('div');
    s.style.position = 'fixed';
    s.style.left = `${x - 8 + (Math.random() - 0.5) * 40}px`;
    s.style.top = `${y - 8 + (Math.random() - 0.5) * 40}px`;
    s.style.width = '8px';
    s.style.height = '8px';
    s.style.borderRadius = '50%';
    s.style.pointerEvents = 'none';
    s.style.background = `hsl(${hueBase + Math.floor((Math.random() - 0.5) * 40)},80%,70%)`;
    s.style.zIndex = 9999;
    document.body.appendChild(s);
    const dx = (Math.random() - 0.5) * 200;
    const dy = -Math.random() * 200 - 20;
    const life = 700 + Math.random() * 400;
    s.animate([
      { transform: 'translate(0,0) scale(1)', opacity: 1 },
      { transform: `translate(${dx}px, ${dy}px) scale(0.3)`, opacity: 0 }
    ], { duration: life, easing: 'cubic-bezier(.2,.8,.2,1)' });
    setTimeout(() => { try { document.body.removeChild(s); } catch (e) {} }, life);
  }
}

const reZeroQuestions = [
  { q: "Who saves Subaru from the Oni?", choices: ['Rem', 'Emilia', 'Ram', 'Beatrice'], a: 0 },
  { q: "What is Emilia's hair color?", choices: ['Black', 'Silver', 'Blue', 'Pink'], a: 1 },
  { q: "Who is Subaru's rival in arrogance?", choices: ['Garff', 'Regulus', 'Roswaal', 'Wilhelm'], a: 1 },
  { q: "What ability is Subaru known for?", choices: ['Time Loop', 'Telepathy', 'Healing', 'Flight'], a: 0 },
  { q: "Who is the spirit contracted to Emilia?", choices: ['Puck', 'Satella', 'Beatrice', 'Ley'], a: 0 },
  { q: "Which town does Subaru first wake up in?", choices: ['Lugnica', 'Lust', 'Ruins', 'Mura'], a: 0 },
  { q: "Who is the witch cult leader associated with the Witch?", choices: ['Petelgeuse', 'Regulus', 'Elsa', 'Rodolg'], a: 0 },
  { q: "What is Beatrice's role?", choices: ['Magic Bookkeeper', 'Knight', 'Healer', 'Alchemist'], a: 0 },
  { q: "Which character uses weapons and silence?", choices: ['Elsa', 'Felt', 'Otto', 'Wilhelm'], a: 0 },
  { q: "Who is known as the Sin Archbishop of Sloth?", choices: ['Regulus', 'Roswaal', 'Puck', 'Subaru'], a: 0 }
];

const aboutMeQuestions = [
  { q: "What's my spelling?", choices: ['SHELLY', 'SHELY', 'SHAILLY', 'SHAILY'], a: 2 },
  { q: "What's my fav. fast-food?", choices: ['pizza', 'momos', 'golgappe', 'burger'], a: 2 },
  { q: "What's my fav. color?", choices: ['Blue', 'Green', 'Pink', 'Black'], a: 0 },
  { q: "What's my fav. hobbie?", choices: ['Kalesh', 'gossips', 'gussa hona', 'All of these'], a: 3 }
];

function Login({ onSuccess }) {
  const [user, setUser] = useState('');
  const [pass, setPass] = useState('');
  const [err, setErr] = useState('');
  function submit(e) {
    e.preventDefault();
    if (user === CREDENTIALS.user && pass === CREDENTIALS.pass) onSuccess(); else setErr('Incorrect username or password');
  }
  return (
    <div className="min-h-screen flex items-center justify-center bg-black/40">
      <div style={{ backgroundImage: `url(${WALLPAPER})`, backgroundSize: 'cover', position: 'absolute', inset: 0, zIndex: -1 }} />
      <form onSubmit={submit} className="p-8 rounded-3xl bg-white/5 backdrop-blur-md border border-white/10 w-full max-w-md text-center">
        <h1 className="text-4xl font-extrabold text-white mb-4">Princess Portal</h1>
        <input required placeholder="Username" value={user} onChange={(e) => setUser(e.target.value)} className="w-full px-4 py-3 rounded-xl mb-3 bg-white/10 text-white" />
        <input required placeholder="Password" type="password" value={pass} onChange={(e) => setPass(e.target.value)} className="w-full px-4 py-3 rounded-xl mb-3 bg-white/10 text-white" />
        <button type="submit" className="w-full py-3 rounded-xl bg-pink-500 font-bold text-lg">Enter</button>
        {err && <div className="mt-3 text-red-400">{err}</div>}
      </form>
    </div>
  );
}

function PortalMain({ goToGames }) {
  return (
    <div className="min-h-screen flex items-center justify-center" style={{ backgroundImage: `url(${WALLPAPER})`, backgroundSize: 'cover' }}>
      <div className="max-w-5xl w-full p-8">
        <motion.div initial={{ scale: 0.9, opacity: 0 }} animate={{ scale: 1, opacity: 1 }} transition={{ duration: 0.6 }} className="rounded-3xl p-8 bg-white/5 backdrop-blur-lg border border-white/10">
          <h2 className="text-5xl font-extrabold text-white">Welcome to the Magical Flow</h2>
          <p className="mt-3 text-white/90">Choose a path and make everything big and sparkling.</p>
          <div className="mt-8 flex gap-4">
            <button onClick={() => { createSparkles(Math.round(window.innerWidth / 2), Math.round(window.innerHeight / 2), 80); goToGames(); }} className="px-8 py-4 rounded-xl bg-purple-600 text-xl font-bold">Play Games</button>
            <button onClick={() => createSparkles(200, 200, 40)} className="px-8 py-4 rounded-xl bg-pink-500 text-xl font-bold">Send Sparkle</button>
          </div>
        </motion.div>
      </div>
    </div>
  );
}

function Quiz({ questions, onComplete, title }) {
  const [idx, setIdx] = useState(0);
  const [answers, setAnswers] = useState(() => Array(questions.length).fill(null));
  function choose(i) {
    setAnswers((prev) => {
      const copy = prev.slice();
      copy[idx] = i;
      return copy;
    });
    if (idx === questions.length - 1) onComplete(answers.map((v, k) => (k === idx ? i : v)).map((v) => v)); else setIdx((s) => s + 1);
  }
  useEffect(() => {
    setAnswers(Array(questions.length).fill(null));
  }, [questions]);
  return (
    <div className="p-6 rounded-2xl bg-white/5 border border-white/10">
      <h3 className="text-2xl font-bold text-white">{title} ({idx + 1}/{questions.length})</h3>
      <p className="mt-3 text-white/90">{questions[idx].q}</p>
      <div className="mt-4 grid grid-cols-1 gap-3">
        {questions[idx].choices.map((c, i) => (
          <button key={i} onClick={() => choose(i)} className="rounded-xl px-6 py-4 text-xl font-semibold bg-white/10 text-white text-left">{c}</button>
        ))}
      </div>
    </div>
  );
}

function Scratch({ onReveal }) {
  const canvasRef = useRef(null);
  const [revealed, setRevealed] = useState(false);
  const [pct, setPct] = useState(0);
  useEffect(() => {
    const c = canvasRef.current;
    if (!c) return;
    const ctx = c.getContext('2d');
    if (!ctx) return;
    const w = 600;
    const h = 200;
    c.width = w;
    c.height = h;
    c.style.width = w + 'px';
    c.style.height = h + 'px';
    ctx.fillStyle = '#999';
    ctx.fillRect(0, 0, w, h);
    ctx.globalCompositeOperation = 'destination-out';
    let isDown = false;
    function pos(e) {
      const r = c.getBoundingClientRect();
      const clientX = e.clientX ?? (e.touches && e.touches[0] && e.touches[0].clientX);
      const clientY = e.clientY ?? (e.touches && e.touches[0] && e.touches[0].clientY);
      return { x: clientX - r.left, y: clientY - r.top };
    }
    function drawAt(e) {
      const p = pos(e);
      if (!p.x && p.x !== 0) return;
      ctx.beginPath();
      ctx.arc(p.x, p.y, 30, 0, Math.PI * 2);
      ctx.fill();
    }
    function down(e) { e.preventDefault(); isDown = true; drawAt(e); }
    function move(e) { if (!isDown) return; drawAt(e); }
    function up() {
      isDown = false;
      try {
        const img = ctx.getImageData(0, 0, w, h).data;
        let clear = 0;
        for (let i = 3; i < img.length; i += 4) if (img[i] === 0) clear++;
        const percent = Math.round((clear / (w * h)) * 100);
        setPct(percent);
        if (percent > 50) {
          setRevealed(true);
          onReveal && onReveal();
        }
      } catch (e) {}
    }
    c.addEventListener('pointerdown', down);
    window.addEventListener('pointerup', up);
    c.addEventListener('pointermove', move);
    c.addEventListener('touchstart', down, { passive: false });
    c.addEventListener('touchmove', move, { passive: false });
    window.addEventListener('touchend', up);
    return () => {
      c.removeEventListener('pointerdown', down);
      window.removeEventListener('pointerup', up);
      c.removeEventListener('pointermove', move);
      c.removeEventListener('touchstart', down);
      c.removeEventListener('touchmove', move);
      window.removeEventListener('touchend', up);
    };
  }, [onReveal]);
  function revealNow() {
    const c = canvasRef.current;
    if (!c) return;
    const ctx = c.getContext('2d');
    ctx.clearRect(0, 0, c.width, c.height);
    setPct(100);
    setRevealed(true);
    onReveal && onReveal();
  }
  return (
    <div className="p-6 rounded-2xl bg-white/5 border border-white/10 flex gap-6 items-center">
      <div className="w-[600px] h-[200px] rounded-xl overflow-hidden relative border border-white/10">
        <img src={BRACELET_IMG} alt="bracelet" className="w-full h-full object-cover" />
        {!revealed && <canvas ref={canvasRef} className="absolute inset-0 z-20" />}
        {revealed && <div className="absolute inset-0 z-30 flex items-center justify-center"><div className="bg-white/10 p-6 rounded-2xl text-center"><h4 className="text-3xl font-bold text-white">You revealed: ✨ Lucky Charm ✨</h4></div></div>}
      </div>
      <div className="w-full max-w-xs"><p className="text-white/90">Reveal progress: <span className="font-bold">{pct}%</span></p><div className="mt-4"><button onClick={revealNow} className="px-6 py-3 rounded-lg bg-pink-500 font-bold">Reveal Instantly</button></div></div>
    </div>
  );
}

function TicTacToeAI() {
  const [board, setBoard] = useState(Array(9).fill(null));
  const [xNext, setXNext] = useState(true);
  const [winner, setWinner] = useState(null);
  useEffect(() => {
    const w = calcWinner(board);
    if (w) setWinner(w);
    else if (!board.includes(null)) setWinner('Draw');
  }, [board]);
  useEffect(() => {
    if (!xNext && !winner) {
      const timer = setTimeout(() => {
        const move = aiMove(board);
        if (move !== null) {
          const nb = board.slice();
          nb[move] = 'O';
          setBoard(nb);
          setXNext(true);
        }
      }, 400);
      return () => clearTimeout(timer);
    }
  }, [xNext, board, winner]);
  function calcWinner(b) {
    const lines = [[0,1,2],[3,4,5],[6,7,8],[0,3,6],[1,4,7],[2,5,8],[0,4,8],[2,4,6]];
    for (let l of lines) {
      const [a,b1,c] = l;
      if (b[a] && b[a] === b[b1] && b[a] === b[c]) return b[a];
    }
    return null;
  }
  function aiMove(b) {
    for (let i = 0; i < 9; i++) {
      if (!b[i]) {
        const nb = b.slice();
        nb[i] = 'O';
        if (calcWinner(nb) === 'O') return i;
      }
    }
    for (let i = 0; i < 9; i++) {
      if (!b[i]) {
        const nb = b.slice();
        nb[i] = 'X';
        if (calcWinner(nb) === 'X') return i;
      }
    }
    const corners = [0,2,6,8].filter(i => !b[i]);
    if (corners.length) return corners[Math.floor(Math.random() * corners.length)];
    if (!b[4]) return 4;
    const empties = b.map((v,i) => v ? null : i).filter(v => v !== null);
    return empties.length ? empties[Math.floor(Math.random() * empties.length)] : null;
  }
  function clickCell(i,e) {
    if (board[i] || winner || !xNext) return;
    const clientX = e && e.clientX ? e.clientX : Math.round(window.innerWidth / 2);
    const clientY = e && e.clientY ? e.clientY : Math.round(window.innerHeight / 2);
    createSparkles(clientX, clientY, 20);
    const nb = board.slice();
    nb[i] = 'X';
    setBoard(nb);
    setXNext(false);
  }
  function reset() {
    setBoard(Array(9).fill(null));
    setWinner(null);
    setXNext(true);
  }
  return (
    <div className="p-6 rounded-2xl bg-white/5 border border-white/10">
      <h3 className="text-2xl font-bold text-white">Tic — Tac — Toe (You vs AI)</h3>
      <div className="mt-4 grid grid-cols-3 gap-4">{board.map((v,i) => (<button key={i} onClick={(e) => clickCell(i,e)} className="w-40 h-40 text-6xl rounded-xl bg-white/6 font-extrabold">{v}</button>))}</div>
      <div className="mt-4 flex gap-4 items-center"><div className="text-white/90">Status: <span className="font-bold text-white text-2xl">{winner ? (winner === 'Draw' ? 'Draw' : winner + ' wins') : xNext ? 'Your turn (X)' : 'AI thinking (O)'}</span></div><button onClick={reset} className="px-6 py-3 rounded-lg bg-purple-600 font-bold">Reset</button></div>
    </div>
  );
}

function Certificate({ name, score }) {
  const canvasRef = useRef(null);
  useEffect(() => {
    const c = canvasRef.current;
    if (!c) return;
    const ctx = c.getContext('2d');
    c.width = 1200;
    c.height = 800;
    ctx.fillStyle = '#fff';
    ctx.fillRect(0,0,c.width,c.height);
    ctx.fillStyle = '#2b063e';
    ctx.fillRect(40,40,c.width-80,c.height-80);
    ctx.fillStyle = '#fff';
    ctx.font = '48px serif';
    ctx.fillText('Certificate of Completion', 120, 200);
    ctx.font = '36px serif';
    ctx.fillText(`Awarded to: ${name}`, 120, 320);
    ctx.font = '28px serif';
    ctx.fillText(`Score: ${score}`, 120, 380);
    ctx.font = '20px serif';
    ctx.fillText('Princess Portal - Magical Flow', 120, 720);
  }, [name, score]);
  function download() {
    const c = canvasRef.current;
    if (!c) return;
    const url = c.toDataURL('image/png');
    const a = document.createElement('a');
    a.href = url;
    a.download = 'certificate.png';
    a.click();
  }
  return (
    <div className="p-6 rounded-2xl bg-white/5 border border-white/10 text-center">
      <canvas ref={canvasRef} className="w-full max-w-3xl mx-auto" />
      <div className="mt-4"><button onClick={download} className="px-6 py-3 rounded-lg bg-green-600 font-bold">Download Certificate</button></div>
    </div>
  );
}

export default function App() {
  const [logged, setLogged] = useState(false);
  const [stage, setStage] = useState('portal');
  const [showResults, setShowResults] = useState(false);
  const [level1Answers, setLevel1Answers] = useState(null);
  const [level2Answers, setLevel2Answers] = useState(null);
  const [level1Score, setLevel1Score] = useState(0);
  const [level2Score, setLevel2Score] = useState(0);
  const [name, setName] = useState('Guest');
  function handleLoginSuccess() { setLogged(true); }
  function completeLevel1(ans) { setLevel1Answers(ans); let sc = 0; for (let i=0;i<reZeroQuestions.length;i++) if (ans[i] === reZeroQuestions[i].a) sc++; setLevel1Score(sc); setStage('level2Intro'); }
  function completeLevel2(ans) { setLevel2Answers(ans); let sc = 0; for (let i=0;i<aboutMeQuestions.length;i++) if (ans[i] === aboutMeQuestions[i].a) sc++; setLevel2Score(sc); setShowResults(true); setStage('results'); }
  useEffect(()=>{ if (showResults) createSparkles(Math.round(window.innerWidth/2), Math.round(window.innerHeight/2), 80); }, [showResults]);
  return (
    <div className="min-h-screen text-white">
      {!logged && <Login onSuccess={handleLoginSuccess} />}
      {logged && stage === 'portal' && <PortalMain goToGames={() => setStage('games')} />}
      {logged && stage === 'games' && (
        <div className="min-h-screen p-8 bg-gradient-to-b from-purple-900 to-indigo-900">
          <div className="max-w-6xl mx-auto">
            <header className="flex items-center justify-between"><h2 className="text-5xl font-extrabold">Games & Quizzes</h2><div className="flex gap-4"><button onClick={() => setStage('portal')} className="px-6 py-3 rounded-xl bg-white/10">Back</button></div></header>
            <div className="mt-8 grid grid-cols-1 lg:grid-cols-2 gap-8">
              <div className="p-6 rounded-2xl bg-white/5 border border-white/10"><Quiz title="Re:Zero Quiz" questions={reZeroQuestions} onComplete={completeLevel1} /></div>
              <div className="p-6 rounded-2xl bg-white/5 border border-white/10"><Scratch onReveal={() => createSparkles(Math.round(window.innerWidth/2), Math.round(window.innerHeight/2), 60)} /></div>
              <div className="p-6 rounded-2xl bg-white/5 border border-white/10"><TicTacToeAI /></div>
              <div className="p-6 rounded-2xl bg-white/5 border border-white/10"><button onClick={() => setStage('level2Intro')} className="w-full py-6 rounded-xl bg-gradient-to-r from-yellow-400 to-pink-400 text-2xl font-bold">Take Level 2 (About Me)</button></div>
            </div>
            <footer className="mt-8 text-center text-white/80">Props: bracelet image is embedded.</footer>
          </div>
        </div>
      )}
      {logged && stage === 'level2Intro' && (
        <div className="min-h-screen p-8 bg-gradient-to-b from-indigo-900 to-pink-900 flex items-center justify-center">
          <div className="max-w-3xl w-full"><div className="p-6 rounded-2xl bg-white/5 border border-white/10 text-center"><h3 className="text-3xl font-bold">Level 2: About Me</h3><p className="mt-2 text-white/90">Answer questions about me. Results and correct answers will be shown only after submission.</p><div className="mt-4"><button onClick={() => setStage('level2Quiz')} className="px-6 py-3 rounded-xl bg-pink-500 font-bold">Start Level 2</button></div></div></div>
        </div>
      )}
      {logged && stage === 'level2Quiz' && (<div className="min-h-screen p-8 bg-gradient-to-b from-purple-900 to-indigo-900"><div className="max-w-4xl mx-auto"><Quiz title="About Me Quiz" questions={aboutMeQuestions} onComplete={(ans)=>completeLevel2(ans)} /></div></div>)}
      {logged && stage === 'results' && (
        <div className="min-h-screen p-8 bg-gradient-to-b from-indigo-900 to-pink-900"><div className="max-w-4xl mx-auto"><div className="p-6 rounded-2xl bg-white/5 border border-white/10 text-center"><h2 className="text-4xl font-bold">Results</h2><p className="mt-4 text-white/90">Re:Zero Score: {level1Score} / {reZeroQuestions.length}</p><p className="mt-2 text-white/90">About Me Score: {level2Score} / {aboutMeQuestions.length}</p><div className="mt-6 grid grid-cols-1 gap-4 p-4 bg-white/6 rounded-xl"><div><h4 className="text-2xl font-bold">Re:Zero Answers</h4>{reZeroQuestions.map((q,i)=>(<div key={i} className="text-left mt-2"><div className="font-semibold">Q: {q.q}</div><div>A: {q.choices[q.a]}</div><div>Your answer: {level1Answers ? (reZeroQuestions[i].choices[level1Answers[i]] ?? 'Not answered') : 'Not taken'}</div></div>))}</div><div><h4 className="text-2xl font-bold">About Me Answers</h4>{aboutMeQuestions.map((q,i)=>(<div key={i} className="text-left mt-2"><div className="font-semibold">Q: {q.q}</div><div>Correct: {q.choices[q.a]}</div><div>Your answer: {level2Answers ? (aboutMeQuestions[i].choices[level2Answers[i]] ?? 'Not answered') : 'Not taken'}</div></div>))}</div></div><div className="mt-6"><input placeholder="Enter name for certificate" className="px-4 py-2 rounded-lg bg-white/10 text-white" value={name} onChange={(e)=>setName(e.target.value)} /><div className="mt-4"><Certificate name={name || 'Guest'} score={`${level1Score}/${reZeroQuestions.length} & ${level2Score}/${aboutMeQuestions.length}`} /></div></div></div></div></div>
      )}
    </div>
  );
}
