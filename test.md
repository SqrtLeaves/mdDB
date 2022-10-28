# p10

Let <img src="https://www.zhihu.com/equation?tex=p%2Cq" alt="p,q" class="ee_img tr_noresize" eeimg="1"> be positive real numbers such that

<img src="https://www.zhihu.com/equation?tex=%5Cfrac%7B1%7D%7Bp%7D%20%2B%20%5Cfrac%7B1%7D%7Bq%7D%20%3D1%5C%5C" alt="\frac{1}{p} + \frac{1}{q} =1\\" class="ee_img tr_noresize" eeimg="1">

Prove the following statements.

## (b.1)

If <img src="https://www.zhihu.com/equation?tex=f%20%5Cin%20%5Cmathscr%7BR%7D%28%5Calpha%29" alt="f \in \mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1"> , <img src="https://www.zhihu.com/equation?tex=g%20%5Cin%20%5Cmathscr%28%5Calpha%29" alt="g \in \mathscr(\alpha)" class="ee_img tr_noresize" eeimg="1"> , <img src="https://www.zhihu.com/equation?tex=f%20%5Cgeq%200%2C%20g%5Cgeq%200" alt="f \geq 0, g\geq 0" class="ee_img tr_noresize" eeimg="1"> , and

<img src="https://www.zhihu.com/equation?tex=%5Cint_a%5Eb%20f%5Ep%20d%5Calpha%20%3D%201%20%3D%20%5Cint_a%5Ebg%5Eq%20d%5Calpha" alt="\int_a^b f^p d\alpha = 1 = \int_a^bg^q d\alpha" class="ee_img tr_noresize" eeimg="1"> then <img src="https://www.zhihu.com/equation?tex=%20%5Cint_a%5Eb%20fg%20~d%5Calpha%20%5Cleq%201" alt=" \int_a^b fg ~d\alpha \leq 1" class="ee_img tr_noresize" eeimg="1">

### Answer:

<img src="https://www.zhihu.com/equation?tex=%5Cint_a%5Eb%20fg%20%5Cleq%20%5Cint_a%5Eb%20%5Cfrac%7Bf%5Ep%7D%7Bp%7D%20%2B%20%5Cfrac%7Bg%5Eq%7D%7Bq%7D%20%20%5C%5C" alt="\int_a^b fg \leq \int_a^b \frac{f^p}{p} + \frac{g^q}{q}  \\" class="ee_img tr_noresize" eeimg="1">

<img src="https://www.zhihu.com/equation?tex=%20%5Cint%20%5Cfrac%7Bf%5Ep%7D%7Bp%7D%20%2B%20%5Cfrac%7Bg%5Eq%7D%7Bq%7D%20%3D%20%5Cfrac%7B1%7D%7Bp%7D%20%5Cint%20f%5Ep%20%2B%20%5Cfrac%7Bp-1%7D%7Bp%7D%20%5Cint%20g%5Eq%20%20%3D%201" alt=" \int \frac{f^p}{p} + \frac{g^q}{q} = \frac{1}{p} \int f^p + \frac{p-1}{p} \int g^q  = 1" class="ee_img tr_noresize" eeimg="1"> <img src="https://www.zhihu.com/equation?tex=%20%5Cint_a%5Eb%20fg%20%5Cleq%201%20" alt=" \int_a^b fg \leq 1 " class="ee_img tr_noresize" eeimg="1">

## (b.2)

From (b.1), we know if 
<img src="https://www.zhihu.com/equation?tex=%5Cint_a%5Eb%20f%5Ep%20d%5Calpha%20%3D%20A%20%3D%20%5Cint_a%5Ebg%5Eq%20d%5Calpha" alt="\int_a^b f^p d\alpha = A = \int_a^bg^q d\alpha" class="ee_img tr_noresize" eeimg="1">

then <img src="https://www.zhihu.com/equation?tex=%20%5Cint_a%5Eb%20fg%20~d%5Calpha%20%5Cleq%20A" alt=" \int_a^b fg ~d\alpha \leq A" class="ee_img tr_noresize" eeimg="1">

## (c)

[[Spark#InequalityProve]]
[[TheoreM#Inequality]]
[[TheoreM#ComplexNumber]]
[[GoodProofs#Analysis]]
If <img src="https://www.zhihu.com/equation?tex=f%2Cg" alt="f,g" class="ee_img tr_noresize" eeimg="1"> are complex functions in <img src="https://www.zhihu.com/equation?tex=%5Cmathscr%7BR%7D%28%5Calpha%29" alt="\mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1"> ,

then

<img src="https://www.zhihu.com/equation?tex=%5CBig%20%7C%20%5Cint_a%5Eb%20fg%20~d%5Calpha%20%5CBig%20%7C%5Cleq%5CBig%20%5B%20%5Cint_a%5Eb%20%7Cf%7C%5Ep%20~d%5Calpha%20%5CBig%20%5D%5E%7B1/p%7D%20%5Ccdot%20%5CBig%20%5B%20%5Cint_a%5Eb%20%7Cg%7C%5Eq%20~d%5Calpha%20%5CBig%20%5D%5E%7B1/q%7D%5C%5C" alt="\Big | \int_a^b fg ~d\alpha \Big |\leq\Big [ \int_a^b |f|^p ~d\alpha \Big ]^{1/p} \cdot \Big [ \int_a^b |g|^q ~d\alpha \Big ]^{1/q}\\" class="ee_img tr_noresize" eeimg="1">

This is Holder's inequality.

When <img src="https://www.zhihu.com/equation?tex=p%20%3D%20q%20%3D%202" alt="p = q = 2" class="ee_img tr_noresize" eeimg="1"> it is usually called the Schwarz inequality.

### Answer:

Define 
<img src="https://www.zhihu.com/equation?tex=%5Ckappa%20%3D%20%5Cint_a%5Eb%7Cf%7C%5E%7Bp%7D~d%5Calpha%20%2C%20%5Clambda%20%3D%20%5Cint_a%5Eb%20%7Cg%7C%5Eq%20~d%5Calpha" alt="\kappa = \int_a^b|f|^{p}~d\alpha , \lambda = \int_a^b |g|^q ~d\alpha" class="ee_img tr_noresize" eeimg="1">

Define 
<img src="https://www.zhihu.com/equation?tex=%5Chat%20f%28x%29%20%3D%20%5Cfrac%7Bf%28x%29%7D%7B%5Ckappa%5E%7B1/p%7D%7D%2C%5Chat%20g%28x%29%20%3D%20%5Cfrac%7Bg%28x%29%7D%7B%5Clambda%5E%7B1/q%7D%7D" alt="\hat f(x) = \frac{f(x)}{\kappa^{1/p}},\hat g(x) = \frac{g(x)}{\lambda^{1/q}}" class="ee_img tr_noresize" eeimg="1">

Because <img src="https://www.zhihu.com/equation?tex=%5Ckappa%2C%20%5Clambda" alt="\kappa, \lambda" class="ee_img tr_noresize" eeimg="1"> are constant relative to <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">, and because <img src="https://www.zhihu.com/equation?tex=f%2Cg%20%5Cin%20%5Cmathscr%7BR%7D%28%5Calpha%29" alt="f,g \in \mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1">, so <img src="https://www.zhihu.com/equation?tex=%5Chat%20f%2C%20%5Chat%20g%20%5Cin%20%5Cmathscr%7BR%7D%28%5Calpha%29" alt="\hat f, \hat g \in \mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1">

By Theorem 6.13, we know <img src="https://www.zhihu.com/equation?tex=%7C%5Chat%20f%7C%2C%20%7C%5Chat%20g%7C%20%5Cin%20%5Cmathscr%7BR%7D%28%5Calpha%29" alt="|\hat f|, |\hat g| \in \mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1">

By Theorem 6.11, we know  <img src="https://www.zhihu.com/equation?tex=%7C%5Chat%20f%7C%5Ep%2C%20%7C%5Chat%20g%7C%5Eq%20%5Cin%20%5Cmathscr%7BR%7D%28%5Calpha%29" alt="|\hat f|^p, |\hat g|^q \in \mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1">

These two functions are "normalized" in the sense that

<img src="https://www.zhihu.com/equation?tex=%5Cint%20%7C%5Chat%20f%7C%5Ep%20%3D%20%5Cint%20%5Cfrac%7B%7Cf%7C%5Ep%7D%7B%5Ckappa%7D%20%3D%20%5Cfrac%7B1%7D%7B%5Ckappa%7D%5Cint%20%7Cf%7C%5Ep%20%3D%201%5C%5C" alt="\int |\hat f|^p = \int \frac{|f|^p}{\kappa} = \frac{1}{\kappa}\int |f|^p = 1\\" class="ee_img tr_noresize" eeimg="1">

<img src="https://www.zhihu.com/equation?tex=%5Cint%20%7C%5Chat%20g%7C%5Eq%20%3D%20%5Cint%20%5Cfrac%7B%7Cg%7C%5Eq%7D%7B%5Clambda%7D%20%3D%20%5Cfrac%7B1%7D%7B%5Clambda%7D%5Cint%20%7Cg%7C%5Eq%20%3D%201%5C%5C" alt="\int |\hat g|^q = \int \frac{|g|^q}{\lambda} = \frac{1}{\lambda}\int |g|^q = 1\\" class="ee_img tr_noresize" eeimg="1">

Thus, by part (b)
<img src="https://www.zhihu.com/equation?tex=%5CBigg%20%7C%20%5Cint%20%5Chat%20f%5Chat%20g%20%5CBigg%7C%20%5Cleq%20%5Cint%20%7C%5Chat%20f%7C%20%5Ccdot%20%7C%5Chat%20g%7C%20%5Cleq%201" alt="\Bigg | \int \hat f\hat g \Bigg| \leq \int |\hat f| \cdot |\hat g| \leq 1" class="ee_img tr_noresize" eeimg="1">

<img src="https://www.zhihu.com/equation?tex=%5CBigg%20%7C%20%5Cint%20%5Cfrac%7Bf%7D%7B%5Ckappa%5E%7B1/p%7D%7D%20%5Cfrac%7Bg%7D%7B%5Clambda%5E%7B1/q%7D%7D%20%5CBigg%7C%20%20%5Cleq%201%5C%5C" alt="\Bigg | \int \frac{f}{\kappa^{1/p}} \frac{g}{\lambda^{1/q}} \Bigg|  \leq 1\\" class="ee_img tr_noresize" eeimg="1">

<img src="https://www.zhihu.com/equation?tex=%5CBigg%20%7C%20%5Cint%20fg%20%5CBigg%7C%20%20%5Cleq%20%5Ckappa%5E%7B1/p%7D%5Clambda%5E%7B1/q%7D%20%3D%20%5CBig%20%5B%20%5Cint_a%5Eb%20%7Cf%7C%5Ep%20~d%5Calpha%20%5CBig%20%5D%5E%7B1/p%7D%20%5Ccdot%20%5CBig%20%5B%20%5Cint_a%5Eb%20%7Cg%7C%5Eq%20~d%5Calpha%20%5CBig%20%5D%5E%7B1/q%7D%20%5C%5C" alt="\Bigg | \int fg \Bigg|  \leq \kappa^{1/p}\lambda^{1/q} = \Big [ \int_a^b |f|^p ~d\alpha \Big ]^{1/p} \cdot \Big [ \int_a^b |g|^q ~d\alpha \Big ]^{1/q} \\" class="ee_img tr_noresize" eeimg="1">

Done

## (d)

Show that Holder inequality is also true for the "improper" integrals described in Ex 7 and 8.

### Answer:

Proof by contrapositive. 
Let
<img src="https://www.zhihu.com/equation?tex=A%28c%29%20%3D%20%5Clim_%7Bc%20%5Crightarrow%20%5Cinfty%7D%20%5CBigg%20%7C%20%5Cint_a%5Ec%20fg%20%5CBigg%20%7C" alt="A(c) = \lim_{c \rightarrow \infty} \Bigg | \int_a^c fg \Bigg |" class="ee_img tr_noresize" eeimg="1">
<img src="https://www.zhihu.com/equation?tex=B%28c%29%20%3D%20%5CBig%20%5B%20%5Cint_a%5Ec%20%7Cf%7C%5Ep%20~d%5Calpha%20%5CBig%20%5D%5E%7B1/p%7D%20%5Ccdot%20%5CBig%20%5B%20%5Cint_a%5Ec%20%7Cg%7C%5Eq%20~d%5Calpha%20%5CBig%20%5D%5E%7B1/q%7D%20" alt="B(c) = \Big [ \int_a^c |f|^p ~d\alpha \Big ]^{1/p} \cdot \Big [ \int_a^c |g|^q ~d\alpha \Big ]^{1/q} " class="ee_img tr_noresize" eeimg="1">

If <img src="https://www.zhihu.com/equation?tex=A%28c%29%20%3C%20B%28c%29" alt="A(c) < B(c)" class="ee_img tr_noresize" eeimg="1"> , then by the definition of limitation,  <img src="https://www.zhihu.com/equation?tex=%5Cexists%20%5Cbar%20c%20%5Cgt%200" alt="\exists \bar c \gt 0" class="ee_img tr_noresize" eeimg="1">, such that <img src="https://www.zhihu.com/equation?tex=%5Cforall%20c%20%5Cgt%20%5Cbar%20c%2C%20A%28c%29%20%3C%20B%28c%29" alt="\forall c \gt \bar c, A(c) < B(c)" class="ee_img tr_noresize" eeimg="1">.
This contradicts with Holder's inequality.

The proof for the case when the improper integral approaching an undefined point is similar.
Done.



Reference:

