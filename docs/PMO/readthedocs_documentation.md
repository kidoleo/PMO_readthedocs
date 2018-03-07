# readthedocs.org

### Scopo :
  Visualizzazione e navigazione della dcoumentazione generata dai gruppi attraverso pagine web
  
### Utilizzo :
  + Creare un account sul sito [read the docs](http://google.it)
  
  [LOGIN IMAGE](https://github.com/kidoleo/PMO_readthedocs/blob/master/docs/PMO/login.PNG)
  
  + Creare o entrare sulla propria repository GitHub ex : [PMO_readthedocs](https://github.com/kidoleo/PMO_readthedocs)
  + Entrare in settings (nella repository), WebHooks aggiungere il webhooks e copiare il Payload URL
  
  [SETTINGS](https://github.com/kidoleo/PMO_readthedocs/blob/master/docs/PMO/settings.PNG)
  
    + Copiare il Payload URL da readthedocs in Amministrazione-->Integretion-->Add Integretion
    
  [PAYLOAD](https://github.com/kidoleo/PMO_readthedocs/blob/master/docs/PMO/payload.PNG)

### NB :
  + Nella repository github sarà necessario avere una cartella docs ex :[PMO_docs](https://github.com/kidoleo/PMO_readthedocs/new/master/docs/)
  + Creare un index.md all' interno di docs con le informazioni principali che verranno mostrate in home


#### Problemi :
  + il file creato all' interno di docs per la home deve essere index.md, con README.md il servizio non funziona
  + tutte le documentazioni devono essere necessariamente messe in una directory denominata docs
