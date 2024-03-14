(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var aa = this || self;
function ba(a, b, c, d) {
  if (b.j !== c.j) {
    a.status = t;
  } else if (b.id || c.id) {
    a.status = b.id === c.id ? ca : t;
  }
  if (a.status !== t) {
    var e = c.l.reduce((g, m) => {
      da(b, m.key) || g.push(m.key);
      return g;
    }, []);
    e.length && a.g.push({step:ea, I:e.length, B:() => e.forEach(g => c.h.removeAttribute(g))});
    var f = b.l.reduce((g, m) => {
      var k;
      a: {
        for (k = 0; k < c.l.length; k++) {
          if (m.key === c.l[k].key) {
            k = c.l[k].value;
            break a;
          }
        }
        k = void 0;
      }
      k !== m.value && g.push(m);
      return g;
    }, []);
    f.length && a.g.push({step:fa, I:f.length, B:() => f.forEach(g => c.h.setAttribute(g.key, g.value))});
    var h = b.m.reduce((g, m) => {
      var k;
      a: {
        for (k = 0; k < c.m.length; k++) {
          if (m.key === c.m[k].key) {
            k = c.m[k].value;
            break a;
          }
        }
        k = void 0;
      }
      k !== m.value && g.push(m);
      return g;
    }, []);
    h.length && a.g.push({step:ha, I:h.length, B:() => h.forEach(g => {
      c.node instanceof HTMLInputElement && ("value" === g.key && (c.node.value = g.value), "checked" === g.key && (c.node.checked = g.value));
    })});
    b.v !== c.v && a.g.push({step:ia, I:1, B:() => {
      c.node.textContent = b.v;
    }});
    if (d) {
      let g = ja(d, b.node), m = ja(d, c.node), k = [], n = [];
      m.forEach((l, p) => {
        let q = !0;
        g.forEach(r => {
          l.event === r.event && l.hash === r.hash && (q = !1);
        });
        q && k.push(p);
      });
      g.forEach((l, p) => {
        let q = !0;
        m.forEach(r => {
          r.event === l.event && r.hash === l.hash && (q = !1);
        });
        q && n.push(p);
      });
      k.length && a.g.push({step:ka, I:k.length, B:() => {
        k.forEach(l => c.node.removeEventListener(m[l].event, m[l].B));
        k.sort((l, p) => l < p ? 1 : p < l ? -1 : 0).forEach(l => m.splice(l, 1));
        d.g.set(c.node, m);
      }});
      n.length && a.g.push({step:la, I:n.length, B:() => {
        n.forEach(l => {
          c.node.addEventListener(g[l].event, g[l].B);
          m.push({event:g[l].event, B:g[l].B, hash:g[l].hash});
          d.g.set(c.node, m);
        });
      }});
    }
  }
}
function ma(a, b, c, d) {
  let e = b.g.map(() => !1), f = c.g.map(() => !1), h = [], g = [];
  b.g.forEach((n, l) => {
    c.g.forEach((p, q) => {
      e[l] || f[q] || (p = new na(n, p, d), p.status !== t && (p.status === ca || 0 === p.h ? (e[l] = !0, f[q] = !0, h.push({H:l, U:q, L:q}), p.status === ca ? a.m++ : a.l++, a.j.push(p)) : g.push({ba:l, $:q, V:p, Ia:p.h, selected:!1})));
    });
  });
  0 < g.length && (g = g.sort((n, l) => n.V.h < l.V.h ? -1 : n.V.h === l.V.h ? 0 : 1), g.forEach(n => {
    e[n.ba] || f[n.$] || (e[n.ba] = !0, f[n.$] = !0, n.selected = !0, h.push({H:n.ba, U:n.$, L:n.$}), a.j.push(n.V));
  }));
  let m = f.reduce((n, l, p) => l ? n : [...n, p], []);
  m.length && (a.g.push({step:oa, I:m.length, B:() => m.forEach(n => {
    c.node.removeChild(c.g[n].node);
  })}), m.forEach(n => {
    h = h.map(l => n > l.U ? l : {H:l.H, U:l.U, L:l.L - 1});
  }));
  let k = e.reduce((n, l, p) => l ? n : [...n, p], []);
  k.length && (a.g.push({step:pa, I:k.length, B:() => k.forEach(n => {
    c.node.appendChild(b.g[n].node);
  })}), k.forEach(n => h.push({H:n, U:Number.NaN, L:h.length})));
  if (h.reduce((n, l) => n || l.L !== l.H, !1)) {
    let n = h.sort((l, p) => l.H < p.H ? -1 : l.H === p.H ? 0 : 1).map(l => l.L);
    a.g.push({step:qa, I:1, B:() => {
      for (let l = 0; l < n.length; l++) {
        if (l != n[l]) {
          let p = n[l];
          if (c.node instanceof HTMLElement || c.node instanceof SVGElement) {
            let q = c.node.childNodes[l], r = c.node.childNodes[p];
            n.splice(l, 1, l);
            n = n.map(v => v + (v >= l && v < p ? 1 : 0));
            c.node.insertBefore(r, q);
          }
        }
      }
    }});
  }
}
function ra(a) {
  if (a.status === t) {
    return 0;
  }
  let b = 0;
  a.g.forEach(c => b += sa[c.step] * c.I);
  b += sa[ta] * a.l;
  b += sa[ua] * a.m;
  a.j.forEach(c => b += c.h);
  return b;
}
class na {
  constructor(a, b, c, d) {
    this.g = [];
    this.status = va;
    this.j = [];
    this.h = Number.NaN;
    this.m = this.l = 0;
    if (!0 !== d && (ba(this, a, b, c), this.status === t)) {
      return;
    }
    if (u.has(a.h)) {
      d = u.get(a.h);
      if (!u.has(b.h)) {
        var e = b.h.attachShadow({mode:d.mode});
        u.set(b.h, e);
      }
      e = u.get(b.h);
      wa(d, e, c);
    } else {
      u.has(b.h) && (this.status = t, console.log("n\u00e3o tira sr"));
    }
    this.status !== t && (ma(this, a, b, c), this.h = ra(this));
  }
  update() {
    this.j.forEach(a => {
      a.update();
    });
    this.g.forEach(a => {
      try {
        a.B();
      } catch (b) {
        console.error(a.step, b);
      }
    });
  }
}
function wa(a, b, c) {
  let d = "string" !== typeof a ? a : xa("div", f => f.innerHTML = a);
  b instanceof ShadowRoot && d instanceof HTMLElement && d.attributes.length && (d = xa("div", f => f.appendChild(d)));
  let e = ya(d);
  b = ya(b);
  (new na(e, b, c, !0)).update();
}
;function ya(a) {
  function b(e) {
    d.currentNode.childNodes.length !== e.g.length ? (d.firstChild(), e = new za(d.currentNode, e), b(e)) : d.nextSibling() ? (e = new za(d.currentNode, e.A), b(e)) : (d.parentNode(), d.currentNode && e.A && b(e.A));
  }
  function c(e) {
    e.g = e.g.filter(f => {
      let h = f.node instanceof Text ? 0 < f.node.textContent.trim().length : !0;
      h || e.node.removeChild(f.node);
      return h;
    });
    e.g.forEach(f => c(f));
  }
  let d = document.createTreeWalker(a, NodeFilter.SHOW_ALL);
  a = new za(a);
  b(a);
  c(a);
  return a;
}
function da(a, b) {
  return b ? a.l.reduce((c, d) => c || d.key === b, !1) : a.node instanceof HTMLElement ? !0 : !1;
}
function Aa(a) {
  let b = [];
  var c = [];
  if (a.node instanceof HTMLElement || a.node instanceof SVGElement) {
    c = a.node.attributes;
    for (let d = 0; d < c.length; d++) {
      b.push(c[d]);
    }
    c = b.reduce((d, e) => {
      "id" === e.localName && (a.id = e.value);
      d.push({key:e.localName, value:e.value});
      return d;
    }, []);
  }
  return c;
}
class za {
  constructor(a, b) {
    b && (this.A = b);
    this.node = a;
    this.g = [];
    b && b.g.push(this);
    this.v = null;
    this.l = Aa(this);
    this.m = [];
    this.id = "";
    a instanceof HTMLElement || a instanceof SVGElement ? (this.h = a, this.j = this.h.localName, a instanceof HTMLInputElement && (this.m.push({key:"value", value:a.value}), this.m.push({key:"checked", value:a.checked}))) : a instanceof Text ? (this.j = Ba, this.v = a.textContent) : a instanceof ShadowRoot ? this.j = Ca : a instanceof Comment ? this.j = Da : (this.j = a.constructor.name, console.log("TYPE", a, this.j));
  }
  toString(a = 0) {
    const b = "    ".repeat(a);
    let c = `${b}<${this.j}>\n`;
    this.g.forEach(d => {
      c += `${d.toString(a + 1)}`;
    });
    return c += `${b}</${this.j}>\n`;
  }
}
;var pa = 1, oa = 2, qa = 3, ia = 4, fa = 5, ea = 6, ha = 7, la = 8, ka = 9, ta = 10, ua = 11, Ba = "-Text", Da = "!--", Ca = "div", t = 1, va = 2, ca = 3;
function ja(a, b) {
  return (a = a.g.get(b)) ? a : [];
}
class Ea {
  constructor() {
    this.g = new WeakMap();
    this.h = (a, b, c) => {
      let d = this.g.get(a);
      d || (d = [], this.g.set(a, d));
      if (!Fa.has(c)) {
        a = c.toString();
        let e = 0;
        for (let f = 0; f < a.length; f++) {
          e = (e << 5) - e + a.charCodeAt(f), e |= 0;
        }
        Fa.set(c, e);
      }
      a = Fa.get(c);
      d.push({event:b, B:c, hash:a});
    };
  }
}
var Fa = new WeakMap();
const sa = {[ea]:1, [fa]:1, [ha]:1, [pa]:10, [ia]:1, [qa]:1, [oa]:10, [la]:1, [ka]:1, [ta]:-100.11, [ua]:-100.33, [12]:0};
function Ga() {
  let a = window.location.search.substring(1).split("&"), b = {};
  for (let c = 0; c < a.length; ++c) {
    let d = a[c].split("=", 2);
    b[d[0]] = 1 == d.length ? "" : decodeURIComponent(d[1].replace(/\+/g, " "));
  }
  return b;
}
const w = {G:{qa:function(a, b, c) {
  let d = 1;
  for (;;) {
    var e = 0;
    for (var f = 2; f <= d; f++) {
      e += Math.pow(b, f - 1);
    }
    e = a - e;
    f = [];
    for (let h = 1; h <= d; h++) {
      let g = e % b;
      f.splice(0, 0, c(g));
      e -= g;
      e /= b;
    }
    if (e) {
      d++;
    } else {
      return f.join("");
    }
  }
}, na:function(a, b) {
  return w.G.oa(new Date(a), b);
}, oa:function(a, b) {
  const c = a.getDate().toString().padStart(2, "0"), d = (a.getMonth() + 1).toString().padStart(2, "0"), e = a.getFullYear(), f = a.getHours().toString().padStart(2, "0"), h = a.getMinutes().toString().padStart(2, "0");
  a = a.getSeconds().toString().padStart(2, "0");
  return b ? `${c}/${d}/${e} ${f}:${h}:${a}` : `${d}/${c}/${e} ${f}:${h}:${a}`;
}, Ha:function(a) {
  const [b, c, d] = a.split("-").map(e => parseInt(e, 10));
  return new Date(b, c - 1, d);
}, xa:function(a, b) {
  const [c, d, e] = a.split("-").map(f => parseInt(f, 10));
  return w.G.oa(new Date(c, d - 1, e), b);
}, ya:function(a) {
  return w.G.wa(new Date(a));
}, wa:function(a) {
  return `${a.getFullYear()}-${(a.getMonth() + 1).toString().padStart(2, "0")}-${a.getDate().toString().padStart(2, "0")}`;
}, Ka:function(a) {
  return w.G.qa(a, 26, b => String.fromCharCode(65 + b));
}, La:function(a) {
  return w.G.qa(a, 64, b => 10 > b ? String.fromCharCode(48 + b - 0) : 36 > b ? String.fromCharCode(65 + b - 10) : 62 > b ? String.fromCharCode(97 + b - 36) : 62 === b ? "-" : "+");
}}, debug:{Ma:function() {
  let a = new Date();
  return a.getHours().toString().padStart(2, "0") + ":" + a.getMinutes().toString().padStart(2, "0") + ":" + a.getSeconds().toString().padStart(2, "0");
}}, Aa:function(a) {
  return Math.floor((new Date(a) - a) / 6E4);
}, J:{Ea:function(a = 200, b = 440, c = 1, d = "sine") {
  const e = new (window.AudioContext || window.webkitAudioContext)(), f = e.createOscillator(), h = e.createGain();
  f.connect(h);
  h.connect(e.destination);
  h.gain.value = c;
  f.frequency.value = b;
  f.type = d;
  f.start(e.currentTime);
  f.stop(e.currentTime + 0.001 * a);
}, pa:function(a = 200, b = 400, c = 1, d = "square") {
  const e = new (window.AudioContext || window.webkitAudioContext)(), f = e.createOscillator(), h = e.createGain();
  f.connect(h);
  h.connect(e.destination);
  h.gain.value = c;
  f.frequency.value = b;
  f.type = d;
  f.start();
  f.stop(e.currentTime + a / 1000);
}, Na:() => w.J.pa(100, 400, 0.2, "square"), za:() => w.J.pa(200, 300, 0.3, "sawtooth"), T:function() {
  const a = new (window.AudioContext || window.webkitAudioContext)(), b = a.createOscillator();
  b.type = "sine";
  b.frequency.setValueAtTime(440, a.currentTime);
  const c = a.createGain();
  c.gain.setValueAtTime(0, a.currentTime);
  c.gain.linearRampToValueAtTime(0.3, a.currentTime + 0.01);
  c.gain.linearRampToValueAtTime(0, a.currentTime + 0.3);
  b.connect(c);
  c.connect(a.destination);
  b.start(a.currentTime);
  b.stop(a.currentTime + 0.3);
}}};
var z = new Ea(), Ha = new WeakMap(), u = new WeakMap();
class Ia {
  constructor(a) {
    this.g = a;
  }
  get h() {
    return this.g;
  }
  get button() {
    return this.g;
  }
  get style() {
    return this.g;
  }
  get l() {
    return this.g;
  }
  get j() {
    return this.g;
  }
  get a() {
    return this.g;
  }
  get label() {
    return this.g;
  }
}
function xa(a, b) {
  a = document.createElement(a);
  b && b(a);
  return a;
}
async function A(a, b, c) {
  a = document.createElement(a);
  c && c.appendChild(a);
  c = new Ja(a);
  b && await b(c);
  return c;
}
async function Ka(a, b) {
  let c = await A(b && "tagName" in b ? b.tagName.toLocaleLowerCase() : "div");
  c.e.innerHTML = a;
  b.appendChild(c.j);
  return c;
}
function B(a, b, c) {
  let d = [];
  c(e => d.push(e));
  a.data.push({sa:b, rules:d.join("")});
}
function La(a, b) {
  xa("style", c => {
    b.e.appendChild(c);
    c.innerText = a.data.map(d => `${d.sa} { ${d.rules} }`).join(" ");
  });
}
class Ma {
  constructor() {
    this.data = [];
  }
  add(a, b) {
    this.data.push({sa:a, rules:b});
  }
}
function Na(a) {
  return new Proxy(a, {get:(b, c) => "addEventListener" === c ? (d, e, f) => {
    z.h(b, d, e);
    return b.addEventListener(d, e, f);
  } : "function" === typeof b[c] ? b[c].bind(b) : b[c], set:(b, c, d) => {
    "string" === typeof c && c.toLowerCase().startsWith("on") ? (c = c.substring(2), z.h(b, c, d), b.addEventListener(c, d)) : b[c] = d;
    return !0;
  }});
}
async function C(a, b, c) {
  return A(b, c, a.h);
}
async function Oa(a, b) {
  return Ka(b, a.h);
}
function Pa(a, b) {
  let c = new Ma();
  b(c);
  La(c, a);
}
async function Qa(a) {
  var b = await C(a, "div");
  if ("attachShadow" in a.h) {
    return b = b.h.attachShadow({mode:"open"}), u.set(a.h, b), new Ja(b);
  }
  throw Error("attachShadow");
}
class Ja {
  constructor(a) {
    this.h = a;
    this.l = Na(a);
    this.g = new Ia(a);
  }
  get e() {
    return this.l;
  }
  get j() {
    return this.h;
  }
}
async function Ra(a, b, c) {
  b = 1000 / b;
  let d = Date.now();
  d - a[0] > b && (await c(), a[0] = d);
}
async function Sa(a, b) {
  var c = void 0;
  c = 20;
  let d = await A("div");
  Ha.has(a) || Ha.set(a, [0]);
  let e = Ha.get(a);
  Ra(e, c, async() => {
    await b(d);
    wa(d.j, a, z);
  });
}
async function Ta(a, b) {
  A("div", async c => {
    await b(c);
    wa(c.j, a, z);
  });
}
function Ua(a, b) {
  let c = a;
  do {
    c.style.height = "100%";
    c.style.width = "100%";
    c.style.margin = 0;
    if (!b || "HTML" === c.tagName) {
      break;
    }
    c = c.parentNode;
  } while (c);
  !b && a instanceof HTMLElement && (b = () => a.style.height = `${0.5 * a.offsetWidth}px`, window.addEventListener("resize", b), b());
}
;function D(a) {
  return new Promise((b, c) => {
    a.onsuccess = () => b(a.result);
    a.onerror = () => c(a.error);
  });
}
function Va(a, b) {
  a = indexedDB.open(a);
  a.onupgradeneeded = d => {
    d = d.target.result;
    d.objectStoreNames.contains(b) || d.createObjectStore(b);
  };
  const c = D(a);
  return (d, e) => c.then(f => {
    f = f.transaction(b, d).objectStore(b);
    return e(f);
  });
}
let Wa;
function E() {
  Wa ||= Va("keyval-store", "keyval");
  return Wa;
}
function F(a, b) {
  return a("readonly", c => {
    c = c.openCursor();
    c.onsuccess = d => {
      if (d = d.target.result) {
        b(d), d.continue();
      }
    };
    return D(c);
  });
}
class Xa {
  constructor(a) {
    this.g = Va(...a.split("."));
  }
  async get(a) {
    return G.get(a, this.g);
  }
  async set(a, b) {
    return G.set(a, b, this.g);
  }
  async P(a) {
    return G.P(a, this.g);
  }
  async clear() {
    return G.clear(this.g);
  }
}
async function Ya(a) {
  a.g = [];
  var b = await indexedDB.databases();
  for (let c of b) {
    c.name && (b = await Za(c.name), a.g.push({name:c.name, version:c.version ?? -1, ta:b.ta, keys:b.keys}));
  }
  for (let c of a.g) {
    for (let d of c.keys) {
      console.log(`db:'${c.name}', v:${c.version}, store:'${d.store}', key:'${d.key}'`);
    }
  }
}
async function Za(a) {
  const b = indexedDB.open(a);
  return new Promise((c, d) => {
    b.onsuccess = async function() {
      const e = b.result, f = Array.from(e.objectStoreNames), h = [];
      for (let g of f) {
        const m = e.transaction(g, "readwrite").objectStore(g).getAllKeys();
        await (async() => {
          let k = await D(m);
          for (let n of k) {
            h.push({store:g, key:n});
          }
        })();
      }
      e.close();
      c({ta:f, keys:h});
    };
    b.onerror = () => d(b.error);
  });
}
class $a {
  constructor() {
    this.g = [];
    Ya(this);
  }
  async clear() {
    const a = await indexedDB.databases();
    for (let b of a) {
      b.name && indexedDB.deleteDatabase(b.name);
    }
  }
}
const G = {get:function(a, b = E()) {
  return b("readonly", c => D(c.get(a)));
}, set:function(a, b, c = E()) {
  return c("readwrite", d => {
    d = d.put(b, a);
    return D(d);
  });
}, update:function(a, b, c = E()) {
  return c("readwrite", d => new Promise((e, f) => {
    const h = d.get(a);
    h.onsuccess = () => {
      try {
        const g = b(h.result, a), m = d.put(g, a);
        e(D(m));
      } catch (g) {
        f(g);
      }
    };
    h.onerror = function() {
      f(h.error);
    };
  }));
}, P:function(a, b = E()) {
  return b("readwrite", c => D(c.delete(a)));
}, clear:function(a = E()) {
  return a("readwrite", b => D(b.clear()));
}, Ja:function(a, b = E()) {
  return b("readonly", c => Promise.all(a.map(d => D(c.get(d)))));
}, Ga:F, keys:function(a = E()) {
  const b = [];
  return F(a, c => b.push(c.key)).then(() => b);
}, values:function(a = E()) {
  const b = [];
  return F(a, c => b.push(c.value)).then(() => b);
}, entries:function(a = E()) {
  const b = [];
  return F(a, c => b.push({key:c.key, value:c.value})).then(() => b);
}, Fa:Va, O:Xa, Da:$a};
var H = a => {
  a = a.folder && a.name ? `${a.folder}/${a.name}` : a.folder ? a.folder : a.name;
  a = a.split("/").reduce((b, c) => {
    c && b.push(c);
    return b;
  }, []);
  return a.join("/");
}, ab = new Map();
function bb(a, b) {
  b && ab.clear();
  if (a && a.name && a.mimeType) {
    b = a.name.split(".");
    var c = 1 < b.length ? b[b.length - 1] : "";
    b = ab.get(c);
    b || (b = new Map(), ab.set(c, b));
    c = b.get(a.mimeType);
    c || (c = [], b.set(a.mimeType, c));
    c.push(a);
  }
}
;var I = G, J = w;
function cb(a, b, c) {
  return a.map(d => db(d, b, c));
}
function db(a, b, c) {
  a.size && "string" === typeof a.size && (a.size = parseInt(a.size, 10));
  a.folder = c;
  a.g = b;
  a.isfile = "application/vnd.google-apps.folder" == a.mimeType ? !1 : !0;
  return a;
}
async function L(a, b, c, d) {
  c = "object" === typeof c ? c : new Headers({Authorization:`Bearer ${c}`});
  b = {method:b, headers:c};
  d && (b.body = d);
  try {
    const e = await fetch(a, b);
    if (!e.ok) {
      let f = await e.json();
      f.error && f.error.errors && f.error.errors.forEach(h => {
        console.log("Erro:", h.message);
        console.log(h.reason);
        switch(h.reason) {
          case "quotaExceeded":
            console.log("Voc\u00ea excedeu uma quota do Google Drive.");
            break;
          case "userRateLimitExceeded":
            console.log("Voc\u00ea excedeu a quota de limita\u00e7\u00e3o de taxa de usu\u00e1rio.");
            break;
          case "rateLimitExceeded":
            console.log("Voc\u00ea excedeu a quota de limita\u00e7\u00e3o de taxa do aplicativo.");
            break;
          default:
            console.log("Erro desconhecido.");
        }
      });
    }
    return e;
  } catch (e) {
    return null;
  }
}
async function eb(a, b, c = "") {
  let d = `https://www.googleapis.com/drive/v3/files?q=${encodeURIComponent(`('${b}' in parents)`)}&fields=${encodeURIComponent("files(id,name,modifiedTime,size,mimeType,trashed)")}`;
  a = await L(d, "GET", a);
  if (!a) {
    return [];
  }
  a = (await a.json()).files;
  return cb(a, b, c);
}
async function fb(a, b, c = null, d = null, e = null, f = null, h = null) {
  const g = {name:b};
  e && (g.mimeType = e);
  if (null !== d !== (null !== c)) {
    throw Error("inconsist\u00eancia par\u00e2metros");
  }
  c && (g.parents = [c]);
  f && (g.modifiedTime = f);
  e = new FormData();
  e.append("metadata", new Blob([JSON.stringify(g)], {type:"application/json"}));
  h && e.append("file", h, b);
  a = await L("https://www.googleapis.com/upload/drive/v3/files?uploadType=multipart&fields=id,name,modifiedTime,size,mimeType,trashed", "POST", a, e);
  if (!a) {
    throw Error("Erro ao criar arquivo:");
  }
  if ("error" in a) {
    throw Error("Erro ao atualizar arquivo:");
  }
  a = await a.json();
  return db(a, c ?? "root", d ?? "");
}
async function gb(a, b, c = "", d = -1) {
  const e = [];
  for (b = [[b, c, 0]]; 0 < b.length;) {
    const [h, g, m] = b.shift();
    c = e;
    var f = await eb(a, h, g);
    for (const k of f) {
      if (f = `${g}/${k.name}`, "application/vnd.google-apps.folder" === k.mimeType) {
        if (-1 === d || m + 1 <= d) {
          b.push([k.id, f, m + 1]), c.push(k);
        }
      } else {
        c.push(k);
      }
    }
  }
  return e;
}
async function hb(a, b) {
  a = await L(`https://www.googleapis.com/drive/v3/files/${b}?alt=media`, "GET", a);
  if (!a || !a.ok) {
    throw Error("Erro na API do Google Drive:" + a?.status);
  }
  return await a.blob();
}
async function ib(a, b, c = null, d = null) {
  return fb(a, b, c, d, "application/vnd.google-apps.folder");
}
async function jb(a, b) {
  await L(`https://www.googleapis.com/drive/v3/files/${b}`, "DELETE", a);
}
async function kb(a, b, c, d) {
  b = `https://www.googleapis.com/upload/drive/v3/files/${b}?uploadType=multipart${"&fields=id,name,modifiedTime,size,mimeType,trashed"}`;
  d = {modifiedTime:d};
  const e = new FormData();
  e.append("metadata", new Blob([JSON.stringify(d)], {type:"application/json"}));
  e.append("file", c);
  a = await L(b, "PATCH", a, e);
  if (!a) {
    throw Error("Erro ao atualizar arquivo:");
  }
  if ("error" in a) {
    throw console.log(a), Error("Erro ao atualizar arquivo:");
  }
  return await a.json();
}
;async function lb(a) {
  "file" === a.handle.kind && (a.g = await a.handle.getFile(), a.size = a.g.size, a.mimeType = a.g.type, a.modifiedTime = w.G.na(a.g.lastModified, !1));
}
class mb {
  constructor(a, b) {
    this.folder = a;
    this.name = b.name;
    this.handle = b;
    "file" === b.kind ? this.isfile = !0 : "directory" === b.kind && (this.isfile = !1);
  }
  async update(a) {
    if ("file" === this.handle.kind) {
      this.handle = await nb(await this.handle, a), await lb(this);
    } else {
      throw Error("invalid type");
    }
  }
}
async function ob(a, b) {
  return a.getDirectoryHandle(b, {create:!0});
}
async function pb(a, b) {
  try {
    return await a.getDirectoryHandle(b, {create:!1});
  } catch (c) {
    return null;
  }
}
async function nb(a, b) {
  let c = await a.createWritable();
  await c.write(b);
  await c.close();
  return a;
}
async function qb(a, b) {
  console.log(b);
  let c = b.split("/");
  console.log(c);
  for (let d of c) {
    if (d && (a = await pb(a, d), !a)) {
      throw Error("n\u00e3o achado diret\u00f3rio [" + d + "] de " + b);
    }
  }
  return a;
}
async function rb(a, b) {
  const c = await a.getDirectoryHandle(b);
  for await (const d of c.values()) {
    "file" === d.kind ? await c.removeEntry(d.name) : "directory" === d.kind && await rb(c, d.name);
  }
  await a.removeEntry(b, {recursive:!0});
}
async function sb(a, b = "", c = !0) {
  let d = [];
  for await (const f of a.values()) {
    var e = f;
    a = new mb(b, e);
    if ("file" === e.kind) {
      a.isfile = !0, await lb(a), d.push(a);
    } else if ("directory" === e.kind) {
      a.isfile = !1;
      e = await sb(e, b ? `${b}/${e.name}` : e.name);
      if (c) {
        for (let h of e) {
          d.push(h);
        }
      } else {
        a.s = e;
      }
      d.push(a);
    }
  }
  return d;
}
async function tb(a = null) {
  let b = {};
  if (null !== a) {
    let c = "desktop documents downloads music pictures videos".split(" ");
    "FileSystemDirectoryHandle" === (a?.constructor.name ?? "") || c.includes(a) ? b.startIn = a : "string" === typeof a && (b.id = a);
  }
  try {
    return await window.showDirectoryPicker(b);
  } catch (c) {
    return null;
  }
}
async function ub(a) {
  try {
    return "granted" === await a.queryPermission() || "granted" === await a.requestPermission();
  } catch (b) {
    return !1;
  }
}
var vb = mb;
async function wb(a, b, c, d) {
  b = b.split("/");
  for (let e of b) {
    e && (a = await ob(a, e));
  }
  a = await a.getFileHandle(c, {create:!0});
  c = await a.createWritable();
  await c.write(d);
  await c.close();
  return a;
}
async function xb(a, b, c) {
  a = await qb(a, b);
  a.removeEntry(c);
}
async function yb(a, b) {
  b = b.split("/");
  let c = b.pop();
  b.length && (a = await qb(a, b.join("/")));
  await rb(a, c);
}
var zb = {la:function(a, b) {
  a = a.replace(/\/$/, "");
  b = b.replace(/\/$/, "");
  return b.startsWith(a) ? b === a ? !1 : "/" === b[a.length] : !1;
}};
const M = new I.O("fileApp.data");
async function Ab(a, b = !1) {
  b || null === a.g ? (await a.l(), a.g && a.files.length && await M.set(a.g, a.files)) : (b = await M.get(a.g), a.files = b ? b : []);
}
class Bb {
  constructor() {
    this.files = [];
    this.g = null;
  }
  R() {
    return !0;
  }
  async l() {
  }
  async N() {
  }
  async K() {
  }
  async v() {
  }
  async A() {
  }
  async j() {
    return null;
  }
  async fa() {
    this.g && await M.P(this.g);
  }
}
function N(a) {
  return a.split("/").filter(b => !!b).join("/");
}
function O(a, b) {
  for (let c of a.files) {
    if (c === b) {
      return c;
    }
  }
  throw Error("inconsist\u00eancia fileSource");
}
async function Cb(a) {
  try {
    return await (await fetch(a.ha)).text();
  } catch (b) {
    throw b;
  }
}
async function P(a) {
  if (a.m && 20 > J.Aa(a.ea)) {
    return a.m;
  }
  let b = await Cb(a);
  return b ? (a.m = b, a.ea = new Date(), b) : "";
}
class Db extends Bb {
  constructor() {
    super();
    this.F = this.ha = "";
    this.h = new Map();
    this.D = void 0;
    this.ea = this.m = null;
  }
  R(a) {
    bb(a, null === a);
    if (null === a) {
      return this.h = new Map(), !1;
    }
    let b = O(this, a);
    if (b.trashed || "application/vnd.google-apps.spreadsheet" === b.mimeType) {
      return !1;
    }
    a = H(a).split("/").filter(c => !!c).join("/");
    b.isfile ? this.h.set(N(b.folder), b.g) : this.h.set(N(a), b.id);
    return !0;
  }
  async l() {
    try {
      this.files = await gb(await P(this), this.F, void 0, this.D);
    } catch (a) {
      alert("Erro ao acessar o GDRIVE");
    }
  }
  async K(a) {
    a = O(this, a);
    let b = await P(this);
    return hb(b, a.id);
  }
  async v(a) {
    let b = O(this, a);
    a = await P(this);
    await jb(a, b.id);
    this.files = this.files.filter(c => c !== b);
    await M.set(this.g, this.files);
  }
  async N(a, b, c) {
    var d = await P(this);
    if (b) {
      return d = O(this, b), a = (new Date(a.modifiedTime)).toISOString(), b = await P(this), c = await kb(b, d.id, c, a), d.modifiedTime = c.modifiedTime, d.size = parseInt(c.size, 10), await M.set(this.g, this.files), d;
    }
    var e = this.F;
    b = a.folder.split("/");
    let f = "/", h;
    for (let g = 0; g < b.length; g++) {
      if (!b[g]) {
        continue;
      }
      h = f;
      f = f + "/" + b[g];
      let m = N(f);
      this.h.has(m) ? e = this.h.get(m) : (e = await ib(d, b[g], e, h), this.files.push(e), e = e.id);
    }
    c = await fb(d, a.name, e, a.folder, a.mimeType, (new Date(a.modifiedTime)).toISOString(), c);
    this.files.push(c);
    await M.set(this.g, this.files);
    return c;
  }
  async A(a) {
    var b = N(a);
    b = this.h.get(b);
    if (!b) {
      throw Error("Caminho n\u00e3o localizado " + a);
    }
    let c = await P(this);
    await jb(c, b);
    this.files = this.files.filter(d => !(zb.la(a, H(d)) || H(d) === a));
    await M.set(this.g, this.files);
  }
}
function Eb(a, b) {
  for (let c of a.files) {
    if (c === b) {
      return c;
    }
  }
  throw Error("inconsist\u00eancia fileSource " + (b?.folder ?? "_") + "/" + (b?.name ?? "_"));
}
class Fb extends Bb {
  constructor() {
    super();
    this.handle = null;
  }
  get h() {
    return (this.g ?? "") + "_handle";
  }
  async l() {
    let a = await M.get(this.h);
    (this.handle = await ub(a) ? a : await tb(a)) && await ub(this.handle) ? (M.set(this.h, this.handle), this.files = await sb(this.handle, "", !0)) : (this.handle = null, this.files = []);
  }
  async N(a, b, c) {
    if (!this.handle) {
      return null;
    }
    if (b) {
      return a = Eb(this, b), await a.update(c), await M.set(this.g, this.files), a;
    }
    c = await wb(this.handle, a.folder, a.name, c);
    a = new vb(a.folder, c);
    await lb(a);
    this.files.push(a);
    await M.set(this.g, this.files);
    return a;
  }
  async K(a) {
    return a ? await Eb(this, a).handle.getFile() : null;
  }
  async v(a) {
    if (!this.handle) {
      throw Error("no handle");
    }
    await xb(this.handle, a.folder, a.name);
    this.files = this.files.filter(b => b !== a);
    await M.set(this.g, this.files);
  }
  async A(a) {
    if (!this.handle) {
      throw Error("no handle");
    }
    await yb(this.handle, a);
    this.files = this.files.filter(b => !(zb.la(a, H(b)) || H(b) === a));
    await M.set(this.g, this.files);
  }
  async j() {
    if (!this.g) {
      return !1;
    }
    let a = await M.get(this.h);
    if (await ub(a)) {
      return this.handle = a, !0;
    }
    (this.handle = await tb(a)) && M.set(this.h, this.handle);
    return !!this.handle;
  }
  async fa() {
    this.g && (await M.P(this.g), await M.P(this.h));
  }
}
;function Gb(a) {
  a.j = [];
  a.aa = [];
  a.v = [];
  a.l = -1;
  a.m = [];
  a.F = [0, 0];
  a.D = [0, 0];
  a.s.map(async b => Gb(b));
}
function Q(a, b = !1) {
  return (() => 1 === a.u ? [a] : b && 2 === a.u ? a.s.map(c => Q(c, !0)).flat() : Hb(a).some(c => 5 === a.j[c] || 1 === a.j[c]) ? a.s.map(c => Q(c, !0)).flat(1) : [])();
}
function Hb(a) {
  return a.M.reduce((b, c, d) => {
    b.includes(d) || b.push(d);
    return b;
  }, []);
}
function Ib(a, b, c, d = null) {
  function e(g, m) {
    for (let k of f) {
      if ([g, m].includes(k)) {
        return k;
      }
    }
    return 0;
  }
  if (1 === a.u) {
    let g = [0, 0];
    if (a.o[b] || a.o[c]) {
      !a.o[b] && a.o[c] ? g[1] = 3 : a.o[b] && !a.o[c] ? g[0] = 3 : g = a.o[b].size === a.o[c].size ? [1, 1] : [2, 2];
    }
    d && (0 !== g[0] && d(a.o[b]) && (g[0] = 0), 0 !== g[1] && d(a.o[c]) && (g[1] = 0));
    return g;
  }
  let f = [2, 3, 1, 0], h = [0, 0];
  a.s.forEach(g => {
    g = Ib(g, b, c, d);
    h[b] = e(h[b], g[b]);
    h[c] = e(h[c], g[c]);
  });
  return h;
}
function R(a, b) {
  return 1 === a.u ? a.o[b]?.size ?? 0 : a.s.reduce((c, d) => R(d, b) + c, 0);
}
function Jb(a, b) {
  return 1 === a.u ? a.o[b] ? 1 : 0 : a.s.reduce((c, d) => Jb(d, b) + c, 0);
}
function Kb(a, b) {
  return 1 === a.u ? 0 : (0 < Jb(a, b) ? 1 : 0) + a.s.reduce((c, d) => Kb(d, b) + c, 0);
}
function S(a, b, c) {
  let d = c ? (new Date()).toISOString() : "1970-01-01T00:00:00.000Z";
  if (1 === a.u) {
    return a.o[b]?.modifiedTime ?? d;
  }
  let e = new Date(d);
  2 === a.u && a.s.forEach(f => {
    if (f = S(f, b, c)) {
      var h = new Date(f);
      if (c && h < e || h > e) {
        d = f, e = h;
      }
    }
  });
  return d;
}
function Lb(a, b, c, d) {
  let e = `${b}/${c.replace("/", "\u2215")}`.split("/"), f = a;
  e.forEach((h, g) => {
    if (h) {
      let m = h.replace("\u2215", "/");
      g !== e.length - 1 || 2 === d ? (g = f.s.find(k => k.name === h && 2 === k.u), g || (g = new Mb(h, 2, f), g.name = m)) : (g = f.s.find(k => k.name === h && k.u === d), g || (g = new Mb(h, d, f), g.name = m));
      f = g;
    }
  });
  return f;
}
class Mb {
  constructor(a, b, c = null) {
    this.name = a;
    this.h = c && c.h ? `${c.h}/${a}` : a;
    this.u = b;
    this.g = c;
    this.s = [];
    this.A = this.h.split("/").reduce((d, e) => d + (e ? 1 : 0), 0);
    this.o = [];
    this.M = [];
    this.j = [];
    this.aa = [];
    this.v = [];
    this.l = -1;
    this.m = [];
    this.F = [];
    this.D = [];
    if (c) {
      if (2 !== c.u) {
        throw Error();
      }
      c.s.push(this);
    }
  }
}
;const T = {ia:"\ud83d\udcc1", da:"\ud83d\udcc2", ga:"\ud83d\udd39"};
function U(a) {
  function b(k) {
    let n = 2 === k.u, l = e.includes(k.h);
    n && g.push(k);
    m.reduce((p, q) => {
      q = (q = k.o[q]) ? h(q) : !0;
      return p && q;
    }, !0) || g.push(k);
    n && l && n && l && k.s.map((p, q) => {
      b(p);
      p.l = q;
      m.forEach(r => {
        p.M[r] && (k.m[r] = q);
      });
      m.forEach(r => {
        let v = p.o[r];
        !v || h && h(v) || k.D[r]++;
      });
    });
  }
  function c(k, n, l) {
    k.j[n] = l;
    k.s.forEach(p => c(p, n, l));
  }
  function d(k, n) {
    let l = 2 === k.u, p = e.includes(k.h), [q, r] = m, v = Ib(k, q, r, f.h);
    for (let x of m) {
      if (l ? k.j[x] = n ? p ? 2 : 1 : 5 : k.o[x] && (k.j[x] = 3), n) {
        var y = v[x];
        let Xb = 1 === y || 0 === y ? "gray" : 3 === y ? "purple" : 2 === y ? "red" : "purple";
        y = K => "function" === typeof K ? K(Xb) : K;
        let Yb = l ? p ? y(T.ia) : y(T.da) : y(T.ga);
        k.aa[x] = function() {
          let K = `span class="${f.K.ua}"`;
          return k.M[x] ? `<${K}>${k.v[x]}</span>${Yb} ${k.name}` : `<${K}>${k.v[x]}</span>`;
        }();
      }
    }
    l && p ? k.s.map(x => d(x, n)) : l && !p && k.s.map(x => d(x, !1));
  }
  let e = a.j, f = a, h = a.h, g = [];
  a.l.forEach(k => Nb(k, a.m));
  Gb(a.m);
  let m = a.A;
  a.m.s.forEach(k => b(k));
  m.forEach(k => g.forEach(n => {
    let l = [], p = n;
    for (; 1 < p.A;) {
      var q = n, r = p, v = k;
      if (1 === r.u) {
        let y = r.o[v];
        y && (h && h(y) || r.g.F[v]++);
      }
      q = r.M[v] ? 1 === r.u ? r.g.F[v] === r.g.D[v] ? "\u2514\u2500" : "\u251c\u2500" : r.l < r.g.m[v] ? "\u2502&nbsp" : r.l == r.g.m[v] ? q.A === r.A ? "\u2514\u2500" : "&nbsp&nbsp" : "ab" : r.l < r.g.m[v] ? "\u2502&nbsp" : "&nbsp&nbsp";
      void 0 === q && (q = "p");
      l.unshift(q);
      p = p.g;
    }
    n.v[k] = l.join("");
  }));
  a.m.s.forEach(k => {
    m.forEach(n => c(k, n, 0));
    d(k, !0);
  });
  a.v = g;
}
async function V(a, b, c = null) {
  null === c ? await Promise.all(a.source.map(d => Ab(d, b))) : a.source[c] && await Ab(a.source[c], b);
  Ob(a);
  U(a);
  a.D = !0;
}
async function Pb(a) {
  a.D ? U(a) : await V(a, !1);
}
function Ob(a) {
  let b = a.source.map(d => d.files), c = new Mb("", 2, null);
  for (let [d, e] of Array.from(b).entries()) {
    a.source[d].R(null), e.forEach(f => {
      if (a.source[d].R(f) && void 0 !== f.folder && void 0 !== f.name) {
        var h = Lb(c, f.folder, f.name, f.isfile ? 1 : 2);
        for (f.isfile && (h.o[d] = f); h.M[d] = !0, h = h.g, h;) {
        }
      }
    });
  }
  a.m = c;
}
async function Qb(a, b, c = null) {
  let d = a.F[b] = !a.F[b];
  a.l = [...a.l.filter(e => e.S !== b), {S:b, ka:d, Y:c, Ba:null}];
  a.l.forEach(e => Nb(e, a.m));
  await Pb(a);
}
async function Rb(a) {
  await Qb(a, 0);
}
async function Sb(a, b) {
  await Qb(a, 1, b);
}
async function Tb(a, b) {
  await Qb(a, 2, b);
}
async function Ub(a) {
  for (let d of a.A) {
    await a.source[d].j();
  }
  let b = a.A.map(d => {
    let e = [], f = [], h = [];
    for (let g of a.g.C[d] ?? []) {
      d = a.v[g - 1];
      2 === d.u && f.push(d);
      for (let m of Q(d, !0)) {
        e.push(m);
      }
      h.push(d);
    }
    return {files:e, va:f, Ca:h};
  }), c = [];
  a.N.forEach((d, e) => {
    let f = b[e].va.reduce((g, m) => g + Kb(m, e), 0), h = b[e].files.reduce((g, m) => g + Jb(m, e), 0);
    f && c.push(`${f} pastas do lado ${d}`);
    h && c.push(`${h} arquivos do lado ${d}`);
  });
  if (confirm(`Confirma apagar: \n ${c.join("\n")}`)) {
    for (let d of a.A) {
      for (let e of b[d].Ca) {
        2 === e.u ? await a.source[d].A(e.h) : await a.source[d].v(e.o[d]);
      }
    }
    a.g.C = [];
    Ob(a);
    U(a);
  }
}
async function Vb(a, b, c) {
  var d = [...(new Set(a.g.C.reduce((e, f) => e.concat(f), [])))];
  d.length || J.J.za();
  await a.source[b].j();
  await a.source[c].j();
  for (let e of d.map(f => a.v[f - 1])) {
    d = Q(e);
    for (let f of d) {
      a.h && a.h(f.o[b]) || (d = Ib(f, b, c, a.h), 0 === d[0] || 2 !== d[0] && 3 !== d[0] || ((d = await a.source[b].K(f.o[b])) ? await a.source[c].N(f.o[b], f.o[c], d) : console.log("sem blob")));
    }
  }
  Ob(a);
  U(a);
}
class Wb {
  constructor() {
    this.source = [];
    this.v = [];
    this.A = [0, 1];
    this.N = ["esquerdo", "direito"];
    this.j = [];
    this.h = null;
    this.D = !1;
    this.F = [!0, !0, !0];
    this.l = [];
    this.l.push({S:0, ka:!1, Y:null, Ba:null});
    this.g = new class {
      constructor() {
        this.C = [[]];
        this.ca = this.ra = this.Z = null;
      }
    }();
    this.K = {ua:""};
    this.now = new Date();
  }
}
function Nb(a, b) {
  let c = a.Y, d = a.ka ? -1 : 1;
  b.s.sort((e, f) => e.u !== f.u ? (2 === e.u ? -1 : 1) * d : 0 === a.S ? e.name.toUpperCase().localeCompare(f.name.toUpperCase()) * d : 1 === a.S && null !== a.Y ? (new Date(S(e, c, !1)) < new Date(S(f, c, !1)) ? -1 : 1) * d : 2 === a.S && null !== a.Y ? (new Date(R(e, c)) < new Date(R(f, c)) ? -1 : 1) * d : 0);
  b.s.forEach(e => Nb(a, e));
}
var Zb = Wb, $b = Db, ac = Fb;
const W = {W:"folder.data", ma:"FT DT-I", ja:"OF"}, bc = new I.O(W.W);
function cc() {
  return [104, 116, 116, 112, 115, 58, 47, 47, 115, 99, 114, 105, 112, 116, 46, 103, 111, 111, 103, 108, 101, 46, 99, 111, 109, 47, 109, 97, 99, 114, 111, 115, 47, 115, 47, 65, 75, 102, 121, 99, 98, 122, 109, 89, 98, 97, 88, 112, 50, 107, 78, 118, 86, 77, 108, 68, 57, 95, 122, 115, 76, 112, 100, 68, 70, 48, 67, 57, 74, 53, 89, 114, 90, 103, 104, 80, 83, 84, 68, 77, 65, 112, 121, 53, 86, 95, 116, 49, 122, 85, 57, 50, 89, 121, 106, 57, 113, 54, 74, 65, 49, 116, 101, 111, 83, 118, 86, 106, 119, 47, 
  101, 120, 101, 99, 63, 116, 111, 107, 101, 110].map(a => String.fromCharCode(a)).join("");
  throw Error();
}
async function dc() {
}
class ec {
  constructor() {
    let a = Ga(), b = a.id ? "_" + a.id : "";
    this.title = b ? "SINCRONIZAR ARQUIVOS" : "RELAT\u00d3RIO VALOR REAL - EXPORTAR ARQUIVOS";
    var c = ["1DsOB_BesxXnEc-mmea9cvauKrSxVGCXg", "1BbOvBSgSeQJk-yx22LAsDI1WnZAANOca"];
    c = a.id ?? c[1];
    this.url = `https://drive.google.com/drive/folders/${c}`;
    T.da = e => `<svg class="${"si"}" fill="${e}"><use href ="#I001"></use></svg>`;
    T.ia = e => `<svg class="${"si"}" fill="${e}"><use href ="#I004"></use></svg>`;
    T.ga = e => `<svg class="${"si"}" style="color:${e}" ><use href ="#ITEM"></use></svg>`;
    this.h = "01/01/2021";
    this.g = new Zb();
    this.g.K.ua = "ftt";
    this.g.h = e => new Date(e.modifiedTime) < new Date(this.h);
    var d = new ac();
    d.g = "local" + b;
    this.g.source.push(d);
    d = new $b();
    d.F = c;
    d.ha = cc();
    d.g = "drive" + b;
    a.level && (d.D = parseInt(a.level, 10));
    console.log(d.D);
    this.g.source.push(d);
  }
  async R() {
    this.h = await bc.get(W.ma) ?? "01/01/2024";
    this.g.j = await bc.get(W.ja) ?? [];
    await Pb(this.g);
  }
}
const fc = function(a, b) {
  class c {
    constructor(d, e) {
      this.h = d;
      this.data = e;
    }
    async X() {
      await Sa(this.h, this.g);
    }
  }
  c.g = new WeakMap();
  c.h = function(d, e, f) {
    const h = c.g;
    if (h.has(d)) {
      return h.get(d);
    }
    let g = new c(d, "function" === typeof b ? b() : b);
    h.set(d, g);
    d = [...f, g];
    g.g = e(d);
    return g;
  };
  return c.h;
}(void 0, new ec());
function gc(a) {
  B(a, "table", b => {
    b("width: 100%;");
    b("border-collapse: collapse;");
    b("font-family: 'Courier New', Courier, monospace;");
  });
  B(a, "table th, table td", b => {
    b("border-right: 1px solid #ddd;");
    b("text-align: left;");
    b("overflow: hidden;");
    b("white-space: nowrap;");
    b("text-overflow: ellipsis;");
    b("max-width: 400px;");
  });
  B(a, "table th:last-child, table td:last-child", b => {
    b("border-right: none;");
  });
  B(a, "table th, table td", b => {
    b("padding: 4px;");
    b("text-align: left;");
    b("border-right: 1px solid #ddd;");
  });
  B(a, "table th:last-child, table td:last-child", b => {
    b("border-right: none;");
  });
  B(a, "table tr:last-child td", b => {
    b("border-bottom: none;");
  });
  B(a, "table tr td,table tr th", b => {
    b("height: 30px;");
    b("white-space: nowrap;");
  });
  B(a, "table th", b => {
    b("background-color: #f2f2f2;");
    b("color: #333;");
    b("position: relative;");
  });
  B(a, "table td", b => {
    b("border-bottom: 1px dotted #ddd;");
  });
}
var hc = a => {
  B(a, ".rz", b => {
    b("display: inline-block;");
    b("width: 5px;");
    b("height: 100%;");
    b("position: absolute;");
    b("right: 0;");
    b("top: 0;");
    b("cursor: col-resize;");
    b("user-select: none;");
  });
}, ic = a => {
  B(a, ".ho tr:hover", b => {
    b("background-color: #ddd;");
  });
}, jc = a => {
  B(a, ".ts", b => {
    b("background-color: rgba(135, 206, 235, 0.5);");
    b("border-top: 1px solid #87CEEB;");
    b("border-bottom: 1px solid #87CEEB;");
  });
};
function kc(a) {
  B(a, ".ib", b => {
    b("display: block;");
  });
  B(a, ".ib a, .ib button", b => {
    b("float: left;");
    b("width: 30px;");
    b("height: 30px;");
    b("display: flex;");
    b("justify-content: center;");
    b("align-items: center;");
    b("background-color: #ddd;");
    b("border: 1px solid #ccc;");
    b("margin: 2px;");
    b("transition: background-color 0.3s;");
    b("outline:none;");
  });
  B(a, ".ib button:focus", () => {
  });
  B(a, ".ib button", b => {
    b("width: auto;");
    b("height: 31px;");
  });
  B(a, ".ib a:hover,.ib button:hover", b => {
    b("filter: brightness(80%);");
  });
  B(a, ".ib svg", b => {
    b("width: 40px;");
    b("height: 40px;");
    b("fill: white;");
  });
}
function lc(a) {
  B(a, ".tc div", b => {
    b("display: flex;");
  });
  B(a, ".tc table", b => {
    b("margin-top: 30px;");
  });
}
function mc(a) {
  B(a, ".dl input", b => {
    b("height: 30px;");
    b("float: right;");
  });
}
var nc = a => {
  B(a, ".ftt", b => {
    b("display: inline-block; transform: scaleY(2.0);");
  });
};
const oc = new I.O(W.W);
function pc(a, b, c, d, e) {
  var f = !1;
  a.C[e] || (a.C[e] = []);
  if (d) {
    f = a.C[e].indexOf(b), -1 < f ? a.C[e].splice(f, 1) : a.C[e].push(b), f = !0;
  } else if (c && null !== a.Z) {
    c = Math.min(b, a.Z);
    const h = Math.max(b, a.Z);
    d || (a.C[e].length = 0);
    d = [e, a.ra].reduce((g, m) => {
      g.includes(m) || g.push(m);
      return g;
    }, []);
    for (let g of d) {
      for (d = c; d <= h; d++) {
        -1 === a.C[g].indexOf(d) && a.C[g].push(d);
      }
    }
  } else {
    a.C = [], a.C[e] = [b], f = !0;
  }
  f && (a.Z = b, a.ra = e);
}
async function qc(a, b) {
  function c(g) {
    g = h + g.clientX - f;
    a.style.width = g + "px";
    oc.set(e, g);
  }
  function d() {
    document.removeEventListener("mousemove", c);
    document.removeEventListener("mouseup", d);
  }
  const e = `width.${b}`;
  if (b = await oc.get(e)) {
    a.style.width = b;
  }
  let [f, h] = [0, 0];
  b = document.createElement("div");
  b.classList.add("rz");
  a.appendChild(b);
  b.addEventListener("mousedown", function(g) {
    f = g.clientX;
    h = a.offsetWidth;
    document.addEventListener("mousemove", c);
    document.addEventListener("mouseup", d);
  });
}
async function rc(a, b, c) {
  a.addEventListener("mousedown", function(d) {
    d.preventDefault();
  });
  a.addEventListener("click", function(d) {
    d.preventDefault();
    var e = d.target.closest("tr");
    e && (e = Array.from(a.querySelectorAll("tr")).indexOf(e), pc(b, e, d.shiftKey, d.ctrlKey, c), b.ca && b.ca());
  });
}
async function sc(a, b, c) {
  a.addEventListener("mousedown", function(d) {
    d.preventDefault();
  });
  a.addEventListener("dblclick", function(d) {
    var e = d.target.closest("tr");
    const f = d.target.closest("td,th");
    d.preventDefault();
    e && (d = Array.from(a.querySelectorAll("tr")).indexOf(e), e = Array.from(e.querySelectorAll("td,th")).indexOf(f), c(d, e, b));
  });
}
;const tc = new I.O(W.W);
async function uc(a, b) {
  let c = a.X.bind(a);
  const d = a.data.g;
  b = await C(await Qa(b), "div");
  b.e.id = "d_div";
  await C(b, "div", async e => {
    await Oa(e, '\n        <svg style="display:none;">\n            <symbol id = "I001" viewBox = "0 -15 512 497"><svg viewBox="0 0 512 512" width="512" xmlns="http://www.w3.org/2000/svg"><g><g><path d="m483.79 135.915h-16.652v-19.381c0-15.555-12.655-28.21-28.21-28.21h-107.241l-15.23-38.423c-3.498-8.826-11.894-14.53-21.389-14.53h-32.412c-4.134 0-7.485 3.351-7.485 7.485s3.351 7.485 7.485 7.485h32.412c3.317 0 6.25 1.992 7.472 5.076l13.043 32.906h-103.09c-3.317 0-6.25-1.993-7.473-5.076l-13.043-32.907h35.848c4.134 0 7.485-3.351 7.485-7.485s-3.351-7.485-7.485-7.485h-167.137c-12.687 0-23.008 10.322-23.008 23.008v21.906c0 4.432-3.606 8.038-8.038 8.038h-1.432c-15.555.002-28.21 12.657-28.21 28.212v121.958c0 4.134 3.351 7.485 7.485 7.485s7.485-3.351 7.485-7.485v-121.958c0-7.301 5.939-13.24 13.24-13.24h1.432c12.687 0 23.008-10.322 23.008-23.008v-21.907c0-4.432 3.606-8.038 8.038-8.038h109.725c3.317 0 6.251 1.992 7.473 5.076l13.218 33.347c3.499 8.826 11.895 14.529 21.389 14.529h226.436c7.3 0 13.24 5.939 13.24 13.24v19.381h-354.539c-15.555 0-28.21 12.655-28.21 28.21v270.309c0 15.01-12.211 27.222-27.221 27.225h-.008c-15.01 0-27.221-12.212-27.221-27.222v-160.928c0-4.134-3.351-7.485-7.485-7.485s-7.485 3.351-7.485 7.485v160.929c0 23.265 18.927 42.192 42.191 42.192h.003 441.596c15.555 0 28.21-12.655 28.21-28.21v-284.294c0-15.556-12.655-28.21-28.21-28.21zm13.24 312.504c0 7.3-5.939 13.24-13.24 13.24h-409.382c6.225-7.354 9.982-16.858 9.982-27.225v-270.309c0-7.301 5.939-13.24 13.24-13.24h386.16c7.3 0 13.24 5.939 13.24 13.24z"/><path d="m125.707 380.061h67.803c4.134 0 7.485-3.351 7.485-7.485s-3.351-7.485-7.485-7.485h-67.803c-4.134 0-7.485 3.351-7.485 7.485s3.351 7.485 7.485 7.485z"/><path d="m233.569 397.689h-107.862c-4.134 0-7.485 3.351-7.485 7.485s3.351 7.485 7.485 7.485h107.862c4.134 0 7.485-3.351 7.485-7.485s-3.351-7.485-7.485-7.485z"/></g></g></svg></symbol>\n            <symbol id = "I004" viewBox = "0 -30 492 482"><svg viewBox="0 0 512 512" width="512" xmlns="http://www.w3.org/2000/svg"><g><g><path d="m485.643 145.982h-58.933v-16.979c0-14.533-11.823-26.357-26.356-26.357h-97.197l-13.701-34.564c-3.287-8.294-11.177-13.654-20.099-13.654h-167.83c-4.134 0-7.485 3.351-7.485 7.485s3.351 7.485 7.485 7.485h54.32c2.745 0 5.171 1.648 6.182 4.199l12.036 30.365c3.287 8.294 11.177 13.654 20.098 13.654h206.191c6.278 0 11.386 5.108 11.386 11.387v16.979h-277.731c-13.383 0-24.638 10.014-26.18 23.292l-44.064 248.131c-.642 3.596-1.542 6.714-2.747 9.533-4.575 10.685-11.54 15.662-21.924 15.663h-.005c-13.299 0-24.119-10.819-24.119-24.118v-289.48c0-6.279 5.108-11.387 11.387-11.387h1.304c11.921 0 21.62-9.698 21.62-21.62v-19.947c0-3.667 2.983-6.65 6.651-6.65h11.344c4.134 0 7.485-3.351 7.485-7.485s-3.351-7.485-7.485-7.485h-11.344c-11.921 0-21.621 9.699-21.621 21.62v19.948c0 3.667-2.983 6.65-6.65 6.65h-1.304c-14.533-.001-26.357 11.823-26.357 26.356v289.48c0 21.553 17.535 39.088 39.089 39.088h.002 402.113c14.302 0 25.98-11.451 26.348-25.666l11.732-68.346c.7-4.074-2.036-7.944-6.111-8.644-4.061-.7-7.943 2.036-8.643 6.111l-11.832 68.923c-.072.419-.108.842-.108 1.267 0 6.278-5.108 11.386-11.386 11.386h-42.633-329.287c2.096-2.863 3.933-6.124 5.496-9.773 1.659-3.878 2.876-8.062 3.721-12.791l44.199-249.037c.665-5.729 5.527-10.049 11.309-10.049h351.634c6.091 0 11.081 4.807 11.374 10.827l-26.608 154.984c-.7 4.074 2.036 7.944 6.11 8.644 4.072.701 7.944-2.036 8.644-6.111l26.73-155.691c.072-.418.108-.842.108-1.267-.001-14.532-11.825-26.356-26.358-26.356zm-291.48-43.336c-2.744 0-5.17-1.648-6.181-4.2l-11.515-29.048h92.889c2.745 0 5.171 1.648 6.182 4.199l11.514 29.048h-92.889z"/><path d="m201.827 369.639c4.134 0 7.485-3.351 7.485-7.485s-3.351-7.485-7.485-7.485h-61.74c-4.134 0-7.485 3.351-7.485 7.485s3.351 7.485 7.485 7.485z"/><path d="m120.627 391.836c0 4.134 3.351 7.485 7.485 7.485h98.217c4.134 0 7.485-3.351 7.485-7.485s-3.351-7.485-7.485-7.485h-98.217c-4.135 0-7.485 3.352-7.485 7.485z"/></g></g></svg></symbol> \n            <symbol id = "I016" viewBox = "0 0 512 512"><svg height="512" viewBox="0 0 512 512" width="512" xmlns="http://www.w3.org/2000/svg"><g><path d="m126.373 182.418h-18.254v41.444h18.254c11.461 0 20.784-9.296 20.784-20.722s-9.324-20.722-20.784-20.722z"/><path d="m423.006 437.605 4.096-3.902h-58.417v55.641z"/><path d="m238.709 182.686v87.167c21.901-2.426 38.989-21.046 38.989-43.584 0-22.537-17.088-41.157-38.989-43.583z"/><path d="m59.417 13.735v67.837h393.166v-67.837c0-7.585-6.15-13.735-13.736-13.735h-365.695c-7.586 0-13.735 6.15-13.735 13.735z"/><path d="m452.583 370.966h-393.166v127.298c0 7.586 6.15 13.735 13.735 13.735h261.555v-95.286c0-9.383 7.606-16.989 16.989-16.989h100.887z"/><path d="m472.979 115.551h-433.958c-7.586 0-13.735 6.15-13.735 13.735v193.966c0 7.586 6.15 13.735 13.735 13.735h433.958c7.586 0 13.735-6.15 13.735-13.735v-193.966c.001-7.585-6.149-13.735-13.735-13.735zm-346.606 142.29h-18.254v29.269c0 9.383-7.606 16.989-16.989 16.989s-16.99-7.606-16.99-16.989v-121.681c0-9.383 7.606-16.989 16.989-16.989h35.243c30.196 0 54.763 24.539 54.763 54.701s-24.566 54.7-54.762 54.7zm107.474 46.258h-12.127c-9.383 0-16.989-7.606-16.989-16.989v-121.681c0-9.383 7.606-16.989 16.989-16.989h12.127c42.915 0 77.829 34.914 77.829 77.829 0 42.916-34.914 77.83-77.829 77.83zm187.024-121.681h-41.165v33.6h22.511c9.383 0 16.989 7.606 16.989 16.989s-7.606 16.989-16.989 16.989h-22.511v37.113c0 9.383-7.606 16.989-16.989 16.989s-16.989-7.606-16.989-16.989v-121.68c0-9.383 7.606-16.989 16.989-16.989h58.154c9.383 0 16.989 7.606 16.989 16.989s-7.607 16.989-16.989 16.989z"/></g></svg></symbol> \n            <symbol id = "ITEM" viewBox = "0 -15 100 85"><svg  viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg"><path d="M50 10 L90 50 L50 90 L10 50 Z" fill="currentColor" stroke = "var(--c_stroke, black)"/></svg></symbol> \n        </svg>\n        ');
  });
  b.e.style.border = "20px solid #F000";
  Pa(b, e => {
    gc(e);
    hc(e);
    ic(e);
    jc(e);
    kc(e);
    lc(e);
    mc(e);
    B(e, ".mn", f => {
      f("display: none;");
      f("position: absolute;");
      f("background-color: #fff;");
      f("border: 1px solid #ccc;");
      f("padding: 5px 0;");
      f("box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);");
    });
    B(e, ".mn div", f => {
      f("padding: 5px 20px;");
      f("cursor: pointer;");
    });
    B(e, ".mn div:hover", f => {
      f("background-color: #f0f0f0;");
    });
    B(e, "table tr th, table tr td", () => {
    });
    B(e, ".si", f => {
      f("width: 1.2em;");
      f("height: 1.2em;");
      f("vertical-align: -0.10em;");
    });
    nc(e);
  });
  await Oa(b, `<h1>${a.data.title}</h1>`);
  await C(b, "div", async e => {
    e.e.classList.add("ib");
    await C(e, "button", async f => {
      async function h() {
        J.J.T();
        f.e.style.cursor = document.body.style.cursor = "wait";
        await V(d, !0, 0);
        await a.X();
        f.e.style.cursor = document.body.style.cursor = "default";
      }
      f.e.innerText = "LER PASTA LOCAL";
      f.e.style.backgroundColor = "SandyBrown";
      f.e.onclick = h;
      f.e.onmousedown = async g => {
        2 === g.button && confirm("ESCOLHER OUTRA PASTA?") && (await d.source[0].fa(), await h());
      };
    });
    await C(e, "button", async f => {
      f.e.innerText = "LER G-DRIVE";
      f.e.style.backgroundColor = "SandyBrown";
      f.e.onclick = async() => {
        J.J.T();
        f.e.style.cursor = document.body.style.cursor = "wait";
        await V(d, !0, 1);
        await a.X();
        f.e.style.cursor = document.body.style.cursor = "default";
      };
    });
    await C(e, "button", async f => {
      f.e.innerText = "ABRIR DRIVE";
      f.e.style.marginLeft = "10px";
      f.e.onclick = () => {
        window.open(a.data.url, "_blank");
      };
    });
    await C(e, "button", async f => {
      f.e.innerText = "UPDLOAD >>";
      f.e.style.marginLeft = "20px";
      f.e.style.backgroundColor = "LightSkyBlue";
      f.e.onclick = async() => {
        J.J.T();
        f.e.style.cursor = document.body.style.cursor = "wait";
        await Vb(d, 0, 1);
        f.e.style.cursor = document.body.style.cursor = "default";
        c();
      };
    });
    await C(e, "button", async f => {
      f.e.innerText = "DOWNLOAD <<";
      f.e.style.marginLeft = "10px";
      f.e.style.backgroundColor = "LightSkyBlue";
      f.e.onclick = async() => {
        J.J.T();
        f.e.style.cursor = document.body.style.cursor = "wait";
        await Vb(d, 1, 0);
        f.e.style.cursor = document.body.style.cursor = "default";
        c();
      };
    });
    await C(e, "div", async f => {
      f.e.classList.add("dl");
      await C(f, "input", async h => {
        h.g.h.type = "date";
        h.g.h.value = J.G.ya(a.data.h);
        h.e.style.marginLeft = "10px";
        h.g.h.title = "MOSTRAR ARQUIVOS MODIFICADOS A PARTIR DESTA DATA:";
        h.e.onchange = async() => {
          let g = J.G.xa(h.g.h.value, !1);
          tc.set(W.ma, g);
          a.data.h = g;
          await V(d, !1);
          c();
        };
      });
    });
    await C(e, "div", async f => {
      f.e.classList.add("mn");
      await C(f, "div", async h => {
        h.e.innerText = "APAGAR";
        h.e.onclick = async() => {
          J.J.T();
          document.body.style.cursor = "wait";
          await Ub(d);
          document.body.style.cursor = "default";
          c();
        };
      });
    });
  });
  await Oa(b, "<br><br>");
  await C(b, "div", async e => {
    let f = await C(e, "div");
    e.e.classList.add("tc");
    await vc(f, d, 0, c);
    await C(f, "div", async h => h.e.style.width = "50px");
    await vc(f, d, 1, c);
  });
}
async function vc(a, b, c, d) {
  await C(a, "table", async e => {
    rc(e.g.j, b.g, c);
    b.g.ca = () => d();
    sc(e.g.j, c, async(f, h, g) => {
      0 === f ? (0 === h && await Rb(b), 1 === h && await Tb(b, g), 2 === h && await Sb(b, g)) : (f = b.v[f - 1].h, h = b.j.indexOf(f), -1 < h ? b.j.splice(h, 1) : b.j.push(f), tc.set(W.ja, b.j), await Pb(b));
      d();
    });
    e.e.oncontextmenu = async f => {
      f.preventDefault();
      let h = 0, g = f.target, m = null;
      for (; 100 > h && !(h++, g = g.parentElement, m = g.querySelector("div.mn"));) {
      }
      m.style.display = "block";
      m.style.left = f.pageX + "px";
      m.style.top = f.pageY + "px";
    };
    e.e.classList.add("ho");
    await C(e, "tr", async f => {
      for (let [h, g] of Array.from(["Nome do Arauivo", "Tamanho", "\u00daltima Modifica\u00e7\u00e3o"]).entries()) {
        await C(f, "th", async m => {
          m.e.innerText = g;
          m.e.style.height = "1em";
          await qc(m.g.l, `${h}`);
        });
      }
    });
    for (let [f, h] of Array.from(b.v).entries()) {
      await C(e, "tr", async g => {
        (b.g.C[c]?.includes(f + 1) ?? !1) && g.e.classList.add("ts");
        let m = h.aa[c] ?? "", k = R(h, c).toLocaleString("pt-BR"), n = J.G.na(S(h, c, !1), !0);
        h.M[c] || (n = k = "");
        try {
          await C(g, "td", async l => {
            l.e.innerHTML = m;
            l.e.style.fontSize = "0.95em";
            l.e.style.overflow = "hidden";
            l.e.style.textOverflow = "ellipses";
          }), await C(g, "td", async l => {
            l.e.innerText = `${k}`;
            l.e.style.textAlign = "right";
            l.e.style.fontSize = "0.8em";
          }), await C(g, "td", async l => {
            l.e.innerText = n;
            l.e.style.textAlign = "center";
            l.e.style.fontSize = "0.8em";
          });
        } catch (l) {
          console.log(f, h.name, l);
        }
      });
    }
  });
}
;new I.O(W.W);
function wc(a) {
  function b(c) {
    let d = c[0];
    return async function(e) {
      await dc();
      e = await C(e, "div");
      e.e.style.display = "flex";
      e.e.style.justifyContent = "center";
      e = await C(e, "div");
      await uc(d, e);
    };
  }
  Ta(a, async function(c) {
    await C(c, "div", async d => {
      d = fc(d.j, b, []);
      await d.data.R();
      await d.X();
    });
  });
}
;function xc(a, b, c = 3) {
  let d = Ga();
  "i" in d && (c = parseInt(d.i, 10));
  Ua(a, b);
  3 == c && wc(a);
}
var X = ["ploft_v1"], Y = aa;
X[0] in Y || "undefined" == typeof Y.execScript || Y.execScript("var " + X[0]);
for (var Z; X.length && (Z = X.shift());) {
  X.length || void 0 === xc ? Y[Z] && Y[Z] !== Object.prototype[Z] ? Y = Y[Z] : Y = Y[Z] = {} : Y[Z] = xc;
}
;}).call(this);
