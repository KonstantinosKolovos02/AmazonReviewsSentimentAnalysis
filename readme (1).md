# Amazon Review Sentiment Analysis με Word2Vec, GloVe & BERT

## Περιγραφή
Το project αυτό υλοποιεί ανάλυση συναισθήματος (sentiment analysis) σε κριτικές προϊόντων της Amazon χρησιμοποιώντας **Word2Vec**, **GloVe** και **BERT embeddings** (freezed & fine-tuned), σε συνδυασμό με αλγορίθμους μηχανικής μάθησης και deep learning. Περιλαμβάνει προεπεξεργασία κειμένου, εκπαίδευση μοντέλου Word2Vec, μετατροπή κριτικών σε διανύσματα χαρακτηριστικών και αξιολόγηση ταξινομητή.

## Τεχνολογίες & Βιβλιοθήκες
- Python
- Jupyter Notebook
- NumPy
- pandas
- gensim (Word2Vec)
- pre-trained GloVe embeddings
- Hugging Face Transformers (BERT)
- scikit-learn

## Ροή Εργασίας
1. **Προεπεξεργασία Κειμένου**  
   Καθαρισμός κριτικών από θόρυβο (σύμβολα, αριθμούς, timestamps κ.λπ.) και μετατροπή σε tokens.

2. **Embeddings Κειμένου**  
   - Εκπαίδευση Word2Vec μοντέλου
   - Χρήση προεκπαιδευμένων GloVe embeddings
   - BERT embeddings σε *freezed* mode
   - BERT *fine-tuned* για sentiment analysis

3. **Αναπαράσταση Κριτικών**  
   Μετατροπή κάθε κριτικής σε διάνυσμα χαρακτηριστικών (μέσος όρος embeddings ή CLS token για BERT).

4. **Ταξινόμηση Συναισθήματος**  
   Εκπαίδευση μοντέλου μηχανικής μάθησης για πρόβλεψη θετικού/αρνητικού συναισθήματος.

5. **Αξιολόγηση & Σύγκριση Μοντέλων**  
   Μέτρηση απόδοσης με metrics όπως accuracy, precision, recall και F1-score.


## Στόχος Project
Στόχος είναι η σύγκριση διαφορετικών τεχνικών αναπαράστασης κειμένου (**Word2Vec, GloVe, BERT freezed, BERT fine-tuned**) ως προς την απόδοσή τους στο sentiment analysis πραγματικών δεδομένων.

Στόχος είναι η κατανόηση και εφαρμογή τεχνικών **NLP** και **distributed word representations** (Word2Vec) για την ανάλυση συναισθήματος πραγματικών δεδομένων κριτικών.

## Μελλοντικές Βελτιώσεις
- Χρήση πιο προχωρημένων embeddings (GloVe, FastText, BERT)
- Πειραματισμός με διαφορετικούς ταξινομητές
- Βελτιστοποίηση υπερπαραμέτρων

---
*Educational / Academic Project*

