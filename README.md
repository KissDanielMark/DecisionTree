# DecisionTree
Adatbányászati technikák HF
Pythonban implementálj egy döntési fa típusú regressziós modellt, amely a következő specifikációnak kell, hogy megfeleljen:

<ul>
<li>kezeljen numerikus bemeneti adatokat, akkor is ha vannak hiányzó értékek</li>
<li>legyen fit(X,y) függvénye, amely elvégzi a modell tanítását</li>
<li>legalább két mérték választható legyen vágási kritériumként (pl. mse)</li>
<li><s>legyen megadható a maximális mélység (aka max_depth)</s>, a minimum vágási elemszám (aka min_samples_split) és a minimum elemszám egy levélben (aka min_samples_leaf).</li>
<li>lehessen random seed-et megadni neki (aka random_state)</li>
<li>legyen predict(X) függvénye, amely adott X-re megjósolja a regressziós értéket</li>
<li>legyen egy print() függvénye, amely ábrázolja a felépített döntési fát </li>
 </ul>
