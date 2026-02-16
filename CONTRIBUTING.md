# 🚀 Come contribuire a Cybersecurity Acronyms

Innanzitutto, grazie per l'interesse! Contribuire a questo progetto è un ottimo modo per imparare e aiutare la community.

### 📝 Aggiungere o Modificare Acronimi
Il cuore dell'app è il file `acronyms.json`. Per aggiungere un nuovo acronimo:

1. **Fai un Fork** del repository.
2. Crea un **nuovo branch** per la tua modifica (`git checkout -b feature/nuovo-acronimo`).
3. Vai nella cartella (o root) dove si trova il file `acronyms.json`.
4. Aggiungi il tuo acronimo seguendo questa struttura:
    ```json
    {
      "acronym": "XYZ",
      "definition": "Extended Yellow Zone",
      "category": "Networking",
      "description": "Descrizione del concetto.\nUsa '\\n' per andare a capo nella descrizione."
    }
    ```
5. **Verifica il JSON**: Assicurati di non aver dimenticato virgole o virgolette.
6. Effettua il **Commit** e il **Push** delle modifiche.
7. Apri una **Pull Request** spiegando brevemente quali termini hai aggiunto.

💡 **Suggerimenti per le descrizioni**
- Sii conciso.
- Se un acronimo è correlato ad un altro già presente (es. AES e 3DES), segnalalo nella descrizione.
- Usa un linguaggio tecnico ma accessibile.

🐛 **Segnalazione Bug**
Se trovi un errore nel codice o una definizione errata, apri una **Issue** descrivendo il problema.

Grazie per il tuo supporto!