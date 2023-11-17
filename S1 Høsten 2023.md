</head>
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>makeatletter
	\newpage 		
\begin{tcolorbox}[width=\textwidth ,colback={ lightgray}]
		\part*{DEL 1 (Uten hjelpemidler)}
	\end{tcolorbox}
 \section*{Oppgave 1 (2 poeng)}



 \begin{align*}
  \left( \dfrac{3a^{2}}{2b^{3}}\right) ^{2}.\left( \dfrac{a^{2}b^{-5}}{4}\right) ^{-1}&=\dfrac{\left( 3a^{2}\right) ^{2}}{\left( 2b^{3}\right) ^{2}}\cdot \dfrac{\left( a^{2}b^{-5}\right) ^{-1}}{4^{-1}}\\
  &=\dfrac{3^{2}\cdot a^{4}}{2^{2}\cdot b^{6}}\cdot \dfrac{a^{-2}\cdot b^{5}}{4^{-1}}\\
  &=\dfrac{3^{2}\cdot a^{4}\cdot a^{-2}\cdot b^{5}}{4\cdot 4^{-1}\cdot b^{6}}\\
  &=\dfrac{9\cdot a^{2}\cdot b^{5}}{4^{0}\cdot b^{6}}\\
  &=\dfrac{9\cdot a^{2}\cdot b^{5}}{1\cdot b\cdot b^{5}}=\dfrac{9a^{2}}{b}
\end{align*}


\section*{Oppgave 2 (2 poeng)}
$$  \begin{aligned}2\ln \left( e^{3}\right) &=2\cdot 3\cdot \ln \left( e\right) =2\cdot 3\cdot 1=6\\
e^{3\cdot ln2}&=e^{\ln 2^{3}}=e^{\ln 8}=8\\
3\lg \left( 70\right) &=3\cdot \lg \left( 7\cdot 10\right) =3\cdot \left( \lg \left( 7\right) +\lg\left( 10\right) \right)\\
& =3\cdot \left( \lg \left( 7\right) +1\right) =3\cdot \lg 7+3\\
\lg\left( 1\right)  &<\lg 7 <\lg\left( 10\right) \\
0 &<\lg 7 <13 \Rightarrow{}\lg \left( 70\right)<6\\
\end{aligned}
$$
Ut fra analysen over kan vi skrive tallene i stigende rekkefølge slik:
$$3\cdot\lg 70,\quad2\ln e^{3},\quad e^{31n2}$$
\section*{Oppgave 3 (2 poeng)} 
\subsection*{ a)}
Det er 6 mulige utfall for hver terning, så det er totalt $6^3 = 216$ mulige utfall for tre terninger.
Det er 6 muligheter for å velge antall øyne på første terning og 5 for andre og 4 for tredje . Antall gunstige utfall blir da $6\cdot 5\cdot 4$
$$Sannsynlighet=\frac{\text{antall gunstige utfall}}{\text{antall muligeutfall}}=\dfrac{6\cdot 5\cdot 4}{6^{3}}=\dfrac{6\cdot 5\cdot 4}{6\cdot 6\cdot 6}=\dfrac{5\cdot 4}{6\cdot 6}=\dfrac{5\cdot 2}{6\cdot 3}=\dfrac{5}{3\cdot 3}=\dfrac{5}{9}=0,56$$

\subsection*{ b)}
antall muligeutfall $= 6^3 = 216$ 
antall gunstige utfall:

Der er 6 muligheter for å velge første tall og 1 mulighet for å velge andre tallet  og det tallet som skal være forskjellig kan velges på 5 måter men alle tre tall kan endre plass og da må vi gange med 3. La oss kalle de to tallene som er like for x og det tallsom er forskjellig for y da har vi:
$$\begin{aligned}\left( x,x,y\right) \\
\left( x,y,x\right) \\
\left( y,x,x\right) \end{aligned}$$
Et eksempel når $x= 1$, og y kan da ha verdiene $2,3,4,5,6$:
\begin{align*}\left( 1,1,2\right) ,,\left( 1,1,3\right) ,,\left( 1,1,4\right) ,,\left( 1,1,5\right) ,,\left( 1,1,6\right) \\
\left( 1,2,1\right) ,,\left( 1,3,1\right) ,,\left( 1,4,1\right) ,,\left( 1,5,1\right) ,,\left( 1,6,1\right) \\
\left( 2,1,1\right) ,,\left( 3,1,1\right) ,,\left( 4,1,1\right) ,,\left( 5,1,1\right) ,,\left( 6,1,1\right) \end{align*}
Sannsynligheten da blir:
$$ \dfrac{3\cdot 6\cdot 5}{6^{3}}=\dfrac{3\cdot .6\cdot 5}{6\cdot 6\cdot 6}=\dfrac{3.5}{6.6}=\dfrac{5}{2\cdot 6}=\dfrac{5}{12}=0,42$$
\section*{Oppgave 4 (4 poeng)}

\subsection*{ a)}
Dette er hypergeometrisk fordeling. Vi lar X være antall svarte kuler som trekkes og m er antall svarte kuler og r totalt antall kuler som trekkes og n er total antall kuler
\begin{align*}
P\left( X=k\right) &=\dfrac{\begin{pmatrix}
m \\
k
\end{pmatrix}\begin{pmatrix}
n-m \\
r-k
\end{pmatrix}}{\begin{pmatrix}
n \\
r
\end{pmatrix}}\\
n&=7,m=3,r=3,k=2\\
P\left( X=2\right) &=\dfrac{\begin{pmatrix}
3 \\
2
\end{pmatrix}\begin{pmatrix}
4 \\
1
\end{pmatrix}}{\begin{pmatrix}
7 \\
3
\end{pmatrix}}=\dfrac{\dfrac{3!}{\left( 3-2\right) !2!}\cdot \dfrac{4!}{\left( 4-1\right) !\cdot 1!}}{\dfrac{7!}{\left( 7-3\right) !\cdot 3!}}\\
&=\dfrac{\dfrac{3!}{2!}\cdot \dfrac{4!}{3!}}{\dfrac{7!}{4!\cdot 3!}}=\dfrac{4!}{2!}\cdot \dfrac{4!\cdot 3!}{7!}=\dfrac{4\cdot 3\cdot 2!\cdot 4!\cdot 3\cdot 2\cdot 1}{2!\cdot 7\cdot 6\cdot 5\cdot 4!}\\
&=\dfrac{4\cdot 3\cdot 3\cdot 2}{7\cdot 6\cdot 5}=\dfrac{4\cdot 3}{7\cdot 5}=\dfrac{12}{35}=0,343=34,3\%
\end{align*}
Det er $34,3 \%$ sannsynlighet for at to av de tre trukne kulene er svarte.\\
Metode 2:
La h representere hvite kuler og s svarte kuler:

\begin{align*}
P(2s)=P(ssh)+P(shs)+P(hss)&=\dfrac{3}{7}\cdot \dfrac{2}{6}\cdot \dfrac{4}{5}+\dfrac{3}{7}\cdot \dfrac{4}{6}\cdot \dfrac{2}{5}+\dfrac{4}{7}\cdot \dfrac{3}{6}\cdot \dfrac{2}{5}\\
&=\dfrac{3}{7}\cdot \dfrac{2}{6}\cdot \dfrac{4}{5}\cdot 3=\dfrac{12}{35}\end{align*}

\subsection*{ b)}
P(minst to hvite kuler ) =P( 2 hvite og 1 svart ) + P (3 hvite kuler og 0 svarte kuler ) =  P( én eller ingen svarte kuler) $=P(X=0)+P (X=1)$
\begin{align*}P\left( X\leq 1\right) &=\left( X=0\right) +P\left( X=1\right) \\
&=\dfrac{\begin{pmatrix}
3 \\
0
\end{pmatrix}
\begin{pmatrix}
4 \\
3
\end{pmatrix}}
{\begin{pmatrix}
7 \\
3
\end{pmatrix}}
+\dfrac{\begin{pmatrix}
3 \\
1
\end{pmatrix}
\begin{pmatrix}
4 \\
2
\end{pmatrix}}
{\begin{pmatrix}
7 \\
3
\end{pmatrix}}=\dfrac{1\cdot \dfrac{4!}{1!\cdot 3!}+\dfrac{3!}{2!\cdot 1!}\cdot \dfrac{4!}{2!\cdot 2!}}{\dfrac{71.}{4!\cdot 3!}}\\
&=\dfrac{\dfrac{4\cdot 3\cdot 2\cdot 1}{3\cdot 2}+\dfrac{3\cdot 2\cdot 4\cdot 3\cdot 2}{2\cdot 2\cdot 2}}{\dfrac{7\cdot 6\cdot 5\cdot 4\cdot 3\cdot 2}{4\cdot 3\cdot 2\cdot 3\cdot 2}}=\dfrac{4+18}{7\cdot 5}=\dfrac{22}{35}=0,629=62,9\%
\end{align*}
Det er $62,9 \%$ sannsynlighet for å trekke minst to hvite kuler.\\

Metode 2:
La h representere hvite kuler og s svarte kuler:
\begin{align*}P\left( 3h\right) &=\dfrac{4}{7}\cdot \dfrac{3}{6}\cdot \dfrac{2}{5}=\dfrac{4}{35}\\
P\left( 2h \,og \,1s\right) &=p\left( shh\right) +p\left( hsh\right) +p\left( hhs\right) \\
&=\dfrac{3}{7}\cdot \dfrac{4}{6}\cdot \dfrac{3}{5}+\dfrac{4}{7}\cdot \dfrac{3}{6}\cdot \dfrac{3}{5}+\dfrac{4}{7}\cdot \dfrac{3}{6}\cdot \dfrac{3}{5}\\
&=\dfrac{3}{7}\cdot \dfrac{4}{6}\cdot \dfrac{3}{5}\cdot 3=\dfrac{18}{35}\\
p\left( \minst\,2h\right)& =P\left( 2h\,og\,1s\right) +P\left( 3h\,og\,0s\right) \\
&=\dfrac{18}{35}+\dfrac{4}{35}=\dfrac{22}{35}=0,629\end{align*}
\section*{Oppgave 5 (2 poeng)}
\subsection*{ a)}
Når programmet kjøres regnes det når den deriverte av K (som er vist i while-løkke betingelsen) blir 260.\\
Vi regner x algebraisk:
\begin{align*}
K\left( x\right) &=0,2x^{2}+140x+7000\\
K'\left( x\right)&=0,4x+140\\
K'\left( x\right) &=260\\
0,4x+140&=260\\
0,4x&=120\\
x&=\dfrac{120}{0,4}=\dfrac{1200}{4}=300\end{align*}
 Resultatet blir $x=300$. Kostnaden øker med 260 kr per enhet per uke i det bedriften produsere akkurat 3$00$ enheter per uke.




\begin{tcolorbox}[width=\textwidth ,colback={ lightgray}]
			\part*{DEL 2 (Med hjelpemidler)}	
		\end{tcolorbox}
		
		\subsection*{Oppgave 1  (8 poeng)}

  
		\subsubsection*{ a)}
  Vi har
\begin{align*}
    
\text{Ny Verdi }&=\text{Gammel Verdi}\cdot \text{Vekstfaktor}^ \textit{antall perioder}\\
N&=G\cdot V^n\\
V&= \left(\frac{N}{G}\right)^{\frac{1}{n}}\\
1+\frac{P}{100}&=(\frac{N}{G})^{\frac{1}{n}}\\
p=\left( \left(\frac{N}{G}\right)^{\frac{1}{n}} -1 \right)\cdot 100
\end{align*}
Vi bruker 2008 som gammel verdi og 2022 som ny verdi og antall år er 15år og løser ligningen i Cas. 
\begin{figure}[H]
		\centering
		\includegraphics[width=0.5\linewidth]{d2o1a.png}
		\caption{}
		\label{fig:del2oppgave1a}
	\end{figure}
 den Den gjennomsnittlige årlige prosentvis vekst blir $1,5 \%$.
 
Om jeg tar hensyn til alle årene så kan jeg regne gjennomsnittlig årlig vekst i Geogebra ved å bruke formelen 
    $$
p=( (\frac{N}{G})^{(1/n)} -1 )\cdot 100$$:

\begin{figure}[H]
		\centering
		\includegraphics[width=0.6\linewidth]{d2o1a1.png}
		\caption{}
		\label{fig:del2oppgave1a}
	\end{figure}
 \begin{figure}[H]
		\centering
		\includegraphics[width=0.7\linewidth]{d2o1a3.png}
		\caption{Med formler}
		\label{fig:del2oppgave1a}
	\end{figure}
Den gjennomsnittlige årlige prosentvis vekst blir $1,65 \%$
  \subsubsection*{ b)}
		Vi setter punktene i regneark i Geogebra og lager liste med punkter så bruker vi regresjon (RegEksp()) for finne funksjonen. Se skjermbilder nedenfor. 
	
		
	\begin{figure}[H]
		\centering
		\includegraphics[width=0.7\linewidth]{d2o1b1.png}
		\caption{}
		\label{fig:del2oppgave1a}
	\end{figure}
 Grafen til funksjonen $g(x)$ er vist nedenfor:
\begin{figure}[H]
	\centering
	\includegraphics[width=0.7\linewidth]{d2o1b2.png}
	\caption{}
	\label{fig:del2oppgave1a1}
\end{figure}

	
	
		\subsubsection*{ c)}
		Vi lager en funksjon som gir oss timelønn til Per i årene 2008-2022:
  
	
	\begin{figure}[H]
		\centering
		\includegraphics[width=0.5\linewidth]{d2o1c1.png}
		\caption{}
		\label{fig:del2oppgave1c}
	\end{figure}
 Så regner vi samlede lønn i Cas vis Sum kommando:
 \begin{figure}[H]
		\centering
		\includegraphics[width=0.5\linewidth]{d2o1c2.png}
		\caption{}
		\label{fig:del2oppgave1c}
	\end{figure}
 Samlede lønn til Per er $7905086,2904\,\,kr$ og til Amalie er $8188601,2366\,\,kr$
		\subsubsection*{ c)}
		Vi bruker Cas til å løse oppgaven ved å sette prosentvis økning til lønnen til Per som ukjent P 
	\begin{figure}[H]
		\centering
		\includegraphics[width=0.5\linewidth]{d2o1d1.png}
		\caption{}
		\label{fig:del2oppgave1d}
	\end{figure}
	
	Lønnen til Per må øke med $2,18 \%$ hvert år for at begge to skal ha lik timelønn i 2025.
	
		\subsection*{Oppgave 2  (6 poeng)} 
			\subsubsection*{ a)}
	Vi tegner begge utrykkene som funksjoner via graftegner i Geogebra og ser at de er bare like to steder så påstanden ikke gjelder for alle $x>0$ og dermed ikke sann.
\begin{figure}[H]
	\centering
	\includegraphics[width=0.5\linewidth]{d2o2a1}
	\caption{}
	\label{fig:del2oppgave3a}
\end{figure}
\begin{figure}[H]
	\centering
	\includegraphics[width=0.7\linewidth]{d2o2a2.png}
	\caption{}
	\label{fig:del2oppgave3a1}
\end{figure}
	\subsubsection*{ b)}
	Påstanden er sann. Den generelle formen på fjerde gradsfunksjon er gitt i rad 1. Vi ser at den kan ha maks tre ekstremale punkter fordi den deriverte er tredje gradspolynom. Vi tar det enkleste tilfellet (rad 3) og ser at det er likevel et ekstremalpunkt fordi den deriverte skifter fortegn.
	 
	\begin{figure}[H]
		\centering
		\includegraphics[width=0.5\linewidth]{d2o2b}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
	
		\subsubsection*{ c)}
        Påstanden er sann.
        Dette er hypergeometrisk forsøk siden det er to grupper (mindre enn 18 (m=17) og større enn eller lik 18 (n-m=34-17=17) og trekningen er uten tilbakelegging. vider er X antall trekk fra gruppen som er mindre enn 18 og k er hvor mange tall som er mindre enn 18 blir trukket ut.
       \begin{align*}P\left( X=k\right) =\dfrac{\begin{pmatrix}
m \\
k
\end{pmatrix}\begin{pmatrix}
n-m \\
r-k
\end{pmatrix}}{\begin{pmatrix}
n \\
r
\end{pmatrix}}\\
n=34,m=17,r=7\\
\end{align*} 
Sannsynligheten for at all de 7 tallene er mindre enn 18 blir $P\left( X=7\right)$.  Vi regner den via sannsynlighetskalkulator i geogebra:
 \begin{figure}[H]
		\centering
		\includegraphics[width=0.8\linewidth]{d2o2c1}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
Sannsynligheten for at ingen av de 7 tallene er mindre enn 18 blir $P\left( X=0\right)$.  Vi regner den via sannsynlighetskalkulator i geogebra:
 Vi regner $P\left( X=0\right)$ via sannsynlighetskalkulator i geogebra:
 \begin{figure}[H]
		\centering
		\includegraphics[width=0.8\linewidth]{d2o2c2}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
Vi ser at begge to er like.

\textcolor{red}{OBS!:}\\
Om man regner null som et naturlig tall blir antall tall som er mindre enn 18, 18 tall og da blir $P(X=7)=0.00592$ og $P(X=0)=0.00213$ og da blir påstanden usann.
\begin{figure}[H]
		\centering
		\includegraphics[width=0.8\linewidth]{d2o2c3}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
 \begin{figure}[H]
		\centering
		\includegraphics[width=0.8\linewidth]{d2o2c4}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
		\section*{Oppgave 3(4 poeng)}
			\subsubsection*{ a)}
   Mona regner ut sannsynligheten for at summen av øynene på to terninger blir er større eller lik 8 (med andre ord) 8, 9, 10, 11 eller 12). Hun teller antall gunstige utfall via betingelsen i if setning (i + j >= 8) og deler det på antall mulige utfall (6*6 = 36), der hver terning har 6 mulige øyne.
	 \begin{figure}[H]
		\centering
		\includegraphics[width=0.7\linewidth]{d2o3a}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
  Sannsynligheten for at summen av øynene på to terninger blir er større eller lik 8 $=0,417=41,7\%$
	\subsubsection*{ b)}
 Vi foreslår dette programmet for å regne sannsynligheten for at summen av øynene på tre terninger blir 7 eller 11:
 \begin{figure}[H]
		\centering
		\includegraphics[width=0.7\linewidth]{d2o3b}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
Vi kjører koden og får at Sannsynligheten for at summen av øynene på to terninger blir er større eller lik 8 $=0,195=19,5\%$	
\subsection*{Oppgave 4 (6 poeng)} 
	\subsubsection*{ a)}
Vi finner funksjon $e(p)$ til den rette linjen som er vist på figuren (rad 1,2,3) så finner vi inntekt funksjon ved å gange prisen med antall produserte enheter (rad 4) så finner vi inntekten når prisen er 40 kr og får at de daglige inntektene blir $84000\,kr$ (rad 5).
\begin{figure}[H]
		\centering
		\includegraphics[width=0.5\linewidth]{d2o4a}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
 \subsubsection*{ b)}
 Vi løser ligningen $I(p)=75000$ i Cas og får at prisen blir $p=20 \,eller \,p=50$ (rad 6).
 \begin{figure}[H]
		\centering
		\includegraphics[width=0.5\linewidth]{d2o4b}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
 
 \subsubsection*{ c)}
  Vi løser oppgaven via CAS. Vi deriver inntektfunksjon og finner ut når den er lik null (rad 7).Vi bekrefter at dette er toppunkt ved andrederiverttesten (rad 8). De daglige inntektene er størst når prisen er $p=\frac{75}{2}=37,5\,kr$  

 \begin{figure}[H]
		\centering
		\includegraphics[width=0.5\linewidth]{d2o4c}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}



 \section*{Oppgave 5(4 poeng)}
			\subsubsection*{ a)}
a) Dette er binomisk forsøk der det er n=1300 delforsøk og i hvert delforsøk er det kun to muligheter (enten billetten blir benyttet eller ikke) og sannsynligheten for at billetten blir benyttet er det samme i hvert forsøk (p=0.45)
Vi bruker geogebra sannsynlighetskalkolator for å regne:
\begin{figure}[H]
		\centering
		\includegraphics[width=0.7\linewidth]{d2o5a}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
Sannsynligheten for at minst 600 av billettene blir benyttet er $0,20935=20,94\,%$
\subsubsection*{ b)}
Vi tester med ulike verdier for n (n=1400,n=1401)
\begin{figure}[H]
		\centering
		\includegraphics[width=0.7\linewidth]{d2o5b1}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
 \begin{figure}[H]
		\centering
		\includegraphics[width=0.7\linewidth]{d2o5b2}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
  Det må deles ut minst 1401 billeter for at minst 600 av dem skal bli benyttet.

  Metode 2: Programmering\\
  Om vi lager en funksjon for binomisk formel, får vi feil melding pga gang av veldig store og veldig små tall i utregningene
  \begin{figure}[H]
		\centering
		\includegraphics[width=0.8\linewidth]{d2o5b3}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}
 Vi kan bruke binomisk modell fra SciPy biblioteket for å løse oppgaven
\begin{figure}[H]
		\centering
		\includegraphics[width=0.9\linewidth]{d2o5b4}
		\caption{}
		\label{fig:del2oppgave3b}
	\end{figure}

	\subsection*{Oppgave 6  (6 poeng)} 
	\subsubsection*{ a)}
Vi bruker Cas og finner at lydintensiteten blir $10 \frac{W}{m^2}$ (Se rad 3).

\begin{figure}[H]
	\centering
	\includegraphics[width=0.5\linewidth]{d2o6a.png}
	\caption{}
	\label{fig:s1del2oppgave2a}
\end{figure}

\subsubsection*{ b)}
Vi lar $L_1,L_2$ være lydstyrkene når lydinensitetene er $l_1,l_2$ så løser vi ligningen $L_2-L_1=2$ for $l_2$ (rad 7) og får at $l_2=\sqrt[5]{10}\cdot l_1$ . Fra dette finner vi økning i prosent $p$ (rad 8). Lyd intensiteten øker 58,5\% når lydstyrken øker med 2 db
\begin{figure}[H]
	\centering
	\includegraphics[width=0.5\linewidth]{d2o6b.png}
	\caption{}
	\label{fig:S_1del2oppgave2b}
\end{figure}
\subsubsection*{ c)}
Første finner vi effekten av lydkilden (rad 11) så finner vi ut hva blir lydintensiteten når lydstyrken er mindre enn $130 \,dB$ (rad 12) . Så bytter vi lydstyrken med formelen som inneholder effekt og løser ulikheten for r (rad 13)
\begin{figure}[H]
	\centering
	\includegraphics[width=0.5\linewidth]{d2o6c.png}
	\caption{}
	\label{fig:S_1del2oppgave2b}
\end{figure}
Vi dropper den negative løsningen og får at avstanden må være minst 185,114 m for at lydstyrken skal være mindre enn $130 \,dB$.



	
		
		
		
				
\end{document}
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']],
      processEscapes: true,
    },
    "HTML-CSS": { availableFonts: ["TeX"] }
  });
</script>
