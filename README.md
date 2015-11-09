# frets
Playin' a bit with guitar notes.

I use it in Python REPL, just like:
  > from frets import frets
  > f = frets(tuning=('E', 'A', 'D', 'G'),      # sets tuning of your guitar, mine is EADG bass guitar
              frets_count=24)                   # sets frets count
  > f.show_me_plz(seek_note='A^')               # shows all 'A^' note on fretboard (A and A^^ too)
  > f.show_me_plz(seek_string='A9')             # shows all frets that have the same note as 'A9' (also octave higher and lower)
  
'^' next to note means octave-higher note than note in initial tuning, '^^' means two octaves
