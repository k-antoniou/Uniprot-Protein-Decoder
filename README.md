# Uniprot-Protein-Decoder

Το πρόγραμμα αυτό θα δέχεται ως είσοδο ένα αρχείο με πολλαπλές εγγραφές από τη Uniprot και θα δίνει σαν έξοδο ένα αρχείο μορφής .txt που θα έχει
τις ακόλουθες πληροφορίες για κάθε πρωτεΐνη: 
1. Στην πρώτη γραμμή θα εμφανίζει το σύμβολο > και στη συνέχεια το ID, το AC (μόνο το ισχύον) και το μήκος της πρωτεΐνης σε αμινοξικά κατάλοιπα και ενδιάμεσα θα τυπώνεται ο χαρακτήρας «|».
2. Στην δεύτερη γραμμή θα τυπώνεται η αμινοξική ακολουθία της πρωτεΐνης χωρίς κενά.
3. Στην τρίτη γραμμή θα εμφανίζεται η θέση των διαμεμβρανικών τμημάτων της πρωτεΐνης σε μία συμβολοσειρά ίδιου μήκους με την αμινοξική ακολουθία όπου οι θέσεις των διαμεμβρανικών θα 
συμβολίζονται με «Μ» και όλες οι υπόλοιπες με «-».
4. Στην τέταρτη γραμμή θα εμφανίζονται τα σύμβολα «//» που υποδεικνύουν το τέλος της εγγραφής στη UniProt.

   