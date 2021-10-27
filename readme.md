
# 积分

<img src = "./img1.png">

$(g_{ii})_{kl}=\frac{1}{16\pi(1-\nu)G}\int_{\Gamma_{i}} (\frac{(3-4\nu)\delta_{kl}}{r}+\frac{r_k r_l}{r^3})d\Gamma(\mathbf{y})$

其中积分中第一项额外系数为$(3-4\nu)\delta_{kl}$。
只对$\int_{\Gamma_{i}} \frac{1}{r} d\Gamma(\mathbf{y})$使用极坐标进行积分计算，因为在$\Delta q_2q_3q_c$中，与$q_2q_c$夹角为特定某个$\theta$，从质心到达边$q_2q_3$距离为$\frac{2A}{3r_{23}sin(\theta+\alpha_2)}$,所以在极坐标替换下积分变为
<!-- $$aa$$
$$
\begin{align}
aaa &= aaaa \\
& = bb \\
\end{align}
$$ -->

$$\int^{\theta_1}_{0}\int^{\frac{2A}{3r_{23}sin(\theta+\alpha_2)}}_{0} drd\theta = \frac{2A}{3r_{23}}\int^{\theta_1}_{0}\frac{1}{sin(\theta+\alpha_2)}d\theta = ln[\frac{tan(\frac{\theta_1+\alpha_2}{2})}{tan(\frac{\alpha_2}{2})}]$$

对另外两个三角形也是同样的形式，最终第一个积分项
$$J_1^{\Delta}=\frac{2A}{3}[\frac{J(\theta_1,\alpha_2)}{r_{23}}+\frac{J(\theta_2,\alpha_3)}{r_{31}}+\frac{J(\theta_3,\alpha_1)}{r_{12}}]$$
其中$J(\theta,\alpha)=ln[\frac{tan(\frac{\theta+\alpha}{2})}{tan(\frac{\alpha}{2})}]$