# 📬 Email Digest Generator (Colab + Gemini)
Questo notebook automatizza la lettura di email da una casella Gmail, le invia a Gemini per generare un riassunto e inoltra il digest a un altro indirizzo.

[Apri in Colab](https://colab.research.google.com/github/Frydrichas/newsletter_digest/blob/main/newsletter_digest.ipynb)


## ✨ Funzionalità
- Connessione a Gmail via IMAP
- Filtro per mittente e soggetto
- Riassunto delle email tramite Google Gemini
- Invio del digest tramite SMTP

## ▶️ Esecuzione
- Apri il notebook in Google Colab
- Configura i secret con i tuoi dati (o mettili nel notebook)
- Esegui tutte le celle
- Riceverai un’email riassuntiva con i contenuti selezionati

## 📦 Requisiti
- Account Google con accesso IMAP attivo
- Etichetta o filtro per individuare le newsletter
- Password per app generata da Google
- Accesso a Gemini (Google AI Studio / API key)
