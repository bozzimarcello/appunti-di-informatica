# XAML e Code Behind

Il codice di una applicazione WPF viene scritto con due linguaggi C# e XAML.

## C#

Il linguaggio C# viene usato per implementare gli algoritmi che rappresentano le funzioni del programma. I File che contengono il codice C# terminano con l'estensione .cs e vengono chiamati "Code Behind" nella documentazione ufficiale. Questo nome deriva dal fatto che il codice C# sta "dietro" il codice che descrive l'interfaccia utente, implementandone il comportamento.

## XAML

Il linguaggio XAML descrive l'interfaccia grafica in termini di finestre, contenitori e controlli. Si tratta di un linguaggio descrittivo derivato dal HTML, quindi ogni elemento è racchiuso nei simboli < e >. Per descrivere le caratteristiche di un elemento si usano gli attributi espressi tramite un nome ed un valore.
Per esempio un bottone identificato dal nome BtnSalva, che mostra una etichetta "salva" è definito da:

``` html
<Button x:Name="BtnSalva" Content="Salva" />
```

## Gestori degli eventi

I gestori degli eventi sono metodi collegati ai controlli dell'interfaccia con una porzione di codice C# che implementa una funzionalità.
Per inserire un nuovo gestore su un controllo usando Visual Studio si può usare l'azione di doppio-clic, verrà creato un metodo nel code behind che si chiamerà con lo stesso nome del controllo seguito dall'evento che verrà gestito. E' possibile modificare questi collegamenti tra controlli e gestori dall'interfaccia usando la finestra delle Proprietà di Visual Studio e selezionando il filtro con l'icona del fulmine. 
