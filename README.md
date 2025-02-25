This code builds an interactive webpage designed for musicians working with guitar and bass chords. In summary, it includes:

HTML & CSS: The basic structure of the page styled with a modern, relaxed look. It features a three-column layout for chord panels (for both guitar and bass) and an interactive fretboard (using a canvas element) to display chord diagrams.
Dynamic Content Generation: JavaScript is used to dynamically create lists of chord buttons. When a chord is selected, the interactive fretboard is updated to display the corresponding diagram.
Fretboard Display: Both dynamic (canvas) and static (SVG) elements are employed to render fretboards. In the SVG fretboards, horizontal and vertical lines are drawn with labels for musical notes (displayed in both English and Greek).
Sound Playback & Basic Notes: There are buttons that play the basic musical notes using the Web Audio API.
Live Pitch Detection: By accessing the microphone and using an auto-correlation algorithm, the code analyzes the incoming audio in real time and displays the detected note (in both English and Greek).
Chord Viewer Integration: An iframe is included to load external pages with additional chord information for users who want more details.
Scroll To Top: A button is provided for smooth scrolling back to the top of the page.


Αυτός ο κώδικας δημιουργεί μία διαδραστική ιστοσελίδα που απευθύνεται σε μουσικούς που ασχολούνται με τα ακόρδα κιθάρας και μπάσου. Συνοπτικά, περιλαμβάνει:

HTML & CSS: Ο βασικός σκελετός της σελίδας με ορισμένα χαλαρά, μοντέρνα στυλ. Περιλαμβάνει διάταξη σε τρεις στήλες για πίνακες ακόρδων (για κιθάρα και μπάσο) και μία διαδραστική ταστιέρα (canvas) για απεικόνιση ακόρδων.
Δυναμική Δημιουργία Περιεχομένου: Με JavaScript δημιουργούνται λίστες από κουμπιά για τα ακόρδα, και επιλέγοντας ένα ακόρδο ενημερώνεται η διαδραστική ταστιέρα ώστε να εμφανίζει το αντίστοιχο διάγραμμα.
Απεικόνιση Ταστιέρων: Χρησιμοποιούνται τόσο δυναμικά (canvas) όσο και στατικά (SVG) στοιχεία για την απεικόνιση των ταστιέρων. Στα SVG, σχεδιάζονται οριζόντιες και κάθετες γραμμές με ετικέτες για τις νότες (στα αγγλικά και στα ελληνικά).
Αναπαραγωγή Ήχου & Βασικές Νότες: Υπάρχουν κουμπιά που επιτρέπουν την αναπαραγωγή βασικών μουσικών νοτών χρησιμοποιώντας το Web Audio API.
Ζωντανός Εντοπισμός Νότας: Με χρήση του μικροφώνου και ενός αλγορίθμου αυτοσυσχέτισης (auto-correlation), ο κώδικας ανιχνεύει τη συχνότητα του ήχου σε πραγματικό χρόνο και εμφανίζει την αντίστοιχη νότα (και στα δύο γλωσσικά συστήματα).
Ενσωμάτωση Chord Viewer: Υπάρχει ένα iframe που φορτώνει εξωτερικές σελίδες με περισσότερα ακόρδα, για όσους θέλουν επιπλέον πληροφορίες.
Scroll To Top: Ένα κουμπί που επιτρέπει την ομαλή επιστροφή στην κορυφή της σελίδας.


https://nioz-zz.github.io/pablo/
