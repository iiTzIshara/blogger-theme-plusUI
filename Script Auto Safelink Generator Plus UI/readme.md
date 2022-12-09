
Let's get straight to the point of this article, which is how to install the safelink script for the Plus UI theme. The first step is to copy and paste the two JavaScript codes below right above the code  ```  <!--[ </body> close ]-->  ```

```sh
<script>/*<![CDATA[*//* Safelink */ function _0x4001(){var r=["indexOf","fromCharCode","248082FnFLPu","2dyVCwX","851934NCaRZc","1464344UJimDR","255DsMQPg","13242QFkwLe","472829bEwnSk","24WKgyRt","3319965YzkqUw","10ZsypoO","875633sYiivu","MNBVCXZLKJHGFDSAPOIUYTREWQmnbvcxzlkjhgfdsapoiuytrewq0987654321+/=","_utf8_enc","charCodeAt","_keyStr","charAt","replace","length"];return(_0x4001=function(){return r})()}function _0x2f39a2(r,n){return _0x3fd0(r-544,n)}function _0x3fd0(r,n){var t=_0x4001();return(_0x3fd0=function(r,n){return t[r=+r]})(r,n)}!function(){function r(r,n){return _0x3fd0(n-107,r)}var n=_0x4001();function t(r,n){return _0x3fd0(n-241,r)}for(;;)try{if(213392==+parseInt(r(105,107))*(-parseInt(r(107,108))/2)+-parseInt(r(99,109))/3+parseInt(r(116,110))/4+parseInt(r(116,111))/5*(-parseInt(t(255,246))/6)+parseInt(t(249,247))/7*(parseInt(r(109,114))/8)+parseInt(t(258,249))/9+parseInt(t(245,250))/10*(-parseInt(r(113,117))/11))break;n.push(n.shift())}catch(r){n.push(n.shift())}}();var b64={_keyStr:_0x2f39a2(555,551),enc:function(r){function n(r,n){return _0x3fd0(r- -600,n)}var t,e,f,i,u,c,a="",o=0;function d(r,n){return _0x3fd0(r- -100,n)}for(r=b64[n(-588,-592)](r);o<r.length;)f=(c=r.charCodeAt(o++))>>2,i=(3&c)<<4|(t=r[d(-87,-84)](o++))>>4,u=(15&t)<<2|(e=r[d(-87,-97)](o++))>>6,c=63&e,isNaN(t)?u=c=64:isNaN(e)&&(c=64),a=a+this[d(-86,-93)][d(-85,-83)](f)+this[n(-586,-579)].charAt(i)+this[d(-86,-88)][n(-585,-583)](u)+this._keyStr[n(-585,-579)](c);return a},dec:function(r){function n(r,n){return _0x3fd0(r-70,n)}function t(r,n){return _0x3fd0(r-457,n)}var e,f,i,u,c,a="",o=0;for(r=r[t(473,474)](/[^A-Za-z0-9\+\/\=]/g,"");o<r[t(474,475)];)e=this._keyStr[n(88,89)](r[t(472,474)](o++))<<2|(i=this[n(84,91)].indexOf(r.charAt(o++)))>>4,f=(15&i)<<4|(u=this[n(84,91)].indexOf(r[n(85,83)](o++)))>>2,i=(3&u)<<6|(c=this[t(471,471)].indexOf(r[n(85,93)](o++))),a+=String[n(89,97)](e),64!=u&&(a+=String.fromCharCode(f)),64!=c&&(a+=String[n(89,95)](i));return b64._utf8_dec(a)},_utf8_enc:function(r){function n(r,n){return _0x3fd0(r-954,n)}r=r[n(970,962)](/\r\n/g,"\n");for(var t="",e=0;e<r[n(971,973)];e++){var f=r[n(967,972)](e);f<128?t+=String[n(973,983)](f):(127<f&&f<2048?t+=String[i(659,662)](f>>6|192):(t+=String.fromCharCode(f>>12|224),t+=String.fromCharCode(f>>6&63|128)),t+=String[i(671,662)](63&f|128))}function i(r,n){return _0x3fd0(n-643,r)}return t},_utf8_dec:function(r){function n(r,n){return _0x3fd0(r-515,n)}for(var t="",e=0,f=c1=c2=0;e<r[n(532,525)];)(f=r[i(391,387)](e))<128?(t+=String[n(534,526)](f),e++):191<f&&f<224?(c2=r.charCodeAt(e+1),t+=String[n(534,543)]((31&f)<<6|63&c2),e+=2):(c2=r.charCodeAt(e+1),c3=r[i(391,388)](e+2),t+=String.fromCharCode((15&f)<<12|(63&c2)<<6|63&c3),e+=3);function i(r,n){return _0x3fd0(r-378,n)}return t}}; /*]]>*/</script>

 ```

```sh
<script>/*<![CDATA[*/
/* Safelink Settings */ var aSl={par:"url",hcd:5000,gcd:15000,nwt:false,sby:"published",mxr:20,pwt:"Getting your link..."};
/* Safelink */ function _0x1541(t,n){var e=_0x4a4c();return(_0x1541=function(t,n){return e[t=+t]})(t,n)}function _0x4a4c(){var t=[".safeL","location","hash","includes","split","get","length","click","preventDefault","target","getAttribute","href","par","nwt","open","_blank","dec","replace","feeds/posts/summary?alt=json&orderby=","&max-results=","sSS","toString","indexOf","history","replaceState","title","feed","entry","floor","random","alternate","link","hmVrfy","hidden","#hmVrfy .pstL","alt","No post was found","SAFE_L","true","gSS","gcd",".safeGoL","setAttribute","vsbl","innerHTML","pwt","rSS"];return(_0x4a4c=function(){return t})()}!function(){var t=224,n=230,e=255,r=236,a=229,l=240,i=246,u=257,o=249,s=236,c=94,S=263,d=242,f=243,x=225,_=244,h=245,v=103,g=89,w=239,p=246,b=81,m=88,L=248,q=96,y=86,C=275,P=261,A=73,E=72,M=264,k=261,T=252,G=71,N=70,U=233,j=235,F=237,I=81,O=69,V=108,B=102,D=68,H=218,J=231,R=329,W=66,z=278,K=52,Q=440,X=462,Y=223,Z=439,$=462,tt=926,nt=916,et=416,rt=249,at=238,lt=418,it=724,ut=737,ot=35,st=53,ct=736,St=755,dt=735,ft=777,xt=757,_t=741,ht=757,vt=38,gt=45,wt=751,pt=732,bt=752,mt=731,Lt=739,qt=730,yt=729,Ct=22,Pt=8,At=763,Et=770,Mt=754,kt=747,Tt=112,Gt=116,Nt=758,Ut=753,jt=499,Ft=477,It=504,Ot=514,Vt=224,Bt=111;function Dt(t,n){return _0x1541(n- -Bt,t)}function Ht(t,n){return _0x1541(n-Vt,t)}var Jt,Rt,Wt,zt,Kt=qSell(Ht(208,t));function Qt(t){var e=498;const n=window[r(jt,Ft)][r(500,483)];function r(t,n){return _0x1541(t-e,n)}if(n&&n[r(501,It)]("=")&&n[r(502,518)](/=(.*)/s)[0]=="#?"+t&&""!=n.split(/=(.*)/s)[1])return window[r(499,Ot)].hash.split(/=(.*)/s)[1]}function Xt(t){var n=window[_0x1541(Gt-115,Tt)].search;const e=new URLSearchParams(n);return e.has(t)?e[_0x1541(Nt-753,Ut)](t):void 0}0<Kt[Ht(245,n)]&&Kt.forEach(t=>{var a=448,l=449,i=447,u=427,o=160,s=144,c=138,S=422,d=147,f=134,x=454,_=441,h=465,v=455,g=456;t.addEventListener(_0x1541(Mt-kt,Et),function(t){function n(t,n){return _0x1541(n- -147,t)}function e(t,n){return _0x1541(t- -g,n)}t[e(-a,-l)]();var r=t[e(-i,-u)][n(-158,-137)](n(-o,-136)),t=t[n(-s,-c)].getAttribute("data-href");null!=(t=null!=r&&"/"!=r&&"#"!=r&&""!=r?r:null!=t&&"#"!=t&&""!=t?t:void 0)&&(t=b64.enc(t),t=blogUrl+"#?"+aSl[e(-444,-S)]+"="+t,1==aSl[n(-d,-f)]?window[e(-442,-x)](t,e(-_,-h)):window.location[e(-445,-v)]=t)})}),null==Qt(aSl[Ht(e,r)])&&null==Xt(aSl.par)||(Kt=null!=Qt(aSl[Dt(-98,-99)])?b64[Ht(a,l)](Qt(aSl[Ht(i,r)])):b64[Ht(u,l)](Xt(aSl[Ht(o,s)])),Jt=blogUrl[Dt(-92,-c)](/.*?:\/\//g,"//")+Ht(S,d)+aSl.sby+Ht(S,f)+aSl.mxr,Pu[Ht(x,_)]("SAFE_L",Kt),0<(Kt=window[Dt(-129,-110)][Ht(t,h)]())[Dt(-v,-g)]("#")&&(Kt=Kt.substring(0,Kt[Ht(w,p)]("#")),window[Dt(-b,-m)][Ht(242,L)]({},document[Dt(-q,-y)],Kt)),Pu.gAj({url:Jt,async:!0,success:function(t){var n=956,e=713;function r(t,n){return _0x1541(n- -At,t)}function a(t,n){return _0x1541(t-Pt,n)}if((t=JSON.parse(t)[r(-it,-ut)]).entry&&0!==t[a(ot,st)].length){for(var l,i,u=(t=t[r(-725,-ct)])[Math[r(-St,-dt)](Math[a(37,49)]()*t[r(-ft,-xt)])],o=0,s=u.link[r(-_t,-ht)];o<s;o++)a(vt,gt)==(i=u[r(-wt,-pt)][o]).rel&&(l=i.href);remCt(getid(r(-bt,-mt)),r(-Lt,-qt)),qSel(r(-749,-yt)).href=l,setTimeout(function(){addCt(getid(_0x1541(-961- -993,-n)),_0x1541(-678- -e,-657))},aSl.hcd)}else toastNotif(a(44,Ct))}})),null!=Pu.gSS(Ht(C,P))&&Dt(-69,-A)==isPost&&(Jt=Pu[Dt(-60,-E)](Ht(M,k)),Rt=Math[Ht(239,T)](aSl[Dt(-E,-G)]/1e3),Wt=Rt,qSel(Dt(-74,-N))[Ht(U,j)]=Jt,1==aSl[Ht(243,F)]&&qSel(".safeGoL")[Dt(-I,-O)](Dt(-V,-B),Ht(t,239)),addCt(getid("aSlCnt"),Dt(-49,-D)),zt=setInterval(function(){var t=193,n=246,e=--Wt/Rt*100;function r(t,n){return _0x1541(n-lt,t)}qSel(".aSlW").style.width=100-e+"%",qSel(".aSlCd")[r(Q,X)]=Math[_0x1541(-218- -n,-Y)](Wt),Wt<=0&&(clearInterval(zt),qSel(".aSlCd")[r(Z,$)]="0",setTimeout(()=>{qSel(".aSlC")[_0x1541(et-372,396)]=aSl[_0x1541(at-t,rt)]},1e3),setTimeout(()=>{var t=959;addCt(qSel(".aSlB"),_0x1541(-nt- -t,-tt)),addCt(getid("aSlCnt"),"alt")},4e3))},1e3),qSel(".safeGoL").addEventListener(Ht(H,J),function(){Pu[_0x1541(324-z,R)](_0x1541(89-K,W))}))}(); if(qSel('.aScr')!==null){qSel('.aScr').addEventListener('click', () =>{setTimeout(() =>{qSel('.safeGoL').scrollIntoView({behaviour:'smooth', block:'center', inline:'center'})},200)})}
 /*]]>*/</script>

 ```

Also add the CSS code below just below the tag ```/* --- Your Custom CSS goes here --- */```
```sh
/* Human Verification */ .hmv{position:relative;font-family:var(--fontBa);border-radius:10px;padding:30px 20px;margin-bottom:40px;text-align:center;overflow:hidden} .hmv::before{content:'';position:absolute;z-index:0;top:0;right:0;bottom:0;left:0;background:var(--linkB);opacity:.06} .hmv::after{content:'';width:60px;height:60px;background:rgba(0,0,0,.15);display:block;border-radius:50%;position:absolute;top:-12px;left:-12px;opacity:.1} .hmv >*{position:relative;z-index:1} .hmv .hmvH{font-size:1.2rem;font-weight:700;margin-bottom:15px} .hmv .hmvD{font-family:var(--fontB);font-size:13px;opacity:.8;display:inline-flex;align-items:center} .hmv .hmvD svg{width:13px;height:13px;margin-right:5px} .hmv:not(.alt) .button, .hmv.alt .hmvH.bef, .hmv:not(.alt) .hmvH.aft, .hmv.alt .hmvD{display:none} .drK .hmv::before{background:var(--darkBs);opacity:1}
 
/* Scroll to Continue */ .aSlT, .aSlB{display:none;align-items:center;justify-content:center;text-align:center;padding:30px 0} .aSlP{display:block;position:relative;height:40px;width:100%;display:none;align-items:center;justify-content:center;z-index:0;border-radius:var(--buttonR);overflow:hidden} .aSlP::before{content:''; position: absolute;top:0;right:0;bottom:0;left:0; background:var(--linkC);opacity:.5} .aSlW{position: absolute;top:0;bottom:0;left:0;width:0;background:var(--linkC);opacity:.6;transition:width 1s ease} .aSlP > span{position:absolute;color:#fffdfc;font-size:15px;overflow:hidden;white-space:nowrap;text-overflow:ellipsis} .aScr{display:none;position:relative;width:100%;font-family:var(--fontBa);border-radius:10px;padding:30px 20px;text-align:center;overflow:hidden} .aScr::after{content:'';width:60px;height:60px;background:rgba(0,0,0,.15);display:block;border-radius:50%;position:absolute;top:-12px;left:-12px;opacity:.1} .aScr::before{content:'';position:absolute;z-index:0;top:0;right:0;bottom:0;left:0;background:var(--linkB);opacity:.06} .aScr .hglt{color:var(--linkC)} .aScr .aScrH{position:relative;z-index:1;font-size:1.2rem;font-weight:700;margin-bottom:15px} .aScr .aScrD{position:relative;z-index:1;font-family:var(--fontB);font-size:13px;opacity:.8;display:inline-flex;align-items:center} .aScr .aScrD svg{width:13px;height:13px;margin-right:5px;stroke-width:1.5} .aSlT.vsbl, .aSlB.vsbl, .aSlT:not(.alt) .aSlP{display:flex} .aSlT.alt .aScr{display:block} .aSlT.nInt .aSlP > span{font-size:13px} .Rtl .aSlW{left:unset;right:0} .Rtl .aScr .aScrD svg{margin-right:0;margin-left:5px} .drK .aSlP::before{background:var(--darkBs);opacity:1} .drK .aSlW{background:var(--darkBa);opacity:1} .drK .aScr{background:var(--darkBs)} .drK .aScr::before{background:var(--darkBa);opacity:1} .drK .aScr .hglt{color:var(--darkU)}

 ```

Then copy and paste the following HTML code at the bottom of the code ```<main class='blogItm mainbar'>```
```sh
 <b:if cond='data:view.isHomepage'>
  <!--[ Human verification ]-->
  <div class='hmv hidden' id='hmVrfy'>
    <div class='hmvH bef'>Verify that You are not a Robot</div>
    <div class='hmvH aft'>Are you a Robot?</div>
    <div class='hmvD'><svg viewBox='0 0 50 50' x='0px' y='0px'><path d='M25.251,6.461c-10.318,0-18.683,8.365-18.683,18.683h4.068c0-8.071,6.543-14.615,14.615-14.615V6.461z'><animateTransform attributeName='transform' attributeType='xml' dur='0.6s' from='0 25 25' repeatCount='indefinite' to='360 25 25' type='rotate'/></path></svg>Generating Link... Please Wait</div>
    <a class='button pstL' href='/'>I am not a Robot</a>
  </div>
</b:if>
 ```
 
 Also add the code below just below the tag ```<b:tag class='pInr' cond='data:view.isSingleItem' name='div'>```
 ```sh
 <b:if cond='data:view.isPost'>
  <!--[ Safelink Countdown Timer ]-->
  <div class='aSlT' id='aSlCnt'>
    <div class='aSlP'>
      <div class='aSlW'/>
      <span class='aSlC'>Please wait <span class='aSlCd'>0</span> seconds...</span>
    </div>
    <div class='aScr'>
      <div class='aScrH'>Scroll Down and click on <span class='hglt'>Go to Link</span> for destination</div>
      <div class='aScrD'><svg class='line' viewbox='0 0 24 24'><path d='M22 11.07V12a10 10 0 1 1-5.93-9.14'/><polyline points='23 3 12 14 9 11'/></svg>Congrats! Link is Generated</div>
    </div>
  </div>
</b:if>
  ```

Also put the following html code just below the tag ```<data:post.body/>```
 ```sh
<b:if cond='data:view.isPost'>
  <!--[ Safelink Destination Button ]-->
  <div class='aSlB'>
    <a class='button safeGoL' href='/' title='Go to Link'><i class='icon demo'/>Go to Link</a>
  </div>
</b:if>
   ```
   
   
   
Then the final step, create a static page on the blog and paste the following code in HTML writing mode.   
 ```sh
   <style>
  /*! SafeLink Generator CSS */
  .hidden{display:none !important}
  button{cursor:pointer}
  button:hover{opacity:.9}
</style>

<h2>Safelink</h2>
<!--[ SafeLink ]-->
<div class='cArea'>
  <label>
    <input class='cInpt' id='safeIn' name='' type='text' />
    <span class='n req'>Enter Link here</span>
  </label>
</div>
<div class='cArea'>
  <label>
    <input class='cInpt' id='safeOut' name='' type='text' readonly />
    <span class='n'>Protected Link</span>
  </label>
</div>
<div class='cArea'>
  <button class='button' id='safeGen'>Protect Link</button>
  <button class='button hidden' id='safeCpy'>Copy</button>
  <button class='button hidden' id='safeViw'>View</button>
</div>

<!--[ Safelink ]-->
<script>
  /*<![CDATA[*/
  /* SafeLink settings */
  var safeSet = {
    safePar: "#?url",
    succNtf: "<i class='check'></i>Link Protected, Click on Copy",
    entrNtf: "<i class='warn'></i>Enter link to protect!",
    cpydNtf: "<i class='clipboard'></i>Copied to clipboard!",
  };
  /* SafeLink scripts */
  function _0x4b5f(){var t=["nJi2mJq1mLfgEhzRvW","C2fMzuLU","ywrKrxzLBNrmAxn0zw5LCG","C2v0qxr0CMLIDxrL","mJqZmtq3nNfhvxHuBa","C2fMzunWEq","Ahr0Chm6lY8","mtaXody0u0DArgD0","x2jSyw5R","mtbnzfrwzve","C2fMzvzPDW","zw5J","y29WEq","y3b5ze50zG","ngT4zfHNvW","Ahr0CdOVlW","zxHLy0nVBw1HBMq","CMvTB3zLqwXSuMfUz2vZ","BgvUz3rO","C2fMzvbHCG","lNDPzgDLDcbPBNb1DfT0ExbLpxrLEhrDlcaUD2LKz2v0igLUChv0w3r5Cgu9zw1HAwXDlcaUD2LKz2v0ihrLEhrHCMvH","AgLKzgvU","mJKXmZCXnZzTB3bishO","otG2otrkEMTeuwK","DMfSDwu","C2fMzu91Da","mtCZotq1mu13whzbtG","Aw5WDxq","mZqYnZK1mfHIsMPbwa","y2XPy2S","Aw5KzxHpzG","zgf0ys10zxH0","B3bLBG","C2fMzuDLBG","B25JBgLJAW"];return(_0x4b5f=function(){return t})()}function _0x227a(a,t){var u=_0x4b5f();return(_0x227a=function(t,n){var r=u[t=+t];void 0===_0x227a.AFejpy&&(_0x227a.UIWYON=function(t){for(var n,r,e="",f="",a=0,u=0;r=t.charAt(u++);~r&&(n=a%4?64*n+r:r,a++%4)&&(e+=String.fromCharCode(255&n>>(-2*a&6))))r="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=".indexOf(r);for(var i=0,o=e.length;i<o;i++)f+="%"+("00"+e.charCodeAt(i).toString(16)).slice(-2);return decodeURIComponent(f)},a=arguments,_0x227a.AFejpy=!0);var e=u[0],f=t+e,e=a[f];return e?r=e:(r=_0x227a.UIWYON(r),a[f]=r),r})(a,t)}(function(){function t(t,n){return _0x227a(t-811,n)}var n=_0x4b5f();function r(t,n){return _0x227a(t- -794,n)}for(;;)try{if(681338==+parseInt(r(-783,-783))+parseInt(t(838,831))/2+-parseInt(t(825,821))/3*(-parseInt(r(-792,-805))/4)+parseInt(r(-762,-759))/5*(parseInt(t(827,834))/6)+parseInt(r(-771,-775))/7+-parseInt(r(-764,-781))/8+-parseInt(r(-784,-787))/9)break;n.push(n.shift())}catch(t){n.push(n.shift())}})(),function(){for(var t=qSell(o(70,75)),n=0;n<t[r(-595,-587)];n++)t[n][o(87,89)](r(-566,-578),function(){var t=this[n(-683,-678)]?"fl":"nfl";function n(t,n){return _0x227a(n- -690,t)}this[n(-647,-664)]("data-text",t)});function r(t,n){return _0x227a(n- -593,t)}var f=getid(r(-581,-569)),a=getid(r(-592,-580)),e=getid(o(83,73)),u=getid(o(90,106)),i=getid(r(-565,-560));function o(t,n){return _0x227a(t-62,n)}f.addEventListener("blur",function(){var t=f[r(-575,-561)];function n(t,n){return _0x227a(n- -586,t)}function r(t,n){return _0x227a(n- -573,t)}return~t.indexOf(n(-568,-557))||~t[n(-578,-568)](r(-556,-570))||""==t||(t="https://"+t),f[r(-548,-561)]=t,f}),e.addEventListener("click",function(){function t(t,n){return _0x227a(t- -369,n)}var n,r;function e(t,n){return _0x227a(t- -344,n)}""!=f[e(-332,-342)]?(n=b64[t(-335,-346)](f[t(-357,-368)]),r=blogUrl+safeSet[t(-362,-376)]+"="+n,a[t(-357,-350)]=r,a[e(-318,-305)](e(-325,-340),"fl"),i[t(-347,-364)]=function(){window[_0x227a(20,610)](r,_0x227a(31,1029))},remCt(u,"hidden"),remCt(i,e(-335,-330)),toastNotif(safeSet.succNtf)):toastNotif(safeSet.entrNtf)}),u[o(87,100)](r(-590,-576),function(){function t(t,n){return _0x227a(t-791,n)}function n(t,n){return _0x227a(t- -873,n)}a[t(803,819)];var r=getSelection();r[n(-868,-857)](),a.select(),document[n(-869,-885)](t(791,804)),r[t(796,788)](),toastNotif(safeSet[t(792,783)])})}();
  /*]]>*/
</script>
   
    ```
    
    
The code above is a page from the manual safelink URL generator tool, if you want to generate a safelink URL automatically use the code below for each post with a download button and the like.   

```sh
 <div style="text-align:center"><a class="button safeL" href="#" data-href="Your Url here"><i class="icon demo"></i>View Demo</a></div> 
  ```
  
  
It is recommended to continue using the safelink generator tool on the page, because there is a bug caused by cookies on automatic safelink, which makes safelink remain active even though you have clicked the URL several times. And every time you enter the safelink URL, it is recommended to use tags ```target='_blank'```in each URL button.

Example:```<a href='url_safe_link' terget='_blank'></a>  ```
