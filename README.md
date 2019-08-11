# Stein Density Ratio Estimation (SDRE) and Its Applications

### Reference: 
[*Song Liu, Takafumi Kanamori, Wittawat Jitkrittum, Yu Chen, Fisher Efficient Inference of Intractable Models, E-print: arXiv:1805.07454, 2019*](https://arxiv.org/abs/1805.07454)

### Folder Structure: 
- **DRE**: Stein Density Ratio Estimation
- **Inference**: Model Inference using SDRE
- **util**: Helper Functions

- README: this file

```bash
cd DRE
python demoPrimal.py
```

```
0
1
2
3
4
delta: [-0.01534369 -0.01241881 -0.01777918 -0.00768591 -0.0086371 ]
delta: [-0.02901659 -0.02353518 -0.03350215 -0.01435563 -0.01642222]
delta: [-0.04125819 -0.03353829 -0.04745818 -0.02016631 -0.02346772]
delta: [-0.05225114 -0.04256851 -0.05986838 -0.02523761 -0.0298599 ]
delta: [-0.06214061 -0.05073489 -0.07090946 -0.02966475 -0.03566779]
delta: [-0.07104592 -0.05812541 -0.08072779 -0.03352609 -0.04094841]
delta: [-0.07906781 -0.0648134  -0.08944823 -0.03688792 -0.04575019]
delta: [-0.08629326 -0.07086168 -0.09717992 -0.03980748 -0.0501152 ]
delta: [-0.09279865 -0.07632543 -0.10401999 -0.04233505 -0.05408063]
delta: [-0.09865206 -0.08125403 -0.11005621 -0.04451533 -0.05767994]
delta: [-0.10391471 -0.08569239 -0.11536862 -0.04638834 -0.06094354]
delta: [-0.10864213 -0.08968188 -0.12003071 -0.04799016 -0.06389932]
delta: [-0.11288492 -0.09326087 -0.12411014 -0.04935334 -0.06657308]
delta: [-0.1166893  -0.09646518 -0.12766925 -0.05050729 -0.06898871]
delta: [-0.12009755 -0.09932829 -0.13076539 -0.05147855 -0.07116846]
delta: [-0.12314838 -0.10188149 -0.13345114 -0.05229096 -0.07313299]
delta: [-0.12587713 -0.10415401 -0.13577452 -0.05296591 -0.07490154]
delta: [-0.1283161  -0.10617305 -0.13777916 -0.05352246 -0.07649194]
delta: [-0.13049467 -0.10796384 -0.13950448 -0.05397755 -0.07792073]
delta: [-0.13243956 -0.10954965 -0.14098593 -0.05434614 -0.07920317]
delta: [-0.13417501 -0.11095191 -0.14225518 -0.05464135 -0.08035331]
delta: [-0.13572295 -0.1121902  -0.1433404  -0.05487468 -0.08138406]
delta: [-0.13710316 -0.11328237 -0.14426647 -0.0550561  -0.08230723]
delta: [-0.13833349 -0.11424461 -0.14505533 -0.05519425 -0.08313359]
delta: [-0.13942997 -0.11509155 -0.14572618 -0.05529655 -0.08387295]
delta: [-0.14040703 -0.11583635 -0.14629578 -0.05536937 -0.0845342 ]
delta: [-0.14127755 -0.11649082 -0.14677869 -0.05541812 -0.08512541]
delta: [-0.14205311 -0.11706552 -0.14718755 -0.0554474  -0.08565384]
delta: [-0.14274405 -0.11756987 -0.14753323 -0.05546108 -0.08612607]
delta: [-0.1433596  -0.11801224 -0.14782514 -0.05546241 -0.086548  ]
delta: [-0.143908   -0.11840008 -0.14807134 -0.05545411 -0.08692495]
delta: [-0.14439661 -0.11873996 -0.14827873 -0.05543844 -0.08726167]
delta: [-0.14483198 -0.11903772 -0.14845322 -0.05541725 -0.08756245]
delta: [-0.14521994 -0.11929848 -0.14859986 -0.05539208 -0.08783111]
delta: [-0.1455657  -0.11952679 -0.14872296 -0.05536417 -0.08807109]
delta: [-0.14587388 -0.11972664 -0.14882616 -0.05533453 -0.08828545]
delta: [-0.14614861 -0.11990154 -0.14891259 -0.05530396 -0.08847693]
delta: [-0.14639355 -0.12005458 -0.14898486 -0.05527311 -0.08864797]
delta: [-0.14661197 -0.12018847 -0.14904524 -0.05524247 -0.08880078]
delta: [-0.14680676 -0.12030558 -0.1490956  -0.05521244 -0.0889373 ]
delta: [-0.1469805  -0.12040802 -0.14913754 -0.05518329 -0.08905928]
delta: [-0.14713551 -0.1204976  -0.14917243 -0.05515524 -0.08916828]
delta: [-0.14727381 -0.12057594 -0.1492014  -0.05512844 -0.08926569]
delta: [-0.14739723 -0.12064444 -0.14922542 -0.05510299 -0.08935274]
delta: [-0.14750739 -0.12070433 -0.14924529 -0.05507894 -0.08943054]
delta: [-0.14760573 -0.12075669 -0.1492617  -0.05505631 -0.08950009]
delta: [-0.14769352 -0.12080246 -0.14927522 -0.05503511 -0.08956227]
delta: [-0.14777192 -0.12084247 -0.14928633 -0.05501531 -0.08961786]
delta: [-0.14784194 -0.12087744 -0.14929545 -0.05499687 -0.08966756]
delta: [-0.14790449 -0.120908   -0.1493029  -0.05497975 -0.08971201]
delta: [-0.14796036 -0.12093472 -0.14930897 -0.05496389 -0.08975176]
delta: [-0.14801029 -0.12095806 -0.1493139  -0.05494923 -0.08978731]
delta: [-0.1480549  -0.12097846 -0.14931789 -0.05493571 -0.08981911]
delta: [-0.14809477 -0.12099628 -0.1493211  -0.05492325 -0.08984755]
delta: [-0.14813041 -0.12101185 -0.14932367 -0.0549118  -0.089873  ]
delta: [-0.14816228 -0.12102546 -0.14932572 -0.05490129 -0.08989577]
delta: [-0.14819076 -0.12103734 -0.14932734 -0.05489165 -0.08991614]
delta: [-0.14821624 -0.12104772 -0.1493286  -0.05488282 -0.08993437]
delta: [-0.14823902 -0.12105679 -0.14932959 -0.05487475 -0.08995069]
delta: [-0.1482594  -0.12106471 -0.14933034 -0.05486737 -0.08996529]
delta: [-0.14827763 -0.12107162 -0.1493309  -0.05486063 -0.08997836]
delta: [-0.14829393 -0.12107766 -0.14933132 -0.05485449 -0.08999005]
delta: [-0.14830852 -0.12108293 -0.14933162 -0.0548489  -0.09000053]
delta: [-0.14832158 -0.12108753 -0.14933182 -0.0548438  -0.0900099 ]
delta: [-0.14833326 -0.12109154 -0.14933195 -0.05483916 -0.0900183 ]
delta: [-0.14834372 -0.12109505 -0.14933202 -0.05483495 -0.09002581]
delta: [-0.14835308 -0.1210981  -0.14933205 -0.05483112 -0.09003254]
delta: [-0.14836146 -0.12110077 -0.14933204 -0.05482764 -0.09003857]
delta: [-0.14836896 -0.1211031  -0.14933201 -0.05482448 -0.09004396]
delta: [-0.14837568 -0.12110513 -0.14933197 -0.05482161 -0.0900488 ]
delta: [-0.14838169 -0.12110689 -0.14933191 -0.05481902 -0.09005312]
delta: [-0.14838708 -0.12110844 -0.14933184 -0.05481666 -0.090057  ]
delta: [-0.1483919  -0.12110978 -0.14933176 -0.05481453 -0.09006047]
delta: [-0.14842624 -0.12111783 -0.1493309  -0.05479839 -0.09008521]
delta: [-0.14842699 -0.12111795 -0.14933088 -0.05479801 -0.09008575]
gradient descent converged after 90 iterations

 diff between GD solver and builtin solver:
[-1.74338949e-06  2.20755595e-06 -3.80123256e-06  5.16225588e-06
 -5.94081083e-06]
```