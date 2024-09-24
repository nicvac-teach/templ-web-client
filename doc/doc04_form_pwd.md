## Input di una password:
Una password non deve essere mostrata mentre viene digitata.<br/>
Si può utilizzare la seguente sintassi HTML per creare un input di tipo password:

```html
<label>Password</label>
<input class="w3-input w3-border" type="password" name="pwd">
```
Il tag **label** viene utilizzato per descrivere l'input. Il tag **input** definisce la casella di testo in cui poter inserire la password.<br/>
L'attributo _type="password"_ stabilisce che l'input inserito è di tipo password e che quindi non sarà visibile durante la digitazione. <br/>
L'attributo _name="pwd"_ definisce la variabile _pwd_ che potrà essere usata dal server quando riceverà i dati inseriti.

## Esercizio 04 - Aggiungere nel form l'input password

Nel file **index.html**, all'interno del form già predisposto in **Esercizio 03**, aggiungere:
- un input per la password di accesso all'evento

Il risultato atteso è il seguente:
![esempio form](img05_formPwd01.png)

<details style="border: 1px solid #007bff; border-radius: 5px; padding: 10px; background-color: #f0f0f0;">
  <summary>Solo dopo aver svolto l'esercizio, apri qui per vedere la soluzione</summary>

```html
    <div class="w3-card-4">
      <div class="w3-container w3-green">
        <h2>Registrazione evento</h2>
      </div>
      <form class="w3-container">
        <p>
        <input class="w3-input" type="text" name="nome">
        <label>Nome</label></p>
        <p>
        <input class="w3-input" type="text" name="cognome">
        <label>Cognome</label></p>
        <p>
        <input class="w3-input" type="number" name="eta">
        <label>Età</label></p>
        <p>
        <input class="w3-input" type="date" name="dataEvento">
        <label>Data evento</label></p>
        <p>
        <label>Password Evento</label>
        <input class="w3-input w3-border" type="password" name="pwd">
      </form>
    </div>

```
</details>

<br/>

[Clicca qui per la prossima lezione](./doc05_form_checkbox.md)
