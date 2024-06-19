Uputa za korištenje

Za korištenje potrebno je uplodat sve datoteke na google drive te otvoriti bilježnice pomoću google colab-a.
Nakon što je bilježnica učitana treba namjestiti runtime na T4 GPU: 
	Runtime -> Change runtime type -> T4 GPU -> Save
 
Te zatim pokrenuti:
	Runtime -> Run all

Važno je imati datoteke Gene_annotations i Test_gene_annotation zato što model uzima podatke za treniranje i testiranje iz tih datoteka.
Dodavanje novih skupaova podataka za testiranje ili treniranje je moguće na slijedeći način:
  1. Potrebno je skinuti podatke o genomu preko NCBI web stranice. Kod preuzimanja podataka važno je da se preuzmu FASTA i GFF datoteke.
  2. Preuzetu zip datoteku zatim treba rasprakirati unutar datoteke Gene_annotations za treniranje ili unutar datoteke Test_gene_annotations za testiranje.

Datoteka upgraded_trained_model služi za učitavanje istreniranog modela kod testiranja.
