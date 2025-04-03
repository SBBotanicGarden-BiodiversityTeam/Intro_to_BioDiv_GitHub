[VMMV_pycno_k10_ordered.pdf](https://github.com/user-attachments/files/19579846/VMMV_pycno_k10_ordered.pdf)# Basic markdown (.md) file formatting
[Basic instruction for creating repository with an .md (markdown) file](#basic-instruction-for-creating-repository-with-an-md-markdown-file)  
    - [On GitHub](#on-github)  
    - [On CLI - *in the works*](#on-cli-command-line-interface-aka-terminal)  
[Formatting for a GitHub markdown file](#Formatting-for-a-github-markdown-file)

## Basic instruction for creating an .md (markdown) file on GitHub
Within a repository, we make, store, edit, all sorts of things - markdown files (help us keep track of our pipeline), code, results, other documents, other folders of documents. Here we focus on the markdown file. 

To make a markdown file, click on the "Add file" at the top right of the inner window. This will open a fresh file where you can compose your new file. This can be a markdown file, straight code, etc. 

A markdown file helps to keep track of your pipeline and parameters you used so that it is reproducible. **It is only as good as the extent to which you document it.** To make a markdown file, name your file something descriptive with a `.md` end in the space at the top right.

## Editing an .md file and "commiting changes"
Before we get into formatting, the green Commit Changes button at the top right is key. Once you have written something in the window, click commit changes, and then if you wish add a note about what you did to the doc, and then click commit changes again. You will see the fruits of what you have written in html format and this also essentially functions as a `Save` button. If you close the window with out commiting changes, you will lose whatever you just did before the most recent "Commit Changes". If you want to edit again, click on the pen icon at the top right. 

## Formatting for a GitHub markdown file
*For all formatting examples, if possible I will put what is typed into the codespace as well as what that looks like once we commit changes.*

Normal text can be written, well, normally

    Normal text can be written, well, normally

To put anything in codespace window, you just indent those lines one or more tabs:

        To put anything in codespace window, you just indent those lines one or more tabs:
If you have many lines of code you want in codespace, highlight the whole block and hit `tab` or `command ]` to indent/put it in code space it all at once.

To put `filenames` or short lines of code into `code font` you add ticks around it. This has to be the tick marks found on the same key as the tilda `~`. 

        To put `filenames` or short lines of code into `code font` you add ticks around it.

*tip: if its code you are putting in codespace, use just one tab. Later if you want to copy that code from the codespace window, you won't have to delete the extra tab at the begininning of each line.
### Headers
    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
    ###### H6
# H1
## H2
### H3
#### H4
##### H5
###### H6

### Emphasis

Italics with *asterisks* or _underscores_. \
Bold, with double **asterisks** or double __underscores__. \
Combine with **asterisks and _underscores_**. \
Strikethrough with two tildes. ~~Scratch this.~~

    Italics with *asterisks* or _underscores_.

    Bold, with double **asterisks** or double __underscores__.

    Combine with **asterisks and _underscores_**.

    Strikethrough with two tildes. ~~Scratch this.~~

### Lists and bullet points

1. First list item
2. Another item
      * Unordered sub-list.
      * Unordered list can use asterisks
           - Or minuses
           + Or pluses
           * All will be bullet points
1. Actual numbers don't matter, just that it's a number
      1. Ordered sub-list
      2. Second item
4. And another item.

   You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown). \
   To have a line break without a paragraph, you will need to use two trailing spaces or a `space \`.  
   Note that this line is separate, but within the same paragraph.  

        1. First ordered list item
        2. Another item
        [tab] * Unordered sub-list.
              * Unordered list can use asterisks
                    - Or minuses
                    + Or pluses
                    * All will be bullet points
        1. Actual numbers don't matter, just that it's a number
        [spaces]1. Ordered sub-list will change this 1 to i 
        [spaces]2. Ordered sub-list will change this 2 to ii
        4. Another item.
  
      [3spaces]You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown). \
      To have a line break without a paragraph, you will need to use two trailing spaces or a `space \`.[2spaces]
      Note that this line is separate, but within the same paragraph.[2spaces]
  
### Links
There are two ways to create links.
1. Hyperlinked text:  
    [hyperlinked text to CCH2](https://www.cch2.org/portal/collections/search/index.php) \
2. plain ol' URLs in angle brackets will automatically get turned into links. 
https://sbbotanicgarden.org/ or <https://sbbotanicgarden.org/>

        1. Hyperlinked text: \
            [hyperlinked text to CCH2](https://www.cch2.org/portal/collections/search/index.php) \
        2. plain ol' URLs in angle brackets will automatically get turned into links. \
        https://sbbotanicgarden.org/ or <https://sbbotanicgarden.org/>
   
### Table of contents
Similar to linking but within your doc. The format is:  
`[whatever text you want in table](#exact-text-you-want-to-link-to-no-caps-no-symbols-dash-separated)`

[1. Top of page to Basic instruction](#basic-instruction-for-creating-repository-with-an-md-markdown-file)

### Images

[%PDF-1.4
%���� ReportLab Generated PDF document http://www.reportlab.com
1 0 obj
<<
/F1 2 0 R
>>
endobj
2 0 obj
<<
/BaseFont /Helvetica /Encoding /WinAnsiEncoding /Name /F1 /Subtype /Type1 /Type /Font
>>
endobj
3 0 obj
<<
/Contents 7 0 R /MediaBox [ 0 0 1500 450 ] /Parent 6 0 R /Resources <<
/ExtGState <<
/gRLs0 <<
/ca 0
>> /gRLs1 <<
/ca 1
>>
>> /Font 1 0 R /ProcSet [ /PDF /Text /ImageB /ImageC /ImageI ]
>> /Rotate 0 /Trans <<

>> 
  /Type /Page
>>
endobj
4 0 obj
<<
/PageMode /UseNone /Pages 6 0 R /Type /Catalog
>>
endobj
5 0 obj
<<
/Author (anonymous) /CreationDate (D:20250401125800+08'00') /Creator (ReportLab PDF Library - www.reportlab.com) /Keywords () /ModDate (D:20250401125800+08'00') /Producer (ReportLab PDF Library - www.reportlab.com) 
  /Subject (unspecified) /Title (untitled) /Trapped /False
>>
endobj
6 0 obj
<<
/Count 1 /Kids [ 3 0 R ] /Type /Pages
>>
endobj
7 0 obj
<<
/Filter [ /ASCII85Decode /FlateDecode ] /Length 4755
>>
stream
Gb!$Lh2g@"'uf))YL$cp^l53&8pZF:-UI&TY'5F\/e"Lu;X?B&2aNT+^(`dWOsA#&e57D@Aj)KPH[iW^*D5K'Tp8W[^SL])p/4o:m]%qSQBc9d]6BP,6s&3XXBs]<LnQc2H!8s8>sH+'k3![drU6UAs7Pp\bnohU^O3,`pQ%6TbYV6iFf"`jj1hX=:Y`#<pOBc(5?)['.p_O?a\eL>&,'-^R\u@!p-\MV-YX=m>p#m[PcTQ'L?1,MHl0F.rUp"+NR>dE28dXP\lS#bA&=#%d(N0VDk9*pNY>oUV)2jbU)R,$.jncL/YIgj/lgY"@VDXTeP!a^Skk:0C"gpiBkTX\Nad)2.k#V@3iPLlQ(P!#N7%I&W18V8PL'h):MCZP$YWt^MuIR3`)&CAVNNWakL6/ORb%.@dKMcc$"J2\/Zbjaj!<\Fq70,8(g]H8lWl!j2F>0H3`ds@'6l\mWi'Pu0D*0.<>rmH!a8^p;@RX\P<O@q0*r;:4tWe4BrVdA=5;,%)TM7J>$15kNHHnc](^92KF'c5(=gm@DU^<]Q)>p:$nn9-oe^NK69kBQV-sccTS<%ke^X:Z[_6eUOt_IMe"V/W2N4@N7R'sg(rH_p@6K$Q:cD:R^B[>t_"28;]pY`YZ(<JL_?aI7$gMGpX@Js+^3gR5n,ccqDl32*X?W,R0S5Y<JpK4ilGRuQ]*]d-#q`*RBh^[FZ!F4Z$"J2\/Z^n[7OdVBRCY56i$Gb'Su1cDM-/(QBc+_qBOSTBV?YGKAa7\tJsXi9HCEF,>)[Ki\g36n"gkMj9^=dFY4>Y&">?GPok)o7M"OsH.ZE:3[%O"foj'0GDOJ']N8XrIYhi%m>Ht?C=()4bT`t*G9f7Q*Y><V$L)84RH8BE:70&7@#[P;NbA#HK>LCW*hNBQZ(U1bs1TXYe]ir&U,BaAFW&IBG788P5A#Q/INh]>/=Gab1/(*XSl;=Q&UsO3HaJ122N5sB?+H<2b0cEjFK05U>a*9_+&+XB`+6:gk5/uV3I?6tJqA>9kp-B`ompeJOiWj`cbn'AYWZU9kF?djA.=[;se,CbVV>`b%:&gtNQ32[.=<7I`UU^@QO6$Io4IQq6nlT2uaJ69H.$*HpTKJMb!:kM+'j1Sff+C8^C]2$]:q;Sd8.4^dQ@R,""AmZI4g5&gVBZ)HK(=I=TQ2%RPd].eQ@LH)":RgsF<uZ5*TdWX'Ug6Hnn=$``a_"1+H>Ff?o4H"!:jf`!64%Z![*Qd#_5$E;<i:#++NJ]pn9f_!9:5DB"j(#Tf_1fnf.^m]0P(R[//cEE!cG=Sl:/Z=3,c0)nOBJn3_J]!Q\Oh6S"B09`m>;k8RgYQ-kPb;k\?l7e5=:OLeD-ofAl*p7[,sL@SRPOLnKA1M>Q2X)tfqH!UPA%2a/g0(K\2:nFQbEbV*H``jrC^"P=nneKqVT!s5j(J(H2fL5^j)p7ah5]-kl]?"Tg,C*#d8p(kKA2L5iT)kdjo`L[LjgkjC/Z9bY$nBk=5\Y$4^g^-N%Kf60l3@NGb4QQIg0-_F(K@QL!7HJqJ[qFo]`jY/ednhcQ0Tuo[&(KuG#;JO^DY/b(I0J00;uru:us7D?.^89Ys.V.CiIQgT6D'R\O@d^=4dM>Z$s_nfH>WPQU.`'o/e0$I0MfMQN9S7m4uJ%]Nk^QO1*43UTnt[5W%IQ",t:TAH;7V]*pA7DjLLEbOZG!TrZ*eI\sRc%&Jf7r&g$K*P+ioj(EZI_,-S&aNsArQB=#)N1K&mX<U;;+Zn/&=GP>C6@P42iCD=t13Tf>Yn!UeKm_`P#De`48d%LQ@OXOfSQLZq`'Sp=9<jMq=f#rMX&+pYZ#O?6Z2ge3K3Z>]I#8AR)%1C42TS<<`1ts-Qa$OG@Y7q(6MuZLEZ#7(-T9%WX:0#V*D*ODfbB2CAMG/3O@=+::ssfJ![LV_$C&MK.$Qn1Lp7mK]uWm&3><Tik"pRjRR;Yr=:PL*,<6GTNTX,g4ISWgnTYNIaJ1a0+R_">!okBc:k8J]*"%XSS3m>J%rj!Op+[$\a?IhA!;VC0'H$^,LB?Pc*"%XKS3qkuO)cX6rZMaTb%<UI.#[%\J1QRFJ[-+&"j!Dt'I\mu:k1*S6\2N[%L(!9_P$t_'Sca$0cUO^7;sYOdXHrQ,Z,NgPXTO>B$a58a5*Tn6En*/#f\VH&/`NSJ5@4Y!^Y63#RJF*,7k^:M1Atb)ZkU3jZt$Y_[HeVI['_[^^mam+SZP_!s1[)FF_/bER6O3kCekJ)_,kJ+SZOl!s1[1COk=oUB,odjt^?6K.I34^6Y&\B/[a6K,lF\(bde_?GJf/DZKnoN!0VXE"sK,_c"98"?ung1!Bb/6uWbmcs#e!aRsBH!!4pg!t7RO%Ns,If)W_T[L=8e__8ejN9q&61sW][VFpL@@CmC2#]2@"L84-IJ8hTl$lFr1P6$:*2DSZ"g-,]Ha4nUaiFoh?0Use0erW=fS+WLdlN.1u0nEtFT`t<.0PGtC]E/0efq\U66VQDM=D5Or":Q2V!cu.Bo/@p[a:K!:!Z%3;%fo$M&1NQK>U6d!GhDWo;CA.H]o_O+%PZ`$mlZ,^+XHOX<%PfSm04Ca^]Y^/b-V.&=BIc6rsk@0_#T.kQpCC-24D:\!/%GAH-Sb$mm\A,?%BjD."jC"'n@^PV?./pfi%mF(g@>$'P0c8Lgk0K^eg9o"<`T,SH)&D2S^';"@_!+!2:<W#;?j#lMq4E^N0AW;)So7.#&J0PtSN6q`QSt794r]Dur9o:c`Os<3?f5dXq=H&YO/m!/q]E?[Vp>B`ime[<c3_W(\!-@tj"H(I7)N!$Ekl+.*$Xf)rg%@K!tD:q7>A8.4]i,)MoS!.ZoE!f5MKb7qsJPlCruLkQ-6%<;a_deOjC+r2Bk2om9r8CqdAMcdK^?O#MS68#"pD3)L`b?0jbh]N`?&G<b'/n%'*I=keE!]9cY\VQLqeUruDX-Ck*l6qQ6eNjs>X.q5#=9htC[>qO0EZJ[foK(-(#^2HO;!]<_,2#g/6aMCrJnRYGqc,^KU<%MB`R+"nhgt]qC0+`KDtF+]7hkh)Z@IV,oaPe&#uKn+e,g,Qd]]YG*(ZcA?jfM]3oAlXP9=GN_(?cQWdKG'5b]ZIKZ)9u&;d.$&J@Tl6R7O%7n=U?%[#s)*26=f3'uUQE/6p0hpC8*VPnEl`6d?P.Fc_H8sOV$MNg%hB'=,k`),8$M5%O8&jpY+,`:Hu8.;m8OXOBP,;GE@7UkRtLdY+n(l=rk+VI(LA"<Mo)WFTC2+F><4Tah#.dg0c+G$8j5o)mt@k<AS#"\r_NKH1])e;g12TF`iD3.1`gE;EK[kSXgEJ#g"k/LLCeIAf4\f5.!PW-Yjl<P%!S#a+d,"6]c/<99*=VU64r\\8EqF4Trr=-&aHC%%cDJAWCYEq!nGNB'4Pe6Kr/C%Ps5o/Rbr"t?5=+66"\LTnainTe@A5Vd;&$d$U*+X'W_@Nq#GN$SEN4\S3,f3j^0bWY%r#i%:Q`o+J<jhpiG*D`(=)Tbk&EN0baS?D>)ft/le_`3)IeioJWok`?eSV>W5ETPQf<[RqRbJ'Cql%H2P0NfH^-FIjqE=nCh:Yc]j7WMBCep%]:%eUVCsI0o4mXHpPO6J-)"!"P!)9n7,MVf&JB@6OdT4r)DulDDc52-#GmV8sHNL-_cV&d8gD/Q<]EDoR?(u2^9)p<n27N!(X6!W;-C[H2[66/DqSmL?U3U+Uk@gkukA&cA&qJ)Ij_AYQ97S@Y,tZdMQN0]#CV'Sks.Ut!`Nul!"_b3Nj\2rj^uWU!D+:Du!)7XnR?`$j3P=EU1X%Fr/qB.f]B,2]J0mp!=4s?T!]\m.:[YH8!%1u<aX+P!9l@%"<&snd"$"t9545Y'J0qbF_f:J!"$"u&1+q5`BQ@`k(7XXm38&O'm]_*>-Q<</*OZL:1U=DFg_ncKE3f-b>d=a'jQ'3N:o`rpq4j'ad+;c'C]DWYcZ1$NK+"TLDk>cb?[St/d^n`3S\@u7@s.OOH?#8m<H;(uYA6qsJ+RJ:%!+R;a'YF_hsW2J?bUpcjl;j)D]X@U]RP1tiMX^<+!6!Fkhtpe^:`'UKY%3(oC$U)h`cDYnZUL!J#^+.1H2u'qg;>cp!m36)@0%hf6q:GC1K0_Y=HpeeAQ%C?RMJAWO=-1[9UJ=V('N"b3Oqk1t</+>4g*CRVE^7Go_'oVE.%BMa%%pRelJk+5["hprf/95Q%CRf3d@BFZXtr0C)BTqcBu8Hh0mU?XC=8VQXX0Y@_][?<*VpYNMddG%Y0?i'0qC?^\X>]mY/Zi\Z(s0R`UUqslqm.GAM`.Hdi<h:6_]](-?V=k[Ub>JpE?gLkm0>0NhLo[T>CeG\bn]@uhaf.#G%Dm%KZ][Y4cf5/X$VBpTG)YUW#*Q-@uA^=T@hS-XjH()J6H#)-efAa-.VD!#I)X>"a3=km9D=qM[)!(WSH6qA,bW'tG1jtd'@q^&[jdbqkoOX>JU#"Ii2t]tqQWZ5$DKfIUo7jUDV9Jh;=8-(8f[lJe.-*45RJ0cIm-VuG8opH8bknF_GPC2_5WVVHk5Eh+Hi*B+D4ROW.jsZ=ICYEprqsLEHu[mLdOZ?.]`7Eq\%c7lg[ZElStrL.X;YBN].NbSj[n0@c(`Un]A%?JU7S0_cE%mh\$mshna9!&lHPL>ot/t!+$?0k/bQMc97<Ndhq7eL&Ei>!ZF?\7G7?HNHdgo!\51Z+N7;H/R[j1uWl-a_&_N\9>1B2>l1nE'Gq[)XFYNc,%VD<A5NlM9`ls+N!:s97o7,Lc"V^~>endstream
endobj
xref
0 8
0000000000 65535 f 
0000000073 00000 n 
0000000104 00000 n 
0000000211 00000 n 
0000000460 00000 n 
0000000528 00000 n 
0000000824 00000 n 
0000000883 00000 n 
trailer
<<
/ID 
[<e88d6e3816b8eb7fb227c9ff85b6b92c><e88d6e3816b8eb7fb227c9ff85b6b92c>]
% ReportLab generated PDF document -- digest (http://www.reportlab.com)

/Info 5 0 R
/Root 4 0 R
/Size 8
>>
startxref
5729
%%EOF
Uploading VMMV_pycno_k10_ordered.pdf…]()

### Emojis

https://gist.github.com/rxaviers/7360908
