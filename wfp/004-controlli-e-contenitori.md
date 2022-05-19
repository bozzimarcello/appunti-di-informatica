# Controlli e contenitori

## Contenitori
Sono necessari per gestire il posizionamento dei controlli sullo schermo.
I contenitori incontrati fin'ora sono:
- Window (finestra), contenitore principale di tutti i controlli, possiamo configurarlo attraverso le proprietà seguenti: Title, Height, Width, Resize
- Grid, consente il posizionamento basandosi su coordinate che possono essere modificate con il trascinamento del mouse ed il drag & drop, volendo si può definire una sorta di griglia di allineamento e posizionare gli elementi nelle celle così ottenuto indicando riga e colonna
- StackPanel, consente di elencare i controlli che contiene in senso verticale partendo dall'alto oppure in senso orizzontale partendo dalla sinistra senza dover indicare le coordinate o le dimensioni del controllo

# Controlli
Sono il principale sistema di interazione con l'utente. Sono elencati nel pannello di Visual Studio chiamato "Casella degli strumenti", ma possono essere specificati anche nel codice XAML.
I controlli incontrati fin'ora sono:
- Label, serve per visualizzare un testo (OUTPUT)
- TextBox, serve per acquisire un testo dall'utente (INPUT)
- Button, serve per avviare un'azione implementata nel code-behind
- ListBox, serve a visualizzare una lista (OUTPUT), NB per inserire un nuovo elemento da codice si utilizza NomeLista.Items.Add("testo")
- ComboBox, serve a mostrare una casella di testo combinata con un elenco di valori predefiniti (INPUT/OUTPUT)
