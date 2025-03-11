(function(){'use strict';var r;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var da=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ea(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ea(this);function u(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&b!=null&&da(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;da(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];typeof d==="function"&&typeof d.prototype[a]!="function"&&da(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(aa(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
var ka=typeof Object.create=="function"?Object.create:function(a){function b(){}
b.prototype=a;return new b},la=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if(typeof Reflect!="undefined"&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){e===void 0&&(e=c);
e=ka(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ma;
if(typeof Object.setPrototypeOf=="function")ma=Object.setPrototypeOf;else{var na;a:{var oa={a:!0},pa={};try{pa.__proto__=oa;na=pa.a;break a}catch(a){}na=!1}ma=na?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var qa=ma;
function w(a,b){a.prototype=ka(b.prototype);a.prototype.constructor=a;if(qa)qa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Aa=b.prototype}
function y(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function A(a){if(!(a instanceof Array)){a=y(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ra(a){return sa(a,a)}
function sa(a,b){a.raw=b;Object.freeze&&(Object.freeze(a),Object.freeze(b));return a}
function ta(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ua=typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ta(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||ua});
function va(){this.D=!1;this.u=null;this.i=void 0;this.h=1;this.o=this.M=0;this.P=this.j=null}
function wa(a){if(a.D)throw new TypeError("Generator is already running");a.D=!0}
va.prototype.G=function(a){this.i=a};
function xa(a,b){a.j={exception:b,xd:!0};a.h=a.M||a.o}
va.prototype.return=function(a){this.j={return:a};this.h=this.o};
va.prototype.yield=function(a,b){this.h=b;return{value:a}};
va.prototype.A=function(a){this.h=a};
function ya(a,b,c){a.M=b;c!=void 0&&(a.o=c)}
function za(a,b){a.h=b;a.M=0}
function Aa(a){a.M=0;var b=a.j.exception;a.j=null;return b}
function Ba(a){var b=a.P.splice(0)[0];(b=a.j=a.j||b)?b.xd?a.h=a.M||a.o:b.A!=void 0&&a.o<b.A?(a.h=b.A,a.j=null):a.h=a.o:a.h=0}
function Ca(a){this.h=new va;this.i=a}
function Da(a,b){wa(a.h);var c=a.h.u;if(c)return Ea(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Fa(a)}
function Ea(a,b,c,d){try{var e=b.call(a.h.u,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.D=!1,e;var f=e.value}catch(g){return a.h.u=null,xa(a.h,g),Fa(a)}a.h.u=null;d.call(a.h,f);return Fa(a)}
function Fa(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.D=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,xa(a.h,c)}a.h.D=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.xd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ga(a){this.next=function(b){wa(a.h);a.h.u?b=Ea(a,a.h.u.next,b,a.h.G):(a.h.G(b),b=Fa(a));return b};
this.throw=function(b){wa(a.h);a.h.u?b=Ea(a,a.h.u["throw"],b,a.h.G):(xa(a.h,b),b=Fa(a));return b};
this.return=function(b){return Da(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ha(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function B(a){return Ha(new Ga(new Ca(a)))}
function C(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("globalThis",function(a){return a||fa});
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return la});
u("Reflect.setPrototypeOf",function(a){return a?a:qa?function(b,c){try{return qa(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.X=0;this.ab=void 0;this.h=[];this.u=!1;var h=this.i();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(this.h==null){this.h=[];var h=this;this.j(function(){h.u()})}this.h.push(g)};
var e=fa.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.u=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.o(l)}}}this.h=null};
c.prototype.o=function(g){this.j(function(){throw g;})};
b.prototype.i=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.U),reject:g(this.j)}};
b.prototype.U=function(g){if(g===this)this.j(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.Z(g);else{a:switch(typeof g){case "object":var h=g!=null;break a;case "function":h=!0;break a;default:h=!1}h?this.P(g):this.o(g)}};
b.prototype.P=function(g){var h=void 0;try{h=g.then}catch(k){this.j(k);return}typeof h=="function"?this.ha(h,g):this.o(g)};
b.prototype.j=function(g){this.M(2,g)};
b.prototype.o=function(g){this.M(1,g)};
b.prototype.M=function(g,h){if(this.X!=0)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.X);this.X=g;this.ab=h;this.X===2&&this.Y();this.D()};
b.prototype.Y=function(){var g=this;e(function(){if(g.G()){var h=fa.console;typeof h!=="undefined"&&h.error(g.ab)}},1)};
b.prototype.G=function(){if(this.u)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if(typeof k==="undefined")return!0;typeof g==="function"?g=new g("unhandledrejection",{cancelable:!0}):typeof h==="function"?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.ab;return k(g)};
b.prototype.D=function(){if(this.h!=null){for(var g=0;g<this.h.length;++g)f.i(this.h[g]);this.h=null}};
var f=new c;b.prototype.Z=function(g){var h=this.i();g.fc(h.resolve,h.reject)};
b.prototype.ha=function(g,h){var k=this.i();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(p,t){return typeof p=="function"?function(v){try{l(p(v))}catch(x){m(x)}}:t}
var l,m,n=new b(function(p,t){l=p;m=t});
this.fc(k(g,l),k(h,m));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.fc=function(g,h){function k(){switch(l.X){case 1:g(l.ab);break;case 2:h(l.ab);break;default:throw Error("Unexpected state: "+l.X);}}
var l=this;this.h==null?f.i(k):this.h.push(k);this.u=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=y(g),m=l.next();!m.done;m=l.next())d(m.value).fc(h,k)})};
b.all=function(g){var h=y(g),k=h.next();return k.done?d([]):new b(function(l,m){function n(v){return function(x){p[v]=x;t--;t==0&&l(p)}}
var p=[],t=0;do p.push(void 0),t++,d(k.value).fc(n(p.length-1),m),k=h.next();while(!k.done)})};
return b});
u("Object.setPrototypeOf",function(a){return a||qa});
u("Symbol.dispose",function(a){return a?a:Symbol("Symbol.dispose")});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=y(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return l==="object"&&k!==null||l==="function"}
function e(k){if(!ta(k,g)){var l=new c;da(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(m.get(k)!=2||m.get(l)!=3)return!1;m.delete(k);m.set(l,4);return!m.has(k)&&m.get(l)==4}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ta(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&ta(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ta(k,g)&&ta(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ta(k,g)&&ta(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ha(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;l=="object"||l=="function"?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h[0][l];if(m&&ta(h[0],l))for(h=0;h<m.length;h++){var n=m[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:m,index:h,entry:n}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=y(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var h=Object.seal({x:4}),k=new a(y([[h,"s"]]));if(k.get(h)!="s"||k.size!=1||k.get({x:4})||k.set({x:4},"t")!=k||k.size!=2)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||m.value[1]!="s")return!1;m=l.next();return m.done||m.value[0].x!=4||m.value[1]!="t"||!l.next().done?!1:!0}catch(n){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=h===0?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=y(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var c=Object.seal({x:4}),d=new a(y([c]));if(!d.has(c)||d.size!=1||d.add(c)!=d||d.size!=1||d.add({x:4})!=d||d.size!=2)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||f.value[0].x!=4||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=c===0?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
function Ia(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.entries",function(a){return a?a:function(){return Ia(this,function(b,c){return[b,c]})}});
u("Array.prototype.keys",function(a){return a?a:function(){return Ia(this,function(b){return b})}});
function Ja(a,b,c){if(a==null)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"endsWith");b+="";c===void 0&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;e>0&&c>0;)if(d[--c]!=b[--e])return!1;return e<=0}});
u("Number.isFinite",function(a){return a?a:function(b){return typeof b!=="number"?!1:!isNaN(b)&&b!==Infinity&&b!==-Infinity}});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ta(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?b!==0||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(c<0&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return Ja(this,b,"includes").indexOf(b,c||0)!==-1}});
u("Array.from",function(a){return a?a:function(b,c,d){c=c!=null?c:function(h){return h};
var e=[],f=typeof Symbol!="undefined"&&Symbol.iterator&&b[Symbol.iterator];if(typeof f=="function"){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ta(b,d)&&c.push([d,b[d]]);return c}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.MIN_SAFE_INTEGER",function(){return-9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
u("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||b===Infinity||b===-Infinity||b===0)return b;var c=Math.floor(Math.abs(b));return b<0?-c:c}});
u("Math.clz32",function(a){return a?a:function(b){b=Number(b)>>>0;if(b===0)return 32;var c=0;(b&4294901760)===0&&(b<<=16,c+=16);(b&4278190080)===0&&(b<<=8,c+=8);(b&4026531840)===0&&(b<<=4,c+=4);(b&3221225472)===0&&(b<<=2,c+=2);(b&2147483648)===0&&c++;return c}});
u("Math.log10",function(a){return a?a:function(b){return Math.log(b)/Math.LN10}});
u("Number.isNaN",function(a){return a?a:function(b){return typeof b==="number"&&isNaN(b)}});
u("Array.prototype.values",function(a){return a?a:function(){return Ia(this,function(b,c){return c})}});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Ka=Ka||{},D=this||self;function E(a,b,c){a=a.split(".");c=c||D;for(var d;a.length&&(d=a.shift());)a.length||b===void 0?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function F(a,b){a=a.split(".");b=b||D;for(var c=0;c<a.length;c++)if(b=b[a[c]],b==null)return null;return b}
function La(a){var b=typeof a;return b!="object"?b:a?Array.isArray(a)?"array":b:"null"}
function Qa(a){var b=La(a);return b=="array"||b=="object"&&typeof a.length=="number"}
function Ra(a){var b=typeof a;return b=="object"&&a!=null||b=="function"}
function Sa(a){return Object.prototype.hasOwnProperty.call(a,Ta)&&a[Ta]||(a[Ta]=++Ua)}
var Ta="closure_uid_"+(Math.random()*1E9>>>0),Ua=0;function Va(a,b,c){return a.call.apply(a.bind,arguments)}
function Wa(a,b,c){if(!a)throw Error();if(arguments.length>2){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Xa(a,b,c){Xa=Function.prototype.bind&&Function.prototype.bind.toString().indexOf("native code")!=-1?Va:Wa;return Xa.apply(null,arguments)}
function Za(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function $a(){return Date.now()}
function ab(a){return a}
function bb(a,b){function c(){}
c.prototype=b.prototype;a.Aa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
;function cb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,cb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));b!==void 0&&(this.cause=b)}
bb(cb,Error);cb.prototype.name="CustomError";var db=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};/*

 Copyright Google LLC
 SPDX-License-Identifier: Apache-2.0
*/
var eb=globalThis.trustedTypes,fb;function gb(){var a=null;if(!eb)return a;try{var b=function(c){return c};
a=eb.createPolicy("goog#html",{createHTML:b,createScript:b,createScriptURL:b})}catch(c){}return a}
function hb(){fb===void 0&&(fb=gb());return fb}
;function ib(a){this.h=a}
ib.prototype.toString=function(){return this.h+""};
function jb(a){var b=hb();return new ib(b?b.createScriptURL(a):a)}
function kb(a){if(a instanceof ib)return a.h;throw Error("");}
;var lb=ra([""]),mb=sa(["\x00"],["\\0"]),nb=sa(["\n"],["\\n"]),ob=sa(["\x00"],["\\u0000"]);function pb(a){return a.toString().indexOf("`")===-1}
pb(function(a){return a(lb)})||pb(function(a){return a(mb)})||pb(function(a){return a(nb)})||pb(function(a){return a(ob)});function qb(a){this.h=a}
qb.prototype.toString=function(){return this.h};
var rb=new qb("about:invalid#zClosurez");function sb(a){this.Ge=a}
function tb(a){return new sb(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var ub=[tb("data"),tb("http"),tb("https"),tb("mailto"),tb("ftp"),new sb(function(a){return/^[^:]*([/?#]|$)/.test(a)})],vb=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function wb(a){if(a instanceof qb)if(a instanceof qb)a=a.h;else throw Error("");else a=vb.test(a)?a:void 0;return a}
;function xb(a,b){b=wb(b);b!==void 0&&(a.href=b)}
;function yb(a,b){throw Error(b===void 0?"unexpected value "+a+"!":b);}
;function zb(a){this.h=a}
zb.prototype.toString=function(){return this.h+""};function Ab(a){a=a===void 0?document:a;var b,c;a=(c=(b=a).querySelector)==null?void 0:c.call(b,"script[nonce]");return a==null?"":a.nonce||a.getAttribute("nonce")||""}
;function Bb(a){this.h=a}
Bb.prototype.toString=function(){return this.h+""};
function Cb(a){var b=hb();return new Bb(b?b.createScript(a):a)}
function Db(a){if(a instanceof Bb)return a.h;throw Error("");}
;function Eb(a){var b=Ab(a.ownerDocument);b&&a.setAttribute("nonce",b)}
function Fb(a,b){a.src=kb(b);Eb(a)}
;function Gb(){this.h=Hb[0].toLowerCase()}
Gb.prototype.toString=function(){return this.h};function Ib(a){var b="true".toString(),c=[new Gb];if(c.length===0)throw Error("");if(c.map(function(d){if(d instanceof Gb)d=d.h;else throw Error("");return d}).every(function(d){return"data-loaded".indexOf(d)!==0}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;var Jb="alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Lb(a,b){if(b instanceof ib)a.href=kb(b).toString(),a.rel="stylesheet";else{if(Jb.indexOf("stylesheet")===-1)throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=wb(b);b!==void 0&&(a.href=b,a.rel="stylesheet")}}
;var Mb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},Nb=Array.prototype.forEach?function(a,b){Array.prototype.forEach.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)e in d&&b.call(void 0,d[e],e,a)},Ob=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f=typeof a==="string"?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Pb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e=typeof a==="string"?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Qb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
Nb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Rb(a,b){a:{for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return b<0?null:typeof a==="string"?a.charAt(b):a[b]}
function Sb(a,b){b=Mb(a,b);var c;(c=b>=0)&&Array.prototype.splice.call(a,b,1);return c}
function Tb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Qa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Ub(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function Vb(a){var b=F("window.location.href");a==null&&(a='Unknown Error of type "null/undefined"');if(typeof a==="string")return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||D.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Wb(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(c==
null){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Xb[c])c=Xb[c];else{c=String(c);if(!Xb[c]){var f=/function\s+([^\(]+)/m.exec(c);Xb[c]=f?f[1]:"[Anonymous]"}c=Xb[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";typeof a.toString==="function"&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function Wb(a,b){b||(b={});b[Yb(a)]=!0;var c=a.stack||"",d=a.cause;d&&!b[Yb(d)]&&(c+="\nCaused by: ",d.stack&&d.stack.indexOf(d.toString())==0||(c+=typeof d==="string"?d:d.message+"\n"),c+=Wb(d,b));a=a.errors;if(Array.isArray(a)){d=1;var e;for(e=0;e<a.length&&!(d>4);e++)b[Yb(a[e])]||(c+="\nInner error "+d++ +": ",a[e].stack&&a[e].stack.indexOf(a[e].toString())==0||(c+=typeof a[e]==="string"?a[e]:a[e].message+"\n"),c+=Wb(a[e],b));e<a.length&&(c+="\n... "+(a.length-e)+" more inner errors")}return c}
function Yb(a){var b="";typeof a.toString==="function"&&(b=""+a);return b+a.stack}
var Xb={};function Zb(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var $b=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function ac(a){return a?decodeURI(a):a}
function bc(a,b){return b.match($b)[a]||null}
function cc(a){return ac(bc(3,a))}
function dc(a){var b=a.match($b);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function ec(a){var b=a.indexOf("#");return b<0?a:a.slice(0,b)}
function fc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)fc(a,String(b[d]),c);else b!=null&&c.push(a+(b===""?"":"="+encodeURIComponent(String(b))))}
function hc(a){var b=[],c;for(c in a)fc(c,a[c],b);return b.join("&")}
function ic(a,b){b=hc(b);if(b){var c=a.indexOf("#");c<0&&(c=a.length);var d=a.indexOf("?");if(d<0||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
function jc(a,b,c,d){for(var e=c.length;(b=a.indexOf(c,b))>=0&&b<d;){var f=a.charCodeAt(b-1);if(f==38||f==63)if(f=a.charCodeAt(b+e),!f||f==61||f==38||f==35)return b;b+=e+1}return-1}
var kc=/#|$/,lc=/[?&]($|#)/;function mc(a,b){for(var c=a.search(kc),d=0,e,f=[];(e=jc(a,d,b,c))>=0;)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(lc,"$1")}
;var nc=(new Date("2024-01-01T00:00:00Z")).getTime();function oc(a){var b=C.apply(1,arguments).filter(function(d){return d}).join("&");
if(!b)return a;var c=a.match(/[?&]adurl=/);return c?a.slice(0,c.index+1)+b+"&"+a.slice(c.index+1):a+(a.indexOf("?")===-1?"?":"&")+b}
function pc(a){var b=a.url;a=a.Wh;this.j=b;this.D=a;a=/[?&]dsh=1(&|$)/.test(b);this.u=!a&&/[?&]ae=1(&|$)/.test(b);this.M=!a&&/[?&]ae=2(&|$)/.test(b);if((this.h=/[?&]adurl=([^&]*)/.exec(b))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}this.o=(new Date).getTime()-nc}
function qc(a){a=a.D;if(!a)return"";var b="";a.platform&&(b+="&uap="+encodeURIComponent(a.platform));a.platformVersion&&(b+="&uapv="+encodeURIComponent(a.platformVersion));a.uaFullVersion&&(b+="&uafv="+encodeURIComponent(a.uaFullVersion));a.architecture&&(b+="&uaa="+encodeURIComponent(a.architecture));a.model&&(b+="&uam="+encodeURIComponent(a.model));a.bitness&&(b+="&uab="+encodeURIComponent(a.bitness));a.fullVersionList&&(b+="&uafvl="+encodeURIComponent(a.fullVersionList.map(function(c){return encodeURIComponent(c.brand)+
";"+encodeURIComponent(c.version)}).join("|")));
typeof a.wow64!=="undefined"&&(b+="&uaw="+Number(a.wow64));return b.substring(1)}
;function rc(){try{var a,b;return!!((a=window)==null?0:(b=a.top)==null?0:b.location.href)&&!1}catch(c){return!0}}
;function sc(a){a&&typeof a.dispose=="function"&&a.dispose()}
;function tc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Qa(d)?tc.apply(null,d):sc(d)}}
;function H(){this.ea=this.ea;this.M=this.M}
H.prototype.ea=!1;H.prototype.dispose=function(){this.ea||(this.ea=!0,this.ba())};
H.prototype[Symbol.dispose]=function(){this.dispose()};
function uc(a,b){a.addOnDisposeCallback(Za(sc,b))}
H.prototype.addOnDisposeCallback=function(a,b){this.ea?b!==void 0?a.call(b):a():(this.M||(this.M=[]),b&&(a=a.bind(b)),this.M.push(a))};
H.prototype.ba=function(){if(this.M)for(;this.M.length;)this.M.shift()()};function vc(){var a=wc();a=a===void 0?"bevasrsg":a;return new Promise(function(b){var c=window===window.top?window:rc()?window:window.top,d=c[a],e;((e=d)==null?0:e.bevasrs)?b(new xc(d.bevasrs)):(d||(d={},d=(d.nqfbel=[],d),c[a]=d),d.nqfbel.push(function(f){b(new xc(f))}))})}
function xc(a){H.call(this);var b=this;this.vm=a;this.i="keydown keypress keyup input focusin focusout select copy cut paste change click dblclick auxclick pointerover pointerdown pointerup pointermove pointerout dragenter dragleave drag dragend mouseover mousedown mouseup mousemove mouseout touchstart touchend touchmove wheel".split(" ");this.h=void 0;this.Zc=this.vm.p;this.j=this.o.bind(this);this.addOnDisposeCallback(function(){return void yc(b)})}
w(xc,H);xc.prototype.snapshot=function(a){return this.vm.s(Object.assign({},a.vb&&{c:a.vb},a.cd&&{s:a.cd},a.dd!==void 0&&{p:a.dd}))};
xc.prototype.o=function(a){this.vm.e(a)};
function yc(a){a.h!==void 0&&(a.i.forEach(function(b){var c;(c=a.h)==null||c.removeEventListener(b,a.j)}),a.h=void 0)}
;function zc(a){var b=b===void 0?47:b;var c=[];Ac(a,Bc,6).forEach(function(d){Cc(d,2)<=b&&c.push(Cc(d,1))});
return c}
function Dc(a){var b=b===void 0?47:b;var c=[];Ac(a,Bc,6).forEach(function(d){Cc(d,2)>b&&c.push(Cc(d,1))});
return c}
;var Ec;function Fc(){H.apply(this,arguments);this.j=1;this[Ec]=this.dispose}
w(Fc,H);Fc.prototype.share=function(){if(this.ea)throw Error("E:AD");this.j++;return this};
Fc.prototype.dispose=function(){--this.j||H.prototype.dispose.call(this)};
Ec=Symbol.dispose;function Gc(a){return{fieldType:2,fieldName:a}}
function Hc(a){return{fieldType:3,fieldName:a}}
;function Ic(a){this.h=a;a.Gc("/client_streamz/bg/frs",Hc("ke"))}
Ic.prototype.record=function(a,b){this.h.record("/client_streamz/bg/frs",a,b)};
function Jc(a){this.h=a;a.Gc("/client_streamz/bg/wrl",Hc("mn"),Gc("ac"),Gc("sc"),Hc("rk"),Hc("mk"))}
Jc.prototype.record=function(a,b,c,d,e,f){this.h.record("/client_streamz/bg/wrl",a,b,c,d,e,f)};
function Kc(a){this.i=a;a.Kb("/client_streamz/bg/ec",Hc("en"),Hc("mk"))}
Kc.prototype.h=function(a,b){this.i.Ib("/client_streamz/bg/ec",a,b)};
function Lc(a){this.h=a;a.Gc("/client_streamz/bg/el",Hc("en"),Hc("rk"),Hc("mk"))}
Lc.prototype.record=function(a,b,c,d){this.h.record("/client_streamz/bg/el",a,b,c,d)};
function Mc(a){this.i=a;a.Kb("/client_streamz/bg/cec",Gc("ec"),Hc("rk"),Hc("mk"))}
Mc.prototype.h=function(a,b,c){this.i.Ib("/client_streamz/bg/cec",a,b,c)};
function Nc(a){this.i=a;a.Kb("/client_streamz/bg/po/csc",Gc("cs"),Hc("rk"),Hc("mk"))}
Nc.prototype.h=function(a,b,c){this.i.Ib("/client_streamz/bg/po/csc",a,b,c)};
function Oc(a){this.i=a;a.Kb("/client_streamz/bg/po/ctav",Hc("av"),Hc("rk"),Hc("mk"))}
Oc.prototype.h=function(a,b,c){this.i.Ib("/client_streamz/bg/po/ctav",a,b,c)};
function Pc(a){this.i=a;a.Kb("/client_streamz/bg/po/cwsc",Hc("su"),Hc("rk"),Hc("mk"))}
Pc.prototype.h=function(a,b,c){this.i.Ib("/client_streamz/bg/po/cwsc",a,b,c)};function Qc(a){D.setTimeout(function(){throw a;},0)}
;var Rc,Sc=F("CLOSURE_FLAGS"),Tc=Sc&&Sc[610401301];Rc=Tc!=null?Tc:!1;function Uc(){var a=D.navigator;return a&&(a=a.userAgent)?a:""}
var Vc,Wc=D.navigator;Vc=Wc?Wc.userAgentData||null:null;function Xc(a){return Rc?Vc?Vc.brands.some(function(b){return(b=b.brand)&&b.indexOf(a)!=-1}):!1:!1}
function I(a){return Uc().indexOf(a)!=-1}
;function Yc(){return Rc?!!Vc&&Vc.brands.length>0:!1}
function Zc(){return Yc()?!1:I("Opera")}
function $c(){return I("Firefox")||I("FxiOS")}
function ad(){return Yc()?Xc("Chromium"):(I("Chrome")||I("CriOS"))&&!(Yc()?0:I("Edge"))||I("Silk")}
;function bd(){return Rc?!!Vc&&!!Vc.platform:!1}
function cd(){return I("iPhone")&&!I("iPod")&&!I("iPad")}
;function dd(a){dd[" "](a);return a}
dd[" "]=function(){};var ed=Zc(),fd=Yc()?!1:I("Trident")||I("MSIE"),gd=I("Edge"),hd=I("Gecko")&&!(Uc().toLowerCase().indexOf("webkit")!=-1&&!I("Edge"))&&!(I("Trident")||I("MSIE"))&&!I("Edge"),id=Uc().toLowerCase().indexOf("webkit")!=-1&&!I("Edge");id&&I("Mobile");bd()||I("Macintosh");bd()||I("Windows");(bd()?Vc.platform==="Linux":I("Linux"))||bd()||I("CrOS");var jd=bd()?Vc.platform==="Android":I("Android");cd();I("iPad");I("iPod");cd()||I("iPad")||I("iPod");Uc().toLowerCase().indexOf("kaios");$c();var kd=cd()||I("iPod"),ld=I("iPad");!I("Android")||ad()||$c()||Zc()||I("Silk");ad();var md=I("Safari")&&!(ad()||(Yc()?0:I("Coast"))||Zc()||(Yc()?0:I("Edge"))||(Yc()?Xc("Microsoft Edge"):I("Edg/"))||(Yc()?Xc("Opera"):I("OPR"))||$c()||I("Silk")||I("Android"))&&!(cd()||I("iPad")||I("iPod"));var nd={},od=null;function pd(a,b){Qa(a);b===void 0&&(b=0);qd();b=nd[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function rd(a){var b=a.length,c=b*3/4;c%3?c=Math.floor(c):"=.".indexOf(a[b-1])!=-1&&(c="=.".indexOf(a[b-2])!=-1?c-2:c-1);var d=new Uint8Array(c),e=0;sd(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function sd(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),m=od[l];if(m!=null)return m;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
qd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(h===64&&e===-1)break;b(e<<2|f>>4);g!=64&&(b(f<<4&240|g>>2),h!=64&&b(g<<6&192|h))}}
function qd(){if(!od){od={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;c<5;c++){var d=a.concat(b[c].split(""));nd[c]=d;for(var e=0;e<d.length;e++){var f=d[e];od[f]===void 0&&(od[f]=e)}}}}
;var td=typeof Uint8Array!=="undefined",ud=!fd&&typeof btoa==="function";function vd(a){if(!ud)return pd(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var wd=/[-_.]/g,xd={"-":"+",_:"/",".":"="};function yd(a){return xd[a]||""}
function zd(a){return td&&a!=null&&a instanceof Uint8Array}
var Ad={};function Bd(a,b){Cd(b);this.h=a;if(a!=null&&a.length===0)throw Error("ByteString should be constructed with non-empty values");}
Bd.prototype.sizeBytes=function(){Cd(Ad);var a=this.h;if(a!=null&&!zd(a))if(typeof a==="string")if(ud){wd.test(a)&&(a=a.replace(wd,yd));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=rd(a);else La(a),a=null;return(a=a==null?a:this.h=a)?a.length:0};
var Dd;function Cd(a){if(a!==Ad)throw Error("illegal external caller");}
;var Ed=void 0;function Fd(a){a=Error(a);Ub(a,"warning");return a}
function Gd(a){if(a!=null){var b;var c=(b=Ed)!=null?b:Ed={};b=c[a]||0;b>=5||(c[a]=b+1,a=Error(),Ub(a,"incident"),Qc(a))}}
;var Hd=typeof Symbol==="function"&&typeof Symbol()==="symbol";function Id(a,b,c){return typeof Symbol==="function"&&typeof Symbol()==="symbol"?(c===void 0?0:c)&&Symbol.for&&a?Symbol.for(a):a!=null?Symbol(a):Symbol():b}
var Jd=Id("jas",void 0,!0),Kd=Id(void 0,"1oa"),Ld=Id(void 0,Symbol()),Md=Id(void 0,"0actk"),Nd=Id(void 0,"8utk");Math.max.apply(Math,A(Object.values({lh:1,kh:2,jh:4,oh:8,nh:16,mh:32,Nf:64,qh:128,ih:256,hh:512,Tf:1024,ph:2048,Uf:4096,Of:8192})));var K=Hd?Jd:"Fe",Od={Fe:{value:0,configurable:!0,writable:!0,enumerable:!1}},Pd=Object.defineProperties;function Qd(a,b){Hd||K in a||Pd(a,Od);a[K]|=b}
function Rd(a,b){Hd||K in a||Pd(a,Od);a[K]=b}
;function Sd(){return typeof BigInt==="function"}
;function Td(a){return Array.prototype.slice.call(a)}
;var Ud={};function Vd(a){return a!==null&&typeof a==="object"&&!Array.isArray(a)&&a.constructor===Object}
var Wd,Xd=[];Rd(Xd,55);Wd=Object.freeze(Xd);function Yd(a){if(a&2)throw Error();}
var Zd=Object.freeze({});function $d(a){a.Eh=!0;return a}
;var ae=$d(function(a){return typeof a==="number"}),be=$d(function(a){return typeof a==="string"}),ce=$d(function(a){return typeof a==="boolean"});
function de(){var a=ee;return $d(function(b){for(var c in a)if(b===a[c]&&!/^[0-9]+$/.test(c))return!0;return!1})}
var fe=$d(function(a){return a!=null&&typeof a==="object"&&typeof a.then==="function"});var ge=typeof D.BigInt==="function"&&typeof D.BigInt(0)==="bigint";function he(a){var b=a;if(be(b)){if(!/^\s*(?:-?[1-9]\d*|0)?\s*$/.test(b))throw Error(String(b));}else if(ae(b)&&!Number.isSafeInteger(b))throw Error(String(b));return ge?BigInt(a):a=ce(a)?a?"1":"0":be(a)?a.trim()||"0":String(a)}
var ne=$d(function(a){return ge?a>=ie&&a<=je:a[0]==="-"?ke(a,le):ke(a,me)}),le=Number.MIN_SAFE_INTEGER.toString(),ie=ge?BigInt(Number.MIN_SAFE_INTEGER):void 0,me=Number.MAX_SAFE_INTEGER.toString(),je=ge?BigInt(Number.MAX_SAFE_INTEGER):void 0;
function ke(a,b){if(a.length>b.length)return!1;if(a.length<b.length||a===b)return!0;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(d>e)return!1;if(d<e)return!0}}
;var oe=0,pe=0;function qe(a){var b=a>>>0;oe=b;pe=(a-b)/4294967296>>>0}
function re(a){if(a<0){qe(0-a);var b=y(se(oe,pe));a=b.next().value;b=b.next().value;oe=a>>>0;pe=b>>>0}else qe(a)}
function te(a,b){b>>>=0;a>>>=0;if(b<=2097151)var c=""+(4294967296*b+a);else Sd()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+c*6777216+b*6710656,c+=b*8147497,b*=2,a>=1E7&&(c+=a/1E7>>>0,a%=1E7),c>=1E7&&(b+=c/1E7>>>0,c%=1E7),c=b+ue(c)+ue(a));return c}
function ue(a){a=String(a);return"0000000".slice(a.length)+a}
function ve(){var a=oe,b=pe;b&2147483648?Sd()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=y(se(a,b)),a=b.next().value,b=b.next().value,a="-"+te(a,b)):a=te(a,b);return a}
function se(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;var we=typeof BigInt==="function"?BigInt.asIntN:void 0,xe=Number.isSafeInteger,ye=Number.isFinite,ze=Math.trunc;function Ae(a){return a.displayName||a.name||"unknown type name"}
function Be(a){if(a!=null&&typeof a!=="boolean")throw Error("Expected boolean but got "+La(a)+": "+a);return a}
var Ce=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function De(a){switch(typeof a){case "bigint":return!0;case "number":return ye(a);case "string":return Ce.test(a);default:return!1}}
function Ee(a){if(typeof a!=="number")throw Fd("int32");if(!ye(a))throw Fd("int32");return a|0}
function Fe(a){return a==null?a:Ee(a)}
function Ge(a){if(a==null)return a;if(typeof a==="string"&&a)a=+a;else if(typeof a!=="number")return;return ye(a)?a|0:void 0}
function He(a){var b=0;b=b===void 0?0:b;if(!De(a))throw Fd("int64");var c=typeof a;switch(b){case 2048:switch(c){case "string":return Ie(a);case "bigint":return String(we(64,a));default:return Je(a)}case 4096:switch(c){case "string":return b=ze(Number(a)),xe(b)?a=he(b):(b=a.indexOf("."),b!==-1&&(a=a.substring(0,b)),a=Sd()?he(we(64,BigInt(a))):he(Ke(a))),a;case "bigint":return he(we(64,a));default:return xe(a)?he(Le(a)):he(Je(a))}case 0:switch(c){case "string":return Ie(a);case "bigint":return he(we(64,
a));default:return Le(a)}default:return yb(b,"Unknown format requested type for int64")}}
function Me(a){return a==null?a:He(a)}
function Ne(a){var b=a.length;return a[0]==="-"?b<20?!0:b===20&&Number(a.substring(0,7))>-922337:b<19?!0:b===19&&Number(a.substring(0,6))<922337}
function Ke(a){a.indexOf(".");if(Ne(a))return a;if(a.length<16)re(Number(a));else if(Sd())a=BigInt(a),oe=Number(a&BigInt(4294967295))>>>0,pe=Number(a>>BigInt(32)&BigInt(4294967295));else{var b=+(a[0]==="-");pe=oe=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),pe*=1E6,oe=oe*1E6+d,oe>=4294967296&&(pe+=Math.trunc(oe/4294967296),pe>>>=0,oe>>>=0);b&&(b=y(se(oe,pe)),a=b.next().value,b=b.next().value,oe=a,pe=b)}return ve()}
function Le(a){De(a);a=ze(a);if(!xe(a)){re(a);var b=oe,c=pe;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,b==0&&(c=c+1>>>0);var d=c*4294967296+(b>>>0);b=Number.isSafeInteger(d)?d:te(b,c);a=typeof b==="number"?a?-b:b:a?"-"+b:b}return a}
function Je(a){De(a);a=ze(a);if(xe(a))a=String(a);else{var b=String(a);Ne(b)?a=b:(re(a),a=ve())}return a}
function Ie(a){De(a);var b=ze(Number(a));if(xe(b))return String(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));return Ke(a)}
function Oe(a){if(a==null)return a;if(typeof a==="bigint")return ne(a)?a=Number(a):(a=we(64,a),a=ne(a)?Number(a):String(a)),a;if(De(a))return typeof a==="number"?Le(a):Ie(a)}
function Pe(a){if(typeof a!=="string")throw Error();return a}
function Qe(a){if(a!=null&&typeof a!=="string")throw Error();return a}
function Re(a){return a==null||typeof a==="string"?a:void 0}
function Se(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Ae(b)+" but got "+(a&&Ae(a.constructor)));}
function Te(a,b,c){if(a!=null&&typeof a==="object"&&a.Rc===Ud)return a;if(Array.isArray(a)){var d=a[K]|0,e=d;e===0&&(e|=c&32);e|=c&2;e!==d&&Rd(a,e);return new b(a)}}
;function Ue(a){return a}
function Ve(a){return a}
function We(a,b,c,d){return Xe(a,b,c,d,Ye,Ze)}
function $e(a,b,c,d){return Xe(a,b,c,d,af,bf)}
function Xe(a,b,c,d,e,f){if(!c.length&&!d)return 1;for(var g=0,h=0,k=0,l=0,m=0,n=c.length-1;n>=0;n--){var p=c[n];d&&n===c.length-1&&p===d||(l++,p!=null&&k++)}if(d)for(var t in d)n=+t,isNaN(n)||(m+=cf(n),h++,n>g&&(g=n));l=e(l,k)+f(h,g,m);t=k;n=h;p=g;for(var v=m,x=c.length-1;x>=0;x--){var z=c[x];if(!(z==null||d&&x===c.length-1&&z===d)){z=x-b;var G=e(z,t)+f(n,p,v);G<l&&(a=1+z,l=G);n++;t--;v+=cf(z);p=Math.max(p,z)}}b=e(0,0)+f(n,p,v);b<l&&(a=1,l=b);if(d){n=h;p=g;v=m;t=k;for(var J in d)d=+J,isNaN(d)||d>=
1024||(n--,t++,v-=J.length,g=e(d,t)+f(n,p,v),g<l&&(a=1+d,l=g))}return a}
function bf(a,b,c){return c+a*3+(a>1?a-1:0)}
function af(a,b){return(a>1?a-1:0)+(a-b)*4}
function Ze(a,b){return a==0?0:9*Math.max(1<<32-Math.clz32(a+a/2-1),4)<=b?a==0?0:a<4?100+(a-1)*16:a<6?148+(a-4)*16:a<12?244+(a-6)*16:a<22?436+(a-12)*19:a<44?820+(a-22)*17:52+32*a:40+4*b}
function Ye(a){return 40+4*a}
function cf(a){return a>=100?a>=1E4?Math.ceil(Math.log10(1+a)):a<1E3?3:4:a<10?1:2}
;function df(a,b,c,d,e){var f=d?!!(b&32):void 0;d=[];var g=a.length,h=!1;if(b&64){if(b&256){g--;var k=a[g];var l=g;Vd(k)}else l=4294967295,k=void 0,g&&Vd(a[g-1]);if(!(e||b&512)){h=!0;var m;var n=((m=ef)!=null?m:Ve)(k?l- -1:b>>14&1023||536870912,-1,a,k);l=n+-1}}else l=4294967295,b&1||(k=g&&a[g-1],Vd(k)?(g--,l=g,n=0):k=void 0);m=void 0;for(var p=0;p<g;p++){var t=a[p];if(t!=null&&(t=c(t,f))!=null)if(p>=l){var v=void 0;((v=m)!=null?v:m={})[p- -1]=t}else d[p]=t}if(k)for(var x in k)g=k[x],g!=null&&(g=c(g,
f))!=null&&(p=+x,p<n?d[p+-1]=g:(p=void 0,((p=m)!=null?p:m={})[x]=g));m&&(h?d.push(m):d[l]=m);e&&(Rd(d,b&16761409|(m!=null?290:34)),(a=(b=ab(Ld))?a[b]:void 0)&&(d[Ld]=Td(a)));return d}
function ff(a){switch(typeof a){case "number":return Number.isFinite(a)?a:""+a;case "bigint":return ne(a)?Number(a):""+a;case "boolean":return a?1:0;case "object":if(Array.isArray(a)){var b=a[K]|0;return a.length===0&&b&1?void 0:df(a,b,ff,!1,!1)}if(a.Rc===Ud)return gf(a);if(a instanceof Bd)return b=a.h,b==null?"":typeof b==="string"?b:a.h=vd(b);if(zd(a))return zd(a)&&Gd(Nd),vd(a);return}return a}
var ef;function hf(a,b){if(b){ef=b===Ve||b!==Ue&&b!==We&&b!==$e?Ve:b;try{return gf(a)}finally{ef=void 0}}return gf(a)}
function gf(a){a=a.F;return df(a,a[K]|0,ff,void 0,!1)}
;function L(a,b,c){if(a==null){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-16760833|(b&1023)<<14)}else{if(!Array.isArray(a))throw Error("narr");d=a[K]|0;8192&d||!(64&d)||2&d||jf();if(d&1024)throw Error("farr");if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error("mid");a:{c=a;var e=c.length;if(e){var f=e-1,g=c[f];if(Vd(g)){d|=256;b=d&512?0:-1;f-=b;if(f>=1024)throw Error("pvtlmt");for(var h in g)e=+h,e<f&&(c[e+b]=g[h],delete g[h]);d=d&-16760833|(f&1023)<<14;break a}}if(b){h=Math.max(b,e-(d&512?0:
-1));if(h>1024)throw Error("spvt");d=d&-16760833|(h&1023)<<14}}}Rd(a,d);return a}
function jf(){Gd(Md)}
;function kf(a,b){if(typeof a!=="object")return a;if(Array.isArray(a)){var c=a[K]|0;if(a.length===0&&c&1)return;if(c&2)return a;var d;if(d=b)d=c===0||!!(c&32)&&!(c&64||!(c&16));return d?(Qd(a,34),c&4&&Object.freeze(a),a):df(a,c,kf,b!==void 0,!0)}if(a.Rc===Ud)return b=a.F,c=b[K]|0,c&2?a:df(b,c,kf,!0,!0);if(a instanceof Bd)return a;if(zd(a))return zd(a)&&Gd(Nd),new Uint8Array(a)}
function lf(a){var b=a.F;if(!((b[K]|0)&2))return a;a=new a.constructor(df(b,b[K]|0,kf,!0,!0));b=a.F;b[K]&=-3;return a}
;function mf(a,b){a=a.F;return nf(a,a[K]|0,b)}
function nf(a,b,c){if(c===-1)return null;var d=c+(b&512?0:-1),e=a.length-1;if(d>=e&&b&256)return a[e][c];if(d<=e)return a[d]}
function of(a,b,c){var d=a.F,e=d[K]|0;Yd(e);pf(d,e,b,c);return a}
function pf(a,b,c,d){var e=b&512?0:-1,f=c+e,g=a.length-1;if(f>=g&&b&256)return a[g][c]=d,b;if(f<=g)return a[f]=d,b;d!==void 0&&(g=b>>14&1023||536870912,c>=g?d!=null&&(f={},a[g+e]=(f[c]=d,f),b|=256,Rd(a,b)):a[f]=d);return b}
function qf(a){return!!(2&a)&&!!(4&a)||!!(1024&a)}
function rf(a,b,c){var d=a.F,e=d[K]|0;Yd(e);if(b==null)return pf(d,e,3),a;if(!Array.isArray(b))throw Fd();var f=b[K]|0,g=f,h=qf(f),k=h||Object.isFrozen(b);h||(f=0);k||(b=Td(b),g=0,f=sf(f,e),f=tf(f,e,!0),k=!1);f|=21;h=4&f?2048&f?2048:4096&f?4096:0:void 0;h=h!=null?h:0;for(var l=0;l<b.length;l++){var m=b[l],n=c(m,h);Object.is(m,n)||(k&&(b=Td(b),g=0,f=sf(f,e),f=tf(f,e,!0),k=!1),b[l]=n)}f!==g&&(k&&(b=Td(b),f=sf(f,e),f=tf(f,e,!0)),Rd(b,f));pf(d,e,3,b);return a}
function uf(a,b,c,d){a=a.F;var e=a[K]|0;Yd(e);if(d==null){var f=vf(a);if(wf(f,a,e,c)===b)f.set(c,0);else return}else{c.includes(b);f=vf(a);var g=wf(f,a,e,c);g!==b&&(g&&(e=pf(a,e,g)),f.set(c,b))}pf(a,e,b,d)}
function vf(a){if(Hd){var b;return(b=a[Kd])!=null?b:a[Kd]=new Map}if(Kd in a)return a[Kd];b=new Map;Object.defineProperty(a,Kd,{value:b});return b}
function wf(a,b,c,d){var e=a.get(d);if(e!=null)return e;for(var f=e=0;f<d.length;f++){var g=d[f];nf(b,c,g)!=null&&(e!==0&&(c=pf(b,c,e)),e=g)}a.set(d,e);return e}
function xf(a,b,c){a=a.F;var d=a[K]|0,e=nf(a,d,c);b=Te(e,b,d);b!==e&&b!=null&&pf(a,d,c,b);return b}
function yf(a,b,c){b=xf(a,b,c);if(b==null)return b;a=a.F;var d=a[K]|0;if(!(d&2)){var e=lf(b);e!==b&&(b=e,pf(a,d,c,b))}return b}
function Ac(a,b,c){var d=void 0===Zd?2:4;var e=a.F[K]|0,f=e,g=!(2&e);a=a.F;var h=!!(2&f);e=h?1:d;g&&(g=!h);d=nf(a,f,c);d=Array.isArray(d)?d:Wd;var k=d[K]|0;h=!!(4&k);if(!h){var l=k;l===0&&(l=sf(l,f));k=d;l|=1;var m=f,n=!!(2&l);n&&(m|=2);for(var p=!n,t=!0,v=0,x=0;v<k.length;v++){var z=Te(k[v],b,m);if(z instanceof b){if(!n){var G=!!((z.F[K]|0)&2);p&&(p=!G);t&&(t=G)}k[x++]=z}}x<v&&(k.length=x);l|=4;l=t?l|16:l&-17;l=p?l|8:l&-9;Rd(k,l);n&&Object.freeze(k);k=l}if(g&&!(8&k||!d.length&&(e===1||e===4&&32&
k))){qf(k)&&(d=Td(d),k=sf(k,f),f=pf(a,f,c,d));b=d;g=k;for(k=0;k<b.length;k++)l=b[k],m=lf(l),l!==m&&(b[k]=m);g|=8;g=b.length?g&-17:g|16;Rd(b,g);k=g}e===1||e===4&&32&k?qf(k)||(f=k,c=!!(32&k),k|=!d.length||16&k&&(!h||c)?2:1024,k!==f&&Rd(d,k),Object.freeze(d)):(e===2&&qf(k)&&(d=Td(d),k=sf(k,f),k=tf(k,f,!1),Rd(d,k),f=pf(a,f,c,d)),qf(k)||(c=k,k=tf(k,f,!1),k!==c&&Rd(d,k)));return d}
function zf(a,b,c,d){d!=null?Se(d,b):d=void 0;return of(a,c,d)}
function Af(a,b,c,d){var e=a.F,f=e[K]|0;Yd(f);if(d==null)return pf(e,f,c),a;if(!Array.isArray(d))throw Fd();for(var g=d[K]|0,h=g,k=qf(g),l=k||Object.isFrozen(d),m=!0,n=!0,p=0;p<d.length;p++){var t=d[p];Se(t,b);k||(t=!!((t.F[K]|0)&2),m&&(m=!t),n&&(n=t))}k||(g=m?13:5,g=n?g|16:g&-17);l&&g===h||(d=Td(d),h=0,g=sf(g,f),g=tf(g,f,!0));g!==h&&Rd(d,g);pf(e,f,c,d);return a}
function sf(a,b){a=(2&b?a|2:a&-3)|32;return a&=-1025}
function tf(a,b,c){32&b&&c||(a&=-33);return a}
function Bf(a){a=mf(a,1);var b=b===void 0?!1:b;var c=typeof a;b=a==null?a:c==="bigint"?String(we(64,a)):De(a)?c==="string"?Ie(a):b?Je(a):Le(a):void 0;return b}
function Cc(a,b,c){c=c===void 0?0:c;var d;return(d=Ge(mf(a,b)))!=null?d:c}
function Cf(a,b){var c=c===void 0?"":c;var d;return(d=Re(mf(a,b)))!=null?d:c}
function Df(a){var b=b===void 0?0:b;a=mf(a,1);a=a==null?a:ye(a)?a|0:void 0;return a!=null?a:b}
function Ef(a,b,c){return of(a,b,Qe(c))}
function Ff(a,b,c){c=Qe(c);a=a.F;var d=a[K]|0;Yd(d);pf(a,d,b,c===""?void 0:c)}
function Gf(a,b,c){if(c!=null){if(!ye(c))throw Fd("enum");c|=0}return of(a,b,c)}
;function M(a,b,c){this.F=L(a,b,c)}
r=M.prototype;r.toJSON=function(){return hf(this)};
r.serialize=function(a){return JSON.stringify(hf(this,a))};
function Hf(a,b){if(b==null||b=="")return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error("dnarr");Qd(b,32);return new a(b)}
r.clone=function(){var a=this,b=a.F;a=new a.constructor(df(b,b[K]|0,kf,!0,!0));b=a.F;b[K]&=-3;return a};
r.Rc=Ud;r.toString=function(){return this.F.toString()};function If(){this.ctor=Jf;this.isRepeated=0;this.h=yf;this.defaultValue=void 0}
If.prototype.register=function(){dd(this)};function Kf(a){return function(b){return Hf(a,b)}}
;function Lf(a){this.F=L(a)}
w(Lf,M);function Mf(a,b){return rf(a,b,Ee)}
;function Nf(a){this.F=L(a)}
w(Nf,M);var Of=[1,2,3];function Pf(a){this.F=L(a)}
w(Pf,M);var Qf=[1,2,3];function Rf(a){this.F=L(a)}
w(Rf,M);function Sf(a){this.F=L(a)}
w(Sf,M);function Tf(a){this.F=L(a)}
w(Tf,M);function Uf(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.indexOf("blob:")===0&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();a.indexOf("//")==0&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");c!=-1&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if(c!=="http"&&c!=="https"&&c!=="chrome-extension"&&
c!=="moz-extension"&&c!=="file"&&c!=="android-app"&&c!=="chrome-search"&&c!=="chrome-untrusted"&&c!=="chrome"&&c!=="app"&&c!=="devtools")throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(d!=-1){var e=b.substring(d+1);b=b.substring(0,d);if(c==="http"&&e!=="80"||c==="https"&&e!=="443")a=":"+e}return c+"://"+b+a}
;function Vf(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(n){for(var p=g,t=0;t<64;t+=4)p[t/4]=n[t]<<24|n[t+1]<<16|n[t+2]<<8|n[t+3];for(t=16;t<80;t++)n=p[t-3]^p[t-8]^p[t-14]^p[t-16],p[t]=(n<<1|n>>>31)&4294967295;n=e[0];var v=e[1],x=e[2],z=e[3],G=e[4];for(t=0;t<80;t++){if(t<40)if(t<20){var J=z^v&(x^z);var ba=1518500249}else J=v^x^z,ba=1859775393;else t<60?(J=v&x|z&(v|x),ba=2400959708):(J=v^x^z,ba=3395469782);J=((n<<5|n>>>27)&4294967295)+J+G+ba+p[t]&4294967295;G=z;z=x;x=(v<<30|v>>>2)&4294967295;v=n;n=J}e[0]=e[0]+n&4294967295;e[1]=e[1]+v&4294967295;
e[2]=e[2]+x&4294967295;e[3]=e[3]+z&4294967295;e[4]=e[4]+G&4294967295}
function c(n,p){if(typeof n==="string"){n=unescape(encodeURIComponent(n));for(var t=[],v=0,x=n.length;v<x;++v)t.push(n.charCodeAt(v));n=t}p||(p=n.length);t=0;if(l==0)for(;t+64<p;)b(n.slice(t,t+64)),t+=64,m+=64;for(;t<p;)if(f[l++]=n[t++],m++,l==64)for(l=0,b(f);t+64<p;)b(n.slice(t,t+64)),t+=64,m+=64}
function d(){var n=[],p=m*8;l<56?c(h,56-l):c(h,64-(l-56));for(var t=63;t>=56;t--)f[t]=p&255,p>>>=8;b(f);for(t=p=0;t<5;t++)for(var v=24;v>=0;v-=8)n[p++]=e[t]>>v&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;k<64;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,je:function(){for(var n=d(),p="",t=0;t<n.length;t++)p+="0123456789ABCDEF".charAt(Math.floor(n[t]/16))+"0123456789ABCDEF".charAt(n[t]%16);return p}}}
;function Wf(a,b,c){var d=String(D.location.href);return d&&a&&b?[b,Xf(Uf(d),a,c||null)].join(" "):null}
function Xf(a,b,c){var d=[],e=[];if((Array.isArray(c)?2:1)==1)return e=[b,a],Nb(d,function(h){e.push(h)}),Yf(e.join(" "));
var f=[],g=[];Nb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=f.length==0?[c,b,a]:[f.join(":"),c,b,a];Nb(d,function(h){e.push(h)});
a=Yf(e.join(" "));a=[c,a];g.length==0||a.push(g.join(""));return a.join("_")}
function Yf(a){var b=Vf();b.update(a);return b.je().toLowerCase()}
;function Zf(a){this.h=a||{cookie:""}}
r=Zf.prototype;r.isEnabled=function(){if(!D.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{Tb:60});if(this.get("TESTCOOKIESENABLED")!=="1")return!1;this.remove("TESTCOOKIESENABLED");return!0};
r.set=function(a,b,c){var d=!1;if(typeof c==="object"){var e=c.bf;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Tb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');h===void 0&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=h<0?"":h==0?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+h*1E3)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(e!=null?";samesite="+
e:"")};
r.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=db(d[e]);if(f.lastIndexOf(c,0)==0)return f.slice(c.length);if(f==a)return""}return b};
r.remove=function(a,b,c){var d=this.get(a)!==void 0;this.set(a,"",{Tb:0,path:b,domain:c});return d};
r.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=db(a[f]),d=e.indexOf("="),d==-1?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;a>=0;a--)this.remove(b[a])};
var $f=new Zf(typeof document=="undefined"?null:document);function ag(){var a=D.__SAPISID||D.__APISID||D.__3PSAPISID||D.__1PSAPISID||D.__OVERRIDE_SID;if(a)return!0;typeof document!=="undefined"&&(a=new Zf(document),a=a.get("SAPISID")||a.get("APISID")||a.get("__Secure-3PAPISID")||a.get("__Secure-1PAPISID"));return!!a}
function bg(a,b,c,d){(a=D[a])||typeof document==="undefined"||(a=(new Zf(document)).get(b));return a?Wf(a,c,d):null}
function cg(a){var b=Uf(String(D.location.href)),c=[];if(ag()){b=b.indexOf("https:")==0||b.indexOf("chrome-extension:")==0||b.indexOf("chrome-untrusted://new-tab-page")==0||b.indexOf("moz-extension:")==0;var d=b?D.__SAPISID:D.__APISID;d||typeof document==="undefined"||(d=new Zf(document),d=d.get(b?"SAPISID":"APISID")||d.get("__Secure-3PAPISID"));(d=d?Wf(d,b?"SAPISIDHASH":"APISIDHASH",a):null)&&c.push(d);b&&((b=bg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&c.push(b),(a=bg("__3PSAPISID",
"__Secure-3PAPISID","SAPISID3PHASH",a))&&c.push(a))}return c.length==0?null:c.join(" ")}
;function dg(){}
dg.prototype.compress=function(a){var b,c,d,e;return B(function(f){switch(f.h){case 1:return b=new CompressionStream("gzip"),c=(new Response(b.readable)).arrayBuffer(),d=b.writable.getWriter(),f.yield(d.write((new TextEncoder).encode(a)),2);case 2:return f.yield(d.close(),3);case 3:return e=Uint8Array,f.yield(c,4);case 4:return f.return(new e(f.i))}})};
dg.prototype.isSupported=function(a){return a<1024?!1:typeof CompressionStream!=="undefined"};function eg(a){this.F=L(a)}
w(eg,M);function fg(a,b){this.intervalMs=a;this.callback=b;this.enabled=!1;this.h=function(){return $a()};
this.i=this.h()}
fg.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
fg.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.i=this.h())};
fg.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
fg.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.h()-this.i,0);b<this.intervalMs*.8?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),this.callback(),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function gg(a){this.F=L(a)}
w(gg,M);function hg(a){this.F=L(a)}
w(hg,M);function ig(a,b){this.x=a!==void 0?a:0;this.y=b!==void 0?b:0}
r=ig.prototype;r.clone=function(){return new ig(this.x,this.y)};
r.equals=function(a){return a instanceof ig&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
r.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
r.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
r.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
r.scale=function(a,b){this.x*=a;this.y*=typeof b==="number"?b:a;return this};function jg(a,b){this.width=a;this.height=b}
r=jg.prototype;r.clone=function(){return new jg(this.width,this.height)};
r.aspectRatio=function(){return this.width/this.height};
r.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
r.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
r.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
r.scale=function(a,b){this.width*=a;this.height*=typeof b==="number"?b:a;return this};function kg(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function lg(a){var b=mg,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function ng(a){for(var b in a)return!1;return!0}
function og(a,b){if(a!==null&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function pg(a){return a!==null&&"privembed"in a?a.privembed:!1}
function qg(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function rg(a){var b={},c;for(c in a)b[c]=a[c];return b}
function sg(a){if(!a||typeof a!=="object")return a;if(typeof a.clone==="function")return a.clone();if(typeof Map!=="undefined"&&a instanceof Map)return new Map(a);if(typeof Set!=="undefined"&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:typeof ArrayBuffer!=="function"||typeof ArrayBuffer.isView!=="function"||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=sg(a[c]);return b}
var tg="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function ug(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<tg.length;f++)c=tg[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function vg(a,b){this.h=a===wg&&b||""}
vg.prototype.toString=function(){return this.h};
var wg={};new vg(wg,"");"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function xg(a){var b=document;return typeof a==="string"?b.getElementById(a):a}
function yg(a){var b=document;a=String(a);b.contentType==="application/xhtml+xml"&&(a=a.toLowerCase());return b.createElement(a)}
function zg(a){a&&a.parentNode&&a.parentNode.removeChild(a)}
function Ag(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Bg(a){this.F=L(a)}
w(Bg,M);Bg.prototype.lc=function(){return Df(this)};function Cg(a){this.F=L(a)}
w(Cg,M);function Dg(a){this.F=L(a)}
w(Dg,M);function Eg(a,b){Af(a,Cg,1,b)}
;function Fg(a){this.F=L(a)}
w(Fg,M);var Gg=["platform","platformVersion","architecture","model","uaFullVersion"],Hg=new Dg,Ig=null;function Jg(a,b){b=b===void 0?Gg:b;if(!Ig){var c;a=(c=a.navigator)==null?void 0:c.userAgentData;if(!a||typeof a.getHighEntropyValues!=="function"||a.brands&&typeof a.brands.map!=="function")return Promise.reject(Error("UACH unavailable"));c=(a.brands||[]).map(function(e){var f=new Cg;f=Ef(f,1,e.brand);return Ef(f,2,e.version)});
Eg(of(Hg,2,Be(a.mobile)),c);Ig=a.getHighEntropyValues(b)}var d=new Set(b);return Ig.then(function(e){var f=Hg.clone();d.has("platform")&&Ef(f,3,e.platform);d.has("platformVersion")&&Ef(f,4,e.platformVersion);d.has("architecture")&&Ef(f,5,e.architecture);d.has("model")&&Ef(f,6,e.model);d.has("uaFullVersion")&&Ef(f,7,e.uaFullVersion);return f}).catch(function(){return Hg.clone()})}
;function Kg(a){this.F=L(a)}
w(Kg,M);function Lg(a){this.F=L(a,4)}
w(Lg,M);function Mg(a){this.F=L(a,36)}
w(Mg,M);function Ng(a){this.F=L(a,19)}
w(Ng,M);Ng.prototype.Wb=function(a){return Gf(this,2,a)};function Og(a,b){this.Wa=b=b===void 0?!1:b;this.j=this.locale=null;this.i=0;this.isFinal=!1;this.h=new Ng;Number.isInteger(a)&&this.h.Wb(a);b||(this.locale=document.documentElement.getAttribute("lang"));Pg(this,new Kg)}
Og.prototype.Wb=function(a){this.h.Wb(a);return this};
function Pg(a,b){zf(a.h,Kg,1,b);Df(b)||Gf(b,1,1);a.Wa||(b=Qg(a),Cf(b,5)||Ef(b,5,a.locale));a.j&&(b=Qg(a),yf(b,Dg,9)||zf(b,Dg,9,a.j))}
function Rg(a,b){a.i=b}
function Sg(a){var b=b===void 0?Gg:b;var c=a.Wa?void 0:window;c?Jg(c,b).then(function(d){a.j=d;d=Qg(a);zf(d,Dg,9,a.j);return!0}).catch(function(){return!1}):Promise.resolve(!1)}
function Qg(a){a=yf(a.h,Kg,1);var b=yf(a,Fg,11);b||(b=new Fg,zf(a,Fg,11,b));return b}
function Tg(a,b,c,d,e,f,g){c=c===void 0?0:c;d=d===void 0?0:d;e=e===void 0?null:e;f=f===void 0?0:f;g=g===void 0?0:g;if(xf(yf(a.h,Kg,1),Fg,11)!==void 0){var h=Qg(a);var k=new Bg;k=Gf(k,1,a.i);k=of(k,2,Be(a.isFinal));d=of(k,3,Fe(d>0?d:void 0));d=of(d,4,Fe(f>0?f:void 0));d=of(d,5,Fe(g>0?g:void 0));f=d.F;g=f[K]|0;d=g&2?d:new d.constructor(df(f,g,kf,!0,!0));zf(h,Bg,10,d)}a=a.h.clone();h=Date.now().toString();a=of(a,4,Me(h));b=b.slice();b=Af(a,Mg,3,b);e&&(a=new gg,e=of(a,13,Fe(e)),a=new hg,e=zf(a,gg,2,e),
a=new Lg,e=zf(a,hg,1,e),e=Gf(e,2,9),zf(b,Lg,18,e));c&&of(b,14,Me(c));return b}
;var Ug=function(){if(!D.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
D.addEventListener("test",c,b);D.removeEventListener("test",c,b)}catch(d){}return a}();function Vg(a){this.h=this.i=this.j=a}
Vg.prototype.reset=function(){this.h=this.i=this.j};
Vg.prototype.getValue=function(){return this.i};function Wg(a){this.F=L(a,8)}
w(Wg,M);var Xg=Kf(Wg);function Jf(a){this.F=L(a)}
w(Jf,M);var Yg=new If;function Zg(a){H.call(this);var b=this;this.componentId="";this.h=[];this.Pa="";this.pageId=null;this.Qa=this.ha=-1;this.G=this.experimentIds=null;this.Y=this.Z=this.D=this.o=0;this.rb=1;this.timeoutMillis=0;this.oa=!1;this.logSource=a.logSource;this.hb=a.hb||function(){};
this.j=new Og(a.logSource,a.Wa);this.network=a.network||null;this.mb=a.mb||null;this.bufferSize=1E3;this.P=a.zf||null;this.sessionIndex=a.sessionIndex||null;this.Ob=a.Ob||!1;this.logger=null;this.withCredentials=!a.qd;this.Wa=a.Wa||!1;this.U=!this.Wa&&!!window&&!!window.navigator&&window.navigator.sendBeacon!==void 0;this.Fa=typeof URLSearchParams!=="undefined"&&!!(new URL($g())).searchParams&&!!(new URL($g())).searchParams.set;var c=Gf(new Kg,1,1);Pg(this.j,c);this.u=new Vg(1E4);a=ah(this,a.ld);
this.i=new fg(this.u.getValue(),a);this.xa=new fg(6E5,a);this.Ob||this.xa.start();this.Wa||(document.addEventListener("visibilitychange",function(){document.visibilityState==="hidden"&&b.Jc()}),document.addEventListener("pagehide",this.Jc.bind(this)))}
w(Zg,H);function ah(a,b){return a.Fa?b?function(){b().then(function(){a.flush()})}:function(){a.flush()}:function(){}}
r=Zg.prototype;r.ba=function(){this.Jc();this.i.stop();this.xa.stop();H.prototype.ba.call(this)};
function bh(a){a.P||(a.P=$g());try{return(new URL(a.P)).toString()}catch(b){return(new URL(a.P,window.location.origin)).toString()}}
r.log=function(a){if(this.Fa){a=a.clone();var b=this.rb++;a=of(a,21,Me(b));this.componentId&&Ef(a,26,this.componentId);b=a;if(Bf(b)==null){var c=Date.now();c=Number.isFinite(c)?c.toString():"0";of(b,1,Me(c))}Oe(mf(b,15))==null&&of(b,15,Me((new Date).getTimezoneOffset()*60));this.experimentIds&&(c=this.experimentIds.clone(),zf(b,eg,16,c));b=this.h.length-this.bufferSize+1;b>0&&(this.h.splice(0,b),this.o+=b);this.h.push(a);this.Ob||this.i.enabled||this.i.start()}};
r.flush=function(a,b){var c=this;if(this.h.length===0)a&&a();else if(this.oa&&this.U)this.j.i=3,ch(this);else{var d=Date.now();if(this.Qa>d&&this.ha<d)b&&b("throttled");else{this.network&&(typeof this.network.lc==="function"?Rg(this.j,this.network.lc()):this.j.i=0);var e=Tg(this.j,this.h,this.o,this.D,this.mb,this.Z,this.Y),f=this.hb();if(f&&this.Pa===f)b&&b("stale-auth-token");else{this.h=[];this.i.enabled&&this.i.stop();this.o=0;d=e.serialize();var g;this.G&&this.G.isSupported(d.length)&&(g=this.G.compress(d));
var h=dh(this,d,f),k=function(n){c.u.reset();c.i.setInterval(c.u.getValue());if(n){var p=null;try{var t=JSON.stringify(JSON.parse(n.replace(")]}'\n","")));p=Xg(t)}catch(z){}if(p){n=Number;var v="-1";v=v===void 0?"0":v;var x;t=(x=Bf(p))!=null?x:v;x=n(t);x>0&&(c.ha=Date.now(),c.Qa=c.ha+x);p=Yg.ctor?Yg.h(p,Yg.ctor,175237375):Yg.h(p,175237375,null);if(p=p===null?void 0:p)p=Cc(p,1,-1),p!==-1&&(c.u=new Vg(p<1?1:p),c.i.setInterval(c.u.getValue()))}}a&&a();c.D=0},l=function(n,p){var t=Ac(e,Mg,3);
var v;var x=(v=Oe(mf(e,14)))!=null?v:void 0;v=c.u;v.h=Math.min(3E5,v.h*2);v.i=Math.min(3E5,v.h+Math.round(.1*(Math.random()-.5)*2*v.h));c.i.setInterval(c.u.getValue());n===401&&f&&(c.Pa=f);x&&(c.o+=x);p===void 0&&(p=c.isRetryable(n));p&&(c.h=t.concat(c.h),c.Ob||c.i.enabled||c.i.start());b&&b("net-send-failed",n);++c.D},m=function(){c.network&&c.network.send(h,k,l)};
g?g.then(function(n){h.Bc["Content-Encoding"]="gzip";h.Bc["Content-Type"]="application/binary";h.body=n;h.ce=2;m()},function(){m()}):m()}}}};
function dh(a,b,c){c=c===void 0?a.hb():c;var d={},e=new URL(bh(a));c&&(d.Authorization=c);a.sessionIndex&&(d["X-Goog-AuthUser"]=a.sessionIndex,e.searchParams.set("authuser",a.sessionIndex));a.pageId&&(Object.defineProperty(d,"X-Goog-PageId",{value:a.pageId}),e.searchParams.set("pageId",a.pageId));return{url:e.toString(),body:b,ce:1,Bc:d,requestType:"POST",withCredentials:a.withCredentials,timeoutMillis:a.timeoutMillis}}
r.Jc=function(){this.j.isFinal=!0;this.flush();this.j.isFinal=!1};
function ch(a){gh(a,function(b,c){b=new URL(b);b.searchParams.set("format","json");var d=!1;try{d=window.navigator.sendBeacon(b.toString(),c.serialize())}catch(e){}d||(a.U=!1);return d})}
function gh(a,b){if(a.h.length!==0){var c=new URL(bh(a));c.searchParams.delete("format");var d=a.hb();d&&c.searchParams.set("auth",d);c.searchParams.set("authuser",a.sessionIndex||"0");for(d=0;d<10&&a.h.length;++d){var e=a.h.slice(0,32),f=Tg(a.j,e,a.o,a.D,a.mb,a.Z,a.Y);if(!b(c.toString(),f)){++a.D;break}a.o=0;a.D=0;a.Z=0;a.Y=0;a.h=a.h.slice(e.length)}a.i.enabled&&a.i.stop()}}
r.isRetryable=function(a){return 500<=a&&a<600||a===401||a===0};
function $g(){return"https://play.google.com/log?format=json&hasfast=true"}
;function hh(){this.Wd=typeof AbortController!=="undefined"}
hh.prototype.send=function(a,b,c){var d=this,e,f,g,h,k,l,m,n,p,t;return B(function(v){switch(v.h){case 1:return f=(e=d.Wd?new AbortController:void 0)?setTimeout(function(){e.abort()},a.timeoutMillis):void 0,ya(v,2,3),g=Object.assign({},{method:a.requestType,
headers:Object.assign({},a.Bc)},a.body&&{body:a.body},a.withCredentials&&{credentials:"include"},{signal:a.timeoutMillis&&e?e.signal:null}),v.yield(fetch(a.url,g),5);case 5:h=v.i;if(h.status!==200){(k=c)==null||k(h.status);v.A(3);break}if((l=b)==null){v.A(7);break}return v.yield(h.text(),8);case 8:l(v.i);case 7:case 3:v.P=[v.j];v.M=0;v.o=0;clearTimeout(f);Ba(v);break;case 2:m=Aa(v);switch((n=m)==null?void 0:n.name){case "AbortError":(p=c)==null||p(408);break;default:(t=c)==null||t(400)}v.A(3)}})};
hh.prototype.lc=function(){return 4};function ih(a,b){H.call(this);this.logSource=a;this.sessionIndex=b;this.Ua="https://play.google.com/log?format=json&hasfast=true";this.i=null;this.o=!1;this.network=null;this.componentId="";this.h=this.mb=null;this.j=!1;this.pageId=null;this.bufferSize=void 0}
w(ih,H);function jh(a,b){a.i=b;return a}
function kh(a,b){a.network=b;return a}
function lh(a,b){a.h=b}
function mh(a){a.j=!0;return a}
ih.prototype.qd=function(){this.u=!0;return this};
function nh(a){a.network||(a.network=new hh);var b=new Zg({logSource:a.logSource,hb:a.hb?a.hb:cg,sessionIndex:a.sessionIndex,zf:a.Ua,Wa:a.o,Ob:!1,qd:a.u,ld:a.ld,network:a.network});uc(a,b);if(a.i){var c=a.i,d=Qg(b.j);Ef(d,7,c)}b.G=new dg;a.componentId&&(b.componentId=a.componentId);a.mb&&(b.mb=a.mb);a.pageId&&(b.pageId=a.pageId);a.h&&((d=a.h)?(b.experimentIds||(b.experimentIds=new eg),c=b.experimentIds,d=d.serialize(),Ef(c,4,d)):b.experimentIds&&of(b.experimentIds,4));a.j&&(b.oa=b.U);Sg(b.j);a.bufferSize&&
(b.bufferSize=a.bufferSize);a.network.Wb&&a.network.Wb(a.logSource);a.network.nf&&a.network.nf(b);return b}
;function oh(a,b,c,d,e,f,g){a=a===void 0?-1:a;b=b===void 0?"":b;c=c===void 0?"":c;d=d===void 0?!1:d;e=e===void 0?"":e;H.call(this);this.logSource=a;this.componentId=b;f?b=f:(a=new ih(a,"0"),a.componentId=b,uc(this,a),c!==""&&(a.Ua=c),d&&(a.o=!0),e&&jh(a,e),g&&kh(a,g),b=nh(a));this.h=b}
w(oh,H);
oh.prototype.flush=function(a){var b=a||[];if(b.length){a=new Tf;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=new Sf;f=Ef(f,1,e.i);var g=ph(e);f=rf(f,g,Pe);g=[];var h=[];for(var k=y(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var m=e.o;for(var n=e.Kc(l)||[],p=[],t=0;t<n.length;t++){var v=n[t],x=v&&v.h;v=new Pf;switch(m){case 3:x=Number(x);Number.isFinite(x)&&uf(v,1,Qf,Me(x));break;case 2:x=Number(x);if(x!=null&&typeof x!=="number")throw Error("Value of float/double field must be a number, found "+typeof x+
": "+x);uf(v,2,Qf,x)}p.push(v)}m=p;for(n=0;n<m.length;n++){p=m[n];t=new Rf;p=zf(t,Pf,2,p);t=l;v=[];x=qh(e);for(var z=0;z<x.length;z++){var G=x[z],J=t[z],ba=new Nf;switch(G){case 3:uf(ba,1,Of,Qe(String(J)));break;case 2:G=Number(J);Number.isFinite(G)&&uf(ba,2,Of,Fe(G));break;case 1:uf(ba,3,Of,Be(J==="true"))}v.push(ba)}Af(p,Nf,1,v);g.push(p)}}Af(f,Rf,4,g);c.push(f);e.clear()}Af(a,Sf,1,c);b=this.h;if(a instanceof Mg)b.log(a);else try{var ca=new Mg,Ma=a.serialize();var Kb=Ef(ca,8,Ma);b.log(Kb)}catch(ja){}this.h.flush()}};function rh(a){this.h=a}
;function sh(a,b,c){this.i=a;this.o=b;this.fields=c||[];this.h=new Map}
function qh(a){return a.fields.map(function(b){return b.fieldType})}
function ph(a){return a.fields.map(function(b){return b.fieldName})}
r=sh.prototype;r.Xd=function(a){var b=C.apply(1,arguments),c=this.Kc(b);c?c.push(new rh(a)):this.Id(a,b)};
r.Id=function(a){var b=this.kd(C.apply(1,arguments));this.h.set(b,[new rh(a)])};
r.Kc=function(){var a=this.kd(C.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
r.we=function(){var a=this.Kc(C.apply(0,arguments));return a&&a.length?a[0]:void 0};
r.clear=function(){this.h.clear()};
r.kd=function(){var a=C.apply(0,arguments);return a?a.join(","):"key"};function th(a,b){sh.call(this,a,3,b)}
w(th,sh);th.prototype.j=function(a){var b=C.apply(1,arguments),c=0,d=this.we(b);d&&(c=d.h);this.Id(c+a,b)};function uh(a,b){sh.call(this,a,2,b)}
w(uh,sh);uh.prototype.record=function(a){this.Xd(a,C.apply(1,arguments))};function vh(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
vh.prototype.stopPropagation=function(){this.j=!0};
vh.prototype.preventDefault=function(){this.defaultPrevented=!0};function wh(a,b){vh.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
bb(wh,vh);
wh.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;b=a.relatedTarget;b||(c=="mouseover"?b=a.fromElement:c=="mouseout"&&(b=a.toElement));this.relatedTarget=b;d?(this.clientX=d.clientX!==void 0?d.clientX:d.pageX,this.clientY=d.clientY!==void 0?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||0):(this.clientX=a.clientX!==void 0?a.clientX:a.pageX,this.clientY=a.clientY!==
void 0?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||(c=="keypress"?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType=a.pointerType;this.state=a.state;this.i=a;a.defaultPrevented&&wh.Aa.preventDefault.call(this)};
wh.prototype.stopPropagation=function(){wh.Aa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
wh.prototype.preventDefault=function(){wh.Aa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var xh="closure_listenable_"+(Math.random()*1E6|0);var yh=0;function zh(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.oc=e;this.key=++yh;this.Vb=this.ec=!1}
function Ah(a){a.Vb=!0;a.listener=null;a.proxy=null;a.src=null;a.oc=null}
;function Bh(a){this.src=a;this.listeners={};this.h=0}
Bh.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Ch(a,b,d,e);g>-1?(b=a[g],c||(b.ec=!1)):(b=new zh(b,this.src,f,!!d,e),b.ec=c,a.push(b));return b};
Bh.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Ch(e,b,c,d);return b>-1?(Ah(e[b]),Array.prototype.splice.call(e,b,1),e.length==0&&(delete this.listeners[a],this.h--),!0):!1};
function Dh(a,b){var c=b.type;c in a.listeners&&Sb(a.listeners[c],b)&&(Ah(b),a.listeners[c].length==0&&(delete a.listeners[c],a.h--))}
function Ch(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Vb&&f.listener==b&&f.capture==!!c&&f.oc==d)return e}return-1}
;var Eh="closure_lm_"+(Math.random()*1E6|0),Fh={},Gh=0;function Hh(a,b,c,d,e){if(d&&d.once)Ih(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Hh(a,b[f],c,d,e);else c=Jh(c),a&&a[xh]?a.listen(b,c,Ra(d)?!!d.capture:!!d,e):Kh(a,b,c,!1,d,e)}
function Kh(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ra(e)?!!e.capture:!!e,h=Lh(a);h||(a[Eh]=h=new Bh(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Mh();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Ug||(e=g),e===void 0&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Nh(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Gh++}}
function Mh(){function a(c){return b.call(a.src,a.listener,c)}
var b=Oh;return a}
function Ih(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ih(a,b[f],c,d,e);else c=Jh(c),a&&a[xh]?Ph(a,b,c,Ra(d)?!!d.capture:!!d,e):Kh(a,b,c,!0,d,e)}
function Qh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Qh(a,b[f],c,d,e);else(d=Ra(d)?!!d.capture:!!d,c=Jh(c),a&&a[xh])?a.i.remove(String(b),c,d,e):a&&(a=Lh(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Ch(b,c,d,e)),(c=a>-1?b[a]:null)&&Rh(c))}
function Rh(a){if(typeof a!=="number"&&a&&!a.Vb){var b=a.src;if(b&&b[xh])Dh(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Nh(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Gh--;(c=Lh(b))?(Dh(c,a),c.h==0&&(c.src=null,b[Eh]=null)):Ah(a)}}}
function Nh(a){return a in Fh?Fh[a]:Fh[a]="on"+a}
function Oh(a,b){if(a.Vb)a=!0;else{b=new wh(b,this);var c=a.listener,d=a.oc||a.src;a.ec&&Rh(a);a=c.call(d,b)}return a}
function Lh(a){a=a[Eh];return a instanceof Bh?a:null}
var Sh="__closure_events_fn_"+(Math.random()*1E9>>>0);function Jh(a){if(typeof a==="function")return a;a[Sh]||(a[Sh]=function(b){return a.handleEvent(b)});
return a[Sh]}
;function Th(){H.call(this);this.i=new Bh(this);this.xa=this;this.Z=null}
bb(Th,H);Th.prototype[xh]=!0;r=Th.prototype;r.addEventListener=function(a,b,c,d){Hh(this,a,b,c,d)};
r.removeEventListener=function(a,b,c,d){Qh(this,a,b,c,d)};
function Uh(a,b){var c=a.Z;if(c){var d=[];for(var e=1;c;c=c.Z)d.push(c),++e}a=a.xa;c=b.type||b;typeof b==="string"?b=new vh(b,a):b instanceof vh?b.target=b.target||a:(e=b,b=new vh(c,a),ug(b,e));e=!0;var f;if(d)for(f=d.length-1;!b.j&&f>=0;f--){var g=b.h=d[f];e=Vh(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Vh(g,c,!0,b)&&e,b.j||(e=Vh(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Vh(g,c,!1,b)&&e}
r.ba=function(){Th.Aa.ba.call(this);this.removeAllListeners();this.Z=null};
r.listen=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function Ph(a,b,c,d,e){a.i.add(String(b),c,!0,d,e)}
r.removeAllListeners=function(a){if(this.i){var b=this.i;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,Ah(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function Vh(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Vb&&g.capture==c){var h=g.listener,k=g.oc||g.src;g.ec&&Dh(a.i,g);e=h.call(k,d)!==!1&&e}}return e&&!d.defaultPrevented}
;var Wh=typeof AsyncContext!=="undefined"&&typeof AsyncContext.Snapshot==="function"?function(a){return a&&AsyncContext.Snapshot.wrap(a)}:function(a){return a};function Xh(a,b){this.j=a;this.o=b;this.i=0;this.h=null}
Xh.prototype.get=function(){if(this.i>0){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Yh(a,b){a.o(b);a.i<100&&(a.i++,b.next=a.h,a.h=b)}
;function Zh(){this.i=this.h=null}
Zh.prototype.add=function(a,b){var c=$h.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Zh.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var $h=new Xh(function(){return new ai},function(a){return a.reset()});
function ai(){this.next=this.scope=this.h=null}
ai.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
ai.prototype.reset=function(){this.next=this.scope=this.h=null};var bi,ci=!1,di=new Zh;function ei(a,b){bi||fi();ci||(bi(),ci=!0);di.add(a,b)}
function fi(){var a=Promise.resolve(void 0);bi=function(){a.then(gi)}}
function gi(){for(var a;a=di.remove();){try{a.h.call(a.scope)}catch(b){Qc(b)}Yh($h,a)}ci=!1}
;function hi(){}
function ii(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;function ji(a){this.X=0;this.ab=void 0;this.ub=this.Sa=this.parent_=null;this.nc=this.Ic=!1;if(a!=hi)try{var b=this;a.call(void 0,function(c){ki(b,2,c)},function(c){ki(b,3,c)})}catch(c){ki(this,3,c)}}
function li(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
li.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var mi=new Xh(function(){return new li},function(a){a.reset()});
function ni(a,b,c){var d=mi.get();d.i=a;d.h=b;d.context=c;return d}
function oi(a){return new ji(function(b,c){c(a)})}
ji.prototype.then=function(a,b,c){return pi(this,Wh(typeof a==="function"?a:null),Wh(typeof b==="function"?b:null),c)};
ji.prototype.$goog_Thenable=!0;function qi(a,b,c,d){ri(a,ni(b||hi,c||null,d))}
r=ji.prototype;r.finally=function(a){var b=this;a=Wh(a);return new Promise(function(c,d){qi(b,function(e){a();c(e)},function(e){a();
d(e)})})};
r.Dc=function(a,b){return pi(this,null,Wh(a),b)};
r.catch=ji.prototype.Dc;r.cancel=function(a){if(this.X==0){var b=new si(a);ei(function(){ti(this,b)},this)}};
function ti(a,b){if(a.X==0)if(a.parent_){var c=a.parent_;if(c.Sa){for(var d=0,e=null,f=null,g=c.Sa;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&d>1)));g=g.next)e||(f=g);e&&(c.X==0&&d==1?ti(c,b):(f?(d=f,d.next==c.ub&&(c.ub=d),d.next=d.next.next):ui(c),vi(c,e,3,b)))}a.parent_=null}else ki(a,3,b)}
function ri(a,b){a.Sa||a.X!=2&&a.X!=3||wi(a);a.ub?a.ub.next=b:a.Sa=b;a.ub=b}
function pi(a,b,c,d){var e=ni(null,null,null);e.child=new ji(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);k===void 0&&h instanceof si?g(h):f(k)}catch(l){g(l)}}:g});
e.child.parent_=a;ri(a,e);return e.child}
r.xf=function(a){this.X=0;ki(this,2,a)};
r.yf=function(a){this.X=0;ki(this,3,a)};
function ki(a,b,c){if(a.X==0){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.X=1;a:{var d=c,e=a.xf,f=a.yf;if(d instanceof ji){qi(d,e,f,a);var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Ra(d))try{var k=d.then;if(typeof k==="function"){xi(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.ab=c,a.X=b,a.parent_=null,wi(a),b!=3||c instanceof si||yi(a,c))}}
function xi(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function wi(a){a.Ic||(a.Ic=!0,ei(a.qe,a))}
function ui(a){var b=null;a.Sa&&(b=a.Sa,a.Sa=b.next,b.next=null);a.Sa||(a.ub=null);return b}
r.qe=function(){for(var a;a=ui(this);)vi(this,a,this.X,this.ab);this.Ic=!1};
function vi(a,b,c,d){if(c==3&&b.h&&!b.j)for(;a&&a.nc;a=a.parent_)a.nc=!1;if(b.child)b.child.parent_=null,zi(b,c,d);else try{b.j?b.i.call(b.context):zi(b,c,d)}catch(e){Ai.call(null,e)}Yh(mi,b)}
function zi(a,b,c){b==2?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function yi(a,b){a.nc=!0;ei(function(){a.nc&&Ai.call(null,b)})}
var Ai=Qc;function si(a){cb.call(this,a)}
bb(si,cb);si.prototype.name="cancel";function Bi(a,b){Th.call(this);this.j=a||1;this.h=b||D;this.o=Xa(this.tf,this);this.u=$a()}
bb(Bi,Th);r=Bi.prototype;r.enabled=!1;r.Ea=null;r.setInterval=function(a){this.j=a;this.Ea&&this.enabled?(this.stop(),this.start()):this.Ea&&this.stop()};
r.tf=function(){if(this.enabled){var a=$a()-this.u;a>0&&a<this.j*.8?this.Ea=this.h.setTimeout(this.o,this.j-a):(this.Ea&&(this.h.clearTimeout(this.Ea),this.Ea=null),Uh(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
r.start=function(){this.enabled=!0;this.Ea||(this.Ea=this.h.setTimeout(this.o,this.j),this.u=$a())};
r.stop=function(){this.enabled=!1;this.Ea&&(this.h.clearTimeout(this.Ea),this.Ea=null)};
r.ba=function(){Bi.Aa.ba.call(this);this.stop();delete this.h};function Ci(a){H.call(this);this.G=a;this.j=0;this.o=100;this.u=!1;this.i=new Map;this.D=new Set;this.flushInterval=3E4;this.h=new Bi(this.flushInterval);this.h.listen("tick",this.Yb,!1,this);uc(this,this.h)}
w(Ci,H);r=Ci.prototype;r.sendIsolatedPayload=function(a){this.u=a;this.o=1};
function Di(a){a.h.enabled||a.h.start();a.j++;a.j>=a.o&&a.Yb()}
r.Yb=function(){var a=this.i.values();a=[].concat(A(a)).filter(function(b){return b.h.size});
a.length&&this.G.flush(a,this.u);Ei(a);this.j=0;this.h.enabled&&this.h.stop()};
r.Kb=function(a){var b=C.apply(1,arguments);this.i.has(a)||this.i.set(a,new th(a,b))};
r.Gc=function(a){var b=C.apply(1,arguments);this.i.has(a)||this.i.set(a,new uh(a,b))};
function Fi(a,b){return a.D.has(b)?void 0:a.i.get(b)}
r.Ib=function(a){this.Vd(a,1,C.apply(1,arguments))};
r.Vd=function(a,b){var c=C.apply(2,arguments),d=Fi(this,a);d&&d instanceof th&&(d.j(b,c),Di(this))};
r.record=function(a,b){var c=C.apply(2,arguments),d=Fi(this,a);d&&d instanceof uh&&(d.record(b,c),Di(this))};
function Ei(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Gi(){}
Gi.prototype.serialize=function(a){var b=[];Hi(this,a,b);return b.join("")};
function Hi(a,b,c){if(b==null)c.push("null");else{if(typeof b=="object"){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Hi(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],typeof f!="function"&&(c.push(e),Ii(d,c),c.push(":"),Hi(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Ii(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Ji={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Ki=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Ii(a,b){b.push('"',a.replace(Ki,function(c){var d=Ji[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Ji[c]=d);return d}),'"')}
;function Li(){Th.call(this);this.headers=new Map;this.h=!1;this.J=null;this.o=this.Y="";this.j=this.U=this.D=this.P=!1;this.G=0;this.u=null;this.oa="";this.ha=!1}
bb(Li,Th);var Mi=/^https?$/i,Ni=["POST","PUT"],Oi=[];function Pi(a,b,c,d,e,f,g){var h=new Li;Oi.push(h);b&&h.listen("complete",b);Ph(h,"ready",h.ee);f&&(h.G=Math.max(0,f));g&&(h.ha=g);h.send(a,c,d,e)}
r=Li.prototype;r.ee=function(){this.dispose();Sb(Oi,this)};
r.send=function(a,b,c,d){if(this.J)throw Error("[goog.net.XhrIo] Object is active with another request="+this.Y+"; newUri="+a);b=b?b.toUpperCase():"GET";this.Y=a;this.o="";this.P=!1;this.h=!0;this.J=new XMLHttpRequest;this.J.onreadystatechange=Wh(Xa(this.Bd,this));try{this.getStatus(),this.U=!0,this.J.open(b,String(a),!0),this.U=!1}catch(g){this.getStatus();Qi(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,d[e]);else if(typeof d.keys===
"function"&&typeof d.get==="function"){e=y(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=D.FormData&&a instanceof D.FormData;!(Mb(Ni,b)>=0)||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=y(c);for(d=b.next();!d.done;d=b.next())c=y(d.value),d=c.next().value,c=c.next().value,this.J.setRequestHeader(d,c);this.oa&&(this.J.responseType=this.oa);"withCredentials"in this.J&&this.J.withCredentials!==this.ha&&(this.J.withCredentials=this.ha);try{this.u&&(clearTimeout(this.u),this.u=null),this.G>0&&(this.getStatus(),this.u=setTimeout(this.wf.bind(this),this.G)),
this.getStatus(),this.D=!0,this.J.send(a),this.D=!1}catch(g){this.getStatus(),Qi(this,g)}};
r.wf=function(){typeof Ka!="undefined"&&this.J&&(this.o="Timed out after "+this.G+"ms, aborting",this.getStatus(),Uh(this,"timeout"),this.abort(8))};
function Qi(a,b){a.h=!1;a.J&&(a.j=!0,a.J.abort(),a.j=!1);a.o=b;Ri(a);Si(a)}
function Ri(a){a.P||(a.P=!0,Uh(a,"complete"),Uh(a,"error"))}
r.abort=function(){this.J&&this.h&&(this.getStatus(),this.h=!1,this.j=!0,this.J.abort(),this.j=!1,Uh(this,"complete"),Uh(this,"abort"),Si(this))};
r.ba=function(){this.J&&(this.h&&(this.h=!1,this.j=!0,this.J.abort(),this.j=!1),Si(this,!0));Li.Aa.ba.call(this)};
r.Bd=function(){this.ea||(this.U||this.D||this.j?Ti(this):this.Ne())};
r.Ne=function(){Ti(this)};
function Ti(a){if(a.h&&typeof Ka!="undefined")if(a.D&&(a.J?a.J.readyState:0)==4)setTimeout(a.Bd.bind(a),0);else if(Uh(a,"readystatechange"),a.isComplete()){a.getStatus();a.h=!1;try{if(Ui(a))Uh(a,"complete"),Uh(a,"success");else{try{var b=(a.J?a.J.readyState:0)>2?a.J.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";Ri(a)}}finally{Si(a)}}}
function Si(a,b){if(a.J){a.u&&(clearTimeout(a.u),a.u=null);var c=a.J;a.J=null;b||Uh(a,"ready");try{c.onreadystatechange=null}catch(d){}}}
r.isActive=function(){return!!this.J};
r.isComplete=function(){return(this.J?this.J.readyState:0)==4};
function Ui(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=b===0)a=bc(1,String(a.Y)),!a&&D.self&&D.self.location&&(a=D.self.location.protocol.slice(0,-1)),b=!Mi.test(a?a.toLowerCase():"");c=b}return c}
r.getStatus=function(){try{return(this.J?this.J.readyState:0)>2?this.J.status:-1}catch(a){return-1}};
r.getLastError=function(){return typeof this.o==="string"?this.o:String(this.o)};function Vi(){}
Vi.prototype.send=function(a,b,c){b=b===void 0?function(){}:b;
c=c===void 0?function(){}:c;
Pi(a.url,function(d){d=d.target;if(Ui(d)){try{var e=d.J?d.J.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Bc,a.timeoutMillis,a.withCredentials)};
Vi.prototype.lc=function(){return 1};function Wi(a,b){this.logger=a;this.event=b;this.startTime=Xi()}
Wi.prototype.done=function(){this.logger.Sb(this.event,Xi()-this.startTime)};
function Yi(){Fc.apply(this,arguments)}
w(Yi,Fc);function Zi(a,b){var c=Xi();b=b();a.Sb("n",Xi()-c);return b}
function $i(){Yi.apply(this,arguments)}
w($i,Yi);r=$i.prototype;r.Oc=function(){};
r.Bb=function(){};
r.Sb=function(){};
r.Ha=function(){};
r.Ac=function(){};
r.Nd=function(){};
function aj(a){return{rf:new Ic(a),errorCount:new Mc(a),eventCount:new Kc(a),pe:new Lc(a),Zh:new Jc(a),bi:new Nc(a),uh:new Oc(a),ai:new Pc(a)}}
function bj(a,b,c,d){a=mh(kh(jh(new ih(1828,"0"),a),new Vi));b.length&&lh(a,Mf(new Lf,b));d!==void 0&&(a.Ua=d);var e=new oh(1828,"","",!1,"",nh(a));uc(e,a);var f=new Ci({flush:function(g){try{e.flush(g)}catch(h){c(h)}}});
f.addOnDisposeCallback(function(){setTimeout(function(){try{f.Yb()}finally{e.dispose()}})});
f.o=1E5;f.flushInterval=3E4;f.h.setInterval(3E4);return f}
function cj(a,b){H.call(this);var c=this;this.callback=a;this.i=b;this.h=-b;this.addOnDisposeCallback(function(){return void clearTimeout(c.timer)})}
w(cj,H);function dj(a){if(a.timer===void 0){var b=Math.max(0,a.h+a.i-Xi());a.timer=setTimeout(function(){try{a.callback()}finally{a.h=Xi(),a.timer=void 0}},b)}}
function ej(a,b,c){Yi.call(this);this.metrics=a;this.Da=b;this.ob=c}
w(ej,Yi);ej.prototype.Oc=function(a){this.metrics.rf.record(a,this.Da)};
ej.prototype.Bb=function(a){this.metrics.eventCount.h(a,this.Da)};
ej.prototype.Sb=function(a,b){this.metrics.pe.record(b,a,this.ob,this.Da)};
ej.prototype.Ha=function(a){this.metrics.errorCount.h(a,this.ob,this.Da)};
function fj(a,b){b=b===void 0?[]:b;var c={Da:a.Da||"_",ob:a.ob||"",kc:a.kc||[],sc:a.sc|0,Ua:a.Ua,uc:a.uc||function(){},
Hb:a.Hb||function(e,f){return bj(e,f,c.uc,c.Ua)}};
b=c.Hb("47",c.kc.concat(b));ej.call(this,aj(b),c.Da,c.ob);var d=this;this.options=c;this.service=b;this.i=!a.Hb;this.h=new cj(function(){return void d.service.Yb()},c.sc);
this.addOnDisposeCallback(function(){d.h.dispose();d.i&&d.service.dispose()})}
w(fj,ej);fj.prototype.Nd=function(a){var b=this;this.h.dispose();this.i&&this.service.dispose();this.service=this.options.Hb("47",this.options.kc.concat(a));this.h=new cj(function(){return void b.service.Yb()},this.options.sc);
this.metrics=aj(this.service)};
fj.prototype.Ac=function(){dj(this.h)};
function Xi(){var a,b,c;return(c=(a=globalThis.performance)==null?void 0:(b=a.now)==null?void 0:b.call(a))!=null?c:Date.now()}
;function gj(a){this.F=L(a)}
w(gj,M);function hj(a){this.F=L(a)}
w(hj,M);function ij(a){this.F=L(a,0,"bfkj")}
w(ij,M);var jj=function(a){return $d(function(b){return b instanceof a&&!((b.F[K]|0)&2)})}(ij);function Bc(a){this.F=L(a)}
w(Bc,M);function kj(a){this.F=L(a)}
w(kj,M);var lj=Kf(kj);function mj(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function nj(a,b,c){if(a.disable)return new $i;b=b?zc(b):[];if(c)return c.Nd(b),c.share();a={Da:a.Da,ob:a.ob,kc:a.Ah,sc:a.Kh,Ua:a.Ua,uc:a.uc,Hb:a.Hb};c=b;c=c===void 0?[]:c;return new fj(a,c)}
function oj(a){function b(v,x,z,G){Promise.resolve().then(function(){k.done();h.Ac();h.dispose();g.resolve({Zd:v,qf:x,Re:z,wh:G})})}
function c(v,x,z,G){if(!d.logger.ea){var J="k";x?J="h":z&&(J="u");J!=="k"?G!==0&&(d.logger.Bb(J),d.logger.Sb(J,v)):d.i<=0?(d.logger.Bb(J),d.logger.Sb(J,v),d.i=Math.floor(Math.random()*200)):d.i--}}
H.call(this);var d=this;this.i=Math.floor(Math.random()*200);this.h=new kj;if("challenge"in a&&jj(a.challenge)){var e=Cf(a.challenge,4);var f=Cf(a.challenge,5);Cf(a.challenge,7)&&(this.h=lj(Cf(a.challenge,7)))}else e=a.program,f=a.globalName;this.addOnDisposeCallback(function(){var v,x,z;return B(function(G){if(G.h==1)return G.yield(d.j,2);v=G.i;x=v.qf;(z=x)==null||z();G.h=0})});
this.logger=nj(a.zd||{},this.h,a.xh);uc(this,this.logger);var g=new mj;this.j=g.promise;this.logger.Bb("t");var h=this.logger.share(),k=new Wi(h,"t");if(!D[f])throw this.logger.Ha(25),Error("EGOU");if(!D[f].a)throw this.logger.Ha(26),Error("ELIU");try{var l=D[f].a;f=[];for(var m=[],n=zc(this.h),p=0;p<n.length;p++)f.push(n[p]),m.push(1);var t=Dc(this.h);for(n=0;n<t.length;n++)f.push(t[n]),m.push(2);this.u=y(l(e,b,!0,a.Yh,c,[f,m],Cf(this.h,5))).next().value;this.Zc=g.promise.then(function(){})}catch(v){throw this.logger.Ha(28),
v;
}}
w(oj,H);oj.prototype.snapshot=function(a){if(this.ea)throw Error("Already disposed");this.logger.Bb("n");var b=this.logger.share();return this.j.then(function(c){var d=c.Zd;return new Promise(function(e){var f=new Wi(b,"n");d(function(g){f.done();b.Oc(g.length);b.Ac();b.dispose();e(g)},[a.vb,
a.cd,a.Bf,a.dd])})})};
oj.prototype.ed=function(a){var b=this;if(this.ea)throw Error("Already disposed");this.logger.Bb("n");var c=Zi(this.logger,function(){return b.u([a.vb,a.cd,a.Bf,a.dd])});
this.logger.Oc(c.length);this.logger.Ac();return c};
oj.prototype.o=function(a){this.j.then(function(b){var c;(c=b.Re)==null||c(a)})};function pj(a){if(!a)return null;a=Re(mf(a,4));return a===null||a===void 0?null:jb(a)}
;function qj(){this.promises={};this.h=null}
function rj(){qj.instance||(qj.instance=new qj);return qj.instance}
function sj(a,b){return tj(a,yf(b,gj,1),yf(b,hj,2),Cf(b,3))}
function tj(a,b,c,d){if(!b&&!c)return Promise.resolve();if(!d)return uj(b,c);var e;(e=a.promises)[d]||(e[d]=new Promise(function(f,g){uj(b,c).then(function(){a.h=d;f()},function(h){delete a.promises[d];
g(h)})}));
return a.promises[d]}
function uj(a,b){return b?vj(b):a?wj(a):Promise.resolve()}
function vj(a){return new Promise(function(b,c){var d=yg("SCRIPT"),e=pj(a);Fb(d,e);d.onload=function(){zg(d);b()};
d.onerror=function(){zg(d);c(Error("EWLS"))};
(document.getElementsByTagName("HEAD")[0]||document.documentElement).appendChild(d)})}
function wj(a){return new Promise(function(b){var c=yg("SCRIPT");if(a){var d=Re(mf(a,6));d=d===null||d===void 0?null:Cb(d)}else d=null;c.textContent=Db(d);Eb(c);(document.getElementsByTagName("HEAD")[0]||document.documentElement).appendChild(c);zg(c);b()})}
;var xj=window;function yj(a){var b=zj;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Aj(){var a=[];yj(function(b){a.push(b)});
return a}
var zj={Cf:"allow-forms",Df:"allow-modals",Ef:"allow-orientation-lock",Ff:"allow-pointer-lock",Gf:"allow-popups",Hf:"allow-popups-to-escape-sandbox",If:"allow-presentation",Jf:"allow-same-origin",Kf:"allow-scripts",Lf:"allow-top-navigation",Mf:"allow-top-navigation-by-user-activation"},Bj=ii(function(){return Aj()});
function Cj(){var a=Dj(),b={};Nb(Bj(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Dj(){var a=a===void 0?document:a;return a.createElement("iframe")}
;function Ej(a){typeof a=="number"&&(a=Math.round(a)+"px");return a}
;var Fj=(new Date).getTime();function Gj(a){Th.call(this);var b=this;this.D=this.j=0;this.Ca=a!=null?a:{pa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.h=(d=(c=window.navigator)==null?void 0:c.onLine)!=null?d:!0;this.o=function(){return B(function(e){return e.yield(Hj(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.D||Ij(this)}
w(Gj,Th);function Jj(){var a=Kj;Gj.instance||(Gj.instance=new Gj(a));return Gj.instance}
Gj.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Ca.qa(this.D);delete Gj.instance};
Gj.prototype.ta=function(){return this.h};
function Ij(a){a.D=a.Ca.pa(function(){var b;return B(function(c){if(c.h==1)return a.h?((b=window.navigator)==null?0:b.onLine)?c.A(3):c.yield(Hj(a),3):c.yield(Hj(a),3);Ij(a);c.h=0})},3E4)}
function Hj(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f,g;return B(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=(e=d)==null?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.j=a.Ca.pa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.P=[h.j];h.M=0;h.o=0;a.u=void 0;a.j&&(a.Ca.qa(a.j),a.j=0);g!==a.h&&(a.h=g,a.h?Uh(a,"networkstatus-online"):Uh(a,"networkstatus-offline"));c(g);Ba(h);break;case 2:Aa(h),g=!1,h.A(3)}})})}
;function Lj(){this.data=[];this.h=-1}
Lj.prototype.set=function(a,b){b=b===void 0?!0:b;0<=a&&a<52&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Lj.prototype.get=function(a){return!!this.data[a]};
function Mj(a){a.h===-1&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function Nj(){this.blockSize=-1}
;function Oj(){this.blockSize=-1;this.blockSize=64;this.h=[];this.u=[];this.M=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.o=this.i=0;this.reset()}
bb(Oj,Nj);Oj.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.o=this.i=0};
function Pj(a,b,c){c||(c=0);var d=a.M;if(typeof b==="string")for(var e=0;e<16;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;e<16;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(b=16;b<80;b++)c=d[b-3]^d[b-8]^d[b-14]^d[b-16],d[b]=(c<<1|c>>>31)&4294967295;b=a.h[0];c=a.h[1];e=a.h[2];for(var f=a.h[3],g=a.h[4],h,k,l=0;l<80;l++)l<40?l<20?(h=f^c&(e^f),k=1518500249):(h=c^e^f,k=1859775393):l<60?(h=c&e|f&(c|e),k=2400959708):(h=c^e^f,k=3395469782),
h=(b<<5|b>>>27)+h+g+k+d[l]&4294967295,g=f,f=e,e=(c<<30|c>>>2)&4294967295,c=b,b=h;a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+e&4294967295;a.h[3]=a.h[3]+f&4294967295;a.h[4]=a.h[4]+g&4294967295}
Oj.prototype.update=function(a,b){if(a!=null){b===void 0&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.u,f=this.i;d<b;){if(f==0)for(;d<=c;)Pj(this,a,d),d+=this.blockSize;if(typeof a==="string")for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Pj(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Pj(this,e);f=0;break}}this.i=f;this.o+=b}};
Oj.prototype.digest=function(){var a=[],b=this.o*8;this.i<56?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;c>=56;c--)this.u[c]=b&255,b/=256;Pj(this,this.u);for(c=b=0;c<5;c++)for(var d=24;d>=0;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Qj(a){return typeof a.className=="string"?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Rj(a,b){typeof a.className=="string"?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Sj(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Qj(a).match(/\S+/g)||[],b=Mb(a,b)>=0);return b}
function Tj(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Sj(a,"inverted-hdpi")&&Rj(a,Array.prototype.filter.call(a.classList?a.classList:Qj(a).match(/\S+/g)||[],function(b){return b!="inverted-hdpi"}).join(" "))}
;function Uj(){}
Uj.prototype.next=function(){return Vj};
var Vj={done:!0,value:void 0};Uj.prototype.sb=function(){return this};function Wj(a){if(a instanceof Xj||a instanceof Yj||a instanceof Zj)return a;if(typeof a.next=="function")return new Xj(function(){return a});
if(typeof a[Symbol.iterator]=="function")return new Xj(function(){return a[Symbol.iterator]()});
if(typeof a.sb=="function")return new Xj(function(){return a.sb()});
throw Error("Not an iterator or iterable.");}
function Xj(a){this.h=a}
Xj.prototype.sb=function(){return new Yj(this.h())};
Xj.prototype[Symbol.iterator]=function(){return new Zj(this.h())};
Xj.prototype.i=function(){return new Zj(this.h())};
function Yj(a){this.h=a}
w(Yj,Uj);Yj.prototype.next=function(){return this.h.next()};
Yj.prototype[Symbol.iterator]=function(){return new Zj(this.h)};
Yj.prototype.i=function(){return new Zj(this.h)};
function Zj(a){Xj.call(this,function(){return a});
this.j=a}
w(Zj,Xj);Zj.prototype.next=function(){return this.j.next()};function N(a){H.call(this);this.u=1;this.j=[];this.o=0;this.h=[];this.i={};this.D=!!a}
bb(N,H);r=N.prototype;r.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.u;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.u=e+3;d.push(e);return e};
r.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.ac(a)}return!1};
r.ac=function(a){var b=this.h[a];if(b){var c=this.i[b];this.o!=0?(this.j.push(a),this.h[a+1]=function(){}):(c&&Sb(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
r.qb=function(a,b){var c=this.i[a];if(c){var d=Array(arguments.length-1),e=arguments.length,f;for(f=1;f<e;f++)d[f-1]=arguments[f];if(this.D)for(f=0;f<c.length;f++)e=c[f],ak(this.h[e+1],this.h[e+2],d);else{this.o++;try{for(f=0,e=c.length;f<e&&!this.ea;f++){var g=c[f];this.h[g+1].apply(this.h[g+2],d)}}finally{if(this.o--,this.j.length>0&&this.o==0)for(;c=this.j.pop();)this.ac(c)}}return f!=0}return!1};
function ak(a,b,c){ei(function(){a.apply(b,c)})}
r.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.ac,this),delete this.i[a])}else this.h.length=0,this.i={}};
r.ba=function(){N.Aa.ba.call(this);this.clear();this.j.length=0};function bk(a){this.h=a}
bk.prototype.set=function(a,b){b===void 0?this.h.remove(a):this.h.set(a,(new Gi).serialize(b))};
bk.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(b!==null)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
bk.prototype.remove=function(a){this.h.remove(a)};function ck(a){this.h=a}
bb(ck,bk);function dk(a){this.data=a}
function ek(a){return a===void 0||a instanceof dk?a:new dk(a)}
ck.prototype.set=function(a,b){ck.Aa.set.call(this,a,ek(b))};
ck.prototype.i=function(a){a=ck.Aa.get.call(this,a);if(a===void 0||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
ck.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,a===void 0)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function fk(a){this.h=a}
bb(fk,ck);fk.prototype.set=function(a,b,c){if(b=ek(b)){if(c){if(c<$a()){fk.prototype.remove.call(this,a);return}b.expiration=c}b.creation=$a()}fk.Aa.set.call(this,a,b)};
fk.prototype.i=function(a){var b=fk.Aa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<$a()||c&&c>$a())fk.prototype.remove.call(this,a);else return b}};function gk(){}
;function hk(){}
bb(hk,gk);hk.prototype[Symbol.iterator]=function(){return Wj(this.sb(!0)).i()};
hk.prototype.clear=function(){var a=Array.from(this);a=y(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function ik(a){this.h=a;this.i=null}
bb(ik,hk);r=ik.prototype;r.isAvailable=function(){var a=this.h;if(a)try{a.setItem("__sak","1");a.removeItem("__sak");var b=!0}catch(c){b=c instanceof DOMException&&(c.name==="QuotaExceededError"||c.code===22||c.code===1014||c.name==="NS_ERROR_DOM_QUOTA_REACHED")&&a&&a.length!==0}else b=!1;return this.i=b};
r.set=function(a,b){jk(this);try{this.h.setItem(a,b)}catch(c){if(this.h.length==0)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
r.get=function(a){jk(this);a=this.h.getItem(a);if(typeof a!=="string"&&a!==null)throw"Storage mechanism: Invalid value was encountered";return a};
r.remove=function(a){jk(this);this.h.removeItem(a)};
r.sb=function(a){jk(this);var b=0,c=this.h,d=new Uj;d.next=function(){if(b>=c.length)return Vj;var e=c.key(b++);if(a)return{value:e,done:!1};e=c.getItem(e);if(typeof e!=="string")throw"Storage mechanism: Invalid value was encountered";return{value:e,done:!1}};
return d};
r.clear=function(){jk(this);this.h.clear()};
r.key=function(a){jk(this);return this.h.key(a)};
function jk(a){if(a.h==null)throw Error("Storage mechanism: Storage unavailable");var b;((b=a.i)!=null?b:a.isAvailable())||Qc(Error("Storage mechanism: Storage unavailable"))}
;function kk(){var a=null;try{a=D.localStorage||null}catch(b){}ik.call(this,a)}
bb(kk,ik);function lk(a,b){this.i=a;this.h=b+"::"}
bb(lk,hk);lk.prototype.set=function(a,b){this.i.set(this.h+a,b)};
lk.prototype.get=function(a){return this.i.get(this.h+a)};
lk.prototype.remove=function(a){this.i.remove(this.h+a)};
lk.prototype.sb=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Uj;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return{value:a?e.slice(c.h.length):c.i.get(e),done:!1}};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var O={},mk=typeof Uint8Array!=="undefined"&&typeof Uint16Array!=="undefined"&&typeof Int32Array!=="undefined";O.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if(typeof c!=="object")throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
O.bd=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var nk={tb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
sd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},ok={tb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
sd:function(a){return[].concat.apply([],a)}};
O.pf=function(){mk?(O.pb=Uint8Array,O.Ja=Uint16Array,O.Ud=Int32Array,O.assign(O,nk)):(O.pb=Array,O.Ja=Array,O.Ud=Array,O.assign(O,ok))};
O.pf();var pk=!0;try{new Uint8Array(1)}catch(a){pk=!1}
function qk(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if((f&64512)===55296&&b+1<d){var g=a.charCodeAt(b+1);(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=f<128?1:f<2048?2:f<65536?3:4}var h=new O.pb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),(f&64512)===55296&&b+1<d&&(g=a.charCodeAt(b+1),(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)),f<128?h[c++]=f:(f<2048?h[c++]=192|f>>>6:(f<65536?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var rk={};rk=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;c!==0;){f=c>2E3?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var sk={},tk,uk=[],vk=0;vk<256;vk++){tk=vk;for(var wk=0;wk<8;wk++)tk=tk&1?3988292384^tk>>>1:tk>>>1;uk[vk]=tk}sk=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^uk[(a^b[d])&255];return a^-1};var xk={};xk={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function yk(a){for(var b=a.length;--b>=0;)a[b]=0}
var zk=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],Ak=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],Bk=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],Ck=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],Dk=Array(576);yk(Dk);var Ek=Array(60);yk(Ek);var Fk=Array(512);yk(Fk);var Gk=Array(256);yk(Gk);var Hk=Array(29);yk(Hk);var Ik=Array(30);yk(Ik);function Jk(a,b,c,d,e){this.Kd=a;this.te=b;this.se=c;this.le=d;this.Le=e;this.vd=a&&a.length}
var Kk,Lk,Mk;function Nk(a,b){this.rd=a;this.Db=0;this.bb=b}
function Ok(a,b){a.aa[a.pending++]=b&255;a.aa[a.pending++]=b>>>8&255}
function Pk(a,b,c){a.ia>16-c?(a.na|=b<<a.ia&65535,Ok(a,a.na),a.na=b>>16-a.ia,a.ia+=c-16):(a.na|=b<<a.ia&65535,a.ia+=c)}
function Qk(a,b,c){Pk(a,c[b*2],c[b*2+1])}
function Rk(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(--b>0);return c>>>1}
function Sk(a,b,c){var d=Array(16),e=0,f;for(f=1;f<=15;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[c*2+1],e!==0&&(a[c*2]=Rk(d[e]++,e))}
function Tk(a){var b;for(b=0;b<286;b++)a.ra[b*2]=0;for(b=0;b<30;b++)a.fb[b*2]=0;for(b=0;b<19;b++)a.ja[b*2]=0;a.ra[512]=1;a.Oa=a.Gb=0;a.ya=a.matches=0}
function Uk(a){a.ia>8?Ok(a,a.na):a.ia>0&&(a.aa[a.pending++]=a.na);a.na=0;a.ia=0}
function Vk(a,b,c){Uk(a);Ok(a,c);Ok(a,~c);O.tb(a.aa,a.window,b,c,a.pending);a.pending+=c}
function Wk(a,b,c,d){var e=b*2,f=c*2;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Xk(a,b,c){for(var d=a.da[c],e=c<<1;e<=a.Na;){e<a.Na&&Wk(b,a.da[e+1],a.da[e],a.depth)&&e++;if(Wk(b,d,a.da[e],a.depth))break;a.da[c]=a.da[e];c=e;e<<=1}a.da[c]=d}
function Yk(a,b,c){var d=0;if(a.ya!==0){do{var e=a.aa[a.Nb+d*2]<<8|a.aa[a.Nb+d*2+1];var f=a.aa[a.Nc+d];d++;if(e===0)Qk(a,f,b);else{var g=Gk[f];Qk(a,g+256+1,b);var h=zk[g];h!==0&&(f-=Hk[g],Pk(a,f,h));e--;g=e<256?Fk[e]:Fk[256+(e>>>7)];Qk(a,g,c);h=Ak[g];h!==0&&(e-=Ik[g],Pk(a,e,h))}}while(d<a.ya)}Qk(a,256,b)}
function Zk(a,b){var c=b.rd,d=b.bb.Kd,e=b.bb.vd,f=b.bb.le,g,h=-1;a.Na=0;a.yb=573;for(g=0;g<f;g++)c[g*2]!==0?(a.da[++a.Na]=h=g,a.depth[g]=0):c[g*2+1]=0;for(;a.Na<2;){var k=a.da[++a.Na]=h<2?++h:0;c[k*2]=1;a.depth[k]=0;a.Oa--;e&&(a.Gb-=d[k*2+1])}b.Db=h;for(g=a.Na>>1;g>=1;g--)Xk(a,c,g);k=f;do g=a.da[1],a.da[1]=a.da[a.Na--],Xk(a,c,1),d=a.da[1],a.da[--a.yb]=g,a.da[--a.yb]=d,c[k*2]=c[g*2]+c[d*2],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[g*2+1]=c[d*2+1]=k,a.da[1]=k++,Xk(a,c,1);while(a.Na>=
2);a.da[--a.yb]=a.da[1];g=b.rd;k=b.Db;d=b.bb.Kd;e=b.bb.vd;f=b.bb.te;var l=b.bb.se,m=b.bb.Le,n,p=0;for(n=0;n<=15;n++)a.Ka[n]=0;g[a.da[a.yb]*2+1]=0;for(b=a.yb+1;b<573;b++){var t=a.da[b];n=g[g[t*2+1]*2+1]+1;n>m&&(n=m,p++);g[t*2+1]=n;if(!(t>k)){a.Ka[n]++;var v=0;t>=l&&(v=f[t-l]);var x=g[t*2];a.Oa+=x*(n+v);e&&(a.Gb+=x*(d[t*2+1]+v))}}if(p!==0){do{for(n=m-1;a.Ka[n]===0;)n--;a.Ka[n]--;a.Ka[n+1]+=2;a.Ka[m]--;p-=2}while(p>0);for(n=m;n!==0;n--)for(t=a.Ka[n];t!==0;)d=a.da[--b],d>k||(g[d*2+1]!==n&&(a.Oa+=(n-g[d*
2+1])*g[d*2],g[d*2+1]=n),t--)}Sk(c,h,a.Ka)}
function $k(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);b[(c+1)*2+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];++g<h&&l===f||(g<k?a.ja[l*2]+=g:l!==0?(l!==e&&a.ja[l*2]++,a.ja[32]++):g<=10?a.ja[34]++:a.ja[36]++,g=0,e=l,f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function al(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];if(!(++g<h&&l===f)){if(g<k){do Qk(a,l,a.ja);while(--g!==0)}else l!==0?(l!==e&&(Qk(a,l,a.ja),g--),Qk(a,16,a.ja),Pk(a,g-3,2)):g<=10?(Qk(a,17,a.ja),Pk(a,g-3,3)):(Qk(a,18,a.ja),Pk(a,g-11,7));g=0;e=l;f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function bl(a){var b=4093624447,c;for(c=0;c<=31;c++,b>>>=1)if(b&1&&a.ra[c*2]!==0)return 0;if(a.ra[18]!==0||a.ra[20]!==0||a.ra[26]!==0)return 1;for(c=32;c<256;c++)if(a.ra[c*2]!==0)return 1;return 0}
var cl=!1;function dl(a,b,c){a.aa[a.Nb+a.ya*2]=b>>>8&255;a.aa[a.Nb+a.ya*2+1]=b&255;a.aa[a.Nc+a.ya]=c&255;a.ya++;b===0?a.ra[c*2]++:(a.matches++,b--,a.ra[(Gk[c]+256+1)*2]++,a.fb[(b<256?Fk[b]:Fk[256+(b>>>7)])*2]++);return a.ya===a.Rb-1}
;function el(a,b){a.msg=xk[b];return b}
function fl(a){for(var b=a.length;--b>=0;)a[b]=0}
function gl(a){var b=a.state,c=b.pending;c>a.S&&(c=a.S);c!==0&&(O.tb(a.output,b.aa,b.Ub,c,a.Eb),a.Eb+=c,b.Ub+=c,a.gd+=c,a.S-=c,b.pending-=c,b.pending===0&&(b.Ub=0))}
function hl(a,b){var c=a.va>=0?a.va:-1,d=a.v-a.va,e=0;if(a.level>0){a.K.Hc===2&&(a.K.Hc=bl(a));Zk(a,a.qc);Zk(a,a.ic);$k(a,a.ra,a.qc.Db);$k(a,a.fb,a.ic.Db);Zk(a,a.nd);for(e=18;e>=3&&a.ja[Ck[e]*2+1]===0;e--);a.Oa+=3*(e+1)+5+5+4;var f=a.Oa+3+7>>>3;var g=a.Gb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&c!==-1)Pk(a,b?1:0,3),Vk(a,c,d);else if(a.strategy===4||g===f)Pk(a,2+(b?1:0),3),Yk(a,Dk,Ek);else{Pk(a,4+(b?1:0),3);c=a.qc.Db+1;d=a.ic.Db+1;e+=1;Pk(a,c-257,5);Pk(a,d-1,5);Pk(a,e-4,4);for(f=0;f<e;f++)Pk(a,
a.ja[Ck[f]*2+1],3);al(a,a.ra,c-1);al(a,a.fb,d-1);Yk(a,a.ra,a.fb)}Tk(a);b&&Uk(a);a.va=a.v;gl(a.K)}
function P(a,b){a.aa[a.pending++]=b}
function il(a,b){a.aa[a.pending++]=b>>>8&255;a.aa[a.pending++]=b&255}
function jl(a,b){var c=a.yd,d=a.v,e=a.wa,f=a.Ad,g=a.v>a.la-262?a.v-(a.la-262):0,h=a.window,k=a.cb,l=a.Ia,m=a.v+258,n=h[d+e-1],p=h[d+e];a.wa>=a.ud&&(c>>=2);f>a.B&&(f=a.B);do{var t=b;if(h[t+e]===p&&h[t+e-1]===n&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<m;);t=258-(m-d);d=m-258;if(t>e){a.Cb=b;e=t;if(t>=f)break;n=h[d+e-1];p=h[d+e]}}}while((b=l[b&k])>g&&--c!==0);return e<=
a.B?e:a.B}
function kl(a){var b=a.la,c;do{var d=a.Sd-a.B-a.v;if(a.v>=b+(b-262)){O.tb(a.window,a.window,b,b,0);a.Cb-=b;a.v-=b;a.va-=b;var e=c=a.pc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ia[--e],a.Ia[e]=f>=b?f-b:0;while(--c);d+=b}if(a.K.ma===0)break;e=a.K;c=a.window;f=a.v+a.B;var g=e.ma;g>d&&(g=d);g===0?c=0:(e.ma-=g,O.tb(c,e.input,e.lb,g,f),e.state.wrap===1?e.I=rk(e.I,c,g,f):e.state.wrap===2&&(e.I=sk(e.I,c,g,f)),e.lb+=g,e.nb+=g,c=g);a.B+=c;if(a.B+a.sa>=3)for(d=a.v-a.sa,a.R=a.window[d],
a.R=(a.R<<a.Ma^a.window[d+1])&a.La;a.sa&&!(a.R=(a.R<<a.Ma^a.window[d+3-1])&a.La,a.Ia[d&a.cb]=a.head[a.R],a.head[a.R]=d,d++,a.sa--,a.B+a.sa<3););}while(a.B<262&&a.K.ma!==0)}
function ll(a,b){for(var c;;){if(a.B<262){kl(a);if(a.B<262&&b===0)return 1;if(a.B===0)break}c=0;a.B>=3&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,c=a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);c!==0&&a.v-c<=a.la-262&&(a.T=jl(a,c));if(a.T>=3)if(c=dl(a,a.v-a.Cb,a.T-3),a.B-=a.T,a.T<=a.Pc&&a.B>=3){a.T--;do a.v++,a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v;while(--a.T!==0);a.v++}else a.v+=a.T,a.T=0,a.R=a.window[a.v],a.R=(a.R<<a.Ma^a.window[a.v+1])&a.La;else c=dl(a,0,
a.window[a.v]),a.B--,a.v++;if(c&&(hl(a,!1),a.K.S===0))return 1}a.sa=a.v<2?a.v:2;return b===4?(hl(a,!0),a.K.S===0?3:4):a.ya&&(hl(a,!1),a.K.S===0)?1:2}
function ml(a,b){for(var c,d;;){if(a.B<262){kl(a);if(a.B<262&&b===0)return 1;if(a.B===0)break}c=0;a.B>=3&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,c=a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);a.wa=a.T;a.Dd=a.Cb;a.T=2;c!==0&&a.wa<a.Pc&&a.v-c<=a.la-262&&(a.T=jl(a,c),a.T<=5&&(a.strategy===1||a.T===3&&a.v-a.Cb>4096)&&(a.T=2));if(a.wa>=3&&a.T<=a.wa){d=a.v+a.B-3;c=dl(a,a.v-1-a.Dd,a.wa-3);a.B-=a.wa-1;a.wa-=2;do++a.v<=d&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);
while(--a.wa!==0);a.jb=0;a.T=2;a.v++;if(c&&(hl(a,!1),a.K.S===0))return 1}else if(a.jb){if((c=dl(a,0,a.window[a.v-1]))&&hl(a,!1),a.v++,a.B--,a.K.S===0)return 1}else a.jb=1,a.v++,a.B--}a.jb&&(dl(a,0,a.window[a.v-1]),a.jb=0);a.sa=a.v<2?a.v:2;return b===4?(hl(a,!0),a.K.S===0?3:4):a.ya&&(hl(a,!1),a.K.S===0)?1:2}
function nl(a,b){for(var c,d,e,f=a.window;;){if(a.B<=258){kl(a);if(a.B<=258&&b===0)return 1;if(a.B===0)break}a.T=0;if(a.B>=3&&a.v>0&&(d=a.v-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.v+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.T=258-(e-d);a.T>a.B&&(a.T=a.B)}a.T>=3?(c=dl(a,1,a.T-3),a.B-=a.T,a.v+=a.T,a.T=0):(c=dl(a,0,a.window[a.v]),a.B--,a.v++);if(c&&(hl(a,!1),a.K.S===0))return 1}a.sa=0;return b===4?(hl(a,!0),a.K.S===0?3:4):
a.ya&&(hl(a,!1),a.K.S===0)?1:2}
function ol(a,b){for(var c;;){if(a.B===0&&(kl(a),a.B===0)){if(b===0)return 1;break}a.T=0;c=dl(a,0,a.window[a.v]);a.B--;a.v++;if(c&&(hl(a,!1),a.K.S===0))return 1}a.sa=0;return b===4?(hl(a,!0),a.K.S===0?3:4):a.ya&&(hl(a,!1),a.K.S===0)?1:2}
function pl(a,b,c,d,e){this.ye=a;this.Ke=b;this.Me=c;this.Je=d;this.ue=e}
var ql;ql=[new pl(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(a.B<=1){kl(a);if(a.B===0&&b===0)return 1;if(a.B===0)break}a.v+=a.B;a.B=0;var d=a.va+c;if(a.v===0||a.v>=d)if(a.B=a.v-d,a.v=d,hl(a,!1),a.K.S===0)return 1;if(a.v-a.va>=a.la-262&&(hl(a,!1),a.K.S===0))return 1}a.sa=0;if(b===4)return hl(a,!0),a.K.S===0?3:4;a.v>a.va&&hl(a,!1);return 1}),
new pl(4,4,8,4,ll),new pl(4,5,16,8,ll),new pl(4,6,32,32,ll),new pl(4,4,16,16,ml),new pl(8,16,32,32,ml),new pl(8,16,128,128,ml),new pl(8,32,128,256,ml),new pl(32,128,258,1024,ml),new pl(32,258,258,4096,ml)];
function rl(){this.K=null;this.status=0;this.aa=null;this.wrap=this.pending=this.Ub=this.za=0;this.H=null;this.Ba=0;this.method=8;this.Ab=-1;this.cb=this.jd=this.la=0;this.window=null;this.Sd=0;this.head=this.Ia=null;this.Ad=this.ud=this.strategy=this.level=this.Pc=this.yd=this.wa=this.B=this.Cb=this.v=this.jb=this.Dd=this.T=this.va=this.Ma=this.La=this.Lc=this.pc=this.R=0;this.ra=new O.Ja(1146);this.fb=new O.Ja(122);this.ja=new O.Ja(78);fl(this.ra);fl(this.fb);fl(this.ja);this.nd=this.ic=this.qc=
null;this.Ka=new O.Ja(16);this.da=new O.Ja(573);fl(this.da);this.yb=this.Na=0;this.depth=new O.Ja(573);fl(this.depth);this.ia=this.na=this.sa=this.matches=this.Gb=this.Oa=this.Nb=this.ya=this.Rb=this.Nc=0}
function sl(a,b){if(!a||!a.state||b>5||b<0)return a?el(a,-2):-2;var c=a.state;if(!a.output||!a.input&&a.ma!==0||c.status===666&&b!==4)return el(a,a.S===0?-5:-2);c.K=a;var d=c.Ab;c.Ab=b;if(c.status===42)if(c.wrap===2)a.I=0,P(c,31),P(c,139),P(c,8),c.H?(P(c,(c.H.text?1:0)+(c.H.Va?2:0)+(c.H.extra?4:0)+(c.H.name?8:0)+(c.H.comment?16:0)),P(c,c.H.time&255),P(c,c.H.time>>8&255),P(c,c.H.time>>16&255),P(c,c.H.time>>24&255),P(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),P(c,c.H.os&255),c.H.extra&&c.H.extra.length&&
(P(c,c.H.extra.length&255),P(c,c.H.extra.length>>8&255)),c.H.Va&&(a.I=sk(a.I,c.aa,c.pending,0)),c.Ba=0,c.status=69):(P(c,0),P(c,0),P(c,0),P(c,0),P(c,0),P(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),P(c,3),c.status=113);else{var e=8+(c.jd-8<<4)<<8;e|=(c.strategy>=2||c.level<2?0:c.level<6?1:c.level===6?2:3)<<6;c.v!==0&&(e|=32);c.status=113;il(c,e+(31-e%31));c.v!==0&&(il(c,a.I>>>16),il(c,a.I&65535));a.I=1}if(c.status===69)if(c.H.extra){for(e=c.pending;c.Ba<(c.H.extra.length&65535)&&(c.pending!==c.za||
(c.H.Va&&c.pending>e&&(a.I=sk(a.I,c.aa,c.pending-e,e)),gl(a),e=c.pending,c.pending!==c.za));)P(c,c.H.extra[c.Ba]&255),c.Ba++;c.H.Va&&c.pending>e&&(a.I=sk(a.I,c.aa,c.pending-e,e));c.Ba===c.H.extra.length&&(c.Ba=0,c.status=73)}else c.status=73;if(c.status===73)if(c.H.name){e=c.pending;do{if(c.pending===c.za&&(c.H.Va&&c.pending>e&&(a.I=sk(a.I,c.aa,c.pending-e,e)),gl(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ba<c.H.name.length?c.H.name.charCodeAt(c.Ba++)&255:0;P(c,f)}while(f!==0);c.H.Va&&c.pending>
e&&(a.I=sk(a.I,c.aa,c.pending-e,e));f===0&&(c.Ba=0,c.status=91)}else c.status=91;if(c.status===91)if(c.H.comment){e=c.pending;do{if(c.pending===c.za&&(c.H.Va&&c.pending>e&&(a.I=sk(a.I,c.aa,c.pending-e,e)),gl(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ba<c.H.comment.length?c.H.comment.charCodeAt(c.Ba++)&255:0;P(c,f)}while(f!==0);c.H.Va&&c.pending>e&&(a.I=sk(a.I,c.aa,c.pending-e,e));f===0&&(c.status=103)}else c.status=103;c.status===103&&(c.H.Va?(c.pending+2>c.za&&gl(a),c.pending+2<=c.za&&(P(c,
a.I&255),P(c,a.I>>8&255),a.I=0,c.status=113)):c.status=113);if(c.pending!==0){if(gl(a),a.S===0)return c.Ab=-1,0}else if(a.ma===0&&(b<<1)-(b>4?9:0)<=(d<<1)-(d>4?9:0)&&b!==4)return el(a,-5);if(c.status===666&&a.ma!==0)return el(a,-5);if(a.ma!==0||c.B!==0||b!==0&&c.status!==666){d=c.strategy===2?ol(c,b):c.strategy===3?nl(c,b):ql[c.level].ue(c,b);if(d===3||d===4)c.status=666;if(d===1||d===3)return a.S===0&&(c.Ab=-1),0;if(d===2&&(b===1?(Pk(c,2,3),Qk(c,256,Dk),c.ia===16?(Ok(c,c.na),c.na=0,c.ia=0):c.ia>=
8&&(c.aa[c.pending++]=c.na&255,c.na>>=8,c.ia-=8)):b!==5&&(Pk(c,0,3),Vk(c,0,0),b===3&&(fl(c.head),c.B===0&&(c.v=0,c.va=0,c.sa=0))),gl(a),a.S===0))return c.Ab=-1,0}if(b!==4)return 0;if(c.wrap<=0)return 1;c.wrap===2?(P(c,a.I&255),P(c,a.I>>8&255),P(c,a.I>>16&255),P(c,a.I>>24&255),P(c,a.nb&255),P(c,a.nb>>8&255),P(c,a.nb>>16&255),P(c,a.nb>>24&255)):(il(c,a.I>>>16),il(c,a.I&65535));gl(a);c.wrap>0&&(c.wrap=-c.wrap);return c.pending!==0?0:1}
;var tl={};tl=function(){this.input=null;this.nb=this.ma=this.lb=0;this.output=null;this.gd=this.S=this.Eb=0;this.msg="";this.state=null;this.Hc=2;this.I=0};var ul=Object.prototype.toString;
function vl(a){if(!(this instanceof vl))return new vl(a);a=this.options=O.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&a.windowBits>0?a.windowBits=-a.windowBits:a.gzip&&a.windowBits>0&&a.windowBits<16&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.K=new tl;this.K.S=0;var b=this.K;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;c===-1&&(c=6);e<0?(h=0,e=-e):e>15&&(h=2,e-=16);if(f<1||f>
9||d!==8||e<8||e>15||c<0||c>9||g<0||g>4)b=el(b,-2);else{e===8&&(e=9);var k=new rl;b.state=k;k.K=b;k.wrap=h;k.H=null;k.jd=e;k.la=1<<k.jd;k.cb=k.la-1;k.Lc=f+7;k.pc=1<<k.Lc;k.La=k.pc-1;k.Ma=~~((k.Lc+3-1)/3);k.window=new O.pb(k.la*2);k.head=new O.Ja(k.pc);k.Ia=new O.Ja(k.la);k.Rb=1<<f+6;k.za=k.Rb*4;k.aa=new O.pb(k.za);k.Nb=1*k.Rb;k.Nc=3*k.Rb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.nb=b.gd=0;b.Hc=2;c=b.state;c.pending=0;c.Ub=0;c.wrap<0&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.I=c.wrap===2?
0:1;c.Ab=0;if(!cl){d=Array(16);for(f=g=0;f<28;f++)for(Hk[f]=g,e=0;e<1<<zk[f];e++)Gk[g++]=f;Gk[g-1]=f;for(f=g=0;f<16;f++)for(Ik[f]=g,e=0;e<1<<Ak[f];e++)Fk[g++]=f;for(g>>=7;f<30;f++)for(Ik[f]=g<<7,e=0;e<1<<Ak[f]-7;e++)Fk[256+g++]=f;for(e=0;e<=15;e++)d[e]=0;for(e=0;e<=143;)Dk[e*2+1]=8,e++,d[8]++;for(;e<=255;)Dk[e*2+1]=9,e++,d[9]++;for(;e<=279;)Dk[e*2+1]=7,e++,d[7]++;for(;e<=287;)Dk[e*2+1]=8,e++,d[8]++;Sk(Dk,287,d);for(e=0;e<30;e++)Ek[e*2+1]=5,Ek[e*2]=Rk(e,5);Kk=new Jk(Dk,zk,257,286,15);Lk=new Jk(Ek,
Ak,0,30,15);Mk=new Jk([],Bk,0,19,7);cl=!0}c.qc=new Nk(c.ra,Kk);c.ic=new Nk(c.fb,Lk);c.nd=new Nk(c.ja,Mk);c.na=0;c.ia=0;Tk(c);c=0}else c=el(b,-2);c===0&&(b=b.state,b.Sd=2*b.la,fl(b.head),b.Pc=ql[b.level].Ke,b.ud=ql[b.level].ye,b.Ad=ql[b.level].Me,b.yd=ql[b.level].Je,b.v=0,b.va=0,b.B=0,b.sa=0,b.T=b.wa=2,b.jb=0,b.R=0);b=c}}else b=-2;if(b!==0)throw Error(xk[b]);a.header&&(b=this.K)&&b.state&&b.state.wrap===2&&(b.state.H=a.header);if(a.dictionary){var l;typeof a.dictionary==="string"?l=qk(a.dictionary):
ul.call(a.dictionary)==="[object ArrayBuffer]"?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.K;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,b===2||b===1&&l.status!==42||l.B)b=-2;else{b===1&&(a.I=rk(a.I,f,g,0));l.wrap=0;g>=l.la&&(b===0&&(fl(l.head),l.v=0,l.va=0,l.sa=0),c=new O.pb(l.la),O.tb(c,f,g-l.la,l.la,0),f=c,g=l.la);c=a.ma;d=a.lb;e=a.input;a.ma=g;a.lb=0;a.input=f;for(kl(l);l.B>=3;){f=l.v;g=l.B-2;do l.R=(l.R<<l.Ma^l.window[f+3-1])&l.La,l.Ia[f&l.cb]=l.head[l.R],l.head[l.R]=f,f++;while(--g);
l.v=f;l.B=2;kl(l)}l.v+=l.B;l.va=l.v;l.sa=l.B;l.B=0;l.T=l.wa=2;l.jb=0;a.lb=d;a.input=e;a.ma=c;l.wrap=b;b=0}else b=-2;if(b!==0)throw Error(xk[b]);this.rh=!0}}
vl.prototype.push=function(a,b){var c=this.K,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:b===!0?4:0;typeof a==="string"?c.input=qk(a):ul.call(a)==="[object ArrayBuffer]"?c.input=new Uint8Array(a):c.input=a;c.lb=0;c.ma=c.input.length;do{c.S===0&&(c.output=new O.pb(d),c.Eb=0,c.S=d);a=sl(c,e);if(a!==1&&a!==0)return wl(this,a),this.ended=!0,!1;if(c.S===0||c.ma===0&&(e===4||e===2))if(this.options.to==="string"){var f=O.bd(c.output,c.Eb);b=f;f=f.length;if(f<65537&&(b.subarray&&pk||!b.subarray))b=
String.fromCharCode.apply(null,O.bd(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=O.bd(c.output,c.Eb),this.chunks.push(b)}while((c.ma>0||c.S===0)&&a!==1);if(e===4)return(c=this.K)&&c.state?(d=c.state.status,d!==42&&d!==69&&d!==73&&d!==91&&d!==103&&d!==113&&d!==666?a=el(c,-2):(c.state=null,a=d===113?el(c,-3):0)):a=-2,wl(this,a),this.ended=!0,a===0;e===2&&(wl(this,0),c.S=0);return!0};
function wl(a,b){b===0&&(a.result=a.options.to==="string"?a.chunks.join(""):O.sd(a.chunks));a.chunks=[];a.err=b;a.msg=a.K.msg}
function xl(a,b){b=b||{};b.gzip=!0;b=new vl(b);b.push(a,!0);if(b.err)throw b.msg||xk[b.err];return b.result}
;function yl(a){return a?(a=a.privateDoNotAccessOrElseSafeScriptWrappedValue)?Cb(a):null:null}
function zl(a){return a?(a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue)?jb(a):null:null}
;function Al(a){return jb(a===null?"null":a===void 0?"undefined":a)}
;function Bl(a){this.name=a}
;var Cl=new Bl("rawColdConfigGroup");var Dl=new Bl("rawHotConfigGroup");function El(a){this.F=L(a)}
w(El,M);function Fl(a){this.F=L(a)}
w(Fl,M);Fl.prototype.setTrackingParams=function(a){if(a!=null)if(typeof a==="string")a=a?new Bd(a,Ad):Dd||(Dd=new Bd(null,Ad));else if(a.constructor!==Bd)if(zd(a))a instanceof Uint8Array||Array.isArray(a),a=a.length?new Bd(new Uint8Array(a),Ad):Dd||(Dd=new Bd(null,Ad));else throw Error();return of(this,1,a)};var Gl=new Bl("continuationCommand");var Hl=new Bl("webCommandMetadata");var Il=new Bl("signalServiceEndpoint");var Jl={Sf:"EMBEDDED_PLAYER_MODE_UNKNOWN",Pf:"EMBEDDED_PLAYER_MODE_DEFAULT",Rf:"EMBEDDED_PLAYER_MODE_PFP",Qf:"EMBEDDED_PLAYER_MODE_PFL"};var Kl=new Bl("feedbackEndpoint");var ee={Vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNKNOWN",pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_FOR_TESTING",Gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_RESUME_TO_HOME_TTL",Ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_START_TO_SHORTS_ANALYSIS_SLICE",eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DEVICE_LAYER_SLICE",Ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNIFIED_LAYER_SLICE",Xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_VISITOR_LAYER_SLICE",Mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHOW_SHEET_COMMAND_HANDLER_BLOCK",
Zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_MIGRATED_COMPONENT",Yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_CHANNEL_NAME_TOOLTIP",Jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATION_LOCK_SUPPORTED",Pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_THEATER_MODE_ENABLED",eh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_PIN_SUGGESTION",dh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_LONG_PRESS_EDU_TOAST",bh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_AMBIENT",Qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TIME_WATCHED_PANEL",
Lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SEARCH_FROM_SEARCH_BAR_OVERLAY",fh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_VOICE_SEARCH_EDU_TOAST",Og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SUGGESTED_LANGUAGE_SELECTED",gh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_TRIGGER_SHORTS_PIP",wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IN_ZP_VOICE_CRASHY_SET",Cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_SUPPRESSED",Bg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_ALLOWED",Eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_PULL_TO_REFRESH_ATTEMPT",
ah:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_BLOCK_KABUKI",Fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_TALL_SCREEN",Dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_NORMAL_SCREEN",Wf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_ENABLED",Vf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_DISABLED",Xf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_AUTOPLAY_ENABLED",Yf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_CAST_MATCH_OCCURRED",ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_ELIGIBLE",lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ENDSCREEN_TRIGGERED",
Ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_TRIGGERED",zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_LACT_THRESHOLD_EXCEEDED",qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MATCHED_ON_REMOTE_CONNECTION",sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHABLE_ON_REMOTE_CONNECTION",rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MISATTRIBUTED_ON_REMOTE_CONNECTION",vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_TV_IS_SIGNED_IN_ON_REMOTE_CONNECTION",Sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_COLD_ON_REMOTE_CONNECTION",
Tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_NON_COLD_ON_REMOTE_CONNECTION",yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ON_REMOTE_CONNECTION",dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_VALID",ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_INVALID",cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_UNDEFINED",Zf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_DEFINED",xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_LACT_THRESHOLD_EXCEEDED",
Kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROUND_TRIP_HANDLING_ON_REMOTE_CONNECTION",ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_BEFORE_APP_RELOAD",tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_AFTER_APP_RELOAD",jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_INELIGIBLE",Rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TVHTML5_MID_ROLL_THRESHOLD_REACHED",ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_PENDING",
mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_ACTIVATED",kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_M2_ELIGIBLE",Hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_LANDSCAPE",Ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_PORTRAIT",hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMBEDS_FACEOFF_UI_EVENT",og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_RECEIVED",gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ELIGIBLE_TO_SUPPRESS_TRANSPORT_CONTROLS_BUTTONS",
Wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_USER_HAS_THEATER_MODE_COOKIE_ENABLED",fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DOCUMENT_PICTURE_IN_PICTURE_SUPPORTED"};var Ll=new Bl("shareEndpoint"),Ml=new Bl("shareEntityEndpoint"),Nl=new Bl("shareEntityServiceEndpoint"),Ol=new Bl("webPlayerShareEntityServiceEndpoint");var Pl=new Bl("playlistEditEndpoint");var Ql=new Bl("modifyChannelNotificationPreferenceEndpoint");var Rl=new Bl("unsubscribeEndpoint");var Sl=new Bl("subscribeEndpoint");function Tl(){var a=Ul;F("yt.ads.biscotti.getId_")||E("yt.ads.biscotti.getId_",a)}
function Vl(a){E("yt.ads.biscotti.lastId_",a)}
;function Wl(a,b){b.length>1?a[b[0]]=b[1]:b.length===1&&Object.assign(a,b[0])}
;var Xl=D.window,Yl,Zl,$l=(Xl==null?void 0:(Yl=Xl.yt)==null?void 0:Yl.config_)||(Xl==null?void 0:(Zl=Xl.ytcfg)==null?void 0:Zl.data_)||{};E("yt.config_",$l);function am(){Wl($l,arguments)}
function R(a,b){return a in $l?$l[a]:b}
function bm(a){var b=$l.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var cm=[];function dm(a){cm.forEach(function(b){return b(a)})}
function em(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){fm(b)}}:a}
function fm(a){var b=F("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),am("ERRORS",b));dm(a)}
function gm(a,b,c,d,e){var f=F("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=R("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),am("ERRORS",f))}
;var hm=/^[\w.]*$/,im={q:!0,search_query:!0};function jm(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(f.length===1&&f[0]||f.length===2)try{var g=km(f[0]||""),h=km(f[1]||"");if(g in c){var k=c[g];Array.isArray(k)?Tb(k,h):c[g]=[k,h]}else c[g]=h}catch(p){var l=p,m=f[0],n=String(jm);l.args=[{key:m,value:f[1],query:a,method:lm===n?"unchanged":n}];im.hasOwnProperty(m)||gm(l)}}return c}
var lm=String(jm);function mm(a){var b=[];kg(a,function(c,d){var e=encodeURIComponent(String(d));c=Array.isArray(c)?c:[c];Nb(c,function(f){f==""?b.push(e):b.push(e+"="+encodeURIComponent(String(f)))})});
return b.join("&")}
function nm(a){a.charAt(0)==="?"&&(a=a.substring(1));return jm(a,"&")}
function om(a){return a.indexOf("?")!==-1?(a=(a||"").split("#")[0],a=a.split("?",2),nm(a.length>1?a[1]:a[0])):{}}
function pm(a,b){return qm(a,b||{},!0)}
function qm(a,b,c){var d=a.split("#",2);a=d[0];d=d.length>1?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=nm(e[1]||"");for(var f in b)!c&&e!==null&&f in e||(e[f]=b[f]);return ic(a,e)+d}
function rm(a){if(!b)var b=window.location.href;var c=bc(1,a),d=cc(a);c&&d?(a=a.match($b),b=b.match($b),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?cc(b)===d&&(Number(bc(4,b))||null)===(Number(bc(4,a))||null):!0;return a}
function km(a){return a&&a.match(hm)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function sm(a){var b=tm;a=a===void 0?F("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Fj;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Na){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=g===void 0?xj:g;try{var h=g.history.length}catch(Na){h=0}e.u_his=h;var k;e.u_h=(k=xj.screen)==null?void 0:k.height;var l;e.u_w=(l=xj.screen)==null?void 0:l.width;var m;e.u_ah=(m=xj.screen)==null?void 0:m.availHeight;var n;e.u_aw=
(n=xj.screen)==null?void 0:n.availWidth;var p;e.u_cd=(p=xj.screen)==null?void 0:p.colorDepth}catch(Na){}h=b.h;try{var t=h.screenX;var v=h.screenY}catch(Na){}try{var x=h.outerWidth;var z=h.outerHeight}catch(Na){}try{var G=h.innerWidth;var J=h.innerHeight}catch(Na){}try{var ba=h.screenLeft;var ca=h.screenTop}catch(Na){}try{G=h.innerWidth,J=h.innerHeight}catch(Na){}try{var Ma=h.screen.availWidth;var Kb=h.screen.availTop}catch(Na){}t=[ba,ca,t,v,Ma,Kb,x,z,G,J];try{var ja=(b.h.top||window).document,Ya=
ja.compatMode=="CSS1Compat"?ja.documentElement:ja.body;var Oa=(new jg(Ya.clientWidth,Ya.clientHeight)).round()}catch(Na){Oa=new jg(-12245933,-12245933)}ja=Oa;Oa={};var Pa=Pa===void 0?D:Pa;Ya=new Lj;"SVGElement"in Pa&&"createElementNS"in Pa.document&&Ya.set(0);v=Cj();v["allow-top-navigation-by-user-activation"]&&Ya.set(1);v["allow-popups-to-escape-sandbox"]&&Ya.set(2);Pa.crypto&&Pa.crypto.subtle&&Ya.set(3);"TextDecoder"in Pa&&"TextEncoder"in Pa&&Ya.set(4);Pa=Mj(Ya);Oa.bc=Pa;Oa.bih=ja.height;Oa.biw=
ja.width;Oa.brdim=t.join();b=b.i;b=(Oa.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,Oa.wgl=!!xj.WebGLRenderingContext,Oa);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var tm=new function(){var a=window.document;this.h=window;this.i=a};
E("yt.ads_.signals_.getAdSignalsString",function(a){return mm(sm(a))});$a();navigator.userAgent.indexOf(" (CrKey ");var um="XMLHttpRequest"in D?function(){return new XMLHttpRequest}:null;
function wm(){if(!um)return null;var a=um();return"open"in a?a:null}
function xm(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function ym(a,b){typeof a==="function"&&(a=em(a));return window.setTimeout(a,b)}
;var zm="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(A(zm),["client_dev_set_cookie"]);function S(a){a=Am(a);return typeof a==="string"&&a==="false"?!1:!!a}
function T(a,b){a=Am(a);return a===void 0&&b!==void 0?b:Number(a||0)}
function Am(a){return R("EXPERIMENT_FLAGS",{})[a]}
function Bm(){for(var a=[],b=R("EXPERIMENTS_FORCED_FLAGS",{}),c=y(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=R("EXPERIMENT_FLAGS",{});d=y(Object.keys(c));for(var e=d.next();!e.done;e=d.next())e=e.value,e.startsWith("force_")&&b[e]===void 0&&a.push({key:e,value:String(c[e])});return a}
;var Cm={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},Dm="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(A(zm)),Em=!1;function Fm(a,b,c,d,e,f,g,h){function k(){(l&&"readyState"in l?l.readyState:0)===4&&b&&em(b)(l)}
c=c===void 0?"GET":c;d=d===void 0?"":d;h=h===void 0?!1:h;var l=wm();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;S("debug_forward_web_query_parameters")&&(a=Gm(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c=c==="POST"&&(window.FormData===void 0||!(d instanceof FormData));if(e=Hm(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"===m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
if(h&&"setAttributionReporting"in XMLHttpRequest.prototype){a={eventSourceEligible:!0,triggerEligible:!1};try{l.setAttributionReporting(a)}catch(n){gm(n)}}l.send(d);return l}
function Hm(a,b){b=b===void 0?{}:b;var c=rm(a),d=R("INNERTUBE_CLIENT_NAME"),e=S("web_ajax_ignore_global_headers_if_set"),f;for(f in Cm){var g=R(Cm[f]),h=f==="X-Goog-AuthUser"||f==="X-Goog-PageId";f!=="X-Goog-Visitor-Id"||g||(g=R("VISITOR_DATA"));var k;if(!(k=!g)){if(!(k=c||(cc(a)?!1:!0))){k=a;var l;if(l=S("add_auth_headers_to_remarketing_google_dot_com_ping")&&f==="Authorization"&&(d==="TVHTML5"||d==="TVHTML5_UNPLUGGED"||d==="TVHTML5_SIMPLY"))l=cc(k),l=l!==null?l.split(".").reverse():null,l=l===null?
!1:l[1]==="google"?!0:l[2]==="google"?l[0]==="au"&&l[1]==="com"?!0:l[0]==="uk"&&l[1]==="co"?!0:!1:!1;l&&(k=ac(bc(5,k))||"",k=k.split("/"),k="/"+(k.length>1?k[1]:""),l=k==="/pagead");k=l?!0:!1}k=!k}k||e&&b[f]!==void 0||d==="TVHTML5_UNPLUGGED"&&h||(b[f]=g)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!cc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!cc(a)){try{var m=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(n){}m&&
(b["X-YouTube-Time-Zone"]=m)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&cc(a)||(b["X-YouTube-Ad-Signals"]=mm(sm()));return b}
function Im(a,b){b.method="POST";b.postParams||(b.postParams={});return Jm(a,b)}
function Jm(a,b){var c=b.format||"JSON";a=Km(a,b);var d=Lm(a,b),e=!1,f=Mm(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=xm(k),m=null,n=400<=k.status&&k.status<500,p=500<=k.status&&k.status<600;if(l||n||p)m=Nm(a,c,k,b.convertToSafeHtml);l&&(l=Om(c,k,m));m=m||{};n=b.context||D;l?b.onSuccess&&b.onSuccess.call(n,k,m):b.onError&&b.onError.call(n,k,m);b.onFinish&&b.onFinish.call(n,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&d>0){var g=b.onTimeout;var h=ym(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||D,f))},d)}return f}
function Km(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=pm(a,b);return a}
function Lm(a,b){var c=R("XSRF_FIELD_NAME"),d=R("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=R("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||cc(a)&&!b.withCredentials&&cc(a)!==document.location.hostname||b.method!=="POST"||h&&h!=="application/x-www-form-urlencoded"||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(S("ajax_parse_query_data_only_when_filled")&&f&&Object.keys(f).length>0||f)&&typeof e==="string"&&(e=nm(e),ug(e,f),e=b.postBodyFormat&&b.postBodyFormat===
"JSON"?JSON.stringify(e):hc(e));f=e||f&&!ng(f);!Em&&f&&b.method!=="POST"&&(Em=!0,fm(Error("AJAX request with postData should use POST")));return e}
function Nm(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,gm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&a.indexOf("json")>=0&&(f.substring(0,5)===")]}'\n"&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Pm(a):null)e={},Nb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Qm(g)})}d&&Rm(e);
return e}
function Rm(a){if(Ra(a))for(var b in a){var c;(c=b==="html_content")||(c=b.length-5,c=c>=0&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b];var e=hb();d=new zb(e?e.createHTML(d):d);a[c]=d}else Rm(a[b])}}
function Om(a,b,c){if(b&&b.status===204)return!0;switch(a){case "JSON":return!!c;case "XML":return Number(c&&c.return_code)===0;case "RAW":return!0;default:return!!c}}
function Pm(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&a.length>0?a[0]:null:null}
function Qm(a){var b="";Nb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Gm(a){var b=window.location.search,c=cc(a);S("debug_handle_relative_url_for_query_forward_killswitch")||!c&&rm(a)&&(c=document.location.hostname);var d=ac(bc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=nm(b),f={};Nb(Dm,function(g){e[g]&&(f[g]=e[g])});
return qm(a,f||{},!1)}
var Mm=Fm;var Sm=[{Qc:function(a){return"Cannot read property '"+a.key+"'"},
vc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Qc:function(a){return"Cannot call '"+a.key+"'"},
vc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Qc:function(a){return a.key+" is not defined"},
vc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Um={Ya:[],Ta:[{callback:Tm,weight:500}]};function Tm(a){if(a.name==="JavaException")return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Vm(){this.Ta=[];this.Ya=[]}
var Wm;function Xm(){if(!Wm){var a=Wm=new Vm;a.Ya.length=0;a.Ta.length=0;Um.Ya&&a.Ya.push.apply(a.Ya,Um.Ya);Um.Ta&&a.Ta.push.apply(a.Ta,Um.Ta)}return Wm}
;var Ym=new N;function Zm(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=$m(b);if(e===Infinity)break;var f=e>>3;switch(e&7){case 0:e=$m(b);if(f===2)return e;break;case 1:if(f===2)return;d+=8;break;case 2:e=$m(b);if(f===2)return a.substr(d,e);d+=e;break;case 5:if(f===2)return;d+=4;break;default:return}}while(d<c)}
function $m(a){var b=a(),c=b&127;if(b<128)return c;b=a();c|=(b&127)<<7;if(b<128)return c;b=a();c|=(b&127)<<14;if(b<128)return c;b=a();return b<128?c|(b&127)<<21:Infinity}
;function an(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=bn(d,a[d],b,c),e>500));d++);d=e}else if(typeof a==="object")for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f=typeof g!=="string"||f!=="clickTrackingParams"&&f!=="trackingParams"?0:(g=Zm(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?bn(f+".ve",g,h,k):0;d+=f;d+=bn(e,a[e],b,c);if(d>500)break}}else c[b]=cn(a),d+=c[b].length;else c[b]=cn(a),d+=c[b].length;return d}
function bn(a,b,c,d){c+="."+a;a=cn(b);d[c]=a;return c.length+a.length}
function cn(a){try{return(typeof a==="string"?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function dn(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function en(){if(!D.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return D.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":D.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":D.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":D.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function fn(){this.Ld=!0}
function gn(){fn.instance||(fn.instance=new fn);return fn.instance}
function hn(a,b){a={};var c=[];"USER_SESSION_ID"in $l&&c.push({key:"u",value:R("USER_SESSION_ID")});if(c=cg(c))a.Authorization=c,c=b=b==null?void 0:b.sessionIndex,c===void 0&&(c=Number(R("SESSION_INDEX",0)),c=isNaN(c)?0:c),S("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in $l||(a["X-Origin"]=window.location.origin),b===void 0&&"DELEGATED_SESSION_ID"in $l&&(a["X-Goog-PageId"]=R("DELEGATED_SESSION_ID"));return a}
;var jn={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function kn(a,b,c,d,e){$f.set(""+a,b,{Tb:c,path:"/",domain:d===void 0?"youtube.com":d,secure:e===void 0?!1:e})}
function ln(a){return $f.get(""+a,void 0)}
function mn(a,b,c){$f.remove(""+a,b===void 0?"/":b,c===void 0?"youtube.com":c)}
function nn(){if(S("embeds_web_enable_cookie_detection_fix")){if(!D.navigator.cookieEnabled)return!1}else if(!$f.isEnabled())return!1;if($f.h.cookie)return!0;S("embeds_web_enable_cookie_detection_fix")?$f.set("TESTCOOKIESENABLED","1",{Tb:60,bf:"none",secure:!0}):$f.set("TESTCOOKIESENABLED","1",{Tb:60});if($f.get("TESTCOOKIESENABLED")!=="1")return!1;$f.remove("TESTCOOKIESENABLED");return!0}
;var on=F("ytglobal.prefsUserPrefsPrefs_")||{};E("ytglobal.prefsUserPrefsPrefs_",on);function pn(){this.h=R("ALT_PREF_COOKIE_NAME","PREF");this.i=R("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=ln(this.h);a&&this.parse(a)}
var qn;function rn(){qn||(qn=new pn);return qn}
r=pn.prototype;r.get=function(a,b){sn(a);tn(a);a=on[a]!==void 0?on[a].toString():null;return a!=null?a:b?b:""};
r.set=function(a,b){sn(a);tn(a);if(b==null)throw Error("ExpectedNotNull");on[a]=b.toString()};
function un(a){return!!((vn("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
r.remove=function(a){sn(a);tn(a);delete on[a]};
r.clear=function(){for(var a in on)delete on[a]};
function tn(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function sn(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function vn(a){a=on[a]!==void 0?on[a].toString():null;return a!=null&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
r.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(on[d]=c.toString())}};var wn={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},xn={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function yn(){var a=D.navigator;return a?a.connection:void 0}
function zn(){var a=yn();if(a){var b=wn[a.type||"unknown"]||"CONN_UNKNOWN";a=wn[a.effectiveType||"unknown"]||"CONN_UNKNOWN";b==="CONN_CELLULAR_UNKNOWN"&&a!=="CONN_UNKNOWN"&&(b=a);if(b!=="CONN_UNKNOWN")return b;if(a!=="CONN_UNKNOWN")return a}}
function An(){var a=yn();if(a!=null&&a.effectiveType)return xn.hasOwnProperty(a.effectiveType)?xn[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function U(a){var b=C.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(A(b));Object.setPrototypeOf(this,this.constructor.prototype)}
w(U,Error);function Bn(){try{return Cn(),!0}catch(a){return!1}}
function Cn(a){if(R("DATASYNC_ID")!==void 0)return R("DATASYNC_ID");throw new U("Datasync ID not set",a===void 0?"unknown":a);}
;function Dn(){}
function En(a,b){return Kj.Ra(a,0,b)}
Dn.prototype.pa=function(a,b){return this.Ra(a,1,b)};
Dn.prototype.Jb=function(a){var b=F("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var Fn=T("web_emulated_idle_callback_delay",300),Gn=1E3/60-3,Hn=[8,5,4,3,2,1,0];
function In(a){a=a===void 0?{}:a;H.call(this);this.i=[];this.j={};this.Z=this.h=0;this.Y=this.u=!1;this.P=[];this.U=this.ha=!1;for(var b=y(Hn),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.o=0;this.Fc=a.timeout||1;this.G=Gn;this.D=0;this.xa=this.Oe.bind(this);this.Ec=this.uf.bind(this);this.Pa=this.Yd.bind(this);this.Qa=this.ze.bind(this);this.rb=this.Ve.bind(this);this.Fa=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!S("disable_scheduler_requestIdleCallback");(this.oa=a.useRaf!==
!1&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.xa)}
w(In,H);r=In.prototype;r.Jb=function(a){var b=$a();Jn(this,a);a=$a()-b;this.u||(this.G-=a)};
r.Ra=function(a,b,c){++this.Z;if(b===10)return this.Jb(a),this.Z;var d=this.Z;this.j[d]=a;this.u&&!c?this.P.push({id:d,priority:b}):(this.i[b].push(d),this.Y||this.u||(this.h!==0&&Kn(this)!==this.D&&this.stop(),this.start()));return d};
r.qa=function(a){delete this.j[a]};
function Ln(a){a.P.length=0;for(var b=5;b>=0;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
r.isHidden=function(){return!!document.hidden||!1};
function Mn(a){return!a.isHidden()&&a.oa}
function Kn(a){if(a.i[8].length){if(a.U)return 4;if(Mn(a))return 3}for(var b=5;b>=a.o;b--)if(a.i[b].length>0)return b>0?Mn(a)?3:2:1;return 0}
r.Ha=function(a){var b=F("yt.logging.errors.log");b&&b(a)};
function Jn(a,b){try{b()}catch(c){a.Ha(c)}}
function Nn(a){for(var b=y(Hn),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
r.ze=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ha=!0;On(this,b);this.ha=!1};
r.uf=function(){On(this)};
r.Yd=function(){Pn(this)};
r.Ve=function(a){this.U=!0;var b=Kn(this);b===4&&b!==this.D&&(this.stop(),this.start());On(this,void 0,a);this.U=!1};
r.Oe=function(){this.isHidden()||Pn(this);this.h&&(this.stop(),this.start())};
function Pn(a){a.stop();a.u=!0;for(var b=$a(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&Jn(a,e)}Qn(a);a.u=!1;Nn(a)&&a.start();b=$a()-b;a.G-=b}
function Qn(a){for(var b=0,c=a.P.length;b<c;b++){var d=a.P[b];a.i[d.priority].push(d.id)}a.P.length=0}
function On(a,b,c){a.U&&a.D===4&&a.h||a.stop();a.u=!0;b=$a()+(b||a.G);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Ha(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&Jn(a,f);d=a.ha?0:1;d=a.o>d?a.o:d;if(!($a()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&Jn(a,c)}while(c&&$a()<b)}a.u=!1;Qn(a);a.G=Gn;Nn(a)&&a.start()}
r.start=function(){this.Y=!1;if(this.h===0)switch(this.D=Kn(this),this.D){case 1:var a=this.Qa;this.h=this.Fa?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,Fn);break;case 2:this.h=window.setTimeout(this.Ec,this.Fc);break;case 3:this.h=window.requestAnimationFrame(this.rb);break;case 4:this.h=window.setTimeout(this.Pa,0)}};
r.pause=function(){this.stop();this.Y=!0};
r.stop=function(){if(this.h){switch(this.D){case 1:var a=this.h;this.Fa?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
r.ba=function(){Ln(this);this.stop();this.oa&&document.removeEventListener("visibilitychange",this.xa);H.prototype.ba.call(this)};var Rn=F("yt.scheduler.instance.timerIdMap_")||{},Sn=T("kevlar_tuner_scheduler_soft_state_timer_ms",800),Tn=0,Un=0;function Vn(){var a=F("ytglobal.schedulerInstanceInstance_");if(!a||a.ea)a=new In(R("scheduler")||{}),E("ytglobal.schedulerInstanceInstance_",a);return a}
function Wn(){Xn();var a=F("ytglobal.schedulerInstanceInstance_");a&&(sc(a),E("ytglobal.schedulerInstanceInstance_",null))}
function Xn(){Ln(Vn());for(var a in Rn)Rn.hasOwnProperty(a)&&delete Rn[Number(a)]}
function Yn(a,b,c){if(!c)return c=c===void 0,-Vn().Ra(a,b,c);var d=window.setTimeout(function(){var e=Vn().Ra(a,b);Rn[d]=e},c);
return d}
function Zn(a){Vn().Jb(a)}
function $n(a){var b=Vn();if(a<0)b.qa(-a);else{var c=Rn[a];c?(b.qa(c),delete Rn[a]):window.clearTimeout(a)}}
function ao(){bo()}
function bo(){window.clearTimeout(Tn);Vn().start()}
function co(){Vn().pause();window.clearTimeout(Tn);Tn=window.setTimeout(ao,Sn)}
function eo(){window.clearTimeout(Un);Un=window.setTimeout(function(){fo(0)},Sn)}
function fo(a){eo();var b=Vn();b.o=a;b.start()}
function go(a){eo();var b=Vn();b.o>a&&(b.o=a,b.start())}
function ho(){window.clearTimeout(Un);var a=Vn();a.o=0;a.start()}
;function io(){Dn.apply(this,arguments)}
w(io,Dn);function jo(){io.instance||(io.instance=new io);return io.instance}
io.prototype.Ra=function(a,b,c){c!==void 0&&Number.isNaN(Number(c))&&(c=void 0);var d=F("yt.scheduler.instance.addJob");return d?d(a,b,c):c===void 0?(a(),NaN):ym(a,c||0)};
io.prototype.qa=function(a){if(a===void 0||!Number.isNaN(Number(a))){var b=F("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
io.prototype.start=function(){var a=F("yt.scheduler.instance.start");a&&a()};
io.prototype.pause=function(){var a=F("yt.scheduler.instance.pause");a&&a()};
var Kj=jo();
S("web_scheduler_auto_init")&&!F("yt.scheduler.initialized")&&(E("yt.scheduler.instance.dispose",Wn),E("yt.scheduler.instance.addJob",Yn),E("yt.scheduler.instance.addImmediateJob",Zn),E("yt.scheduler.instance.cancelJob",$n),E("yt.scheduler.instance.cancelAllJobs",Xn),E("yt.scheduler.instance.start",bo),E("yt.scheduler.instance.pause",co),E("yt.scheduler.instance.setPriorityThreshold",fo),E("yt.scheduler.instance.enablePriorityThreshold",go),E("yt.scheduler.instance.clearPriorityThreshold",ho),E("yt.scheduler.initialized",
!0));function ko(a){var b=new kk;this.h=(a=b.isAvailable()?a?new lk(b,a):b:null)?new fk(a):null;this.i=document.domain||window.location.hostname}
ko.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+c*1E3);return}catch(f){}var e="";if(d)try{e=escape((new Gi).serialize(b))}catch(f){return}else e=escape(b);kn(a,e,c,this.i)};
ko.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=ln(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
ko.prototype.remove=function(a){this.h&&this.h.remove(a);mn(a,"/",this.i)};var lo=function(){var a;return function(){a||(a=new ko("ytidb"));return a}}();
function mo(){var a;return(a=lo())==null?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var no=[],oo,po=!1;function qo(){var a={};for(oo=new ro(a.handleError===void 0?so:a.handleError,a.logEvent===void 0?to:a.logEvent);no.length>0;)switch(a=no.shift(),a.type){case "ERROR":oo.Ha(a.payload);break;case "EVENT":oo.logEvent(a.eventType,a.payload)}}
function uo(a){po||(oo?oo.Ha(a):(no.push({type:"ERROR",payload:a}),no.length>10&&no.shift()))}
function vo(a,b){po||(oo?oo.logEvent(a,b):(no.push({type:"EVENT",eventType:a,payload:b}),no.length>10&&no.shift()))}
;function wo(a){if(a.indexOf(":")>=0)throw Error("Database name cannot contain ':'");}
function xo(a){return a.substr(0,a.indexOf(":"))||a}
;var yo=kd||ld;function zo(a){var b=Uc();return b?b.toLowerCase().indexOf(a)>=0:!1}
;var Ao={},Bo=(Ao.AUTH_INVALID="No user identifier specified.",Ao.EXPLICIT_ABORT="Transaction was explicitly aborted.",Ao.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Ao.MISSING_INDEX="Index not created.",Ao.MISSING_OBJECT_STORES="Object stores not created.",Ao.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Ao.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",Ao.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
Ao.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Ao.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Ao.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Ao.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Ao),Co={},Do=(Co.AUTH_INVALID="ERROR",Co.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Co.EXPLICIT_ABORT="IGNORED",Co.IDB_NOT_SUPPORTED="ERROR",Co.MISSING_INDEX=
"WARNING",Co.MISSING_OBJECT_STORES="ERROR",Co.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",Co.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",Co.QUOTA_EXCEEDED="WARNING",Co.QUOTA_MAYBE_EXCEEDED="WARNING",Co.UNKNOWN_ABORT="WARNING",Co.INCOMPATIBLE_DB_VERSION="WARNING",Co),Eo={},Fo=(Eo.AUTH_INVALID=!1,Eo.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Eo.EXPLICIT_ABORT=!1,Eo.IDB_NOT_SUPPORTED=!1,Eo.MISSING_INDEX=!1,Eo.MISSING_OBJECT_STORES=!1,Eo.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Eo.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Eo.QUOTA_EXCEEDED=!1,Eo.QUOTA_MAYBE_EXCEEDED=!0,Eo.UNKNOWN_ABORT=!0,Eo.INCOMPATIBLE_DB_VERSION=!1,Eo);function Go(a,b,c,d,e){b=b===void 0?{}:b;c=c===void 0?Bo[a]:c;d=d===void 0?Do[a]:d;e=e===void 0?Fo[a]:e;U.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:self.document===void 0,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Go.prototype)}
w(Go,U);function Ho(a,b){Go.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Bo.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Ho.prototype)}
w(Ho,Go);function Io(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Io.prototype)}
w(Io,Error);var Jo=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Ko(a,b,c,d){b=xo(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Go)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if(e.name==="QuotaExceededError")return new Go("QUOTA_EXCEEDED",a);if(md&&e.name==="UnknownError")return new Go("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Io)return new Go("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if(e.name==="InvalidStateError"&&Jo.some(function(f){return e.message.includes(f)}))return new Go("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if(e.name==="AbortError")return new Go("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Cd:e.name})];e.level="WARNING";return e}
function Lo(a,b,c){var d=mo();return new Go("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:d==null?void 0:d.hasSucceededOnce}})}
;function Mo(a){if(!a)throw Error();throw a;}
function No(a){return a}
function Oo(a){this.h=a}
function Po(a){function b(e){if(d.state.status==="PENDING"){d.state={status:"REJECTED",reason:e};e=y(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if(d.state.status==="PENDING"){d.state={status:"FULFILLED",value:e};e=y(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Po.all=function(a){return new Po(new Oo(function(b,c){var d=[],e=a.length;e===0&&b(d);for(var f={zb:0};f.zb<a.length;f={zb:f.zb},++f.zb)Po.resolve(a[f.zb]).then(function(g){return function(h){d[g.zb]=h;e--;e===0&&b(d)}}(f)).catch(function(g){c(g)})}))};
Po.resolve=function(a){return new Po(new Oo(function(b,c){a instanceof Po?a.then(b,c):b(a)}))};
Po.reject=function(a){return new Po(new Oo(function(b,c){c(a)}))};
Po.prototype.then=function(a,b){var c=this,d=a!=null?a:No,e=b!=null?b:Mo;return new Po(new Oo(function(f,g){c.state.status==="PENDING"?(c.h.push(function(){Qo(c,c,d,f,g)}),c.i.push(function(){Ro(c,c,e,f,g)})):c.state.status==="FULFILLED"?Qo(c,c,d,f,g):c.state.status==="REJECTED"&&Ro(c,c,e,f,g)}))};
Po.prototype.catch=function(a){return this.then(void 0,a)};
function Qo(a,b,c,d,e){try{if(a.state.status!=="FULFILLED")throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Po?So(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Ro(a,b,c,d,e){try{if(a.state.status!=="REJECTED")throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Po?So(a,b,f,d,e):d(f)}catch(g){e(g)}}
function So(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Po?So(a,b,f,d,e):d(f)},function(f){e(f)})}
;function To(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Uo(a){return new Promise(function(b,c){To(a,b,c)})}
function Vo(a){return new Po(new Oo(function(b,c){To(a,b,c)}))}
;function Wo(a,b){return new Po(new Oo(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Xo=window,V=Xo.ytcsi&&Xo.ytcsi.now?Xo.ytcsi.now:Xo.performance&&Xo.performance.timing&&Xo.performance.now&&Xo.performance.timing.navigationStart?function(){return Xo.performance.timing.navigationStart+Xo.performance.now()}:function(){return(new Date).getTime()};function Yo(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(V());this.i=!1}
r=Yo.prototype;r.add=function(a,b,c){return Zo(this,[a],{mode:"readwrite",ka:!0},function(d){return d.objectStore(a).add(b,c)})};
r.clear=function(a){return Zo(this,[a],{mode:"readwrite",ka:!0},function(b){return b.objectStore(a).clear()})};
r.close=function(){this.h.close();var a;((a=this.options)==null?0:a.closed)&&this.options.closed()};
r.count=function(a,b){return Zo(this,[a],{mode:"readonly",ka:!0},function(c){return c.objectStore(a).count(b)})};
function $o(a,b,c){a=a.h.createObjectStore(b,c);return new ap(a)}
r.delete=function(a,b){return Zo(this,[a],{mode:"readwrite",ka:!0},function(c){return c.objectStore(a).delete(b)})};
r.get=function(a,b){return Zo(this,[a],{mode:"readonly",ka:!0},function(c){return c.objectStore(a).get(b)})};
function bp(a,b,c){return Zo(a,[b],{mode:"readwrite",ka:!0},function(d){d=d.objectStore(b);return Vo(d.h.put(c,void 0))})}
r.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Zo(a,b,c,d){var e,f,g,h,k,l,m,n,p,t,v,x;return B(function(z){switch(z.h){case 1:var G={mode:"readonly",ka:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};typeof c==="string"?G.mode=c:Object.assign(G,c);e=G;a.transactionCount++;f=e.ka?3:1;g=0;case 2:if(h){z.A(4);break}g++;k=Math.round(V());ya(z,5);l=a.h.transaction(b,e.mode);G=z.yield;var J=new cp(l);J=dp(J,d);return G.call(z,J,7);case 7:return m=z.i,n=Math.round(V()),ep(a,k,n,g,void 0,b.join(),e),z.return(m);case 5:p=Aa(z);t=Math.round(V());v=Ko(p,
a.h.name,b.join(),a.h.version);if((x=v instanceof Go&&!v.h)||g>=f)ep(a,k,t,g,v,b.join(),e),h=v;z.A(2);break;case 4:return z.return(Promise.reject(h))}})}
function ep(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Go&&(e.type==="QUOTA_EXCEEDED"||e.type==="QUOTA_MAYBE_EXCEEDED")&&vo("QUOTA_EXCEEDED",{dbName:xo(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Go&&e.type==="UNKNOWN_ABORT"&&(c-=a.j,c<0&&c>=2147483648&&(c=0),vo("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),fp(a,!1,d,f,b,g.tag),uo(e)):fp(a,!0,d,f,b,g.tag)}
function fp(a,b,c,d,e,f){vo("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:f===void 0?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
r.getName=function(){return this.h.name};
function ap(a){this.h=a}
r=ap.prototype;r.add=function(a,b){return Vo(this.h.add(a,b))};
r.autoIncrement=function(){return this.h.autoIncrement};
r.clear=function(){return Vo(this.h.clear()).then(function(){})};
function gp(a,b,c){a.h.createIndex(b,c,{unique:!1})}
r.count=function(a){return Vo(this.h.count(a))};
function hp(a,b){return ip(a,{query:b},function(c){return c.delete().then(function(){return jp(c)})}).then(function(){})}
r.delete=function(a){return a instanceof IDBKeyRange?hp(this,a):Vo(this.h.delete(a))};
r.get=function(a){return Vo(this.h.get(a))};
r.index=function(a){try{return new kp(this.h.index(a))}catch(b){if(b instanceof Error&&b.name==="NotFoundError")throw new Io(a,this.h.name);throw b;}};
r.getName=function(){return this.h.name};
r.keyPath=function(){return this.h.keyPath};
function ip(a,b,c){a=a.h.openCursor(b.query,b.direction);return lp(a).then(function(d){return Wo(d,c)})}
function cp(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Go;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(k===null)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function dp(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return y(d).next().value})}
cp.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Go("EXPLICIT_ABORT");};
cp.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new ap(a),this.i.set(a,b));return b};
function kp(a){this.h=a}
r=kp.prototype;r.count=function(a){return Vo(this.h.count(a))};
r.delete=function(a){return mp(this,{query:a},function(b){return b.delete().then(function(){return jp(b)})})};
r.get=function(a){return Vo(this.h.get(a))};
r.keyPath=function(){return this.h.keyPath};
r.unique=function(){return this.h.unique};
function mp(a,b,c){a=a.h.openCursor(b.query===void 0?null:b.query,b.direction===void 0?"next":b.direction);return lp(a).then(function(d){return Wo(d,c)})}
function np(a,b){this.request=a;this.cursor=b}
function lp(a){return Vo(a).then(function(b){return b?new np(a,b):null})}
function jp(a){a.cursor.continue(void 0);return lp(a.request)}
np.prototype.delete=function(){return Vo(this.cursor.delete()).then(function(){})};
np.prototype.getValue=function(){return this.cursor.value};
np.prototype.update=function(a){return Vo(this.cursor.update(a))};function op(a,b,c){return new Promise(function(d,e){function f(){p||(p=new Yo(g.result,{closed:n}));return p}
var g=b!==void 0?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.be,k=c.blocking,l=c.sf,m=c.upgrade,n=c.closed,p;g.addEventListener("upgradeneeded",function(t){try{if(t.newVersion===null)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(g.transaction===null)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&t.dataLoss!=="none"&&vo("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:xo(a)});var v=f(),x=new cp(g.transaction);
m&&m(v,function(z){return t.oldVersion<z&&t.newVersion>=z},x);
x.done.catch(function(z){e(z)})}catch(z){e(z)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){vo("IDB_UNEXPECTEDLY_CLOSED",{dbName:xo(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function pp(a,b,c){c=c===void 0?{}:c;return op(a,b,c)}
function qp(a,b){b=b===void 0?{}:b;var c,d,e,f;return B(function(g){if(g.h==1)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.be)&&c.addEventListener("blocked",function(){e()}),g.yield(Uo(c),4);
if(g.h!=2)return za(g,0);f=Aa(g);throw Ko(f,a,"",-1);})}
;function rp(a,b){this.name=a;this.options=b;this.j=!0;this.u=this.o=0}
rp.prototype.i=function(a,b,c){c=c===void 0?{}:c;return pp(a,b,c)};
rp.prototype.delete=function(a){a=a===void 0?{}:a;return qp(this.name,a)};
function sp(a,b){return new Go("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function tp(a,b){if(!b)throw Lo("openWithToken",xo(a.name));return a.open()}
rp.prototype.open=function(){function a(){var f,g,h,k,l,m,n,p,t,v;return B(function(x){switch(x.h){case 1:return g=(f=Error().stack)!=null?f:"",ya(x,2),x.yield(c.i(c.name,c.options.version,e),4);case 4:for(var z=h=x.i,G=c.options,J=[],ba=y(Object.keys(G.Fb)),ca=ba.next();!ca.done;ca=ba.next()){ca=ca.value;var Ma=G.Fb[ca],Kb=Ma.We===void 0?Number.MAX_VALUE:Ma.We;!(z.h.version>=Ma.Lb)||z.h.version>=Kb||z.h.objectStoreNames.contains(ca)||J.push(ca)}k=J;if(k.length===0){x.A(5);break}l=Object.keys(c.options.Fb);
m=h.objectStoreNames();if(c.u<T("ytidb_reopen_db_retries",0))return c.u++,h.close(),uo(new Go("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());if(!(c.o<T("ytidb_remake_db_retries",1))){x.A(6);break}c.o++;return x.yield(c.delete(),7);case 7:return uo(new Go("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());case 6:throw new Ho(m,l);case 5:return x.return(h);case 2:n=Aa(x);
if(n instanceof DOMException?n.name!=="VersionError":"DOMError"in self&&n instanceof DOMError?n.name!=="VersionError":!(n instanceof Object&&"message"in n)||n.message!=="An attempt was made to open a database using a lower version than the existing version."){x.A(8);break}return x.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:p=x.i;t=p.h.version;if(c.options.version!==void 0&&t>c.options.version+1)throw p.close(),c.j=!1,sp(c,t);return x.return(p);case 8:throw b(),n instanceof
Error&&!S("ytidb_async_stack_killswitch")&&(n.stack=n.stack+"\n"+g.substring(g.indexOf("\n")+1)),Ko(n,c.name,"",(v=c.options.version)!=null?v:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw sp(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,sf:b,upgrade:this.options.upgrade};return this.h=d=a()};var up=new rp("YtIdbMeta",{Fb:{databases:{Lb:1}},upgrade:function(a,b){b(1)&&$o(a,"databases",{keyPath:"actualName"})}});
function vp(a,b){var c;return B(function(d){if(d.h==1)return d.yield(tp(up,b),2);c=d.i;return d.return(Zo(c,["databases"],{ka:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Vo(f.h.put(a,void 0)).then(function(){})})}))})}
function wp(a,b){var c;return B(function(d){if(d.h==1)return a?d.yield(tp(up,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function xp(a,b){var c,d;return B(function(e){return e.h==1?(c=[],e.yield(tp(up,b),2)):e.h!=3?(d=e.i,e.yield(Zo(d,["databases"],{ka:!0,mode:"readonly"},function(f){c.length=0;return ip(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return jp(g)})}),3)):e.return(c)})}
function yp(a){return xp(function(b){return b.publicName==="LogsDatabaseV2"&&b.userIdentifier!==void 0},a)}
function zp(a,b,c){return xp(function(d){return c?d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)},b)}
function Ap(a){var b,c;return B(function(d){if(d.h==1)return b=Cn("YtIdbMeta hasAnyMeta other"),d.yield(xp(function(e){return e.userIdentifier!==void 0&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(c.length>0)})}
;var Bp,Cp=new function(){}(new function(){});
function Dp(){var a,b,c,d;return B(function(e){switch(e.h){case 1:a=mo();if((b=a)==null?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=yo)f=/WebKit\/([0-9]+)/.exec(Uc()),f=!!(f&&parseInt(f[1],10)>=600);f&&(f=/WebKit\/([0-9]+)/.exec(Uc()),f=!(f&&parseInt(f[1],10)>=602));if(f||gd)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(vp(d,Cp),4);case 4:return e.yield(wp("yt-idb-test-do-not-use",Cp),5);case 5:return e.return(!0);case 2:return Aa(e),e.return(!1)}})}
function Ep(){if(Bp!==void 0)return Bp;po=!0;return Bp=Dp().then(function(a){po=!1;var b;if((b=lo())!=null&&b.h){var c;b={hasSucceededOnce:((c=mo())==null?void 0:c.hasSucceededOnce)||a};var d;(d=lo())==null||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Fp(){return F("ytglobal.idbToken_")||void 0}
function Gp(){var a=Fp();return a?Promise.resolve(a):Ep().then(function(b){(b=b?Cp:void 0)&&E("ytglobal.idbToken_",b);return b})}
;var Hp=0;function Ip(a,b){Hp||(Hp=Kj.pa(function(){var c,d,e,f,g;return B(function(h){switch(h.h){case 1:return h.yield(Gp(),2);case 2:c=h.i;if(!c)return h.return();d=!0;ya(h,3);return h.yield(zp(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return h.yield(qp(f.actualName),7);case 7:return h.yield(wp(f.actualName,c),6);case 6:za(h,4);break;case 3:g=Aa(h),uo(g),d=!1;case 4:Kj.qa(Hp),Hp=0,d&&Ip(a,b),h.h=0}})}))}
function Jp(){var a;return B(function(b){return b.h==1?b.yield(Gp(),2):(a=b.i)?b.return(Ap(a)):b.return(!1)})}
new mj;function Kp(a){if(!Bn())throw a=new Go("AUTH_INVALID",{dbName:a}),uo(a),a;var b=Cn();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Lp(a,b,c,d){var e,f,g,h,k,l;return B(function(m){switch(m.h){case 1:return f=(e=Error().stack)!=null?e:"",m.yield(Gp(),2);case 2:g=m.i;if(!g)throw h=Lo("openDbImpl",a,b),S("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),uo(h),h;wo(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Kp(a);ya(m,3);return m.yield(vp(k,g),5);case 5:return m.yield(pp(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=Aa(m),ya(m,7),m.yield(wp(k.actualName,
g),9);case 9:za(m,8);break;case 7:Aa(m);case 8:throw l;}})}
function Mp(a,b,c){c=c===void 0?{}:c;return Lp(a,b,!1,c)}
function Np(a,b,c){c=c===void 0?{}:c;return Lp(a,b,!0,c)}
function Op(a,b){b=b===void 0?{}:b;var c,d;return B(function(e){if(e.h==1)return e.yield(Gp(),2);if(e.h!=3){c=e.i;if(!c)return e.return();wo(a);d=Kp(a);return e.yield(qp(d.actualName,b),3)}return e.yield(wp(d.actualName,c),0)})}
function Pp(a,b,c){a=a.map(function(d){return B(function(e){return e.h==1?e.yield(qp(d.actualName,b),2):e.yield(wp(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Qp(){var a=a===void 0?{}:a;var b,c;return B(function(d){if(d.h==1)return d.yield(Gp(),2);if(d.h!=3){b=d.i;if(!b)return d.return();wo("LogsDatabaseV2");return d.yield(yp(b),3)}c=d.i;return d.yield(Pp(c,a,b),0)})}
function Rp(a,b){b=b===void 0?{}:b;var c;return B(function(d){if(d.h==1)return d.yield(Gp(),2);if(d.h!=3){c=d.i;if(!c)return d.return();wo(a);return d.yield(qp(a,b),3)}return d.yield(wp(a,c),0)})}
;function Sp(a,b){rp.call(this,a,b);this.options=b;wo(a)}
w(Sp,rp);function Tp(a,b){var c;return function(){c||(c=new Sp(a,b));return c}}
Sp.prototype.i=function(a,b,c){c=c===void 0?{}:c;return(this.options.shared?Np:Mp)(a,b,Object.assign({},c))};
Sp.prototype.delete=function(a){a=a===void 0?{}:a;return(this.options.shared?Rp:Op)(this.name,a)};
function Up(a,b){return Tp(a,b)}
;var Vp={},Wp=Up("ytGcfConfig",{Fb:(Vp.coldConfigStore={Lb:1},Vp.hotConfigStore={Lb:1},Vp),shared:!1,upgrade:function(a,b){b(1)&&(gp($o(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),gp($o(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Xp(a){return tp(Wp(),a)}
function Yp(a,b,c){var d,e,f;return B(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:V()},g.yield(Xp(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(bp(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Zp(a,b,c,d){var e,f,g;return B(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:V()},h.yield(Xp(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(bp(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function $p(a){var b,c;return B(function(d){return d.h==1?d.yield(Xp(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Zo(b,["coldConfigStore"],{mode:"readwrite",ka:!0},function(e){return mp(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function aq(a){var b,c;return B(function(d){return d.h==1?d.yield(Xp(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Zo(b,["hotConfigStore"],{mode:"readwrite",ka:!0},function(e){return mp(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function bq(){H.call(this);this.i=[];this.h=[];var a=F("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(A(a)),this.h=a):(this.h=[],E("yt.gcf.config.hotUpdateCallbacks",this.h))}
w(bq,H);bq.prototype.ba=function(){for(var a=y(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);b>=0&&c.splice(b,1)}this.i.length=0;H.prototype.ba.call(this)};function cq(){this.h=0;this.i=new bq}
function dq(){var a;return(a=F("yt.gcf.config.hotConfigGroup"))!=null?a:R("RAW_HOT_CONFIG_GROUP")}
function eq(a,b,c){var d,e,f;return B(function(g){switch(g.h){case 1:if(!S("start_client_gcf")){g.A(0);break}c&&(a.j=c,E("yt.gcf.config.hotConfigGroup",a.j||null));a.o(b);d=Fp();if(!d){g.A(3);break}if(c){g.A(4);break}return g.yield(aq(d),5);case 5:e=g.i,c=(f=e)==null?void 0:f.config;case 4:return g.yield(Yp(c,b,d),3);case 3:if(c)for(var h=c,k=y(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function fq(a,b,c){var d,e,f,g;return B(function(h){if(h.h==1){if(!S("start_client_gcf"))return h.A(0);a.coldHashData=b;E("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Fp())?c?h.A(4):h.yield($p(d),5):h.A(0)}h.h!=4&&(e=h.i,c=(f=e)==null?void 0:f.config);if(!c)return h.A(0);g=c.configData;return h.yield(Zp(c,b,g,d),0)})}
function gq(){if(!cq.instance){var a=new cq;cq.instance=a}a=cq.instance;var b=V()-a.h;if(!(a.h!==0&&b<T("send_config_hash_timer"))){b=F("yt.gcf.config.coldConfigData");var c=F("yt.gcf.config.hotHashData"),d=F("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=V());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
cq.prototype.o=function(a){this.hotHashData=a;E("yt.gcf.config.hotHashData",this.hotHashData||null)};function hq(){return"INNERTUBE_API_KEY"in $l&&"INNERTUBE_API_VERSION"in $l}
function iq(){return{innertubeApiKey:R("INNERTUBE_API_KEY"),innertubeApiVersion:R("INNERTUBE_API_VERSION"),Ae:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),wd:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Ch:R("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION"),Ce:R("INNERTUBE_CONTEXT_HL"),Be:R("INNERTUBE_CONTEXT_GL"),De:R("INNERTUBE_HOST_OVERRIDE")||"",Ee:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Dh:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:R("SERIALIZED_CLIENT_CONFIG_DATA")}}
function jq(a){var b={client:{hl:a.Ce,gl:a.Be,clientName:a.wd,clientVersion:a.innertubeContextClientVersion,configInfo:a.Ae}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=D.devicePixelRatio;c&&c!=1&&(b.client.screenDensityFloat=String(c));c=R("EXPERIMENTS_TOKEN","");c!==""&&(b.client.experimentsToken=c);c=Bm();c.length>0&&(b.request={internalExperimentFlags:c});c=a.wd;if((c==="WEB"||c==="MWEB"||c===1||c===2)&&b){var d;b.client.mainAppWebInfo=(d=b.client.mainAppWebInfo)!=
null?d:{};b.client.mainAppWebInfo.webDisplayMode=en()}(d=F("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(S("web_log_memory_total_kbytes")&&((e=D.navigator)==null?0:e.deviceMemory)){var f;e=(f=D.navigator)==null?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+e*1E6)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=zn())&&b&&(b.client.connectionType=a);S("web_log_effective_connection_type")&&
(a=An())&&b&&(b.client.effectiveConnectionType=a);S("start_client_gcf")&&(e=gq())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,b&&(b.client.configInfo=b.client.configInfo||{},a&&(b.client.configInfo.coldConfigData=a),f&&(b.client.configInfo.coldHashData=f),e&&(b.client.configInfo.hotHashData=e)));R("DELEGATED_SESSION_ID")&&!S("pageid_as_header_web")&&(b.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});!S("fill_delegate_context_in_gel_killswitch")&&(a=R("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=R("INNERTUBE_CONTEXT");var g;if(S("enable_persistent_device_token")&&(a==null?0:(g=a.client)==null?0:g.rolloutToken)){var h;b.client.rolloutToken=a==null?void 0:(h=a.client)==null?void 0:h.rolloutToken}g=Object;h=g.assign;a=b.client;f={};e=y(Object.entries(nm(R("DEVICE",""))));for(d=e.next();!d.done;d=e.next())c=y(d.value),d=c.next().value,c=c.next().value,d==="cbrand"?f.deviceMake=c:d==="cmodel"?f.deviceModel=c:d==="cbr"?f.browserName=
c:d==="cbrver"?f.browserVersion=c:d==="cos"?f.osName=c:d==="cosver"?f.osVersion=c:d==="cplatform"&&(f.platform=c);b.client=h.call(g,a,f);return b}
function kq(a,b,c){c=c===void 0?{}:c;var d={};R("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":R("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||R("AUTHORIZATION");b||(a?b="Bearer "+F("gapi.auth.getToken")().sh:(a=hn(gn()),S("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;var lq=typeof TextEncoder!=="undefined"?new TextEncoder:null,mq=lq?function(a){return lq.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};var nq={next:"wn_s",browse:"br_s",search:"sr_s",reel:"r_wrs",player:"ps_s"},oq={next:"wn_r",browse:"br_r",search:"sr_r",reel:"r_wrr",player:"ps_r"};function pq(a,b){this.version=a;this.args=b}
pq.prototype.serialize=function(){return{version:this.version,args:this.args}};function qq(a,b){this.topic=a;this.h=b}
qq.prototype.toString=function(){return this.topic};var rq=F("ytPubsub2Pubsub2Instance")||new N;N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.ac;N.prototype.publish=N.prototype.qb;N.prototype.clear=N.prototype.clear;E("ytPubsub2Pubsub2Instance",rq);var sq=F("ytPubsub2Pubsub2SubscribedKeys")||{};E("ytPubsub2Pubsub2SubscribedKeys",sq);var tq=F("ytPubsub2Pubsub2TopicToKeys")||{};E("ytPubsub2Pubsub2TopicToKeys",tq);var uq=F("ytPubsub2Pubsub2IsAsync")||{};E("ytPubsub2Pubsub2IsAsync",uq);
E("ytPubsub2Pubsub2SkipSubKey",null);function vq(a,b){var c=wq();c&&c.publish.call(c,a.toString(),a,b)}
function xq(a){var b=yq,c=wq();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=F("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(sq[d])try{if(f&&b instanceof qq&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Qd){var l=new h;h.Qd=l.version}var m=h.Qd}catch(z){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{m=Reflect;var n=m.construct;
var p=k.args,t=p.length;if(t>0){var v=Array(t);for(k=0;k<t;k++)v[k]=p[k];var x=v}else x=[];f=n.call(m,h,x)}catch(z){throw z.message="yt.pubsub2.Data.deserialize(): "+z.message,z;}}catch(z){throw z.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+z.message,z;}a.call(window,f)}catch(z){fm(z)}},uq[b.toString()]?F("yt.scheduler.instance")?Kj.pa(g):ym(g,0):g())});
sq[d]=!0;tq[b.toString()]||(tq[b.toString()]=[]);tq[b.toString()].push(d);return d}
function zq(){var a=Aq,b=xq(function(c){a.apply(void 0,arguments);Bq(b)});
return b}
function Bq(a){var b=wq();b&&(typeof a==="number"&&(a=[a]),Nb(a,function(c){b.unsubscribeByKey(c);delete sq[c]}))}
function wq(){return F("ytPubsub2Pubsub2Instance")}
;function Cq(a,b,c){c=c===void 0?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&vq("meta_logging_csi_event",{timerName:a,Vh:b})}
;var Dq=void 0,Eq=void 0;function Fq(){Eq||(Eq=zl(R("WORKER_SERIALIZATION_URL")));return Eq||void 0}
function Gq(){var a=Fq();Dq||a===void 0||(Dq=new Worker(kb(a),void 0));return Dq}
;var Hq=T("max_body_size_to_compress",5E5),Iq=T("min_body_size_to_compress",500),Jq=!0,Kq=0,Lq=0,Mq=T("compression_performance_threshold_lr",250),Nq=T("slow_compressions_before_abandon_count",4),Oq=!1,Pq=new Map,Qq=1,Rq=!0;function Sq(){if(typeof Worker==="function"&&Fq()&&!Oq){var a=function(c){c=c.data;if(c.op==="gzippedGelBatch"){var d=Pq.get(c.key);d&&(Tq(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),Pq.delete(c.key))}},b=Gq();
b&&(b.addEventListener("message",a),b.onerror=function(){Pq.clear()},Oq=!0)}}
function Uq(a,b,c,d,e){e=e===void 0?!1:e;var f={startTime:V(),ticks:{},infos:{}};if(Jq)try{var g=Vq(b);if(g!=null&&(g>Hq||g<Iq))d(a,c);else{if(S("gzip_gel_with_worker")&&(S("initial_gzip_use_main_thread")&&!Rq||!S("initial_gzip_use_main_thread"))){Oq||Sq();var h=Gq();if(h&&!e){Pq.set(Qq,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:Qq});Qq++;return}}var k=xl(mq(b));Tq(k,f,a,c,d)}}catch(l){gm(l),d(a,c)}else d(a,c)}
function Tq(a,b,c,d,e){Rq=!1;var f=V();b.ticks.gelc=f;Lq++;S("disable_compression_due_to_performance_degredation")&&f-b.startTime>=Mq&&(Kq++,S("abandon_compression_after_N_slow_zips")?Lq===T("compression_disable_point")&&Kq>Nq&&(Jq=!1):Jq=!1);Wq(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function Xq(a){var b=b===void 0?!1:b;var c=c===void 0?!1:c;var d=V(),e={startTime:d,ticks:{},infos:{}},f=b?F("yt.logging.gzipForFetch",!1):!0;if(Jq&&f){if(!a.body)return a;try{var g=c?a.body:typeof a.body==="string"?a.body:JSON.stringify(a.body);f=g;if(!c&&typeof g==="string"){var h=Vq(g);if(h!=null&&(h>Hq||h<Iq))return a;c=b?{level:1}:void 0;f=xl(mq(g),c);var k=V();e.ticks.gelc=k;if(b){Lq++;if((S("disable_compression_due_to_performance_degredation")||S("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Mq)if(Kq++,S("abandon_compression_after_N_slow_zips")||S("abandon_compression_after_N_slow_zips_lr")){b=Kq/Lq;var l=Nq/T("compression_disable_point");Lq>0&&Lq%T("compression_disable_point")===0&&b>=l&&(Jq=!1)}else Jq=!1;Wq(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(m){return gm(m),a}}else return a}
function Vq(a){try{return(new Blob(a.split(""))).size}catch(b){return gm(b),null}}
function Wq(a){S("gel_compression_csi_killswitch")||!S("log_gel_compression_latency")&&!S("log_gel_compression_latency_lr")||Cq("gel_compression",a,{sampleRate:.1})}
;function Yq(a){a=Object.assign({},a);delete a.Authorization;var b=cg();if(b){var c=new Oj;c.update(R("INNERTUBE_API_KEY"));c.update(b);a.hash=pd(c.digest(),3)}return a}
;var Zq;function $q(){Zq||(Zq=new ko("yt.innertube"));return Zq}
function ar(a,b,c,d){if(d)return null;d=$q().get("nextId",!0)||1;var e=$q().get("requests",!0)||{};e[d]={method:a,request:b,authState:Yq(c),requestTime:Math.round(V())};$q().set("nextId",d+1,86400,!0);$q().set("requests",e,86400,!0);return d}
function br(a){var b=$q().get("requests",!0)||{};delete b[a];$q().set("requests",b,86400,!0)}
function cr(a){var b=$q().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(Math.round(V())-d.requestTime<6E4)){var e=d.authState,f=Yq(kq(!1));qg(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(V())),dr(a,d.method,e,{}));delete b[c]}}$q().set("requests",b,86400,!0)}}
;function er(a){this.dc=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.xb=function(){};
this.now=Date.now;this.Pb=!1;var b;this.Md=(b=a.Md)!=null?b:100;var c;this.Hd=(c=a.Hd)!=null?c:1;var d;this.Fd=(d=a.Fd)!=null?d:2592E6;var e;this.Ed=(e=a.Ed)!=null?e:12E4;var f;this.Gd=(f=a.Gd)!=null?f:5E3;var g;this.V=(g=a.V)!=null?g:void 0;this.jc=!!a.jc;var h;this.hc=(h=a.hc)!=null?h:.1;var k;this.xc=(k=a.xc)!=null?k:10;a.handleError&&(this.handleError=a.handleError);a.xb&&(this.xb=a.xb);a.Pb&&(this.Pb=a.Pb);a.dc&&(this.dc=a.dc);this.W=a.W;this.Ca=a.Ca;this.ga=a.ga;this.fa=a.fa;this.sendFn=a.sendFn;
this.Wc=a.Wc;this.Tc=a.Tc;fr(this)&&(!this.W||this.W("networkless_logging"))&&gr(this)}
function gr(a){fr(a)&&!a.Pb&&(a.h=!0,a.jc&&Math.random()<=a.hc&&a.ga.de(a.V),hr(a),a.fa.ta()&&a.Zb(),a.fa.listen(a.Wc,a.Zb.bind(a)),a.fa.listen(a.Tc,a.od.bind(a)))}
r=er.prototype;r.writeThenSend=function(a,b){var c=this;b=b===void 0?{}:b;if(fr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ga.set(d,this.V).then(function(e){d.id=e;c.fa.ta()&&ir(c,d)}).catch(function(e){ir(c,d);
jr(c,e)})}else this.sendFn(a,b)};
r.sendThenWrite=function(a,b,c){var d=this;b=b===void 0?{}:b;if(fr(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.W&&this.W("nwl_skip_retry")&&(e.skipRetry=c);if(this.fa.ta()||this.W&&this.W("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return B(function(k){if(k.h==1)return k.yield(d.ga.set(e,d.V).catch(function(l){jr(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.ga.set(e,this.V).catch(function(g){d.sendFn(a,b,e.skipRetry);
jr(d,g)})}else this.sendFn(a,b,this.W&&this.W("nwl_skip_retry")&&c)};
r.sendAndWrite=function(a,b){var c=this;b=b===void 0?{}:b;if(fr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){d.id!==void 0?c.ga.wb(d.id,c.V):e=!0;c.fa.kb&&c.W&&c.W("vss_network_hint")&&c.fa.kb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.ga.set(d,this.V).then(function(g){d.id=g;e&&c.ga.wb(d.id,c.V)}).catch(function(g){jr(c,g)})}else this.sendFn(a,b,void 0,!0)};
r.Zb=function(){var a=this;if(!fr(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Ca.pa(function(){var b;return B(function(c){if(c.h==1)return c.yield(a.ga.td("NEW",a.V),2);if(c.h!=3)return b=c.i,b?c.yield(ir(a,b),3):(a.od(),c.return());a.i&&(a.i=0,a.Zb());c.h=0})},this.Md))};
r.od=function(){this.Ca.qa(this.i);this.i=0};
function ir(a,b){var c;return B(function(d){switch(d.h){case 1:if(!fr(a))throw Error("IndexedDB is not supported: immediateSend");if(b.id===void 0){d.A(2);break}return d.yield(a.ga.Ie(b.id,a.V),3);case 3:(c=d.i)||a.xb(Error("The request cannot be found in the database."));case 2:if(kr(a,b,a.Fd)){d.A(4);break}a.xb(Error("Networkless Logging: Stored logs request expired age limit"));if(b.id===void 0){d.A(5);break}return d.yield(a.ga.wb(b.id,a.V),5);case 5:return d.return();case 4:b.skipRetry||(b=lr(a,
b));if(!b){d.A(0);break}if(!b.skipRetry||b.id===void 0){d.A(8);break}return d.yield(a.ga.wb(b.id,a.V),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function lr(a,b){if(!fr(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return B(function(m){switch(m.h){case 1:g=mr(f);(h=nr(f))&&a.W&&a.W("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.W&&a.W("nwl_consider_error_code")&&g||a.W&&!a.W("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.xc)){m.A(2);break}if(!a.fa.Cc){m.A(3);break}return m.yield(a.fa.Cc(),3);case 3:if(a.fa.ta()){m.A(2);break}c(e,f);if(!a.W||!a.W("nwl_consider_error_code")||((k=b)==null?void 0:k.id)===void 0){m.A(6);
break}return m.yield(a.ga.Xc(b.id,a.V,!1),6);case 6:return m.return();case 2:if(a.W&&a.W("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.xc)return m.return();a.potentialEsfErrorCounter++;if(((l=b)==null?void 0:l.id)===void 0){m.A(8);break}return b.sendCount<a.Hd?m.yield(a.ga.Xc(b.id,a.V,!0,h?!1:void 0),12):m.yield(a.ga.wb(b.id,a.V),8);case 12:a.Ca.pa(function(){a.fa.ta()&&a.Zb()},a.Gd);
case 8:c(e,f),m.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return B(function(h){if(h.h==1)return((g=b)==null?void 0:g.id)===void 0?h.A(2):h.yield(a.ga.wb(b.id,a.V),2);a.fa.kb&&a.W&&a.W("vss_network_hint")&&a.fa.kb(!0);d(e,f);h.h=0})};
return b}
function kr(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function hr(a){if(!fr(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ga.td("QUEUED",a.V).then(function(b){b&&!kr(a,b,a.Ed)?a.Ca.pa(function(){return B(function(c){if(c.h==1)return b.id===void 0?c.A(2):c.yield(a.ga.Xc(b.id,a.V),2);hr(a);c.h=0})}):a.fa.ta()&&a.Zb()})}
function jr(a,b){a.Td&&!a.fa.ta()?a.Td(b):a.handleError(b)}
function fr(a){return!!a.V||a.dc}
function mr(a){var b;return(a=a==null?void 0:(b=a.error)==null?void 0:b.code)&&a>=400&&a<=599?!1:!0}
function nr(a){var b;a=a==null?void 0:(b=a.error)==null?void 0:b.code;return!(a!==400&&a!==415)}
;var or;
function pr(){if(or)return or();var a={};or=Up("LogsDatabaseV2",{Fb:(a.LogsRequestsStore={Lb:2},a),shared:!1,upgrade:function(b,c,d){c(2)&&$o(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),gp(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return or()}
;function qr(a){return tp(pr(),a)}
function rr(a,b){var c,d,e,f;return B(function(g){if(g.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(qr(b),2);if(g.h!=3)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:R("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(bp(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=V();sr(c);return g.return(f)})}
function tr(a,b){var c,d,e,f,g,h,k,l;return B(function(m){if(m.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},m.yield(qr(b),2);if(m.h!=3)return d=m.i,e=R("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,V()],h=IDBKeyRange.bound(f,g),k="prev",S("use_fifo_for_networkless")&&(k="next"),l=void 0,m.yield(Zo(d,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(n){return mp(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:k},
function(p){p.getValue()&&(l=p.getValue(),a==="NEW"&&(l.status="QUEUED",p.update(l)))})}),3);
c.ticks.tc=V();sr(c);return m.return(l)})}
function ur(a,b){var c;return B(function(d){if(d.h==1)return d.yield(qr(b),2);c=d.i;return d.return(Zo(c,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Vo(f.h.put(g,void 0)).then(function(){return g})})}))})}
function vr(a,b,c,d){c=c===void 0?!0:c;var e;return B(function(f){if(f.h==1)return f.yield(qr(b),2);e=f.i;return f.return(Zo(e,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),d!==void 0&&(k.options.compress=d),Vo(h.h.put(k,void 0)).then(function(){return k})):Po.resolve(void 0)})}))})}
function wr(a,b){var c;return B(function(d){if(d.h==1)return d.yield(qr(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function xr(a){var b,c;return B(function(d){if(d.h==1)return d.yield(qr(a),2);b=d.i;c=V()-2592E6;return d.yield(Zo(b,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(e){return ip(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return jp(f)})})}),0)})}
function yr(){B(function(a){return a.yield(Qp(),0)})}
function sr(a){S("nwl_csi_killswitch")||Cq("networkless_performance",a,{sampleRate:1})}
;var zr={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrCowatchPartyEvent:492,vrCowatchUserStartOrJoinEvent:504,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,
mbsConnectionInitiated:138,mbsPlaybackInitiated:139,mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,
kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,
transactionFlowPaymentSubmitted:460,transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,
ypcPauseFlowSucceeded:190,ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,
ypcFamilyCreateFlowCancelled:259,ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,
accountRegistryChange:226,userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,
musicSideloadedPlaylistServiceCalled:246,embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,apiTest:270,
yongleUsbSetup:271,touStrikeInterstitialEvent:272,liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,
notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,
tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,
iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,
mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,
mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,
clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,
mdeQosEvent:510,mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,mdeExporterEvent:497,genericClientExperimentEvent:423,homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,externalVideoShareToYoutubeAttempt:501,parentCodeEvent:502,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,
mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,
cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,producerProjectElementAdded:453,producerProjectElementRemoved:454,producerAppStateChange:509,producerProjectDiskInsufficientExportFailure:516,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,
miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485,offlineDeleteEvent:486,crossDeviceNotificationTransfer:487,androidIntentEvent:488,unpluggedAmbientInterludesCounterfactualEvent:489,keyPlaysPlayback:490,
shortsCreationFallbackEvent:493,vssData:491,castMatch:494,miniAppPerformanceMetrics:495,userFeedbackEvent:496,kidsGuestSessionMismatch:498,musicSideloadedPlaylistMigrationEvent:499,sleepTimerSessionFinishEvent:500,watchEpPromoConflict:503,innertubeResponseCacheMetrics:505,miniAppAdEvent:506,dataPlanUpsellEvent:507,producerProjectRenamed:508,producerMediaSelectionEvent:511,embedsAutoplayStatusChanged:512,remoteConnectEvent:513,connectedSessionMisattributionEvent:514,producerProjectElementModified:515};var Ar={},Br=Up("ServiceWorkerLogsDatabase",{Fb:(Ar.SWHealthLog={Lb:1},Ar),shared:!0,upgrade:function(a,b){b(1)&&gp($o(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function Cr(a){return tp(Br(),a)}
function Dr(a){var b,c;B(function(d){if(d.h==1)return d.yield(Cr(a),2);b=d.i;c=V()-2592E6;return d.yield(Zo(b,["SWHealthLog"],{mode:"readwrite",ka:!0},function(e){return ip(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return jp(f)})})}),0)})}
function Er(a){var b;return B(function(c){if(c.h==1)return c.yield(Cr(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var Fr={},Gr=0;function Hr(a){var b=b===void 0?{}:b;var c=new Image,d=""+Gr++;Fr[d]=c;c.onload=c.onerror=function(){delete Fr[d]};
b.Rh&&(c.referrerPolicy="no-referrer");c.src=a}
;var Ir;function Jr(){Ir||(Ir=new ko("yt.offline"));return Ir}
function Kr(a){if(S("offline_error_handling")){var b=Jr().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Jr().set("errors",b,2592E3,!0)}}
;function Lr(){this.h=new Map;this.i=!1}
function Mr(){if(!Lr.instance){var a=F("yt.networkRequestMonitor.instance")||new Lr;E("yt.networkRequestMonitor.instance",a);Lr.instance=a}return Lr.instance}
Lr.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Lr.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:a===!1&&this.i?!0:null};
Lr.prototype.removeParams=function(a){return a.split("?")[0]};
Lr.prototype.removeParams=Lr.prototype.removeParams;Lr.prototype.isEndpointCFR=Lr.prototype.isEndpointCFR;Lr.prototype.requestComplete=Lr.prototype.requestComplete;Lr.getInstance=Mr;function Nr(){Th.call(this);var a=this;this.j=!1;this.h=Jj();this.h.listen("networkstatus-online",function(){if(a.j&&S("offline_error_handling")){var b=Jr().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new U(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;fm(d)}Jr().set("errors",{},2592E3,!0)}}})}
w(Nr,Th);function Or(){if(!Nr.instance){var a=F("yt.networkStatusManager.instance")||new Nr;E("yt.networkStatusManager.instance",a);Nr.instance=a}return Nr.instance}
r=Nr.prototype;r.ta=function(){return this.h.ta()};
r.kb=function(a){this.h.h=a};
r.xe=function(){var a=window.navigator.onLine;return a===void 0?!0:a};
r.ne=function(){this.j=!0};
r.listen=function(a,b){return this.h.listen(a,b)};
r.Cc=function(a){a=Hj(this.h,a);a.then(function(b){S("use_cfr_monitor")&&Mr().requestComplete("generate_204",b)});
return a};
Nr.prototype.sendNetworkCheckRequest=Nr.prototype.Cc;Nr.prototype.listen=Nr.prototype.listen;Nr.prototype.enableErrorFlushing=Nr.prototype.ne;Nr.prototype.getWindowStatus=Nr.prototype.xe;Nr.prototype.networkStatusHint=Nr.prototype.kb;Nr.prototype.isNetworkAvailable=Nr.prototype.ta;Nr.getInstance=Or;function Pr(a){a=a===void 0?{}:a;Th.call(this);var b=this;this.h=this.u=0;this.j=Or();var c=F("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){Qr(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Qr(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){Uh(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Uh(b,"publicytnetworkstatus-offline")})))}
w(Pr,Th);Pr.prototype.ta=function(){var a=F("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Pr.prototype.kb=function(a){var b=F("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Pr.prototype.Cc=function(a){var b=this,c;return B(function(d){c=F("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return S("skip_network_check_if_cfr")&&Mr().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.kb(((f=window.navigator)==null?void 0:f.onLine)||!0);e(b.ta())})):c?d.return(c(a)):d.return(!0)})};
function Qr(a,b){a.rateLimit?a.h?(Kj.qa(a.u),a.u=Kj.pa(function(){a.o!==b&&(Uh(a,b),a.o=b,a.h=V())},a.rateLimit-(V()-a.h))):(Uh(a,b),a.o=b,a.h=V()):Uh(a,b)}
;var Rr;function Sr(){var a=er.call;Rr||(Rr=new Pr({Ih:!0,zh:!0}));a.call(er,this,{ga:{de:xr,wb:wr,td:tr,Ie:ur,Xc:vr,set:rr},fa:Rr,handleError:function(b,c,d){var e,f=d==null?void 0:(e=d.error)==null?void 0:e.code;if(f===400||f===415){var g;gm(new U(b.message,c,d==null?void 0:(g=d.error)==null?void 0:g.code),void 0,void 0,void 0,!0)}else fm(b)},
xb:gm,sendFn:Tr,now:V,Td:Kr,Ca:jo(),Wc:"publicytnetworkstatus-online",Tc:"publicytnetworkstatus-offline",jc:!0,hc:.1,xc:T("potential_esf_error_limit",10),W:S,Pb:!(Bn()&&Ur())});this.j=new mj;S("networkless_immediately_drop_all_requests")&&yr();Rp("LogsDatabaseV2")}
w(Sr,er);function Vr(){var a=F("yt.networklessRequestController.instance");a||(a=new Sr,E("yt.networklessRequestController.instance",a),S("networkless_logging")&&Gp().then(function(b){a.V=b;gr(a);a.j.resolve();a.jc&&Math.random()<=a.hc&&a.V&&Dr(a.V);S("networkless_immediately_drop_sw_health_store")&&Wr(a)}));
return a}
Sr.prototype.writeThenSend=function(a,b){b||(b={});b=Xr(a,b);Bn()||(this.h=!1);er.prototype.writeThenSend.call(this,a,b)};
Sr.prototype.sendThenWrite=function(a,b,c){b||(b={});b=Xr(a,b);Bn()||(this.h=!1);er.prototype.sendThenWrite.call(this,a,b,c)};
Sr.prototype.sendAndWrite=function(a,b){b||(b={});b=Xr(a,b);Bn()||(this.h=!1);er.prototype.sendAndWrite.call(this,a,b)};
Sr.prototype.awaitInitialization=function(){return this.j.promise};
function Wr(a){var b;B(function(c){if(!a.V)throw b=Lo("clearSWHealthLogsDb"),b;return c.return(Er(a.V).catch(function(d){a.handleError(d)}))})}
function Tr(a,b,c,d){d=d===void 0?!1:d;b=S("web_fp_via_jspb")?Object.assign({},b):b;S("use_cfr_monitor")&&Yr(a,b);if(S("use_request_time_ms_header"))b.headers&&rm(a)&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));else{var e;if((e=b.postParams)==null?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(V())}if(c&&Object.keys(b).length===0){var f=f===void 0?"":f;var g=g===void 0?!1:g;var h=h===void 0?!1:h;if(a)if(f)Fm(a,void 0,"POST",f,void 0);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",
!1)||h)Fm(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new pc({url:a});if(k.u?typeof k.i!=="string"||k.i.length===0?0:{version:3,ke:k.i,ae:oc(k.j,"act=1","ri=1",qc(k))}:k.M&&{version:4,ke:oc(k.j,"dct=1","suid="+k.o,""),ae:oc(k.j,"act=1","ri=1","suid="+k.o)}){var l=ac(bc(5,a)),m;if(!(m=!l||!l.endsWith("/aclk"))){var n=a.search(kc),p=jc(a,0,"ri",n);if(p<0)var t=null;else{var v=a.indexOf("&",p);if(v<0||v>n)v=n;t=decodeURIComponent(a.slice(p+3,v!==-1?v:0).replace(/\+/g," "))}m=t!=="1"}var x=
!m;break b}}catch(G){}x=!1}if(x){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var z=!0;break b}}catch(G){}z=!1}c=z?!0:!1}else c=!1;c||Hr(a)}}else b.compress?b.postBody?(typeof b.postBody!=="string"&&(b.postBody=JSON.stringify(b.postBody)),Uq(a,b.postBody,b,Jm,d)):Uq(a,JSON.stringify(b.postParams),b,Im,d):Jm(a,b)}
function Xr(a,b){S("use_event_time_ms_header")&&rm(a)&&(b.headers||(b.headers={}),b.headers["X-Goog-Event-Time"]=JSON.stringify(Math.round(V())));return b}
function Yr(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Mr().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Mr().requestComplete(a,!0);d(e,f)}}
function Ur(){return cc(document.location.toString())!=="www.youtube-nocookie.com"}
;var Zr=!1,$r=D.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Zr};E("ytNetworklessLoggingInitializationOptions",$r);function as(){var a;B(function(b){if(b.h==1)return b.yield(Gp(),2);a=b.i;if(!a||!Bn()&&!S("nwl_init_require_datasync_id_killswitch")||!Ur())return b.A(0);Zr=!0;$r.isNwlInitialized=Zr;return b.yield(Vr().awaitInitialization(),0)})}
;function bs(a){var b=this;this.config_=null;a?this.config_=a:hq()&&(this.config_=iq());En(function(){cr(b)},5E3)}
bs.prototype.isReady=function(){!this.config_&&hq()&&(this.config_=iq());return!!this.config_};
function dr(a,b,c,d){function e(n){n=n===void 0?!1:n;var p;if(d.retry&&h!="www.youtube-nocookie.com"&&(n||S("skip_ls_gel_retry")||g.headers["Content-Type"]!=="application/json"||(p=ar(b,c,l,k)),p)){var t=g.onSuccess,v=g.onFetchSuccess;g.onSuccess=function(G,J){br(p);t(G,J)};
c.onFetchSuccess=function(G,J){br(p);v(G,J)}}try{if(n&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?Vr().writeThenSend(m,g):Vr().sendAndWrite(m,g);
else if(d.compress){var x=!d.networklessOptions.writeThenSend;if(g.postBody){var z=g.postBody;typeof z!=="string"&&(z=JSON.stringify(g.postBody));Uq(m,z,g,Jm,x)}else Uq(m,JSON.stringify(g.postParams),g,Im,x)}else S("web_all_payloads_via_jspb")?Jm(m,g):Im(m,g)}catch(G){if(G.name==="InvalidAccessError")p&&(br(p),p=0),gm(Error("An extension is blocking network request."));else throw G;}p&&En(function(){cr(a)},5E3)}
!R("VISITOR_DATA")&&b!=="visitor_id"&&Math.random()<.01&&gm(new U("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new U("innertube xhrclient not ready",b,c,d);fm(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(n,p){if(d.onSuccess)d.onSuccess(p)},
onFetchSuccess:function(n){if(d.onSuccess)d.onSuccess(n)},
onError:function(n,p){if(d.onError)d.onError(p)},
onFetchError:function(n){if(d.onError)d.onError(n)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.De)&&(h=f);var k=a.config_.Ee||!1,l=kq(k,h,d);Object.assign(g.headers,l);g.headers.Authorization&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var m=pm(""+h+("/youtubei/"+a.config_.innertubeApiVersion+"/"+b),{alt:"json"});(F("ytNetworklessLoggingInitializationOptions")?$r.isNwlInitialized:Zr)?Ep().then(function(n){e(n)}):e(!1)}
;var cs=0,ds=id?"webkit":hd?"moz":fd?"ms":ed?"o":"";E("ytDomDomGetNextId",F("ytDomDomGetNextId")||function(){return++cs});var es={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function gs(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in es||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&c.nodeType==3&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else this.type=="mouseover"?d=a.fromElement:this.type=="mouseout"&&(d=a.toElement);this.relatedTarget=d;this.clientX=a.clientX!=void 0?a.clientX:a.pageX;this.clientY=a.clientY!=void 0?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||(this.type=="keypress"?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function hs(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
gs.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
gs.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
gs.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var mg=D.ytEventsEventsListeners||{};E("ytEventsEventsListeners",mg);var ms=D.ytEventsEventsCounter||{count:0};E("ytEventsEventsCounter",ms);
function ns(a,b,c,d){d=d===void 0?{}:d;a.addEventListener&&(b!="mouseenter"||"onmouseenter"in document?b!="mouseleave"||"onmouseenter"in document?b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return lg(function(e){var f=typeof e[4]==="boolean"&&e[4]==!!d,g=Ra(e[4])&&Ra(d)&&qg(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function ps(a,b,c,d){d=d===void 0?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=ns(a,b,c,d);if(e)return e;e=++ms.count+"";var f=!(b!="mouseenter"&&b!="mouseleave"||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new gs(h);if(!Ag(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new gs(h);
h.currentTarget=a;return c.call(a,h)};
g=em(g);a.addEventListener?(b=="mouseenter"&&f?b="mouseover":b=="mouseleave"&&f?b="mouseout":b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),qs()||typeof d==="boolean"?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);mg[e]=[a,b,c,g,d];return e}
function rs(a){a&&(typeof a=="string"&&(a=[a]),Nb(a,function(b){if(b in mg){var c=mg[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?qs()||typeof c==="boolean"?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete mg[b]}}))}
var qs=ii(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});function ss(a){this.G=a;this.h=null;this.o=0;this.D=null;this.u=0;this.i=[];for(a=0;a<4;a++)this.i.push(0);this.j=0;this.U=ps(window,"mousemove",Xa(this.Y,this));a=Xa(this.P,this);typeof a==="function"&&(a=em(a));this.Z=window.setInterval(a,25)}
bb(ss,H);ss.prototype.Y=function(a){a.h===void 0&&hs(a);var b=a.h;a.i===void 0&&hs(a);this.h=new ig(b,a.i)};
ss.prototype.P=function(){if(this.h){var a=V();if(this.o!=0){var b=this.D,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.i[this.j]=Math.abs((d-this.u)/this.u)>.5?1:0;for(c=b=0;c<4;c++)b+=this.i[c]||0;b>=3&&this.G();this.u=d}this.o=a;this.D=this.h;this.j=(this.j+1)%4}};
ss.prototype.ba=function(){window.clearInterval(this.Z);rs(this.U)};var ts={};
function us(a){var b=a===void 0?{}:a;a=b.Te===void 0?!1:b.Te;b=b.oe===void 0?!0:b.oe;if(F("_lact",window)==null){var c=parseInt(R("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;E("_lact",c,window);E("_fact",c,window);c==-1&&vs();ps(document,"keydown",vs);ps(document,"keyup",vs);ps(document,"mousedown",vs);ps(document,"mouseup",vs);a?ps(window,"touchmove",function(){ws("touchmove",200)},{passive:!0}):(ps(window,"resize",function(){ws("resize",200)}),b&&ps(window,"scroll",function(){ws("scroll",200)}));
new ss(function(){ws("mouse",100)});
ps(document,"touchstart",vs,{passive:!0});ps(document,"touchend",vs,{passive:!0})}}
function ws(a,b){ts[a]||(ts[a]=!0,Kj.pa(function(){vs();ts[a]=!1},b))}
function vs(){F("_lact",window)==null&&us();var a=Date.now();E("_lact",a,window);F("_fact",window)==-1&&E("_fact",a,window);(a=F("ytglobal.ytUtilActivityCallback_"))&&a()}
function xs(){var a=F("_lact",window);return a==null?-1:Math.max(Date.now()-a,0)}
;var ys=D.ytPubsubPubsubInstance||new N,zs=D.ytPubsubPubsubSubscribedKeys||{},As=D.ytPubsubPubsubTopicToKeys||{},Bs=D.ytPubsubPubsubIsSynchronous||{};function Cs(a,b){var c=Ds();if(c&&b){var d=c.subscribe(a,function(){function e(){zs[d]&&b.apply&&typeof b.apply=="function"&&b.apply(window,f)}
var f=arguments;try{Bs[a]?e():ym(e,0)}catch(g){fm(g)}},void 0);
zs[d]=!0;As[a]||(As[a]=[]);As[a].push(d);return d}return 0}
function Es(a){var b=Ds();b&&(typeof a==="number"?a=[a]:typeof a==="string"&&(a=[parseInt(a,10)]),Nb(a,function(c){b.unsubscribeByKey(c);delete zs[c]}))}
function Fs(a,b){var c=Ds();c&&c.publish.apply(c,arguments)}
function Gs(a){var b=Ds();if(b)if(b.clear(a),a)Hs(a);else for(var c in As)Hs(c)}
function Ds(){return D.ytPubsubPubsubInstance}
function Hs(a){As[a]&&(a=As[a],Nb(a,function(b){zs[b]&&delete zs[b]}),a.length=0)}
N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.ac;N.prototype.publish=N.prototype.qb;N.prototype.clear=N.prototype.clear;E("ytPubsubPubsubInstance",ys);E("ytPubsubPubsubTopicToKeys",As);E("ytPubsubPubsubIsSynchronous",Bs);E("ytPubsubPubsubSubscribedKeys",zs);var Is=Symbol("injectionDeps");function Js(a){this.name=a}
Js.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Ks(a){this.key=a}
function Ls(){this.i=new Map;this.j=new Map;this.h=new Map}
function Ms(a,b){a.i.set(b.zc,b);var c=a.j.get(b.zc);if(c)try{c.Qh(a.resolve(b.zc))}catch(d){c.Oh(d)}}
Ls.prototype.resolve=function(a){return a instanceof Ks?Ns(this,a.key,[],!0):Ns(this,a,[])};
function Ns(a,b,c,d){d=d===void 0?!1:d;if(c.indexOf(b)>-1)throw Error("Deps cycle for: "+b);if(a.h.has(b))return a.h.get(b);if(!a.i.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.i.get(b);c.push(b);if(d.Pd!==void 0)var e=d.Pd;else if(d.Af)e=d[Is]?Os(a,d[Is],c):[],e=d.Af.apply(d,A(e));else if(d.Od){e=d.Od;var f=e[Is]?Os(a,e[Is],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(A(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Uh||a.h.set(b,e);return e}
function Os(a,b,c){return b?b.map(function(d){return d instanceof Ks?Ns(a,d.key,c,!0):Ns(a,d,c)}):[]}
;var Ps;function Qs(){Ps||(Ps=new Ls);return Ps}
;var Rs=window;function Ss(){var a,b;return"h5vcc"in Rs&&((a=Rs.h5vcc.traceEvent)==null?0:a.traceBegin)&&((b=Rs.h5vcc.traceEvent)==null?0:b.traceEnd)?1:"performance"in Rs&&Rs.performance.mark&&Rs.performance.measure?2:0}
function Ts(a){var b=Ss();switch(b){case 1:Rs.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Rs.performance.mark(a+"-start");break;case 0:break;default:yb(b,"unknown trace type")}}
function Us(a){var b=Ss();switch(b){case 1:Rs.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:b=a+"-start";var c=a+"-end";Rs.performance.mark(c);Rs.performance.measure(a,b,c);break;case 0:break;default:yb(b,"unknown trace type")}}
;var Vs=S("web_enable_lifecycle_monitoring")&&Ss()!==0,Ws=S("web_enable_lifecycle_monitoring");function Xs(a){var b,c;(c=(b=window).onerror)==null||c.call(b,a.message,"",0,0,a)}
;function Ys(a){var b=this;var c=c===void 0?0:c;var d=d===void 0?jo():d;this.j=c;this.scheduler=d;this.i=new mj;this.h=a;for(a={ib:0};a.ib<this.h.length;a={wc:void 0,ib:a.ib},a.ib++)a.wc=this.h[a.ib],c=function(e){return function(){e.wc.Mc();b.h[e.ib].yc=!0;b.h.every(function(f){return f.yc===!0})&&b.i.resolve()}}(a),d=this.getPriority(a.wc),d=this.scheduler.Ra(c,d),this.h[a.ib]=Object.assign({},a.wc,{Mc:c,
jobId:d})}
function Zs(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=y(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],c.jobId===void 0||c.yc||(a.scheduler.qa(c.jobId),a.scheduler.Ra(c.Mc,10))}
Ys.prototype.cancel=function(){for(var a=y(this.h),b=a.next();!b.done;b=a.next())b=b.value,b.jobId===void 0||b.yc||this.scheduler.qa(b.jobId),b.yc=!0;this.i.resolve()};
Ys.prototype.getPriority=function(a){var b;return(b=a.priority)!=null?b:this.j};function $s(a){this.state=a;this.plugins=[];this.o=void 0;this.D={};Vs&&Ts(this.state)}
r=$s.prototype;r.install=function(a){this.plugins.push(a);return this};
r.uninstall=function(){var a=this;C.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);b>-1&&a.plugins.splice(b,1)})};
r.transition=function(a,b){var c=this;Vs&&Us(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Zs(this.j),this.j=void 0);at(this,a,b);this.state=a;Vs&&Ts(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(bt(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function bt(a,b){var c=b.filter(function(e){return ct(a,e)===10}),d=b.filter(function(e){return ct(a,e)!==10});
return a.D.Th?function(){var e=C.apply(0,arguments);return B(function(f){if(f.h==1)return f.yield(a.Ze.apply(a,[c].concat(A(e))),2);a.Jd.apply(a,[d].concat(A(e)));f.h=0})}:function(){var e=C.apply(0,arguments);
a.af.apply(a,[c].concat(A(e)));a.Jd.apply(a,[d].concat(A(e)))}}
r.af=function(a){for(var b=C.apply(1,arguments),c=jo(),d=y(a),e=d.next(),f={};!e.done;f={Qb:void 0},e=d.next())f.Qb=e.value,c.Jb(function(g){return function(){dt(g.Qb.name);et(function(){return g.Qb.callback.apply(g.Qb,A(b))});
ft(g.Qb.name)}}(f))};
r.Ze=function(a){var b=C.apply(1,arguments),c,d,e,f,g;return B(function(h){h.h==1&&(c=jo(),d=y(a),e=d.next(),f={});if(h.h!=3){if(e.done)return h.A(0);f.Xa=e.value;f.cc=void 0;g=function(k){return function(){dt(k.Xa.name);var l=et(function(){return k.Xa.callback.apply(k.Xa,A(b))});
fe(l)?k.cc=S("web_lifecycle_error_handling_killswitch")?l.then(function(){ft(k.Xa.name)}):l.then(function(){ft(k.Xa.name)},function(m){Xs(m);
ft(k.Xa.name)}):ft(k.Xa.name)}}(f);
c.Jb(g);return f.cc?h.yield(f.cc,3):h.A(3)}f={Xa:void 0,cc:void 0};e=d.next();return h.A(2)})};
r.Jd=function(a){var b=C.apply(1,arguments),c=this,d=a.map(function(e){return{Mc:function(){dt(e.name);et(function(){return e.callback.apply(e,A(b))});
ft(e.name)},
priority:ct(c,e)}});
d.length&&(this.j=new Ys(d))};
function ct(a,b){var c,d;return(d=(c=a.o)!=null?c:b.priority)!=null?d:0}
function dt(a){Vs&&a&&Ts(a)}
function ft(a){Vs&&a&&Us(a)}
function at(a,b,c){Ws&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
fa.Object.defineProperties($s.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});
function et(a){if(S("web_lifecycle_error_handling_killswitch"))return a();try{return a()}catch(b){Xs(b)}}
;function gt(a){$s.call(this,a===void 0?"none":a);this.h=null;this.o=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.u},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var ht;w(gt,$s);gt.prototype.i=function(a,b){var c=this;this.h=En(function(){c.currentState==="application_navigating"&&c.transition("none")},5E3);
a(b==null?void 0:b.event)};
gt.prototype.u=function(a,b){this.h&&(Kj.qa(this.h),this.h=null);a(b==null?void 0:b.event)};
function jt(){ht||(ht=new gt);return ht}
;var kt=[];E("yt.logging.transport.getScrapedGelPayloads",function(){return kt});function lt(){this.store={};this.h={}}
lt.prototype.storePayload=function(a,b){a=mt(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);S("more_accurate_gel_parser")&&(b=new CustomEvent("TRANSPORTING_NEW_EVENT"),window.dispatchEvent(b));return a};
lt.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=nt(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,A(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,A(this.store[b[d]].splice(0,a.sizeLimit))));(a==null?0:a.sizeLimit)&&c.length<(a==null?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,A(this.smartExtractMatchingEntries(a))));return c};
lt.prototype.extractMatchingEntries=function(a){a=nt(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,A(this.store[a[c]])),delete this.store[a[c]]);return b};
lt.prototype.getSequenceCount=function(a){a=nt(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=((d=this.store[a[c]])==null?void 0:d.length)||0}return b};
function nt(a,b){var c=mt(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(d.length<=1&&mt(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(ot(b.auth,g[0])){var h=b.isJspb;ot(h===void 0?"undefined":h?"true":"false",g[1])&&ot(b.cttAuthInfo,g[2])&&(h=b.tier,h=h===void 0?"undefined":JSON.stringify(h),ot(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function ot(a,b){return a===void 0||a==="undefined"?!0:a===b}
lt.prototype.getSequenceCount=lt.prototype.getSequenceCount;lt.prototype.extractMatchingEntries=lt.prototype.extractMatchingEntries;lt.prototype.smartExtractMatchingEntries=lt.prototype.smartExtractMatchingEntries;lt.prototype.storePayload=lt.prototype.storePayload;function mt(a){return[a.auth===void 0?"undefined":a.auth,a.isJspb===void 0?"undefined":a.isJspb,a.cttAuthInfo===void 0?"undefined":a.cttAuthInfo,a.tier===void 0?"undefined":a.tier].join("/")}
;function pt(a,b){if(a)return a[b.name]}
;var qt=T("initial_gel_batch_timeout",2E3),rt=T("gel_queue_timeout_max_ms",6E4),st=T("gel_min_batch_size",5),tt=void 0;function ut(){this.o=this.h=this.i=0;this.j=!1}
var vt=new ut,wt=new ut,xt=new ut,zt=new ut,At,Bt=!0,Ct=D.ytLoggingTransportTokensToCttTargetIds_||{};E("ytLoggingTransportTokensToCttTargetIds_",Ct);var Dt={};function Et(){var a=F("yt.logging.ims");a||(a=new lt,E("yt.logging.ims",a));return a}
function Ft(a,b){if(a.endpoint==="log_event"){Gt();var c=Ht(a),d=It(a.payload)||"";a:{if(S("enable_web_tiered_gel")){var e=zr[d||""];var f,g,h,k=Qs().resolve(new Ks(cq))==null?void 0:(f=dq())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.eventLoggingConfig)==null?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(e.enabled===!1&&!S("web_payload_policy_disabled_killswitch"))return;k=Jt(e.tier);if(k===400){Kt(a,b);return}}Dt[c]=
!0;c={cttAuthInfo:c,isJspb:!1,tier:k};Et().storePayload(c,a.payload);Lt(b,c,d==="gelDebuggingEvent")}}
function Lt(a,b,c){function d(){Mt({writeThenSend:!0},void 0,e,b.tier)}
var e=!1;e=e===void 0?!1:e;c=c===void 0?!1:c;a&&(tt=new a);a=T("tvhtml5_logging_max_batch_ads_fork")||T("tvhtml5_logging_max_batch")||T("web_logging_max_batch")||100;var f=V(),g=Nt(e,b.tier),h=g.o;c&&(g.j=!0);c=0;b&&(c=Et().getSequenceCount(b));c>=1E3?d():c>=a?At||(At=Ot(function(){d();At=void 0},0)):f-h>=10&&(Pt(e,b.tier),g.o=f)}
function Kt(a,b){if(a.endpoint==="log_event"){S("more_accurate_gel_parser")&&Et().storePayload({isJspb:!1},a.payload);Gt();var c=Ht(a),d=new Map;d.set(c,[a.payload]);var e=It(a.payload)||"";b&&(tt=new b);return new ji(function(f,g){tt&&tt.isReady()?Qt(d,tt,f,g,{bypassNetworkless:!0},!0,e==="gelDebuggingEvent"):f()})}}
function Ht(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);Ct[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function Mt(a,b,c,d){a=a===void 0?{}:a;c=c===void 0?!1:c;new ji(function(e,f){var g=Nt(c,d),h=g.j;g.j=!1;Rt(g.i);Rt(g.h);g.h=0;tt&&tt.isReady()?d===void 0&&S("enable_web_tiered_gel")?St(e,f,a,b,c,300,h):St(e,f,a,b,c,d,h):(Pt(c,d),e())})}
function St(a,b,c,d,e,f,g){var h=tt;c=c===void 0?{}:c;e=e===void 0?!1:e;f=f===void 0?200:f;g=g===void 0?!1:g;var k=new Map,l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(d!==void 0)f=S("enable_web_tiered_gel")?Et().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):Et().extractMatchingEntries(e),k.set(d,f);else for(d=y(Object.keys(Dt)),l=d.next();!l.done;l=d.next())l=l.value,e=S("enable_web_tiered_gel")?Et().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):Et().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),e.length>0&&k.set(l,e),(S("web_fp_via_jspb_and_json")&&c.writeThenSend||!S("web_fp_via_jspb_and_json"))&&delete Dt[l];Qt(k,h,a,b,c,!1,g)}
function Pt(a,b){function c(){Mt({writeThenSend:!0},void 0,a,b)}
a=a===void 0?!1:a;b=b===void 0?200:b;var d=Nt(a,b),e=d===zt||d===xt?5E3:rt;S("web_gel_timeout_cap")&&!d.h&&(e=Ot(function(){c()},e),d.h=e);
Rt(d.i);e=R("LOGGING_BATCH_TIMEOUT",T("web_gel_debounce_ms",1E4));S("shorten_initial_gel_batch_timeout")&&Bt&&(e=qt);e=Ot(function(){T("gel_min_batch_size")>0?Et().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=st&&c():c()},e);
d.i=e}
function Qt(a,b,c,d,e,f,g){e=e===void 0?{}:e;var h=Math.round(V()),k=a.size,l=(g===void 0?0:g)&&S("vss_through_gel_video_stats")?"video_stats":"log_event";a=y(a);var m=a.next();for(g={};!m.done;g={Sc:void 0,batchRequest:void 0,dangerousLogToVisitorSession:void 0,Vc:void 0,Uc:void 0},m=a.next()){var n=y(m.value);m=n.next().value;n=n.next().value;g.batchRequest=sg({context:jq(b.config_||iq())});if(!Qa(n)&&!S("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=n;(n=Ct[m])&&
Tt(g.batchRequest,m,n);delete Ct[m];g.dangerousLogToVisitorSession=m==="visitorOnlyApprovedKey";Ut(g.batchRequest,h,g.dangerousLogToVisitorSession);S("always_send_and_write")&&(e.writeThenSend=!1);g.Vc=function(p){S("start_client_gcf")&&Kj.pa(function(){return B(function(t){return t.yield(Vt(p),0)})});
k--;k||c()};
g.Sc=0;g.Uc=function(p){return function(){p.Sc++;if(e.bypassNetworkless&&p.Sc===1)try{dr(b,l,p.batchRequest,Wt({writeThenSend:!0},p.dangerousLogToVisitorSession,p.Vc,p.Uc,f)),Bt=!1}catch(t){fm(t),d()}k--;k||c()}}(g);
try{dr(b,l,g.batchRequest,Wt(e,g.dangerousLogToVisitorSession,g.Vc,g.Uc,f)),Bt=!1}catch(p){fm(p),d()}}}
function Wt(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,th:!!e,headers:{},postBodyFormat:"",postBody:"",compress:S("compress_gel")||S("compress_gel_lr")};Xt()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));return a}
function Ut(a,b,c){Xt()||(a.requestTimeMs=String(b));S("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=R("EVENT_ID"))&&((c=R("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*65535/2)),c++,c>65535&&(c=1),am("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Tt(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Gt(){var a;(a=F("yt.logging.transport.enableScrapingForTest"))||(a=Am("il_payload_scraping"),a=(a!==void 0?String(a):"")!=="enable_il_payload_scraping");a||(kt=[],E("yt.logging.transport.enableScrapingForTest",!0),E("yt.logging.transport.scrapedPayloadsForTesting",kt),E("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),E("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
E("yt.logging.transport.scrapeClientEvent",!0))}
function Xt(){return S("use_request_time_ms_header")||S("lr_use_request_time_ms_header")}
function Ot(a,b){return S("transport_use_scheduler")===!1?ym(a,b):S("logging_avoid_blocking_during_navigation")||S("lr_logging_avoid_blocking_during_navigation")?En(function(){if(jt().currentState==="none")a();else{var c={};jt().install((c.none={callback:a},c))}},b):En(a,b)}
function Rt(a){S("transport_use_scheduler")?Kj.qa(a):window.clearTimeout(a)}
function Vt(a){var b,c,d,e,f,g,h,k,l,m;return B(function(n){return n.h==1?(d=(b=a)==null?void 0:(c=b.responseContext)==null?void 0:c.globalConfigGroup,e=pt(d,Dl),g=(f=d)==null?void 0:f.hotHashData,h=pt(d,Cl),l=(k=d)==null?void 0:k.coldHashData,(m=Qs().resolve(new Ks(cq)))?g?e?n.yield(eq(m,g,e),2):n.yield(eq(m,g),2):n.A(2):n.return()):l?h?n.yield(fq(m,l,h),0):n.yield(fq(m,l),0):n.A(0)})}
function Nt(a,b){b=b===void 0?200:b;return a?b===300?zt:wt:b===300?xt:vt}
function It(a){a=Object.keys(a);a=y(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,zr[b])return b}
function Jt(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var Yt=D.ytLoggingGelSequenceIdObj_||{};E("ytLoggingGelSequenceIdObj_",Yt);
function Zt(a,b,c,d){d=d===void 0?{}:d;var e={},f=Math.round(d.timestamp||V());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=xs();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!S("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,Yt[b]=b in Yt?Yt[b]+1:0,a.sequence={index:Yt[b],groupKey:b},d.endOfSequence&&delete Yt[d.sequenceGroup]);(d.sendIsolatedPayload?Kt:Ft)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function to(a,b,c){c=c===void 0?{}:c;var d=bs;R("ytLoggingEventsDefaultDisabled",!1)&&bs===bs&&(d=null);Zt(a,b,d,c)}
;function $t(a){return a.slice(0,void 0).map(function(b){return b.name}).join(" > ")}
;var au=new Set,bu=0,cu=0,du=0,eu=[],fu=[],gu=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function so(a){hu(a)}
function W(a){hu(a,"WARNING")}
function iu(a){a instanceof Error?hu(a):(a=Ra(a)?JSON.stringify(a):String(a),a=new U(a),a.name="RejectedPromiseError",W(a))}
function hu(a,b,c,d,e,f,g,h){f=f===void 0?{}:f;f.name=c||R("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||R("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),S("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(bu>=5))){d=[];e=y(fu);for(f=e.next();!f.done;f=e.next()){f=f.value;try{f()&&d.push(f())}catch(z){}}d=[].concat(A(eu),A(d));var k=Vb(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var m=l.split("\n");m.shift();l=m.join("\n")}m=k.lineNumber||"Not available";k=k.fileName||"Not available";var n=0;if(a.hasOwnProperty("args")&&
a.args&&a.args.length)for(var p=0;p<a.args.length&&!(n=an(a.args[p],"params."+p,c,n),n>=500);p++);else if(a.hasOwnProperty("params")&&a.params){var t=a.params;if(typeof a.params==="object")for(p in t){if(t[p]){var v="params."+p,x=cn(t[p]);c[v]=x;n+=v.length+x.length;if(n>500)break}}else c.params=cn(t)}if(d.length)for(p=0;p<d.length&&!(n=an(d[p],"params.context."+p,c,n),n>=500);p++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);p={message:e,name:f,lineNumber:m,
fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(p.lineNumber=p.lineNumber+":"+c);if(a.level==="IGNORED")a=0;else a:{a=Xm();c=y(a.Ya);for(d=c.next();!d.done;d=c.next())if(d=d.value,p.message&&p.message.match(d.Jh)){a=d.weight;break a}a=y(a.Ta);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(p)){a=c.weight;break a}a=1}p.sampleWeight=a;a=y(Sm);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.vc[p.name])for(e=y(c.vc[p.name]),d=e.next();!d.done;d=e.next())if(f=
d.value,d=p.message.match(f.regexp)){p.params["params.error.original"]=d[0];e=f.groups;f={};for(m=0;m<e.length;m++)f[e[m]]=d[m+1],p.params["params.error."+e[m]]=d[m+1];p.message=c.Qc(f);break}p.params||(p.params={});a=Xm();p.params["params.errorServiceSignature"]="msg="+a.Ya.length+"&cb="+a.Ta.length;p.params["params.serviceWorker"]="false";D.document&&D.document.querySelectorAll&&(p.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));(new vg(wg,"sample")).constructor!==
vg&&(p.params["params.fconst"]="true");window.yterr&&typeof window.yterr==="function"&&window.yterr(p);if(p.sampleWeight!==0&&!au.has(p.message)){if(g&&S("web_enable_error_204"))ju(b===void 0?"ERROR":b,p);else{b=b===void 0?"ERROR":b;b==="ERROR"?(Ym.qb("handleError",p),S("record_app_crashed_web")&&du===0&&p.sampleWeight===1&&(du++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},S("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:p.message}}}}),to("appCrashed",
g)),cu++):b==="WARNING"&&Ym.qb("handleWarning",p);if(S("kevlar_gel_error_routing")){g=b;h=h===void 0?{}:h;b:{a=y(gu);for(c=a.next();!c.done;c=a.next())if(zo(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:p.stack};p.fileName&&(c.filename=p.fileName);a=p.lineNumber&&p.lineNumber.split?p.lineNumber.split(":"):[];a.length!==0&&(a.length!==1||isNaN(Number(a[0]))?a.length!==2||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=
Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:p.message,errorClassName:p.name,sampleWeight:p.sampleWeight};g==="ERROR"?a.level="ERROR_LEVEL_ERROR":g==="WARNING"&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];R("FEXP_EXPERIMENTS")&&(h.experimentIds=R("FEXP_EXPERIMENTS"));d=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!bm("web_disable_gel_stp_ecatcher_killswitch")&&d)for(e=y(Object.keys(d)),f=e.next();!f.done;f=e.next())f=
f.value,h.kvPairs.push({key:f,value:String(d[f])});if(d=p.params)for(e=y(Object.keys(d)),f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:"client."+f,value:String(d[f])});d=R("SERVER_NAME");e=R("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(to("clientError",h),(g==="ERROR"||S("errors_flush_gel_always_killswitch"))&&Mt(void 0,void 0,!1))}S("suppress_error_204_logging")||
ju(b,p)}try{au.add(p.message)}catch(z){}bu++}}}
function ju(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:R("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=y(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=y(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];(c=R("LAVA_VERSION"))&&(a.postParams["lava.version"]=c);c=R("SERVER_NAME");b=R("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Jm(R("ECATCHER_REPORT_HOST","")+"/error_204",a)}
function ku(a){var b=C.apply(1,arguments);a.args||(a.args=[]);Array.isArray(a.args)&&a.args.push.apply(a.args,A(b))}
;function lu(){this.register=new Map}
function mu(a){a=y(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Nh("ABORTED")}
lu.prototype.clear=function(){mu(this);this.register.clear()};
var nu=new lu;var ou=Date.now().toString();
function pu(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;a<16;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(Math.random()*256)}if(ou)for(a=1,b=0;b<ou.length;b++)d[a%16]^=d[(a-1)%16]/4^ou.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var qu,ru=D.ytLoggingDocDocumentNonce_;ru||(ru=pu(),E("ytLoggingDocDocumentNonce_",ru));qu=ru;function su(a){this.h=a}
r=su.prototype;r.getAsJson=function(){var a={};this.h.trackingParams!==void 0?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,this.h.veCounter!==void 0&&(a.veCounter=this.h.veCounter),this.h.elementIndex!==void 0&&(a.elementIndex=this.h.elementIndex));this.h.dataElement!==void 0&&(a.dataElement=this.h.dataElement.getAsJson());this.h.youtubeData!==void 0&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
r.getAsJspb=function(){var a=new Fl;this.h.trackingParams!==void 0?a.setTrackingParams(this.h.trackingParams):(this.h.veType!==void 0&&of(a,2,Fe(this.h.veType)),this.h.veCounter!==void 0&&of(a,6,Fe(this.h.veCounter)),this.h.elementIndex!==void 0&&of(a,3,Fe(this.h.elementIndex)),this.h.isCounterfactual&&of(a,5,Be(!0)));if(this.h.dataElement!==void 0){var b=this.h.dataElement.getAsJspb();zf(a,Fl,7,b)}this.h.youtubeData!==void 0&&zf(a,El,8,this.h.jspbYoutubeData);return a};
r.toString=function(){return JSON.stringify(this.getAsJson())};
r.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
r.getLoggingDirectives=function(){return this.h.loggingDirectives};function tu(a){return R("client-screen-nonce-store",{})[a===void 0?0:a]}
function uu(a,b){b=b===void 0?0:b;var c=R("client-screen-nonce-store");c||(c={},am("client-screen-nonce-store",c));c[b]=a}
function vu(a){a=a===void 0?0:a;return a===0?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function wu(a){return R(vu(a===void 0?0:a))}
E("yt_logging_screen.getRootVeType",wu);function xu(){var a=R("csn-to-ctt-auth-info");a||(a={},am("csn-to-ctt-auth-info",a));return a}
function yu(){return Object.values(R("client-screen-nonce-store",{})).filter(function(a){return a!==void 0})}
function zu(a){a=tu(a===void 0?0:a);if(!a&&!R("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
E("yt_logging_screen.getCurrentCsn",zu);function Au(a,b,c){var d=xu();(c=zu(c))&&delete d[c];b&&(d[a]=b)}
function Bu(a){return xu()[a]}
E("yt_logging_screen.getCttAuthInfo",Bu);E("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=c===void 0?0:c;if(a!==tu(c)||b!==R(vu(c)))if(Au(a,d,c),uu(a,c),am(vu(c),b),b=function(){setTimeout(function(){a&&to("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:qu,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});function Cu(){var a=rg(Du),b;return(new ji(function(c,d){a.onSuccess=function(e){xm(e)?c(new Eu(e)):d(new Fu("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Fu("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Fu("Request timed out","net.timeout",e))};
b=Jm("//googleads.g.doubleclick.net/pagead/id",a)})).Dc(function(c){if(c instanceof si){var d;
(d=b)==null||d.abort()}return oi(c)})}
function Fu(a,b,c){cb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
w(Fu,cb);function Eu(a){this.xhr=a}
;function Gu(){this.X=0;this.h=null}
Gu.prototype.then=function(a,b,c){return this.X===1&&a?(a=a.call(c,this.h))&&typeof a.then==="function"?a:Hu(a):this.X===2&&b?(a=b.call(c,this.h))&&typeof a.then==="function"?a:Iu(a):this};
Gu.prototype.getValue=function(){return this.h};
Gu.prototype.isRejected=function(){return this.X==2};
Gu.prototype.$goog_Thenable=!0;function Iu(a){var b=new Gu;a=a===void 0?null:a;b.X=2;b.h=a===void 0?null:a;return b}
function Hu(a){var b=new Gu;a=a===void 0?null:a;b.X=1;b.h=a===void 0?null:a;return b}
;function Ju(a){var b=R("INNERTUBE_HOST_OVERRIDE");b&&(a=String(b)+String(dc(a)));return a}
function Ku(a){var b={};S("json_condensed_response")&&(b.prettyPrint="false");return a=qm(a,b||{},!1)}
function Lu(a,b){var c=c===void 0?{}:c;a={method:b===void 0?"POST":b,mode:rm(a)?"same-origin":"cors",credentials:rm(a)?"same-origin":"include"};b={};for(var d=y(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);Object.keys(b).length>0&&(a.headers=b);return a}
;function Mu(){return ag()||(kd||ld)&&zo("applewebkit")&&!zo("version")&&(!zo("safari")||zo("gsa/"))||jd&&zo("version/")?!0:R("EOM_VISITOR_DATA")?!1:!0}
;function Nu(a){var b=a.docid||a.video_id||a.videoId||a.id;if(b)return b;b=a.raw_player_response;b||(a=a.player_response)&&(b=JSON.parse(a));return b&&b.videoDetails&&b.videoDetails.videoId||null}
;function Ou(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in Jl)if(Jl[d]==c.embeddedPlayerMode){b=Jl[d];break b}}return b==="EMBEDDED_PLAYER_MODE_PFL"}
;function Pu(a){cb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Qu;this.isTimeout=a instanceof Fu&&a.errorCode=="net.timeout";this.isCanceled=a instanceof si}
w(Pu,cb);Pu.prototype.name="BiscottiError";function Qu(){cb.call(this,"Biscotti ID is missing from server")}
w(Qu,cb);Qu.prototype.name="BiscottiMissingError";var Du={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Ru=null;function Su(){if(S("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Mu())return Error("User has not consented - not fetching biscotti id.");var a=R("PLAYER_VARS",{});if(pg(a)=="1")return Error("Biscotti ID is not available in private embed mode");if(Ou(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Ul(){var a=Su();if(a!==void 0)return oi(a);Ru||(Ru=Cu().then(Tu).Dc(function(b){return Uu(2,b)}));
return Ru}
function Tu(a){a=a.xhr.responseText;if(a.lastIndexOf(")]}'",0)!=0)throw new Qu;a=JSON.parse(a.substr(4));if((a.type||1)>1)throw new Qu;a=a.id;Vl(a);Ru=Hu(a);Vu(18E5,2);return a}
function Uu(a,b){b=new Pu(b);Vl("");Ru=Iu(b);a>0&&Vu(12E4,a-1);throw b;}
function Vu(a,b){ym(function(){Cu().then(Tu,function(c){return Uu(b,c)}).Dc(hi)},a)}
function Wu(){try{var a=F("yt.ads.biscotti.getId_");return a?a():Ul()}catch(b){return oi(b)}}
;var Hb=ra(["data-"]);function Xu(a){a&&(a.dataset?a.dataset[Yu()]="true":Ib(a))}
function Zu(a){return a?a.dataset?a.dataset[Yu()]:a.getAttribute("data-loaded"):null}
var $u={};function Yu(){return $u.loaded||($u.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;function av(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||rg(b);this.assets=a.assets||{};this.attrs=a.attrs||rg(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
av.prototype.clone=function(){var a=new av,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];La(c)=="object"?a[b]=rg(c):a[b]=c}return a};var bv=["att/get"],cv=["share/get_share_panel"],dv=["share/get_web_player_share_panel"],ev=["feedback"],fv=["notification/modify_channel_preference"],gv=["browse/edit_playlist"],hv=["subscription/subscribe"],iv=["subscription/unsubscribe"];var jv=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};E("yt.msgs_",jv);function kv(a){Wl(jv,arguments)}
;function lv(a,b,c){mv(a,b,c===void 0?null:c)}
function nv(a){a=ov(a);var b=document.getElementById(a);b&&(Gs(a),b.parentNode.removeChild(b))}
function pv(a,b){a&&b&&(a=""+Sa(b),(a=qv[a])&&Es(a))}
function mv(a,b,c){c=c===void 0?null:c;var d=ov(a),e=document.getElementById(d),f=e&&Zu(e),g=e&&!f;f?b&&b():(b&&(f=Cs(d,b),b=""+Sa(b),qv[b]=f),g||(e=rv(a,d,function(){Zu(e)||(Xu(e),Fs(d),ym(function(){Gs(d)},0))},c)))}
function rv(a,b,c,d){d=d===void 0?null:d;var e=yg("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Fb(e,Al(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function ov(a){var b=document.createElement("a");xb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Zb(a)}
var qv={};function sv(a){var b=tv(a),c=document.getElementById(b),d=c&&Zu(c);d||c&&!d||(c=uv(a,b,function(){if(!Zu(c)){Xu(c);Fs(b);var e=Za(Gs,b);ym(e,0)}}))}
function uv(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Al(a);Lb(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function tv(a){var b=yg("A");xb(b,new qb(a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Zb(a)}
;function vv(a){var b=C.apply(1,arguments);if(!wv(a)||b.some(function(d){return!wv(d)}))throw Error("Only objects may be merged.");
b=y(b);for(var c=b.next();!c.done;c=b.next())xv(a,c.value)}
function xv(a,b){for(var c in b)if(wv(b[c])){if(c in a&&!wv(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});xv(a[c],b[c])}else if(yv(b[c])){if(c in a&&!yv(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);zv(a[c],b[c])}else a[c]=b[c];return a}
function zv(a,b){b=y(b);for(var c=b.next();!c.done;c=b.next())c=c.value,wv(c)?a.push(xv({},c)):yv(c)?a.push(zv([],c)):a.push(c);return a}
function wv(a){return typeof a==="object"&&!Array.isArray(a)}
function yv(a){return typeof a==="object"&&Array.isArray(a)}
;var Av="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function Bv(a,b){var c=c===void 0?!0:c;var d=R("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=cc(window.location.href);e&&d.push(e);e=cc(a);if(Mb(d,e)>=0||!e&&a.lastIndexOf("/",0)==0)if(d=document.createElement("a"),xb(d,a),a=d.href)if(a=dc(a),a=ec(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:zu()},b)),f){var f=parseInt(f,10);isFinite(f)&&f>0&&Cv(a,b,f)}else Cv(a,b)}
function Cv(a,b,c){a=Dv(a);b=b?hc(b):"";c=c||5;Mu()&&kn(a,b,c)}
function Dv(a){for(var b=y(Av),c=b.next();!c.done;c=b.next())a=mc(a,c.value);return"ST-"+Zb(a).toString(36)}
;function Ev(a){pq.call(this,1,arguments);this.csn=a}
w(Ev,pq);var yq=new qq("screen-created",Ev),Fv=[],Gv=0,Hv=new Map,Iv=new Map,Jv=new Map;
function Kv(a,b,c,d,e){e=e===void 0?!1:e;for(var f=Lv({cttAuthInfo:Bu(b)||void 0},b),g=y(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(ng(k)||!k.trackingParams&&!k.veType)&&W(Error("Child VE logged with no data"));if(S("no_client_ve_attach_unless_shown")){var l=Mv(h,b);if(k.veType&&!Iv.has(l)&&!Jv.has(l)&&!e){if(!S("il_attach_cache_limit")||Hv.size<1E3){Hv.set(l,[a,b,c,h]);return}S("il_attach_cache_limit")&&Hv.size>1E3&&W(new U("IL Attach cache exceeded limit"))}h=Mv(c,b);Hv.has(h)?
Nv(c,b):Jv.set(h,!0)}}d=d.filter(function(m){m.csn!==b?(m.csn=b,m=!0):m=!1;return m});
c={csn:b,parentVe:c.getAsJson(),childVes:Pb(d,function(m){return m.getAsJson()})};
b==="UNDEFINED_CSN"?Ov("visualElementAttached",f,c):a?Zt("visualElementAttached",c,a,f):to("visualElementAttached",c,f)}
function Ov(a,b,c){Fv.push({Se:a,payload:c,Fh:void 0,options:b});Gv||(Gv=zq())}
function Aq(a){if(Fv){for(var b=y(Fv),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,to(c.Se,c.payload,c.options));Fv.length=0}Gv=0}
function Mv(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function Nv(a,b){a=Mv(a,b);Hv.has(a)&&(b=Hv.get(a)||[],Kv(b[0],b[1],b[2],[b[3]],!0),Hv.delete(a))}
function Lv(a,b){S("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function Pv(){try{return!!self.localStorage}catch(a){return!1}}
;function Qv(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Rv(a){if(Pv()){var b=Object.keys(window.localStorage);b=y(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Qv(c);d===void 0||a.includes(d)||self.localStorage.removeItem(c)}}}
function Sv(){if(!Pv())return!1;var a=Cn(),b=Object.keys(window.localStorage);b=y(b);for(var c=b.next();!c.done;c=b.next())if(c=Qv(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Tv(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return(R("INNERTUBE_CLIENT_NAME")==="WEB"||R("INNERTUBE_CLIENT_NAME")==="WEB_CREATOR")&&a}
function Uv(a){if(R("LOGGED_IN",!0)&&Tv()){var b=R("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=cc(window.location.href);c&&b.push(c);c=cc(a);Mb(b,c)>=0||!c&&a.lastIndexOf("/",0)==0?(b=dc(a),(b=ec(b))?(b=Dv(b),b=(b=ln(b)||null)?nm(b):{}):b=null):b=null;b==null&&(b={});c=b;var d=void 0;Tv()?(d||(d=R("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&Bv(a,b)}}
;function Vv(a,b,c){b=b===void 0?{}:b;c=c===void 0?!1:c;var d=R("EVENT_ID");d&&(b.ei||(b.ei=d));b&&Bv(a,b);if(c)return!1;Uv(a);var e=e===void 0?{}:e;var f=f===void 0?"":f;var g=g===void 0?window:g;b=ic(a,e);Uv(b);a=void 0;a=a===void 0?ub:a;a:if(f=b+f,a=a===void 0?ub:a,!(f instanceof qb)){for(b=0;b<a.length;++b)if(c=a[b],c instanceof sb&&c.Ge(f)){f=new qb(f);break a}f=void 0}g=g.location;f=wb(f||rb);f!==void 0&&(g.href=f);return!0}
;function Wv(a){if(pg(R("PLAYER_VARS",{}))!="1"){a&&Tl();try{Wu().then(function(){},function(){}),ym(Wv,18E5)}catch(b){fm(b)}}}
;var Xv=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Yv(){var a=a===void 0?window.location.href:a;if(S("kevlar_disable_theme_param"))return null;var b=ac(bc(5,a));if(S("enable_dark_theme_only_on_shorts")&&b!=null&&b.startsWith("/shorts/"))return"USER_INTERFACE_THEME_DARK";try{var c=om(a).theme;return Xv.get(c)||null}catch(d){}return null}
;function Zv(){this.h={};if(this.i=nn()){var a=ln("CONSISTENCY");a&&$v(this,{encryptedTokenJarContents:a})}}
Zv.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=((c=b.Ga.context)==null?void 0:(d=c.request)==null?void 0:d.consistencyTokenJars)||[];var e;if(a=(e=a.responseContext)==null?void 0:e.consistencyTokenJar){e=y(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];$v(this,a)}};
function $v(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,typeof b.expirationSeconds==="string")){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},c*1E3);
a.i&&kn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var aw=window.location.hostname.split(".").slice(-2).join(".");function bw(){this.j=-1;var a=R("LOCATION_PLAYABILITY_TOKEN");R("INNERTUBE_CLIENT_NAME")==="TVHTML5"&&(this.h=cw(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var dw;function ew(){dw=F("yt.clientLocationService.instance");dw||(dw=new bw,E("yt.clientLocationService.instance",dw));return dw}
r=bw.prototype;
r.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});if(this.i)a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(this.i.coords.latitude*1E7),a.client.locationInfo.longitudeE7=Math.floor(this.i.coords.longitude*1E7),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0;else if(this.o||this.locationPlayabilityToken)a.client.locationPlayabilityToken=this.o||
this.locationPlayabilityToken};
r.handleResponse=function(a){var b;a=(b=a.responseContext)==null?void 0:b.locationPlayabilityToken;a!==void 0&&(this.locationPlayabilityToken=a,this.i=void 0,R("INNERTUBE_CLIENT_NAME")==="TVHTML5"?(this.h=cw(this))&&this.h.set("yt-location-playability-token",a,15552E3):kn("YT_CL",JSON.stringify({loctok:a}),15552E3,aw,!0))};
function cw(a){return a.h===void 0?new ko("yt-client-location"):a.h}
r.clearLocationPlayabilityToken=function(a){a==="TVHTML5"?(this.h=cw(this))&&this.h.remove("yt-location-playability-token"):mn("YT_CL");this.o=void 0;this.j!==-1&&(clearTimeout(this.j),this.j=-1)};
r.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;R("INNERTUBE_CLIENT_NAME")==="MWEB"&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
r.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);if(a==null?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
r.createLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);return b};function fw(a,b,c){b=b===void 0?!1:b;c=c===void 0?!1:c;var d=R("INNERTUBE_CONTEXT");if(!d)return hu(Error("Error: No InnerTubeContext shell provided in ytconfig.")),{};d=sg(d);S("web_no_tracking_params_in_shell_killswitch")||delete d.clickTracking;d.client||(d.client={});var e=d.client;e.clientName==="MWEB"&&e.clientFormFactor!=="AUTOMOTIVE_FORM_FACTOR"&&(e.clientFormFactor=R("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");e.screenWidthPoints=window.innerWidth;e.screenHeightPoints=window.innerHeight;
e.screenPixelDensity=Math.round(window.devicePixelRatio||1);e.screenDensityFloat=window.devicePixelRatio||1;e.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var f=f===void 0?!1:f;rn();var g="USER_INTERFACE_THEME_LIGHT";un(165)?g="USER_INTERFACE_THEME_DARK":un(174)?g="USER_INTERFACE_THEME_LIGHT":!S("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(g="USER_INTERFACE_THEME_DARK");
f=f?g:Yv()||g;e.userInterfaceTheme=f;if(!b){if(f=zn())e.connectionType=f;S("web_log_effective_connection_type")&&(f=An())&&(d.client.effectiveConnectionType=f)}var h;if(S("web_log_memory_total_kbytes")&&((h=D.navigator)==null?0:h.deviceMemory)){var k;h=(k=D.navigator)==null?void 0:k.deviceMemory;d.client.memoryTotalKbytes=""+h*1E6}S("web_gcf_hashes_innertube")&&(f=gq())&&(k=f.coldConfigData,h=f.coldHashData,f=f.hotHashData,d.client.configInfo=d.client.configInfo||{},k&&(d.client.configInfo.coldConfigData=
k),h&&(d.client.configInfo.coldHashData=h),f&&(d.client.configInfo.hotHashData=f));k=om(D.location.href);!S("web_populate_internal_geo_killswitch")&&k.internalcountrycode&&(e.internalGeo=k.internalcountrycode);e.clientName==="MWEB"||e.clientName==="WEB"?(e.mainAppWebInfo={graftUrl:D.location.href},S("kevlar_woffle")&&dn.instance&&(k=dn.instance,e.mainAppWebInfo.pwaInstallabilityStatus=!k.h&&k.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),e.mainAppWebInfo.webDisplayMode=
en(),e.mainAppWebInfo.isWebNativeShareAvailable=navigator&&navigator.share!==void 0):e.clientName==="TVHTML5"&&(!S("web_lr_app_quality_killswitch")&&(k=R("LIVING_ROOM_APP_QUALITY"))&&(e.tvAppInfo=Object.assign(e.tvAppInfo||{},{appQuality:k})),k=R("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(e.tvAppInfo=Object.assign(e.tvAppInfo||{},{certificationScope:k}));if(!S("web_populate_time_zone_itc_killswitch")){a:{if(typeof Intl!=="undefined")try{var l=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break a}catch(Ma){}l=
void 0}l&&(e.timeZone=l)}(l=R("EXPERIMENTS_TOKEN",""))?e.experimentsToken=l:delete e.experimentsToken;l=Bm();Zv.instance||(Zv.instance=new Zv);e=Zv.instance.h;k=[];h=0;for(var m in e)k[h++]=e[m];d.request=Object.assign({},d.request,{internalExperimentFlags:l,consistencyTokenJars:k});!S("web_prequest_context_killswitch")&&(m=R("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(d.request.externalPrequestContext=m);l=rn();m=un(58);l=l.get("gsml","");d.user=Object.assign({},d.user);m&&(d.user.enableSafetyMode=
m);l&&(d.user.lockedSafetyMode=!0);S("warm_op_csn_cleanup")?c&&(b=zu())&&(d.clientScreenNonce=b):!b&&(b=zu())&&(d.clientScreenNonce=b);a&&(d.clickTracking={clickTrackingParams:a});if(a=F("yt.mdx.remote.remoteClient_"))d.remoteClient=a;ew().setLocationOnInnerTubeContext(d);try{var n=sm(),p=n.bid;delete n.bid;d.adSignalsInfo={params:[],bid:p};for(var t=y(Object.entries(n)),v=t.next();!v.done;v=t.next()){var x=y(v.value),z=x.next().value,G=x.next().value;n=z;p=G;a=void 0;(a=d.adSignalsInfo.params)==
null||a.push({key:n,value:""+p})}var J,ba;if(((J=d.client)==null?void 0:J.clientName)==="TVHTML5"||((ba=d.client)==null?void 0:ba.clientName)==="TVHTML5_UNPLUGGED"){var ca=R("INNERTUBE_CONTEXT");ca.adSignalsInfo&&(d.adSignalsInfo.advertisingId=ca.adSignalsInfo.advertisingId,d.adSignalsInfo.advertisingIdSignalType="DEVICE_ID_TYPE_CONNECTED_TV_IFA",d.adSignalsInfo.limitAdTracking=ca.adSignalsInfo.limitAdTracking)}}catch(Ma){hu(Ma)}return d}
;function gw(a){var b={"Content-Type":"application/json"};R("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=R("EOM_VISITOR_DATA"):R("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=R("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=R("LOGGED_IN",!1);R("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=R("DEBUG_SETTINGS_METADATA"));a!=="cors"&&((a=R("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=R("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=R("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=R("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a),R("ENABLE_LAVA_HEADER_ON_IT_EXPANSION")&&(a=R("SERIALIZED_LAVA_DEVICE_CONTEXT"))&&(b["X-YouTube-Lava-Device-Context"]=a));return b}
;function hw(){this.h={}}
hw.prototype.contains=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)};
hw.prototype.get=function(a){if(this.contains(a))return this.h[a]};
hw.prototype.set=function(a,b){this.h[a]=b};
hw.prototype.remove=function(a){delete this.h[a]};function iw(){this.mappings=new hw}
iw.prototype.getModuleId=function(a){return a.serviceId.getModuleId()};
iw.prototype.get=function(a){a:{var b=this.mappings.get(a.toString());switch(b.type){case "mapping":a=b.value;break a;case "factory":b=b.value();this.mappings.set(a.toString(),{type:"mapping",value:b});a=b;break a;default:a=yb(b)}}return a};
new iw;function jw(a){return function(){return new a}}
;var kw={},lw=(kw.WEB_UNPLUGGED="^unplugged/",kw.WEB_UNPLUGGED_ONBOARDING="^unplugged/",kw.WEB_UNPLUGGED_OPS="^unplugged/",kw.WEB_UNPLUGGED_PUBLIC="^unplugged/",kw.WEB_CREATOR="^creator/",kw.WEB_KIDS="^kids/",kw.WEB_EXPERIMENTS="^experiments/",kw.WEB_MUSIC="^music/",kw.WEB_REMIX="^music/",kw.WEB_MUSIC_EMBEDDED_PLAYER="^music/",kw.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",kw);
function mw(a){var b=b===void 0?"UNKNOWN_INTERFACE":b;if(a.length===1)return a[0];var c=lw[b];if(c){c=new RegExp(c);for(var d=y(a),e=d.next();!e.done;e=d.next())if(e=e.value,c.exec(e))return e}var f=[];Object.entries(lw).forEach(function(g){var h=y(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
c=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
d=y(a);for(e=d.next();!e.done;e=d.next())if(e=e.value,!c.exec(e))return e;return a[0]}
;function nw(){}
nw.prototype.u=function(a,b,c){b=b===void 0?{}:b;c=c===void 0?jn:c;var d={context:fw(a.clickTrackingParams,!1,this.o)};var e=this.i(a);if(e){this.h(d,e,b);var f;b="/youtubei/v1/"+mw(this.j());(e=(f=pt(a.commandMetadata,Hl))==null?void 0:f.apiUrl)&&(b=e);f=Ku(Ju(b));a=Object.assign({},{command:a},void 0);d={input:f,Za:Lu(f),Ga:d,config:a};d.config.Mb?d.config.Mb.identity=c:d.config.Mb={identity:c};return d}hu(new U("Error: Failed to create Request from Command.",a))};
fa.Object.defineProperties(nw.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!1}}});
function ow(){}
w(ow,nw);function pw(){}
w(pw,ow);pw.prototype.u=function(){return{input:"/getDatasyncIdsEndpoint",Za:Lu("/getDatasyncIdsEndpoint","GET"),Ga:{}}};
pw.prototype.j=function(){return[]};
pw.prototype.i=function(){};
pw.prototype.h=function(){};var qw={},rw=(qw.GET_DATASYNC_IDS=jw(pw),qw);function sw(a){var b;(b=F("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},E("ytcsi."+(a||"")+"data_",b));return b}
function tw(){var a=sw();a.info||(a.info={});return a.info}
function uw(a){a=sw(a);a.metadata||(a.metadata={});return a.metadata}
function vw(a){a=sw(a);a.tick||(a.tick={});return a.tick}
function ww(a){a=sw(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function xw(a){a=ww(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function yw(a){var b=sw(a).nonce;b||(b=pu(),sw(a).nonce=b);return b}
;function zw(){var a=F("ytcsi.debug");a||(a=[],E("ytcsi.debug",a),E("ytcsi.reference",{}));return a}
function Aw(a){a=a||"";var b=F("ytcsi.reference");b||(zw(),b=F("ytcsi.reference"));if(b[a])return b[a];var c=zw(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var X={},Bw=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X.app_startup="LATENCY_ACTION_APP_STARTUP",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",X.channel_activity="LATENCY_ACTION_KIDS_CHANNEL_ACTIVITY",X.channels="LATENCY_ACTION_CHANNELS",X.chips="LATENCY_ACTION_CHIPS",X.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.editor=
"LATENCY_ACTION_EDITOR",X.embed="LATENCY_ACTION_EMBED",X.embed_no_video="LATENCY_ACTION_EMBED_NO_VIDEO",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.favorites="LATENCY_ACTION_FAVORITES",X.home="LATENCY_ACTION_HOME",X.inboarding="LATENCY_ACTION_INBOARDING",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",
X.management="LATENCY_ACTION_MANAGEMENT",X.mini_app="LATENCY_ACTION_MINI_APP_PLAY",X.notification_settings="LATENCY_ACTION_KIDS_NOTIFICATION_SETTINGS",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",
X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.projects="LATENCY_ACTION_PROJECTS",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.red="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.premium="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.privacy_policy="LATENCY_ACTION_KIDS_PRIVACY_POLICY",X.review="LATENCY_ACTION_REVIEW",X.search_overview_answer="LATENCY_ACTION_SEARCH_OVERVIEW_ANSWER",X.search_ui="LATENCY_ACTION_SEARCH_UI",
X.search_suggest="LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.store="LATENCY_ACTION_STORE",X.supervision_dashboard="LATENCY_ACTION_KIDS_SUPERVISION_DASHBOARD",X.tenx="LATENCY_ACTION_TENX",X.video_preview="LATENCY_ACTION_VIDEO_PREVIEW",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",
X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",
X.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",X.attestation_challenge_fetch="LATENCY_ACTION_ATTESTATION_CHALLENGE_FETCH",X);function Cw(a,b){pq.call(this,1,arguments);this.timer=b}
w(Cw,pq);var Dw=new qq("aft-recorded",Cw);E("ytLoggingGelSequenceIdObj_",D.ytLoggingGelSequenceIdObj_||{});var Ew=D.ytLoggingLatencyUsageStats_||{};E("ytLoggingLatencyUsageStats_",Ew);function Fw(){this.h=0}
function Gw(){Fw.instance||(Fw.instance=new Fw);return Fw.instance}
Fw.prototype.tick=function(a,b,c,d){Hw(this,"tick_"+a+"_"+b)||to("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
Fw.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Hw(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,to("latencyActionInfo",a,{cttAuthInfo:c}))};
Fw.prototype.jspbInfo=function(){};
Fw.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Hw(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,to("latencyActionSpan",a,{cttAuthInfo:c}))};
function Hw(a,b){Ew[b]=Ew[b]||{count:0};var c=Ew[b];c.count++;c.time=V();a.h||(a.h=En(function(){var d=V(),e;for(e in Ew)Ew[e]&&d-Ew[e].time>6E4&&delete Ew[e];a&&(a.h=0)},5E3));
return c.count>5?(c.count===6&&Math.random()*1E5<1&&(c=new U("CSI data exceeded logging limit with key",b.split("_")),b.indexOf("plev")>=0||W(c)),!0):!1}
;var Iw=window;function Jw(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function Kw(){var a;if(S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=Y==null?void 0:(a=Y.getEntriesByType)==null?void 0:(b=a.call(Y,"navigation"))==null?void 0:(c=b[0])==null?void 0:(d=c.toJSON)==null?void 0:d.call(c);e?(e.requestStart=Lw(e.requestStart),e.responseEnd=Lw(e.responseEnd),e.redirectStart=Lw(e.redirectStart),e.redirectEnd=Lw(e.redirectEnd),e.domainLookupEnd=Lw(e.domainLookupEnd),e.connectStart=Lw(e.connectStart),e.connectEnd=
Lw(e.connectEnd),e.responseStart=Lw(e.responseStart),e.secureConnectionStart=Lw(e.secureConnectionStart),e.domainLookupStart=Lw(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=S("csi_performance_timing_to_object")?JSON.parse(JSON.stringify(Y.timing)):Y.timing;return a}
function Lw(a){return Math.round(Mw()+a)}
function Mw(){return(S("csi_use_time_origin")||S("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=Iw.performance||Iw.mozPerformance||Iw.msPerformance||Iw.webkitPerformance||new Jw;var Nw=!1,Ow=!1,Pw={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj",'script[name="embed_client"]':"ecj",'link[rel="stylesheet"][name="embed-ui"]':"ecc"};Xa(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||hi,Y);function Qw(a,b){if(!S("web_csi_action_sampling_enabled")||!sw(b).actionDisabled){var c=Aw(b||"");vv(c.info,a);a.loadType&&(c=a.loadType,uw(b).loadType=c);vv(xw(b),a);c=yw(b);b=sw(b).cttAuthInfo;Gw().info(a,c,b)}}
function Rw(){var a,b,c,d;return((d=Qs().resolve(new Ks(cq))==null?void 0:(a=dq())==null?void 0:(b=a.loggingHotConfig)==null?void 0:(c=b.csiConfig)==null?void 0:c.debugTicks)!=null?d:[]).map(function(e){return Object.values(e)[0]})}
function Z(a,b,c){if(!S("web_csi_action_sampling_enabled")||!sw(c).actionDisabled){var d=yw(c),e;if(e=S("web_csi_debug_sample_enabled")&&d){(Qs().resolve(new Ks(cq))==null?0:dq())&&!Ow&&(Ow=!0,Z("gcfl",V(),c));var f,g,h;e=(Qs().resolve(new Ks(cq))==null?void 0:(f=dq())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.csiConfig)==null?void 0:h.debugSampleWeight)||0;if(f=e!==0)b:{f=Rw();if(f.length>0)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=f*31+d.charCodeAt(g),
g<d.length-1&&(f%=0x800000000000);e=f%1E5%e!==0;sw(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Qw(f,c));sw(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){if(a[0]!=="_"&&(e=a,f=b,Y.mark))if(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),f===void 0||S("web_csi_disable_alt_time_performance_mark"))Y.mark(e);else{f=S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")?f-Y.timeOrigin:f-(Y.timeOrigin||Y.timing.navigationStart);try{Y.mark(e,
{startTime:f})}catch(k){}}e=Aw(c||"");e.tick[a]=b||V();if(e.callback&&e.callback[a])for(e=y(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=ww(c);e.gelTicks&&(e.gelTicks[a]=!0);f=vw(c);e=b||V();S("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=sw(c).cttAuthInfo;a==="_start"?(a=Gw(),Hw(a,"baseline_"+d)||to("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):Gw().tick(a,d,b,f);Sw(c);return e}}}
function Tw(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=ds+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Uw(){function a(f,g,h){g=g.match("_rid")?g.split("_rid")[0]:g;typeof h==="number"&&(h=JSON.stringify(h));f.requestIds?f.requestIds.push({endpoint:g,id:h}):f.requestIds=[{endpoint:g,id:h}]}
for(var b={},c=y(Object.entries(R("TIMING_INFO",{}))),d=c.next();!d.done;d=c.next()){var e=y(d.value);d=e.next().value;e=e.next().value;switch(d){case "GetBrowse_rid":a(b,d,e);break;case "GetGuide_rid":a(b,d,e);break;case "GetHome_rid":a(b,d,e);break;case "GetPlayer_rid":a(b,d,e);break;case "GetSearch_rid":a(b,d,e);break;case "GetSettings_rid":a(b,d,e);break;case "GetTrending_rid":a(b,d,e);break;case "GetWatchNext_rid":a(b,d,e);break;case "yt_red":b.isRedSubscriber=!!e;break;case "yt_ad":b.isMonetized=
!!e}}return b}
function Vw(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;d==="SCRIPT"?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):d==="LINK"&&(c=a.href);Ab(document)&&a.setAttribute("nonce",Ab(document));return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=Mw(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),a.transferSize!==void 0&&a.transferSize===0)?!0:!1:!1}
function Ww(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=Ob(b,function(c){return c.name.indexOf(a+"//fonts.gstatic.com/s/")===0});
(b=Qb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&b.startTime>0&&b.responseEnd>0&&(Z("wffs",Lw(b.startTime)),Z("wffe",Lw(b.responseEnd)))}
function Xw(a){var b=Yw("aft",a);if(b)return b;b=R((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Yw(b[d],a);if(e)return e}return NaN}
function Yw(a,b){if(a=vw(b)[a])return typeof a==="number"?a:a[a.length-1]}
function Sw(a){var b=Yw("_start",a),c=Xw(a),d=S("enable_cow_info_csi")||!Nw;b&&c&&d&&(vq(Dw,new Cw(Math.round(c-b),a)),Nw=!0)}
function Zw(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=Rb(a,function(c){return c.name==="first-paint"}))return Lw(a.startTime)}var b;
S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")?b=Y.getEntriesByType("first-paint")[0].startTime:b=Y.timing.Lh;return b?Math.max(0,b):0}
;function $w(a,b){em(function(){Aw("").info.actionType=a;b&&am("TIMING_AFT_KEYS",b);am("TIMING_ACTION",a);var c=Uw();Object.keys(c).length>0&&Qw(c);c={isNavigation:!0,actionType:Bw[R("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};var d=R("PREVIOUS_ACTION");d&&(c.previousAction=Bw[d]||"LATENCY_ACTION_UNKNOWN");if(d=R("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=R("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=zu())&&d!=="UNDEFINED_CSN"&&(c.clientScreenNonce=d);d=Tw();if(d===1||d===-1)c.isVisible=!0;uw();tw();
c.loadType="cold";d=tw();var e=Kw(),f=Mw(),g=R("CSI_START_TIMESTAMP_MILLIS",0);g>0&&!S("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Z("srt",e.responseStart),d.prerender!==1&&Z("_start",f,void 0));d=Zw();d>0&&Z("fpt",d);d=Kw();d.isPerformanceNavigationTiming&&Qw({performanceNavigationTiming:!0},void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);d.redirectEnd-d.redirectStart>0&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,
void 0));d.domainLookupEnd-d.domainLookupStart>0&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));d.connectEnd-d.connectStart>0&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Mw()&&d.connectEnd-d.secureConnectionStart>0&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Ww();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in Pw)Pw.hasOwnProperty(h)&&(e=Pw[h],
Vw(h,e)&&d.push(e));if(d.length>0)for(c.resourceInfo=[],h=y(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Qw(c);c=ww();c.preLoggedGelInfos||(c.preLoggedGelInfos=[]);h=c.preLoggedGelInfos;c=xw();d=void 0;for(e=0;e<h.length;e++)if(f=h[e],f.loadType){d=f.loadType;break}if(uw().loadType==="cold"&&(c.loadType==="cold"||d==="cold")){d=vw();e=ww();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if(typeof d[k]==="number")Z(k,Yw(k));else if(S("log_repeated_ytcsi_ticks"))for(f=
y(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Z(k.slice(1),g);k={};d=!1;h=y(h);for(e=h.next();!e.done;e=h.next())d=e.value,vv(c,d),vv(k,d),d=!0;d&&Qw(k)}E("ytglobal.timingready_",!0);k=R("TIMING_ACTION");F("ytglobal.timingready_")&&k&&ax()&&Xw()&&Sw()})()}
function ax(a){return em(function(){return bx("_start",a)})()}
function cx(a,b,c){em(Qw)(a,b,c===void 0?!1:c)}
function dx(a,b,c){return em(Z)(a,b,c)}
function bx(a,b){return em(function(){var c=vw(b);return a in c})()}
function ex(a){if(!S("universal_csi_network_ticks"))return"";a=ac(bc(5,a))||"";for(var b=Object.keys(nq),c=0;c<b.length;c++){var d=b[c];if(a.includes(d))return d}return""}
function fx(a){if(!S("universal_csi_network_ticks"))return function(){};
var b=nq[a];return b?(gx(b),function(){var c=S("universal_csi_network_ticks")?(c=oq[a])?gx(c):!1:!1;return c}):function(){}}
function gx(a){return em(function(){if(bx(a))return!1;dx(a,void 0,void 0);return!0})()}
function hx(a){em(function(){if(!ax("attestation_challenge_fetch")||bx(a,"attestation_challenge_fetch"))return!1;dx(a,void 0,"attestation_challenge_fetch");return!0})()}
function ix(){em(function(){var a=yw();requestAnimationFrame(function(){setTimeout(function(){a===yw()&&dx("ol",void 0,void 0)},0)})})()}
var jx=window;jx.ytcsi&&(jx.ytcsi.infoGel=cx,jx.ytcsi.tick=dx);function kx(a,b){var c=C.apply(2,arguments);a=a===void 0?0:a;U.call(this,b,c);this.errorType=a;Object.setPrototypeOf(this,this.constructor.prototype)}
w(kx,U);var lx="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD shorts_prefetch".split(" "),mx=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse","type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.PlayerResponse"];function nx(a,b,c,d){this.u=a;this.fa=b;this.j=c;this.o=d;this.i=void 0;this.h=new Map;a.Xb||(a.Xb={});a.Xb=Object.assign({},rw,a.Xb)}
function ox(a,b,c,d){if(nx.instance!==void 0){if(d=nx.instance,a=[a!==d.u,b!==d.fa,c!==d.j,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new U("InnerTubeTransportService is already initialized",a);
}else nx.instance=new nx(a,b,c,d)}
function px(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=c===void 0?jn:c;var d=qx(a,b);return d?new ji(function(e,f){var g,h,k,l,m;return B(function(n){switch(n.h){case 1:return n.yield(d,2);case 2:g=n.i;h=g.u(b,void 0,c);if(!h){f(new U("Error: Failed to build request for command.",b));n.A(0);break}Uv(h.input);l=((k=h.Za)==null?void 0:k.mode)==="cors"?"cors":void 0;if(a.j.Ld){m=rx(h.config,l);n.A(4);break}return n.yield(sx(h.config,l),5);case 5:m=n.i;case 4:e(tx(a,h,m)),n.h=
0}})}):oi(new U("Error: No request builder found for command.",b))}
function ux(a,b){function c(){}
var d="/youtubei/v1/"+mw(bv);var e=e===void 0?{Mb:{identity:jn}}:e;var f=f===void 0?!0:f;c=fx(ex(d));b.context||(b.context=fw(void 0,f));return new ji(function(g){var h,k,l,m,n;return B(function(p){if(p.h==1)return h=Ju(d),k=rm(h)?"same-origin":"cors",a.j.Ld?(l=rx(e,k),p.A(2)):p.yield(sx(e,k),3);p.h!=2&&(l=p.i);m=Ku(Ju(d));n={input:m,Za:Lu(m),Ga:b,config:e};g(tx(a,n,l,c));p.h=0})})}
function vx(a,b,c){var d;if(b&&!(b==null?0:(d=b.sequenceMetaData)==null?0:d.skipProcessing)&&a.o){d=y(lx);for(var e=d.next();!e.done;e=d.next())e=e.value,a.o[e]&&a.o[e].handleResponse(b,c)}}
function tx(a,b,c,d){d=d===void 0?function(){}:d;
var e,f,g,h,k,l,m,n,p,t,v,x,z,G,J,ba,ca,Ma,Kb,ja,Ya,Oa,Pa,Na,eh,fh,is,js,ks,ls;return B(function(ia){switch(ia.h){case 1:ia.A(2);break;case 3:if((e=ia.i)&&!e.isExpired())return ia.return(Promise.resolve(e.h()));case 2:if(!((f=b)==null?0:(g=f.Ga)==null?0:g.context)){ia.A(4);break}h=b.Ga.context;ia.A(5);break;case 5:k=y([]),l=k.next();case 8:if(l.done){ia.A(4);break}m=l.value;return ia.yield(m.Mh(h),9);case 9:l=k.next();ia.A(8);break;case 4:if((n=a.i)==null||!n.Sh(b.input,b.Ga)){ia.A(12);break}return ia.yield(a.i.Hh(b.input,
b.Ga),13);case 13:return p=ia.i,vx(a,p,b),ia.return(p);case 12:return(x=(v=b.config)==null?void 0:v.Ph)&&a.h.has(x)?t=a.h.get(x):(z=JSON.stringify(b.Ga),ba=(J=(G=b.Za)==null?void 0:G.headers)!=null?J:{},b.Za=Object.assign({},b.Za,{headers:Object.assign({},ba,c)}),ca=Object.assign({},b.Za),b.Za.method==="POST"&&(ca=Object.assign({},ca,{body:z})),((Ma=b.config)==null?0:Ma.Xe)&&dx(b.config.Xe),Kb=function(){return a.fa.fetch(b.input,ca,b.config)},t=Kb(),x&&a.h.set(x,t)),ia.yield(t,14);
case 14:if((ja=ia.i)&&"error"in ja&&((Ya=ja)==null?0:(Oa=Ya.error)==null?0:Oa.details))for(Pa=ja.error.details,Na=y(Pa),eh=Na.next();!eh.done;eh=Na.next())fh=eh.value,(is=fh["@type"])&&mx.indexOf(is)>-1&&(delete fh["@type"],ja=fh);x&&a.h.has(x)&&a.h.delete(x);((js=b.config)==null?0:js.Ye)&&dx(b.config.Ye);if(ja||(ks=a.i)==null||!ks.vh(b.input,b.Ga)){ia.A(15);break}return ia.yield(a.i.Gh(b.input,b.Ga),16);case 16:ja=ia.i;case 15:return vx(a,ja,b),((ls=b.config)==null?0:ls.Ue)&&dx(b.config.Ue),d(),
ia.return(ja||void 0)}})}
function qx(a,b){a:{a=a.u;var c,d=(c=pt(b,Il))==null?void 0:c.signal;if(d&&a.Xb&&(c=a.Xb[d])){var e=c();break a}var f;if((c=(f=pt(b,Gl))==null?void 0:f.request)&&a.he&&(f=a.he[c])){e=f();break a}for(e in b)if(a.pd[e]&&(b=a.pd[e])){e=b();break a}e=void 0}if(e!==void 0)return Promise.resolve(e)}
function sx(a,b){var c,d,e,f;return B(function(g){if(g.h==1){e=(c=a)==null?void 0:(d=c.Mb)==null?void 0:d.sessionIndex;var h=g.yield;var k=hn(0,{sessionIndex:e});if(!(k instanceof ji)){var l=new ji(hi);ki(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},gw(b),f)))})}
function rx(a,b){var c;a=a==null?void 0:(c=a.Mb)==null?void 0:c.sessionIndex;c=hn(0,{sessionIndex:a});return Object.assign({},gw(b),c)}
;var wx=new Js("INNERTUBE_TRANSPORT_TOKEN");function xx(){}
w(xx,ow);xx.prototype.j=function(){return hv};
xx.prototype.i=function(a){return pt(a,Sl)||void 0};
xx.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
fa.Object.defineProperties(xx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function yx(){}
w(yx,ow);yx.prototype.j=function(){return iv};
yx.prototype.i=function(a){return pt(a,Rl)||void 0};
yx.prototype.h=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
fa.Object.defineProperties(yx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});var zx=new Js("SHARE_CLIENT_PARAMS_PROVIDER_TOKEN");function Ax(a){this.M=a}
w(Ax,ow);Ax.prototype.j=function(){return cv};
Ax.prototype.i=function(a){return pt(a,Ml)||pt(a,Nl)||pt(a,Ll)};
Ax.prototype.h=function(a,b){b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);if(b.clientParamIdentifier){var c;if((c=this.M)==null?0:c.h(b.clientParamIdentifier))a.clientParams=this.M.i(b.clientParamIdentifier)}};
Ax[Is]=[zx];function Bx(){}
w(Bx,ow);Bx.prototype.j=function(){return ev};
Bx.prototype.i=function(a){return pt(a,Kl)||void 0};
Bx.prototype.h=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
fa.Object.defineProperties(Bx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Cx(){}
w(Cx,ow);Cx.prototype.j=function(){return fv};
Cx.prototype.i=function(a){return pt(a,Ql)||void 0};
Cx.prototype.h=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function Dx(){}
w(Dx,ow);Dx.prototype.j=function(){return gv};
Dx.prototype.i=function(a){return pt(a,Pl)||void 0};
Dx.prototype.h=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function Ex(){}
w(Ex,ow);Ex.prototype.j=function(){return dv};
Ex.prototype.i=function(a){return pt(a,Ol)};
Ex.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Fx=new Js("FETCH_FN_TOKEN"),Gx=new Js("PARSE_FN_TOKEN");var Hx=new Js("NETWORK_SLI_TOKEN");function Ix(a,b,c){this.h=a;this.i=b;this.j=c}
Ix.prototype.fetch=function(a,b,c){var d=this,e,f,g;return B(function(h){e=Jx(d,a,b);g=(f=d.i)!=null?f:fetch;return h.return(g(e).then(function(k){return d.handleResponse(k,c)}).catch(function(k){W(k);
if((c==null?0:c.re)&&k instanceof kx&&k.errorType===1)return Promise.reject(k)}))})};
function Jx(a,b,c){if(a.h){var d=ac(bc(5,mc(b,"key")))||"/UNKNOWN_PATH";a.h.start(d)}a=c;S("wug_networking_gzip_request")&&(a=Xq(c));return new window.Request(b,a)}
Ix.prototype.handleResponse=function(a,b){var c,d=(c=this.j)!=null?c:JSON.parse;c=a.text().then(function(e){if((b==null?0:b.He)&&a.ok)return Hf(b.He,e);e=e.replace(")]}'","");if((b==null?0:b.re)&&e)try{var f=d(e)}catch(h){throw new kx(1,"JSON parsing failed after fetch");}var g;return(g=f)!=null?g:d(e)});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Bh(),c=c.then(function(e){W(new U("Error: API fetch failed",a.status,a.url,e));return Object.assign({},e,{errorMetadata:{status:a.status}})}));
return c};
Ix[Is]=[new Ks(Hx),new Ks(Fx),new Ks(Gx)];var Kx=new Js("NETWORK_MANAGER_TOKEN");var Lx;function Mx(){var a,b;if(!Lx){var c=Qs();Ms(c,{zc:Kx,Od:Ix});var d={pd:{feedbackEndpoint:jw(Bx),modifyChannelNotificationPreferenceEndpoint:jw(Cx),playlistEditEndpoint:jw(Dx),shareEntityEndpoint:jw(Ax),subscribeEndpoint:jw(xx),unsubscribeEndpoint:jw(yx),webPlayerShareEntityServiceEndpoint:jw(Ex)}},e=ew(),f={};e&&(f.client_location=e);a===void 0&&(a=gn());b===void 0&&(b=c.resolve(Kx));ox(d,b,a,f);Ms(c,{zc:wx,Pd:nx.instance});Lx=c.resolve(wx)}return Lx}
;function Nx(a){var b=new ij;if(a.interpreterJavascript){var c=yl(a.interpreterJavascript);c=Db(c).toString();var d=new gj;Ef(d,6,c);zf(b,gj,1,d)}else a.interpreterUrl&&(c=zl(a.interpreterUrl),c=kb(c).toString(),d=new hj,Ef(d,4,c),zf(b,hj,2,d));a.interpreterHash&&Ff(b,3,a.interpreterHash);a.program&&Ff(b,4,a.program);a.globalName&&Ff(b,5,a.globalName);a.clientExperimentsStateBlob&&Ff(b,7,a.clientExperimentsStateBlob);return b}
function Ox(a){var b={};a=y(a.split("&"));for(var c=a.next();!c.done;c=a.next())c=c.value.split("="),c.length===2&&(b[c[0]]=c[1]);return b}
;function wc(){if(S("bg_st_hr"))return"havuokmhhs-0";var a,b=((a=performance)==null?void 0:a.timeOrigin)||0;return"havuokmhhs-"+Math.floor(b)}
function Px(a){this.h=a}
Px.prototype.bindInnertubeChallengeFetcher=function(a){this.h.bicf(a)};
Px.prototype.registerChallengeFetchedCallback=function(a){this.h.bcr(a)};
Px.prototype.getLatestChallengeResponse=function(){return this.h.blc()};
function Qx(){return new Promise(function(a){var b=window.top;b.ntpevasrs!==void 0?a(new Px(b.ntpevasrs)):(b.ntpqfbel===void 0&&(b.ntpqfbel=[]),b.ntpqfbel.push(function(c){a(new Px(c))}))})}
;var Rx=[],Sx=!1;function Tx(){if(!S("disable_biscotti_fetch_for_ad_blocker_detection")&&!S("disable_biscotti_fetch_entirely_for_all_web_clients")&&Mu()){var a=R("PLAYER_VARS",{});if(pg(a)!="1"&&!Ou(a)){var b=function(){Sx=!0;"google_ad_status"in window?am("DCLKSTAT",1):am("DCLKSTAT",2)};
try{lv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Rx.push(Kj.pa(function(){if(!(Sx||"google_ad_status"in window)){try{pv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Sx=!0;am("DCLKSTAT",3)}},5E3))}}}
function Ux(){var a=Number(R("DCLKSTAT",0));return isNaN(a)?0:a}
;function Vx(a){this.h=a}
[new Vx("b.f_"),new Vx("j.s_"),new Vx("r.s_"),new Vx("e.h_"),new Vx("i.s_"),new Vx("s.t_"),new Vx("p.h_"),new Vx("s.i_"),new Vx("f.i_"),new Vx("a.b_"),new Vx("a.o_"),new Vx("g.o_"),new Vx("p.i_"),new Vx("p.m_"),new Vx("n.k_"),new Vx("i.f_"),new Vx("a.s_"),new Vx("m.c_"),new Vx("n.h_"),new Vx("o.p_")].reduce(function(a,b){a[b.h]=b;return a},{});function Wx(a,b,c){var d=this;this.network=a;this.options=b;this.o=c;this.h=null;if(b.Xh){var e=new mj;this.h=e.promise;D.ytAtRC&&Kj.Ra(function(){var f,g;return B(function(h){if(h.h==1){if(!D.ytAtRC)return h.return();f=Xx(null);return h.yield(d.gb(f),2)}g=h.i;D.ytAtRC&&D.ytAtRC(JSON.stringify(g));h.h=0})},2);
Qx().then(function(f){var g,h,k,l;return B(function(m){if(m.h==1)return f.bindInnertubeChallengeFetcher(function(n){return d.gb(Xx(n))}),m.yield(vc(),2);
g=m.i;h=f.getLatestChallengeResponse();k=h.challenge;if(!k)throw Error("BGE_MACIL");l={challenge:k,eb:Ox(k),vm:g,bgChallenge:new ij};e.resolve(l);f.registerChallengeFetchedCallback(function(n){n=n.challenge;if(!n)throw Error("BGE_MACR");n={challenge:n,eb:Ox(n),vm:g,bgChallenge:new ij};d.h=Promise.resolve(n)});
m.h=0})})}else b.preload&&Yx(this,new Promise(function(f){En(function(){f(Zx(d))},0)}))}
Wx.prototype.j=function(){var a=this;return B(function(b){return b.h==1?b.yield(Promise.race([a.h,null]),2):b.return(!!b.i)})};
Wx.prototype.i=function(a,b,c){var d=this,e,f,g;return B(function(h){d.h===null&&Yx(d,Zx(d));e=!1;f={};g=function(){var k,l,m;return B(function(n){switch(n.h){case 1:return n.yield(d.h,2);case 2:k=n.i;f.challenge=k.challenge;if(!k.vm){"c1a"in k.eb&&(f.error="ATTESTATION_ERROR_VM_NOT_INITIALIZED");n.A(3);break}l=Object.assign({},{c:k.challenge,e:a},b);ya(n,4);e=!0;if(S("attbs")&&!S("attmusi")){m=k.vm.ed({vb:l});n.A(6);break}return n.yield(k.vm.snapshot({vb:l}),7);case 7:m=n.i;case 6:m?f.webResponse=
m:f.error="ATTESTATION_ERROR_VM_NO_RESPONSE";za(n,3);break;case 4:Aa(n),f.error="ATTESTATION_ERROR_VM_INTERNAL_ERROR";case 3:if(a==="ENGAGEMENT_TYPE_PLAYBACK"){var p=k.eb,t={};p.c6a&&(t.reportingStatus=String(Number(p.c)^Ux()));p.c6b&&(t.broadSpectrumDetectionResult=String(Number(p.c)^Number(R("CATSTAT",0))));f.adblockReporting=t}return n.return(f)}})};
return h.return(Promise.race([g(),$x(c,function(){var k=Object.assign({},f);e&&(k.error="ATTESTATION_ERROR_VM_TIMEOUT");return k})]))})};
function Xx(a){var b={engagementType:"ENGAGEMENT_TYPE_UNBOUND"};a&&(b.interpreterHash=a);return b}
function Zx(a,b){b=b===void 0?0:b;var c,d,e,f,g,h,k,l,m,n,p,t;return B(function(v){switch(v.h){case 1:c=Xx(rj().h);if(S("att_fet_ks"))return ya(v,7),v.yield(a.gb(c),9);ya(v,4);return v.yield(ay(a,c),6);case 6:g=v.i;e=g.Pe;f=g.Qe;d=g;za(v,3);break;case 4:return Aa(v),W(Error("Failed to fetch attestation challenge after "+(b+" attempts; not retrying for 24h."))),by(a,864E5),v.return({challenge:"",eb:{},vm:void 0,bgChallenge:void 0});case 9:d=v.i;if(!d)throw Error("Fetching Attestation challenge returned falsy");
if(!d.challenge)throw Error("Missing Attestation challenge");e=d.challenge;f=Ox(e);if("c1a"in f&&(!d.bgChallenge||!d.bgChallenge.program))throw Error("Expected bg challenge but missing.");za(v,3);break;case 7:h=Aa(v);W(h);b++;if(b>=5)return W(Error("Failed to fetch attestation challenge after "+(b+" attempts; not retrying for 24h."))),by(a,864E5),v.return({challenge:"",eb:{},vm:void 0,bgChallenge:void 0});k=1E3*Math.pow(2,b-1)+Math.random()*1E3;return v.return(new Promise(function(x){En(function(){x(Zx(a,
b))},k)}));
case 3:l=Number(f.t)||7200;by(a,l*1E3);m=void 0;if(!("c1a"in f&&d.bgChallenge)){v.A(10);break}n=Nx(d.bgChallenge);ya(v,11);return v.yield(sj(rj(),n),13);case 13:za(v,12);break;case 11:return p=Aa(v),W(p),v.return({challenge:e,eb:f,vm:m,bgChallenge:n});case 12:return ya(v,14),m=new oj({challenge:n,zd:{Da:"aGIf"}}),v.yield(m.Zc,16);case 16:za(v,10);break;case 14:t=Aa(v),W(t),m=void 0;case 10:return v.return({challenge:e,eb:f,vm:m,bgChallenge:n})}})}
Wx.prototype.gb=function(a){var b=this,c;return B(function(d){c=b.o;if(!c||c.ta())return d.return(b.network.gb(a));hx("att_pna");return d.return(new Promise(function(e){Ph(c,"publicytnetworkstatus-online",function(){b.network.gb(a).then(e)})}))})};
function cy(a){if(!a)throw Error("Fetching Attestation challenge returned falsy");if(!a.challenge)throw Error("Missing Attestation challenge");var b=a.challenge,c=Ox(b);if("c1a"in c&&(!a.bgChallenge||!a.bgChallenge.program))throw Error("Expected bg challenge but missing.");return Object.assign({},a,{Pe:b,Qe:c})}
function ay(a,b){var c,d,e,f,g;return B(function(h){switch(h.h){case 1:c=void 0,d=0,e={};case 2:if(!(d<5)){h.A(4);break}if(!(d>0)){h.A(5);break}e.md=1E3*Math.pow(2,d-1)+Math.random()*1E3;return h.yield(new Promise(function(k){return function(l){En(function(){l(void 0)},k.md)}}(e)),5);
case 5:return ya(h,7),h.yield(a.gb(b),9);case 9:return f=h.i,h.return(cy(f));case 7:c=g=Aa(h),g instanceof Error&&W(g);case 8:d++;e={md:void 0};h.A(2);break;case 4:throw c;}})}
function Yx(a,b){a.h=b}
function dy(a){var b,c,d;return B(function(e){if(e.h==1)return e.yield(Promise.race([a.h,null]),2);b=e.i;var f=Zx(a);a.h=f;(c=b)==null||(d=c.vm)==null||d.dispose();e.h=0})}
function by(a,b){function c(){var e;return B(function(f){e=d-Date.now();return e<1E3?f.yield(dy(a),0):(En(c,Math.min(e,6E4)),f.A(0))})}
var d=Date.now()+b;c()}
function $x(a,b){return new Promise(function(c){En(function(){c(b())},a)})}
;function ey(){this.h=Mx()}
ey.prototype.gb=function(a){hx("att_fsr");return ux(this.h,a).then(function(b){hx("att_frr");return b})};function fy(){var a,b,c;return B(function(d){if(d.h==1)return a=Qs().resolve(wx),a?d.yield(px(a),2):(W(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return W(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.yh;return d.return(c)}W(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;function gy(){var a;return(a=R("WEB_PLAYER_CONTEXT_CONFIGS"))==null?void 0:a.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER}
;var hy=D.caches,iy;function jy(a){var b=a.indexOf(":");return b===-1?{Cd:a}:{Cd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function ky(){return B(function(a){if(iy!==void 0)return a.return(iy);iy=new Promise(function(b){var c;return B(function(d){switch(d.h){case 1:return ya(d,2),d.yield(hy.open("test-only"),4);case 4:return d.yield(hy.delete("test-only"),5);case 5:za(d,3);break;case 2:if(c=Aa(d),c instanceof Error&&c.name==="SecurityError")return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(iy)})}
function ly(a){var b,c,d,e,f,g,h;B(function(k){if(k.h==1)return k.yield(ky(),2);if(k.h!=3){if(!k.i)return k.return(!1);b=[];return k.yield(hy.keys(),3)}c=k.i;d=y(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=jy(f),h=g.datasyncId,!h||a.includes(h)||b.push(hy.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(m){return m})}))})}
function my(){var a,b,c,d,e,f,g;return B(function(h){if(h.h==1)return h.yield(ky(),2);if(h.h!=3){if(!h.i)return h.return(!1);a=Cn("cache contains other");return h.yield(hy.keys(),3)}b=h.i;c=y(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=jy(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function ny(){try{return!!self.sessionStorage}catch(a){return!1}}
;function oy(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function py(a){if(ny()){var b=Object.keys(window.sessionStorage);b=y(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=oy(c);d===void 0||a.includes(d)||self.sessionStorage.removeItem(c)}}}
function qy(){if(!ny())return!1;var a=Cn(),b=Object.keys(window.sessionStorage);b=y(b);for(var c=b.next();!c.done;c=b.next())if(c=oy(c.value),c!==void 0&&c!==a)return!0;return!1}
;function ry(){fy().then(function(a){a&&(Ip(a),ly(a),Rv(a),py(a))})}
function sy(){var a=new Pr;Kj.pa(function(){var b,c,d,e,f;return B(function(g){switch(g.h){case 1:if(S("ytidb_clear_optimizations_killswitch")){g.A(2);break}b=Cn("clear");if(b.startsWith("V")&&b.endsWith("||")){var h=[b];Ip(h);ly(h);Rv(h);py(h);return g.return()}c=Sv();d=qy();return g.yield(my(),3);case 3:return e=g.i,g.yield(Jp(),4);case 4:if(f=g.i,!(c||d||e||f))return g.return();case 2:a.ta()?ry():Ph(a,"publicytnetworkstatus-online",ry),g.h=0}})})}
;var ty=["www.youtube-nocookie.com","www.youtubeeducation.com","youtube.googleapis.com"];function uy(){this.state=1;this.vm=null;this.h=void 0}
r=uy.prototype;r.initialize=function(a,b,c,d){this.h=d;if(a.program){var e;d=(e=a.interpreterUrl)!=null?e:null;if(a.interpreterSafeScript)e=yl(a.interpreterSafeScript);else{var f;e=(f=a.interpreterScript)!=null?f:null}a.interpreterSafeUrl&&(d=zl(a.interpreterSafeUrl).toString());vy(this,e,d,a.program,b,c)}else W(Error("Cannot initialize botguard without program"))};
function vy(a,b,c,d,e,f){var g=g===void 0?"trayride":g;c?(a.state=2,lv(c,function(){window[g]?wy(a,d,g,e):(a.state=3,nv(c),W(new U("Unable to load Botguard","from "+c)))},f)):b?(f=yg("SCRIPT"),b instanceof Bb?(f.textContent=Db(b),Eb(f)):f.textContent=b,f.nonce=Ab(document),document.head.appendChild(f),document.head.removeChild(f),window[g]?wy(a,d,g,e):(a.state=4,W(new U("Unable to load Botguard from JS")))):W(new U("Unable to load VM; no url or JS provided"))}
r.isLoading=function(){return this.state===2};
function wy(a,b,c,d){a.state=5;var e=!!a.h&&ty.includes(cc(a.h)||"");try{var f=new oj({program:b,globalName:c,zd:{disable:!S("att_web_record_metrics")||!S("att_skip_metrics_for_cookieless_domains_ks")&&e,Da:"aGIf"}});f.Zc.then(function(){a.state=6;d&&d(b)});
a.Yc(f)}catch(g){a.state=7,g instanceof Error&&W(g)}}
r.invoke=function(a){a=a===void 0?{}:a;return this.hd()?this.Rd({vb:a}):null};
r.dispose=function(){this.Yc(null);this.state=8};
r.hd=function(){return!!this.vm};
r.Rd=function(a){return this.vm.ed(a)};
r.Yc=function(a){sc(this.vm);this.vm=a};function xy(){var a=F("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function yy(){uy.apply(this,arguments)}
w(yy,uy);yy.prototype.Yc=function(a){var b;(b=xy())==null||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.ed.bind(a)},E("yt.abuse.playerAttLoader",b),E("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(E("yt.abuse.playerAttLoader",null),E("yt.abuse.playerAttLoaderRun",null))};
yy.prototype.hd=function(){return!!xy()};
yy.prototype.Rd=function(a){return xy().bgvmc(a)};function zy(a){$s.call(this,a===void 0?"document_active":a);var b=this;this.o=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.G},{from:"document_active",to:"document_disposed",action:this.u},{from:"document_disposed_preventable",to:"document_disposed",action:this.u},{from:"document_disposed_preventable",to:"flush_logs",action:this.M},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.M},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
w(zy,$s);zy.prototype.G=function(a,b){if(!this.h.get("document_disposed_preventable")){a(b==null?void 0:b.event);var c,d;if((b==null?0:(c=b.event)==null?0:c.defaultPrevented)||(b==null?0:(d=b.event)==null?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
zy.prototype.u=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b==null?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
zy.prototype.M=function(a,b){a(b==null?void 0:b.event);this.transition("document_active")};
zy.prototype.i=function(){this.h=new Map};function Ay(a){$s.call(this,a===void 0?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.M},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.u},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.M},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.M},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.u},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.u},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){document.visibilityState==="visible"?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
S("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
w(Ay,$s);Ay.prototype.i=function(a,b){a(b==null?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Ay.prototype.h=function(a,b){a(b==null?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Ay.prototype.u=function(a,b){a(b==null?void 0:b.event)};
Ay.prototype.M=function(a,b){a(b==null?void 0:b.event)};function By(){this.o=new zy;this.u=new Ay}
By.prototype.install=function(){var a=C.apply(0,arguments),b=this;a.forEach(function(c){b.o.install(c)});
a.forEach(function(c){b.u.install(c)})};function Cy(){this.o=[];this.i=new Map;this.h=new Map;this.j=new Set}
Cy.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=c===void 0?0:c;if(d)if(c=zu(c===void 0?0:c)){a=this.client;d=new su({trackingParams:d});var e=void 0;if(S("no_client_ve_attach_unless_shown")){var f=Mv(d,c);Iv.set(f,!0);Nv(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=Lv({cttAuthInfo:Bu(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);c==="UNDEFINED_CSN"?Ov("visualElementGestured",f,d):a?Zt("visualElementGestured",d,a,f):to("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
Cy.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new su({trackingParams:a}),b,c===void 0?0:c)};
Cy.prototype.visualElementStateChanged=function(a,b,c){c=c===void 0?0:c;if(c===0&&this.j.has(c))this.o.push([a,b]);else{var d=c;d=d===void 0?0:d;c=zu(d);a||(a=(a=wu(d===void 0?0:d))?new su({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=Lv({cttAuthInfo:Bu(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},c==="UNDEFINED_CSN"?Ov("visualElementStateChanged",d,b):a?Zt("visualElementStateChanged",b,a,d):to("visualElementStateChanged",b,d))}};
function Dy(a,b){if(b===void 0)for(var c=yu(),d=0;d<c.length;d++)c[d]!==void 0&&Dy(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&Kv(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function Ey(){By.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));S("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a));S("web_log_cfg_cee_ks")||En(Fy)}
w(Ey,By);Ey.prototype.j=function(){to("finalPayload",{csn:zu()})};
Ey.prototype.h=function(){mu(nu)};
Ey.prototype.i=function(){var a=Dy;Cy.instance||(Cy.instance=new Cy);a(Cy.instance)};
function Fy(){var a=R("CLIENT_EXPERIMENT_EVENTS");if(a){var b=de();a=y(a);for(var c=a.next();!c.done;c=a.next())c=c.value,b(c)&&to("genericClientExperimentEvent",{eventType:c});delete $l.CLIENT_EXPERIMENT_EVENTS}}
;function Gy(){}
function Hy(){var a=F("ytglobal.storage_");a||(a=new Gy,E("ytglobal.storage_",a));return a}
Gy.prototype.estimate=function(){var a,b,c;return B(function(d){a=navigator;return((b=a.storage)==null?0:b.estimate)?d.return(a.storage.estimate()):((c=a.webkitTemporaryStorage)==null?0:c.queryUsageAndQuota)?d.return(Iy()):d.return()})};
function Iy(){var a=navigator;return new Promise(function(b,c){var d;(d=a.webkitTemporaryStorage)!=null&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
E("ytglobal.storageClass_",Gy);function ro(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;self.document===void 0||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=.2}
ro.prototype.Ha=function(a){this.handleError(a)};
ro.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":S("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":S("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Jy(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=.1&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=
Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function Jy(a,b){Hy().estimate().then(function(c){c=Object.assign({},b,{isSw:self.document===void 0,isIframe:self!==self.top,deviceStorageUsageMbytes:Ky(c==null?void 0:c.usage),deviceStorageQuotaMbytes:Ky(c==null?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function Ky(a){return typeof a==="undefined"?"-1":String(Math.ceil(a/1048576))}
;var Ly={},My=(Ly["api.invalidparam"]=2,Ly.auth=150,Ly["drm.auth"]=150,Ly["heartbeat.net"]=150,Ly["heartbeat.servererror"]=150,Ly["heartbeat.stop"]=150,Ly["html5.unsupportedads"]=5,Ly["fmt.noneavailable"]=5,Ly["fmt.decode"]=5,Ly["fmt.unplayable"]=5,Ly["html5.missingapi"]=5,Ly["html5.unsupportedlive"]=5,Ly["drm.unavailable"]=5,Ly["mrm.blocked"]=151,Ly["embedder.identity.denied"]=152,Ly);var Ny=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn playmuted muted_autoplay_duration_mode".split(" "));function Oy(a){return(a.search("cue")===0||a.search("load")===0)&&a!=="loadModule"}
function Py(a,b,c){if(typeof a==="string")return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=y(Ny);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function Qy(a,b,c,d){if(Ra(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};typeof a==="string"&&a.length===16?b.list="PL"+a:b.playlist=a;return b}
;function Ry(a){H.call(this);var b=this;this.api=a;this.Y=this.u=!1;this.D=[];this.P={};this.j=[];this.i=[];this.Z=!1;this.sessionId=this.h=null;this.targetOrigin="*";this.U=S("web_player_split_event_bus_iframe");this.o=R("POST_MESSAGE_ORIGIN")||document.location.protocol+"//"+document.location.hostname;this.G=function(c){a:if(!(b.o!=="*"&&c.origin!==b.o||b.h&&c.source!==b.h||typeof c.data!=="string")){try{var d=JSON.parse(c.data)}catch(h){break a}if(d)switch(d.event){case "listening":var e=c.source;
c=c.origin;d=d.id;c!=="null"&&(b.o=b.targetOrigin=c);b.h=e;b.sessionId=d;if(b.u){b.Y=!0;b.u=!1;b.sendMessage("initialDelivery",Sy(b));b.sendMessage("onReady");e=y(b.D);for(d=e.next();!d.done;d=e.next())Ty(b,d.value);b.D=[]}break;case "command":if(e=d.func,d=d.args,e==="addEventListener"&&d)e=d[0],d=c.origin,e==="onReady"?b.api.logApiCall(e+" invocation",d):e==="onError"&&b.Z&&(b.api.logApiCall(e+" invocation",d,b.errorCode),b.errorCode=void 0),b.api.logApiCall(e+" registration",d),b.P[e]||e==="onReady"||
(c=Uy(b,e,d),b.i.push({eventType:e,listener:c,origin:d}),b.U?b.api.handleExternalCall("addEventListener",[e,c],d):b.api.addEventListener(e,c),b.P[e]=!0);else if(c=c.origin,b.api.isExternalMethodAvailable(e,c)){d=d||[];if(d.length>0&&Oy(e)){var f=d;if(Ra(f[0])&&!Array.isArray(f[0]))var g=f[0];else switch(g={},e){case "loadVideoById":case "cueVideoById":g=Py(f[0],f[1]!==void 0?Number(f[1]):void 0,f[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":g=f[0];typeof g==="string"&&(g={mediaContentUrl:g,
startSeconds:f[1]!==void 0?Number(f[1]):void 0,suggestedQuality:f[2]});c:{if((f=g.mediaContentUrl)&&(f=/\/([ve]|embed)\/([^#?]+)/.exec(f))&&f[2]){f=f[2];break c}f=null}g.videoId=f;g=Py(g);break;case "loadPlaylist":case "cuePlaylist":g=Qy(f[0],f[1],f[2],f[3])}d.length=1;d[0]=g}b.api.handleExternalCall(e,d,c);Oy(e)&&Vy(b,Sy(b))}}}};
Wy.addEventListener("message",this.G);if(a=R("WIDGET_ID"))this.sessionId=a;Xy(this,"onReady",function(){b.u=!0;var c=b.api.getVideoData();if(!c.isPlayable){b.Z=!0;c=c.errorCode;var d=d===void 0?5:d;b.errorCode=c?My[c]||d:d;b.sendMessage("onError",Number(b.errorCode))}});
Xy(this,"onVideoProgress",this.kf.bind(this));Xy(this,"onVolumeChange",this.lf.bind(this));Xy(this,"onApiChange",this.cf.bind(this));Xy(this,"onPlaybackQualityChange",this.gf.bind(this));Xy(this,"onPlaybackRateChange",this.hf.bind(this));Xy(this,"onStateChange",this.jf.bind(this));Xy(this,"onWebglSettingsChanged",this.mf.bind(this));Xy(this,"onCaptionsTrackListChanged",this.df.bind(this));Xy(this,"captionssettingschanged",this.ef.bind(this))}
w(Ry,H);function Vy(a,b){a.sendMessage("infoDelivery",b)}
r=Ry.prototype;r.sendMessage=function(a,b){a={event:a,info:b===void 0?null:b};this.Y?Ty(this,a):this.D.push(a)};
function Uy(a,b,c){return function(d){b==="onError"?a.api.logApiCall(b+" invocation",c,d):a.api.logApiCall(b+" invocation",c);a.sendMessage(b,d)}}
function Xy(a,b,c){a.j.push({eventType:b,listener:c});a.api.addEventListener(b,c)}
function Sy(a){if(!a.api)return null;var b=a.api.getApiInterface();Sb(b,"getVideoData");for(var c={apiInterface:b},d=0,e=b.length;d<e;d++){var f=b[d];if(f.search("get")===0||f.search("is")===0){var g=0;f.search("get")===0?g=3:f.search("is")===0&&(g=2);g=f.charAt(g).toLowerCase()+f.substring(g+1);try{var h=a.api[f]();c[g]=h}catch(k){}}}c.videoData=a.api.getVideoData();c.currentTimeLastUpdated_=Date.now()/1E3;return c}
r.jf=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&!S("embeds_enable_vfsyb")&&(a.storyboardFormat=this.api.getStoryboardFormat());Vy(this,a)};
r.gf=function(a){a={playbackQuality:a};this.api.getAvailableQualityLevels&&(a.availableQualityLevels=this.api.getAvailableQualityLevels());this.api.getPreferredQuality&&(a.preferredQuality=this.api.getPreferredQuality());Vy(this,a)};
r.hf=function(a){Vy(this,{playbackRate:a})};
r.cf=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
r.lf=function(){Vy(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
r.kf=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Vy(this,a)};
r.mf=function(){Vy(this,{sphericalProperties:this.api.getSphericalProperties()})};
r.df=function(){if(this.api.getCaptionTracks){var a={captionTracks:this.api.getCaptionTracks()};Vy(this,a)}};
r.ef=function(){if(this.api.getSubtitlesUserSettings){var a={subtitlesUserSettings:this.api.getSubtitlesUserSettings()};Vy(this,a)}};
function Ty(a,b){if(a.h){b.channel="widget";a.sessionId&&(b.id=a.sessionId);try{var c=JSON.stringify(b);a.h.postMessage(c,a.targetOrigin)}catch(d){W(d)}}}
r.ba=function(){H.prototype.ba.call(this);Wy.removeEventListener("message",this.G);for(var a=0;a<this.j.length;a++){var b=this.j[a];this.api.removeEventListener(b.eventType,b.listener)}this.j=[];for(a=0;a<this.i.length;a++)b=this.i[a],this.U?this.api.handleExternalCall("removeEventListener",[b.eventType,b.listener],b.origin):this.api.removeEventListener(b.eventType,b.listener);this.i=[]};
var Wy=window;function Yy(a,b,c){H.call(this);var d=this;this.api=a;this.id=b;this.origin=c;this.h={};this.j=S("web_player_split_event_bus_iframe");this.i=function(e){a:if(e.origin===d.origin){var f=e.data;if(typeof f==="string"){try{f=JSON.parse(f)}catch(k){break a}if(f.command){var g=f.command;f=f.data;e=e.origin;if(!d.ea){var h=f||{};switch(g){case "addEventListener":typeof h.event==="string"&&d.addListener(h.event,e);break;case "removeEventListener":typeof h.event==="string"&&d.removeListener(h.event,e);break;
default:d.api.isReady()&&d.api.isExternalMethodAvailable(g,e||null)&&(f=Zy(g,f||{}),f=d.api.handleExternalCall(g,f,e||null),(f=$y(g,f))&&az(d,g,f))}}}}}};
bz.addEventListener("message",this.i);az(this,"RECEIVING")}
w(Yy,H);r=Yy.prototype;r.addListener=function(a,b){if(!(a in this.h)){var c=this.ff.bind(this,a);this.h[a]=c;this.addEventListener(a,c,b)}};
r.ff=function(a,b){this.ea||az(this,a,cz(a,b))};
r.removeListener=function(a,b){a in this.h&&(this.removeEventListener(a,this.h[a],b),delete this.h[a])};
r.addEventListener=function(a,b,c){this.j?a==="onReady"?this.api.addEventListener(a,b):this.api.handleExternalCall("addEventListener",[a,b],c||null):this.api.addEventListener(a,b)};
r.removeEventListener=function(a,b,c){this.j?a==="onReady"?this.api.removeEventListener(a,b):this.api.handleExternalCall("removeEventListener",[a,b],c||null):this.api.removeEventListener(a,b)};
function Zy(a,b){switch(a){case "loadVideoById":return[Py(b)];case "cueVideoById":return[Py(b)];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return[Qy(b)];case "cuePlaylist":return[Qy(b)];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];case "setShuffle":return[b.shufflePlaylist];
case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function $y(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
function cz(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}if(b!=null)return{value:b}}
function az(a,b,c){a.ea||(b={id:a.id,command:b},c&&(b.data=c),dz.postMessage(JSON.stringify(b),a.origin))}
r.ba=function(){bz.removeEventListener("message",this.i);for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);H.prototype.ba.call(this)};
var bz=window,dz=window.parent;var ez=new yy;function fz(){return ez.hd()}
function gz(a){a=a===void 0?{}:a;return ez.invoke(a)}
;function hz(a,b,c,d,e){H.call(this);var f=this;this.D=b;this.webPlayerContextConfig=d;this.Ec=e;this.Pa=!1;this.api={};this.oa=this.u=null;this.U=new N;this.h={};this.Z=this.xa=this.elementId=this.Qa=this.config=null;this.Y=!1;this.j=this.G=null;this.Fa={};this.Fc=["onReady"];this.lastError=null;this.rb=NaN;this.P={};this.ha=0;this.i=this.o=a;uc(this,this.U);iz(this);c?this.ha=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&(jz(this),kz(this))}
w(hz,H);r=hz.prototype;r.getId=function(){return this.D};
r.loadNewVideoConfig=function(a){if(!this.ea){this.ha&&(clearTimeout(this.ha),this.ha=0);var b=a||{};b instanceof av||(b=new av(b));this.config=b;this.setConfig(a);kz(this);this.isReady()&&lz(this)}};
function jz(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;a.elementId==="video-player"&&(a.elementId=a.D,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.D:a.config.attrs.id=a.D);var c;((c=a.i)==null?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
r.setConfig=function(a){this.Qa=a;this.config=mz(a);jz(this);if(!this.xa){var b;this.xa=nz(this,((b=this.config.args)==null?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if((c=this.config)==null?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=Ej(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=Ej(Number(a)||a))};
function lz(a){if(a.config&&a.config.loaded!==!0)if(a.config.loaded=!0,!a.config.args||a.config.args.autoplay!=="0"&&a.config.args.autoplay!==0&&a.config.args.autoplay!==!1){var b;a.api.loadVideoByPlayerVars((b=a.config.args)!=null?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function oz(a){var b=!0,c=pz(a);c&&a.config&&(b=c.dataset.version===qz(a));return b&&!!F("yt.player.Application.create")}
function kz(a){if(!a.ea&&!a.Y){var b=oz(a);if(b&&(pz(a)?"html5":null)==="html5")a.Z="html5",a.isReady()||rz(a);else if(sz(a),a.Z="html5",b&&a.j&&a.o)a.o.appendChild(a.j),rz(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.G=function(){c=!0;var d=tz(a,"player_bootstrap_method")?F("yt.player.Application.createAlternate")||F("yt.player.Application.create"):F("yt.player.Application.create");var e=a.config?mz(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig,a.Ec);rz(a)};
a.Y=!0;b?a.G():(lv(qz(a),a.G),(b=uz(a))&&sv(b||""),vz(a)&&!c&&E("yt.player.Application.create",null))}}}
function pz(a){var b=xg(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function rz(a){if(!a.ea){var b=pz(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Y=!1;if(!tz(a,"html5_remove_not_servable_check_killswitch")){var d;if((b==null?0:b.isNotServable)&&a.config&&(b==null?0:b.isNotServable((d=a.config.args)==null?void 0:d.video_id)))return}wz(a)}else a.rb=setTimeout(function(){rz(a)},50)}}
function wz(a){iz(a);a.Pa=!0;var b=pz(a);if(b){a.u=xz(a,b,"addEventListener");a.oa=xz(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=xz(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.u&&a.u(g,a.h[g]);lz(a);a.xa&&a.xa(a.api);a.U.qb("onReady",a.api)}
function xz(a,b,c){var d=b[c];return function(){var e=C.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if(c!=="sendAbandonmentPing")throw f.params=c,a.lastError=f,e=new U("PlayerProxy error in method call",{error:f,method:c,playerId:a.D}),e.level="WARNING",e;}}}
function iz(a){a.Pa=!1;if(a.oa)for(var b in a.h)a.h.hasOwnProperty(b)&&a.oa(b,a.h[b]);for(var c in a.P)a.P.hasOwnProperty(c)&&clearTimeout(Number(c));a.P={};a.u=null;a.oa=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Qa};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
r.isReady=function(){return this.Pa};
r.addEventListener=function(a,b){var c=this,d=nz(this,b);d&&(Mb(this.Fc,a)>=0||this.h[a]||(b=yz(this,a),this.u&&this.u(a,b)),this.U.subscribe(a,d),a==="onReady"&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
r.removeEventListener=function(a,b){this.ea||(b=nz(this,b))&&this.U.unsubscribe(a,b)};
function nz(a,b){var c=b;if(typeof b==="string"){if(a.Fa[b])return a.Fa[b];c=function(){var d=C.apply(0,arguments),e=F(b);if(e)try{e.apply(D,d)}catch(f){throw d=new U("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.Fa[b]=c}return c?c:null}
function yz(a,b){function c(d){function e(){if(!a.ea)try{a.U.qb(b,d!=null?d:void 0)}catch(h){var g=new U("PlayerProxy error when creating global callback",{error:h.message,event:b,playerId:a.D,data:d,originalStack:h.stack,componentStack:h.ge});g.level="WARNING";throw g;}}
if(tz(a,"web_player_publish_events_immediately"))e();else{var f=setTimeout(function(){e();var g=a.P,h=String(f);h in g&&delete g[h]},0);
og(a.P,String(f))}}
return a.h[b]=c}
r.getPlayerType=function(){return this.Z||(pz(this)?"html5":null)};
r.getLastError=function(){return this.lastError};
function sz(a){a.cancel();iz(a);a.Z=null;a.config&&(a.config.loaded=!1);var b=pz(a);b&&(oz(a)||!vz(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
r.cancel=function(){this.G&&pv(qz(this),this.G);clearTimeout(this.rb);this.Y=!1};
r.ba=function(){sz(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new U("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.Fa=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Qa=this.config=this.api=null;delete this.o;delete this.i;H.prototype.ba.call(this)};
function vz(a){var b,c;a=(b=a.config)==null?void 0:(c=b.args)==null?void 0:c.fflags;return!!a&&a.indexOf("player_destroy_old_version=true")!==-1}
function qz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function uz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function tz(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if((d=a.config)==null?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function mz(a){for(var b={},c=y(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]=typeof e==="object"?rg(e):e}return b}
;var zz={},Az="player_uid_"+(Math.random()*1E9>>>0);function Bz(a,b){var c="player",d=!1;d=d===void 0?!0:d;c=typeof c==="string"?xg(c):c;var e=Az+"_"+Sa(c),f=zz[e];if(f&&d)return Cz(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new hz(c,e,a,b,void 0);zz[e]=f;f.addOnDisposeCallback(function(){delete zz[f.getId()]});
return f.api}
function Cz(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Dz=null,Ez=null;
function Fz(){ix();var a=rn(),b=un(119),c=window.devicePixelRatio>1;if(document.body&&Sj(document.body,"exp-invert-logo"))if(c&&!Sj(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Sj(d,"inverted-hdpi")){var e=Qj(d);Rj(d,e+(e.length>0?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Sj(document.body,"inverted-hdpi")&&Tj();if(b!=c){b="f"+(Math.floor(119/31)+1);d=vn(b)||0;d=c?d|67108864:d&-67108865;d===0?delete on[b]:(c=d.toString(16),on[b]=c.toString());
c=!0;S("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in on)on.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(on[f])));var f=d.join("&");kn(b,f,63072E3,a.i,c)}}
function Gz(){Hz()}
function Iz(){dx("ep_init_pr");Hz()}
function Hz(){var a=Dz.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function Jz(){Dz&&Dz.sendAbandonmentPing&&Dz.sendAbandonmentPing();R("PL_ATT")&&ez.dispose();for(var a=Kj,b=0,c=Rx.length;b<c;b++)a.qa(Rx[b]);Rx.length=0;nv("//static.doubleclick.net/instream/ad_status.js");Sx=!1;am("DCLKSTAT",0);tc(Ez);Dz&&(Dz.removeEventListener("onVideoDataChange",Gz),Dz.destroy())}
;dx("ep_init_eps");E("yt.setConfig",am);E("yt.config.set",am);E("yt.setMsg",kv);E("yt.msgs.set",kv);E("yt.logging.errors.log",hu);
E("writeEmbed",function(){dx("ep_init_wes");var a=R("PLAYER_CONFIG");if(!a){var b=R("PLAYER_VARS");b&&(a={args:b})}Wv(!0);a.args.ps==="gvn"&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=R("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);S("embeds_enable_new_csi")||$w("embed",["ol"]);c=gy();if(!c.serializedForcedExperimentIds){var d=om(window.location.href);d.forced_experiments&&
(c.serializedForcedExperimentIds=d.forced_experiments)}var e;((e=a.args)==null?0:e.autoplay)?$w("watch",["pbs","pbu","pbp"]):S("embeds_enable_new_csi")&&(a.args&&Nu(a.args)?$w("video_preview",["ol"]):$w("embed_no_video",["ep_init_pr"]));Dz=Bz(a,c);Dz.addEventListener("onVideoDataChange",Gz);Dz.addEventListener("onReady",Iz);a=R("POST_MESSAGE_ID","player");R("ENABLE_JS_API")?Ez=new Ry(Dz):R("ENABLE_POST_API")&&typeof a==="string"&&typeof b==="string"&&(Ez=new Yy(Dz,a,b));Tx();S("ytidb_create_logger_embed_killswitch")||
qo();a={};Ey.h||(Ey.h=new Ey);Ey.h.install((a.flush_logs={callback:function(){Mt()}},a));
as();S("ytidb_clear_embedded_player")&&Kj.pa(function(){Mx();sy()});
S("enable_rta_manager")&&En(function(){var f=new ey;var g={preload:!S("enable_rta_npi")},h;typeof g==="boolean"?h={preload:g}:typeof g==="undefined"?h={preload:!0}:h=g;g=new Pr;Wx.instance=new Wx(f,h,g);f=Wx.instance;h=f.i.bind(f);E("yt.aba.att",h);f=f.j.bind(f);E("yt.aba.att2",f)});
dx("ep_init_wee")});
E("yt.abuse.player.botguardInitialized",F("yt.abuse.player.botguardInitialized")||fz);E("yt.abuse.player.invokeBotguard",F("yt.abuse.player.invokeBotguard")||gz);E("yt.abuse.dclkstatus.checkDclkStatus",F("yt.abuse.dclkstatus.checkDclkStatus")||Ux);E("yt.player.exports.navigate",F("yt.player.exports.navigate")||Vv);E("yt.util.activity.init",F("yt.util.activity.init")||us);E("yt.util.activity.getTimeSinceActive",F("yt.util.activity.getTimeSinceActive")||xs);
E("yt.util.activity.setTimestamp",F("yt.util.activity.setTimestamp")||vs);window.addEventListener("load",em(function(){Fz()}));
window.addEventListener("pageshow",em(function(a){a.persisted||Fz()}));
window.addEventListener("pagehide",em(function(a){S("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?Jz():a.persisted||Jz()}));
window.onerror=function(a,b,c,d,e){var f;b=b===void 0?"Unknown file":b;c=c===void 0?0:c;var g=!1,h=bm("log_window_onerror_fraction");if(h&&Math.random()<h)g=!0;else{h=document.getElementsByTagName("script");for(var k=0,l=h.length;k<l;k++)if(h[k].src.indexOf("/debug-")>0){g=!0;break}}if(g){g=!1;e?g=!0:(typeof a==="string"?h=a:ErrorEvent&&a instanceof ErrorEvent?(g=!0,h=a.message,b=a.filename,c=a.lineno,d=a.colno):(h="Unknown error",b="Unknown file",c=0),e=new U(h),e.name="UnhandledWindowError",e.message=
h,e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d);if(!S("wiz_enable_component_stack_propagation_killswitch")){a=e;var m;if((m=f)==null||!m.componentStack)if(m=a.ge)f||(f={}),f.componentStack=$t(m)}f&&ku(e,f);g?hu(e):W(e)}};
Ai=iu;window.addEventListener("unhandledrejection",function(a){iu(a.reason)});
Nb(R("ERRORS")||[],function(a){hu.apply(null,a)});
am("ERRORS",[]);dx("ep_init_epe");}).call(this);
