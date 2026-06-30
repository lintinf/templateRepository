## Scopo di Questo Repository

Lo scopo di questo repository è:
- Standardizzare e comunicare le modalità di condivisione degli appunti, all'interno dei repository relativi agli insegnamenti del corso LINTINF dell'Università degli Studi di Parma (UniPr).
- Facilitare le studentesse e gli studenti della LINTINF nella condivisione degli appunti.

## Struttura del Repository

Root\
&#8202;├-Nome o Alias dello studente\
&hairsp; &hairsp;&hairsp; &hairsp;├-DeliveryNote.md\
&hairsp; &hairsp;&hairsp; &hairsp;├-License.md\
&hairsp; &hairsp;&hairsp; &hairsp;├-Appunti\
&hairsp; &hairsp;&hairsp; &hairsp;&hairsp; &hairsp;&hairsp; &hairsp;├- File dello studente.*

## Spiegazione della Struttura

Nella **Root**, ovvero nella posizione iniziale della repository, è presente una cartella intitolata **"Nome o alias di chi condivide gli appunti"**.  
Tale cartella andrà poi caricata all'interno della repository relativa all'insegnamento interessato.
Questa cartella, che prende il nome della persona o un alias, conterrà diversi file al suo interno:
- **DeliveryNote.md**  
  Il file **DeliveryNote.md** è un documento in formato Markdown che funge da "bolla d'accompagnamento" degli appunti. In esso sono riportate varie informazioni relative agli appunti. Vedremo, in una sezione dedicata, il motivo della presenza di questo file e la sua struttura.
- **Appunti**  
  Nella cartella **Appunti** andranno caricati i vostri appunti.

## Che Tipo di Appunti Posso Caricare? E in Che Formato?

Sebbene siano preferibili appunti redatti in formato digitale (Markdown, LaTeX, PDF non scannerizzati, ecc.), non vi sono vincoli particolari.  
È possibile caricare anche file PDF contenenti le pagine dei vostri appunti scannerizzati, poiché potrebbero rappresentare uno spunto utile per le studentesse e gli studenti futuri.  
**L'unico vincolo è l'utilizzo di formati leggibili da qualunque sistema operativo.**  
*"Sì, mi sto riferendo proprio a voi utenti Mac ;)"*

## DeliveryNote

Considerate questo file come se fosse una sorta di *"biglietto da visita"* dei vostri appunti.  
Il suo scopo principale è fornire informazioni rapide alle studentesse e agli studenti, senza che debbano aprire ogni singolo file.  
Potete variare la sua struttura in base alla tipologia degli appunti, ma è importante rispettare la sua forma base:

```md
Nome o Alias di chi condivide gli appunti: [Place Holder]  
Tipologia di Appunti: [Scritti in digitale / Scritti a mano e digitalizzati / Misti]  
// Se il corso è diviso in moduli  
Moduli Trattati:  
- Modulo 1  
- Modulo 2  
// Da qui in poi potete inserire qualunque informazione ritenuta necessaria.
```

Questo file non è obbligatorio, ma è fortemente consigliato per aiutare le studentesse e gli studenti a orientarsi.

## Licenza

Avrete notato la presenza del file **LICENSE.md**.  
Questo file contiene la licenza applicata ai vostri appunti.  
Data la natura di questo progetto, abbiamo deciso di utilizzare la licenza *Attribution-NonCommercial-ShareAlike 4.0 International* (CC BY-NC-SA 4.0).  
Trovate ulteriori informazioni sulla licenza al seguente link: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1).

La licenza serve a garantire che:
- Vengano rispettati i crediti relativi ai rispettivi autori;
- Non vengano utilizzati gli appunti a scopo commerciale.
