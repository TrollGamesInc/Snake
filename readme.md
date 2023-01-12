
<!doctype html>
<html lang="en-US">
<head>
<meta charset="utf-8">
<meta content="initial-scale=1, minimum-scale=1, width=device-width" name="viewport">
<title>Play Google Snake</title>
<meta name="description" content="Play the classic snake game on Google. Eat the apples and grow your snake as long as possible." />
<meta name="keywords" content="Play Google Snake Online" />
<meta name="author" content="w3technic" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://snak.ee" />
<meta property="og:site_name" content="Google Snake" />
<meta property="og:title" content="Play Google Snake Online" />
<meta property="og:description" content="Play the classic snake game on Google. Eat the apples and grow your snake as long as possible." />
<meta property="og:image" content="https://snak.ee/thumb.jpeg" />
<meta name="twitter:image:alt" content="Play Google Snake Online" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="robots" content="all" />
<meta name="revisit-after" content="7 days" />
<link rel="canonical" href="https://snak.ee" />
<link rel="home" href="https://snak.ee/" />
<link rel=" shortcut icon" href="favicon.ico" />
<link rel="icon" type="image/x-icon" sizes="16x16" href="favicon.ico" />
<link rel="icon" type="image/png" sizes="180x180" href="180.png" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-title" content="Google Snake" />
<link rel="apple-touch-icon" sizes="180x180" href="180.png" />

<script async src="https://www.googletagmanager.com/gtag/js?id=G-8M7T5YEWXP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-8M7T5YEWXP');
</script>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-6875580793823494" crossorigin="anonymous"></script>
<script nonce="MbQrqGoifFdVWeMKcb2vew==">
        (function() {
            window.google = {
                kEI: 'zvE-Xq3cBYzyapb0lPgB',
                kEXPI: '31',
                kBL: 'YUnL'
            };
            google.sn = 'web';
            google.kHL = 'en-MA';
        })();
        (function() {
            google.lc = [];
            google.li = 0;
            google.getEI = function(a) {
                for (var b; a && (!a.getAttribute || !(b = a.getAttribute("eid")));) a = a.parentNode;
                return b || google.kEI
            };
            google.getLEI = function(a) {
                for (var b = null; a && (!a.getAttribute || !(b = a.getAttribute("leid")));) a = a.parentNode;
                return b
            };
            google.ml = function() {
                return null
            };
            google.time = function() {
                return Date.now()
            };
            google.log = function(a, b, e, c, g) {
                if (a = google.logUrl(a, b, e, c, g)) {
                    b = new Image;
                    var d = google.lc,
                        f = google.li;
                    d[f] = b;
                    b.onerror = b.onload = b.onabort = function() {
                        delete d[f]
                    };
                    google.vel && google.vel.lu && google.vel.lu(a);
                    b.src = a;
                    google.li = f + 1
                }
            };
            google.logUrl = function(a, b, e, c, g) {
                var d = "",
                    f = google.ls || "";
                e || -1 != b.search("&ei=") || (d = "&ei=" + google.getEI(c), -1 == b.search("&lei=") && (c = google.getLEI(c)) && (d += "&lei=" + c));
                c = "";
                !e && google.cshid && -1 == b.search("&cshid=") && "slh" != a && (c = "&cshid=" + google.cshid);
                a = e || "/" + (g || "gen_204") + "?atyp=i&ct=" + a + "&cad=" + b + d + f + "&zx=" + google.time() + c;
                /^http:/i.test(a) && "https:" == window.location.protocol && (google.ml(Error("a"), !1, {
                    src: a,
                    glmm: 1
                }), a = "");
                return a
            };
        }).call(this);
        (function() {
            google.y = {};
            google.x = function(a, b) {
                if (a) var c = a.id;
                else {
                    do c = Math.random(); while (google.y[c])
                }
                google.y[c] = [a, b];
                return !1
            };
            google.lm = [];
            google.plm = function(a) {
                google.lm.push.apply(google.lm, a)
            };
            google.lq = [];
            google.load = function(a, b, c) {
                google.lq.push([
                    [a], b, c
                ])
            };
            google.loadAll = function(a, b) {
                google.lq.push([a, b])
            };
        }).call(this);
        google.f = {};
        (function() {
            document.documentElement.addEventListener("submit", function(b) {
                var a;
                if (a = b.target) {
                    var c = a.getAttribute("data-submitfalse");
                    a = "1" == c || "q" == c && !a.elements.q.value ? !0 : !1
                } else a = !1;
                a && (b.preventDefault(), b.stopPropagation())
            }, !0);
            document.documentElement.addEventListener("click", function(b) {
                var a;
                a: {
                    for (a = b.target; a && a != document.documentElement; a = a.parentElement)
                        if ("A" == a.tagName) {
                            a = "1" == a.getAttribute("data-nohref");
                            break a
                        } a = !1
                }
                a && b.preventDefault()
            }, !0);
        }).call(this);
        (function() {
            google.hs = {
                h: true,
                sie: false
            };
        })();
        (function() {
            var b = [];
            google.jsc = {
                xx: b,
                x: function(a) {
                    b.push(a)
                },
                mm: [],
                m: function(a) {
                    google.jsc.mm.length || (google.jsc.mm = a)
                }
            };
        }).call(this);
        (function() {
            google.em = [];
            google.emn = 3;
            google.snet = true;
            google.spjs = false;
            google.lgm = '';
            google.emw = false;
            google.eme = false;
            google.pdt = 0;
        })();
        (function() {
            var f = ['sb_wiz', 'aa', 'abd', 'aspn', 'async', 'bgd', 'dvl', 'foot', 'kyn', 'lu', 'm', 'mUpTid', 'mpck', 'mu', 'sf', 'tl', 'vs'];
            var c = '{\x22Fkg7bd\x22:{},\x22HcFEGb\x22:{},\x22IvlUe\x22:{},\x22MC8mtf\x22:{},\x22OF7gzc\x22:{},\x22RMhBfe\x22:{},\x22T4BAC\x22:{},\x22TJw5qb\x22:{},\x22TbaHGc\x22:{},\x22Y33vzc\x22:{},\x22ZyRBae\x22:{},\x22aa\x22:{},\x22abd\x22:{\x22abd\x22:false,\x22deb\x22:false,\x22det\x22:false},\x22aspn\x22:{},\x22async\x22:{},\x22bgd\x22:{\x22ac\x22:true,\x22as\x22:true,\x22at\x22:0,\x22ea\x22:true,\x22ed\x22:0,\x22ei\x22:true,\x22el\x22:true,\x22ep\x22:true,\x22er\x22:true,\x22et\x22:0,\x22eu\x22:false,\x22wl\x22:false},\x22cdos\x22:{\x22cdobsel\x22:false},\x22cr\x22:{\x22qir\x22:false,\x22rctj\x22:true,\x22ref\x22:false,\x22uff\x22:false},\x22csi\x22:{},\x22d\x22:{},\x22ddls\x22:{},\x22dvl\x22:{\x22cookie_secure\x22:true,\x22cookie_timeout\x22:86400,\x22driver_ui_type\x22:2,\x22jsc\x22:\x22[null,null,null,30000,null,null,null,2,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,[\\\x2286400000\\\x22,\\\x22604800000\\\x22,2.0]\\n,null,1]\\n\x22,\x22mnr_crd\x22:\x221\x22,\x22msg_err\x22:\x22Location unavailable\x22,\x22msg_gps\x22:\x22Using GPS\x22,\x22msg_unk\x22:\x22Unknown\x22,\x22msg_upd\x22:\x22Update location\x22,\x22msg_use\x22:\x22Use precise location\x22},\x22foot\x22:{\x22pf\x22:true,\x22po\x22:true,\x22qe\x22:false},\x22gf\x22:{\x22pid\x22:196,\x22si\x22:true},\x22hsm\x22:{},\x22iDPoPb\x22:{},\x22jsa\x22:{\x22csi\x22:true,\x22csir\x22:100},\x22kyn\x22:{},\x22llc\x22:{},\x22lu\x22:{},\x22m\x22:{},\x22mUpTid\x22:{},\x22mpck\x22:{\x22me\x22:false},\x22mu\x22:{\x22murl\x22:\x22https://adservice.google.com/adsid/google/ui\x22},\x22mvYTse\x22:{},\x22sb_wiz\x22:{\x22rfs\x22:[],\x22stok\x22:\x22PzxmhUVP_lTJBd3XHYBtuFufji8\x22,\x22ueh\x22:\x229817c073_aa991a9d_cde5ff8a_d79830ee_a5344768\x22},\x22sf\x22:{},\x22tg8oTe\x22:{},\x22tl\x22:{\x22rvkey\x22:\x22AIzaSyC_9Rt88UMjzgg5pIVArnfuIVkJx4zCdTY\x22},\x22uz938c\x22:{},\x22vWNDde\x22:{},\x22vs\x22:{},\x22ws9Tlc\x22:{},\x22yQ43ff\x22:{}}';
            google.pmc = JSON.parse(c);
            google.plm(f);
            if (window.agsa_ext && window.agsa_ext.setNativeUiState) {
                window.agsa_ext.setNativeUiState(0, 0);
            }
        })();
        google.x(null, function() {
            (function() {
                google.drty && google.drty();
            })();
        });
        (function() {
            var b = [function() {
                google.tick && google.tick("load", "dcl")
            }];
            google.dclc = function(a) {
                b.length ? b.push(a) : a()
            };

            function c() {
                for (var a; a = b.shift();) a()
            }
            window.addEventListener ? (document.addEventListener("DOMContentLoaded", c, !1), window.addEventListener("load", c, !1)) : window.attachEvent && window.attachEvent("onload", c);
        }).call(this);
        (function() {
            var f = this || self,
                h = Date.now || function() {
                    return +new Date
                };
            var x = {};
            var aa = function(a, c) {
                if (null === c) return !1;
                if ("contains" in a && 1 == c.nodeType) return a.contains(c);
                if ("compareDocumentPosition" in a) return a == c || !!(a.compareDocumentPosition(c) & 16);
                for (; c && a != c;) c = c.parentNode;
                return c == a
            };
            var ba = function(a, c) {
                    return function(d) {
                        d || (d = window.event);
                        return c.call(a, d)
                    }
                },
                z = function(a) {
                    a = a.target || a.srcElement;
                    !a.getAttribute && a.parentNode && (a = a.parentNode);
                    return a
                },
                A = "undefined" != typeof navigator && /Macintosh/.test(navigator.userAgent),
                ca = "undefined" != typeof navigator && !/Opera/.test(navigator.userAgent) && /WebKit/.test(navigator.userAgent),
                da = {
                    A: 1,
                    INPUT: 1,
                    TEXTAREA: 1,
                    SELECT: 1,
                    BUTTON: 1
                },
                ea = function() {
                    this._mouseEventsPrevented = !0
                },
                F = {
                    A: 13,
                    BUTTON: 0,
                    CHECKBOX: 32,
                    COMBOBOX: 13,
                    FILE: 0,
                    GRIDCELL: 13,
                    LINK: 13,
                    LISTBOX: 13,
                    MENU: 0,
                    MENUBAR: 0,
                    MENUITEM: 0,
                    MENUITEMCHECKBOX: 0,
                    MENUITEMRADIO: 0,
                    OPTION: 0,
                    RADIO: 32,
                    RADIOGROUP: 32,
                    RESET: 0,
                    SUBMIT: 0,
                    SWITCH: 32,
                    TAB: 0,
                    TREE: 13,
                    TREEITEM: 13
                },
                G = {
                    CHECKBOX: !0,
                    FILE: !0,
                    OPTION: !0,
                    RADIO: !0
                },
                H = {
                    COLOR: !0,
                    DATE: !0,
                    DATETIME: !0,
                    "DATETIME-LOCAL": !0,
                    EMAIL: !0,
                    MONTH: !0,
                    NUMBER: !0,
                    PASSWORD: !0,
                    RANGE: !0,
                    SEARCH: !0,
                    TEL: !0,
                    TEXT: !0,
                    TEXTAREA: !0,
                    TIME: !0,
                    URL: !0,
                    WEEK: !0
                },
                fa = {
                    A: !0,
                    AREA: !0,
                    BUTTON: !0,
                    DIALOG: !0,
                    IMG: !0,
                    INPUT: !0,
                    LINK: !0,
                    MENU: !0,
                    OPTGROUP: !0,
                    OPTION: !0,
                    PROGRESS: !0,
                    SELECT: !0,
                    TEXTAREA: !0
                };
            var I = function() {
                    this.h = this.a = null
                },
                K = function(a, c) {
                    var d = J;
                    d.a = a;
                    d.h = c;
                    return d
                };
            I.prototype.g = function() {
                var a = this.a;
                this.a && this.a != this.h ? this.a = this.a.__owner || this.a.parentNode : this.a = null;
                return a
            };
            var L = function() {
                this.i = [];
                this.a = 0;
                this.h = null;
                this.j = !1
            };
            L.prototype.g = function() {
                if (this.j) return J.g();
                if (this.a != this.i.length) {
                    var a = this.i[this.a];
                    this.a++;
                    a != this.h && a && a.__owner && (this.j = !0, K(a.__owner, this.h));
                    return a
                }
                return null
            };
            var J = new I,
                M = new L;
            var O = function() {
                    this.o = [];
                    this.a = [];
                    this.g = [];
                    this.j = {};
                    this.h = null;
                    this.i = [];
                    N(this, "_custom")
                },
                ha = "undefined" != typeof navigator && /iPhone|iPad|iPod/.test(navigator.userAgent),
                P = String.prototype.trim ? function(a) {
                    return a.trim()
                } : function(a) {
                    return a.replace(/^\s+/, "").replace(/\s+$/, "")
                },
                ia = /\s*;\s*/,
                ma = function(a, c) {
                    return function p(b, g) {
                        g = void 0 === g ? !0 : g;
                        var m = c;
                        if ("_custom" == m) {
                            m = b.detail;
                            if (!m || !m._type) return;
                            m = m._type
                        }
                        if ("click" == m && (A && b.metaKey || !A && b.ctrlKey || 2 == b.which || null == b.which &&
                                4 == b.button || b.shiftKey)) m = "clickmod";
                        else {
                            var l = b.which || b.keyCode;
                            ca && 3 == l && (l = 13);
                            if (13 != l && 32 != l) l = !1;
                            else {
                                var e = z(b),
                                    n;
                                (n = "keydown" != b.type || !!(!("getAttribute" in e) || (e.getAttribute("type") || e.tagName).toUpperCase() in H || "BUTTON" == e.tagName.toUpperCase() || e.type && "FILE" == e.type.toUpperCase() || e.isContentEditable) || b.ctrlKey || b.shiftKey || b.altKey || b.metaKey || (e.getAttribute("type") || e.tagName).toUpperCase() in G && 32 == l) || ((n = e.tagName in da) || (n = e.getAttributeNode("tabindex"), n = null != n && n.specified), n = !(n && !e.disabled));
                                if (n) l = !1;
                                else {
                                    n = (e.getAttribute("role") || e.type || e.tagName).toUpperCase();
                                    var q = !(n in F) && 13 == l;
                                    e = "INPUT" != e.tagName.toUpperCase() || !!e.type;
                                    l = (0 == F[n] % l || q) && e
                                }
                            }
                            l && (m = "clickkey")
                        }
                        e = b.srcElement || b.target;
                        l = Q(m, b, e, "", null);
                        b.path ? (M.i = b.path, M.a = 0, M.h = this, M.j = !1, n = M) : n = K(e, this);
                        for (; q = n.g();) {
                            var k = q;
                            var r = void 0;
                            var u = k;
                            q = m;
                            var t = u.__jsaction;
                            if (!t) {
                                var y;
                                t = null;
                                "getAttribute" in u && (t = u.getAttribute("jsaction"));
                                if (y = t) {
                                    t = x[y];
                                    if (!t) {
                                        t = {};
                                        for (var B = y.split(ia), ja = B ? B.length : 0, C = 0; C < ja; C++) {
                                            var w = B[C];
                                            if (w) {
                                                var D = w.indexOf(":"),
                                                    R = -1 != D,
                                                    ka = R ? P(w.substr(0, D)) : "click";
                                                w = R ? P(w.substr(D + 1)) : w;
                                                t[ka] = w
                                            }
                                        }
                                        x[y] = t
                                    }
                                    u.__jsaction = t
                                } else t = la, u.__jsaction = t
                            }
                            u = t;
                            "maybe_click" == q && u.click ? (r = q, q = "click") : "clickkey" == q ? q = "click" : "click" != q || u.click || (q = "clickonly");
                            r = {
                                m: r ? r : q,
                                action: u[q] || "",
                                event: null,
                                s: !1
                            };
                            l = Q(r.m, r.event || b, e, r.action || "", k, l.timeStamp);
                            if (r.s || r.action) break
                        }
                        l && "touchend" == l.eventType && (l.event._preventMouseEvents = ea);
                        if (r && r.action) {
                            if (e = "clickkey" == m) e = z(b), e = (e.type ||
                                e.tagName).toUpperCase(), (e = 32 == (b.which || b.keyCode) && "CHECKBOX" != e) || (e = z(b), n = e.tagName.toUpperCase(), r = (e.getAttribute("role") || "").toUpperCase(), e = "BUTTON" === n || "BUTTON" === r ? !0 : !(e.tagName.toUpperCase() in fa) || "A" === n || "SELECT" === n || (e.getAttribute("type") || e.tagName).toUpperCase() in G || (e.getAttribute("type") || e.tagName).toUpperCase() in H ? !1 : !0);
                            e && (b.preventDefault ? b.preventDefault() : b.returnValue = !1);
                            if ("mouseenter" == m || "mouseleave" == m)
                                if (e = b.relatedTarget, !("mouseover" == b.type && "mouseenter" ==
                                        m || "mouseout" == b.type && "mouseleave" == m) || e && (e === k || aa(k, e))) l.action = "", l.actionElement = null;
                                else {
                                    m = {};
                                    for (var v in b) "function" !== typeof b[v] && "srcElement" !== v && "target" !== v && (m[v] = b[v]);
                                    m.type = "mouseover" == b.type ? "mouseenter" : "mouseleave";
                                    m.target = m.srcElement = k;
                                    m.bubbles = !1;
                                    l.event = m;
                                    l.targetElement = k
                                }
                        } else l.action = "", l.actionElement = null;
                        k = l;
                        a.h && !k.event.a11ysgd && (v = Q(k.eventType, k.event, k.targetElement, k.action, k.actionElement, k.timeStamp), "clickonly" == v.eventType && (v.eventType = "click"), a.h(v, !0));
                        if (k.actionElement) {
                            if (a.h) {
                                if (!k.actionElement || "A" != k.actionElement.tagName || "click" != k.eventType && "clickmod" != k.eventType || (b.preventDefault ? b.preventDefault() : b.returnValue = !1), (b = a.h(k)) && g) {
                                    p.call(this, b, !1);
                                    return
                                }
                            } else {
                                if ((g = f.document) && !g.createEvent && g.createEventObject) try {
                                    var E = g.createEventObject(b)
                                } catch (pa) {
                                    E = b
                                } else E = b;
                                k.event = E;
                                a.i.push(k)
                            }
                            if ("touchend" == k.event.type && k.event._mouseEventsPrevented) {
                                b = k.event;
                                for (var qa in b);
                                h()
                            }
                        }
                    }
                },
                Q = function(a, c, d, b, g, p) {
                    return {
                        eventType: a,
                        event: c,
                        targetElement: d,
                        action: b,
                        actionElement: g,
                        timeStamp: p || h()
                    }
                },
                la = {},
                na = function(a, c) {
                    return function(d) {
                        var b = a,
                            g = c,
                            p = !1;
                        "mouseenter" == b ? b = "mouseover" : "mouseleave" == b && (b = "mouseout");
                        if (d.addEventListener) {
                            if ("focus" == b || "blur" == b || "error" == b || "load" == b) p = !0;
                            d.addEventListener(b, g, p)
                        } else d.attachEvent && ("focus" == b ? b = "focusin" : "blur" == b && (b = "focusout"), g = ba(d, g), d.attachEvent("on" + b, g));
                        return {
                            m: b,
                            l: g,
                            capture: p
                        }
                    }
                },
                N = function(a, c) {
                    if (!a.j.hasOwnProperty(c)) {
                        var d = ma(a, c),
                            b = na(c, d);
                        a.j[c] = d;
                        a.o.push(b);
                        for (d = 0; d < a.a.length; ++d) {
                            var g = a.a[d];
                            g.g.push(b.call(null, g.a))
                        }
                        "click" == c && N(a, "keydown")
                    }
                };
            O.prototype.l = function(a) {
                return this.j[a]
            };
            var V = function(a, c) {
                    var d = new oa(c);
                    a: {
                        for (var b = 0; b < a.a.length; b++)
                            if (S(a.a[b], c)) {
                                c = !0;
                                break a
                            } c = !1
                    }
                    if (c) return a.g.push(d), d;
                    T(a, d);
                    a.a.push(d);
                    U(a);
                    return d
                },
                U = function(a) {
                    for (var c = a.g.concat(a.a), d = [], b = [], g = 0; g < a.a.length; ++g) {
                        var p = a.a[g];
                        W(p, c) ? (d.push(p), X(p)) : b.push(p)
                    }
                    for (g = 0; g < a.g.length; ++g) p = a.g[g], W(p, c) ? d.push(p) : (b.push(p), T(a, p));
                    a.a = b;
                    a.g = d
                },
                T = function(a, c) {
                    var d = c.a;
                    ha && (d.style.cursor = "pointer");
                    for (d = 0; d < a.o.length; ++d) c.g.push(a.o[d].call(null, c.a))
                },
                Y = function(a, c) {
                    a.h = c;
                    a.i && (0 < a.i.length && c(a.i), a.i = null)
                },
                oa = function(a) {
                    this.a = a;
                    this.g = []
                },
                S = function(a, c) {
                    for (a = a.a; a != c && c.parentNode;) c = c.parentNode;
                    return a == c
                },
                W = function(a, c) {
                    for (var d = 0; d < c.length; ++d)
                        if (c[d].a != a.a && S(c[d], a.a)) return !0;
                    return !1
                },
                X = function(a) {
                    for (var c = 0; c < a.g.length; ++c) {
                        var d = a.a,
                            b = a.g[c];
                        d.removeEventListener ? d.removeEventListener(b.m, b.l, b.capture) : d.detachEvent && d.detachEvent("on" + b.m, b.l)
                    }
                    a.g = []
                };
            var Z = new O;
            V(Z, window.document.documentElement);
            N(Z, "click");
            N(Z, "focus");
            N(Z, "focusin");
            N(Z, "blur");
            N(Z, "focusout");
            N(Z, "error");
            N(Z, "load");
            N(Z, "change");
            N(Z, "dblclick");
            N(Z, "input");
            N(Z, "keyup");
            N(Z, "keydown");
            N(Z, "keypress");
            N(Z, "mousedown");
            N(Z, "mouseenter");
            N(Z, "mouseleave");
            N(Z, "mouseout");
            N(Z, "mouseover");
            N(Z, "mouseup");
            N(Z, "paste");
            N(Z, "touchstart");
            N(Z, "touchend");
            N(Z, "touchcancel");
            N(Z, "speech");
            (function(a) {
                google.jsad = function(c) {
                    Y(a, c)
                };
                google.jsaac = function(c) {
                    return V(a, c)
                };
                google.jsarc = function(c) {
                    X(c);
                    for (var d = !1, b = 0; b < a.a.length; ++b)
                        if (a.a[b] === c) {
                            a.a.splice(b, 1);
                            d = !0;
                            break
                        } if (!d)
                        for (d = 0; d < a.g.length; ++d)
                            if (a.g[d] === c) {
                                a.g.splice(d, 1);
                                break
                            } U(a)
                }
            })(Z);
            window.gws_wizbind = function(a) {
                return {
                    trigger: function(c) {
                        var d = a.l(c.type);
                        d || (N(a, c.type), d = a.l(c.type));
                        var b = c.target || c.srcElement;
                        d && d.call(b.ownerDocument.documentElement, c)
                    },
                    bind: function(c) {
                        Y(a, c)
                    }
                }
            }(Z);
        }).call(this);
    </script>
<style>
        body {
            margin: 0;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #161616;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;

        }

        body>div {
            height: 100%
        }

        html {
            -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
            height: 100%
        }

        trivia-game {
            display: block;
            height: 100%
        }

        .fp-f {
            bottom: 0;
            height: auto;
            left: 0;
            position: fixed !important;
            right: 0;
            top: 0;
            width: auto;
            z-index: 127
        }

        .fp-h:not(.fp-nh):not(.goog-modalpopup-bg):not(.goog-modalpopup) {
            display: none !important
        }

        .fp-zh.fp-h:not(.fp-nh):not(.goog-modalpopup-bg):not(.goog-modalpopup) {
            display: block !important;
            height: 0;
            overflow: hidden;
            transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0)
        }

        .fp-i .fp-c {
            display: block;
            min-height: 100vh
        }

        li.fp-c {
            list-style: none
        }

        .fp-w {
            box-sizing: border-box;
            left: 0;
            margin-left: auto;
            margin-right: auto;
            max-width: 1217px;
            right: 0
        }
                 #menu1 li a {
            display: flex;
              align-items: center;
              justify-content: center;
              gap:5px;
            }
    </style>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/gracehuynhh/doodlejump/w3navigation.css" />
</head>
<body>

<nav>
<div id="side-navigation">
<div id="menuToggle">
<input type="checkbox" aria-label="Show or Hide Menu" id="checkbox1" />
<span></span>
<span></span>
<span></span>
<div id="menu-container">
<div id="scrollable-container">
<div id="left-column">

<ul id="menu1">
<li style="text-align:center">
<h1>Google Snake </h1>
</li>
<li><a class="inactive" href="https://retrobowl.ee" title="Retro Bowl"><img alt="Retro Bowl" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/retro-bowl-150x150.webp" height="30px" width="30px"> Retro Bowl</a></li><li><a class="inactive" href="https://flappybird.ee/" title="Flappy Bird"><img alt="Flappy Bird" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/flappy-bird.webp" height="30px" width="30px"> Flappy Bird</a></li><li><a class="inactive" href="https://doodlejump.io/" title="Doodle Jump"><img alt="Doodle Jump" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/doodle-jump.jpeg" height="30px" width="30px"> Doodle Jump</a></li><li><a class="inactive" href="https://playslope.io/" title="Slope Unblocked"><img alt="Slope Unblocked" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/slope.webp" height="30px" width="30px"> Slope Unblocked</a></li><li><a class="inactive" href="https://chromedino.io/" title="Chrome Dino"><img alt="Chrome Dino" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/chrome-dino.webp" height="30px" width="30px"> Chrome Dino</a></li><li><a class="inactive" href="https://cookieclicker.ee" title="Cookie Clicker"><img alt="Cookie Clicker" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/cookie-clicker.webp" height="30px" width="30px"> Cookie Clicker</a></li><li><a class="inactive" href="https://supermario.ee/" title="Super Mario"><img alt="Super Mario" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/super-mario.webp" height="30px" width="30px"> Super Mario</a></li><li><a class="inactive" href="https://2048.ee/" title="2048 Original"><img alt="2048 Original" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/2048.webp" height="30px" width="30px"> 2048 Original</a></li><li><a class="inactive" href="https://2048.ee/doge/" title="2048 Doge"><img alt="2048 Doge" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/2048-doge.webp" height="30px" width="30px"> 2048 Doge</a></li><li><a class="inactive" href="https://2048.ee/cupcakes" title="2048 Cupcakes"><img alt="2048 Cupcakes" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/2048-cupcakes.webp" height="30px" width="30px"> 2048 Cupcakes</a></li><li><a class="inactive" href="https://tictactoe.ee/" title="Tic Tac Toe"><img alt="Tic Tac Toe" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/tictactoe.png" height="30px" width="30px"> Tic Tac Toe</a></li><li><a class="inactive" href="https://pacman.ee/" title="Pacman"><img alt="Pacman" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/pacman-150x150.png" height="30px" width="30px"> Pacman</a></li><li><a class="inactive" href="https://pvz.ee" title="Plant vs Zombies"><img alt="Plant vs Zombies" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/pvz.png" height="30px" width="30px"> Plant vs Zombies</a></li><li><a class="inactive" href="https://minesweeper.ee" title="Minesweeper"><img alt="Minesweeper" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/minesweeper.png" height="30px" width="30px"> Minesweeper</a></li><li><a class="inactive" href="https://ponggame.io/" title="Pong Game"><img alt="Pong Game" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/pong-game.webp" height="30px" width="30px"> Pong Game</a></li><li><a class="inactive" href="https://freemahjong.io/" title="Free Mahjong"><img alt="Free Mahjong" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/mahjong.webp" height="30px" width="30px"> Free Mahjong</a></li><li><a class="inactive" href="https://solitair.ee" title="Google Solitaire"><img alt="Google Solitaire" class="lazy" data-src="https://solitair.ee/images/180.png" height="30px" width="30px"> Google Solitaire</a></li><li class="active"><a href="https://snak.ee/" title="Google Snake"><img alt="Google Snake" class="lazy" data-src="https://snak.ee/180.png" height="30px" width="30px"> Google Snake</li></a><li><a class="inactive" href="https://tunnelrush.app/" title="Tunnel Rush"><img alt="Tunnel Rush" class="lazy" data-src="https://tunnelrush.app/wp-content/uploads/2022/12/unnamed-7-1.png" height="30px" width="30px"> Tunnel Rush</a></li><li><a class="inactive" href="https://motox3m.pro" title="Moto X3M"><img alt="Moto X3M" class="lazy" data-src="https://motox3m.pro/wp-content/uploads/2022/12/unnamed-25.png" height="30px" width="30px"> Moto X3M</a></li><li><a class="inactive" href="https://ducklife.app" title="Duck Life"><img alt="Duck Life" class="lazy" data-src="https://ducklife.app/128x128.png" height="30px" width="30px"> Duck Life</a></li><li><a class="inactive" href="https://run3.pro/" title="Run 3"><img alt="Run 3" class="lazy" data-src="https://run3.pro/wp-content/uploads/2022/12/d3c19e9b-9b7b-4a54-9cb5-6188a5bd7d3b.png" height="30px" width="30px"> Run 3</a></li><li><a class="inactive" href="https://happywheels.app" title="Happy Wheels"><img alt="Happy Wheels" class="lazy" data-src="https://happywheels.app/wp-content/uploads/2022/12/03e4c40ab79cf7df89bd7a44484288b9.jpg" height="30px" width="30px"> Happy Wheels</a></li><li><a class="inactive" href="https://chesswai.com/" title="Chess Online"><img alt="Chess Online" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/chess.webp" height="30px" width="30px"> Chess Online</a></li><li><a class="inactive" href="https://playwordle.io/" title="Wordle"><img alt="Wordle" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/wordle.webp" height="30px" width="30px"> Wordle</a></li><li><a class="inactive" href="https://aow.ee/" title="Age of War"><img alt="Age of War" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/aow-150x150.png" height="30px" width="30px"> Age of War</a></li><li><a class="inactive" href="https://invaders.ee" title="Space Invaders"><img alt="Space Invaders" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/invaders-150x150.png" height="30px" width="30px"> Space Invaders</a></li><li><a class="inactive" href="https://kong.ee" title="Donkey Kong"><img alt="Donkey Kong" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/donkey-kong-150x150.png" height="30px" width="30px"> Donkey Kong</a></li><li><a class="inactive" href="https://frogger.ee" title="Frogger"><img alt="Frogger" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/frogger-150x150.png" height="30px" width="30px"> Frogger</a></li><li><a class="inactive" href="https://galaga.ee" title="Galaga"><img alt="Galaga" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/galaga-150x150.png" height="30px" width="30px"> Galaga</a></li><li><a class="inactive" href="https://sonic.ee" title="Sonic"><img alt="Sonic" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/sonic-150x150.png" height="30px" width="30px"> Sonic</a></li><li><a class="inactive" href="https://qbert.ee/" title="Qbert"><img alt="Qbert" class="lazy" data-src="https://qbert.ee/images/qbert-game-icon-512.png" height="30px" width="30px"> Qbert</a></li><li><a class="inactive" href="https://watersortgame.com/" title="Water Sort"><img alt="Water Sort" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/water-sort.webp" height="30px" width="30px"> Water Sort</a></li><li><a class="inactive" href="https://templerun.ee/" title="Temple Run 2"><img alt="Temple Run 2" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/temple-run-2.png" height="30px" width="30px"> Temple Run 2</a></li><li><a class="inactive" href="https://subwaysurfers.app/" title="Subway Surfers"><img alt="Subway Surfers" class="lazy" data-src="https://www.w3technic.com/wp-content/uploads/2022/05/subway-surfers.png" height="30px" width="30px"> Subway Surfers</a></li><li><a class="inactive" href="https://asteroids.ee/" title="Asteroids"><img alt="Asteroids" class="lazy" data-src="https://asteroids.ee/images/asteroids-game-icon-512.png" height="30px" width="30px"> Asteroids</a></li><li><a class="inactive" href="https://jetpac.ee/" title="Jetpac"><img alt="Jetpac" class="lazy" data-src="https://jetpac.ee/images/jetpac-game-icon-512.png" height="30px" width="30px"> Jetpac</a></li><li><a class="inactive" href="https://sudokugame.ee" title="Sudoku"><img alt="Sudoku" class="lazy" data-src="https://sudokugame.ee/images/128x128.png" height="30px" width="30px"> Sudoku</a></li><li><a class="inactive" href="https://sites.google.com/view/unblocked-games-4all/" title="Unblocked Games 4all"><img alt="Unblocked Games 4all" class="lazy" data-src="https://cdn-icons-png.flaticon.com/512/720/720307.png" height="30px" width="30px"> Unblocked Games 4all</a></li><li><a class="inactive" href="https://play.google.com/store/apps/details?id=com.solitairegames.freecell" title="FreeCell Solitaire (Android)"><img alt="FreeCell Solitaire (Android)" class="lazy" data-src="https://play-lh.googleusercontent.com/ZVbg_rTFLYYbJRnsujq1WzVswO9eYYFyyvW-YPQj_kCilev5dTZXlAp8FlThOn96JA=w240-h480-rw" height="30px" width="30px"> FreeCell Solitaire (Android)</a></li><li><a class="inactive" href="https://www.vnagame.com" title="Other Games"><img alt="Other Games" class="lazy" data-src="https://vnagame.com/images/login-logo.png" height="30px" width="30px"> Other Games</a></li><li><a class="inactive" href="https://porkgames.com/" title="Porkgames.com"><img alt="Porkgames.com" class="lazy" data-src="https://porkgames.com/public/static/favicon.png" height="30px" width="30px"> Porkgames.com</a></li>
</ul>
</div>
<div id="menu-bottom">
<p></p>
</div>
</div>
</div>
</div>
</div>
</nav>

<style>
        @media only screen and (max-width:285px),
        only screen and (orientation:landscape) and (max-height:285px) {}

        @media only screen and (max-width:315px),
        only screen and (orientation:landscape) and (max-height:315px) {}

        @media only screen and (max-width:215px),
        only screen and (orientation:landscape) and (max-height:215px) {}
    </style>
<link href="//fonts.googleapis.com/css?family=Roboto:500" rel="stylesheet" type="text/css" nonce="MbQrqGoifFdVWeMKcb2vew==">
<div class="EjCLSb yZz3de r-iIT029GlNi00" jscontroller="" jsl="$t t-0ZvUBxKupfQ;$x 0;" data-ved="0ahUKEwit-5upv8LnAhUMuRoKHRY6BR8QtOUBCAE">
<style>
            .EjCLSb {
                width: 600px;
                height: 600px
            }

            #Q3CKle {
                position: relative;
                width: 100%;
                height: 70px;
                background-color: #4a752c;
                user-select: none;
                border-radius: 15px 15px 0 0!important;
               
                

            }

            .wSwbef {
                overflow: hidden
            }

            .TO4uAe {
                position: relative;
                top: 16px;
                height: 38px;
                width: 38px;
                display: inline-block
            }

            .UJhXPd {
                height: 60px;
                width: 60px;
                margin-bottom: 3px
            }

            .XUtzXd {
                height: 100%;
                position: relative;
                top: 0;
                left: 0;
                user-drag: none;
                user-select: none
            }

            .MR2r3b {
                position: absolute;
                top: 21px;
                visibility: hidden
            }

            .ZEpI5d {
                position: absolute;
                top: 20px
            }

            .mL9Mvb {
                position: absolute;
                top: 23px
            }

            .jNB0Ic {
                width: 100%;
                height: calc(100% - 70px)
            }

            .cer0Bd {
                width: 100%;
                height: 100%;
                border-radius:0 0 15px 15px!important;
            }

            .dyP0v {
                font-family: Roboto, Arial, sans-serif;
                color: white;
                font-size: 20px;
                width: 60px;
                height: 35px;
                position: relative;
                padding-left: 5px;
                top: 8px;
                display: inline-block
            }

            #EfeGfb {
                position: absolute;
                left: 20px;
                height: 70px
            }

            #RprIte {
                position: absolute;
                right: 20px;
                height: 70px
            }

            #TqOHCc {
                width: 28px;
                right: 80px;
                z-index: 1000;
                cursor: pointer
            }

            #yhjoFc {
                width: 30px;
                right: 40px;
                z-index: 1001;
                cursor: pointer
            }

            #Xc2gWd {
                width: 25px;
                right: 8px;
                z-index: 1002;
                cursor: pointer
            }

            .yZz3de #yhjoFc {
                right: 8px
            }

            .yZz3de #TqOHCc {
                right: 46px
            }

            #fj6BWc {
                position: absolute;
                left: 0;
                top: 0;
                width: 100%;
                height: 100%;
                background-color: #578a34;
                z-index: 1003
            }

            #Z3vFrd {
                position: absolute;
                left: 0;
                top: 0;
                width: 100%;
                height: 100%;
                background-color: rgb(0, 0, 0);
                background-color: rgba(0, 0, 0, 0.7);
                transition: opacity 0.3s
            }

            #wkV5ib {
                position: relative;
                top: 50%;
                transform: translateY(-50%)
            }

            .T7SB3d {
                position: relative;
                background: #4ac0fd;
                width: 300px;
                height: 300px;
                margin: auto;
                border-radius: 8px;
                text-align: center;
                background-size: contain;
                user-select: none
            }

            .jfYnYe {
                position: absolute;
                left: 0;
                top: 0;
                width: 100%;
                height: 100%;
                border-radius: 8px
            }

            .bF4Gmf {
                display: inline-block;
                margin: 32px;
                text-align: center
            }

            .dxb8tb {
                font: 400 28px Roboto, Arial, sans-serif;
                color: white
            }

            .wUt0xf {
                width: 300px;
                margin: auto;
                display: flex
            }

            .FL0z2d {
                background: #15c;
                height: 64px;
                border-radius: 8px;
                border: none;
                color: #fff;
                font-size: 20px;
                text-align: center;
                user-select: none;
                cursor: pointer;
                display: inline-block
            }

            .Uxkl7b {
                margin: 12px 0 0 6px;
                flex-grow: 1
            }

            .Uxkl7b img {
                vertical-align: middle;
                margin: 0 6px 2px -5px;
                width: 30px;
                height: 30px
            }

            .Uxkl7b h2 {
                font: 400 20px Roboto, Arial, sans-serif;
                color: white;
                padding: 0;
                margin: 0;
                margin-top: 20px;
                display: inline-block
            }

            .SesFYc {
                width: 64px;
                margin: 12px 6px 0 0
            }

            .SesFYc img {
                vertical-align: middle;
                margin: 15px auto;
                width: 35px;
                height: 35px
            }

            #pPeeKb {
               position: absolute;
                left: 0;
                top: 0;
                width: 100%;
                height: 100%;

                transition: opacity 200ms
            }

            #mbPNob {
                width: 120px;
                height: 120px;
                background-image: url(//www.google.com/logos/fnbx/snake_arcade/keys.svg);
                background-size: 100px auto;
                background-repeat: no-repeat;
                background-position: center;
                background-color: rgb(0, 0, 0);
                background-color: rgba(0, 0, 0, 0.6);
                border-radius: 16px;
                position: relative;
                top: 50%;
                transform: translateY(-50%);
                display: block;
                margin: auto;
                user-select: none
            }
            .ad {
  outline: 1px solid #333;
  background-color: #333;
  overflow: hidden;
}
.adsbygoogle {
  display: inline-block;
}
.ad.skyscraper1,
.ad.skyscraper2,
.ad.skyscraper1 .adsbygoogle,
.ad.skyscraper2 .adsbygoogle {
  width: 300px;

}
.ad.skyscraper1 {
  position: absolute;
  top: 50%;
  margin-top: -300px;
  left: 0;
}
.ad.skyscraper2 {
  position: absolute;
  top: 50%;
  margin-top: -300px;
  right: 0;
}
.ad.mobile,
.ad.mobile .adsbygoogle {
  display: block;
  width: 100%;
  height: 50px;
}
.ad.mobile {
  position: absolute;
  bottom: 0;
  bottom: env(safe-area-inset-bottom);
  width: 100%;
  margin: 0;
  overflow: hidden;
}
.ad.mobile .adsbygoogle {
  margin: 0 auto;
}
@media (min-width: 1261px) {
  .ad.skyscraper1 {
    margin-left: 71px;
  }
  .ad.skyscraper2 {
    margin-right: 71px;
  }
}

@media (max-width: 1600px) {
 .ad.skyscraper1,
.ad.skyscraper2,
.ad.skyscraper1 .adsbygoogle,
.ad.skyscraper2 .adsbygoogle {
  width: 160px;

} 
}


@media (max-width: 815px) and (min-height: 661px) {
  .ad.skyscraper2, .ad.skyscraper1 {
    display: none;
  }
}
@media (max-height: 800px) {
  .ad.skyscraper1,
  .ad.skyscraper2 {
    margin-top: -290px;
  }
}
@media (max-height: 660px) {

  .ad.skyscraper1,
  .ad.skyscraper2 {
    margin-top: -280px;
  }
}
@media (max-width: 540px) {
  .ad.skyscraper1,
  .ad.skyscraper2 {
    display: none;
  }
  .neave,
  .mute {
    display: block;
  }
}

@media (max-height: 520px) {
  .ad.mobile,
  .ad.skyscraper1,
  .ad.skyscraper2 {
    display: none;
  }
  .neave,
  .mute {
    display: block;
  }
  .mobile .game,
  .game {
    top: 60px;
    margin-top: 0;
  }
  .mobile .scores,
  .scores {
    top: 380px;
    margin-top: 0;
    padding-bottom: 0;
  }
}
@media (max-width: 350px) {
  .scores .swap {
    display: none;
  }
}
@media (min-width: 421px) and (max-height: 450px) {
  .mobile .game,
  .game {
    top: 10px;
  }
  .mobile .scores,
  .scores {
    top: 320px;
  }
}

#full-screen-game-div-button nav{
    display: inline-flex;
    align-items:center;
    gap:10px;
}
@media (max-width: 1060px) {

  .ad.skyscraper1,
  .ad.skyscraper2 {
    display: none!important;
  }
    
}


        </style>
<style>
            html:not(.zAoYTe) .hide-focus-ring {
                outline: 0
            }
        </style>
<div jsname="P0FCKc" id="Q3CKle" class="iIT029GlNi00-9Xq1fte90IQ">
<div id="EfeGfb">
<div class="TO4uAe wSwbef"><img class="XUtzXd iIT029GlNi00-q5ufrUb0rxo" src="//www.google.com/logos/fnbx/snake_arcade/apple_types.png" jsname="lh7ff" alt=""></div>
<div class="dyP0v iIT029GlNi00-J8c2I1boFu0" jsname="A0kWCf" id="GdeGKe">0</div>
<div class="TO4uAe wSwbef"><img class="XUtzXd iIT029GlNi00-loelSMH6pko" src="//www.google.com/logos/fnbx/snake_arcade/trophy_types.png" jsname="UEI8qf" alt=""></div>
<div class="dyP0v iIT029GlNi00-7nurwbos37w" jsname="E5ziSe" id="aNT4hf">0</div>
</div>
<div id="RprIte"><img class="MR2r3b iIT029GlNi00-6R4AmD5UGL0" src="//www.gstatic.com/images/icons/material/system/2x/not_interested_white_24dp.png" jsname="p57eQc" alt="End game" id="TqOHCc" jsaction="r.hbc3FNsMMdg" data-rtid="iIT029GlNi00" jsl="$x 1;"><img class="ZEpI5d iIT029GlNi00-R44MBeTIbJg" src="//www.gstatic.com/images/icons/material/system/2x/volume_up_white_24dp.png" jsname="N7ntOd" alt="Mute" id="yhjoFc" jsaction="r.o-p5trNwwLE" data-rtid="iIT029GlNi00" jsl="$x 2;"></div>
</div>
<div class="jNB0Ic iIT029GlNi00-0rQhgMpCKVg" jsname="JI3Aqc"><canvas class="cer0Bd iIT029GlNi00-QvWXnsGipoA" jsname="UzWXSb"></canvas></div>
<div style="opacity:0;visibility:hidden" jsname="Yfvsbd" id="Z3vFrd" class="iIT029GlNi00-Ms1Vcbzhn30" data-ved="0ahUKEwit-5upv8LnAhUMuRoKHRY6BR8QpcwCCAI">
<div id="wkV5ib">
<div class="hide-focus-ring T7SB3d iIT029GlNi00-cxWq4UlEY-w" jsname="Rs1rF" id="NLEtbb" role="button" tabindex="0" jsaction="r.sHPDQJqnwV8" data-rtid="iIT029GlNi00" jsl="$x 4;"><canvas class="jfYnYe iIT029GlNi00-fP9vg3SWOJI" jsname="kAVrAc"></canvas>
<div class="hide-focus-ring bF4Gmf" role="button" tabindex="0" jsaction="r.TD2p1_3-DII" data-rtid="iIT029GlNi00" jsl="$x 5;">
<div class="UJhXPd wSwbef"><img class="XUtzXd iIT029GlNi00-Jc_LQhV4LUk" src="//www.google.com/logos/fnbx/snake_arcade/apple_types.png" jsname="h6Ousc" alt=""></div>
 <div class="dxb8tb iIT029GlNi00-_sr9b_2nffI" jsname="LOtDEe" id="dxb8tb">0</div>
</div>
<div class="hide-focus-ring bF4Gmf" role="button" tabindex="0" jsaction="r.RmZ_CtXtnBA" data-rtid="iIT029GlNi00" jsl="$x 6;">
<div class="UJhXPd wSwbef"><img class="XUtzXd iIT029GlNi00-J8pweCeLDq4" src="//www.google.com/logos/fnbx/snake_arcade/trophy_types.png" jsname="LpoWPe" alt=""></div>
<div class="dxb8tb iIT029GlNi00-bnFUm9ATFvc" jsname="Vp6PHf" id="tVkfse">0</div>
</div>
</div>
<div class="wUt0xf">
<div class="FL0z2d SesFYc iIT029GlNi00-Fsenb6SWLfA" jsname="qycu7d" jsaction="r.1skNaPYd1Uk" data-rtid="iIT029GlNi00" jsl="$x 7;" data-ved="0ahUKEwit-5upv8LnAhUMuRoKHRY6BR8Q7r0FCAM"><img src="//www.gstatic.com/images/icons/material/system/2x/shuffle_white_24dp.png" alt="Shuffle"></div>
<div class="FL0z2d Uxkl7b iIT029GlNi00-IlV_-wJg2k0" jsname="NSjDf" jsaction="r.FJSS3DVgE68" data-rtid="iIT029GlNi00" jsl="$x 8;" data-ved="0ahUKEwit-5upv8LnAhUMuRoKHRY6BR8Qo8wCCAQ"><img src="//www.gstatic.com/images/icons/material/system/2x/refresh_white_24dp.png" alt="Play again">
<h2>Play again</h2>
</div>
</div>
</div>
</div>
<div jsname="IoE5Ec" id="pPeeKb" class="iIT029GlNi00-L50QgkC_Vkw">
<div id="mbPNob"></div>
</div>
<div jsname="y7GBZ" id="fj6BWc" class="iIT029GlNi00-QrMey-L_Hvc"></div>
</div>
<script nonce="MbQrqGoifFdVWeMKcb2vew==">
        function _F_installCss() {}
        (function() {
            var pinto_primary_url = '/xjs/_/js/k\x3dxjs.s.en_GB.ZNLR_FtigPE.O/ck\x3dxjs.s.V_G3gJ11U4c.L.F4.O/m\x3djsa,dbm,r,d,hsm,sb_wiz,aa,abd,aspn,async,bgd,dvl,foot,kyn,lu,m,mUpTid,mpck,mu,sf,tl,vs,snek/am\x3dAAAAgCUAs24AOP-DIAAAqGMAAEBAm2BjgRAkZBArJAAg/d\x3d1/dg\x3d2/ct\x3dzgms/rs\x3dACT90oHQIQ7X04LgXUpi4CP-NZDRIFyqkA';
            var _expids = '0,202084,11,1151652,4797,865,730,224,3110,1994,207,1987,427,540,250,10,1051,175,364,925,437,73,4,60,690,52,75,145,238,23,116,2,875,58,501,415620,712176,1527267,1294,7105,180,3382,1716,1604,2044,314,893,633,1770,1137,4795,5298,2488,260,68,5033,10931,279,1191,14056,867,7049,2445,2646,793,845,4693,10213,369,8819,3961,1800,512,2111,4858,1362,4323,4967,448,2574,4746,3123,7811,99,1496,320,1968,76,1968,8909,5191,106,2054,920,873,1217,93,2466,416,2530,3,667,3230,2374,1560,448,12,866,12,5,7,5402,620,2884,16,321,1981,1192,1345,1396,1381,520,399,2277,8,443,2415,827,704,423,744,112,2212,202,1,327,149,1103,840,124,350,43,317,825,277,55,48,157,663,484,2954,260,52,1136,3,661,1402,606,1315,524,184,1777,143,378,374,311,1261,747,429,44,1009,95,326,1169,115,16,84,42,375,1556,870,161,1478,608,473,549,790,29,52,667,1039,3227,773,2072,7,1320,6313,390,58,199,1438,709,2,2898,819,2662,170,472,426,303,1,1720,2458,1226,1175,220,63,4,128,153,3654,1274,108,1246,468,1141,72,480,908,2,435,141,897,313,127,123,1153,366,1413,719,265,712,96,1145,667,320,1350,713,61,1,354,226,599,396,828,842,175,10,2,23,1695,356,523,113,88,29,157,624,189,183,388,39,107,59,89,574,621,214,720,119,5,241,398,1025,1,378,329,340,351,232,2,351,2597,46,222,11,1,240,500,82,643,74,47,268,159,199,2,49,37,96,613,147,216,1054,416,831,121,5848484,1805893,4194915,26779128,24,919957';
            window._ = this;
            window._DumpException = function(e) {
                throw e;
            };
            google.xjsu = pinto_primary_url;
            google.kEXPI = _expids;
        })();
        (function() {
            var m = [
                [
                    ["root", [
                        ["t-0ZvUBxKupfQ", "iIT029GlNi00", "r-iIT029GlNi00", [
                            ["standalone_immersive", null, null, null, null, [null, null, null, null, 1]]
                        ], null, "snek"]
                    ], ""]
                ]
            ];
            google.jsc && google.jsc.m(m);
            google.log('rfl', '');
        })();
        (function() {
            var m = [];
            var a = m;
            window.W_jd = window.W_jd || {};
            for (var b = 0; b < a.length; b += 2) window.W_jd[a[b]] = JSON.parse(a[b + 1]);
        })();
    </script>
<script>
        // Set the options globally
        // to make LazyLoad self-initialize
        window.lazyLoadOptions = {
            // Your custom settings go here
        };
    </script>
<div class="ad skyscraper1">
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-6875580793823494" crossorigin="anonymous"></script>
<ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6875580793823494" data-ad-slot="6887564054" data-ad-format="auto" data-full-width-responsive="true"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
</div>
<div class="ad skyscraper2">
<ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6875580793823494" data-ad-slot="6887564054" data-ad-format="auto" data-full-width-responsive="true"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
</div>
<script src="https://cdn.jsdelivr.net/gh/gracehuynhh/google-snake/js/snakedesktop.js"></script>
<script defer src="https://cdn.jsdelivr.net/npm/vanilla-lazyload@17.8.1/dist/lazyload.min.js"></script>
<script type="text/javascript" src="//s7.addthis.com/js/300/addthis_widget.js#pubid=ra-6271f5abca80cec0"></script>
<script defer src="https://static.cloudflareinsights.com/beacon.min.js/vaafb692b2aea4879b33c060e79fe94621666317369993" integrity="sha512-0ahDYl866UMhKuYcW078ScMalXqtFJggm7TmlUtp0UlD4eQk0Ixfnm5ykXKvGJNFjLMoortdseTfsRT8oCfgGA==" data-cf-beacon='{"rayId":"78886b803e468c4d","version":"2022.11.3","r":1,"token":"5ccdd60d458c4fa7be4cad999e65940d","si":100}' crossorigin="anonymous"></script>
</body>
</html>
