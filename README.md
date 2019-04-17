# JQUERY MASK GLOBAL 

## Objetivos do Script :

- Facilitar a utilidade em máscaras mais complexas, utilizando apenas um função.
- O arquivo jquery.mask.js está compactado com a função.
- O html possui alguns exemplos básicos, mas estão livres a ser alterados.

## Code:

```
Line 598. 

    $('input[data-mask]').each(function() {
            $(this).mask($(this).attr('data-mask'));
    });

```

