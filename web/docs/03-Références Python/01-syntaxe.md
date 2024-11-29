# Syntaxe Python

## Indentation

La base de la syntaxe en python est l'indentation.
Le nombre de tabulation ou d'espace


## Déclaration



```
   if  ($pid > 0) 
     { sleep 1 while !-e $FIFO; } 
   else 
     { 
      system("mknod", $FIFO, "p") == 0 
            or  die "$0: mknod failed"; 
      open(my $fh, ">", $FIFO); 
      sleep $SLEEP; 
      exit 0; 
     } 
```