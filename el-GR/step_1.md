Τα μπλοκ μέσα σε ένα μπλοκ `εάν...τότε`{:class="block3control"} θα εκτελεστούν μόνο εάν η **συνθήκη** στην εξαγωνική είσοδο είναι **αληθής**.

```blocks3
if <> then
end
```

Υπάρχουν πολλά μπλοκ με σχήμα εξαγώνου για **συνθήκες** στο Scratch, συμπεριλαμβανομένων μπλοκ στα μενού `Αισθητήρες`{:class="block3sensing"} και `Τελεστές`{:class="block3operators"}.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Αν θέλεις να τρέχουν διαφορετικά μπλοκ εντολών όταν η **συνθήκη ** είναι **ψευδής**, χρησιμοποίησε ένα μπλοκ `εάν... τότε... αλλιώς`{:class="block3control"}:

```blocks3
if <(money) > [9]> then
hide
change [money v] by [-10]
else
say [You don't have enough] for [2] seconds
end
```

Μπορείς να δημιουργήσεις πιο σύνθετους ελέγχους κάνοντας «ενθέσεις (nesting)» με μπλοκ `εάν...τότε`{:class="block3control"} και `εάν...τότε...αλλιώς`{:class="block3control"} το ένα μέσα στο άλλο.
