[laboratorul1.md](https://github.com/user-attachments/files/34367857/laboratorul1.md)
# Laborator 1: Definirea produsului inițial

## 1. Cercetarea produselor

### Întrebarea de cercetare

**How do existing products help a User follow market information, and which parts belong in this Dashboard's first version?**

Pentru cercetarea inițială au fost analizate două produse existente: **Yahoo Finance** și **Interactive Brokers (IBKR)**. Scopul cercetării este de a identifica funcțiile care îi ajută pe utilizatori să urmărească investițiile și informațiile de pe piață și de a selecta funcțiile potrivite pentru prima versiune a unui Tablou de Bord Personal pentru Investiții de dimensiuni reduse.

### Produse analizate

| Produs                         | Utilizator probabil și obiectiv                                                                                          | Model reutilizabil                                                                          |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------- |
//Yahoo Finance reprezintă un produs orientat spre informații și urmărirea investițiilor, iar Interactive Brokers reprezintă un produs orientat spre portofoliu și trading.
| **Yahoo Finance**              | Investitor individual care dorește să urmărească acțiuni, portofolii și evoluția investițiilor într-un singur loc.       | Watchlist, portofoliu personal, afișarea prețului, variației și performanței investițiilor. |
| **Interactive Brokers (IBKR)** | Investitor care dorește să urmărească pozițiile, valoarea portofoliului, câștigurile/pierderile și activitatea contului. | Dashboard cu sumarul portofoliului, poziții, performanță, câștiguri/pierderi și activitate. |

### Observații din cercetare

**Yahoo Finance** permite utilizatorilor să creeze watchlist-uri și portofolii și să urmărească investițiile de interes. Portofoliile pot afișa informații despre dețineri, performanță și alte valori relevante.

**Interactive Brokers** oferă o imagine de ansamblu asupra portofoliului, inclusiv poziții curente, valoarea de piață, profitul/pierderea realizată și nerealizată și performanța istorică.

Din aceste produse pot fi preluate pentru prima versiune următoarele idei:

* adăugarea investițiilor urmărite;
* afișarea prețului curent;
* afișarea variației prețului;
* organizarea investițiilor într-un portofoliu;
* afișarea valorii totale a portofoliului;
* afișarea profitului sau pierderii;
* posibilitatea de a vedea informațiile principale într-un singur tablou de bord.

### Funcții care NU vor fi incluse în prima versiune

Pentru a păstra produsul simplu și potrivit pentru investiții de dimensiuni reduse, prima versiune nu va include:

* executarea efectivă a ordinelor de cumpărare sau vânzare;
* conectarea directă la conturi bancare sau brokeri;
* analiză tehnică avansată;
* indicatori tehnici complecși;
* rapoarte fiscale;
* instrumente complexe de gestionare a riscului;
* recomandări automate de cumpărare sau vânzare.

Prin urmare, produsul va avea rolul de **instrument personal de urmărire și organizare a investițiilor**, nu de platformă de tranzacționare.

---

## 2. Părțile interesate și actorii

### Părți interesate

| Parte interesată                | Interes în produs                                                             |
| ------------------------------- | ----------------------------------------------------------------------------- |
| **Utilizatorul / Investitorul** | Dorește să urmărească investițiile și evoluția portofoliului.                 |
| **Administratorul produsului**  | Se ocupă de funcționarea și întreținerea produsului.                          |
| **Furnizorul de date de piață** | Furnizează informații despre prețurile și evoluția instrumentelor financiare. |

### Actori

**Actor principal:**

* **Investitorul** – utilizează tabloul de bord pentru a adăuga investiții, a urmări prețurile și a verifica performanța portofoliului.

**Actori externi:**

* **Furnizorul de date de piață** – oferă datele necesare pentru afișarea informațiilor despre instrumentele urmărite.

---

## 3. Promisiunea produsului și domeniul de aplicare

### Promisiunea produsului

**Tabloul de Bord Personal pentru Investiții** îi permite unui investitor individual să își urmărească într-un singur loc investițiile și principalele informații despre evoluția acestora.

Produsul are ca scop simplificarea urmăririi investițiilor printr-o interfață clară, în care utilizatorul poate vedea rapid:

* ce investiții urmărește;
* prețul curent;
* variația prețului;
* valoarea portofoliului;
* profitul sau pierderea;
* evoluția generală a portofoliului.

### Obiective

1. Centralizarea investițiilor într-un singur loc.
2. Afișarea rapidă a principalelor informații despre investiții.
3. Urmărirea evoluției portofoliului.
4. Păstrarea unei structuri simple și ușor de înțeles.
5. Reducerea timpului necesar pentru verificarea investițiilor.

### Non-obiective

Prima versiune a produsului nu urmărește:

1. efectuarea tranzacțiilor;
2. oferirea de recomandări financiare;
3. gestionarea conturilor bancare;
4. realizarea unei analize tehnice complexe;
5. gestionarea automată a portofoliului;
6. calcularea și gestionarea obligațiilor fiscale.

### Domeniul de aplicare

Sistemul va permite utilizatorului să:

* adauge o investiție;
* elimine o investiție;
* vizualizeze lista investițiilor;
* urmărească prețurile;
* vizualizeze modificarea prețurilor;
* vizualizeze valoarea portofoliului;
* urmărească profitul sau pierderea;
* organizeze investițiile într-un portofoliu personal.

---

## 4. Cerințe funcționale

### User Story 1 – Adăugarea unei investiții

**În calitate de investitor, vreau să pot adăuga o investiție în tabloul de bord pentru a o putea urmări.**

**Definition of Done:**

* utilizatorul poate introduce simbolul/ticker-ul investiției;
* investiția este adăugată în lista personală;
* investiția apare în tabloul de bord;
* sunt afișate informațiile principale despre aceasta.

### User Story 2 – Vizualizarea investițiilor

**În calitate de investitor, vreau să văd toate investițiile mele într-o singură listă pentru a putea verifica rapid portofoliul.**

**Definition of Done:**

* tabloul de bord afișează lista investițiilor;
* fiecare investiție are identificator și nume;
* este afișat prețul curent;
* este afișată variația prețului.

### User Story 3 – Vizualizarea performanței

**În calitate de investitor, vreau să văd evoluția investițiilor pentru a înțelege dacă valoarea portofoliului meu crește sau scade.**

**Definition of Done:**

* este afișată valoarea investițiilor;
* este afișată variația valorii;
* este afișat profitul sau pierderea;
* valorile sunt prezentate într-un format ușor de înțeles.

### User Story 4 – Organizarea portofoliului

**În calitate de investitor, vreau să îmi organizez investițiile într-un portofoliu pentru a le putea urmări mai ușor.**

**Definition of Done:**

* utilizatorul poate avea un portofoliu personal;
* investițiile pot fi adăugate în portofoliu;
* investițiile pot fi eliminate;
* valoarea totală a portofoliului este afișată.

### User Story 5 – Eliminarea unei investiții

**În calitate de investitor, vreau să pot elimina o investiție pentru a păstra lista actualizată.**

**Definition of Done:**

* utilizatorul poate selecta o investiție;
* utilizatorul poate elimina investiția;
* investiția nu mai apare în lista principală;
* valoarea portofoliului este actualizată.

---

## 5. Vizualizare contextuală a sistemului C4

### Sistemul

**Tabloul de Bord Personal pentru Investiții**

Sistemul este utilizat de un investitor individual pentru urmărirea investițiilor și a portofoliului personal.

### Contextul sistemului

```text
                    +----------------------+
                    |      Investitor      |
                    |       (User)         |
                    +----------+-----------+
                               |
                               | urmărește investiții
                               | gestionează portofoliu
                               v
              +--------------------------------------+
              |                                      |
              |   Tablou de Bord Personal pentru     |
              |            Investiții                |
              |                                      |
              +------------------+-------------------+
                                 |
                                 | primește date despre
                                 | instrumente financiare
                                 v
                    +----------------------------+
                    | Furnizor de date de piață  |
                    |                            |
                    +----------------------------+
```

### Descrierea relațiilor

**Investitorul → Tabloul de Bord Personal**

Investitorul utilizează sistemul pentru a adăuga, elimina și urmări investițiile și pentru a vizualiza performanța portofoliului.

**Tabloul de Bord Personal → Furnizorul de date de piață**

Sistemul utilizează date de piață pentru a afișa informații precum prețul și variația instrumentelor urmărite.

**Furnizorul de date de piață → Tabloul de Bord Personal**

Furnizorul transmite informațiile necesare pentru actualizarea datelor afișate utilizatorului.

### Limita sistemului

În interiorul limitei sistemului se află:

* gestionarea listei de investiții;
* gestionarea portofoliului personal;
* afișarea prețurilor;
* afișarea variațiilor;
* calcularea și afișarea valorii portofoliului;
* afișarea profitului/pierderii.

În afara limitei sistemului se află:

* executarea ordinelor de tranzacționare;
* gestionarea conturilor bancare;
* furnizarea de recomandări financiare;
* analiza tehnică avansată;
* gestionarea fiscală.
