# htmltest

* Generate X options for select tag
```
for ((i=1; i<=40000; i++))
do
  echo "<option value=\"$i\">$i</option>" 
done |pbcopy
```