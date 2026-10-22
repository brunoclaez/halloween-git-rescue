Acció 3.11: Enregistrem l'estat defectuós a l'historial
```bash
git commit -m "feat: unhandled-spectral-exception"
```
Captura 18:
![alt text](img/image-18.png)
Acció 3.12:Executem aquesta comanda per veure la diferencia entre l'estat anterior infectat i l'actual estat segur
```bash
git diff HEAD~1 HEAD
```
Captura 19:
![alt text](img/image-19.png)
Acció 3.13:fem un git reset per purificar l'historial (primer hem de guardat tots els canvis anteriors per no perdre'ls)
```bash
git reset --hard HEAD~1
```
Captura 20:
![alt text](img/image-20.png)
Acció 3.14: Realitzem aquesta comanda: "git log --oneline --graph --all", per poder veure de manera gràfica la topologia del repositori
```bash
git log --oneline --graph --all
```
Totes les captures que hi han a continuació són de com es veu de manera hgràfica tota la topologia del repositori:
Captura 21:
![alt text](img/image-21.png)
Captura 22:
![alt text](img/image-22.png)
Captura 23:
![alt text](img/image-23.png)
Captura 24:
![alt text](img/image-24.png)
Captura 25:
![alt text](img/image-25.png)
Captura 26:
![alt text](img/image-26.png)
Captura 27:
![alt text](img/image-27.png)
Captura 28:
![alt text](img/image-28.png)