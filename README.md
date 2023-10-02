#Check Telefono
- Il primo passo di questo esercizio è scaricare il file da classroom e rinominarlo correttamente\
- Successivamente si procede aprendo la cartella su Visual Studio Code e iniziare a scrivere il codice\

- Per prima cosa dobbiamo scorrere ogni elemento dentro al vettore usando un foreach, in questo modo:\

###
    foreach (var num in vettore)
    {
        
    }
   
###

- Dentro al vettore richiamiamo il metodo "IsnumeroTelefonoItaliano" e verifichiamo che num sia valido\
###
    if(IsnumeroTelefonoItaliano(num))
    {
        return true;
    }
   
###


- Il prossimo passo è quello di creare un metodo che verifica le caratteristiche richieste del numero di telefono\
- Per verificare la lunghezza della stringa e i prefissi, bisogna usare un if e se ritorna vero signifa che è valido il prefisso\
###
    if(num.Lenght == 13 && (num.StartsWith("+39"))
    {
        return true;
    }
   
###


- Ora si procede crando gli altri due metodi per verificare i numeri di telefono con le caratteristiche non ancora verificate\
###
    if(num.Lenght == 14 && (num.StartsWith("0039"))
    {
        return true;
    }
   
###
###
    if(num.Lenght == 10 && (num.StartsWith("3"))
    {
        return true;
    }
  
###
- se la stringa non soddisfa le condizioni imposte il programma ritornerà "false"; ciò vorrà dire che il numero non sarà valido.













