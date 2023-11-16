# Οδηγίες

### Προαπαιτούμενα
Node.js <br>
Ide or editor of your choice <br>
Git <br>

### Εγκατάσταση
Δημιουργήστε ένα φάκελο, μέσα στον οποίο θα γίνει η εγκατάσταση, για παράδειγμα

```
C:/project1
```
Χρησιμοποιήστε τη γραμμή εντολών με δικαιώματα διαχειριστή για να εκτελέσετε τις ακόλουθες εντολές. <br> Παρακαλώ προσαρμόστε ανάλογα με το φάκελο που επιλέξατε στο προηγούμενο βήμα.
```
cd /project1
git init
git pull https://github.com/stranger997/master_react_1.git
npm install
npm start
``` 
### Για αλλαγή branch
Με δημιουργία νέου mbranch
```
git checkout -b "your_branch_here"
```
Σε υπάρχων branch
```
git checkout "your_branch_here"
```
Έλεγχος των αρχείων που έχουν προστεθεί στο τοπικό git-repo μετά το τελευταίο commit (αν είναι κόκκινα, έχουν δημιουργηθεί αλλά δεν έχουν τροστεθεί στο τοπικό git-repo)
```
git status
```
### Πρόσθεση νεοδημιουργηθέντων αρχείων στο τοπικό git-repo
```
git add .
```
### Προετοιμασία πακέτου για προσθήκη σε απομακρυσμένο repo github
```
git commit -m "your_message_here"
```
### Αποστολή commit στο github την πρώτη φορά
```
git push --set-upstream https://github.com/stranger997/master_react_1.git master
```
### Τις επόμενες
```
git push
```


