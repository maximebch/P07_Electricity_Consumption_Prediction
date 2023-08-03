# P07_Electricity_Consumption_Prediction
<h2><strong><em>Data Analyst Certification by OpenClassrooms, in partnership with&nbsp;ENSAE-ENSAI</em></strong></h2>
<p><em>Predicting electricity consumption for an energy supplier</em><br /><em>Skills:</em></p>
<ul>
<li><em>Master smoothing methods and the Holt-Winters method</em></li>
<li><em>Master the notions of components and decomposition models</em></li>
<li><em>Master the ARMA method</em></li>
<li><em>Graph a time series</em></li>
</ul>
<div>
<div>
<div>
<div>
<div>
<h1>Pr&eacute;disez la demande en &eacute;lectricit&eacute;</h1>
</div>
</div>
</div>
<div>
<div data-videotitle="video" data-current-user-id="7132501" data-project-id="150" data-codio-button-label="Acc&eacute;der au code">
<p><strong>Pr&eacute;requis</strong></p>
<p>Pour effectuer ce projet, vous devrez ma&icirc;triser la manipulation de donn&eacute;es en&nbsp;<strong>Python</strong>&nbsp;ou&nbsp;<strong>R</strong>, conna&icirc;tre la mod&eacute;lisation de type&nbsp;<strong>r&eacute;gression lin&eacute;aire</strong>, ainsi que les diff&eacute;rentes mod&eacute;lisations de&nbsp;<strong>s&eacute;ries temporelles</strong>&nbsp;(AR, MA, ARMA, ARIMA, etc.)&nbsp;</p>
<h3>Mise en situation</h3>
<p>Vous &ecirc;tes employ&eacute; chez Enercoop, soci&eacute;t&eacute; coop&eacute;rative qui s'est d&eacute;velopp&eacute;e gr&acirc;ce &agrave; la lib&eacute;ralisation du march&eacute; de l&rsquo;&eacute;lectricit&eacute; en France. Elle est sp&eacute;cialis&eacute;e dans les &eacute;nergies renouvelables.</p>
<p>La plupart de ces &eacute;nergies renouvelables est cependant intermittente, il est donc difficile de pr&eacute;voir les capacit&eacute;s de production d'&eacute;lectricit&eacute;. De plus, la demande en &eacute;lectricit&eacute; des utilisateurs varie au cours du temps, et d&eacute;pend de param&egrave;tres comme la m&eacute;t&eacute;o (temp&eacute;rature, luminosit&eacute;, etc.) Tout le challenge est de mettre en ad&eacute;quation l'offre et la demande !</p>
<h3>Les donn&eacute;es</h3>
<p>Voici&nbsp;<a href="https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DAN_V1_P9/data_conso.zip">les donn&eacute;es</a>.&nbsp;Ce sont les donn&eacute;es journali&egrave;res et non mensuelles, donc vous les devrez recompiler en donn&eacute;es mensuelles.</p>
<p>Pour les plus curieux et les plus motiv&eacute;s, voici&nbsp;<a href="https://www.rte-france.com/eco2mix/telecharger-les-indicateurs">les donn&eacute;es sources</a>. Libre &agrave; vous&nbsp;de recompiler les donn&eacute;es par vous m&ecirc;me pour arriver aux donn&eacute;es journali&egrave;res. Attention toutefois, c&rsquo;est un travail tr&egrave;s formateur mais relativement long et complexe. Votre mentor dispose d&rsquo;un notebook qu&rsquo;il pourra mettre &agrave; votre disposition si besoin.</p>
<p>Voici &eacute;galement les&nbsp;<a href="https://cegibat.grdf.fr/simulateur/calcul-dju">donn&eacute;es m&eacute;t&eacute;o</a>&nbsp;que vous utiliserez pour corriger les donn&eacute;es de l'effet temp&eacute;rature.</p>
<h3>Votre mission</h3>
<p><em>Vous vous concentrerez uniquement sur la pr&eacute;diction de la demande en &eacute;lectricit&eacute;.</em></p>
<ol>
<li>Corrigez les donn&eacute;es de consommation mensuelles de l'effet temp&eacute;rature (dues au chauffage &eacute;lectrique) en utilisant une r&eacute;gression lin&eacute;aire.</li>
<li>Effectuez une d&eacute;saisonnalisation de la consommation que vous aurez obtenue apr&egrave;s correction, gr&acirc;ce aux moyennes mobiles.</li>
<li>Effectuez une pr&eacute;vision de la consommation (corrig&eacute;e de l'effet temp&eacute;rature) sur un an, en utilisant la m&eacute;thode de Holt Winters (lissage exponentiel) puis la m&eacute;thode SARIMA sur la s&eacute;rie temporelle.</li>
</ol>
<p>Pour chaque traitement effectu&eacute; (correction de l'effet temp&eacute;rature, d&eacute;saisonnalisation, etc.), vous pr&eacute;senterez les 2 s&eacute;ries temporelles avant et apr&egrave;s traitement, sur un graphique o&ugrave; les&nbsp;deux s&eacute;ries temporelles seront superpos&eacute;es.</p>
<h3>Livrable</h3>
<p>Le livrable attendu est un fichier .zip, contenant :</p>
<ul>
<li>Le&nbsp;<strong>code</strong>&nbsp;en R ou Python permettant de r&eacute;pondre aux questions pos&eacute;es. Merci de bien commenter votre code. Un seul fichier suffit, mais veillez &agrave; s&eacute;parer celui-ci en plusieurs parties correspondant &agrave; chacune des&nbsp;trois questions pos&eacute;es.</li>
<li>&nbsp;Les&nbsp;<strong>graphiques</strong>&nbsp;au format jpg ou png.</li>
</ul>
<aside data-claire-semantic="information">
<p>Pour faciliter votre passage au jury, d&eacute;posez sur la plateforme, dans un dossier nomm&eacute; &ldquo;<em>P9_nom_prenom</em>&rdquo;, tous les livrables du projet. Chaque livrable doit &ecirc;tre nomm&eacute; avec le num&eacute;ro du projet et selon l'ordre dans lequel il appara&icirc;t, par exemple &ldquo;<em>P9_01_code</em>&rdquo;, &ldquo;<em>P9_02_graphiques</em>&rdquo;, et ainsi de suite.</p>
</aside>
<h3>Soutenance</h3>
<p>&nbsp;Voici le d&eacute;roulement indicatif de la soutenance :</p>
<div>
<div>
<table>
<tbody>
<tr>
<td>5min</td>
<td>Pr&eacute;sentation des donn&eacute;es utilis&eacute;es (source, pr&eacute;-traitements &eacute;ventuels, choix &eacute;ventuels, etc.)</td>
</tr>
<tr>
<td>5min</td>
<td>D&eacute;tail du programme (explication des lignes de code importantes, des objets manipul&eacute;s, etc.)</td>
</tr>
<tr>
<td>5min</td>
<td>Pr&eacute;sentation et interpr&eacute;tation des graphiques de la question 1</td>
</tr>
<tr>
<td>5min</td>
<td>Pr&eacute;sentation et interpr&eacute;tation des graphiques de la question 2</td>
</tr>
<tr>
<td>10min</td>
<td>Pr&eacute;sentation et interpr&eacute;tation des graphiques de la question 3</td>
</tr>
<tr>
<td>5 &agrave; 10 min</td>
<td>S&eacute;ance de questions-r&eacute;ponses &eacute;ventuelle</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
<h3>Comp&eacute;tences &eacute;valu&eacute;es</h3>
<ul>
<li>
<div>Maitriser les m&eacute;thodes de lissage et la m&eacute;thode de Holt-Winters</div>
</li>
<li>
<div>&nbsp;Maitriser les notions de composantes et de mod&egrave;les de d&eacute;composition</div>
</li>
<li>
<div>&nbsp;Maitriser la m&eacute;thode ARMA</div>
</li>
<li>
<div>&nbsp;Repr&eacute;senter graphiquement une s&eacute;rie temporelle</div>
</li>
</ul>
</div>
</div>
</div>
