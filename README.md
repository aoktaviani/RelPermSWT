# RelPermSWT
JScript source code to generate the SWT table using the Corey equatio
// JScript source code to generate the SWT table using the Corey equation
var swmin=Swcon;
var swmax=1-Soirw;
var kwlines="**$ Sw krw krow";
var sw=swmin;
var krw, kro;
while(sw<=swmax+0.00000001)
{
if(sw<=Swcrit)
{ krw=0; }
else
{ krw=Krwiro*Math.pow((sw-Swcrit)/(1-Soirw-Swcrit),nw);}
var next Sw=sw+0.01;
if(sw>1-Sorw||nextSw>swmax+0.000001)
{kro=0; }
else
{ kro=Krocw*Math.pow((1-Sorw-sw)/(1-Sorw-Swcon),no); }
kwlines+="\r\n"+" "+sw.toFixed(3)+" "+krw.toFixed(8)+" "+kro.toFixed(8);
sw=sw+0.01;
}
kwlines;
