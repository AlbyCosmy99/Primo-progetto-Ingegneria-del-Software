# 🛠️ Primo Progetto – Ingegneria del Software

Repository contenente il **primo progetto del corso di Ingegneria del Software** (Università di Padova).  
Il progetto, della durata di **7 giorni**, è stato svolto come parte dell’esame del corso.  
L’esame complessivo (progetto + parte teorica) è stato **superato con valutazione 29/30** il **16/09/2021**. ✅

---

## 📌 Richiesta del progetto

- Supporre di lavorare in **Java Micro Edition (CLDC 1.1)**  
  👉 [Documentazione CLDC 1.1](https://docs.oracle.com/javame/config/cldc/ref-impl/cldc1.1/jsr139/index.html)

- Adattare una libreria originaria di **J2SE 1.4.2** che utilizza le interfacce:  
  - `List`  
  - `Collection`  
  - `Iterator`  
  - `ListIterator`  

- Sviluppare un **adapter per l’interfaccia List**, usando come *adaptee* la classe `Vector` di CLDC 1.1.  
- Il comportamento deve essere **compatibile con la documentazione di J2SE 1.4.2** (incluso `subList` e recursive sublisting).  
- Definizione locale delle interfacce:  
  - `HCollection`, `HList`, `HIterator`, `HListIterator`  
- Implementazione della classe `ListAdapter` nel package `myAdapter`, che implementa `HList` e `HCollection`.  
- Implementazione completa anche per gli **iteratori** (`HIterator`, `HListIterator`).  
- Obbligo di implementare **tutte le optional operations**.  

---

## ✅ Metodologia

- Utilizzo della **Test Driven Development (TDD)**  
- Implementazione di test suite con **JUnit**  
- Package `myTest` con classe `TestRunner` eseguibile da linea di comando  
- Documentazione test secondo i template:  
  - **SAFe** (test suite)  
  - **Homework** (test case)  
- Documentazione prodotta con **Javadoc** (+ eventuali PDF/HTML dedicati).  
- Separazione dei file in cartelle:  
  - `src/` → Codice sorgente  
  - `myTest/` → Test suite JUnit  
  - `doc/` → Documentazione  
  - `junit/` → Jar di JUnit (se versione diversa da quella a lezione)  

---

## 📂 Struttura del progetto

```
.
├── myAdapter/
│   ├── HCollection.java
│   ├── HList.java
│   ├── HIterator.java
│   ├── HListIterator.java
│   └── ListAdapter.java
├── myTest/
│   ├── ListAdapterTest.java
│   ├── VectorIteratorAdapterTest.java
│   ├── TestRunner.java
│   └── ...
├── doc/               # Documentazione Javadoc + SAFe/Homework test docs
├── junit/             # JUnit jar (se necessario)
└── README.md
```

---

## 🛠️ Tecnologie utilizzate

- **Java 2 Micro Edition (CLDC 1.1)**  
- **Java 2 Standard Edition 1.4.2 API** (per specifiche)  
- **JUnit** (testing framework)  
- **Javadoc** (documentazione)  

---


## 🎓 Contesto accademico

- Corso: **Ingegneria del Software** – Università di Padova  
- Data: **Settembre 2021**  
- Valutazione finale: **29/30**  
