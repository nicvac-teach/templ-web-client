# Principali elementi utilizzabili all'interno di un form.

![esempio form](./img03_form01.png)

Vediamo i principali elementi utilizzabili all'interno di un form.

## Input di testo:
Gli input di testo sono utilizzati per consentire all'utente di inserire dati di testo alfanumerici. Si possono utilizzare per richiedere nome, cognome, indirizzo email e altro ancora.<br/>
Per esempio, come visto nell'esempio precedente si può utilizzare la seguente sintassi HTML per creare un input di testo con w3.css:

```html
<label>Cognome</label>
<input class="w3-input w3-border" type="text" name="cognome">
```
Il tag **label** viene utilizzato per descrivere l'input di testo. Il tag **input** definisce la casella di testo in cui poter scrivere.<br/>
L'attributo _type="text"_ stabilisce che l'input inserito è di tipo stringa. <br/>
L'attributo _name="cognome"_ definisce la variabile _cognome_ che potrà essere usata dal server quando riceverà i dati inseriti.

## Input numerico:
Gli input numerici sono simili a quelli di testo, ma consentono di inserire solo numeri. Possono essere utilizzati per richiedere l'età, il numero di telefono o altre informazioni numeriche. Un esempio di input numerico è il seguente:
```html
<label>Età</label>
<input class="w3-input" type="number" name="eta">
```
## Input di una data
Gli input per la data sono un altro tipo di input che può essere utilizzato nei form. Questi elementi consentono all'utente di selezionare una data tramite un calendario interattivo. Gli input per la data possono essere utilizzati per richiedere la data di nascita o di scadenza di un documento. Il seguente codice HTML può essere utilizzato per creare un input per la data con w3.css:

```html
<label>Data di nascita</label>
<input class="w3-input" type="date" name="dataNascita">
```
ottenendo il seguente risultato.
![esempio form](./img04_formData01.png)

<br/>

## Esercizio 03 - Aggiungere nel form, l'input di testo, numerico e data

Nel file **index.html**, all'interno del form già predisposto in **Esercizio 01**, aggiungere:
- un input di testo per inserire il nome
- un input di testo per inserire il cognome
- un input numerico per inserire l'età
- un input numerico per inserire la data dell'evento

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
      </form>
    </div>

```
</details>
<br/>




[Clicca qui per la prossima lezione](./doc04_form_pwd.md)

