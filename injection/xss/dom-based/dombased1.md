<h1> xss dom based 1 </h1>
dom based xss is when the input form a request is shown into the dom which is practicaly reflected
<img src='https://i.postimg.cc/BvSnZjYX/Screenshot-2026-08-05-144233.png'>
here we are missioned to find the lost code in the routehandler to find a exploit<br>https://i.postimg.cc/bwH5PTF4/Screenshot-2026-08-05-150604.png'> <br> here is the route script <code>js/goatApp/view/GoatRouter.js</code><br> now lets open it<br><img src='https://i.postimg.cc/tgq4RsS1/Screenshot-2026-08-05-144354.png'> it shows this code which is the one we want <code>'test/:param': 'testRoute'</code><br> now lets test it with the base route <code>start.mvc#test</code><br><img src='https://i.postimg.cc/rpVwyDnR/Screenshot-2026-08-05-144437.png'> and it is the right route
