![](RotatingCube.gif)   
3D Animation
============
In addition to the 2 dimensional graphics functions you've used, P5 also has a set of 3 dimensional graphics functions. In this assignment you will create an animation using
one or more of these functions. The people who wrote P5 have put together a great [3D tutorial](https://github.com/processing/p5.js/wiki/Getting-started-with-WebGL-in-p5#introducing-webgl-in-p5js). You may also find slides 318 - 365 in the [slide presentation](https://docs.google.com/presentation/d/1fm_Di0qR4HpRWTf8tJtcW3u5by3OrilfXIPZ517K1js/edit?usp=sharing) helpful.

Suggested steps for starting this assignment:
-----------------------------------------------
1. Start a new [P5 program](https://editor.p5js.org/)
2. In `function setup()` you will need to call the 3 argument version of `createCanvas()`, e.g.`createCanvas(400, 400, WEBGL);` since we will be using the 3d functions.
3. In `function draw()` you could use the following functions in this order:
   * `background()`
   * `translate()` moves the coordinates where the box will be drawn
   * `rotateX()` rotates the box around the X axis
   * `rotateY()` rotates the box around the Y axis
   * `box()` draws the rotated and translated box
4. Experiment with different arguments to get a feel for how they effect the box.
5. You'll need someway to animate the box. It could rotate on its own, or you could add something like `mouseDragged()` or `keyPressed()` with `mouseX` and `mouseY` used to change the amount of rotation. Whatever method you choose, since the amount of rotation will be changing, you'll will probably need a variable or two to store the amount of rotation in the x, y and/or z directions.

Optional Extensions
---------------------
* You may want to use `pointLight()` to make a 3 dimensional lighting effect. Moving the position of the `pointlight()` can create interesting effects.
* You can change the perspective with `camera()`
* Bind rotation to mouse or keys.
* Create a 3D shape that is not built in (not a torus, cube, sphere/ellipsoid, cone, plane, cylinder.) For example, you could create a composite 3D shape like a house (pyramid on a cube) or an ice cream cone (sphere on a cone)
* For the really adventurous, you could design an object in CAD software (e.g. [Tinkercad](https://www.tinkercad.com/dashboard)) export it as an `obj` file and upload it to your P5 program.      

These are only suggestions, your 3d animation doesn't have to look like any other. Have fun and be creative!

Samples of Student Work
-----------------------
[Yeshi](https://preview.p5js.org/yesherpa/present/Erbhpt1rO)   
[Ally](https://preview.p5js.org/alzhao/present/o-KMzPvdQ)   
[John](https://preview.p5js.org/joieng/present/r5xCkdnzX)   
[Cali](https://preview.p5js.org/cacasanas/present/a4-ri1e8N)   
[Tiffany](https://preview.p5js.org/ticaballero/present/VruDjrWAn)   
[Tania](https://preview.p5js.org/tacastanonperez/present/lVecPI9TD)   
[Oliver](https://preview.p5js.org/Oliver312/present/xGh1_7vgU)   
[Amy](https://preview.p5js.org/amhuang4/present/l7a43p7mo)   
[Jasmine](https://preview.p5js.org/jaguan4/present/gK63QI596)   
[Bella](https://preview.p5js.org/bejayanti/present/WoZpVbNtn)   
[Pansy](https://preview.p5js.org/pakuang/present/cq-IaLsbq)   
[Andrei](https://preview.p5js.org/anliterato/present/rOqwpm93w)   
[Patrick](https://preview.p5js.org/payao/present/06SZj3aTc)   
[Alyssa](https://preview.p5js.org/almagtoto-diaz/present/EOSsyax7Ts)   
[Margaux](https://preview.p5js.org/Mabarahonaventura/present/VWdkZHmrA)   
[Emerson](https://preview.p5js.org/Hello_its_Emerz/present/qY6vvSQt7)   
[Owen](https://preview.p5js.org/owsheetz/present/JGL2yjWx3)   
[Noah](https://preview.p5js.org/BiZaark/present/mZftlFElQ)   
[Aaron](https://preview.p5js.org/aahill1/present/aONXcRj2x)   
[Evie](https://preview.p5js.org/evchien/present/RUITOC4as)   
[Isaac](https://preview.p5js.org/ischu/present/jUmFoh1lP)   
[Grace](https://preview.p5js.org/grhuang/present/42Q6rN3Ry)   
[Breana](https://preview.p5js.org/brlew1/present/OWJvsGmPC)   
[Alvaro](https://preview.p5js.org/algarduno1/present/EkUCn013t)   
[Peter](https://preview.p5js.org/n_ll/present/hJlkWbU8ro)   
[Tennyson](https://preview.p5js.org/Tennyson/present/TUi2RsnIv)   
[Kaitlyn](https://preview.p5js.org/kaluu/present/r1Ck7dcZB)   
[Rio](https://preview.p5js.org/rihaile/present/hscI5mWUF)   
[Hao](https://preview.p5js.org/hatang/present/dT6nSRsTb)    
[Linen](https://preview.p5js.org/lifeng/present/gm06bp0fO)   
[Joanne](https://editor.p5js.org/joguan59/present/JYn05XRko)   
[Adam](https://editor.p5js.org/adamgooch/present/zf4zHWTWn)   
[Michelle](https://editor.p5js.org/michelle0/present/T08hkL7dX)   
[Kenneth](https://editor.p5js.org/kelee20/present/wEvG9kQUv)   
[Tiffany](https://editor.p5js.org/titse/present/YrvDU8XcL)   
[Justin](https://editor.p5js.org/jushiu/present/x_ORpprxe)   
[Azalea](https://editor.p5js.org/Azalea/present/N5AVGosgy)   
[Lillian](https://editor.p5js.org/litang/present/nhzKAz7jO)   
[Sean](https://editor.p5js.org/sewong3/present/gYxXFl-dS)   
[Michelle](https://editor.p5js.org/mitan4/present/KNaTTs8uj)   
[Jason](https://editor.p5js.org/jawong32/present/ol7COabbO)   
[Alisa](https://editor.p5js.org/aiyale/present/7WCOTf0Jw)   
[Elvin](https://editor.p5js.org/elli1/present/PXPQZ5stl)   
[Naomi](https://editor.p5js.org/nakung/present/C1FnJFibk)   
[Joanna](https://editor.p5js.org/jogaray-velazquez/present/OFTRyb2wu)   
[Tommy](https://editor.p5js.org/Touyen/present/yc6W67tVS)   
[Juan](https://editor.p5js.org/jucalvohuerta/present/2dSxIaahd)   
[Christina](https://editor.p5js.org/chchan10/present/13Dq_JlIs)   
[Henry](https://editor.p5js.org/hejuarez1/present/dJEuuoDtN)   
[Emely](https://editor.p5js.org/emsarcenobravo/present/A7xSIt1qe)   
[Micheal](https://editor.p5js.org/mibennett1/present/p1dUo7h0m)   
[Victor](https://editor.p5js.org/visibrian/present/WXoVP6FaD)   
[Sally](https://editor.p5js.org/sahong3/present/1xJ1EyfXJ)   
[Jennie](https://editor.p5js.org/jilin20/present/n7Ub6DVhN)   
[Benjamin](https://editor.p5js.org/benhan/present/V5thSi3Jr)   
[Paolo](https://editor.p5js.org/paolo415/present/p6jSK39vd)   
[John](https://editor.p5js.org/jocarlin/present/XHrIoGBuN)   
[Cameron](https://editor.p5js.org/canguyen1/present/G-c7lcfmo)   
[Ashton](https://editor.p5js.org/ashan-voltaic/present/Ec_xAz18n)   
[Ken](https://editor.p5js.org/Keshfer/present/cDVpNNh8N)   
[Kami](https://editor.p5js.org/kawang7/present/f5CRO1ztD)   
[Audrey](https://editor.p5js.org/AudreyLau8/present/1taN_fApD)    
[Dat](https://editor.p5js.org/tuduong1/present/Kjxo3fdzs)   
[Tobias](https://editor.p5js.org/tozuercher/present/YE4JxYP2Z)   
[Tushig](https://editor.p5js.org/Tushig.itgel/present/_jlky215Y)   
[Cyrus](https://editor.p5js.org/cygriffin/present/Ov5l_bhvT)   
[Tommy](https://editor.p5js.org/toyu3/present/rRtYJ4wzk)   
[Irisa](https://editor.p5js.org/irchu1/present/KvhcGJa5F)   
[Niko](https://editor.p5js.org/NikoTsu/present/pM-WkaXBs)   
[Juan](https://editor.p5js.org/jucalvohuerta/present/2dSxIaahd)   
[Damian](https://editor.p5js.org/dabogdon/present/PeoaM4z_l)   
[Marissa](https://editor.p5js.org/maholmes/present/OYBUOMrK_)   
[Daniil](https://editor.p5js.org/dakardava/present/nsAdyCn2L)   
[Tyler](https://editor.p5js.org/tylee2/present/_DOUaOBSf)   
[Rachel](https://editor.p5js.org/raroyer/present/yNRUchcJ9)   
[Cameron](https://editor.p5js.org/canguyen1/present/G-c7lcfmo)   
[Benjamin](https://editor.p5js.org/bewong4/present/laLmDsssq)   
[Melissa](https://editor.p5js.org/metam3/present/82NU3jYvl)   
[Michael](https://editor.p5js.org/mimui/present/CpWHk6_AR)   
[Gloria](https://editor.p5js.org/glchun/present/pVLbi5xrC)   
[Marco](https://editor.p5js.org/malee21/present/kL0hTR9Mh)   

