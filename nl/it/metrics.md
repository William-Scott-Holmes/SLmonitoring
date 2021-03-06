---

copyright:
  years: 2017, 2018
lastupdated: "2018-03-29"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Metriche raccolte (Beta)
Questo argomento tratta delle metriche raccolte per questa applicazione di monitoraggio beta sui server virtuali e bare metal.
{:shortdesc}

Questo argomento tratta di tutte le metriche disponibili tramite le query Grafana. Per ulteriori informazioni, consulta [Creazione di una query di monitoraggio avanzata (Beta)](advanced_query.html). I grafici sono disponibili nell'interfaccia utente solo per le seguenti metriche:
* CPU utilization
* Memory Usage
* Disk Read and Write (bytes/seconds and IO per second)
* Disk Read and Write latency
* Public network throughput (in/out)
* Private network throughput (in/out)
* Public network packets (in/out) (solo Baremetal)
* Private network packets (in/out) (solo Baremetal)
* Public network errors (in/out) (solo Baremetal)
* Private network errors (in/out) (solo Baremetal)
* Temperature (solo Baremetal)


## Metriche CPU
  Le metriche CPU misurano la percentuale media di tempo per cui una CPU sta eseguendo delle istruzioni durante un dato periodo di tempo. La percentuale di inattività media è inattiva sull'aggiunta di utente, nice, sistema, attesa IO, interrupt hardware e interrupt software.

## Metriche di memoria
* Bytes used/Average used: la quantità di memoria utilizzata in un dato momento, disponibile sia in byte sia come percentuale del totale.
* Swap Bytes used/Average used: la percentuale di memoria di swap utilizzata durante un dato periodo. Questa metrica è un'indicazione della frequenza con cui è necessario richiamare i dati che non sono in memoria. Questa metrica è disponibile solo sui dispositivi bare metal).
  
## Metriche di disco

* Disk Total: la quantità totale di byte disponibili per il disco. Questa metrica deve essere costante.
* Disk Used (Bytes): la quantità di byte utilizzata dal disco in un dato momento.
* Disk Used (Percentage): la percentuale della quantità totale di byte utilizzata rispetto alla quantità totale di byte disponibili per il disco.
* Disk Read/Write (bytes per sec): la quantità media di dati letti/scritti dal/sul disco in un dato periodo.
* Disk Read/Write (operations per sec): operazioni di lettura/scrittura al secondo
* Disk Read/Write (latency in ms per operation): latenza in millisecondi per lettura/scrittura

## Metriche di rete

 * Network Public/Private In: numero di byte inviati dalla rete pubblica/privata
* Network Public/Private Out: numero di byte ricevuti dalla rete pubblica/privata
* Network Public/Private Packets In: numero di pacchetti ricevuti dall'interfaccia di rete nella rete pubblica/privata. Questa metrica è disponibile solo sui dispositivi bare metal).
* Network Public/Private Packets Out: numero di pacchetti inviati dall'interfaccia di rete sulla rete pubblica/privata. Questa metrica è disponibile solo sui dispositivi bare metal).

## Metriche di temperatura
* Average temperature of the system measured in degrees Celsius. Questa metrica è disponibile solo su alcuni dispositivi bare metal.



