Using Frish-Waugh-Lovel theorem we can see that if $X$ and $W$ are independente, then asymptotically the coefficient $\beta_x^{short}$ estimated by regressing 

$$
Y \sim X
$$

is equal to $\beta_x^{long}$, the one we would obtain by estimating

$$
Y \sim X + W .
$$

In fact, the coefficient $\beta_x^{long}$ that we get with $Y \sim X + W$ Is equal to the one we would get regressing

$$
M_W Y \sim M_W X
$$

(by FWL). Se $X$ e $W$ are independent, then:

$$
\mathbb{E}[X W] = 0
$$

and asymptotically $\beta_x^{long}$ obtained by

$$
M_W Y \sim M_W X
$$

is equal to

$$
Y \sim X.
$$

---

Similar reasoning applies to independence conditional to $Z$, but **only if** $\mathbb{E}[Y \mid Z]$ and $\mathbb{E}[X \mid Z]$ are linear. Otherwise, the correct regression will be

$$
Y \sim X + Z + W
$$

equivalent to

$$
M_{WZ} Y \sim M_{WZ} X
$$

(by FWL) and it would **not be equal** to

$$
M_Z Y \sim M_Z X = Y \sim X + Z
$$

This is due to the fact that

$$
M_{WZ} Y \sim M_{WZ} X = M_Z Y \sim M_Z X
$$

only in the conditional means are linear.

---

When conditional expectations given $Z$ are not linear, we can still apply a similar reasoning, but we must estimate 

$$
\mathbb{E}[Y \mid Z] \quad \text{e} \quad \mathbb{E}[X \mid Z]
$$

 **non linearly** and compute the residuals with respect to those estimates.
