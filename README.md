# DecisionTree
Adatbányászati technikák HF
Pythonban implementálj egy döntési fa típusú regressziós modellt, amely a következő specifikációnak kell, hogy megfeleljen:

<ul>
<li><s>kezeljen numerikus bemeneti adatokat, akkor is ha vannak hiányzó értékek</s>✅</li>
<li><s>legyen fit(X,y) függvénye, amely elvégzi a modell tanítását</s>✅</li>
<li><s>legalább két mérték választható legyen vágási kritériumként (pl. mse)</s>✅</li>
<li><s>legyen megadható a maximális mélység (aka max_depth) ✅, a minimum vágási elemszám (aka min_samples_split)✅ és a minimum elemszám egy levélben (aka min_samples_leaf)✅.</s></li>
<li><s>lehessen random seed-et megadni neki (aka random_state)</s>✅</li>
<li><s>legyen predict(X) függvénye, amely adott X-re megjósolja a regressziós értéket</s>✅</li>
<li><s>legyen egy print() függvénye, amely ábrázolja a felépített döntési fát</s>✅</li>
 </ul>
